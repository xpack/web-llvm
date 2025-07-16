---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARMISelDAGToDAG.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arm-h">ARM.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">MCTargetDesc/ARMAddressingModes.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/utils/armbaseinfo-h">Utils/ARMBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">llvm/ADT/APSInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">llvm/CodeGen/SelectionDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagisel-h">llvm/CodeGen/SelectionDAGISel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "llvm/IR/IntrinsicsARM.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include &lt;optional&gt;
#include "ARMGenDAGISel.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-armiseldagtodag-cpp-">anonymous{ARMISelDAGToDAG.cpp}</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel">ARMDAGToDAGISel</a> - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> specific code to select <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> machine instructions for <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operations. <a href="/web-llvm/docs/api/namespaces/anonymous-armiseldagtodag-cpp-/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel">ARMDAGToDAGISel</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisellegacy">ARMDAGToDAGISelLegacy</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c97deb23c9a669470b42d2bd2e99f19">isInt32Immediate</a> (SDNode *N, unsigned &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isInt32Immediate - This method tests to see if the node is a 32-bit constant operand. <a href="#a7c97deb23c9a669470b42d2bd2e99f19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace33718e35b67e1af759c3ec4c8f8443">isInt32Immediate</a> (SDValue N, unsigned &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa1cb1a1d96ce454ea9056f487d718e">isOpcWithIntImmediate</a> (SDNode *N, unsigned Opc, unsigned &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff84d21c1e747c062f6a9198cf7b50d2">isScaledConstantInRange</a> (SDValue Node, int Scale, int RangeMin, int RangeMax, int &amp;ScaledConstant)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a particular node is a constant value representable as (N * Scale) where (N in [<span class="doxyComputerOutput">RangeMin</span>, <span class="doxyComputerOutput">RangeMax</span>). <a href="#aff84d21c1e747c062f6a9198cf7b50d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8e4f1811ba84f2b03bd44a549868127">shouldUseZeroOffsetLdSt</a> (SDValue N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5fffabe945940f787e1fae14feb4682">getAL</a> (SelectionDAG *CurDAG, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAL - Returns a <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">ARMCC::AL</a> immediate node. <a href="#ae5fffabe945940f787e1fae14feb4682">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b90f20408c504ab1763156fd7d3caf3">isVLDfixed</a> (unsigned Opc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65e8a317f18e8ef4236314581cd5a240">isVSTfixed</a> (unsigned Opc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b274201fdc7fbf1fc5f91a661b9410f">getVLDSTRegisterUpdateOpcode</a> (unsigned Opc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36eb7d7a2391433da8399b0c2fb9b56e">isPerfectIncrement</a> (SDValue Inc, EVT VecTy, unsigned NumVecs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given increment is a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> known to be equal to the access size performed by a NEON load/store. <a href="#a36eb7d7a2391433da8399b0c2fb9b56e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe345a54f843bde9e90095b1474084d6">SDValueToConstBool</a> (SDValue SDVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::pair&lt; unsigned, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a887c1d1c000b35aac0528c9ca2564569">getContiguousRangeOfSetBits</a> (const APInt &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201cec669c3caecff012ed5f2fe81c1e">getVectorShuffleOpcode</a> (EVT VT, unsigned Opc64[3], unsigned Opc128[3])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3cb3b8d15dadee766eed8f3eac75ff5">getIntOperandsFromRegisterString</a> (StringRef RegString, SelectionDAG *CurDAG, const SDLoc &amp;DL, std::vector&lt; SDValue &gt; &amp;Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2980b88b119166ba490ca0ca232a9ca9">getBankedRegisterMask</a> (StringRef RegString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af76eaeb7e369fcb227ebc1d1854956b6">getMClassFlagsMask</a> (StringRef Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7bca61e537185dff61903b3228d833b">getMClassRegisterMask</a> (StringRef Reg, const ARMSubtarget *Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac427af237002cfffc36dea0729964774">getARClassRegisterMask</a> (StringRef Reg, StringRef Flags)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb50377c685555d591774bad66934d24">DisableShifterOp</a>("disable-shifter-op", cl::Hidden, cl::desc("Disable isel of shifter-op"), cl::init(false))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"arm-isel"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a>&nbsp;&nbsp;&nbsp;"ARM <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Selection"</td>
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


<div class="doxySectionDef">

## Functions

### getAL() {#ae5fffabe945940f787e1fae14feb4682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue getAL (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * CurDAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>getAL - Returns a <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">ARMCC::AL</a> immediate node.</p>

<p>Definition at line 1577 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>.</p>

</div>
</div>

### getARClassRegisterMask() {#ac427af237002cfffc36dea0729964774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getARClassRegisterMask (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Flags)</td>
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



<p>Definition at line 5413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#af76eaeb7e369fcb227ebc1d1854956b6">getMClassFlagsMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getBankedRegisterMask() {#a2980b88b119166ba490ca0ca232a9ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getBankedRegisterMask (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RegString)</td>
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



<p>Definition at line 5382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#abb1344e353958db14e66ec7ab574001a">llvm::StringRef::lower</a>.</p>

</div>
</div>

### getContiguousRangeOfSetBits() {#a887c1d1c000b35aac0528c9ca2564569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; unsigned, unsigned &gt; &gt; getContiguousRangeOfSetBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A)</td>
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



<p>Definition at line 3529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

### getIntOperandsFromRegisterString() {#ac3cb3b8d15dadee766eed8f3eac75ff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getIntOperandsFromRegisterString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RegString, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * CurDAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops)</td>
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



<p>Definition at line 5354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>

</div>
</div>

### getMClassFlagsMask() {#af76eaeb7e369fcb227ebc1d1854956b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getMClassFlagsMask (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Flags)</td>
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



<p>Definition at line 5392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a> and <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>


<p>Referenced by <a href="#ac427af237002cfffc36dea0729964774">getARClassRegisterMask</a>.</p>

</div>
</div>

### getMClassRegisterMask() {#ac7bca61e537185dff61903b3228d833b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getMClassRegisterMask (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> * Subtarget)</td>
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



<p>Definition at line 5405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getVectorShuffleOpcode() {#a201cec669c3caecff012ed5f2fe81c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getVectorShuffleOpcode (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned Opc64=[3], unsigned Opc128=[3])</td>
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



<p>Definition at line 3611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6db1f207286bd8bc6a978593a55955e9">llvm::EVT::is128BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#afa40b0ea2c1858e1e297227cc17d77db">llvm::EVT::is64BitVector</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>.</p>

</div>
</div>

### getVLDSTRegisterUpdateOpcode() {#a3b274201fdc7fbf1fc5f91a661b9410f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getVLDSTRegisterUpdateOpcode (unsigned Opc)</td>
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



<p>Definition at line 2027 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6b90f20408c504ab1763156fd7d3caf3">isVLDfixed</a> and <a href="#a65e8a317f18e8ef4236314581cd5a240">isVSTfixed</a>.</p>

</div>
</div>

### isInt32Immediate() {#a7c97deb23c9a669470b42d2bd2e99f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isInt32Immediate (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned &amp; Imm)</td>
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

<p>isInt32Immediate - This method tests to see if the node is a 32-bit constant operand.</p>


<p>If so Imm will receive the 32-bit value.</p>


<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aac2f0a84dd2aa5ee4c3f1385e9565f5e">llvm::ISD::Constant</a>, <a href="#a7c97deb23c9a669470b42d2bd2e99f19">isInt32Immediate</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a7c97deb23c9a669470b42d2bd2e99f19">isInt32Immediate</a>, <a href="#ace33718e35b67e1af759c3ec4c8f8443">isInt32Immediate</a>, <a href="#a5fa1cb1a1d96ce454ea9056f487d718e">isOpcWithIntImmediate</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a678f88e041ed213103cc705ea75323a7">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::isRotateAndMask</a>.</p>

</div>
</div>

### isInt32Immediate() {#ace33718e35b67e1af759c3ec4c8f8443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isInt32Immediate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned &amp; Imm)</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a7c97deb23c9a669470b42d2bd2e99f19">isInt32Immediate</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isOpcWithIntImmediate() {#a5fa1cb1a1d96ce454ea9056f487d718e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isOpcWithIntImmediate (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned Opc, unsigned &amp; Imm)</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a7c97deb23c9a669470b42d2bd2e99f19">isInt32Immediate</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#aef3ca350fa266bbc7d421597cae9f11d">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::PreprocessISelDAG</a>.</p>

</div>
</div>

### isPerfectIncrement() {#a36eb7d7a2391433da8399b0c2fb9b56e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isPerfectIncrement (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Inc, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VecTy, unsigned NumVecs)</td>
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

<p>Returns true if the given increment is a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> known to be equal to the access size performed by a NEON load/store.</p>


<p>This means the "[rN]!" form can be used.</p>


<p>Definition at line 2101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>.</p>

</div>
</div>

### isScaledConstantInRange() {#aff84d21c1e747c062f6a9198cf7b50d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isScaledConstantInRange (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Node, int Scale, int RangeMin, int RangeMax, int &amp; ScaledConstant)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a particular node is a constant value representable as (N * Scale) where (N in [<span class="doxyComputerOutput">RangeMin</span>, <span class="doxyComputerOutput">RangeMax</span>).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ScaledConstant</td>
<td class="doxyParamItemDescription"><p>[out] - On success, the pre-scaled constant value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a97fccf6d0a26eb7a492eeecb241a93d0">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::IsAddressingMode5</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ac2a883d3da363288434a1110d9c275f0">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode2OffsetImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a60b48230d0fc952979f69fd95557ab3c">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode2OffsetImmPre</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a54dfd9d8e05d4813fa85c9877c0e270a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode2OffsetReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#abb5c2f66d44327ca2fceb3bf57801150">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode3</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a2831c4e1d62a6a8ebe8754d541736f1b">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode3Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a19417d4f56c31835cfe0cd676435301a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectImmediateInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a8485253be2e78195ae26f28df0dd41d4">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectLdStSOReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a4940db05905a9e557815bb2d99a5738f">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeImm7</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a9b71ec795bacb8b14faaed9a9e4ac5c3">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeImm7Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#aec753c15bbadb0f5a4790c6894e5fcf9">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeImm8</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a5d23fd57cf4c733f4a9d76ae11f00b4a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeImm8Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#adf95459d72259dcba7c222a194d09439">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectTAddrModeImm7</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a67de03b6453d6cb0302cb42a21351422">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeImm5S</a> and <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a01be2a14188ac612c910c9043ae037e1">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeSP</a>.</p>

</div>
</div>

### isVLDfixed() {#a6b90f20408c504ab1763156fd7d3caf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isVLDfixed (unsigned Opc)</td>
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



<p>Definition at line 1954 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a3b274201fdc7fbf1fc5f91a661b9410f">getVLDSTRegisterUpdateOpcode</a>.</p>

</div>
</div>

### isVSTfixed() {#a65e8a317f18e8ef4236314581cd5a240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isVSTfixed (unsigned Opc)</td>
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



<p>Definition at line 1996 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a3b274201fdc7fbf1fc5f91a661b9410f">getVLDSTRegisterUpdateOpcode</a>.</p>

</div>
</div>

### SDValueToConstBool() {#afe345a54f843bde9e90095b1474084d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SDValueToConstBool (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> SDVal)</td>
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



<p>Definition at line 2694 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a5cb49674ec65724b4d9aecb48588a13a">llvm::ConstantSDNode::getZExtValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### shouldUseZeroOffsetLdSt() {#ae8e4f1811ba84f2b03bd44a549868127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldUseZeroOffsetLdSt (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 1113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a67de03b6453d6cb0302cb42a21351422">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeImm5S</a> and <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a9a153a18768a8b602fbac7c74461fdce">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeRR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DisableShifterOp {#acb50377c685555d591774bad66934d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableShifterOp("disable-shifter-op", cl::Hidden, cl::desc("Disable isel of shifter-op"), cl::init(false))</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a32d2decc2fbd86ebc9e635bc3aaf56d9">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectImmShifterOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ab301fda1e7e3cd7b76586ed7233df73a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectRegShifterOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"arm-isel"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### PASS\_NAME {#acf9235cddac26ff3f81e8c56849bcaac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PASS_NAME&nbsp;&nbsp;&nbsp;"ARM <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Selection"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp">ARMISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
