---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipstargetstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MipsTargetStreamer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MipsTargetStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">Target/Mips/MipsTargetStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific streamer interface. <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mipsmctargetdesc-cpp-/mipswincofftargetstreamer">MipsWinCOFFTargetStreamer</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer">MipsTargetAsmStreamer</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer">MipsTargetELFStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51f80b3e6e2aaa02181cff60e90f6d4">MipsTargetStreamer</a> (MCStreamer &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c14a369b734721293032d25d73482b7">setPic</a> (bool Value)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa11d3d36d614c29d1c63b0d1c3d9db">emitDirectiveSetMicroMips</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2261dc88d87519ce2e94ddfeece22a9e">emitDirectiveSetNoMicroMips</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5288c4739dac163b342be353593c7040">setUsesMicroMips</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36c6bb692c53b6e38238458a36a01b1">emitDirectiveSetMips16</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc9172aee17ce9ef6e36aeb49cead1b">emitDirectiveSetNoMips16</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ac655a921f536b820733476056c75e">emitDirectiveSetReorder</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad96ce40f96e341fb3ef36c945550acc1">emitDirectiveSetNoReorder</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43f244b24701d5345baca53c8fce8f64">emitDirectiveSetMacro</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c4cd011ce562d2f3cb59ed52cbf2ee">emitDirectiveSetNoMacro</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea525a8a4a50b55b1db9111763902ead">emitDirectiveSetMsa</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0e4693659b749bfa70b5f7e6a4824e5">emitDirectiveSetNoMsa</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75dddc93169cec0751f8853487912f1a">emitDirectiveSetMt</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833e5a4196c77756d8abd125378f116d">emitDirectiveSetNoMt</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a320c07dc5edc03b21abc79f04c00d062">emitDirectiveSetCRC</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4d4f04e5c1bdc47be5c5e26e8381b6">emitDirectiveSetNoCRC</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad28f6e2510b96128cf1bce96dc7b783e">emitDirectiveSetVirt</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f9efc2fc014bebdae07d5847cb3d6d">emitDirectiveSetNoVirt</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d5f5cc266722979a8f9a32e5c7b20dd">emitDirectiveSetGINV</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b77e3b76f8459feb014f3d6e34ef41">emitDirectiveSetNoGINV</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0596dd2ff1d68d416339fea7e40ba0fc">emitDirectiveSetAt</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb4c1638eb68607271d154cbc673ece8">emitDirectiveSetAtWithArg</a> (unsigned RegNo)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d312bb946ef4b4c6a1593c77361ac60">emitDirectiveSetNoAt</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30fe55a862200bafc317f84b8c519244">emitDirectiveEnd</a> (StringRef Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1753b89a18609caf60fff2f2b22584">emitDirectiveEnt</a> (const MCSymbol &amp;Symbol)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa24fd75e6b507332ceac85850d7409e">emitDirectiveAbiCalls</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c5bbc82931814b855dd3b4b913adf79">emitDirectiveNaN2008</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fb29c2817471abc0cdc60600e196b5e">emitDirectiveNaNLegacy</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade76bf6a3f6d11c3d0a0928d49e7aa2b">emitDirectiveOptionPic0</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecd2d24b73f2f1ca5edd54e9eefd5910">emitDirectiveOptionPic2</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca10e0f5ea5cf41e21cbaece649e895f">emitDirectiveInsn</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d42fba558d9fdc684fb8b4ceb687d6d">emitFrame</a> (unsigned StackReg, unsigned StackSize, unsigned ReturnReg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90a18fdcb6f991c1259fb9f94b05e69b">emitMask</a> (unsigned CPUBitmask, int CPUTopSavedRegOff)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5507b558e355857fbc984d7ada21a55">emitFMask</a> (unsigned FPUBitmask, int FPUTopSavedRegOff)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7214ae790fae0ca98c92d0b5a7821c8">emitDirectiveSetArch</a> (StringRef Arch)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb776dcb1b0923724c3e9acaf6d1051">emitDirectiveSetMips0</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e5eb252afdc4750051c13fad4d6f692">emitDirectiveSetMips1</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70b1699a55f69e1ddf10810b7ba6ad61">emitDirectiveSetMips2</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b5970f934ecff64a0b2471ac15fb184">emitDirectiveSetMips3</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0508a0ddc18b9c7bef61267ccd2ef1">emitDirectiveSetMips4</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4b878b006cf365b035b4c595a703e9">emitDirectiveSetMips5</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade1b256588dce94f4879d008e97479c2">emitDirectiveSetMips32</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb100b60ecb733e3ad1fc666a15f417">emitDirectiveSetMips32R2</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a0fb9cfc35b9ee579259dea2d444bd1">emitDirectiveSetMips32R3</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8e0f6520875562e1f575327fd71d714">emitDirectiveSetMips32R5</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb7cc50b9fe13d9112e8e8f2ec121f97">emitDirectiveSetMips32R6</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af618f5b75efd1f5c6bd492969089c404">emitDirectiveSetMips64</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c5d8196410abd7683793ba3c3f20953">emitDirectiveSetMips64R2</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f0d97c7a46804c80e03d27a466d55f">emitDirectiveSetMips64R3</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02b4ddd0d430be491720868fe27d784d">emitDirectiveSetMips64R5</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad038888187fae9c838c150d80fd7e34c">emitDirectiveSetMips64R6</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e91dffd3aab03752dbe6b7321259a42">emitDirectiveSetDsp</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d2ff8596f3f9ea8b36eca3cd7ce594">emitDirectiveSetDspr2</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc021f2efc3e33e47c5fac5fea8d152">emitDirectiveSetNoDsp</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da861aec13177a569ed596d67c90c0d">emitDirectiveSetMips3D</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b30d96c3cddcef4c04ff0f1a7bc690">emitDirectiveSetNoMips3D</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22aec4488d76be7bf6ca8c186725a50">emitDirectiveSetPop</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d34999cdd0edb20d94b3555dfe1263">emitDirectiveSetPush</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae21816069580c36a180ea513c6073a">emitDirectiveSetSoftFloat</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a687a9e9dbe2c52708e3515bf549c2e54">emitDirectiveSetHardFloat</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac94658314a8398ba0eea2317850a9ae1">emitDirectiveCpAdd</a> (unsigned RegNo)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66461bd97bfa017f4a1c57400ae0a023">emitDirectiveCpLoad</a> (unsigned RegNo)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a660db22c7980498afae281f2ee34f921">emitDirectiveCpLocal</a> (unsigned RegNo)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda7d403af17ee4b867b707bdb9d638b">emitDirectiveCpRestore</a> (int Offset, function_ref&lt; unsigned()&gt; GetATReg, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c9eff9b814fe893a4bf2d56ead0ac5">emitDirectiveCpsetup</a> (unsigned RegNo, int RegOrOffset, const MCSymbol &amp;Sym, bool IsReg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d87cf1dec832dfae915542c6e5ff032">emitDirectiveCpreturn</a> (unsigned SaveLocation, bool SaveLocationIsRegister)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6890c9a436aed972ee4bb882b1ddc1">emitDirectiveModuleFP</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8a672bc299b883b02ce5b21b4716f0a">emitDirectiveModuleOddSPReg</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4762f03cbfd596754e1f21b39462014">emitDirectiveModuleSoftFloat</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8957ea15e88f22c75eca14739820ad9">emitDirectiveModuleHardFloat</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69ef849ea4b485d35669387c0611633">emitDirectiveModuleMT</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3159a0f4c9e5c404313b18245af0a242">emitDirectiveSetFp</a> (MipsABIFlagsSection::FpABIKind Value)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a815e926c8058ffad18bcf9bbb9745ad9">emitDirectiveSetOddSPReg</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7da9427b4879ac386a19ee3bac750f9a">emitDirectiveSetNoOddSPReg</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a146469eea85ec753fd2e3fb88c06ed">emitDirectiveModuleCRC</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1891c2902fc95b25aafb08cb1f5b8f5">emitDirectiveModuleNoCRC</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79d9be8aba11211b8d96072faf5cbba">emitDirectiveModuleVirt</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a076087727a32d717e52affef995e820e">emitDirectiveModuleNoVirt</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b00f2d4eff5955e1dbc71fc249abf33">emitDirectiveModuleGINV</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1492b454e17c86ea6e014ba0f6a90e90">emitDirectiveModuleNoGINV</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49ba9fd9824c6910d3f66c1ae4469891">emitR</a> (unsigned Opcode, unsigned Reg0, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff09aba59d7dcc5dd800735494b14ff">emitII</a> (unsigned Opcode, int16_t Imm1, int16_t Imm2, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b33055c2d9eb274c2d980428f7a1c24">emitRX</a> (unsigned Opcode, unsigned Reg0, MCOperand Op1, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaac5a23f685560581a0ed18649b930af">emitRI</a> (unsigned Opcode, unsigned Reg0, int32_t Imm, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a936108fd0c95676dd98dcfb5ca1d8773">emitRR</a> (unsigned Opcode, unsigned Reg0, unsigned Reg1, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b10941b3ac644fb3508bc6cdc8aa6d5">emitRRX</a> (unsigned Opcode, unsigned Reg0, unsigned Reg1, MCOperand Op2, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3776e68a5559151ee83323b88e9c19a">emitRRR</a> (unsigned Opcode, unsigned Reg0, unsigned Reg1, unsigned Reg2, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbac3ade2206cc952cf43e2ca4566201">emitRRRX</a> (unsigned Opcode, unsigned Reg0, unsigned Reg1, unsigned Reg2, MCOperand Op3, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a187cf8bd0c76fa7b07a76bdf6938c47e">emitRRI</a> (unsigned Opcode, unsigned Reg0, unsigned Reg1, int16_t Imm, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09e7b7665f50b4338f746a50f6a454b1">emitRRIII</a> (unsigned Opcode, unsigned Reg0, unsigned Reg1, int16_t Imm0, int16_t Imm1, int16_t Imm2, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37f96e5964d71bf0607bfe9332dcf551">emitAddu</a> (unsigned DstReg, unsigned SrcReg, unsigned TrgReg, bool Is64Bit, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb76cf6aa796861bf38a631e34717bbb">emitDSLL</a> (unsigned DstReg, unsigned SrcReg, int16_t ShiftAmount, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f176e080c458432506637ce9976533">emitEmptyDelaySlot</a> (bool hasShortDelaySlot, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80a575d616aab5d776fbcce52ddea85">emitNop</a> (SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a271310bf77ed9982cec75ffad22d2a98">emitStoreWithImmOffset</a> (unsigned Opcode, unsigned SrcReg, unsigned BaseReg, int64_t Offset, function_ref&lt; unsigned()&gt; GetATReg, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a store instruction with an offset. <a href="#a271310bf77ed9982cec75ffad22d2a98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e9ecfd84b06cfed78760480dde161a">emitLoadWithImmOffset</a> (unsigned Opcode, unsigned DstReg, unsigned BaseReg, int64_t Offset, unsigned TmpReg, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a load instruction with an immediate offset. <a href="#ac0e9ecfd84b06cfed78760480dde161a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4fc9cf5a21ec44d15ceae97469fd760">emitGPRestore</a> (int Offset, SMLoc IDLoc, const MCSubtargetInfo *STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the $gp restore operation for .cprestore. <a href="#ad4fc9cf5a21ec44d15ceae97469fd760">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1360ac908c09b90b3b913e2e2126092f">reallowModuleDirective</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7651e5345a88084b8ec729848530085b">isModuleDirectiveAllowed</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class PredicateLibrary&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e9af05a3f0fd39459bb7b7ed6571680">updateABIInfo</a> (const PredicateLibrary &amp;P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mipsabiflagssection">MipsABIFlagsSection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada9390d1dcfdccb5558d10779ef5a058">getABIFlagsSection</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6bbf7825f8f4017bd11b8af805876df">getABI</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0149c6589bbda5a439786064155ba1ca">ABI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mipsabiflagssection">MipsABIFlagsSection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affd5266462270aa47e8e8f2e1c7e3193">ABIFlagsSection</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4a317e4d7fd84d1ae2a193a46d5d76">GPRInfoSet</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb0558d4415697ff95ef175530d52505">GPRBitMask</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e12ea8a2a8bac766fbee36aac4ee20">GPROffset</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84cd9ea9478febeb0b364d0d1a064cf8">FPRInfoSet</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065561651519e275e024f18954cafd11">FPRBitMask</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfbfc160bd1afee7c52ccc6d70003b03">FPROffset</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4b5a6f9e52848eeba6bbfb48ce4cb6f">FrameInfoSet</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177a753c8303e0b7a5558894e80a5e7f">FrameOffset</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c812798a63fc4f676d5942454af192">FrameReg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bb3fa998cee14aa1f6e453beec1d489">GPReg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ab24f34b1f8811a662826063b66f8d1">ReturnReg</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3364f2c43ceef3861145f905d75decd8">ModuleDirectiveAllowed</a></td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsTargetStreamer() {#ad51f80b3e6e2aaa02181cff60e90f6d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsTargetStreamer::MipsTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="#a84cd9ea9478febeb0b364d0d1a064cf8">FPRInfoSet</a>, <a href="#ad4b5a6f9e52848eeba6bbfb48ce4cb6f">FrameInfoSet</a>, <a href="#a1bb3fa998cee14aa1f6e453beec1d489">GPReg</a>, <a href="#a5d4a317e4d7fd84d1ae2a193a46d5d76">GPRInfoSet</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#acfff4f9a518231ee043200a694fcbafa">llvm::MCTargetStreamer::MCTargetStreamer</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a170629d07fdadf157b053bcb96007a44">llvm::MipsTargetAsmStreamer::MipsTargetAsmStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a17d3b4679a104b0852f1679b817d2070">llvm::MipsTargetELFStreamer::MipsTargetELFStreamer</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsmctargetdesc-cpp-/mipswincofftargetstreamer/#ae0ceb6a0f5662f387d07152302e32e8d">anonymous{MipsMCTargetDesc.cpp}::MipsWinCOFFTargetStreamer::MipsWinCOFFTargetStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAddu() {#a37f96e5964d71bf0607bfe9332dcf551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitAddu (unsigned DstReg, unsigned SrcReg, unsigned TrgReg, bool Is64Bit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#ab3776e68a5559151ee83323b88e9c19a">emitRRR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a08fd27bcf2c6777016d5ea10cd83e548">llvm::MipsTargetELFStreamer::emitDirectiveCpAdd</a>.</p>

</div>
</div>

### emitDirectiveAbiCalls() {#afa24fd75e6b507332ceac85850d7409e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveAbiCalls ()</td>
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



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### emitDirectiveCpAdd() {#ac94658314a8398ba0eea2317850a9ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveCpAdd (unsigned RegNo)</td>
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



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveCpLoad() {#a66461bd97bfa017f4a1c57400ae0a023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveCpLoad (unsigned RegNo)</td>
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



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveCpLocal() {#a660db22c7980498afae281f2ee34f921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveCpLocal (unsigned RegNo)</td>
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



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>, <a href="#ac6bbf7825f8f4017bd11b8af805876df">getABI</a> and <a href="#a1bb3fa998cee14aa1f6e453beec1d489">GPReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a6dca65256df2dd8715cf3221e33c6f4e">llvm::MipsTargetAsmStreamer::emitDirectiveCpLocal</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a90e588bcf9297ddf422207faca2f001e">llvm::MipsTargetELFStreamer::emitDirectiveCpLocal</a>.</p>

</div>
</div>

### emitDirectiveCpRestore() {#abda7d403af17ee4b867b707bdb9d638b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetStreamer::emitDirectiveCpRestore (int Offset, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; unsigned()&gt; GetATReg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a12406a1009639db38ee6cec215d6ad2e">llvm::MipsTargetAsmStreamer::emitDirectiveCpRestore</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a64e7586a1feca4613439ac07eabce3f0">llvm::MipsTargetELFStreamer::emitDirectiveCpRestore</a>.</p>

</div>
</div>

### emitDirectiveCpreturn() {#a1d87cf1dec832dfae915542c6e5ff032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveCpreturn (unsigned SaveLocation, bool SaveLocationIsRegister)</td>
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



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveCpsetup() {#a45c9eff9b814fe893a4bf2d56ead0ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveCpsetup (unsigned RegNo, int RegOrOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym, bool IsReg)</td>
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



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveEnd() {#a30fe55a862200bafc317f84b8c519244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveEnd (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a61fca0b55aa1ade1848e485fed102087">llvm::MipsAsmPrinter::emitFunctionBodyEnd</a>.</p>

</div>
</div>

### emitDirectiveEnt() {#a5d1753b89a18609caf60fff2f2b22584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveEnt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Symbol)</td>
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



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#adb5eb9c71ffa627ff0624341f7384954">llvm::MipsAsmPrinter::emitFunctionEntryLabel</a>.</p>

</div>
</div>

### emitDirectiveInsn() {#aca10e0f5ea5cf41e21cbaece649e895f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveInsn ()</td>
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



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a39d854dc4e07d2569f3080b5a3903446">llvm::MipsAsmPrinter::emitBasicBlockEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a5307e7e40851d56284c8f92bed1a2074">llvm::MipsTargetAsmStreamer::emitDirectiveInsn</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a2d36c8fdfd59414c759cd42c7c202fb2">llvm::MipsTargetELFStreamer::emitDirectiveInsn</a>.</p>

</div>
</div>

### emitDirectiveModuleCRC() {#a8a146469eea85ec753fd2e3fb88c06ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveModuleCRC ()</td>
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



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveModuleFP() {#afe6890c9a436aed972ee4bb882b1ddc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveModuleFP ()</td>
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



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### emitDirectiveModuleGINV() {#a8b00f2d4eff5955e1dbc71fc249abf33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveModuleGINV ()</td>
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



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveModuleHardFloat() {#ae8957ea15e88f22c75eca14739820ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveModuleHardFloat ()</td>
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



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveModuleMT() {#ae69ef849ea4b485d35669387c0611633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveModuleMT ()</td>
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



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveModuleNoCRC() {#ac1891c2902fc95b25aafb08cb1f5b8f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveModuleNoCRC ()</td>
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



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveModuleNoGINV() {#a1492b454e17c86ea6e014ba0f6a90e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveModuleNoGINV ()</td>
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



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveModuleNoVirt() {#a076087727a32d717e52affef995e820e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveModuleNoVirt ()</td>
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



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveModuleOddSPReg() {#ac8a672bc299b883b02ce5b21b4716f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveModuleOddSPReg ()</td>
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



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="#affd5266462270aa47e8e8f2e1c7e3193">ABIFlagsSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#af9af50941241644986715a4f4cfc4c1f">llvm::MipsTargetAsmStreamer::emitDirectiveModuleOddSPReg</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### emitDirectiveModuleSoftFloat() {#ab4762f03cbfd596754e1f21b39462014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveModuleSoftFloat ()</td>
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



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveModuleVirt() {#ad79d9be8aba11211b8d96072faf5cbba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveModuleVirt ()</td>
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



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveNaN2008() {#a2c5bbc82931814b855dd3b4b913adf79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveNaN2008 ()</td>
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



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### emitDirectiveNaNLegacy() {#a8fb29c2817471abc0cdc60600e196b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveNaNLegacy ()</td>
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



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### emitDirectiveOptionPic0() {#ade76bf6a3f6d11c3d0a0928d49e7aa2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveOptionPic0 ()</td>
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



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### emitDirectiveOptionPic2() {#aecd2d24b73f2f1ca5edd54e9eefd5910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveOptionPic2 ()</td>
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



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveSetArch() {#ab7214ae790fae0ca98c92d0b5a7821c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arch)</td>
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



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a01daeb5c8be5f3367d2f1ae35eeef7e1">llvm::MipsTargetAsmStreamer::emitDirectiveSetArch</a>.</p>

</div>
</div>

### emitDirectiveSetAt() {#a0596dd2ff1d68d416339fea7e40ba0fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetAt ()</td>
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



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#af51d843dc0380195cb3471f75dcdfe35">llvm::MipsTargetAsmStreamer::emitDirectiveSetAt</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a61fca0b55aa1ade1848e485fed102087">llvm::MipsAsmPrinter::emitFunctionBodyEnd</a>.</p>

</div>
</div>

### emitDirectiveSetAtWithArg() {#abb4c1638eb68607271d154cbc673ece8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetAtWithArg (unsigned RegNo)</td>
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



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ae6cd9ccd8b652d056d363261c21cd046">llvm::MipsTargetAsmStreamer::emitDirectiveSetAtWithArg</a>.</p>

</div>
</div>

### emitDirectiveSetCRC() {#a320c07dc5edc03b21abc79f04c00d062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetCRC ()</td>
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



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a82a364374c3191e3e5f10bf982490170">llvm::MipsTargetAsmStreamer::emitDirectiveSetCRC</a>.</p>

</div>
</div>

### emitDirectiveSetDsp() {#a5e91dffd3aab03752dbe6b7321259a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetDsp ()</td>
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



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#afae0ba4a47102271854073a4d61f9681">llvm::MipsTargetAsmStreamer::emitDirectiveSetDsp</a>.</p>

</div>
</div>

### emitDirectiveSetDspr2() {#a29d2ff8596f3f9ea8b36eca3cd7ce594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetDspr2 ()</td>
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



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a39a761dea2ae0f3830ee344926dec922">llvm::MipsTargetAsmStreamer::emitDirectiveSetDspr2</a>.</p>

</div>
</div>

### emitDirectiveSetFp() {#a3159a0f4c9e5c404313b18245af0a242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetFp (<a href="/web-llvm/docs/api/structs/llvm/mipsabiflagssection/#abace76eb927d4f67287e6fe14b80b427">MipsABIFlagsSection::FpABIKind</a> Value)</td>
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



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a00f91cab4f3cdb2e340a89e22b2a0eec">llvm::MipsTargetAsmStreamer::emitDirectiveSetFp</a>.</p>

</div>
</div>

### emitDirectiveSetGINV() {#a3d5f5cc266722979a8f9a32e5c7b20dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetGINV ()</td>
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



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ab45f25222667b7e5446c1132b34c7c15">llvm::MipsTargetAsmStreamer::emitDirectiveSetGINV</a>.</p>

</div>
</div>

### emitDirectiveSetHardFloat() {#a687a9e9dbe2c52708e3515bf549c2e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetHardFloat ()</td>
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



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#adbe82be8551366bdf2eadbffcdd770c4">llvm::MipsTargetAsmStreamer::emitDirectiveSetHardFloat</a>.</p>

</div>
</div>

### emitDirectiveSetMacro() {#a43f244b24701d5345baca53c8fce8f64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMacro ()</td>
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



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a7ff00c6c2ba073517fe26b316453ba71">llvm::MipsTargetAsmStreamer::emitDirectiveSetMacro</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a61fca0b55aa1ade1848e485fed102087">llvm::MipsAsmPrinter::emitFunctionBodyEnd</a>.</p>

</div>
</div>

### emitDirectiveSetMicroMips() {#aaaa11d3d36d614c29d1c63b0d1c3d9db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMicroMips ()</td>
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



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#adb5eb9c71ffa627ff0624341f7384954">llvm::MipsAsmPrinter::emitFunctionEntryLabel</a>.</p>

</div>
</div>

### emitDirectiveSetMips0() {#aaeb776dcb1b0923724c3e9acaf6d1051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips0 ()</td>
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



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ad91386c69bc4809386dd6264f2a79856">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips0</a>.</p>

</div>
</div>

### emitDirectiveSetMips1() {#a5e5eb252afdc4750051c13fad4d6f692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips1 ()</td>
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



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a3f557cddca5326be19f432bd450cfde3">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips1</a>.</p>

</div>
</div>

### emitDirectiveSetMips16() {#af36c6bb692c53b6e38238458a36a01b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips16 ()</td>
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



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#adb5eb9c71ffa627ff0624341f7384954">llvm::MipsAsmPrinter::emitFunctionEntryLabel</a>.</p>

</div>
</div>

### emitDirectiveSetMips2() {#a70b1699a55f69e1ddf10810b7ba6ad61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips2 ()</td>
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



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ae5c90ebe93b677a2af616e0eb15bb95e">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips2</a>.</p>

</div>
</div>

### emitDirectiveSetMips3() {#a4b5970f934ecff64a0b2471ac15fb184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips3 ()</td>
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



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ad73a6f50be872b69bc683d9a83cb46a5">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips3</a>.</p>

</div>
</div>

### emitDirectiveSetMips32() {#ade1b256588dce94f4879d008e97479c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips32 ()</td>
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



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a6bca5753381ba5d5855081753f7a004b">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips32</a>.</p>

</div>
</div>

### emitDirectiveSetMips32R2() {#a5bb100b60ecb733e3ad1fc666a15f417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips32R2 ()</td>
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



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a7421be129b154ceba4ecff7360f35177">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips32R2</a>.</p>

</div>
</div>

### emitDirectiveSetMips32R3() {#a5a0fb9cfc35b9ee579259dea2d444bd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips32R3 ()</td>
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



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a00f2f99b98df7069c011fb34040f79a2">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips32R3</a>.</p>

</div>
</div>

### emitDirectiveSetMips32R5() {#ae8e0f6520875562e1f575327fd71d714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips32R5 ()</td>
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



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a28ff34bf0f17e66bd9b53bd51cd62a92">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips32R5</a>.</p>

</div>
</div>

### emitDirectiveSetMips32R6() {#aeb7cc50b9fe13d9112e8e8f2ec121f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips32R6 ()</td>
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



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a6310b3b97bb8e10587573dd07a07d3d4">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips32R6</a>.</p>

</div>
</div>

### emitDirectiveSetMips3D() {#a2da861aec13177a569ed596d67c90c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips3D ()</td>
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



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ae65831c40725772b82e11689193f26fe">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips3D</a>.</p>

</div>
</div>

### emitDirectiveSetMips4() {#aec0508a0ddc18b9c7bef61267ccd2ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips4 ()</td>
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



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a499d9255ec7d3885c6c333a1274b7f4f">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips4</a>.</p>

</div>
</div>

### emitDirectiveSetMips5() {#a6f4b878b006cf365b035b4c595a703e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips5 ()</td>
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



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a1c0bc297b3766dd372e7a9fc6a6f6143">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips5</a>.</p>

</div>
</div>

### emitDirectiveSetMips64() {#af618f5b75efd1f5c6bd492969089c404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips64 ()</td>
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



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a76d56fe794122769400b0a85b5a5b4ff">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips64</a>.</p>

</div>
</div>

### emitDirectiveSetMips64R2() {#a2c5d8196410abd7683793ba3c3f20953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips64R2 ()</td>
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



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a414deff38378a08da91d015944cc6ddd">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips64R2</a>.</p>

</div>
</div>

### emitDirectiveSetMips64R3() {#a35f0d97c7a46804c80e03d27a466d55f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips64R3 ()</td>
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



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a91e2c0afccf0e34b334fa09801dae491">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips64R3</a>.</p>

</div>
</div>

### emitDirectiveSetMips64R5() {#a02b4ddd0d430be491720868fe27d784d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips64R5 ()</td>
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



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a6570e1b5c566e8153839ad2a6cb6e42b">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips64R5</a>.</p>

</div>
</div>

### emitDirectiveSetMips64R6() {#ad038888187fae9c838c150d80fd7e34c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMips64R6 ()</td>
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



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#aee10cd3ab39f114473e2997f8bd17a8b">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips64R6</a>.</p>

</div>
</div>

### emitDirectiveSetMsa() {#aea525a8a4a50b55b1db9111763902ead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMsa ()</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#aa6e826cdf05881b9ebca72b6894a6eb3">llvm::MipsTargetAsmStreamer::emitDirectiveSetMsa</a>.</p>

</div>
</div>

### emitDirectiveSetMt() {#a75dddc93169cec0751f8853487912f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetMt ()</td>
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



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a509e95256ca177d28b20e9a29b632b64">llvm::MipsTargetAsmStreamer::emitDirectiveSetMt</a>.</p>

</div>
</div>

### emitDirectiveSetNoAt() {#a8d312bb946ef4b4c6a1593c77361ac60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoAt ()</td>
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



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a20066116cd5393db79598aaf2d087a1b">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoAt</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a074ded244377552dba3a7fba6f6e4295">llvm::MipsAsmPrinter::emitFunctionBodyStart</a>.</p>

</div>
</div>

### emitDirectiveSetNoCRC() {#a0c4d4f04e5c1bdc47be5c5e26e8381b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoCRC ()</td>
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



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a23e25e63886f86b04d024d87a3f4ecf5">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoCRC</a>.</p>

</div>
</div>

### emitDirectiveSetNoDsp() {#a1cc021f2efc3e33e47c5fac5fea8d152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoDsp ()</td>
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



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a732a36dc5b5a05154d9d0ce62b06b750">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoDsp</a>.</p>

</div>
</div>

### emitDirectiveSetNoGINV() {#a50b77e3b76f8459feb014f3d6e34ef41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoGINV ()</td>
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



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a653abef52b9d2f7e46b90976cf8b658e">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoGINV</a>.</p>

</div>
</div>

### emitDirectiveSetNoMacro() {#ac3c4cd011ce562d2f3cb59ed52cbf2ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoMacro ()</td>
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



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a2f01a2185b2948ec6bb5e38e4d334eb0">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoMacro</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a074ded244377552dba3a7fba6f6e4295">llvm::MipsAsmPrinter::emitFunctionBodyStart</a>.</p>

</div>
</div>

### emitDirectiveSetNoMicroMips() {#a2261dc88d87519ce2e94ddfeece22a9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoMicroMips ()</td>
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



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#adb5eb9c71ffa627ff0624341f7384954">llvm::MipsAsmPrinter::emitFunctionEntryLabel</a>.</p>

</div>
</div>

### emitDirectiveSetNoMips16() {#a6cc9172aee17ce9ef6e36aeb49cead1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoMips16 ()</td>
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



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a6fc7851e1529b32450a8033c78c95c24">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoMips16</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#adb5eb9c71ffa627ff0624341f7384954">llvm::MipsAsmPrinter::emitFunctionEntryLabel</a>.</p>

</div>
</div>

### emitDirectiveSetNoMips3D() {#a62b30d96c3cddcef4c04ff0f1a7bc690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoMips3D ()</td>
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



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a6e4e565bb1d0e9dd249e9c4eb019a00e">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoMips3D</a>.</p>

</div>
</div>

### emitDirectiveSetNoMsa() {#ad0e4693659b749bfa70b5f7e6a4824e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoMsa ()</td>
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



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ab66870bee8b9f272d6e0f2a82bdb3f23">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoMsa</a>.</p>

</div>
</div>

### emitDirectiveSetNoMt() {#a833e5a4196c77756d8abd125378f116d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoMt ()</td>
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



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a9a400116533850f51f6172ed16602ebb">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoMt</a>.</p>

</div>
</div>

### emitDirectiveSetNoOddSPReg() {#a7da9427b4879ac386a19ee3bac750f9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoOddSPReg ()</td>
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



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a3484f22d4676b5990978279a93465492">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoOddSPReg</a>.</p>

</div>
</div>

### emitDirectiveSetNoReorder() {#ad96ce40f96e341fb3ef36c945550acc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoReorder ()</td>
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



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a074ded244377552dba3a7fba6f6e4295">llvm::MipsAsmPrinter::emitFunctionBodyStart</a>.</p>

</div>
</div>

### emitDirectiveSetNoVirt() {#a39f9efc2fc014bebdae07d5847cb3d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetNoVirt ()</td>
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



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a1dc949eef55df45404ac3dd326ef6e58">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoVirt</a>.</p>

</div>
</div>

### emitDirectiveSetOddSPReg() {#a815e926c8058ffad18bcf9bbb9745ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetOddSPReg ()</td>
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



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#af6db3aeacaa4f50951f1c56dc4bdbb3c">llvm::MipsTargetAsmStreamer::emitDirectiveSetOddSPReg</a>.</p>

</div>
</div>

### emitDirectiveSetPop() {#aa22aec4488d76be7bf6ca8c186725a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetPop ()</td>
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



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#acef2ba3129db979060a08bb8d0854fc4">llvm::MipsTargetAsmStreamer::emitDirectiveSetPop</a>.</p>

</div>
</div>

### emitDirectiveSetPush() {#a73d34999cdd0edb20d94b3555dfe1263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetPush ()</td>
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



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a6f1685dfe32354fac5deeb1ae51b7e46">llvm::MipsTargetAsmStreamer::emitDirectiveSetPush</a>.</p>

</div>
</div>

### emitDirectiveSetReorder() {#a09ac655a921f536b820733476056c75e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetReorder ()</td>
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



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#aea810c86fa3706a505fdf5f2305b0117">llvm::MipsTargetAsmStreamer::emitDirectiveSetReorder</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a61fca0b55aa1ade1848e485fed102087">llvm::MipsAsmPrinter::emitFunctionBodyEnd</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsasmparser/#adb49acf71f4529ada133ab101343bf36">anonymous{MipsAsmParser.cpp}::MipsAsmParser::onEndOfFile</a>.</p>

</div>
</div>

### emitDirectiveSetSoftFloat() {#a1ae21816069580c36a180ea513c6073a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetSoftFloat ()</td>
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



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a1cf24d43b8f82be97b761b1b9004be1a">forbidModuleDirective</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#aee98bfdeb84a34b6b39e64294a5d7f2a">llvm::MipsTargetAsmStreamer::emitDirectiveSetSoftFloat</a>.</p>

</div>
</div>

### emitDirectiveSetVirt() {#ad28f6e2510b96128cf1bce96dc7b783e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDirectiveSetVirt ()</td>
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



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ae249b4f715e26dccafb01dc03e18c86a">llvm::MipsTargetAsmStreamer::emitDirectiveSetVirt</a>.</p>

</div>
</div>

### emitDSLL() {#adb76cf6aa796861bf38a631e34717bbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitDSLL (unsigned DstReg, unsigned SrcReg, int16_t ShiftAmount, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a187cf8bd0c76fa7b07a76bdf6938c47e">emitRRI</a>.</p>

</div>
</div>

### emitEmptyDelaySlot() {#a68f176e080c458432506637ce9976533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitEmptyDelaySlot (bool hasShortDelaySlot, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="#a936108fd0c95676dd98dcfb5ca1d8773">emitRR</a>, <a href="#a187cf8bd0c76fa7b07a76bdf6938c47e">emitRRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a727a5341ff53d48d29ff8455b87d880e">hasShortDelaySlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp/#a3b2972af3f99405c0dda2d67d9155225">isMicroMips</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp/#a63320f216609dcccd140b96d0d557f84">isMips32r6</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsasmparser/#adb49acf71f4529ada133ab101343bf36">anonymous{MipsAsmParser.cpp}::MipsAsmParser::onEndOfFile</a>.</p>

</div>
</div>

### emitFMask() {#ad5507b558e355857fbc984d7ada21a55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitFMask (unsigned FPUBitmask, int FPUTopSavedRegOff)</td>
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



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a2f9c9ef300cdd17a112e9760aaf73e82">llvm::MipsAsmPrinter::printSavedRegsBitmask</a>.</p>

</div>
</div>

### emitFrame() {#a7d42fba558d9fdc684fb8b4ceb687d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitFrame (unsigned StackReg, unsigned StackSize, unsigned ReturnReg)</td>
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



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#a7ab24f34b1f8811a662826063b66f8d1">ReturnReg</a>.</p>

</div>
</div>

### emitGPRestore() {#ad4fc9cf5a21ec44d15ceae97469fd760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitGPRestore (int Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the $gp restore operation for .cprestore.</p>

<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="#ac0e9ecfd84b06cfed78760480dde161a">emitLoadWithImmOffset</a>, <a href="#a1bb3fa998cee14aa1f6e453beec1d489">GPReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitII() {#a7ff09aba59d7dcc5dd800735494b14ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitII (unsigned Opcode, int16_t Imm1, int16_t Imm2, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aae0550266742eb14bea527b1e6f6300a">llvm::MCTargetStreamer::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a580e2a6e8a248c5a4a814c03186e9241">llvm::MCInst::setLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>

</div>
</div>

### emitLoadWithImmOffset() {#ac0e9ecfd84b06cfed78760480dde161a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitLoadWithImmOffset (unsigned Opcode, unsigned DstReg, unsigned BaseReg, int64_t Offset, unsigned TmpReg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a load instruction with an immediate offset.</p>


<p>DstReg and TmpReg are permitted to be the same register iff DstReg is distinct from BaseReg and DstReg is a GPR. It is the callers responsibility to identify such cases and pass the appropriate register in TmpReg.</p>


<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="#aaac5a23f685560581a0ed18649b930af">emitRI</a>, <a href="#a187cf8bd0c76fa7b07a76bdf6938c47e">emitRRI</a>, <a href="#ab3776e68a5559151ee83323b88e9c19a">emitRRR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#ad4fc9cf5a21ec44d15ceae97469fd760">emitGPRestore</a>.</p>

</div>
</div>

### emitMask() {#a90a18fdcb6f991c1259fb9f94b05e69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitMask (unsigned CPUBitmask, int CPUTopSavedRegOff)</td>
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



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a2f9c9ef300cdd17a112e9760aaf73e82">llvm::MipsAsmPrinter::printSavedRegsBitmask</a>.</p>

</div>
</div>

### emitNop() {#ad80a575d616aab5d776fbcce52ddea85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitNop (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="#a936108fd0c95676dd98dcfb5ca1d8773">emitRR</a>, <a href="#a187cf8bd0c76fa7b07a76bdf6938c47e">emitRRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp/#a3b2972af3f99405c0dda2d67d9155225">isMicroMips</a>.</p>

</div>
</div>

### emitR() {#a49ba9fd9824c6910d3f66c1ae4469891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitR (unsigned Opcode, unsigned Reg0, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aae0550266742eb14bea527b1e6f6300a">llvm::MCTargetStreamer::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a580e2a6e8a248c5a4a814c03186e9241">llvm::MCInst::setLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>

</div>
</div>

### emitRI() {#aaac5a23f685560581a0ed18649b930af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitRI (unsigned Opcode, unsigned Reg0, int32_t Imm, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a> and <a href="#a2b33055c2d9eb274c2d980428f7a1c24">emitRX</a>.</p>


<p>Referenced by <a href="#ac0e9ecfd84b06cfed78760480dde161a">emitLoadWithImmOffset</a> and <a href="#a271310bf77ed9982cec75ffad22d2a98">emitStoreWithImmOffset</a>.</p>

</div>
</div>

### emitRR() {#a936108fd0c95676dd98dcfb5ca1d8773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitRR (unsigned Opcode, unsigned Reg0, unsigned Reg1, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a> and <a href="#a2b33055c2d9eb274c2d980428f7a1c24">emitRX</a>.</p>


<p>Referenced by <a href="#a68f176e080c458432506637ce9976533">emitEmptyDelaySlot</a> and <a href="#ad80a575d616aab5d776fbcce52ddea85">emitNop</a>.</p>

</div>
</div>

### emitRRI() {#a187cf8bd0c76fa7b07a76bdf6938c47e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitRRI (unsigned Opcode, unsigned Reg0, unsigned Reg1, int16_t Imm, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a> and <a href="#a8b10941b3ac644fb3508bc6cdc8aa6d5">emitRRX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a219c7bb0dc91e12b2b43dfc1595ce234">llvm::MipsTargetELFStreamer::emitDirectiveCpsetup</a>, <a href="#adb76cf6aa796861bf38a631e34717bbb">emitDSLL</a>, <a href="#a68f176e080c458432506637ce9976533">emitEmptyDelaySlot</a>, <a href="#ac0e9ecfd84b06cfed78760480dde161a">emitLoadWithImmOffset</a>, <a href="#ad80a575d616aab5d776fbcce52ddea85">emitNop</a> and <a href="#a271310bf77ed9982cec75ffad22d2a98">emitStoreWithImmOffset</a>.</p>

</div>
</div>

### emitRRIII() {#a09e7b7665f50b4338f746a50f6a454b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitRRIII (unsigned Opcode, unsigned Reg0, unsigned Reg1, int16_t Imm0, int16_t Imm1, int16_t Imm2, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aae0550266742eb14bea527b1e6f6300a">llvm::MCTargetStreamer::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a580e2a6e8a248c5a4a814c03186e9241">llvm::MCInst::setLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>

</div>
</div>

### emitRRR() {#ab3776e68a5559151ee83323b88e9c19a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitRRR (unsigned Opcode, unsigned Reg0, unsigned Reg1, unsigned Reg2, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a> and <a href="#a8b10941b3ac644fb3508bc6cdc8aa6d5">emitRRX</a>.</p>


<p>Referenced by <a href="#a37f96e5964d71bf0607bfe9332dcf551">emitAddu</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a219c7bb0dc91e12b2b43dfc1595ce234">llvm::MipsTargetELFStreamer::emitDirectiveCpsetup</a>, <a href="#ac0e9ecfd84b06cfed78760480dde161a">emitLoadWithImmOffset</a> and <a href="#a271310bf77ed9982cec75ffad22d2a98">emitStoreWithImmOffset</a>.</p>

</div>
</div>

### emitRRRX() {#abbac3ade2206cc952cf43e2ca4566201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitRRRX (unsigned Opcode, unsigned Reg0, unsigned Reg1, unsigned Reg2, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> Op3, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aae0550266742eb14bea527b1e6f6300a">llvm::MCTargetStreamer::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a580e2a6e8a248c5a4a814c03186e9241">llvm::MCInst::setLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>

</div>
</div>

### emitRRX() {#a8b10941b3ac644fb3508bc6cdc8aa6d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitRRX (unsigned Opcode, unsigned Reg0, unsigned Reg1, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aae0550266742eb14bea527b1e6f6300a">llvm::MCTargetStreamer::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a580e2a6e8a248c5a4a814c03186e9241">llvm::MCInst::setLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a219c7bb0dc91e12b2b43dfc1595ce234">llvm::MipsTargetELFStreamer::emitDirectiveCpsetup</a>, <a href="#a187cf8bd0c76fa7b07a76bdf6938c47e">emitRRI</a> and <a href="#ab3776e68a5559151ee83323b88e9c19a">emitRRR</a>.</p>

</div>
</div>

### emitRX() {#a2b33055c2d9eb274c2d980428f7a1c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitRX (unsigned Opcode, unsigned Reg0, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aae0550266742eb14bea527b1e6f6300a">llvm::MCTargetStreamer::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a580e2a6e8a248c5a4a814c03186e9241">llvm::MCInst::setLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a219c7bb0dc91e12b2b43dfc1595ce234">llvm::MipsTargetELFStreamer::emitDirectiveCpsetup</a>, <a href="#aaac5a23f685560581a0ed18649b930af">emitRI</a> and <a href="#a936108fd0c95676dd98dcfb5ca1d8773">emitRR</a>.</p>

</div>
</div>

### emitStoreWithImmOffset() {#a271310bf77ed9982cec75ffad22d2a98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::emitStoreWithImmOffset (unsigned Opcode, unsigned SrcReg, unsigned BaseReg, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; unsigned()&gt; GetATReg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a store instruction with an offset.</p>


<p>Emit a store instruction with an immediate offset.</p>


<p>If the offset is out of range then it will be synthesized using the assembler temporary.</p>


<p>GetATReg() is a callback that can be used to obtain the current assembler temporary and is only called when the assembler temporary is required. It must handle the case where no assembler temporary is available (typically by reporting an error).</p>


<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="#aaac5a23f685560581a0ed18649b930af">emitRI</a>, <a href="#a187cf8bd0c76fa7b07a76bdf6938c47e">emitRRI</a>, <a href="#ab3776e68a5559151ee83323b88e9c19a">emitRRR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a64e7586a1feca4613439ac07eabce3f0">llvm::MipsTargetELFStreamer::emitDirectiveCpRestore</a>.</p>

</div>
</div>

### forbidModuleDirective() {#a1cf24d43b8f82be97b761b1b9004be1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsTargetStreamer::forbidModuleDirective ()</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#aba7c57fb90825072fe1651fa67af9306">llvm::MipsTargetAsmStreamer::emitDirectiveCpAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a08fd27bcf2c6777016d5ea10cd83e548">llvm::MipsTargetELFStreamer::emitDirectiveCpAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a1d2c08fcdb60f4cf60dab2907f45c44d">llvm::MipsTargetAsmStreamer::emitDirectiveCpLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1760c43fadfe8ae62e75e7debd68fad5">llvm::MipsTargetELFStreamer::emitDirectiveCpLoad</a>, <a href="#a660db22c7980498afae281f2ee34f921">emitDirectiveCpLocal</a>, <a href="#abda7d403af17ee4b867b707bdb9d638b">emitDirectiveCpRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ab75e4f175b242522bac67cfb5dc59d33">llvm::MipsTargetAsmStreamer::emitDirectiveCpreturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#ac108b4db53de8c6f7f8d905f4db03722">llvm::MipsTargetELFStreamer::emitDirectiveCpreturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a56d51423094db4b2932d7e53c69ea140">llvm::MipsTargetAsmStreamer::emitDirectiveCpsetup</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a219c7bb0dc91e12b2b43dfc1595ce234">llvm::MipsTargetELFStreamer::emitDirectiveCpsetup</a>, <a href="#aca10e0f5ea5cf41e21cbaece649e895f">emitDirectiveInsn</a>, <a href="#ab7214ae790fae0ca98c92d0b5a7821c8">emitDirectiveSetArch</a>, <a href="#a0596dd2ff1d68d416339fea7e40ba0fc">emitDirectiveSetAt</a>, <a href="#abb4c1638eb68607271d154cbc673ece8">emitDirectiveSetAtWithArg</a>, <a href="#a5e91dffd3aab03752dbe6b7321259a42">emitDirectiveSetDsp</a>, <a href="#a29d2ff8596f3f9ea8b36eca3cd7ce594">emitDirectiveSetDspr2</a>, <a href="#a3159a0f4c9e5c404313b18245af0a242">emitDirectiveSetFp</a>, <a href="#a687a9e9dbe2c52708e3515bf549c2e54">emitDirectiveSetHardFloat</a>, <a href="#a43f244b24701d5345baca53c8fce8f64">emitDirectiveSetMacro</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a5deff2b01a03385d7a7c725ecd613d42">llvm::MipsTargetAsmStreamer::emitDirectiveSetMicroMips</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a817e80b597165a9bfb2b7467f4062d0b">llvm::MipsTargetELFStreamer::emitDirectiveSetMicroMips</a>, <a href="#aaeb776dcb1b0923724c3e9acaf6d1051">emitDirectiveSetMips0</a>, <a href="#a5e5eb252afdc4750051c13fad4d6f692">emitDirectiveSetMips1</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a4fc0801067bdb2f83bda1282c75db861">llvm::MipsTargetAsmStreamer::emitDirectiveSetMips16</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#ac73d14121a5bc81c1cc4980d87779553">llvm::MipsTargetELFStreamer::emitDirectiveSetMips16</a>, <a href="#a70b1699a55f69e1ddf10810b7ba6ad61">emitDirectiveSetMips2</a>, <a href="#a4b5970f934ecff64a0b2471ac15fb184">emitDirectiveSetMips3</a>, <a href="#ade1b256588dce94f4879d008e97479c2">emitDirectiveSetMips32</a>, <a href="#a5bb100b60ecb733e3ad1fc666a15f417">emitDirectiveSetMips32R2</a>, <a href="#a5a0fb9cfc35b9ee579259dea2d444bd1">emitDirectiveSetMips32R3</a>, <a href="#ae8e0f6520875562e1f575327fd71d714">emitDirectiveSetMips32R5</a>, <a href="#aeb7cc50b9fe13d9112e8e8f2ec121f97">emitDirectiveSetMips32R6</a>, <a href="#a2da861aec13177a569ed596d67c90c0d">emitDirectiveSetMips3D</a>, <a href="#aec0508a0ddc18b9c7bef61267ccd2ef1">emitDirectiveSetMips4</a>, <a href="#a6f4b878b006cf365b035b4c595a703e9">emitDirectiveSetMips5</a>, <a href="#af618f5b75efd1f5c6bd492969089c404">emitDirectiveSetMips64</a>, <a href="#a2c5d8196410abd7683793ba3c3f20953">emitDirectiveSetMips64R2</a>, <a href="#a35f0d97c7a46804c80e03d27a466d55f">emitDirectiveSetMips64R3</a>, <a href="#a02b4ddd0d430be491720868fe27d784d">emitDirectiveSetMips64R5</a>, <a href="#ad038888187fae9c838c150d80fd7e34c">emitDirectiveSetMips64R6</a>, <a href="#aea525a8a4a50b55b1db9111763902ead">emitDirectiveSetMsa</a>, <a href="#a8d312bb946ef4b4c6a1593c77361ac60">emitDirectiveSetNoAt</a>, <a href="#a1cc021f2efc3e33e47c5fac5fea8d152">emitDirectiveSetNoDsp</a>, <a href="#ac3c4cd011ce562d2f3cb59ed52cbf2ee">emitDirectiveSetNoMacro</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#af0f954325e613b62ad0db00f168307bd">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoMicroMips</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1be25a9d5ee50515a6b62665c8c8cb71">llvm::MipsTargetELFStreamer::emitDirectiveSetNoMicroMips</a>, <a href="#a6cc9172aee17ce9ef6e36aeb49cead1b">emitDirectiveSetNoMips16</a>, <a href="#a62b30d96c3cddcef4c04ff0f1a7bc690">emitDirectiveSetNoMips3D</a>, <a href="#ad0e4693659b749bfa70b5f7e6a4824e5">emitDirectiveSetNoMsa</a>, <a href="#a833e5a4196c77756d8abd125378f116d">emitDirectiveSetNoMt</a>, <a href="#a7da9427b4879ac386a19ee3bac750f9a">emitDirectiveSetNoOddSPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a8dc684ca1a1d2fce9a4e6bec8dc3a9bd">llvm::MipsTargetAsmStreamer::emitDirectiveSetNoReorder</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#af1456cf103019565abddab6554f0ad9a">llvm::MipsTargetELFStreamer::emitDirectiveSetNoReorder</a>, <a href="#a815e926c8058ffad18bcf9bbb9745ad9">emitDirectiveSetOddSPReg</a>, <a href="#aa22aec4488d76be7bf6ca8c186725a50">emitDirectiveSetPop</a>, <a href="#a73d34999cdd0edb20d94b3555dfe1263">emitDirectiveSetPush</a>, <a href="#a09ac655a921f536b820733476056c75e">emitDirectiveSetReorder</a>, <a href="#a1ae21816069580c36a180ea513c6073a">emitDirectiveSetSoftFloat</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ae22cc3a2a24f4a01d62f2d3806245f6a">llvm::MipsAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### getABI() {#ac6bbf7825f8f4017bd11b8af805876df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsABIInfo &amp; llvm::MipsTargetStreamer::getABI ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>References <a href="#a0149c6589bbda5a439786064155ba1ca">ABI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a08fd27bcf2c6777016d5ea10cd83e548">llvm::MipsTargetELFStreamer::emitDirectiveCpAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1760c43fadfe8ae62e75e7debd68fad5">llvm::MipsTargetELFStreamer::emitDirectiveCpLoad</a>, <a href="#a660db22c7980498afae281f2ee34f921">emitDirectiveCpLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a64e7586a1feca4613439ac07eabce3f0">llvm::MipsTargetELFStreamer::emitDirectiveCpRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#ac108b4db53de8c6f7f8d905f4db03722">llvm::MipsTargetELFStreamer::emitDirectiveCpreturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a219c7bb0dc91e12b2b43dfc1595ce234">llvm::MipsTargetELFStreamer::emitDirectiveCpsetup</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsreginforecord/#aa84b1e01b55d45024625b88ccccd4772">llvm::MipsRegInfoRecord::EmitMipsOptionRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a94031e736c9e04044ac7181147a54bf6">llvm::MipsTargetELFStreamer::finish</a>.</p>

</div>
</div>

### getABIFlagsSection() {#ada9390d1dcfdccb5558d10779ef5a058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsABIFlagsSection &amp; llvm::MipsTargetStreamer::getABIFlagsSection ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Reference <a href="#affd5266462270aa47e8e8f2e1c7e3193">ABIFlagsSection</a>.</p>

</div>
</div>

### isModuleDirectiveAllowed() {#a7651e5345a88084b8ec729848530085b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetStreamer::isModuleDirectiveAllowed ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>

</div>
</div>

### reallowModuleDirective() {#a1360ac908c09b90b3b913e2e2126092f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsTargetStreamer::reallowModuleDirective ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>

</div>
</div>

### setPic() {#a7c14a369b734721293032d25d73482b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MipsTargetStreamer::setPic (bool Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### setUsesMicroMips() {#a5288c4739dac163b342be353593c7040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetStreamer::setUsesMicroMips ()</td>
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



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#adb5eb9c71ffa627ff0624341f7384954">llvm::MipsAsmPrinter::emitFunctionEntryLabel</a>.</p>

</div>
</div>

### updateABIInfo() {#a8e9af05a3f0fd39459bb7b7ed6571680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateLibrary&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsTargetStreamer::updateABIInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PredicateLibrary &amp; P)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>References <a href="#a0149c6589bbda5a439786064155ba1ca">ABI</a>, <a href="#affd5266462270aa47e8e8f2e1c7e3193">ABIFlagsSection</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#adb5eb9c71ffa627ff0624341f7384954">llvm::MipsAsmPrinter::emitFunctionEntryLabel</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ABI {#a0149c6589bbda5a439786064155ba1ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;MipsABIInfo&gt; llvm::MipsTargetStreamer::ABI</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="#ac6bbf7825f8f4017bd11b8af805876df">getABI</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a17d3b4679a104b0852f1679b817d2070">llvm::MipsTargetELFStreamer::MipsTargetELFStreamer</a> and <a href="#a8e9af05a3f0fd39459bb7b7ed6571680">updateABIInfo</a>.</p>

</div>
</div>

### ABIFlagsSection {#affd5266462270aa47e8e8f2e1c7e3193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsABIFlagsSection llvm::MipsTargetStreamer::ABIFlagsSection</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ae498ff789c1fffa944c38d5e1dc54bf8">llvm::MipsTargetAsmStreamer::emitDirectiveModuleFP</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#af9af50941241644986715a4f4cfc4c1f">llvm::MipsTargetAsmStreamer::emitDirectiveModuleOddSPReg</a>, <a href="#ac8a672bc299b883b02ce5b21b4716f0a">emitDirectiveModuleOddSPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a00f91cab4f3cdb2e340a89e22b2a0eec">llvm::MipsTargetAsmStreamer::emitDirectiveSetFp</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#afeed6d8af2306405a117845c04177102">llvm::MipsTargetELFStreamer::emitMipsAbiFlags</a>, <a href="#ada9390d1dcfdccb5558d10779ef5a058">getABIFlagsSection</a> and <a href="#a8e9af05a3f0fd39459bb7b7ed6571680">updateABIInfo</a>.</p>

</div>
</div>

### FPRBitMask {#a065561651519e275e024f18954cafd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsTargetStreamer::FPRBitMask</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a9eeac4cc804bfa81fbf7da9e1dcff8f9">llvm::MipsTargetELFStreamer::emitFMask</a>.</p>

</div>
</div>

### FPRInfoSet {#a84cd9ea9478febeb0b364d0d1a064cf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetStreamer::FPRInfoSet</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#ada024897e55f47f93f6de1fe7fffc305">llvm::MipsTargetELFStreamer::emitDirectiveEnt</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a9eeac4cc804bfa81fbf7da9e1dcff8f9">llvm::MipsTargetELFStreamer::emitFMask</a> and <a href="#ad51f80b3e6e2aaa02181cff60e90f6d4">MipsTargetStreamer</a>.</p>

</div>
</div>

### FPROffset {#adfbfc160bd1afee7c52ccc6d70003b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MipsTargetStreamer::FPROffset</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a9eeac4cc804bfa81fbf7da9e1dcff8f9">llvm::MipsTargetELFStreamer::emitFMask</a>.</p>

</div>
</div>

### FrameInfoSet {#ad4b5a6f9e52848eeba6bbfb48ce4cb6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetStreamer::FrameInfoSet</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#ada024897e55f47f93f6de1fe7fffc305">llvm::MipsTargetELFStreamer::emitDirectiveEnt</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#aa9fe69c4c82bcd2d3a4b6ea55dd4a806">llvm::MipsTargetELFStreamer::emitFrame</a> and <a href="#ad51f80b3e6e2aaa02181cff60e90f6d4">MipsTargetStreamer</a>.</p>

</div>
</div>

### FrameOffset {#a177a753c8303e0b7a5558894e80a5e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MipsTargetStreamer::FrameOffset</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#aa9fe69c4c82bcd2d3a4b6ea55dd4a806">llvm::MipsTargetELFStreamer::emitFrame</a>.</p>

</div>
</div>

### FrameReg {#af0c812798a63fc4f676d5942454af192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsTargetStreamer::FrameReg</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#aa9fe69c4c82bcd2d3a4b6ea55dd4a806">llvm::MipsTargetELFStreamer::emitFrame</a>.</p>

</div>
</div>

### GPRBitMask {#acb0558d4415697ff95ef175530d52505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsTargetStreamer::GPRBitMask</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a92dae47a85f706dd4bec6cc0ea7f1959">llvm::MipsTargetELFStreamer::emitMask</a>.</p>

</div>
</div>

### GPReg {#a1bb3fa998cee14aa1f6e453beec1d489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsTargetStreamer::GPReg</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a08fd27bcf2c6777016d5ea10cd83e548">llvm::MipsTargetELFStreamer::emitDirectiveCpAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1760c43fadfe8ae62e75e7debd68fad5">llvm::MipsTargetELFStreamer::emitDirectiveCpLoad</a>, <a href="#a660db22c7980498afae281f2ee34f921">emitDirectiveCpLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a64e7586a1feca4613439ac07eabce3f0">llvm::MipsTargetELFStreamer::emitDirectiveCpRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#ac108b4db53de8c6f7f8d905f4db03722">llvm::MipsTargetELFStreamer::emitDirectiveCpreturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a219c7bb0dc91e12b2b43dfc1595ce234">llvm::MipsTargetELFStreamer::emitDirectiveCpsetup</a>, <a href="#ad4fc9cf5a21ec44d15ceae97469fd760">emitGPRestore</a> and <a href="#ad51f80b3e6e2aaa02181cff60e90f6d4">MipsTargetStreamer</a>.</p>

</div>
</div>

### GPRInfoSet {#a5d4a317e4d7fd84d1ae2a193a46d5d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetStreamer::GPRInfoSet</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#ada024897e55f47f93f6de1fe7fffc305">llvm::MipsTargetELFStreamer::emitDirectiveEnt</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a92dae47a85f706dd4bec6cc0ea7f1959">llvm::MipsTargetELFStreamer::emitMask</a> and <a href="#ad51f80b3e6e2aaa02181cff60e90f6d4">MipsTargetStreamer</a>.</p>

</div>
</div>

### GPROffset {#a73e12ea8a2a8bac766fbee36aac4ee20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MipsTargetStreamer::GPROffset</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a92dae47a85f706dd4bec6cc0ea7f1959">llvm::MipsTargetELFStreamer::emitMask</a>.</p>

</div>
</div>

### ReturnReg {#a7ab24f34b1f8811a662826063b66f8d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsTargetStreamer::ReturnReg</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ab08d6867bd7f09740aa8c3d1b07b9f32">llvm::MipsTargetAsmStreamer::emitFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#aa9fe69c4c82bcd2d3a4b6ea55dd4a806">llvm::MipsTargetELFStreamer::emitFrame</a> and <a href="#a7d42fba558d9fdc684fb8b4ceb687d6d">emitFrame</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ModuleDirectiveAllowed {#a3364f2c43ceef3861145f905d75decd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetStreamer::ModuleDirectiveAllowed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
