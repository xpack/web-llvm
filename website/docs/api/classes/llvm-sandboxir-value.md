---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/value
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Value` Class Reference

<p>A SandboxIR <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> has users. This is the base class. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::Value { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">llvm/SandboxIR/Value.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument">Argument</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument">Argument</a> of a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">sandboxir::Function</a>. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/user">User</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user">sandboxir::User</a> has operands. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee179151f966c4d3e6b79b13029d5ed">use_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/sandboxir/useruseiterator">UserUseIterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f4300fa0172b1508fc6d82702211dbd">const_use_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/sandboxir/useruseiterator">UserUseIterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00350c096bb66a07957db161bfad7a07">user_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/mapped-iterator">mapped_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/useruseiterator">sandboxir::UserUseIterator</a>, <a href="/web-llvm/docs/api/structs/llvm/sandboxir/value/usetouser">UseToUser</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac68108ddca4c6ef5c7b5d9c186f156">const_user_iterator</a> = <a href="#a00350c096bb66a07957db161bfad7a07">user_iterator</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ClassID : unsigned { <a href="#afa2029c46b6caf94a7d05ceb0dbcefe9">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38c437d9dcaefebe4efaf0edf00c45de">User</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b479862be57f4448b155a225b5972ac">Use</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a51bd9683e1167d25e2b645659df16e">VAArgInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3539d881344c8843a26bb506f5d0a671">FreezeInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b6a6ca6e4942ee198cdb58963959f0">FenceInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a105433331bc5e110865accd9b63da4ff">SelectInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a369dad8734d5d892a3ecf2870aef5e59">ExtractElementInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0214f7aa1d5031949fd91849f6084b6d">InsertElementInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d2fb6321caaf9c477057c323f74deb3">ShuffleVectorInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ffbe75c00da4ace042051200436174b">ExtractValueInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60fb03fae5fbc7e35f7a6a25c66e7145">InsertValueInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b5b44e66bd1a6ff5091c3e501ee264">BranchInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a955c4f7e0f02efa92ec3b6a0efb28aea">LoadInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c970b286be2bf7b3e2de4cc81a9ff6">StoreInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507ff1515eddab6aade1f9c639d45d32">ReturnInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab98413af141c094f142c9dc597e88e4a">CallBase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af189421b2d4e2e4c985045b84eee2dd3">CallInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ae546a926945494684eeed4ccb13694">InvokeInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb3940474561746eb391fa09835d2e7d">CallBrInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e77f69120edadc2d8723bbb05b270e">LandingPadInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acef2573abe929fbab47661ee76397504">FuncletPadInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86896a55c60df500e45247ae6a90c67c">CatchPadInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac85ed97cd7c97f1a960bca1d12ce770e">CleanupPadInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0358e90e75b75e08d5e9bc2fe43dedb2">CatchReturnInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3a17a4b38a74d8a6f80a1746482a359">GetElementPtrInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ae74d098b741f3ccbf4b7b898537adf">ResumeInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79bf85ac1b69351f041029eaff17702a">CatchSwitchInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7eb5a5b89231219e78ea9678f678186">CleanupReturnInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51642bf4a74518f4e827380a81b0310d">SwitchInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b643be70069658c68fb3d047771eb86">UnaryOperator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79da82c05d91d20c52e064937b35ef2e">BinaryOperator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9645e4372d7022efd24acd311a133178">AtomicRMWInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad35c4527c63aa5a36b64f6f3d40bb21e">AtomicCmpXchgInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae866dc3375e9ba50489c2b3d9cce6330">AllocaInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a127de2d3ee894412c0c7916f6f954491">CastInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6abe966290db4687216fd43f34316dd">PHINode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f62606ea33ba15b80c5b799c9a0ca1">UnreachableInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78d68ae66e32955119e78a75d98f855">CatchSwitchAddHandler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491288b9b4b16c83d513619f00fdcc6c">CmpInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab25d2664c586d20df4d7a31d62f305b9">ConstantArray</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1696f5f9994bd1a179b4c2869d5d90ea">ConstantStruct</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea06d5c01c72b853450109ac8cd4e2af">ConstantAggregateZero</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583b196fc6b358d576dd8e26820521b9">ConstantPointerNull</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af71c3b3f23690ee6a15b4227d496cfc3">UndefValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d548fda8ab959b3433900f43d619717">PoisonValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf5ebc4fa3006b5e52a0e6d02672a09e">BlockAddress</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9afdd98ee0b7ab43bc76deb4180ea986">GlobalValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc864586410a7d1e3791c238b1506ba8">DSOLocalEquivalent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac177bc079fe0a6e9b3d3115702db3bc3">GlobalObject</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd70c9300632f0382cb21a8aba6b52d7">GlobalIFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7039b9bbd22fbf967673646ae083665">GlobalVariable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a766f60740d82f579b4cb3eac65de4eac">GlobalAlias</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4493cf5b1bc679abb48cfec28427692">NoCFIValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a46cc2dce21aa2a095533f915c4eaa3">ConstantPtrAuth</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a847cf9e9ee78147bc19b33f21cbba380">ConstantExpr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc0f7da619e9e72510dc07ed7b5ff6d8">Utils</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f639900c480510650969df9c74d17d">Module</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2547a071ebd5adabda1c797f6e914674">IntrinsicInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ff3f826991522d2e77c1c523f33e19">Operator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c56324d11ac3ceefbb34f357b22d605">OverflowingBinaryOperator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a203bf21939cd93b6539ca11553a18e8c">FPMathOperator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6f9325706131f3b6fb8accb1508d76">Region</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a686b3b5946238534f84b88905a6cb89c">ScoreBoard</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ItTy, typename SBTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7e5bdab1596d88c89ead437cfa80e382">LLVMOpUserItToSBTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af552fdd00b391390d86c243c25dcb00c">operator&lt;&lt;</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a> (ClassID SubclassID, llvm::Value *Val, Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5465a4d8f236a3c290a289d4754456e">Value</a> (const Value &amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable copies. <a href="#ae5465a4d8f236a3c290a289d4754456e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3f09be0be854b376ac073505cbe52d">~Value</a> ()=default</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2ce9860d792beabd4422ed33f31ba3">operator=</a> (const Value &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afa2029c46b6caf94a7d05ceb0dbcefe9">ClassID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b9af008c6420f3340805e50297f9fb">getSubclassID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3ee179151f966c4d3e6b79b13029d5ed">use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af685aa3ea024631ed348071914df61c0">use_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8f4300fa0172b1508fc6d82702211dbd">const_use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a840f6f02fc4d09a1139e6dda58bda416">use_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3ee179151f966c4d3e6b79b13029d5ed">use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7990eceef38cd3c233dc0dc8c082ca0">use_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8f4300fa0172b1508fc6d82702211dbd">const_use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb5a1c99c5b0636bbf9ac81e0a78af0">use_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a3ee179151f966c4d3e6b79b13029d5ed">use_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9af9e80bf058a9ab7fd8eec688442e8">uses</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a8f4300fa0172b1508fc6d82702211dbd">const_use_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affbf163ecdb4d5e1582c6ce5474436f5">uses</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a00350c096bb66a07957db161bfad7a07">user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e1ffac63581af9de82a4b2e37a3590">user_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a00350c096bb66a07957db161bfad7a07">user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57bcba1ffad304a316a7dbffdaa55469">user_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7ac68108ddca4c6ef5c7b5d9c186f156">const_user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8642bd999889a386dc68d5e2ae7e6e2a">user_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7ac68108ddca4c6ef5c7b5d9c186f156">const_user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e9a5ba8949bc8dc81470e0063b1bad">user_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a00350c096bb66a07957db161bfad7a07">user_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ba4e46404a59391af05ca6f0c9ce75">users</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a7ac68108ddca4c6ef5c7b5d9c186f156">const_user_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2e1eddb2449d8c488c0f62ebf3a3be1">users</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a395a45c11744d878a19d9db6315bc026">getNumUses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the number of user edges (not necessarily to unique users). <a href="#a395a45c11744d878a19d9db6315bc026">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d160c299df51820d73ff0f393334f8e">hasNUsesOrMore</a> (unsigned Num) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this value has N uses or more. <a href="#a8d160c299df51820d73ff0f393334f8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8dc6457830695a7580727f3bca040e">hasNUses</a> (unsigned Num) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> has exactly N uses. <a href="#abf8dc6457830695a7580727f3bca040e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f93ad2195368bba2202c3cc75e7cc1d">getType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85254176569bc8ee70fff75a9ff59f11">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac76a388ba3671a3d8a93e610f0bf1e3">replaceUsesWithIf</a> (Value *OtherV, llvm::function_ref&lt; bool(const Use &amp;)&gt; ShouldReplace)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357dd7c60a0ea6b2e6c7ecdf9c9923d1">replaceAllUsesWith</a> (Value *Other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aee5e44d2f0c5681724b6ed1db93d19">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the LLVM IR name of the bottom-most LLVM value. <a href="#a2aee5e44d2f0c5681724b6ed1db93d19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31d1ee1d16b05c2843090dbfb43357f7">verify</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should crash if there is something wrong with the instruction. <a href="#a31d1ee1d16b05c2843090dbfb43357f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab622b4257690e722b1c7a988b2c800d">getUid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the unique id in the form 'SB&lt;number&gt;.' like 'SB1.'. <a href="#aab622b4257690e722b1c7a988b2c800d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1565aa2d231b44e393af53deb7de04c2">dumpCommonHeader</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a119c7591f5a3c513ebda9f69414f786c">dumpCommonFooter</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac886f508d3441b842e387f062899f3a8">dumpCommonPrefix</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a294250e6721c14a9a8d934220e6523d0">dumpCommonSuffix</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c2427f89ac0ba1143af9df4414425c">printAsOperandCommon</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5eb4db26f1949633619280980be341c">dumpOS</a> (raw_ostream &amp;OS) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b7941ce25a56640939feaf586fdf97">dump</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab67dfa80034880c5c77e5218c24c105">clearValue</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afa2029c46b6caf94a7d05ceb0dbcefe9">ClassID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565e36982a32c997c13e56b5c42d9b30">SubclassID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For isa/dyn_cast. <a href="#a565e36982a32c997c13e56b5c42d9b30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8f9533cdeeefaf520a852fa9406d01">UID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> used for forming the name (used for debugging). <a href="#abf8f9533cdeeefaf520a852fa9406d01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The LLVM <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> that corresponds to this SandboxIR <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a>. <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4705ee51ec0da1ba978f2353d2c47f27">Ctx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All values point to the context. <a href="#a4705ee51ec0da1ba978f2353d2c47f27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc1366b7fa3a558a916efd3c68a64834">getSubclassIDStr</a> (ClassID ID)</td>
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

<p>A SandboxIR <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> has users. This is the base class.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_use\_iterator {#a8f4300fa0172b1508fc6d82702211dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::Value::const_use_iterator =  UserUseIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>

</div>
</div>

### const\_user\_iterator {#a7ac68108ddca4c6ef5c7b5d9c186f156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::Value::const_user_iterator =  user_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>

</div>
</div>

### use\_iterator {#a3ee179151f966c4d3e6b79b13029d5ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::Value::use_iterator =  UserUseIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>

</div>
</div>

### user\_iterator {#a00350c096bb66a07957db161bfad7a07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::Value::user_iterator =  mapped_iterator&lt;sandboxir::UserUseIterator, UseToUser&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ClassID {#afa2029c46b6caf94a7d05ceb0dbcefe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::sandboxir::Value::ClassID : unsigned</td>
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


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### AllocaInst {#ae866dc3375e9ba50489c2b3d9cce6330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst">AllocaInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ae866dc3375e9ba50489c2b3d9cce6330">AllocaInst</a>.</p>


<p>Referenced by <a href="#ae866dc3375e9ba50489c2b3d9cce6330">AllocaInst</a>.</p>

</div>
</div>

### AtomicCmpXchgInst {#ad35c4527c63aa5a36b64f6f3d40bb21e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst">AtomicCmpXchgInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ad35c4527c63aa5a36b64f6f3d40bb21e">AtomicCmpXchgInst</a>.</p>


<p>Referenced by <a href="#ad35c4527c63aa5a36b64f6f3d40bb21e">AtomicCmpXchgInst</a>.</p>

</div>
</div>

### AtomicRMWInst {#a9645e4372d7022efd24acd311a133178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst">AtomicRMWInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a9645e4372d7022efd24acd311a133178">AtomicRMWInst</a>.</p>


<p>Referenced by <a href="#a9645e4372d7022efd24acd311a133178">AtomicRMWInst</a>.</p>

</div>
</div>

### BinaryOperator {#a79da82c05d91d20c52e064937b35ef2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/binaryoperator">BinaryOperator</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a79da82c05d91d20c52e064937b35ef2e">BinaryOperator</a>.</p>


<p>Referenced by <a href="#a79da82c05d91d20c52e064937b35ef2e">BinaryOperator</a>.</p>

</div>
</div>

### BlockAddress {#aaf5ebc4fa3006b5e52a0e6d02672a09e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/blockaddress">BlockAddress</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#aaf5ebc4fa3006b5e52a0e6d02672a09e">BlockAddress</a>.</p>


<p>Referenced by <a href="#aaf5ebc4fa3006b5e52a0e6d02672a09e">BlockAddress</a>.</p>

</div>
</div>

### BranchInst {#a50b5b44e66bd1a6ff5091c3e501ee264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst">BranchInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a50b5b44e66bd1a6ff5091c3e501ee264">BranchInst</a>.</p>


<p>Referenced by <a href="#a50b5b44e66bd1a6ff5091c3e501ee264">BranchInst</a>.</p>

</div>
</div>

### CallBase {#ab98413af141c094f142c9dc597e88e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase">CallBase</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ab98413af141c094f142c9dc597e88e4a">CallBase</a>.</p>


<p>Referenced by <a href="#ab98413af141c094f142c9dc597e88e4a">CallBase</a>.</p>

</div>
</div>

### CallBrInst {#adb3940474561746eb391fa09835d2e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbrinst">CallBrInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#adb3940474561746eb391fa09835d2e7d">CallBrInst</a>.</p>


<p>Referenced by <a href="#adb3940474561746eb391fa09835d2e7d">CallBrInst</a>.</p>

</div>
</div>

### CallInst {#af189421b2d4e2e4c985045b84eee2dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callinst">CallInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#af189421b2d4e2e4c985045b84eee2dd3">CallInst</a>.</p>


<p>Referenced by <a href="#af189421b2d4e2e4c985045b84eee2dd3">CallInst</a>.</p>

</div>
</div>

### CastInst {#a127de2d3ee894412c0c7916f6f954491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinst">CastInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a127de2d3ee894412c0c7916f6f954491">CastInst</a>.</p>


<p>Referenced by <a href="#a127de2d3ee894412c0c7916f6f954491">CastInst</a>.</p>

</div>
</div>

### CatchPadInst {#a86896a55c60df500e45247ae6a90c67c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchpadinst">CatchPadInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a86896a55c60df500e45247ae6a90c67c">CatchPadInst</a>.</p>


<p>Referenced by <a href="#a86896a55c60df500e45247ae6a90c67c">CatchPadInst</a>.</p>

</div>
</div>

### CatchReturnInst {#a0358e90e75b75e08d5e9bc2fe43dedb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst">CatchReturnInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a0358e90e75b75e08d5e9bc2fe43dedb2">CatchReturnInst</a>.</p>


<p>Referenced by <a href="#a0358e90e75b75e08d5e9bc2fe43dedb2">CatchReturnInst</a>.</p>

</div>
</div>

### CatchSwitchAddHandler {#ad78d68ae66e32955119e78a75d98f855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchaddhandler">CatchSwitchAddHandler</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ad78d68ae66e32955119e78a75d98f855">CatchSwitchAddHandler</a>.</p>


<p>Referenced by <a href="#ad78d68ae66e32955119e78a75d98f855">CatchSwitchAddHandler</a>.</p>

</div>
</div>

### CatchSwitchInst {#a79bf85ac1b69351f041029eaff17702a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst">CatchSwitchInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a79bf85ac1b69351f041029eaff17702a">CatchSwitchInst</a>.</p>


<p>Referenced by <a href="#a79bf85ac1b69351f041029eaff17702a">CatchSwitchInst</a>.</p>

</div>
</div>

### CleanupPadInst {#ac85ed97cd7c97f1a960bca1d12ce770e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanuppadinst">CleanupPadInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ac85ed97cd7c97f1a960bca1d12ce770e">CleanupPadInst</a>.</p>


<p>Referenced by <a href="#ac85ed97cd7c97f1a960bca1d12ce770e">CleanupPadInst</a>.</p>

</div>
</div>

### CleanupReturnInst {#ae7eb5a5b89231219e78ea9678f678186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst">CleanupReturnInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ae7eb5a5b89231219e78ea9678f678186">CleanupReturnInst</a>.</p>


<p>Referenced by <a href="#ae7eb5a5b89231219e78ea9678f678186">CleanupReturnInst</a>.</p>

</div>
</div>

### CmpInst {#a491288b9b4b16c83d513619f00fdcc6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst">CmpInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a491288b9b4b16c83d513619f00fdcc6c">CmpInst</a>.</p>


<p>Referenced by <a href="#a491288b9b4b16c83d513619f00fdcc6c">CmpInst</a>.</p>

</div>
</div>

### ConstantAggregateZero {#aea06d5c01c72b853450109ac8cd4e2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero">ConstantAggregateZero</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#aea06d5c01c72b853450109ac8cd4e2af">ConstantAggregateZero</a>.</p>


<p>Referenced by <a href="#aea06d5c01c72b853450109ac8cd4e2af">ConstantAggregateZero</a>.</p>

</div>
</div>

### ConstantArray {#ab25d2664c586d20df4d7a31d62f305b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantarray">ConstantArray</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ab25d2664c586d20df4d7a31d62f305b9">ConstantArray</a>.</p>


<p>Referenced by <a href="#ab25d2664c586d20df4d7a31d62f305b9">ConstantArray</a>.</p>

</div>
</div>

### ConstantExpr {#a847cf9e9ee78147bc19b33f21cbba380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantexpr">ConstantExpr</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a847cf9e9ee78147bc19b33f21cbba380">ConstantExpr</a>.</p>


<p>Referenced by <a href="#a847cf9e9ee78147bc19b33f21cbba380">ConstantExpr</a>.</p>

</div>
</div>

### ConstantPointerNull {#a583b196fc6b358d576dd8e26820521b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantpointernull">ConstantPointerNull</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a583b196fc6b358d576dd8e26820521b9">ConstantPointerNull</a>.</p>


<p>Referenced by <a href="#a583b196fc6b358d576dd8e26820521b9">ConstantPointerNull</a>.</p>

</div>
</div>

### ConstantPtrAuth {#a5a46cc2dce21aa2a095533f915c4eaa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth">ConstantPtrAuth</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a5a46cc2dce21aa2a095533f915c4eaa3">ConstantPtrAuth</a>.</p>


<p>Referenced by <a href="#a5a46cc2dce21aa2a095533f915c4eaa3">ConstantPtrAuth</a>.</p>

</div>
</div>

### ConstantStruct {#a1696f5f9994bd1a179b4c2869d5d90ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantstruct">ConstantStruct</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a1696f5f9994bd1a179b4c2869d5d90ea">ConstantStruct</a>.</p>


<p>Referenced by <a href="#a1696f5f9994bd1a179b4c2869d5d90ea">ConstantStruct</a>.</p>

</div>
</div>

### Context {#ac26c806e60ca4a0547680edb68f6e39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>.</p>


<p>Referenced by <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#a85254176569bc8ee70fff75a9ff59f11">getContext</a>, <a href="#a7e5bdab1596d88c89ead437cfa80e382">LLVMOpUserItToSBTy</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#aed798e20a38c7c32351becc11f61f755">llvm::sandboxir::User::User</a> and <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>.</p>

</div>
</div>

### DSOLocalEquivalent {#afc864586410a7d1e3791c238b1506ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dsolocalequivalent">DSOLocalEquivalent</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#afc864586410a7d1e3791c238b1506ba8">DSOLocalEquivalent</a>.</p>


<p>Referenced by <a href="#afc864586410a7d1e3791c238b1506ba8">DSOLocalEquivalent</a>.</p>

</div>
</div>

### ExtractElementInst {#a369dad8734d5d892a3ecf2870aef5e59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractelementinst">ExtractElementInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a369dad8734d5d892a3ecf2870aef5e59">ExtractElementInst</a>.</p>


<p>Referenced by <a href="#a369dad8734d5d892a3ecf2870aef5e59">ExtractElementInst</a>.</p>

</div>
</div>

### ExtractValueInst {#a4ffbe75c00da4ace042051200436174b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst">ExtractValueInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a4ffbe75c00da4ace042051200436174b">ExtractValueInst</a>.</p>


<p>Referenced by <a href="#a4ffbe75c00da4ace042051200436174b">ExtractValueInst</a>.</p>

</div>
</div>

### FenceInst {#a17b6a6ca6e4942ee198cdb58963959f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fenceinst">FenceInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a17b6a6ca6e4942ee198cdb58963959f0">FenceInst</a>.</p>


<p>Referenced by <a href="#a17b6a6ca6e4942ee198cdb58963959f0">FenceInst</a>.</p>

</div>
</div>

### FPMathOperator {#a203bf21939cd93b6539ca11553a18e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator">FPMathOperator</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a203bf21939cd93b6539ca11553a18e8c">FPMathOperator</a>.</p>


<p>Referenced by <a href="#a203bf21939cd93b6539ca11553a18e8c">FPMathOperator</a>.</p>

</div>
</div>

### FreezeInst {#a3539d881344c8843a26bb506f5d0a671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/freezeinst">FreezeInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a3539d881344c8843a26bb506f5d0a671">FreezeInst</a>.</p>


<p>Referenced by <a href="#a3539d881344c8843a26bb506f5d0a671">FreezeInst</a>.</p>

</div>
</div>

### FuncletPadInst {#acef2573abe929fbab47661ee76397504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/funcletpadinst">FuncletPadInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#acef2573abe929fbab47661ee76397504">FuncletPadInst</a>.</p>


<p>Referenced by <a href="#acef2573abe929fbab47661ee76397504">FuncletPadInst</a>.</p>

</div>
</div>

### GetElementPtrInst {#ac3a17a4b38a74d8a6f80a1746482a359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst">GetElementPtrInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ac3a17a4b38a74d8a6f80a1746482a359">GetElementPtrInst</a>.</p>


<p>Referenced by <a href="#ac3a17a4b38a74d8a6f80a1746482a359">GetElementPtrInst</a>.</p>

</div>
</div>

### GlobalAlias {#a766f60740d82f579b4cb3eac65de4eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias">GlobalAlias</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a766f60740d82f579b4cb3eac65de4eac">GlobalAlias</a>.</p>


<p>Referenced by <a href="#a766f60740d82f579b4cb3eac65de4eac">GlobalAlias</a>.</p>

</div>
</div>

### GlobalIFunc {#abd70c9300632f0382cb21a8aba6b52d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc">GlobalIFunc</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#abd70c9300632f0382cb21a8aba6b52d7">GlobalIFunc</a>.</p>


<p>Referenced by <a href="#abd70c9300632f0382cb21a8aba6b52d7">GlobalIFunc</a>.</p>

</div>
</div>

### GlobalObject {#ac177bc079fe0a6e9b3d3115702db3bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject">GlobalObject</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ac177bc079fe0a6e9b3d3115702db3bc3">GlobalObject</a>.</p>


<p>Referenced by <a href="#ac177bc079fe0a6e9b3d3115702db3bc3">GlobalObject</a>.</p>

</div>
</div>

### GlobalValue {#a9afdd98ee0b7ab43bc76deb4180ea986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue">GlobalValue</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a9afdd98ee0b7ab43bc76deb4180ea986">GlobalValue</a>.</p>


<p>Referenced by <a href="#a9afdd98ee0b7ab43bc76deb4180ea986">GlobalValue</a>.</p>

</div>
</div>

### GlobalVariable {#aa7039b9bbd22fbf967673646ae083665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable">GlobalVariable</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#aa7039b9bbd22fbf967673646ae083665">GlobalVariable</a>.</p>


<p>Referenced by <a href="#aa7039b9bbd22fbf967673646ae083665">GlobalVariable</a>.</p>

</div>
</div>

### InsertElementInst {#a0214f7aa1d5031949fd91849f6084b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertelementinst">InsertElementInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a0214f7aa1d5031949fd91849f6084b6d">InsertElementInst</a>.</p>


<p>Referenced by <a href="#a0214f7aa1d5031949fd91849f6084b6d">InsertElementInst</a>.</p>

</div>
</div>

### InsertValueInst {#a60fb03fae5fbc7e35f7a6a25c66e7145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertvalueinst">InsertValueInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a60fb03fae5fbc7e35f7a6a25c66e7145">InsertValueInst</a>.</p>


<p>Referenced by <a href="#a60fb03fae5fbc7e35f7a6a25c66e7145">InsertValueInst</a>.</p>

</div>
</div>

### IntrinsicInst {#a2547a071ebd5adabda1c797f6e914674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/intrinsicinst">IntrinsicInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a2547a071ebd5adabda1c797f6e914674">IntrinsicInst</a>.</p>


<p>Referenced by <a href="#a2547a071ebd5adabda1c797f6e914674">IntrinsicInst</a>.</p>

</div>
</div>

### InvokeInst {#a6ae546a926945494684eeed4ccb13694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst">InvokeInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a6ae546a926945494684eeed4ccb13694">InvokeInst</a>.</p>


<p>Referenced by <a href="#a6ae546a926945494684eeed4ccb13694">InvokeInst</a>.</p>

</div>
</div>

### LandingPadInst {#ad7e77f69120edadc2d8723bbb05b270e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/landingpadinst">LandingPadInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ad7e77f69120edadc2d8723bbb05b270e">LandingPadInst</a>.</p>


<p>Referenced by <a href="#ad7e77f69120edadc2d8723bbb05b270e">LandingPadInst</a>.</p>

</div>
</div>

### LLVMOpUserItToSBTy {#a7e5bdab1596d88c89ead437cfa80e382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class LLVMOpUserItToSBTy</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#a4705ee51ec0da1ba978f2353d2c47f27">Ctx</a>, <a href="#a7e5bdab1596d88c89ead437cfa80e382">LLVMOpUserItToSBTy</a>, <a href="#a565e36982a32c997c13e56b5c42d9b30">SubclassID</a> and <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a>.</p>


<p>Referenced by <a href="#a7e5bdab1596d88c89ead437cfa80e382">LLVMOpUserItToSBTy</a>.</p>

</div>
</div>

### LoadInst {#a955c4f7e0f02efa92ec3b6a0efb28aea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/loadinst">LoadInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a955c4f7e0f02efa92ec3b6a0efb28aea">LoadInst</a>.</p>


<p>Referenced by <a href="#a955c4f7e0f02efa92ec3b6a0efb28aea">LoadInst</a>.</p>

</div>
</div>

### Module {#a21f639900c480510650969df9c74d17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">Module</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>


<p>Referenced by <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>

</div>
</div>

### NoCFIValue {#ad4493cf5b1bc679abb48cfec28427692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue">NoCFIValue</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ad4493cf5b1bc679abb48cfec28427692">NoCFIValue</a>.</p>


<p>Referenced by <a href="#ad4493cf5b1bc679abb48cfec28427692">NoCFIValue</a>.</p>

</div>
</div>

### Operator {#a33ff3f826991522d2e77c1c523f33e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/operator">Operator</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a33ff3f826991522d2e77c1c523f33e19">Operator</a>.</p>


<p>Referenced by <a href="#a33ff3f826991522d2e77c1c523f33e19">Operator</a>.</p>

</div>
</div>

### operator&lt;&lt; {#af552fdd00b391390d86c243c25dcb00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">sandboxir::Value</a> &amp; V</td>
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


<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>

</div>
</div>

### OverflowingBinaryOperator {#a1c56324d11ac3ceefbb34f357b22d605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/overflowingbinaryoperator">OverflowingBinaryOperator</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a1c56324d11ac3ceefbb34f357b22d605">OverflowingBinaryOperator</a>.</p>


<p>Referenced by <a href="#a1c56324d11ac3ceefbb34f357b22d605">OverflowingBinaryOperator</a>.</p>

</div>
</div>

### PHINode {#ac6abe966290db4687216fd43f34316dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode">PHINode</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#ac6abe966290db4687216fd43f34316dd">PHINode</a>.</p>


<p>Referenced by <a href="#ac6abe966290db4687216fd43f34316dd">PHINode</a>.</p>

</div>
</div>

### PoisonValue {#a8d548fda8ab959b3433900f43d619717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue">PoisonValue</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a8d548fda8ab959b3433900f43d619717">PoisonValue</a>.</p>


<p>Referenced by <a href="#a8d548fda8ab959b3433900f43d619717">PoisonValue</a>.</p>

</div>
</div>

### Region {#aae6f9325706131f3b6fb8accb1508d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/region">Region</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#aae6f9325706131f3b6fb8accb1508d76">Region</a>.</p>


<p>Referenced by <a href="#aae6f9325706131f3b6fb8accb1508d76">Region</a>.</p>

</div>
</div>

### ResumeInst {#a8ae74d098b741f3ccbf4b7b898537adf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/resumeinst">ResumeInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a8ae74d098b741f3ccbf4b7b898537adf">ResumeInst</a>.</p>


<p>Referenced by <a href="#a8ae74d098b741f3ccbf4b7b898537adf">ResumeInst</a>.</p>

</div>
</div>

### ReturnInst {#a507ff1515eddab6aade1f9c639d45d32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/returninst">ReturnInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a507ff1515eddab6aade1f9c639d45d32">ReturnInst</a>.</p>


<p>Referenced by <a href="#a507ff1515eddab6aade1f9c639d45d32">ReturnInst</a>.</p>

</div>
</div>

### ScoreBoard {#a686b3b5946238534f84b88905a6cb89c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scoreboard">ScoreBoard</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a686b3b5946238534f84b88905a6cb89c">ScoreBoard</a>.</p>


<p>Referenced by <a href="#a686b3b5946238534f84b88905a6cb89c">ScoreBoard</a>.</p>

</div>
</div>

### SelectInst {#a105433331bc5e110865accd9b63da4ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/selectinst">SelectInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a105433331bc5e110865accd9b63da4ff">SelectInst</a>.</p>


<p>Referenced by <a href="#a105433331bc5e110865accd9b63da4ff">SelectInst</a>.</p>

</div>
</div>

### ShuffleVectorInst {#a4d2fb6321caaf9c477057c323f74deb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst">ShuffleVectorInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a4d2fb6321caaf9c477057c323f74deb3">ShuffleVectorInst</a>.</p>


<p>Referenced by <a href="#a4d2fb6321caaf9c477057c323f74deb3">ShuffleVectorInst</a>.</p>

</div>
</div>

### StoreInst {#a45c970b286be2bf7b3e2de4cc81a9ff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst">StoreInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a45c970b286be2bf7b3e2de4cc81a9ff6">StoreInst</a>.</p>


<p>Referenced by <a href="#a45c970b286be2bf7b3e2de4cc81a9ff6">StoreInst</a>.</p>

</div>
</div>

### SwitchInst {#a51642bf4a74518f4e827380a81b0310d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst">SwitchInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a51642bf4a74518f4e827380a81b0310d">SwitchInst</a>.</p>


<p>Referenced by <a href="#a51642bf4a74518f4e827380a81b0310d">SwitchInst</a>.</p>

</div>
</div>

### UnaryOperator {#a0b643be70069658c68fb3d047771eb86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unaryoperator">UnaryOperator</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a0b643be70069658c68fb3d047771eb86">UnaryOperator</a>.</p>


<p>Referenced by <a href="#a0b643be70069658c68fb3d047771eb86">UnaryOperator</a>.</p>

</div>
</div>

### UndefValue {#af71c3b3f23690ee6a15b4227d496cfc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue">UndefValue</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#af71c3b3f23690ee6a15b4227d496cfc3">UndefValue</a>.</p>


<p>Referenced by <a href="#af71c3b3f23690ee6a15b4227d496cfc3">UndefValue</a>.</p>

</div>
</div>

### UnreachableInst {#a08f62606ea33ba15b80c5b799c9a0ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unreachableinst">UnreachableInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a08f62606ea33ba15b80c5b799c9a0ca1">UnreachableInst</a>.</p>


<p>Referenced by <a href="#a08f62606ea33ba15b80c5b799c9a0ca1">UnreachableInst</a>.</p>

</div>
</div>

### Use {#a7b479862be57f4448b155a225b5972ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a7b479862be57f4448b155a225b5972ac">Use</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a0f2dc3be47f89fbc1bdb308271fbb7c7">llvm::sandboxir::CallBase::getCalledOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#acb9166dd8e540f8c9e6efad7e9cccba0">llvm::sandboxir::User::getOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a8014de6610ee432b675e3819e011acb2">llvm::sandboxir::User::getOperandUseDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#aa469c4f23b78900ac9135b3417819f31">llvm::sandboxir::User::getOperandUseInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a1edb73baa990149e09d9405f596163a3">llvm::sandboxir::User::getUseOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a2a0e1f0647903c551dc3ea6333ab6fc3">llvm::sandboxir::User::getUseOperandNoDefault</a>, <a href="/web-llvm/docs/api/structs/llvm/sandboxir/value/usetouser/#a98bd24ad1ffb8c655d387e446b14d778">llvm::sandboxir::Value::UseToUser::operator()</a>, <a href="#a357dd7c60a0ea6b2e6c7ecdf9c9923d1">replaceAllUsesWith</a>, <a href="#aac76a388ba3671a3d8a93e610f0bf1e3">replaceUsesWithIf</a>, <a href="#a7b479862be57f4448b155a225b5972ac">Use</a>, <a href="#af685aa3ea024631ed348071914df61c0">use_begin</a>, <a href="#ac7990eceef38cd3c233dc0dc8c082ca0">use_end</a>, <a href="#a57bcba1ffad304a316a7dbffdaa55469">user_end</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a29a530f0bf7efe84cbba172fac79970d">llvm::sandboxir::User::verifyUserOfLLVMUse</a>.</p>

</div>
</div>

### User {#a38c437d9dcaefebe4efaf0edf00c45de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user">User</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a38c437d9dcaefebe4efaf0edf00c45de">User</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/sandboxir/value/usetouser/#a98bd24ad1ffb8c655d387e446b14d778">llvm::sandboxir::Value::UseToUser::operator()</a>, <a href="#af685aa3ea024631ed348071914df61c0">use_begin</a>, <a href="#a38c437d9dcaefebe4efaf0edf00c45de">User</a> and <a href="#af6e1ffac63581af9de82a4b2e37a3590">user_begin</a>.</p>

</div>
</div>

### Utils {#abc0f7da619e9e72510dc07ed7b5ff6d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils">Utils</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#abc0f7da619e9e72510dc07ed7b5ff6d8">Utils</a>.</p>


<p>Referenced by <a href="#abc0f7da619e9e72510dc07ed7b5ff6d8">Utils</a>.</p>

</div>
</div>

### VAArgInst {#a5a51bd9683e1167d25e2b645659df16e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vaarginst">VAArgInst</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a5a51bd9683e1167d25e2b645659df16e">VAArgInst</a>.</p>


<p>Referenced by <a href="#a5a51bd9683e1167d25e2b645659df16e">VAArgInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### Value() {#a73b563c1c2654e2f9b3756f38e276284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::Value::Value (<a href="#afa2029c46b6caf94a7d05ceb0dbcefe9">ClassID</a> SubclassID, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#a4705ee51ec0da1ba978f2353d2c47f27">Ctx</a>, <a href="#a565e36982a32c997c13e56b5c42d9b30">SubclassID</a>, <a href="#abf8f9533cdeeefaf520a852fa9406d01">UID</a> and <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a980a2cfe3503510dad80d58a1bf46367">llvm::sandboxir::User::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a1d0f6b7220d01d4fe9ecefd3c296a02d">llvm::sandboxir::User::getOperand</a>, <a href="#a9a2ce9860d792beabd4422ed33f31ba3">operator=</a>, <a href="#a357dd7c60a0ea6b2e6c7ecdf9c9923d1">replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a7a710a597d6f0560bb7e05ea54512520">llvm::sandboxir::User::replaceUsesOfWith</a>, <a href="#aac76a388ba3671a3d8a93e610f0bf1e3">replaceUsesWithIf</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a54abb07f9d20e6d5344ce647621f85a8">llvm::sandboxir::User::setOperand</a>, <a href="#a840f6f02fc4d09a1139e6dda58bda416">use_begin</a>, <a href="#a1cb5a1c99c5b0636bbf9ac81e0a78af0">use_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#aed798e20a38c7c32351becc11f61f755">llvm::sandboxir::User::User</a>, <a href="#a8642bd999889a386dc68d5e2ae7e6e2a">user_begin</a>, <a href="#ac9e9a5ba8949bc8dc81470e0063b1bad">user_end</a> and <a href="#ae5465a4d8f236a3c290a289d4754456e">Value</a>.</p>

</div>
</div>

### Value() {#ae5465a4d8f236a3c290a289d4754456e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::Value::Value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Disable copies.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Value() {#a7f3f09be0be854b376ac073505cbe52d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::sandboxir::Value::~Value ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#a9a2ce9860d792beabd4422ed33f31ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value &amp; llvm::sandboxir::Value::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a58b7941ce25a56640939feaf586fdf97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Value::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#ac5eb4db26f1949633619280980be341c">dumpOS</a>.</p>

</div>
</div>

### dumpCommonFooter() {#a119c7591f5a3c513ebda9f69414f786c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Value::dumpCommonFooter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a> and <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a>.</p>

</div>
</div>

### dumpCommonHeader() {#a1565aa2d231b44e393af53deb7de04c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Value::dumpCommonHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="#adc1366b7fa3a558a916efd3c68a64834">getSubclassIDStr</a>, <a href="#aab622b4257690e722b1c7a988b2c800d">getUid</a> and <a href="#a565e36982a32c997c13e56b5c42d9b30">SubclassID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#aa54928bdcbec1bc934abc9dc7e72445e">llvm::sandboxir::User::dumpCommonHeader</a>.</p>

</div>
</div>

### dumpCommonPrefix() {#ac886f508d3441b842e387f062899f3a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Value::dumpCommonPrefix (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Reference <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument/#a068026a02cfbf57847a29a10aec86286">llvm::sandboxir::Argument::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a71553c04d79dee6c0ca7ac1d66732120">llvm::sandboxir::CmpInst::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#a528b9eb53f5e35beac3d1c8a15ab303c">llvm::sandboxir::Constant::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#ac160aa25e33ee624357efaa86e3fdb6e">llvm::sandboxir::ConstantAggregateZero::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#a91c24ecc5ca2baedce3f506ad124e5eb">llvm::sandboxir::ConstantFP::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#aadbb802d3e7894c2e08a270859cf0d67">llvm::sandboxir::ConstantInt::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantpointernull/#a47d8237c869e94b641d2130bf400cc44">llvm::sandboxir::ConstantPointerNull::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constanttokennone/#a0460bb95bcc2ec0522cd207c625cd6c9">llvm::sandboxir::ConstantTokenNone::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dsolocalequivalent/#aa99d1923bdd6fb8c83529ec72fb1c83a">llvm::sandboxir::DSOLocalEquivalent::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc/#af16b226e66627d4a8e1a50c77f6c468c">llvm::sandboxir::GlobalIFunc::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#ae7039b7126ecea33b18ac65f8377c7a9">llvm::sandboxir::GlobalVariable::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#a4d8418190039efe0158a6d70cdf72d92">llvm::sandboxir::NoCFIValue::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#a526d976518587ce84955474c01907822">llvm::sandboxir::PoisonValue::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/singlellvminstructionimpl/#a76f9c85ffaaa5a96667f79fdc1cb6bf2">llvm::sandboxir::SingleLLVMInstructionImpl&lt; LLVMT &gt;::dumpOS</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#a6cf8905af49fb31eee1e616d8102d59a">llvm::sandboxir::UndefValue::dumpOS</a>.</p>

</div>
</div>

### dumpCommonSuffix() {#a294250e6721c14a9a8d934220e6523d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Value::dumpCommonSuffix (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="#adc1366b7fa3a558a916efd3c68a64834">getSubclassIDStr</a>, <a href="#aab622b4257690e722b1c7a988b2c800d">getUid</a> and <a href="#a565e36982a32c997c13e56b5c42d9b30">SubclassID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument/#a068026a02cfbf57847a29a10aec86286">llvm::sandboxir::Argument::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a71553c04d79dee6c0ca7ac1d66732120">llvm::sandboxir::CmpInst::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#a528b9eb53f5e35beac3d1c8a15ab303c">llvm::sandboxir::Constant::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#ac160aa25e33ee624357efaa86e3fdb6e">llvm::sandboxir::ConstantAggregateZero::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#a91c24ecc5ca2baedce3f506ad124e5eb">llvm::sandboxir::ConstantFP::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#aadbb802d3e7894c2e08a270859cf0d67">llvm::sandboxir::ConstantInt::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantpointernull/#a47d8237c869e94b641d2130bf400cc44">llvm::sandboxir::ConstantPointerNull::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constanttokennone/#a0460bb95bcc2ec0522cd207c625cd6c9">llvm::sandboxir::ConstantTokenNone::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dsolocalequivalent/#aa99d1923bdd6fb8c83529ec72fb1c83a">llvm::sandboxir::DSOLocalEquivalent::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc/#af16b226e66627d4a8e1a50c77f6c468c">llvm::sandboxir::GlobalIFunc::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#ae7039b7126ecea33b18ac65f8377c7a9">llvm::sandboxir::GlobalVariable::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#a4d8418190039efe0158a6d70cdf72d92">llvm::sandboxir::NoCFIValue::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#a526d976518587ce84955474c01907822">llvm::sandboxir::PoisonValue::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/singlellvminstructionimpl/#a76f9c85ffaaa5a96667f79fdc1cb6bf2">llvm::sandboxir::SingleLLVMInstructionImpl&lt; LLVMT &gt;::dumpOS</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#a6cf8905af49fb31eee1e616d8102d59a">llvm::sandboxir::UndefValue::dumpOS</a>.</p>

</div>
</div>

### dumpOS() {#ac5eb4db26f1949633619280980be341c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sandboxir::Value::dumpOS (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>


<p>Referenced by <a href="#a58b7941ce25a56640939feaf586fdf97">dump</a>.</p>

</div>
</div>

### getContext() {#a85254176569bc8ee70fff75a9ff59f11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context &amp; llvm::sandboxir::Value::getContext ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a> and <a href="#a4705ee51ec0da1ba978f2353d2c47f27">Ctx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dsolocalequivalent/#a66f628a21e67b68d6ae93a9f80bb4067">llvm::sandboxir::DSOLocalEquivalent::get</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#afa0e3ddd6a06a4f5de4142baad208a38">llvm::sandboxir::NoCFIValue::get</a>.</p>

</div>
</div>

### getName() {#a2aee5e44d2f0c5681724b6ed1db93d19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sandboxir::Value::getName ()</td>
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

<p>\Returns the LLVM IR name of the bottom-most LLVM value.</p>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a>.</p>

</div>
</div>

### getNumUses() {#a395a45c11744d878a19d9db6315bc026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::Value::getNumUses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns the number of user edges (not necessarily to unique users).</p>


<p>WARNING: This is a linear-time operation.</p>


<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6b2aff7cbd77ba33d6f6fd816ac789d9">llvm::range_size</a> and <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a>.</p>

</div>
</div>

### getSubclassID() {#a27b9af008c6420f3340805e50297f9fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassID llvm::sandboxir::Value::getSubclassID ()</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a565e36982a32c997c13e56b5c42d9b30">SubclassID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument/#ac2bf5cf2da8ea68dc0969485a53f23be">llvm::sandboxir::Argument::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a99be2c82af15ed5f67bbbaa62f221551">llvm::sandboxir::AtomicCmpXchgInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#ab9035fde5a006f3701837b709a61da87">llvm::sandboxir::AtomicRMWInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/binaryoperator/#a6604628209963c12817d8b1e67fbc196">llvm::sandboxir::BinaryOperator::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/blockaddress/#afd7b8936d60b2dce62b15ea6be1484f6">llvm::sandboxir::BlockAddress::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a37ae6ff97ab138e11035976625dca8f1">llvm::sandboxir::BranchInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a23d925a771e3feadff6100257ef8fadf">llvm::sandboxir::CallBase::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbrinst/#a3ac3693ee11b25a5b88de34b6ce0322e">llvm::sandboxir::CallBrInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callinst/#ae050d2ade84b4e89565ad8b5b6052c4e">llvm::sandboxir::CallInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinst/#af97fa044c37a5cc5d67524498263a62e">llvm::sandboxir::CastInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchpadinst/#a10368e0c6bbbce231121631ac924fa5f">llvm::sandboxir::CatchPadInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#a4a8b4e103ada7616b474a0cbb36e2cca">llvm::sandboxir::CatchReturnInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#ac63914b0fcd9dfa9f430c70a1cc93a66">llvm::sandboxir::CatchSwitchInst::classof</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a6fbc33daa780beb81b1ec2326cb716dc">llvm::sandboxir::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanuppadinst/#ae9c8e9e6431a3e3f745b2bb2cd5c7d86">llvm::sandboxir::CleanupPadInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#ae8b63b4ca7fc3eeb7b382a40831547ed">llvm::sandboxir::CleanupReturnInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#afe67cc8b23508a2270d90e949d3c49dc">llvm::sandboxir::CmpInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#a53757f9a4360b8e26ef6053056f323ac">llvm::sandboxir::Constant::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregate/#a0a318142d7fe17d4fa956f433f3ab9e3">llvm::sandboxir::ConstantAggregate::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#a202e7cbfd81f72582bdfa1ed465fd664">llvm::sandboxir::ConstantAggregateZero::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantarray/#a512af533758c1648c0248af6da5c0ae2">llvm::sandboxir::ConstantArray::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantexpr/#aaf52b2152fd9c9736e8ae5d35d795c7b">llvm::sandboxir::ConstantExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#a9e49de615a8bf13dea3a2edd4e2048a7">llvm::sandboxir::ConstantFP::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#ae85c2592c0736d2e0b468ecf210bc5e4">llvm::sandboxir::ConstantInt::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantpointernull/#a5b2dc47575471cbdd73676c4550c13ad">llvm::sandboxir::ConstantPointerNull::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#ae2a827c43ef107eddbef1c2987984aae">llvm::sandboxir::ConstantPtrAuth::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantstruct/#af6407789945bbd1fdee38b9b70bf5e1b">llvm::sandboxir::ConstantStruct::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constanttokennone/#a4fad40944b265a6a78195ffc8b43d67c">llvm::sandboxir::ConstantTokenNone::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantvector/#a2dad9e5ca268029ec084fc00f354e74d">llvm::sandboxir::ConstantVector::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dsolocalequivalent/#a43eeeb1a2c3fd2fafb95a3d071e4047a">llvm::sandboxir::DSOLocalEquivalent::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractelementinst/#ad673d227503e58ddcb4dd3941fa50324">llvm::sandboxir::ExtractElementInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#aeb806dab024fffd71f87e56146305a96">llvm::sandboxir::ExtractValueInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fcmpinst/#a7dc0f1ebabef171f46eda57b34a266bb">llvm::sandboxir::FCmpInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fenceinst/#ad667393c785e6eb52b5965154ac64fc7">llvm::sandboxir::FenceInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/freezeinst/#a6aeae244efe6a8c73b9e61524d022e06">llvm::sandboxir::FreezeInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/funcletpadinst/#a015e4a2115d01a1ca73585c1f0e1b738">llvm::sandboxir::FuncletPadInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#af6a0dec3699a9b9a1ed73ffc8b8a6764">llvm::sandboxir::Function::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#aeaebe8a82d1f9ebcde7515457b7c79e0">llvm::sandboxir::GetElementPtrInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias/#a27c9088f4451608a542ebe926883278d">llvm::sandboxir::GlobalAlias::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc/#abbc45b0a85cfaf675801a4e37b5732e5">llvm::sandboxir::GlobalIFunc::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#ab89473e28097b463697cdef082a6cb8c">llvm::sandboxir::GlobalObject::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#a9ff83b046d3179fbcbb1947b3edbe0d9">llvm::sandboxir::GlobalValue::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a52b87399ac743178d43c569154afeaa0">llvm::sandboxir::GlobalVariable::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/icmpinst/#af6acbea49e46bc81ca9eac9fc0ae48b2">llvm::sandboxir::ICmpInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertelementinst/#afe2d9622cc5adb54383c87a713e410ea">llvm::sandboxir::InsertElementInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertvalueinst/#a757090de36871aa5fe2d8db7681b3fff">llvm::sandboxir::InsertValueInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#aff1bc3ac008c894a80e3819c1dd3ef30">llvm::sandboxir::Instruction::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst/#ac5bb1c2b31e58c83c6261442b0520358">llvm::sandboxir::InvokeInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/landingpadinst/#af6b2872796cf2e145d76cc67048a5b18">llvm::sandboxir::LandingPadInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/loadinst/#ad2fa77720f07e0fb0b5a91eac8bafe54">llvm::sandboxir::LoadInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#a3093bc21e8e8105de403447c1ea7b19d">llvm::sandboxir::NoCFIValue::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/opaqueinst/#ad62a2d8c6746273e6f25de3e5367aea1">llvm::sandboxir::OpaqueInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a9c6db86f76525fd5a3cf52f02648f70f">llvm::sandboxir::PHINode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#afdedf2d17df04e93cfe97aff05b8898d">llvm::sandboxir::PoisonValue::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/resumeinst/#ab869a1775186829fe73041f01b45a029">llvm::sandboxir::ResumeInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/returninst/#a6f24aeb8d5ee0280e581778624b699a5">llvm::sandboxir::ReturnInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/selectinst/#a2ed9b3af029ea94d85c6ebded83d0780">llvm::sandboxir::SelectInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#afedc432860565b4f67bb8e52df73ba7d">llvm::sandboxir::ShuffleVectorInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst/#a5fb772b5660e47c3406da17d16630f0b">llvm::sandboxir::StoreInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#a9bc0013906b15a7c83cb6da7987112e9">llvm::sandboxir::SwitchInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unaryoperator/#a572f58690f59f13e6e6292af8c10a816">llvm::sandboxir::UnaryOperator::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#a86eb966a26a6b7ef7cf475c157188beb">llvm::sandboxir::UndefValue::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unreachableinst/#af4a3319ddda05c225be180cd6f9815e3">llvm::sandboxir::UnreachableInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a980a2cfe3503510dad80d58a1bf46367">llvm::sandboxir::User::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vaarginst/#ad3a963ec6cdc7555e93b858a8a1b730f">llvm::sandboxir::VAArgInst::classof</a>.</p>

</div>
</div>

### getType() {#a5f93ad2195368bba2202c3cc75e7cc1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::sandboxir::Value::getType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="#a4705ee51ec0da1ba978f2353d2c47f27">Ctx</a> and <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/addrspacecastinst/#a774a0a887b03ce2aa37b5409105ebf6f">llvm::sandboxir::AddrSpaceCastInst::getDestAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#a94ed4ff75262c5c7bf6107a1cb09d583">llvm::sandboxir::Utils::getExpectedType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/addrspacecastinst/#a088eb1bfed8c280333c53c97e981b4e0">llvm::sandboxir::AddrSpaceCastInst::getSrcAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantstruct/#ab9dba997038b2bd18c603b16412ef0c2">llvm::sandboxir::ConstantStruct::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractelementinst/#a7ad888b66278c533a367650a3bb01d0f">llvm::sandboxir::ExtractElementInst::getVectorOperandType</a>, <a href="#a357dd7c60a0ea6b2e6c7ecdf9c9923d1">replaceAllUsesWith</a> and <a href="#aac76a388ba3671a3d8a93e610f0bf1e3">replaceUsesWithIf</a>.</p>

</div>
</div>

### getUid() {#aab622b4257690e722b1c7a988b2c800d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::sandboxir::Value::getUid ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the unique id in the form 'SB&lt;number&gt;.' like 'SB1.'.</p>

<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Reference <a href="#abf8f9533cdeeefaf520a852fa9406d01">UID</a>.</p>


<p>Referenced by <a href="#a1565aa2d231b44e393af53deb7de04c2">dumpCommonHeader</a> and <a href="#a294250e6721c14a9a8d934220e6523d0">dumpCommonSuffix</a>.</p>

</div>
</div>

### hasNUses() {#abf8dc6457830695a7580727f3bca040e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Value::hasNUses (unsigned Num)</td>
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

<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> has exactly N uses.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="#af685aa3ea024631ed348071914df61c0">use_begin</a> and <a href="#ac7990eceef38cd3c233dc0dc8c082ca0">use_end</a>.</p>

</div>
</div>

### hasNUsesOrMore() {#a8d160c299df51820d73ff0f393334f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Value::hasNUsesOrMore (unsigned Num)</td>
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

<p>Return true if this value has N uses or more.</p>


<p>This is logically equivalent to <a href="#a395a45c11744d878a19d9db6315bc026">getNumUses()</a> &gt;= N. WARNING: This can be expensive, as it is linear to the number of users.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="#af685aa3ea024631ed348071914df61c0">use_begin</a> and <a href="#ac7990eceef38cd3c233dc0dc8c082ca0">use_end</a>.</p>

</div>
</div>

### printAsOperandCommon() {#a40c2427f89ac0ba1143af9df4414425c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Value::printAsOperandCommon (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument/#a688333637a2d38396fef8f7d9604d601">llvm::sandboxir::Argument::printAsOperand</a>.</p>

</div>
</div>

### replaceAllUsesWith() {#a357dd7c60a0ea6b2e6c7ecdf9c9923d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Value::replaceAllUsesWith (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4705ee51ec0da1ba978f2353d2c47f27">Ctx</a>, <a href="#a5f93ad2195368bba2202c3cc75e7cc1d">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/tracker/#aa19c60a204cb57bc2a7e76803aa34396">llvm::sandboxir::Tracker::isTracking</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/tracker/#abc06dcb45b7b1609a832dcce4b36c227">llvm::sandboxir::Tracker::track</a>, <a href="#a7b479862be57f4448b155a225b5972ac">Use</a>, <a href="#ac9af9e80bf058a9ab7fd8eec688442e8">uses</a>, <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a> and <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>.</p>

</div>
</div>

### replaceUsesWithIf() {#aac76a388ba3671a3d8a93e610f0bf1e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Value::replaceUsesWithIf (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * OtherV, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> &amp;)&gt; ShouldReplace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5f93ad2195368bba2202c3cc75e7cc1d">getType</a>, <a href="#a7b479862be57f4448b155a225b5972ac">Use</a>, <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a> and <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>.</p>

</div>
</div>

### use\_begin() {#af685aa3ea024631ed348071914df61c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value::use_iterator llvm::sandboxir::Value::use_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="#a4705ee51ec0da1ba978f2353d2c47f27">Ctx</a>, <a href="#a7b479862be57f4448b155a225b5972ac">Use</a>, <a href="#a38c437d9dcaefebe4efaf0edf00c45de">User</a> and <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a>.</p>


<p>Referenced by <a href="#abf8dc6457830695a7580727f3bca040e">hasNUses</a>, <a href="#a8d160c299df51820d73ff0f393334f8e">hasNUsesOrMore</a>, <a href="#a840f6f02fc4d09a1139e6dda58bda416">use_begin</a>, <a href="#ac9af9e80bf058a9ab7fd8eec688442e8">uses</a> and <a href="#affbf163ecdb4d5e1582c6ce5474436f5">uses</a>.</p>

</div>
</div>

### use\_begin() {#a840f6f02fc4d09a1139e6dda58bda416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_use_iterator llvm::sandboxir::Value::use_begin ()</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="#af685aa3ea024631ed348071914df61c0">use_begin</a> and <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>.</p>

</div>
</div>

### use\_end() {#ac7990eceef38cd3c233dc0dc8c082ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_iterator llvm::sandboxir::Value::use_end ()</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="#a4705ee51ec0da1ba978f2353d2c47f27">Ctx</a> and <a href="#a7b479862be57f4448b155a225b5972ac">Use</a>.</p>


<p>Referenced by <a href="#abf8dc6457830695a7580727f3bca040e">hasNUses</a>, <a href="#a8d160c299df51820d73ff0f393334f8e">hasNUsesOrMore</a>, <a href="#a1cb5a1c99c5b0636bbf9ac81e0a78af0">use_end</a>, <a href="#ac9af9e80bf058a9ab7fd8eec688442e8">uses</a> and <a href="#affbf163ecdb4d5e1582c6ce5474436f5">uses</a>.</p>

</div>
</div>

### use\_end() {#a1cb5a1c99c5b0636bbf9ac81e0a78af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_use_iterator llvm::sandboxir::Value::use_end ()</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="#ac7990eceef38cd3c233dc0dc8c082ca0">use_end</a> and <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>.</p>

</div>
</div>

### user\_begin() {#af6e1ffac63581af9de82a4b2e37a3590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value::user_iterator llvm::sandboxir::Value::user_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>References <a href="#a38c437d9dcaefebe4efaf0edf00c45de">User</a> and <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a>.</p>


<p>Referenced by <a href="#a8642bd999889a386dc68d5e2ae7e6e2a">user_begin</a>, <a href="#aa5ba4e46404a59391af05ca6f0c9ce75">users</a> and <a href="#aa2e1eddb2449d8c488c0f62ebf3a3be1">users</a>.</p>

</div>
</div>

### user\_begin() {#a8642bd999889a386dc68d5e2ae7e6e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_user_iterator llvm::sandboxir::Value::user_begin ()</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="#af6e1ffac63581af9de82a4b2e37a3590">user_begin</a> and <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>.</p>

</div>
</div>

### user\_end() {#a57bcba1ffad304a316a7dbffdaa55469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">user_iterator llvm::sandboxir::Value::user_end ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="#a4705ee51ec0da1ba978f2353d2c47f27">Ctx</a> and <a href="#a7b479862be57f4448b155a225b5972ac">Use</a>.</p>


<p>Referenced by <a href="#ac9e9a5ba8949bc8dc81470e0063b1bad">user_end</a>, <a href="#aa5ba4e46404a59391af05ca6f0c9ce75">users</a> and <a href="#aa2e1eddb2449d8c488c0f62ebf3a3be1">users</a>.</p>

</div>
</div>

### user\_end() {#ac9e9a5ba8949bc8dc81470e0063b1bad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_user_iterator llvm::sandboxir::Value::user_end ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="#a57bcba1ffad304a316a7dbffdaa55469">user_end</a> and <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>.</p>

</div>
</div>

### users() {#aa5ba4e46404a59391af05ca6f0c9ce75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; user_iterator &gt; llvm::sandboxir::Value::users ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#af6e1ffac63581af9de82a4b2e37a3590">user_begin</a> and <a href="#a57bcba1ffad304a316a7dbffdaa55469">user_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#af1e3ef49a5ed6b995c51268e486c4854">llvm::sandboxir::Instruction::eraseFromParent</a>.</p>

</div>
</div>

### users() {#aa2e1eddb2449d8c488c0f62ebf3a3be1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_user_iterator &gt; llvm::sandboxir::Value::users ()</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#af6e1ffac63581af9de82a4b2e37a3590">user_begin</a> and <a href="#a57bcba1ffad304a316a7dbffdaa55469">user_end</a>.</p>

</div>
</div>

### uses() {#ac9af9e80bf058a9ab7fd8eec688442e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; use_iterator &gt; llvm::sandboxir::Value::uses ()</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#af685aa3ea024631ed348071914df61c0">use_begin</a> and <a href="#ac7990eceef38cd3c233dc0dc8c082ca0">use_end</a>.</p>


<p>Referenced by <a href="#a357dd7c60a0ea6b2e6c7ecdf9c9923d1">replaceAllUsesWith</a>.</p>

</div>
</div>

### uses() {#affbf163ecdb4d5e1582c6ce5474436f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_use_iterator &gt; llvm::sandboxir::Value::uses ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#af685aa3ea024631ed348071914df61c0">use_begin</a> and <a href="#ac7990eceef38cd3c233dc0dc8c082ca0">use_end</a>.</p>

</div>
</div>

### verify() {#a31d1ee1d16b05c2843090dbfb43357f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sandboxir::Value::verify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Should crash if there is something wrong with the instruction.</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### clearValue() {#aab67dfa80034880c5c77e5218c24c105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Value::clearValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="#a0c4530f3c64d8c2eafac20fb87105d8a">Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Ctx {#a4705ee51ec0da1ba978f2353d2c47f27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context&amp; llvm::sandboxir::Value::Ctx</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All values point to the context.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#a249e3556685c37af7a58055436dadbfe">llvm::sandboxir::SwitchInst::addCase</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#a0cacae4db3e4f90ffd8fafb01ade4ce3">llvm::sandboxir::CatchSwitchInst::addHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#ae3c21dcbfdf18433a9bb69131cda53e6">llvm::sandboxir::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#a60b365540bb2d07cbcebdba12039aed9">llvm::sandboxir::Function::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/binaryoperator/#a73974d2f921b57660f1f4e794edf5cfc">llvm::sandboxir::BinaryOperator::BinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#aa6dd0f10f258fb2f51d0360330b3e964">llvm::sandboxir::PHINode::block_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a18e01d4e36f1c4682a37f3175ab6f816">llvm::sandboxir::PHINode::block_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#ad6d818c130a52c32ca2522c25844b151">llvm::sandboxir::CmpInst::CmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a3e70e997a39fb055c1bfab8f994be745">llvm::sandboxir::ShuffleVectorInst::commute</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregate/#af434bf46616dca8d289a74439378f4ff">llvm::sandboxir::ConstantAggregate::ConstantAggregate</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::AllocaInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/binaryoperator/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::BinaryOperator::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbrinst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::CallBrInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchpadinst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::CatchPadInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::CatchReturnInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::CatchSwitchInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanuppadinst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::CleanupPadInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::CleanupReturnInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::ConstantFP::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constanttokennone/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::ConstantTokenNone::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractelementinst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::ExtractElementInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::GetElementPtrInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::GlobalVariable::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertelementinst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::InsertElementInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::InvokeInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/landingpadinst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::LandingPadInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/resumeinst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::ResumeInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/returninst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::ReturnInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::ShuffleVectorInst::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a75f5310b6450a63430608a501bad513e">llvm::sandboxir::Instruction::copyFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#aeb07c11e1ea294e14fdf52b5a9df5ab6">llvm::sandboxir::AllocaInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#ab1859ab99d344b7ca30aaf240e5a8152">llvm::sandboxir::AtomicCmpXchgInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/binaryoperator/#a4a5c1bce78236d072e0b3597032f8ba7">llvm::sandboxir::BinaryOperator::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a4cec83421cd731c080d57c163d9f4e32">llvm::sandboxir::BranchInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a33be833bacd8efc3079465530cd10cea">llvm::sandboxir::BranchInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinst/#a9a5e242d5daa720bf3859f5f3cc2c727">llvm::sandboxir::CastInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinstimpl/#a8b9fe185482e6a7dc4831a29034df896">llvm::sandboxir::CastInstImpl&lt; Op &gt;::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchpadinst/#a75c9c2542ec4d001768526e388e69046">llvm::sandboxir::CatchPadInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#af24319ada8f3c7c23b7df713ba0e2a87">llvm::sandboxir::CatchReturnInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#a8a9d991dc43cfdfd526da5f8d751b224">llvm::sandboxir::CatchSwitchInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanuppadinst/#a7dd404473a05c6b8da7292d8104e992e">llvm::sandboxir::CleanupPadInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a80a29c6e8a935d440a3dc301f3a95dec">llvm::sandboxir::CmpInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractelementinst/#a78edbee00666542bdbc55325cfc95989">llvm::sandboxir::ExtractElementInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#a2990a7387ba4a5f3171b1a69e26cc13c">llvm::sandboxir::ExtractValueInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fenceinst/#a34270559483708ab9ce155c3d5fd7dd8">llvm::sandboxir::FenceInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/freezeinst/#a4a5d9bfe82a9ebba80ef11450bc29712">llvm::sandboxir::FreezeInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#af9e525905347a63733a094e254637234">llvm::sandboxir::GetElementPtrInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertelementinst/#a79d27417580c31f71d7c622c25f11e41">llvm::sandboxir::InsertElementInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertvalueinst/#ac607a611cf8569b74436ab4d7c305ff6">llvm::sandboxir::InsertValueInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst/#a58be6f9d5ec9cd6dae7bd79e196fb837">llvm::sandboxir::InvokeInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/landingpadinst/#afc9de175121e1dffd8a92fb8fea3c431">llvm::sandboxir::LandingPadInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/loadinst/#a1cb42d07d84dbb3ecb28f3ddb2633d9c">llvm::sandboxir::LoadInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/loadinst/#a3628afe685d8a10c3cff51b99279b75a">llvm::sandboxir::LoadInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#aae2fdd8f8ba1bcb18f0e3db689b69af9">llvm::sandboxir::PHINode::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/resumeinst/#a7b32dc17314ff5a46f8c57d7e0f99d79">llvm::sandboxir::ResumeInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/returninst/#a2f02b43426bb78a483a386e070ffbeeb">llvm::sandboxir::ReturnInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#ab162771ca7877c597181850f69bd208c">llvm::sandboxir::ShuffleVectorInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a4ca5925f8d91859a70ccb210b60aac65">llvm::sandboxir::ShuffleVectorInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst/#aa068e56030623495d1a0e9a09bf03fce">llvm::sandboxir::StoreInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst/#a86a911977ed8c04779ec3620271741a0">llvm::sandboxir::StoreInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#a0dae977c12ac6dc276da492629131753">llvm::sandboxir::SwitchInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unaryoperator/#abe81373dd5b903ef9c5740a5522307ff">llvm::sandboxir::UnaryOperator::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unreachableinst/#a0b29309e292ee4061d393ac113b14002">llvm::sandboxir::UnreachableInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vaarginst/#a5d1c7bb253b724115ad196d5942a064a">llvm::sandboxir::VAArgInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a93bc41b0128d7419dda058540bad61fb">llvm::sandboxir::CmpInst::createCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a781d2ab0a52d398b5f6c1a76d8c979ae">llvm::sandboxir::CmpInst::createWithCopiedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unaryoperator/#a6e8a2edd1df04ac5d65c762443eb20f5">llvm::sandboxir::UnaryOperator::createWithCopiedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#a64a5890e1a9e8383a8ec32c06f52fee3">llvm::sandboxir::Function::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#aff295bbd03c1b8177ec8c511467f3147">llvm::sandboxir::Function::end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#ae75fb63d6a6fb2e812148dc01fb501fc">llvm::sandboxir::SwitchInst::findCaseDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantarray/#a65cdb8a376b0aa1971e7e25a558435f8">llvm::sandboxir::ConstantArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#a08d9e2a7a8570dacb3398c95070096a6">llvm::sandboxir::ConstantFP::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#ae9cd3d7b1f348889c449b71b556298e7">llvm::sandboxir::ConstantInt::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantstruct/#a00fe72b32bd949660ddf5975a54231ac">llvm::sandboxir::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constanttokennone/#a93604a7462c36d8a5dbac0fd2afec9d9">llvm::sandboxir::ConstantTokenNone::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ab33e3a5b76de46d7d941f95c2679d6e3">llvm::sandboxir::Instruction::getAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a21c4bebcfc399209abbf62ccee053836">llvm::sandboxir::ConstantPtrAuth::getAddrDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias/#a158155f07514ae91ba76e5af2299527f">llvm::sandboxir::GlobalAlias::getAliasee</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias/#aabb0a4b74885241d72ea92604c3846c3">llvm::sandboxir::GlobalAlias::getAliaseeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a172b5862cbc38a02f448b7269351ef1f">llvm::sandboxir::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantstruct/#a1ce940845363db412b77da9cc3a7ec02">llvm::sandboxir::ConstantStruct::getAnon</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#a116758aec88a7f3195e474d666f2346e">llvm::sandboxir::Function::getArg</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/funcletpadinst/#a2645652b8c4b4b624b306900bc0e15d8">llvm::sandboxir::FuncletPadInst::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a56cdb1f63cf7b4d9339ea064a481ea7a">llvm::sandboxir::AllocaInst::getArraySize</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/blockaddress/#ac44be2ae75307f9aaeba771b6a2e320a">llvm::sandboxir::BlockAddress::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a552321c1d57798780e076e5a812c4bdf">llvm::sandboxir::ConstantInt::getBool</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a0eae402a37659dae2cf3aaf2e250ab7e">llvm::sandboxir::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#aa4416399caf450992e3e329955ecc303">llvm::sandboxir::CallBase::getCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a0f2dc3be47f89fbc1bdb308271fbb7c7">llvm::sandboxir::CallBase::getCalledOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a590805eb44cbd8337136425689452bdf">llvm::sandboxir::CallBase::getCaller</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#a12e338fc4ae8090d42bbea771505e61d">llvm::sandboxir::CatchReturnInst::getCatchPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchpadinst/#a9c5cca636289e446988e0da25c6559cc">llvm::sandboxir::CatchPadInst::getCatchSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#ad71d28c57db29e139745be32c3efef0f">llvm::sandboxir::CatchReturnInst::getCatchSwitchParentPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#a14169e176d3fefeaaf628c715f93bd6f">llvm::sandboxir::CleanupReturnInst::getCleanupPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#aaa7e667cd574bd275eff8bff4d8abdc7">llvm::sandboxir::AtomicCmpXchgInst::getCompareOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a0e989fa9eaf07e9240a5fcd78a188cb7">llvm::sandboxir::BranchInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#aa37737c6c26bcb882570fdaa57f3eaad">llvm::sandboxir::SwitchInst::getCondition</a>, <a href="#a85254176569bc8ee70fff75a9ff59f11">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#a8a456d10b590d146fb7231e1f7b3a44b">llvm::sandboxir::SwitchInst::getDefaultDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinst/#abbb856af6cf50a8d5eabe0938a8fec79">llvm::sandboxir::CastInst::getDestTy</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a23adfa241719c95a093473788bdff957">llvm::sandboxir::ConstantPtrAuth::getDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#ab5ee9034a6c41042c742b5674dbebac3">llvm::sandboxir::ConstantAggregateZero::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#a2e11290cf6eea82cf401adcf53724c36">llvm::sandboxir::ConstantAggregateZero::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#af6cfed2db90bcf25e57b30fef9e46254">llvm::sandboxir::PoisonValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#ab0fc255a67159d66e21a7b6e6ccd6d5d">llvm::sandboxir::PoisonValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#a433b843f13b28bdad0e0eb4f25f74dbd">llvm::sandboxir::UndefValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#aa579bf81b62f5de4e7b7904b93bed865">llvm::sandboxir::UndefValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a749947b601984956fb6ecbcaf40d878f">llvm::sandboxir::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/blockaddress/#aad1d6f553ef70e8fd63624d571e004a9">llvm::sandboxir::BlockAddress::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a1028f775dbfc9831acd142c24e69af10">llvm::sandboxir::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#a533e8a1b992a8f5b16e10908d1984d5e">llvm::sandboxir::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dsolocalequivalent/#a7c1d3a13ba97555fd9ea2b7cd3c4b516">llvm::sandboxir::DSOLocalEquivalent::getGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#a8364be8699ef13a08e1cc737d1a462e4">llvm::sandboxir::NoCFIValue::getGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#ad0d853291c96744ba3dfc2378ee79beb">llvm::sandboxir::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#acd1070a3eee499375b94cf02540339dc">llvm::sandboxir::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a5558ae8ab9a8f38e161ae8b5357c6b37">llvm::sandboxir::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#aded123faf2751b821c2df84a6ac89b78">llvm::sandboxir::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbrinst/#a16051f2944e19b0677756fa6a33cb114">llvm::sandboxir::CallBrInst::getIndirectDestLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbrinst/#a03e31b2a1e5a8deac89f0d539d7c8402">llvm::sandboxir::CallBrInst::getIndirectDestLabelUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a0820af56c48b84fcccb7dda23ff2d5f1">llvm::sandboxir::GlobalVariable::getInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a8926bd3f2d482439d11aaecd3eda70a3">llvm::sandboxir::ConstantInt::getIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a591b79aa413daec436776f4f7b5d566c">llvm::sandboxir::Instruction::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a91edf59855155dc0d8109f93a1d58d92">llvm::sandboxir::ConstantPtrAuth::getKey</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#ab0185a31c3cb2e873b3cf08093d18537">llvm::sandboxir::Utils::getMemInstructionBase</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#af14cae129a6f12f6838fd965b032273c">llvm::sandboxir::AtomicCmpXchgInst::getNewValOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst/#acc71e7e3e270414cfa0ee3b711cb8c6e">llvm::sandboxir::InvokeInst::getNormalDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a8014de6610ee432b675e3819e011acb2">llvm::sandboxir::User::getOperandUseDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#a2dab2e91c26b67cdf679bbdf6bc748b7">llvm::sandboxir::Function::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#afba1279eafd7cf7b6ef9681b6f28283f">llvm::sandboxir::Instruction::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#ae51822bea9cc9878d8aac3145b349297">llvm::sandboxir::CatchSwitchInst::getParentPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a1ab92d211e4a27d51621120afb2920cf">llvm::sandboxir::ConstantPtrAuth::getPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a2631474f544ed47925fa080544135d6b">llvm::sandboxir::AtomicCmpXchgInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#ab33e913f39a9ef2a4f2ac236f41d5a04">llvm::sandboxir::AtomicRMWInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#af1695c8542907cb759908ceefea9483e">llvm::sandboxir::GetElementPtrInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/loadinst/#aa222683051244b2e2a6c56cb7fb1b3b4">llvm::sandboxir::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst/#ab7c62000d821c42fb80a26829969013e">llvm::sandboxir::StoreInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vaarginst/#a1661dc6977ace70ebc3f1b1cf45c98e5">llvm::sandboxir::VAArgInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#ab2f136dbb9bd21f6db488ad4d0e397fb">llvm::sandboxir::GetElementPtrInst::getPointerOperandType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc/#a4cd835207d936ca42937cd3b88cb1e98">llvm::sandboxir::GlobalIFunc::getResolver</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc/#a847a3a7ab8736327e2abc6a1a0b59e4a">llvm::sandboxir::GlobalIFunc::getResolverFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#a89980d8f2a362c063a72c27d87ea1d2f">llvm::sandboxir::GetElementPtrInst::getResultElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/returninst/#ae939011431c2a603bf8d351c75c9f17e">llvm::sandboxir::ReturnInst::getReturnValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#a49c1a042d7191adffd285d8e763169ff">llvm::sandboxir::ConstantAggregateZero::getSequentialElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#a9fd2120587f4f077d196cc9e20f86dc2">llvm::sandboxir::PoisonValue::getSequentialElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#aba7f2f01ded2567a746cfe9cf79fa993">llvm::sandboxir::UndefValue::getSequentialElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a149a0f4e491d68dd8d10aaf94cedabb4">llvm::sandboxir::ShuffleVectorInst::getShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#ac72ebce2f0fcc49c00b52eb9350640cc">llvm::sandboxir::GetElementPtrInst::getSourceElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinst/#a826ff61b0f5f8eeeb3c5a8581bc904b4">llvm::sandboxir::CastInst::getSrcTy</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#a800d9894402db8885f0a5c3c274c1002">llvm::sandboxir::ConstantAggregateZero::getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#aa2fe583dc4d7205996e692bd8582e33a">llvm::sandboxir::PoisonValue::getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#abde39ab11a9bd74a6219aad3b0044f1f">llvm::sandboxir::UndefValue::getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#a41660d810e3c9d23c360f2f39394d080">llvm::sandboxir::CatchReturnInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#a3085bafbd679d8c31e354c0d1eea4a6a">llvm::sandboxir::SwitchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a1d84ba505949537892d7e3ef492fc26c">llvm::sandboxir::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a888f265095c39e440ed5c83a33be6073">llvm::sandboxir::AllocaInst::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantarray/#acdb9fe29c2c8a7a458631d5a8a108f05">llvm::sandboxir::ConstantArray::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantpointernull/#a53272380640bdd570904df3b290f39d4">llvm::sandboxir::ConstantPointerNull::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#a20862401d26b48d85c4370b213dfcdab">llvm::sandboxir::NoCFIValue::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a09cb3d33809f47986e5023a1b50cdcce">llvm::sandboxir::ShuffleVectorInst::getType</a>, <a href="#a5f93ad2195368bba2202c3cc75e7cc1d">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantstruct/#ad3de023aeaed4f2c7173566c0031997a">llvm::sandboxir::ConstantStruct::getTypeForElements</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#ae26eae3468dd2e4b2542820f3374e62a">llvm::sandboxir::CatchSwitchInst::getUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#aa5268ec1ee96ab20496d4d3eabe15336">llvm::sandboxir::CleanupReturnInst::getUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst/#a0dd89a17daa11d1dd559bdd57d6f464d">llvm::sandboxir::InvokeInst::getUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#a0a63db0fc18f1ac4017f8e262fc9996f">llvm::sandboxir::AtomicRMWInst::getValOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/resumeinst/#acff16dfa912fae89a9b9a5e5955fc8a3">llvm::sandboxir::ResumeInst::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst/#ad118cf1c9e2393aea0594b295480bcfb">llvm::sandboxir::StoreInst::getValueOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractelementinst/#a7ad888b66278c533a367650a3bb01d0f">llvm::sandboxir::ExtractElementInst::getVectorOperandType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a0d9e5bd9aa6cd4493d05bb59961a0334">llvm::sandboxir::ConstantPtrAuth::getWithSameSchema</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#afa844660babce871494fdbbcfbfaf0a5">llvm::sandboxir::GlobalObject::GlobalObject</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#af270a95bbd7605a93187b080fdf053b8">llvm::sandboxir::GlobalValue::GlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a04e73b012a325ed386efc0035be7c6d9">llvm::sandboxir::PHINode::hasConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#aeda4df10362479b2eb3d6b12f895401f">llvm::sandboxir::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a8b52fc13d6793d152a3d9dc210f5156e">llvm::sandboxir::Instruction::insertInto</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callinst/#a2547a071ebd5adabda1c797f6e914674">llvm::sandboxir::CallInst::IntrinsicInst</a>, <a href="#a7e5bdab1596d88c89ead437cfa80e382">LLVMOpUserItToSBTy</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#afa6137fa4de3e04d7bdae0144bbd9905">llvm::sandboxir::SwitchInst::removeCase</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#adff189c114a625d2837de30bcabe8099">llvm::sandboxir::Instruction::removeFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a0b2bc62c021fac7a3b7cb98ba3654ff3">llvm::sandboxir::PHINode::removeIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#abd01234117775c7ff32e73f0134b7e34">llvm::sandboxir::PHINode::removeIncomingValue</a>, <a href="#a357dd7c60a0ea6b2e6c7ecdf9c9923d1">replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias/#ab1309f79334a271b4fa4d216dcc5e2f2">llvm::sandboxir::GlobalAlias::setAliasee</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#ae641a2be8d31f3518b04301c98e094d5">llvm::sandboxir::AllocaInst::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#aa13895fba8ebecdd0ca77836d3750caa">llvm::sandboxir::AtomicCmpXchgInst::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#afea0095f9b8d24d9052e472b965f1542">llvm::sandboxir::AtomicRMWInst::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#a83748f9098fea276898c0741262a66e4">llvm::sandboxir::GlobalObject::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a30ebcd2d2e510843030053dbd00b7031">llvm::sandboxir::AllocaInst::setAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/funcletpadinst/#a82cc2d68ad4f4f4d79bbbd9c8a755ada">llvm::sandboxir::FuncletPadInst::setArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#a97678deb11364fbd028c6a437dacbf2d">llvm::sandboxir::CatchReturnInst::setCatchPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/landingpadinst/#a39d50f83ff76d3a431d4c896aafb10d5">llvm::sandboxir::LandingPadInst::setCleanup</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#ade76bff1f6821467269e0dd985baaa5d">llvm::sandboxir::CleanupReturnInst::setCleanupPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#ade5dafda9b8e251beab93f9154736fc1">llvm::sandboxir::SwitchInst::setCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#aa6ed211b74ca9002d55c5b881ae7d088">llvm::sandboxir::GlobalVariable::setConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#a47621555866da42fa41c71023218cc3b">llvm::sandboxir::SwitchInst::setDefaultDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a6ffd1c1a8f379a0462f7ac67eb95d98e">llvm::sandboxir::GlobalVariable::setExternallyInitialized</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a98bb2475710edf44add1383dfc8a4d4b">llvm::sandboxir::AtomicCmpXchgInst::setFailureOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a607f7549e870fb7bf03c0bdeddcedd97">llvm::sandboxir::Instruction::setFast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a076ed6abb9853c90a0dbdd0af7930cb7">llvm::sandboxir::Instruction::setFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#aefff93ab9c3b3d05c19d72362bcd0c90">llvm::sandboxir::GlobalObject::setGlobalObjectSubClassData</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#af57a79465abb3553060726acc4103006">llvm::sandboxir::Instruction::setHasAllowReciprocal</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a6bd41098e8a68ed910f903bdf882371e">llvm::sandboxir::Instruction::setHasApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#afa823f9fcdbe6f11fed742dd95bc748d">llvm::sandboxir::Instruction::setHasNoInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a70cc35150e6169c05919063aa3f9486d">llvm::sandboxir::Instruction::setHasNoNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a2567be2fc35c52f127cf6c8c90c2a814">llvm::sandboxir::Instruction::setHasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a88f79981a5c0a0072e6d8252ccf831ac">llvm::sandboxir::Instruction::setHasNoSignedZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a50736b51464202aa9a12d55ee4a1ac4d">llvm::sandboxir::Instruction::setHasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a8fd48c955a259895ca147ea9f2cd6d64">llvm::sandboxir::PHINode::setIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#ac9ac79e5a1a12af4be6ac3cad1e079e0">llvm::sandboxir::PHINode::setIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a9addc56ed8318970567e31311085b0e6">llvm::sandboxir::GlobalVariable::setInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a034571bc982742eb2cb2d135dee93eb2">llvm::sandboxir::Instruction::setInsertPos</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/possiblydisjointinst/#ae16106c1e614b55000270a227e981fd8">llvm::sandboxir::PossiblyDisjointInst::setIsDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a3f5937211d8aa294dcb81015f012c199">llvm::sandboxir::Instruction::setIsExact</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/possiblynonneginst/#ab6e8d142dc2d6dececc8a6212825645e">llvm::sandboxir::PossiblyNonNegInst::setNonNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a54abb07f9d20e6d5344ce647621f85a8">llvm::sandboxir::User::setOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fenceinst/#a4c42d562e2e9c79bcb1c77c41cfeff11">llvm::sandboxir::FenceInst::setOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#a449c45bfb9ef1e11fe8a5f0fd8dd00da">llvm::sandboxir::CatchSwitchInst::setParentPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a82375fc602bbbdc421f2ae663b595a43">llvm::sandboxir::CmpInst::setPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc/#a70ae64460ad95cab729c96a76d10f14a">llvm::sandboxir::GlobalIFunc::setResolver</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#af802ad5aa5721e72eeab21959b526c9d">llvm::sandboxir::GlobalObject::setSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#abc00dfadd75bc8833db0eccafcfda661">llvm::sandboxir::ShuffleVectorInst::setShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#a4f52d7a4f188d9c95c14e8da6b3f18d2">llvm::sandboxir::CatchReturnInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#ab5196054d0436a16bfc15c8ea9101d8e">llvm::sandboxir::SwitchInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a4db9cec9b5710b9405a70f52212814a7">llvm::sandboxir::AtomicCmpXchgInst::setSuccessOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#ada13bfda99313325ef85d2b2d613c3f8">llvm::sandboxir::AtomicCmpXchgInst::setSyncScopeID</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#a2098c7a23f7e052b0009f5d7a6cdec3c">llvm::sandboxir::AtomicRMWInst::setSyncScopeID</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fenceinst/#aebd434b15ea60ed7298f3805110cd169">llvm::sandboxir::FenceInst::setSyncScopeID</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#a6850150c4508a12b540a3f3497498db5">llvm::sandboxir::GlobalValue::setUnnamedAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#a74f759b54940d0de3b83a3310f0364d4">llvm::sandboxir::CatchSwitchInst::setUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#a3527a0276c2133717040ef9452ec7ce8">llvm::sandboxir::CleanupReturnInst::setUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a92d20c9a65a5af8df6f4cfad584270c3">llvm::sandboxir::AllocaInst::setUsedWithInAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#af44ac69b033b2d5319c8d229eb22b15c">llvm::sandboxir::GlobalValue::setVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a8158695531a595cdf673438b3097338b">llvm::sandboxir::AtomicCmpXchgInst::setVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a7d59ad8f003b26a0c532da138233849d">llvm::sandboxir::AtomicCmpXchgInst::setWeak</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a2f934ebbafcd336726a91d636c2cf853">llvm::sandboxir::BranchInst::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a611d4d9356dd291578cd369630ef3907">llvm::sandboxir::BranchInst::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fcmpinst/#a5c09f89b0fd13cf2405d0af211b888bd">llvm::sandboxir::FCmpInst::swapOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/icmpinst/#a9e604facb59bb8a1337ee2323708303b">llvm::sandboxir::ICmpInst::swapOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/selectinst/#a462041a4b8235d7b12124fca65b8640c">llvm::sandboxir::SelectInst::swapValues</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unaryinstruction/#a22f817d363c16cf5b2189f81c3d3a804">llvm::sandboxir::UnaryInstruction::UnaryInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#a8653b033bb10cd3f8efec74d04a9d11f">llvm::sandboxir::UndefValue::UndefValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#a96a4305f15f7d7f1c7f082a0da873d99">llvm::sandboxir::UndefValue::UndefValue</a>, <a href="#af685aa3ea024631ed348071914df61c0">use_begin</a>, <a href="#ac7990eceef38cd3c233dc0dc8c082ca0">use_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#aed798e20a38c7c32351becc11f61f755">llvm::sandboxir::User::User</a>, <a href="#a57bcba1ffad304a316a7dbffdaa55469">user_end</a>, <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a29a530f0bf7efe84cbba172fac79970d">llvm::sandboxir::User::verifyUserOfLLVMUse</a>.</p>

</div>
</div>

### SubclassID {#a565e36982a32c997c13e56b5c42d9b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassID llvm::sandboxir::Value::SubclassID</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For isa/dyn_cast.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="#a1565aa2d231b44e393af53deb7de04c2">dumpCommonHeader</a>, <a href="#a294250e6721c14a9a8d934220e6523d0">dumpCommonSuffix</a>, <a href="#a27b9af008c6420f3340805e50297f9fb">getSubclassID</a>, <a href="#a7e5bdab1596d88c89ead437cfa80e382">LLVMOpUserItToSBTy</a> and <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>.</p>

</div>
</div>

### UID {#abf8f9533cdeeefaf520a852fa9406d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::Value::UID</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> used for forming the name (used for debugging).</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="#aab622b4257690e722b1c7a988b2c800d">getUid</a> and <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>.</p>

</div>
</div>

### Val {#a0c4530f3c64d8c2eafac20fb87105d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Value* llvm::sandboxir::Value::Val = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The LLVM <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> that corresponds to this SandboxIR <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a>.</p>


<p>NOTE: Some sandboxir Instructions, like Packs, may include more than one value and in these cases <span class="doxyComputerOutput">Val</span> points to the last instruction in program order.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#af1b18cc16d4a3ab82763dbd1250bfebe">llvm::sandboxir::GetElementPtrInst::accumulateConstantOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#a249e3556685c37af7a58055436dadbfe">llvm::sandboxir::SwitchInst::addCase</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#a0cacae4db3e4f90ffd8fafb01ade4ce3">llvm::sandboxir::CatchSwitchInst::addHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#ae3c21dcbfdf18433a9bb69131cda53e6">llvm::sandboxir::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/selectinst/#a1172e5ba927c8eba63a68fd1083e95c5">llvm::sandboxir::SelectInst::areInvalidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#ac2e44a6a0269a41d6b21df599acb3f34">llvm::sandboxir::Function::arg_empty</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/funcletpadinst/#a4893fbd2ed1bf17639ac536b6da25308">llvm::sandboxir::FuncletPadInst::arg_size</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#aa9016c2b90ec3a942df7808ccbb92ba9">llvm::sandboxir::Function::arg_size</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#a60b365540bb2d07cbcebdba12039aed9">llvm::sandboxir::Function::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#aa6dd0f10f258fb2f51d0360330b3e964">llvm::sandboxir::PHINode::block_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a18e01d4e36f1c4682a37f3175ab6f816">llvm::sandboxir::PHINode::block_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#afc1f63779a85d063c9a9e02fb87fa153">llvm::sandboxir::GlobalObject::canIncreaseAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a075f39a7a4718844c3f0e0930715414d">llvm::sandboxir::ShuffleVectorInst::changesLength</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/operator/#a2ed51fc69c30845a5746d526f5abaecb">llvm::sandboxir::Operator::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/overflowingbinaryoperator/#a0d34a5eea3339607eb193ee23a7c6784">llvm::sandboxir::OverflowingBinaryOperator::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/overflowingbinaryoperator/#acbbd464d9cfe5b82d76c7447f09f6166">llvm::sandboxir::OverflowingBinaryOperator::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/overflowingbinaryoperator/#a3964c31047e72713d916ee395a092928">llvm::sandboxir::OverflowingBinaryOperator::classof</a>, <a href="#aab67dfa80034880c5c77e5218c24c105">clearValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a2c89a7c3adbeaf3cc5d02a41401801fb">llvm::Instruction::cloneDebugInfoFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ad1664de8206ba30fc8d13a01850f42db">llvm::sandboxir::Instruction::comesBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a3e70e997a39fb055c1bfab8f994be745">llvm::sandboxir::ShuffleVectorInst::commute</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#aeb07c11e1ea294e14fdf52b5a9df5ab6">llvm::sandboxir::AllocaInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#a1be5545f039ccf065d67ff893358830c">llvm::sandboxir::AtomicRMWInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinst/#a9a5e242d5daa720bf3859f5f3cc2c727">llvm::sandboxir::CastInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchpadinst/#a75c9c2542ec4d001768526e388e69046">llvm::sandboxir::CatchPadInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#af24319ada8f3c7c23b7df713ba0e2a87">llvm::sandboxir::CatchReturnInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a80a29c6e8a935d440a3dc301f3a95dec">llvm::sandboxir::CmpInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractelementinst/#a78edbee00666542bdbc55325cfc95989">llvm::sandboxir::ExtractElementInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#a2990a7387ba4a5f3171b1a69e26cc13c">llvm::sandboxir::ExtractValueInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertelementinst/#a79d27417580c31f71d7c622c25f11e41">llvm::sandboxir::InsertElementInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertvalueinst/#ac607a611cf8569b74436ab4d7c305ff6">llvm::sandboxir::InsertValueInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/resumeinst/#a7b32dc17314ff5a46f8c57d7e0f99d79">llvm::sandboxir::ResumeInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#ab162771ca7877c597181850f69bd208c">llvm::sandboxir::ShuffleVectorInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a4ca5925f8d91859a70ccb210b60aac65">llvm::sandboxir::ShuffleVectorInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unaryoperator/#abe81373dd5b903ef9c5740a5522307ff">llvm::sandboxir::UnaryOperator::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unaryoperator/#a6e8a2edd1df04ac5d65c762443eb20f5">llvm::sandboxir::UnaryOperator::createWithCopiedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a57f89d7b128f61512d8b9d321efdd7db">llvm::sandboxir::CallBase::data_operands_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a5337873da2a75ae20dcc0648c250567d">llvm::sandboxir::CallBase::data_operands_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#a153c49a99fed915f696499cabdd06816">llvm::sandboxir::SwitchInst::defaultDestUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a71583800b3bd19509d34cb223bef0aab">llvm::Instruction::dropOneDbgRecord</a>, <a href="#a119c7591f5a3c513ebda9f69414f786c">dumpCommonFooter</a>, <a href="#ac886f508d3441b842e387f062899f3a8">dumpCommonPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#a94c0db67b995b354f7ac1ff83250e57b">llvm::sandboxir::Function::dumpNameAndArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#a64a5890e1a9e8383a8ec32c06f52fee3">llvm::sandboxir::Function::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#aff295bbd03c1b8177ec8c511467f3147">llvm::sandboxir::Function::end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a9e4ce57aa4a42de3b4eeea3877d14b90">llvm::sandboxir::ConstantInt::equalsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#ae75fb63d6a6fb2e812148dc01fb501fc">llvm::sandboxir::SwitchInst::findCaseDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#adc0559b3ce05ac7f5273dfd241e99071">llvm::sandboxir::ConstantPtrAuth::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dsolocalequivalent/#a66f628a21e67b68d6ae93a9f80bb4067">llvm::sandboxir::DSOLocalEquivalent::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#afa0e3ddd6a06a4f5de4142baad208a38">llvm::sandboxir::NoCFIValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ab33e3a5b76de46d7d941f95c2679d6e3">llvm::sandboxir::Instruction::getAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a21c4bebcfc399209abbf62ccee053836">llvm::sandboxir::ConstantPtrAuth::getAddrDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a645e01e8c9553eb4beb7202344581cd0">llvm::sandboxir::AllocaInst::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#a00fc866209bc3905d81a1ea58862dfc3">llvm::sandboxir::GetElementPtrInst::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#a949b1caf23004048ac27ab2d5bebaee6">llvm::sandboxir::GlobalValue::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias/#a158155f07514ae91ba76e5af2299527f">llvm::sandboxir::GlobalAlias::getAliasee</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias/#aabb0a4b74885241d72ea92604c3846c3">llvm::sandboxir::GlobalAlias::getAliaseeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a7b4b2321950130a77bb094d49a34f5d9">llvm::sandboxir::AllocaInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#af4de1acfd7925c50cd491befe344db35">llvm::sandboxir::AtomicCmpXchgInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#a742dd8cb7a73bf3da45f82bd9de3ea59">llvm::sandboxir::AtomicRMWInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#a3bb0021dedfcf4772e6c83806cfb40e2">llvm::sandboxir::GlobalObject::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/loadinst/#a9bd03c776cc8a9c4620d107d4084770e">llvm::sandboxir::LoadInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst/#a34dbce8be7dfe5a5721471c37e01e023">llvm::sandboxir::StoreInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#af66e286b8ec4624a78705c703340aeb6">llvm::sandboxir::GlobalObject::getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#af5c879521832541d02584c533df0a6ce">llvm::sandboxir::ConstantInt::getAlignValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a172b5862cbc38a02f448b7269351ef1f">llvm::sandboxir::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#ae31edda972b4f0e80525487e5e5af746">llvm::sandboxir::AllocaInst::getAllocationSize</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a496cbedfb5cfd738413e8bca591651c9">llvm::sandboxir::AllocaInst::getAllocationSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#a116758aec88a7f3195e474d666f2346e">llvm::sandboxir::Function::getArg</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/funcletpadinst/#a2645652b8c4b4b624b306900bc0e15d8">llvm::sandboxir::FuncletPadInst::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a4cfe6ac7275f700e905eb8ef38062e60">llvm::sandboxir::CallBase::getArgOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a56cdb1f63cf7b4d9339ea064a481ea7a">llvm::sandboxir::AllocaInst::getArraySize</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a0e875bf05a725c8925549f5843ca837c">llvm::sandboxir::GlobalVariable::getAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a4b4296da74e6fc9d6b0620f0aca07ed0">llvm::sandboxir::GlobalVariable::getAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a0a7e0ab05e7dbe073df42d1624be5fae">llvm::sandboxir::GlobalVariable::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a1be64f21e2c5ee02a173131b7ec7f1d1">llvm::sandboxir::GlobalVariable::getAttributesAsList</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/blockaddress/#ac44be2ae75307f9aaeba771b6a2e320a">llvm::sandboxir::BlockAddress::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a0bd218c8383719a7f1239ba4311df02a">llvm::sandboxir::PHINode::getBasicBlockIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a2e9da7bb1309f5b9609859a42ba93bde">llvm::sandboxir::ConstantInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a0eae402a37659dae2cf3aaf2e250ab7e">llvm::sandboxir::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#aa4416399caf450992e3e329955ecc303">llvm::sandboxir::CallBase::getCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a0f2dc3be47f89fbc1bdb308271fbb7c7">llvm::sandboxir::CallBase::getCalledOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a590805eb44cbd8337136425689452bdf">llvm::sandboxir::CallBase::getCaller</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a08f42b0aa12e3c3a2240f84fb105b26f">llvm::sandboxir::CallBase::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#a12e338fc4ae8090d42bbea771505e61d">llvm::sandboxir::CatchReturnInst::getCatchPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchpadinst/#a9c5cca636289e446988e0da25c6559cc">llvm::sandboxir::CatchPadInst::getCatchSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#ad71d28c57db29e139745be32c3efef0f">llvm::sandboxir::CatchReturnInst::getCatchSwitchParentPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#a14169e176d3fefeaaf628c715f93bd6f">llvm::sandboxir::CleanupReturnInst::getCleanupPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#ac1d89d93236f32664fba204aede53046">llvm::sandboxir::GlobalVariable::getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a32ed1263207fe79c4b6464e332771fec">llvm::sandboxir::GlobalVariable::getCodeModelRaw</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#aaa7e667cd574bd275eff8bff4d8abdc7">llvm::sandboxir::AtomicCmpXchgInst::getCompareOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a0e989fa9eaf07e9240a5fcd78a188cb7">llvm::sandboxir::BranchInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#aa37737c6c26bcb882570fdaa57f3eaad">llvm::sandboxir::SwitchInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a0eaf012d5b315be6181de3e2105bda78">llvm::sandboxir::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a6061d5217b0727ead8ab32b662141f86">llvm::sandboxir::CallBase::getDataOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#a8a456d10b590d146fb7231e1f7b3a44b">llvm::sandboxir::SwitchInst::getDefaultDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinst/#abbb856af6cf50a8d5eabe0938a8fec79">llvm::sandboxir::CastInst::getDestTy</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a23adfa241719c95a093473788bdff957">llvm::sandboxir::ConstantPtrAuth::getDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#a199438d671ec3c302c5539666f422651">llvm::sandboxir::ConstantAggregateZero::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#ab5ee9034a6c41042c742b5674dbebac3">llvm::sandboxir::ConstantAggregateZero::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#a2e11290cf6eea82cf401adcf53724c36">llvm::sandboxir::ConstantAggregateZero::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#af6cfed2db90bcf25e57b30fef9e46254">llvm::sandboxir::PoisonValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#ab0fc255a67159d66e21a7b6e6ccd6d5d">llvm::sandboxir::PoisonValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#a433b843f13b28bdad0e0eb4f25f74dbd">llvm::sandboxir::UndefValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#aa579bf81b62f5de4e7b7904b93bed865">llvm::sandboxir::UndefValue::getElementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a9bec31d36dc55bf47fd3f39a74ffb48b">llvm::sandboxir::AtomicCmpXchgInst::getFailureOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#a241f7b618c994cbff19d4c94c588d8d6">llvm::sandboxir::FPMathOperator::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ac6829e8fb3c2cb98380bd16d6e05b7b1">llvm::sandboxir::Instruction::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#a6ad634a3f7f2727d73f3573f7b598a7e">llvm::sandboxir::FPMathOperator::getFPAccuracy</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/blockaddress/#aad1d6f553ef70e8fd63624d571e004a9">llvm::sandboxir::BlockAddress::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a1028f775dbfc9831acd142c24e69af10">llvm::sandboxir::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#a533e8a1b992a8f5b16e10908d1984d5e">llvm::sandboxir::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#a3798da296680ea3a376f49ec5e37264b">llvm::sandboxir::GlobalObject::getGlobalObjectSubClassData</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dsolocalequivalent/#a7c1d3a13ba97555fd9ea2b7cd3c4b516">llvm::sandboxir::DSOLocalEquivalent::getGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#a8364be8699ef13a08e1cc737d1a462e4">llvm::sandboxir::NoCFIValue::getGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#ad0d853291c96744ba3dfc2378ee79beb">llvm::sandboxir::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#acd1070a3eee499375b94cf02540339dc">llvm::sandboxir::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a5558ae8ab9a8f38e161ae8b5357c6b37">llvm::sandboxir::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#aded123faf2751b821c2df84a6ac89b78">llvm::sandboxir::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#a3ff81b5eec88f21330371593f8f49917">llvm::sandboxir::ExtractValueInst::getIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertvalueinst/#abcf4cd59cb6e8bd828b5c54598a3f8e7">llvm::sandboxir::InsertValueInst::getIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbrinst/#a16051f2944e19b0677756fa6a33cb114">llvm::sandboxir::CallBrInst::getIndirectDestLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbrinst/#a03e31b2a1e5a8deac89f0d539d7c8402">llvm::sandboxir::CallBrInst::getIndirectDestLabelUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a0820af56c48b84fcccb7dda23ff2d5f1">llvm::sandboxir::GlobalVariable::getInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a8926bd3f2d482439d11aaecd3eda70a3">llvm::sandboxir::ConstantInt::getIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#abb49166a67eba75920d4924c89259e50">llvm::sandboxir::CallBase::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/intrinsicinst/#aedbfafcfb6b3b70032dd5efddb667fe8">llvm::sandboxir::IntrinsicInst::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a591b79aa413daec436776f4f7b5d566c">llvm::sandboxir::Instruction::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a91edf59855155dc0d8109f93a1d58d92">llvm::sandboxir::ConstantPtrAuth::getKey</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#ad17d5b90a3ee8f5097a8beaa9eeb74c5">llvm::sandboxir::ConstantInt::getLimitedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#acf0879eed4456688b10e2231cc6b7ac6">llvm::sandboxir::ShuffleVectorInst::getMaskValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a3e226e4fbf6b948a6d822f1c4d0b5b3d">llvm::sandboxir::ConstantInt::getMaybeAlignValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a4b24bc93a32815963fb7b9438292026e">llvm::sandboxir::AtomicCmpXchgInst::getMergedOrdering</a>, <a href="#a2aee5e44d2f0c5681724b6ed1db93d19">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#af14cae129a6f12f6838fd965b032273c">llvm::sandboxir::AtomicCmpXchgInst::getNewValOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst/#acc71e7e3e270414cfa0ee3b711cb8c6e">llvm::sandboxir::InvokeInst::getNormalDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#a74486c31b8603c4bd451c883c91703c2">llvm::sandboxir::GetElementPtrInst::getNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/overflowingbinaryoperator/#aafe54fc3033e0c3c8c0690dcaa886479">llvm::sandboxir::OverflowingBinaryOperator::getNoWrapKind</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#ac796650af932c9ad98ca893d648ed1e0">llvm::sandboxir::SwitchInst::getNumCases</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/landingpadinst/#a680c0f024c2854d1c2f4b5d31d533489">llvm::sandboxir::LandingPadInst::getNumClauses</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#a99b41605ef97afce48c284c0231e56cb">llvm::sandboxir::UndefValue::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#ad923a5bd589e9c88afa3b1d24b7bd00f">llvm::sandboxir::CatchSwitchInst::getNumHandlers</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a5534d087b7f95c34e929308755079562">llvm::sandboxir::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#a11d78b11327a0d66d0eaa7c34aff37a9">llvm::sandboxir::ExtractValueInst::getNumIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#aa969066f4c398ee08eb5abd018ca7159">llvm::sandboxir::GetElementPtrInst::getNumIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertvalueinst/#a9cf827f01558dbf848d5ab1f97d99ab6">llvm::sandboxir::InsertValueInst::getNumIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbrinst/#a60afd77ed9c48a0109fdcfbe607a72d9">llvm::sandboxir::CallBrInst::getNumIndirectDests</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#ac600a3ffce54e05ca28e586af7a04831">llvm::sandboxir::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3287172f2d13af086e6d66364e8c6de3">llvm::Instruction::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbrinst/#aef6fe81d8d3f1375fd42f4e8a9cdbc75">llvm::sandboxir::CallBrInst::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#ad303e5e1ddd84c321d5c739f597f5660">llvm::sandboxir::CatchReturnInst::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#a9b3c8cef9c1e2924fb77f66700e9ebe5">llvm::sandboxir::CleanupReturnInst::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst/#a875d67cd503639ab4b60bb7f3d10f85f">llvm::sandboxir::InvokeInst::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/resumeinst/#ab1ef4bd42896f536297cdccfe6542bf4">llvm::sandboxir::ResumeInst::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#ad707e6ba132dc9be1ce4d3475f79e698">llvm::sandboxir::SwitchInst::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a65202b09251cfcaa8240280179951429">llvm::sandboxir::CallBase::getNumTotalBundleOperands</a>, <a href="#a395a45c11744d878a19d9db6315bc026">getNumUses</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5695ce86ca3854c8b1ad5020c3aa71ee">llvm::Instruction::getOpcodeName</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a8014de6610ee432b675e3819e011acb2">llvm::sandboxir::User::getOperandUseDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#a1dbfb421c0f22697469a79bb05cf08f0">llvm::sandboxir::AtomicRMWInst::getOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#aa05aa3c99d5380535d1f538b960fb139">llvm::sandboxir::AtomicRMWInst::getOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fenceinst/#a0cf89ee6c985786af9128221e0b2352e">llvm::sandboxir::FenceInst::getOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#a2dab2e91c26b67cdf679bbdf6bc748b7">llvm::sandboxir::Function::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#afba1279eafd7cf7b6ef9681b6f28283f">llvm::sandboxir::Instruction::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#ae51822bea9cc9878d8aac3145b349297">llvm::sandboxir::CatchSwitchInst::getParentPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a1ab92d211e4a27d51621120afb2920cf">llvm::sandboxir::ConstantPtrAuth::getPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a3d66ab7922084715f5e454766e3c21c5">llvm::sandboxir::AtomicCmpXchgInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#a230ddbc1dfad82e9c1317687318fbbf5">llvm::sandboxir::AtomicRMWInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#a58936155653b1e878ee2a8d690e7f8a7">llvm::sandboxir::GetElementPtrInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a2631474f544ed47925fa080544135d6b">llvm::sandboxir::AtomicCmpXchgInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#ab33e913f39a9ef2a4f2ac236f41d5a04">llvm::sandboxir::AtomicRMWInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#af1695c8542907cb759908ceefea9483e">llvm::sandboxir::GetElementPtrInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/loadinst/#aa222683051244b2e2a6c56cb7fb1b3b4">llvm::sandboxir::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst/#ab7c62000d821c42fb80a26829969013e">llvm::sandboxir::StoreInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vaarginst/#a1661dc6977ace70ebc3f1b1cf45c98e5">llvm::sandboxir::VAArgInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#ab2f136dbb9bd21f6db488ad4d0e397fb">llvm::sandboxir::GetElementPtrInst::getPointerOperandType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc/#a4cd835207d936ca42937cd3b88cb1e98">llvm::sandboxir::GlobalIFunc::getResolver</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc/#a847a3a7ab8736327e2abc6a1a0b59e4a">llvm::sandboxir::GlobalIFunc::getResolverFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#a89980d8f2a362c063a72c27d87ea1d2f">llvm::sandboxir::GetElementPtrInst::getResultElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/returninst/#ae939011431c2a603bf8d351c75c9f17e">llvm::sandboxir::ReturnInst::getReturnValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#aa20526ec5783cdd6ecd1e43e7c8f85ce">llvm::sandboxir::GlobalObject::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#a49c1a042d7191adffd285d8e763169ff">llvm::sandboxir::ConstantAggregateZero::getSequentialElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#a9fd2120587f4f077d196cc9e20f86dc2">llvm::sandboxir::PoisonValue::getSequentialElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#aba7f2f01ded2567a746cfe9cf79fa993">llvm::sandboxir::UndefValue::getSequentialElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a71943e74a4433d0f7b517a3f3bdd25fd">llvm::sandboxir::ConstantInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a13eb72c67a4a11f538aceb15713aef25">llvm::sandboxir::ShuffleVectorInst::getShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a006c582c4bec3e2881c674cd4ccddefb">llvm::sandboxir::ShuffleVectorInst::getShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a149a0f4e491d68dd8d10aaf94cedabb4">llvm::sandboxir::ShuffleVectorInst::getShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#ac72ebce2f0fcc49c00b52eb9350640cc">llvm::sandboxir::GetElementPtrInst::getSourceElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinst/#a826ff61b0f5f8eeeb3c5a8581bc904b4">llvm::sandboxir::CastInst::getSrcTy</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a00fe6a3df205f2bb5b21ac4ef7a2dca1">llvm::Instruction::getStableDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#a800d9894402db8885f0a5c3c274c1002">llvm::sandboxir::ConstantAggregateZero::getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#aa2fe583dc4d7205996e692bd8582e33a">llvm::sandboxir::PoisonValue::getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#abde39ab11a9bd74a6219aad3b0044f1f">llvm::sandboxir::UndefValue::getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#a41660d810e3c9d23c360f2f39394d080">llvm::sandboxir::CatchReturnInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#a3085bafbd679d8c31e354c0d1eea4a6a">llvm::sandboxir::SwitchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#ae158bad17025f0884cf1facceecf5299">llvm::sandboxir::AtomicCmpXchgInst::getSuccessOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#aeb52627014fa69227696a3a01e233785">llvm::sandboxir::AtomicCmpXchgInst::getSyncScopeID</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#a35c0200f02da2495d189a4aa9e0b4bef">llvm::sandboxir::AtomicRMWInst::getSyncScopeID</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fenceinst/#aaa02e85629382990e0b63d4c8e772b8f">llvm::sandboxir::FenceInst::getSyncScopeID</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a938f7ce5df695f21d8654960074acae5">llvm::sandboxir::Instruction::getTopmostLLVMInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a888f265095c39e440ed5c83a33be6073">llvm::sandboxir::AllocaInst::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantarray/#acdb9fe29c2c8a7a458631d5a8a108f05">llvm::sandboxir::ConstantArray::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantpointernull/#a53272380640bdd570904df3b290f39d4">llvm::sandboxir::ConstantPointerNull::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#a20862401d26b48d85c4370b213dfcdab">llvm::sandboxir::NoCFIValue::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a09cb3d33809f47986e5023a1b50cdcce">llvm::sandboxir::ShuffleVectorInst::getType</a>, <a href="#a5f93ad2195368bba2202c3cc75e7cc1d">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#a172917cab86e4f2d4a9dec8eda7b531e">llvm::sandboxir::GlobalValue::getUnnamedAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#ae26eae3468dd2e4b2542820f3374e62a">llvm::sandboxir::CatchSwitchInst::getUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#aa5268ec1ee96ab20496d4d3eabe15336">llvm::sandboxir::CleanupReturnInst::getUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst/#a0dd89a17daa11d1dd559bdd57d6f464d">llvm::sandboxir::InvokeInst::getUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#a0a63db0fc18f1ac4017f8e262fc9996f">llvm::sandboxir::AtomicRMWInst::getValOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#a1bac7b9ca93c999e49c0033a8b7229b9">llvm::sandboxir::ConstantFP::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a45999468136f46eec13412cf8b0f26fb">llvm::sandboxir::ConstantInt::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/resumeinst/#acff16dfa912fae89a9b9a5e5955fc8a3">llvm::sandboxir::ResumeInst::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#ab6af82aad7b3ac91e331d4e3dfce874e">llvm::sandboxir::ConstantFP::getValueAPF</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst/#ad118cf1c9e2393aea0594b295480bcfb">llvm::sandboxir::StoreInst::getValueOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#a83ba97d60738036de21893e129514d75">llvm::sandboxir::GlobalObject::getVCallVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#a8f75a0779afa9f6c7dcf5b9d9827a695">llvm::sandboxir::GlobalValue::getVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a0d9e5bd9aa6cd4493d05bb59961a0334">llvm::sandboxir::ConstantPtrAuth::getWithSameSchema</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#ae8e37e9cbc36a46d0059d114a0c24ece">llvm::sandboxir::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a5880595d4d1aa34dfc24d7c9bac1027e">llvm::sandboxir::ConstantPtrAuth::hasAddressDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#a019056d71e6b8dbb2264640c056ab73e">llvm::sandboxir::GetElementPtrInst::hasAllConstantIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#a0387ecdd046a8469f8291aa9dfbb6c03">llvm::sandboxir::FPMathOperator::hasAllowContract</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a3c6b8a75e3b104f23329b816a763d3fa">llvm::sandboxir::Instruction::hasAllowContract</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#a237e9a8973c5a57e5cd00875a6df7407">llvm::sandboxir::FPMathOperator::hasAllowReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a12b9066098bf265aac43392868e640ea">llvm::sandboxir::Instruction::hasAllowReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#a2d00f76d85e4cb9f143f21c87e06c8f8">llvm::sandboxir::FPMathOperator::hasAllowReciprocal</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#aeca404ebd9e3a908878a4e3ecdac76e5">llvm::sandboxir::Instruction::hasAllowReciprocal</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#a7d931d18e4dd5d91680743a3286499ad">llvm::sandboxir::FPMathOperator::hasApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a41e32fcf7730927a32c000db6b8a31bb">llvm::sandboxir::Instruction::hasApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#a25d7dd8317de8297642fb8d981ca87f8">llvm::sandboxir::GlobalValue::hasAtLeastLocalUnnamedAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a0047226185c6349fdec1d92c4282b331">llvm::sandboxir::Instruction::hasAtomicLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a7c75203cbebf63471baf350060c2b831">llvm::sandboxir::Instruction::hasAtomicStore</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a7e0984d796e429a17f7426d60e6fe179">llvm::sandboxir::GlobalVariable::hasAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a8fd630950f74e9337ec2947dea205cdd">llvm::sandboxir::GlobalVariable::hasAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#abb3c931ed4a2f3fa5c9b95a02af0791d">llvm::sandboxir::GlobalVariable::hasAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#a2293463a8beb22268779e67d0e40bb4c">llvm::sandboxir::GlobalObject::hasComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#a1fa10a85eff907aa2361defef74503c8">llvm::sandboxir::GlobalValue::hasComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a344ad1cc0936df3cccd349a52aab6000">llvm::sandboxir::PHINode::hasConstantOrUndefValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a04e73b012a325ed386efc0035be7c6d9">llvm::sandboxir::PHINode::hasConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#a1b8fc1ae6b521aa7dcd539b3b87f0cd4">llvm::sandboxir::GlobalValue::hasDefaultVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a3cf0190c170a420ab2cefaa249c56665">llvm::sandboxir::GlobalVariable::hasDefinitiveInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#a967748a3bf1884f4cd4eba8fc60ca1f0">llvm::sandboxir::GlobalValue::hasGlobalUnnamedAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#a8abd84fa012972bd4a229c4ecc8f2563">llvm::sandboxir::GlobalValue::hasHiddenVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a35d7c8e8765f922aa6ac6c4bdf681f85">llvm::sandboxir::GlobalVariable::hasImplicitSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#acff03e25a823347e541847b09c1b4866">llvm::sandboxir::ExtractValueInst::hasIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#a8779fd6aaa6cf8ce7221cf70ab49119b">llvm::sandboxir::GetElementPtrInst::hasIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertvalueinst/#a91d084fdfb46f395c143765d8bd81003">llvm::sandboxir::InsertValueInst::hasIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a3d608c01916981808c02f0d4724f78b1">llvm::sandboxir::GlobalVariable::hasInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#aa41f78ddcf4c11934919bbe4c978b192">llvm::sandboxir::Instruction::hasMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a32d29786321cb2423d92e5b9da296622">llvm::sandboxir::Instruction::hasMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a360740012eda9a58665e7c9cde390cde">llvm::sandboxir::Instruction::hasMetadataOtherThanDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#a48d501c649551a0be5f008066ace0b2d">llvm::sandboxir::FPMathOperator::hasNoInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ad7c150880efca8b50d773c837be73cda">llvm::sandboxir::Instruction::hasNoInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#a9dedc82c362da93666c4316460a96632">llvm::sandboxir::FPMathOperator::hasNoNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ae52def47e49aff52f8fc59acaa032499">llvm::sandboxir::Instruction::hasNoNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/possiblynonneginst/#a91556eb545844a28d27ebff124f536a8">llvm::sandboxir::PossiblyNonNegInst::hasNonNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a42cac47ff9cd1963ddabcb9c330e98ce">llvm::sandboxir::Instruction::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/overflowingbinaryoperator/#a18e8cb700fffc5a9824d08da1047029c">llvm::sandboxir::OverflowingBinaryOperator::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#a459f10a79535f87afecf90b7d456902d">llvm::sandboxir::FPMathOperator::hasNoSignedZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a1ead7aca0015a93a24bbe2b6c957788c">llvm::sandboxir::Instruction::hasNoSignedZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#acb3fa9bf8977fc06471d0646951d4320">llvm::sandboxir::GetElementPtrInst::hasNoUnsignedSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#a1251333c437257cb281027400941f9ff">llvm::sandboxir::GetElementPtrInst::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a0227b67a5425817dfdebb7d51f90e240">llvm::sandboxir::Instruction::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/overflowingbinaryoperator/#a80a2d6e908bdf6fb2239d0e6e27b8e04">llvm::sandboxir::OverflowingBinaryOperator::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/operator/#a0334f0e9533d1621f49a1bc7aa927934">llvm::sandboxir::Operator::hasPoisonGeneratingFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#ae76da390348683efbb915578497d7064">llvm::sandboxir::GlobalValue::hasProtectedVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#a8743f54dd4a19f956de512115d94d5c5">llvm::sandboxir::GlobalObject::hasSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#abca1a7174c7f826a0bcdd4b2c1ec59b0">llvm::sandboxir::ConstantPtrAuth::hasSpecialAddressDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#af20d98097edbb1810a0a4da41521d8c7">llvm::sandboxir::GlobalVariable::hasUniqueInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#a602c9f81a4dd92e7993e03ede08e3349">llvm::sandboxir::CatchSwitchInst::hasUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#a2d37fb1634fa515d1feb526bd74a0f42">llvm::sandboxir::CleanupReturnInst::hasUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#a3d71b9c5bcaa346b3bcc77d01a731b92">llvm::sandboxir::ExtractValueInst::idx_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertvalueinst/#ad7df50b3ce7cddfebb21d0be8b9536fb">llvm::sandboxir::InsertValueInst::idx_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#af679e1725fe477cd15bac8b2a6075c24">llvm::sandboxir::ExtractValueInst::idx_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertvalueinst/#a5f5b18223dd388f0bf7f08e26e2885f8">llvm::sandboxir::InsertValueInst::idx_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a94792cee6fbfd24ae383b9ce70fd2769">llvm::sandboxir::ShuffleVectorInst::increasesLength</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#af3de205b4adfeb53855ac60f9029ac05">llvm::sandboxir::ExtractValueInst::indices</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertvalueinst/#a7225c22214ac88d89721c6f54c3783a7">llvm::sandboxir::InsertValueInst::indices</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#ac92a5f2997eea0db1c8833e73cd34ae5">llvm::sandboxir::CallBase::isArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a38fddebbf9ea947034b53b0dae4e6700">llvm::sandboxir::AllocaInst::isArrayAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a06c696aa12c471522d351eb0b474daac">llvm::sandboxir::Instruction::isAssociative</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/intrinsicinst/#a36b56f010406e38bbdf345ed794be4c1">llvm::sandboxir::IntrinsicInst::isAssociative</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/intrinsicinst/#a604abb6f5252ad1622cb2bf6876846fe">llvm::sandboxir::IntrinsicInst::isAssumeLikeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ac7cb090fa3549e4c24d89f46375cfcfa">llvm::sandboxir::Instruction::isAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a4eb488ae3f9d8139e97279aa501c74b5">llvm::sandboxir::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#af1ab518561daffcf1b5f5fba4a6fccaf">llvm::sandboxir::CallBase::isCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a596225b33a132a043f4ceabcbe4b7612">llvm::sandboxir::Instruction::isCast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/landingpadinst/#a6d7f763d0ef3b935811cb712759257e7">llvm::sandboxir::LandingPadInst::isCatch</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/landingpadinst/#a136fa46d9fdd577ac5bd8f0f2d78082d">llvm::sandboxir::LandingPadInst::isCleanup</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a55743bd32282bf6f87aeb49237b1fb68">llvm::Instruction::isCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#accd031bafbc007f0c558131294fc815c">llvm::sandboxir::Instruction::isCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/intrinsicinst/#ab215285b6951ea8dee543eb009be0ca2">llvm::sandboxir::IntrinsicInst::isCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a9adda21992a57430686b8353e6223652">llvm::sandboxir::PHINode::isComplete</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a7923d3ae310bd0a3d16e0e5233f85109">llvm::sandboxir::ShuffleVectorInst::isConcat</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a90f9b48d07d5c91efa248fb000186672">llvm::sandboxir::BranchInst::isConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#ad5b1218ba4afd76fcd303620c91d2377">llvm::sandboxir::GlobalVariable::isConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a4acb9a791c0b2dc6fb07f62c9166aeff">llvm::sandboxir::CallBase::isDataOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/possiblydisjointinst/#af332f7c8c4858badeb120c8e9c1b00a8">llvm::sandboxir::PossiblyDisjointInst::isDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#abc97388e84943b9ab414c9b37e2d76b3">llvm::sandboxir::Instruction::isExact</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#a48823e5da12f02df3ea52fc4a6bfcd3d">llvm::sandboxir::ConstantFP::isExactlyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#aee812bee8ccb12920656a4a84d37c70e">llvm::sandboxir::ConstantFP::isExactlyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a0c72c59fb4d2db56c3c2eb9297a7be99">llvm::sandboxir::GlobalVariable::isExternallyInitialized</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a072f0057fbdcc7d9ee6f383640ba5fae">llvm::sandboxir::ShuffleVectorInst::isExtractSubvectorMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#a2d48c08d14e857954be9bcd3ad43be9e">llvm::sandboxir::FPMathOperator::isFast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a56a57712e8182ee82f209b73a02d3e08">llvm::sandboxir::Instruction::isFast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a0803b8656fdfacb721f482733f70de9b">llvm::sandboxir::Instruction::isFenceLike</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/landingpadinst/#a12741ccb0bb8db6f56bbce12debacafe">llvm::sandboxir::LandingPadInst::isFilter</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#aef14ce80bfee9ed84d761d39d77f1493">llvm::sandboxir::AtomicRMWInst::isFloatingPointOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a7b757141b5e26c2b754c1c0bcccd339a">llvm::sandboxir::Instruction::isFuncletPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#aa26319dcf406c81514075cd14a88702e">llvm::sandboxir::Instruction::isIdempotent</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a4ee544a72a6e1d59226d110722e09904">llvm::sandboxir::ShuffleVectorInst::isIdentity</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a11224683dad9098eaf168e8274724db2">llvm::sandboxir::ShuffleVectorInst::isIdentityWithExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a09d88ec2c7c034d2bce983202dcddedf">llvm::sandboxir::ShuffleVectorInst::isIdentityWithPadding</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#aa814acfdeb85624bce03d6e8c5e02788">llvm::sandboxir::GetElementPtrInst::isInBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#af3c91f981e054dc529715346acd2d61c">llvm::sandboxir::CallBase::isIndirectCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#ace8428c72983668b327edc15bd03161d">llvm::sandboxir::ConstantFP::isInfinity</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a2f493f84e9075bfb0b441b9e8cf77921">llvm::sandboxir::CallBase::isInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#adb2471b32c45d852920a7a9d51661931">llvm::sandboxir::ShuffleVectorInst::isInsertSubvectorMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a6fe25a28c752cd3fbebd3fe35960cbc0">llvm::sandboxir::Instruction::isIntDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a1b39e6114949bf8f91785c82ce7e3e30">llvm::sandboxir::ShuffleVectorInst::isInterleave</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantptrauth/#a65a439b215dcf87ea9f7d1a1b3bf8c35">llvm::sandboxir::ConstantPtrAuth::isKnownCompatibleWith</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a23569411e32251a57ef71ced8c44a3f4">llvm::sandboxir::Instruction::isLogicalShift</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a53845119c18f8751c93d5a1271d4356d">llvm::sandboxir::ConstantInt::isMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a0d8934e5c7408f92ba9b5505179b2e02">llvm::sandboxir::ConstantInt::isMinusOne</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a811b84896d59f504ffde1cdb1c121b9c">llvm::sandboxir::ConstantInt::isMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a0b38a739bd855981310af6727a2729af">llvm::sandboxir::CallBase::isMustTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#aa79d6bd4e7188e44f4f1b9f477e320b3">llvm::sandboxir::ConstantFP::isNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#a497ac67f865ddcab5125aef9bd850a57">llvm::sandboxir::ConstantFP::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a77c16d1d87ffc194c3f9040d5ad78783">llvm::sandboxir::ConstantInt::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ad85e2a858f9c32262db4b04f6dd1d23e">llvm::sandboxir::Instruction::isNilpotent</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a5c87df8108bd21300448e4bf376aa558">llvm::sandboxir::ConstantInt::isOne</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#ac7bc0d2b9c9db44107b4e72223c4da07">llvm::sandboxir::ShuffleVectorInst::isOneUseSingleSourceMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#aa52f515e2278ca4e6679470430a3e38d">llvm::sandboxir::Instruction::isOnlyUserOfAnyOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a76d59877a3691fd972c58f257b86026f">llvm::sandboxir::ShuffleVectorInst::isReplicationMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a0763e53db0aa8ae2bef6d1579cdae416">llvm::sandboxir::ShuffleVectorInst::isReverse</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#ae3c3174242fb6e6a4c1267aa36f0f131">llvm::sandboxir::ShuffleVectorInst::isSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a2c4cafc2712ddf67270982232c5508c0">llvm::sandboxir::Instruction::isShift</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/loadinst/#aeb2772b8f4d38417226114b8a0902774">llvm::sandboxir::LoadInst::isSimple</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst/#ac2071cfbc784d2657dfba0fde2356737">llvm::sandboxir::StoreInst::isSimple</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a6341116bfdd3308eb2f018ecc7e2eef7">llvm::sandboxir::ShuffleVectorInst::isSingleSource</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a0c3e3f0d6c5b7cd79123c81eeddc16fe">llvm::sandboxir::Instruction::isSpecialTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a6cb0a07bcdfef68e90f786fd32209866">llvm::sandboxir::ShuffleVectorInst::isSplice</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a26bb30bbbd677ace9552e41a55759e15">llvm::sandboxir::AllocaInst::isStaticAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a96f59c98f779995acd7dbafea992b4b6">llvm::sandboxir::CallBase::isTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#affb6e73f7d5d31e5dfbf0bbe3461eb5b">llvm::sandboxir::Instruction::isTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#af4551913fa0855cc9e0f29340a40bb0d">llvm::sandboxir::ShuffleVectorInst::isTranspose</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a99b2c86c64b51f001b776e7c0c692200">llvm::sandboxir::Instruction::isUnaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#ab0ce093a7016d69f2d594f0dc97f42f6">llvm::sandboxir::BranchInst::isUnconditional</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/loadinst/#a14dbb05ec3478e2b61839c7159bc41a1">llvm::sandboxir::LoadInst::isUnordered</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst/#a670b22623151e02254daa6abb26b29b3">llvm::sandboxir::StoreInst::isUnordered</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a08a7e741e6857ca3418b3700f35868d8">llvm::sandboxir::AllocaInst::isUsedWithInAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractelementinst/#ae76e8b3cd14739bf9c93ea40153119e1">llvm::sandboxir::ExtractElementInst::isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertelementinst/#ae505498b4e6d14d846dc2dad88ef014a">llvm::sandboxir::InsertElementInst::isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a7fd4a20d9af38768eb00b8065b71dd76">llvm::sandboxir::ShuffleVectorInst::isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a72083a6afb8aa61a69cd177522a6d7ef">llvm::sandboxir::ShuffleVectorInst::isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#acb13e764fc51d1d9327ecdd87e34d3be">llvm::sandboxir::AtomicCmpXchgInst::isVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#ad6ae364a6fba9109f5cf7d5803002861">llvm::sandboxir::AtomicRMWInst::isVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ac8a2f5c996789f05769e35f75f910591">llvm::sandboxir::Instruction::isVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/loadinst/#ab3530e3ba1dd4c151b049bb2d86bafc3">llvm::sandboxir::LoadInst::isVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst/#ac52909875952757d7e84ca0f74a97f5d">llvm::sandboxir::StoreInst::isVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#af5fa0bd667152cd6192ec82d85d073ce">llvm::sandboxir::AtomicCmpXchgInst::isWeak</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#a8c9961e353d8fcb6fb95684ad4e5ef67">llvm::sandboxir::ConstantFP::isZero</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a4ca48540877873daad3254ef9612505c">llvm::sandboxir::ConstantInt::isZero</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a9f05307d2dc546546e4f1eb3e2a6e251">llvm::sandboxir::ShuffleVectorInst::isZeroEltSplat</a>, <a href="#a7e5bdab1596d88c89ead437cfa80e382">LLVMOpUserItToSBTy</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ab2a8084b66143dea3c1d2e06eb936615">llvm::sandboxir::Instruction::mayHaveSideEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#abf9fe5b59f65d9bcae351a885eabc4e3">llvm::sandboxir::Instruction::mayReadFromMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ab344f0d0ccb0e9b5a10ea4dc7f0ad5e3">llvm::sandboxir::Instruction::mayReadOrWriteMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a9358dd89deb90200693bd2f208c45239">llvm::sandboxir::Instruction::mayThrow</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a18645b6acb3a200b40851cbd5b10b07c">llvm::sandboxir::Instruction::mayWriteToMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a00acedbe40caf585acae6bf934765a72">llvm::sandboxir::User::op_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#add1b0b449637bb3ff8c08cd4287d5395">llvm::sandboxir::User::op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#afa6137fa4de3e04d7bdae0144bbd9905">llvm::sandboxir::SwitchInst::removeCase</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a0b2bc62c021fac7a3b7cb98ba3654ff3">llvm::sandboxir::PHINode::removeIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#abd01234117775c7ff32e73f0134b7e34">llvm::sandboxir::PHINode::removeIncomingValue</a>, <a href="#a357dd7c60a0ea6b2e6c7ecdf9c9923d1">replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#adb65b7728328242af02bba662ee8e7d7">llvm::sandboxir::PHINode::replaceIncomingBlockWith</a>, <a href="#aac76a388ba3671a3d8a93e610f0bf1e3">replaceUsesWithIf</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias/#ab1309f79334a271b4fa4d216dcc5e2f2">llvm::sandboxir::GlobalAlias::setAliasee</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#ae641a2be8d31f3518b04301c98e094d5">llvm::sandboxir::AllocaInst::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#afea0095f9b8d24d9052e472b965f1542">llvm::sandboxir::AtomicRMWInst::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#a83748f9098fea276898c0741262a66e4">llvm::sandboxir::GlobalObject::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a30ebcd2d2e510843030053dbd00b7031">llvm::sandboxir::AllocaInst::setAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/funcletpadinst/#a82cc2d68ad4f4f4d79bbbd9c8a755ada">llvm::sandboxir::FuncletPadInst::setArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#a97678deb11364fbd028c6a437dacbf2d">llvm::sandboxir::CatchReturnInst::setCatchPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#ade76bff1f6821467269e0dd985baaa5d">llvm::sandboxir::CleanupReturnInst::setCleanupPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#ade5dafda9b8e251beab93f9154736fc1">llvm::sandboxir::SwitchInst::setCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#aa6ed211b74ca9002d55c5b881ae7d088">llvm::sandboxir::GlobalVariable::setConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst/#a47621555866da42fa41c71023218cc3b">llvm::sandboxir::SwitchInst::setDefaultDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a6ffd1c1a8f379a0462f7ac67eb95d98e">llvm::sandboxir::GlobalVariable::setExternallyInitialized</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a98bb2475710edf44add1383dfc8a4d4b">llvm::sandboxir::AtomicCmpXchgInst::setFailureOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a076ed6abb9853c90a0dbdd0af7930cb7">llvm::sandboxir::Instruction::setFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#aefff93ab9c3b3d05c19d72362bcd0c90">llvm::sandboxir::GlobalObject::setGlobalObjectSubClassData</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#af57a79465abb3553060726acc4103006">llvm::sandboxir::Instruction::setHasAllowReciprocal</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a6bd41098e8a68ed910f903bdf882371e">llvm::sandboxir::Instruction::setHasApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#afa823f9fcdbe6f11fed742dd95bc748d">llvm::sandboxir::Instruction::setHasNoInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a70cc35150e6169c05919063aa3f9486d">llvm::sandboxir::Instruction::setHasNoNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a88f79981a5c0a0072e6d8252ccf831ac">llvm::sandboxir::Instruction::setHasNoSignedZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a8fd48c955a259895ca147ea9f2cd6d64">llvm::sandboxir::PHINode::setIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#ac9ac79e5a1a12af4be6ac3cad1e079e0">llvm::sandboxir::PHINode::setIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a9addc56ed8318970567e31311085b0e6">llvm::sandboxir::GlobalVariable::setInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/possiblydisjointinst/#ae16106c1e614b55000270a227e981fd8">llvm::sandboxir::PossiblyDisjointInst::setIsDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/possiblynonneginst/#ab6e8d142dc2d6dececc8a6212825645e">llvm::sandboxir::PossiblyNonNegInst::setNonNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a54abb07f9d20e6d5344ce647621f85a8">llvm::sandboxir::User::setOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#aafbaf51cd1bb61a7b616ff2434e40a12">llvm::sandboxir::AtomicRMWInst::setOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fenceinst/#a4c42d562e2e9c79bcb1c77c41cfeff11">llvm::sandboxir::FenceInst::setOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a82375fc602bbbdc421f2ae663b595a43">llvm::sandboxir::CmpInst::setPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc/#a70ae64460ad95cab729c96a76d10f14a">llvm::sandboxir::GlobalIFunc::setResolver</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#af802ad5aa5721e72eeab21959b526c9d">llvm::sandboxir::GlobalObject::setSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#abc00dfadd75bc8833db0eccafcfda661">llvm::sandboxir::ShuffleVectorInst::setShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae959364e4640ac025bbc046d3d7c7e61">llvm::Instruction::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst/#a4f52d7a4f188d9c95c14e8da6b3f18d2">llvm::sandboxir::CatchReturnInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#a2098c7a23f7e052b0009f5d7a6cdec3c">llvm::sandboxir::AtomicRMWInst::setSyncScopeID</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#a6850150c4508a12b540a3f3497498db5">llvm::sandboxir::GlobalValue::setUnnamedAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#a3527a0276c2133717040ef9452ec7ce8">llvm::sandboxir::CleanupReturnInst::setUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a92d20c9a65a5af8df6f4cfad584270c3">llvm::sandboxir::AllocaInst::setUsedWithInAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#af44ac69b033b2d5319c8d229eb22b15c">llvm::sandboxir::GlobalValue::setVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a8158695531a595cdf673438b3097338b">llvm::sandboxir::AtomicCmpXchgInst::setVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst/#a7d59ad8f003b26a0c532da138233849d">llvm::sandboxir::AtomicCmpXchgInst::setWeak</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a2f934ebbafcd336726a91d636c2cf853">llvm::sandboxir::BranchInst::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a611d4d9356dd291578cd369630ef3907">llvm::sandboxir::BranchInst::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fcmpinst/#a5c09f89b0fd13cf2405d0af211b888bd">llvm::sandboxir::FCmpInst::swapOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/icmpinst/#a9e604facb59bb8a1337ee2323708303b">llvm::sandboxir::ICmpInst::swapOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/selectinst/#a462041a4b8235d7b12124fca65b8640c">llvm::sandboxir::SelectInst::swapValues</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a53c07e115dd4e4a07497cd8d2b43a01a">llvm::sandboxir::ConstantInt::uge</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#a622c0107da1a58bf9eba0600928ff42c">llvm::sandboxir::CatchSwitchInst::unwindsToCaller</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst/#a537205f5e1e2d65e330fd9b24ae2d328">llvm::sandboxir::CleanupReturnInst::unwindsToCaller</a>, <a href="#af685aa3ea024631ed348071914df61c0">use_begin</a>, <a href="#af6e1ffac63581af9de82a4b2e37a3590">user_begin</a>, <a href="#a73b563c1c2654e2f9b3756f38e276284">Value</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument/#aad9974dafadc102c607acae06ceaeb55">llvm::sandboxir::Argument::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#a4a93facd552b6d55e38198a180236920">llvm::sandboxir::Constant::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#a6ed61ba0739e353de9c17915f79541c6">llvm::sandboxir::ConstantAggregateZero::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantfp/#a8f07e8b67441936e0eae0b6e9fc9f4f4">llvm::sandboxir::ConstantFP::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#a6928ead2e2677c5101c7ae3dcd02e94d">llvm::sandboxir::ConstantInt::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantpointernull/#a45c14dfe12cd2850bd0e22e43386e1b1">llvm::sandboxir::ConstantPointerNull::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constanttokennone/#a1fbe0eae6aa15b0d30eb7bf0837e2cd1">llvm::sandboxir::ConstantTokenNone::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dsolocalequivalent/#a7a9d4c11f5de1db8ecbacc33106c8ca2">llvm::sandboxir::DSOLocalEquivalent::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#acee180f03b5947c8f371e5b02445d298">llvm::sandboxir::Function::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc/#a17bc578a9c3ecf6022113a945590536f">llvm::sandboxir::GlobalIFunc::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable/#a67b948e4a34f2d71c5e4e3b506b70342">llvm::sandboxir::GlobalVariable::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#a785c19ca46303cf460eeeb8fb65189e1">llvm::sandboxir::NoCFIValue::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#a8e4d233574beafc1ef1f959b912c7594">llvm::sandboxir::PoisonValue::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/singlellvminstructionimpl/#abf3808e6f94bcec8e66656e163c8b6e5">llvm::sandboxir::SingleLLVMInstructionImpl&lt; LLVMT &gt;::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#a29b313c871075891417d8801a355f9b0">llvm::sandboxir::UndefValue::verify</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a67250c676fe2b5ab6619b31d80b5dd5c">llvm::sandboxir::User::verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### getSubclassIDStr() {#adc1366b7fa3a558a916efd3c68a64834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::sandboxir::Value::getSubclassIDStr (<a href="#afa2029c46b6caf94a7d05ceb0dbcefe9">ClassID</a> ID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a1565aa2d231b44e393af53deb7de04c2">dumpCommonHeader</a> and <a href="#a294250e6721c14a9a8d934220e6523d0">dumpCommonSuffix</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">Value.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
