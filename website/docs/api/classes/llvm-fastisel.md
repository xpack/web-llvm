---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/fastisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FastISel` Class Reference

<p>This is a fast-path instruction selection class that generates poor code and doesn't support illegal types or non-trivial lowering, but runs quickly. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FastISel { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">llvm/CodeGen/FastISel.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel">AArch64FastISel</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armfastisel-cpp-/armfastisel">ARMFastISel</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel">MipsFastISel</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-ppcfastisel-cpp-/ppcfastisel">PPCFastISel</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-webassemblyfastisel-cpp-/webassemblyfastisel">WebAssemblyFastISel</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel">X86FastISel</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affd936c53b642934d3fce6b6919fea4d">ArgListEntry</a> = <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/arglistentry">TargetLoweringBase::ArgListEntry</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82396eecbe0fb665491b6c75be3a5713">ArgListTy</a> = <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4ac6bc14db22dbd7b94a3b1bd276796">TargetLoweringBase::ArgListTy</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc58554c43194546f38ed54efd897ec8">SavePoint</a> = <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a> (FunctionLoweringInfo &amp;FuncInfo, const TargetLibraryInfo *LibInfo, bool SkipTargetIndependentISel=false)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb0278799e68968933127f7b9de1550c">~FastISel</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a376bebd788584bb9147314011dd769c9">getLastLocalValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the position of the last instruction emitted for materializing constants for use in the current block. <a href="#a376bebd788584bb9147314011dd769c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bfa1f986356fdcdcab1c98dcf9a84e5">setLastLocalValue</a> (MachineInstr *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the position of the last instruction emitted for materializing constants for use in the current block. <a href="#a0bfa1f986356fdcdcab1c98dcf9a84e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a4d1b2ae70640755d4942597b65376e">startNewBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the current block to which generated machine instructions will be appended. <a href="#a6a4d1b2ae70640755d4942597b65376e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa419164af59a2a951db9a64f81d35084">finishBasicBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flush the local value map. <a href="#aa419164af59a2a951db9a64f81d35084">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b9c043f8fa0596f84e3bf6b25db66a">getCurDebugLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return current debug location information. <a href="#a96b9c043f8fa0596f84e3bf6b25db66a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69b4cef553644304e69e8d671bd5c1c">lowerArguments</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do "fast" instruction selection for function arguments and append the machine instructions to the current block. <a href="#ae69b4cef553644304e69e8d671bd5c1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82e8b29a5326fe0dc88bf14c244a1b0d">selectInstruction</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do "fast" instruction selection for the given LLVM IR instruction and append the generated machine instructions to the current block. <a href="#a82e8b29a5326fe0dc88bf14c244a1b0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a> (const User *I, unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do "fast" instruction selection for the given LLVM IR operator (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> or <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a>), and append generated machine instructions to the current block. <a href="#ab30094b924bc7333b5bf134d7985ca18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a virtual register and arrange for it to be assigned the value for the given LLVM value. <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa01ecad5fa09c3afd2f9cdc2a50d707a">lookUpRegForValue</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up the value to see if its value is already cached in a register. <a href="#aa01ecad5fa09c3afd2f9cdc2a50d707a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5997c4992589047ebc712b52b6e101cb">getRegForGEPIndex</a> (MVT PtrVT, const Value *Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a wrapper around getRegForValue that also takes care of truncating or sign-extending the given getelementptr index value. <a href="#a5997c4992589047ebc712b52b6e101cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a81ca548cc88df15a58aed766bdd890">tryToFoldLoad</a> (const LoadInst *LI, const Instruction *FoldInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We're checking to see if we can fold <span class="doxyComputerOutput">LI</span> into <span class="doxyComputerOutput">FoldInst</span>. <a href="#a5a81ca548cc88df15a58aed766bdd890">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73773042077892da5c7a6b3f8435a175">tryToFoldLoadIntoMI</a> (MachineInstr *, unsigned, const LoadInst *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specified machine instr operand is a vreg, and that vreg is being provided by the specified load instruction. <a href="#a73773042077892da5c7a6b3f8435a175">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5337d3078000bf9b580b28031136af">recomputeInsertPt</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset InsertPt to prepare for inserting instructions into the current block. <a href="#acb5337d3078000bf9b580b28031136af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6066bf2100d34651261866662b42114e">removeDeadCode</a> (MachineBasicBlock::iterator I, MachineBasicBlock::iterator E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all dead instructions between the I and E. <a href="#a6066bf2100d34651261866662b42114e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abc58554c43194546f38ed54efd897ec8">SavePoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb72b2e2b8be6ec3392c569dc53db16f">enterLocalValueArea</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepare InsertPt to begin inserting instructions into the local value area and return the old insert position. <a href="#aeb72b2e2b8be6ec3392c569dc53db16f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3efed0ded914901e7d8741227dfcd249">leaveLocalValueArea</a> (SavePoint Old)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset InsertPt to the given old insert position. <a href="#a3efed0ded914901e7d8741227dfcd249">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52bb01c018d9c9a9bda3d127ab5c7189">handleDbgInfo</a> (const Instruction *II)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-independent lowering of non-instruction debug info associated with this instruction. <a href="#a52bb01c018d9c9a9bda3d127ab5c7189">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1e4ca49328979aa5ddd8e4285e23e3">fastSelectInstruction</a> (const Instruction *I)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code when the normal <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> process fails to select an instruction. <a href="#acc1e4ca49328979aa5ddd8e4285e23e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b32a3c62f5c8ad8f9b9610cc3e5707c">fastLowerArguments</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to do target- specific argument lowering. <a href="#a9b32a3c62f5c8ad8f9b9610cc3e5707c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a6a1f860beb28f193b8313fee58df9b">fastLowerCall</a> (CallLoweringInfo &amp;CLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to do target- specific call lowering. <a href="#a8a6a1f860beb28f193b8313fee58df9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3231fc07f21bf85a28500d24e157282c">fastLowerIntrinsicCall</a> (const IntrinsicInst *II)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to do target- specific intrinsic lowering. <a href="#a3231fc07f21bf85a28500d24e157282c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a813993b16270d29cb0d76fa76140e424">fastEmit_</a> (MVT VT, MVT RetVT, unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to request that an instruction with the given type and opcode be emitted. <a href="#a813993b16270d29cb0d76fa76140e424">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2202cab3109536077a683bcd326fe55">fastEmit_r</a> (MVT VT, MVT RetVT, unsigned Opcode, unsigned Op0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to request that an instruction with the given type, opcode, and register operand be emitted. <a href="#af2202cab3109536077a683bcd326fe55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfe921ad48553b0de6fe092d66e54671">fastEmit_rr</a> (MVT VT, MVT RetVT, unsigned Opcode, unsigned Op0, unsigned Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to request that an instruction with the given type, opcode, and register operands be emitted. <a href="#acfe921ad48553b0de6fe092d66e54671">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c42eef34e00640e9c0edc553e50d5dd">fastEmit_ri</a> (MVT VT, MVT RetVT, unsigned Opcode, unsigned Op0, uint64_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to request that an instruction with the given type, opcode, and register and immediate operands be emitted. <a href="#a3c42eef34e00640e9c0edc553e50d5dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7a01123cf8a0e7acd2b089c65957b26">fastEmit_ri_</a> (MVT VT, unsigned Opcode, unsigned Op0, uint64_t Imm, MVT ImmType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is a wrapper of fastEmit_ri. <a href="#ad7a01123cf8a0e7acd2b089c65957b26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb35ef59bf683a0ff72f447a5ae92f27">fastEmit_i</a> (MVT VT, MVT RetVT, unsigned Opcode, uint64_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to request that an instruction with the given type, opcode, and immediate operand be emitted. <a href="#afb35ef59bf683a0ff72f447a5ae92f27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987b8990145af270282c52928f7ed220">fastEmit_f</a> (MVT VT, MVT RetVT, unsigned Opcode, const ConstantFP *FPImm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to request that an instruction with the given type, opcode, and floating-point immediate operand be emitted. <a href="#a987b8990145af270282c52928f7ed220">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b5f2bc37d0cd978d8f38c2b14aabaf7">fastEmitInst_</a> (unsigned MachineInstOpcode, const TargetRegisterClass *RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with no operands and a result register in the given register class. <a href="#a2b5f2bc37d0cd978d8f38c2b14aabaf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43873dfd861406dc9da68ddcd2bfe1bc">fastEmitInst_r</a> (unsigned MachineInstOpcode, const TargetRegisterClass *RC, unsigned Op0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with one register operand and a result register in the given register class. <a href="#a43873dfd861406dc9da68ddcd2bfe1bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d85017ca59fd0d13bde23551dfc5f90">fastEmitInst_rr</a> (unsigned MachineInstOpcode, const TargetRegisterClass *RC, unsigned Op0, unsigned Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with two register operands and a result register in the given register class. <a href="#a8d85017ca59fd0d13bde23551dfc5f90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe20d43bd5edcb69d1a401105ad3d38e">fastEmitInst_rrr</a> (unsigned MachineInstOpcode, const TargetRegisterClass *RC, unsigned Op0, unsigned Op1, unsigned Op2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with three register operands and a result register in the given register class. <a href="#afe20d43bd5edcb69d1a401105ad3d38e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef1cb331526de21d6b1729a42a72d74f">fastEmitInst_ri</a> (unsigned MachineInstOpcode, const TargetRegisterClass *RC, unsigned Op0, uint64_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with a register operand, an immediate, and a result register in the given register class. <a href="#aef1cb331526de21d6b1729a42a72d74f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91124ff314dcb25457d0a4bd31fa5c52">fastEmitInst_rii</a> (unsigned MachineInstOpcode, const TargetRegisterClass *RC, unsigned Op0, uint64_t Imm1, uint64_t Imm2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with one register operand and two immediate operands. <a href="#a91124ff314dcb25457d0a4bd31fa5c52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7be31f2606d1565335458953610fcd">fastEmitInst_f</a> (unsigned MachineInstOpcode, const TargetRegisterClass *RC, const ConstantFP *FPImm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with a floating point immediate, and a result register in the given register class. <a href="#aba7be31f2606d1565335458953610fcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae348a9f69bb94b326d0e722c74dfaf7b">fastEmitInst_rri</a> (unsigned MachineInstOpcode, const TargetRegisterClass *RC, unsigned Op0, unsigned Op1, uint64_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with two register operands, an immediate, and a result register in the given register class. <a href="#ae348a9f69bb94b326d0e722c74dfaf7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a738eff0daa8e9f33ff056da16adefb4d">fastEmitInst_i</a> (unsigned MachineInstOpcode, const TargetRegisterClass *RC, uint64_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with a single immediate operand, and a result register in the given register class. <a href="#a738eff0daa8e9f33ff056da16adefb4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ab338e9e5f4ea24b2049ab525525bf">fastEmitInst_extractsubreg</a> (MVT RetVT, unsigned Op0, uint32_t Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> for an extract_subreg from a specified index of a superregister to a specified type. <a href="#a03ab338e9e5f4ea24b2049ab525525bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9378963a44c6d0e07ea95c821442cc5">fastEmitZExtFromI1</a> (MVT VT, unsigned Op0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit MachineInstrs to compute the value of <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> with all but the least significant bit set to zero. <a href="#ad9378963a44c6d0e07ea95c821442cc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8715812b9f4dd2bd46163dd1b51128">fastEmitBranch</a> (MachineBasicBlock *MSucc, const DebugLoc &amp;DbgLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an unconditional branch to the given block, unless it is the immediate (fall-through) successor, and update the CFG. <a href="#a1b8715812b9f4dd2bd46163dd1b51128">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb4626a91d27266548cba7efedc6fe6">finishCondBranch</a> (const BasicBlock *BranchBB, MachineBasicBlock *TrueMBB, MachineBasicBlock *FalseMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an unconditional branch to <span class="doxyComputerOutput">FalseMBB</span>, obtains the branch weight and adds TrueMBB and FalseMBB to the successor list. <a href="#aebb4626a91d27266548cba7efedc6fe6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a> (const Value *I, Register Reg, unsigned NumRegs=1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the value map to include the new mapping for this instruction, or insert an extra copy to get the result in a previous determined register. <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a981679659ff46a72dc913da01553667a">createResultReg</a> (const TargetRegisterClass *RC)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a> (const MCInstrDesc &amp;II, Register Op, unsigned OpNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to constrain <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> so that it is usable by argument OpNum of the provided <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a>. <a href="#abb968323ca61fa5d8e99b4523a08f2b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ab744fe6e49b1d9eaa927ec7e292b4">fastMaterializeConstant</a> (const Constant *C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a constant in a register using target-specific logic, such as constant pool loads. <a href="#a85ab744fe6e49b1d9eaa927ec7e292b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4de0df44bcf2e480a2005c6304d9fda">fastMaterializeAlloca</a> (const AllocaInst *C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an alloca address in a register using target-specific logic. <a href="#af4de0df44bcf2e480a2005c6304d9fda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20ec9b646b1726ea156e23cb0f965840">fastMaterializeFloatZero</a> (const ConstantFP *CF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the floating-point constant +0.0 in a register using target- specific logic. <a href="#a20ec9b646b1726ea156e23cb0f965840">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d784ad1fd74a55994d44d0d3ac39b5e">canFoldAddIntoGEP</a> (const User *GEP, const Value *Add)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">Add</span> is an add that can be safely folded into <span class="doxyComputerOutput">GEP</span>. <a href="#a7d784ad1fd74a55994d44d0d3ac39b5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bec3fdf48dcde80a42b76f09d151a03">createMachineMemOperandFor</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a machine mem operand from the given instruction. <a href="#a6bec3fdf48dcde80a42b76f09d151a03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa26a7d0b19ce017fda518be95485fb8e">optimizeCmpPredicate</a> (const CmpInst *CI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a429785d5b6015aff39a7a998d9e70fa3">lowerCallTo</a> (const CallInst *CI, MCSymbol *Symbol, unsigned NumArgs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac50c544ca2ade87e7ad0dd6afccdf84c">lowerCallTo</a> (const CallInst *CI, const char *SymName, unsigned NumArgs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284bf291d22c5fe81d9cae4b4f1a4fea">lowerCallTo</a> (CallLoweringInfo &amp;CLI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c0cdb3908fc8b0f795f411e32bb806e">lowerCall</a> (const CallInst *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac399325c88de95b03c19e68e1229a8f7">selectBinaryOp</a> (const User *I, unsigned ISDOpcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select and emit code for a binary operator instruction, which has an opcode which directly corresponds to the given <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a> opcode. <a href="#ac399325c88de95b03c19e68e1229a8f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b79346e8152f683a6ad35f8049c74ea">selectFNeg</a> (const User *I, const Value *In)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an FNeg operation. <a href="#a9b79346e8152f683a6ad35f8049c74ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09eed569d7f0359be47433ca90532f81">selectGetElementPtr</a> (const User *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f9992c5e3a519e4128db320ba2d2e18">selectStackmap</a> (const CallInst *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8bc20b89a02f7d1d402a9fb561d1717">selectPatchpoint</a> (const CallInst *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f7b01772fb64eab764bc071e84b860e">selectCall</a> (const User *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a> (const IntrinsicInst *II)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedd7b25487ab7f0871e3d722c1766c18">selectBitCast</a> (const User *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5718bb42ac48e382b259cd668ad38e21">selectFreeze</a> (const User *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ec796e4ddba85e210d5a226d56f16f">selectCast</a> (const User *I, unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1434fc5d1782f15a392af0320f13f6c7">selectExtractValue</a> (const User *U)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284276bdba816c71f6c16ee08e842b41">selectXRayCustomEvent</a> (const CallInst *II)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c80b7d55789b6712c22642d4f94b90d">selectXRayTypedEvent</a> (const CallInst *II)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf5f7ebfb9fc299fc26be405cbc4e82f">shouldOptForSize</a> (const MachineFunction *MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb536540d37a55860c52b81778b013e">lowerDbgValue</a> (const Value *V, DIExpression *Expr, DILocalVariable *Var, const DebugLoc &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-independent lowering of debug information. <a href="#a7eb536540d37a55860c52b81778b013e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352ccfab7392a21f5253bca1791022d5">lowerDbgDeclare</a> (const Value *V, DIExpression *Expr, DILocalVariable *Var, const DebugLoc &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-independent lowering of debug information. <a href="#a352ccfab7392a21f5253bca1791022d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29191a0d9a9d50a378d445268e9bf93c">handlePHINodesInSuccessorBlocks</a> (const BasicBlock *LLVMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle PHI nodes in successor blocks. <a href="#a29191a0d9a9d50a378d445268e9bf93c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ff6834a4ddd317a7b1ff922be35317">materializeConstant</a> (const Value *V, MVT VT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for materializeRegForValue to materialize a constant in a target-independent way. <a href="#a12ff6834a4ddd317a7b1ff922be35317">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac682208151aca3dafa5a56cd60043a4d">materializeRegForValue</a> (const Value *V, MVT VT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for getRegForVale. <a href="#ac682208151aca3dafa5a56cd60043a4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15907e93c7ef14c7a6785de682ca38b0">flushLocalValueMap</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clears LocalValueMap and moves the area for the new local variables to the beginning of the block. <a href="#a15907e93c7ef14c7a6785de682ca38b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1db188d7aed06e56642c5890fa5adc8f">removeDeadLocalValueCode</a> (MachineInstr *SavedLastLocalValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes dead local value instructions after SavedLastLocalvalue. <a href="#a1db188d7aed06e56642c5890fa5adc8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5be01d3a07be840817fab33ea35d9e2">addStackMapLiveVars</a> (SmallVectorImpl&lt; MachineOperand &gt; &amp;Ops, const CallInst *CI, unsigned StartIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a stackmap or patchpoint intrinsic call's live variable operands to a stackmap or patchpoint machine instruction. <a href="#ae5be01d3a07be840817fab33ea35d9e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ebe817f1251f532120f40785ea326f6">lowerCallOperands</a> (const CallInst *CI, unsigned ArgIdx, unsigned NumArgs, const Value *Callee, bool ForceRetVoidTy, CallLoweringInfo &amp;CLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower an argument list according to the target calling convention. <a href="#a9ebe817f1251f532120f40785ea326f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b59baac25d2130c5fde409d31c0f51c">LocalValueMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79d5f0dde17b382c909b9806e9436592">MF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018554adfdbafed22851faa4e25cd4af">MRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b79f09f234c1ef637c6d5a4b91e4cc">MFI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd2a710e355d42b82717424f14b1d89">MCP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mimetadata">MIMetadata</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1634563b73a5a9df8b459d913fa4943">TM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a067a743bcdf919af7f64f48631be87fd">DL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accec713e7a93d7b67101624dadf04c98">TLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe0bba218f685c37e6c1ca4b49d2d1f1">TRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06203f8be451bbf280e15b45a1b20224">LibInfo</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7759506c93231c973c2c96665bd6e73">SkipTargetIndependentISel</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade66ed1ba84375d666af381e0153d038">LastLocalValue</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The position of the last instruction for materializing constants for use in the current block. <a href="#ade66ed1ba84375d666af381e0153d038">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f3e11725f5ce0ddf65a31783872863">EmitStartPt</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The top most instruction in the current block that is allowed for emitting local variables. <a href="#a24f3e11725f5ce0ddf65a31783872863">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f55a36c2eb53a2ddda81148868dfd9">SavedInsertPt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insertion point before trying to select the current instruction. <a href="#a35f55a36c2eb53a2ddda81148868dfd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is a fast-path instruction selection class that generates poor code and doesn't support illegal types or non-trivial lowering, but runs quickly.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ArgListEntry {#affd936c53b642934d3fce6b6919fea4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::FastISel::ArgListEntry =  TargetLoweringBase::ArgListEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>

</div>
</div>

### ArgListTy {#a82396eecbe0fb665491b6c75be3a5713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::FastISel::ArgListTy =  TargetLoweringBase::ArgListTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>

</div>
</div>

### SavePoint {#abc58554c43194546f38ed54efd897ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::FastISel::SavePoint =  MachineBasicBlock::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### FastISel() {#ac447d383d507dc43c984bd02ff8e74ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel::FastISel (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * LibInfo, bool SkipTargetIndependentISel=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1931 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="#a06203f8be451bbf280e15b45a1b20224">LibInfo</a>, <a href="#aacd2a710e355d42b82717424f14b1d89">MCP</a>, <a href="#a79d5f0dde17b382c909b9806e9436592">MF</a>, <a href="#a79b79f09f234c1ef637c6d5a4b91e4cc">MFI</a>, <a href="#a018554adfdbafed22851faa4e25cd4af">MRI</a>, <a href="#ab7759506c93231c973c2c96665bd6e73">SkipTargetIndependentISel</a>, <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a>, <a href="#ad1634563b73a5a9df8b459d913fa4943">TM</a> and <a href="#afe0bba218f685c37e6c1ca4b49d2d1f1">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a1bc852ad7149319b7a54dccd62e77b8f">anonymous{AArch64FastISel.cpp}::AArch64FastISel::AArch64FastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-armfastisel-cpp-/armfastisel/#ac8e1ee94bced949e039028f65dc5784d">anonymous{ARMFastISel.cpp}::ARMFastISel::ARMFastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#ae62d9e89cea91d950a28eee7e5a32088">anonymous{MipsFastISel.cpp}::MipsFastISel::MipsFastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcfastisel-cpp-/ppcfastisel/#a0bdf1d28924ab8477bdbdb193c29fb68">anonymous{PPCFastISel.cpp}::PPCFastISel::PPCFastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyfastisel-cpp-/webassemblyfastisel/#a6e71c29d48aa6b75ec5a0ab52b28e67d">anonymous{WebAssemblyFastISel.cpp}::WebAssemblyFastISel::WebAssemblyFastISel</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa2401a1ee0b3876ea3c1cdfe7cd643bf">anonymous{X86FastISel.cpp}::X86FastISel::X86FastISel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~FastISel() {#afb0278799e68968933127f7b9de1550c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel::~FastISel ()</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enterLocalValueArea() {#aeb72b2e2b8be6ec3392c569dc53db16f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel::SavePoint FastISel::enterLocalValueArea ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prepare InsertPt to begin inserting instructions into the local value area and return the old insert position.</p>

<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a> and <a href="#acb5337d3078000bf9b580b28031136af">recomputeInsertPt</a>.</p>


<p>Referenced by <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>.</p>

</div>
</div>

### finishBasicBlock() {#aa419164af59a2a951db9a64f81d35084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FastISel::finishBasicBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flush the local value map.</p>

<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>

</div>
</div>

### getCurDebugLoc() {#a96b9c043f8fa0596f84e3bf6b25db66a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::FastISel::getCurDebugLoc ()</td>
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

<p>Return current debug location information.</p>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Reference <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>.</p>

</div>
</div>

### getLastLocalValue() {#a376bebd788584bb9147314011dd769c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::FastISel::getLastLocalValue ()</td>
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

<p>Return the position of the last instruction emitted for materializing constants for use in the current block.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Reference <a href="#ade66ed1ba84375d666af381e0153d038">LastLocalValue</a>.</p>


<p>Referenced by <a href="#acb5337d3078000bf9b580b28031136af">recomputeInsertPt</a> and <a href="#a82e8b29a5326fe0dc88bf14c244a1b0d">selectInstruction</a>.</p>

</div>
</div>

### getRegForGEPIndex() {#a5997c4992589047ebc712b52b6e101cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::getRegForGEPIndex (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> PtrVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a wrapper around getRegForValue that also takes care of truncating or sign-extending the given getelementptr index value.</p>

<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a3ad406477784397709a339d5a2957b43">llvm::EVT::bitsGT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3bf257bfbd279ecfad670be03b00210e">llvm::EVT::bitsLT</a>, <a href="#af2202cab3109536077a683bcd326fe55">fastEmit_r</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>.</p>


<p>Referenced by <a href="#a09eed569d7f0359be47433ca90532f81">selectGetElementPtr</a>.</p>

</div>
</div>

### getRegForValue() {#a5cec24eb4eadf1232a1463fdbb1cc1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::getRegForValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a virtual register and arrange for it to be assigned the value for the given LLVM value.</p>

<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="#aeb72b2e2b8be6ec3392c569dc53db16f">enterLocalValueArea</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="#a3efed0ded914901e7d8741227dfcd249">leaveLocalValueArea</a>, <a href="#aa01ecad5fa09c3afd2f9cdc2a50d707a">lookUpRegForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a>.</p>


<p>Referenced by <a href="#ad7a01123cf8a0e7acd2b089c65957b26">fastEmit_ri_</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a246d108e7d516b651024d7ab2a75e9be">anonymous{X86FastISel.cpp}::X86FastISel::fastSelectInstruction</a>, <a href="#a5997c4992589047ebc712b52b6e101cb">getRegForGEPIndex</a>, <a href="#a7eb536540d37a55860c52b81778b013e">lowerDbgValue</a>, <a href="#ac399325c88de95b03c19e68e1229a8f7">selectBinaryOp</a>, <a href="#aedd7b25487ab7f0871e3d722c1766c18">selectBitCast</a>, <a href="#a59ec796e4ddba85e210d5a226d56f16f">selectCast</a>, <a href="#a9b79346e8152f683a6ad35f8049c74ea">selectFNeg</a>, <a href="#a5718bb42ac48e382b259cd668ad38e21">selectFreeze</a>, <a href="#a09eed569d7f0359be47433ca90532f81">selectGetElementPtr</a>, <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>, <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>, <a href="#ac8bc20b89a02f7d1d402a9fb561d1717">selectPatchpoint</a>, <a href="#a284276bdba816c71f6c16ee08e842b41">selectXRayCustomEvent</a>, <a href="#a8c80b7d55789b6712c22642d4f94b90d">selectXRayTypedEvent</a> and <a href="#a5a81ca548cc88df15a58aed766bdd890">tryToFoldLoad</a>.</p>

</div>
</div>

### handleDbgInfo() {#a52bb01c018d9c9a9bda3d127ab5c7189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FastISel::handleDbgInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-independent lowering of non-instruction debug info associated with this instruction.</p>

<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7f54f5772ba80cc1f7c4a92203f14e57">llvm::MachineInstrBuilder::addMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca185b7133db22230701a857c059360cc2">llvm::DbgVariableRecord::Assign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca2709046ed364cc54b91f908e85e512ed">llvm::DbgVariableRecord::Declare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a3a0f4e00c3f6345c52c6acd178b3fca3">llvm::DbgRecord::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a8ec5a479378113fc24b647afa2f06ee5">llvm::DbgVariableRecord::getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a1adb590f8f0ceed777898888ed5db7ac">llvm::DbgVariableRecord::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#aa774c62045e74bb457b32713c0670696">llvm::DbgVariableRecord::getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a99dac64e3a954ffbcbf1fc6726a743a2">llvm::DbgVariableRecord::getVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#af9c8103c773f2193dafee38239051d7b">llvm::DbgVariableRecord::hasArgList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a352ccfab7392a21f5253bca1791022d5">lowerDbgDeclare</a>, <a href="#a7eb536540d37a55860c52b81778b013e">lowerDbgValue</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>, <a href="#acb5337d3078000bf9b580b28031136af">recomputeInsertPt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">llvm::DbgVariableRecord::Value</a>.</p>

</div>
</div>

### leaveLocalValueArea() {#a3efed0ded914901e7d8741227dfcd249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FastISel::leaveLocalValueArea (<a href="#abc58554c43194546f38ed54efd897ec8">SavePoint</a> Old)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset InsertPt to the given old insert position.</p>

<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a> and <a href="#ade66ed1ba84375d666af381e0153d038">LastLocalValue</a>.</p>


<p>Referenced by <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>.</p>

</div>
</div>

### lookUpRegForValue() {#aa01ecad5fa09c3afd2f9cdc2a50d707a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::lookUpRegForValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look up the value to see if its value is already cached in a register.</p>


<p>It may be defined by instructions across blocks or defined locally.</p>


<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a1b59baac25d2130c5fde409d31c0f51c">LocalValueMap</a>.</p>


<p>Referenced by <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="#a352ccfab7392a21f5253bca1791022d5">lowerDbgDeclare</a> and <a href="#a7eb536540d37a55860c52b81778b013e">lowerDbgValue</a>.</p>

</div>
</div>

### lowerArguments() {#ae69b4cef553644304e69e8d671bd5c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::lowerArguments ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do "fast" instruction selection for function arguments and append the machine instructions to the current block.</p>


<p>Returns true when successful.</p>


<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9b32a3c62f5c8ad8f9b9610cc3e5707c">fastLowerArguments</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a1b59baac25d2130c5fde409d31c0f51c">LocalValueMap</a>.</p>

</div>
</div>

### recomputeInsertPt() {#acb5337d3078000bf9b580b28031136af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FastISel::recomputeInsertPt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset InsertPt to prepare for inserting instructions into the current block.</p>

<p>Declaration at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a> and <a href="#a376bebd788584bb9147314011dd769c9">getLastLocalValue</a>.</p>


<p>Referenced by <a href="#aeb72b2e2b8be6ec3392c569dc53db16f">enterLocalValueArea</a>, <a href="#a52bb01c018d9c9a9bda3d127ab5c7189">handleDbgInfo</a>, <a href="#a6066bf2100d34651261866662b42114e">removeDeadCode</a> and <a href="#a82e8b29a5326fe0dc88bf14c244a1b0d">selectInstruction</a>.</p>

</div>
</div>

### removeDeadCode() {#a6066bf2100d34651261866662b42114e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FastISel::removeDeadCode (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove all dead instructions between the I and E.</p>

<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a24f3e11725f5ce0ddf65a31783872863">EmitStartPt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ade66ed1ba84375d666af381e0153d038">LastLocalValue</a> and <a href="#acb5337d3078000bf9b580b28031136af">recomputeInsertPt</a>.</p>


<p>Referenced by <a href="#a82e8b29a5326fe0dc88bf14c244a1b0d">selectInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>.</p>

</div>
</div>

### selectInstruction() {#a82e8b29a5326fe0dc88bf14c244a1b0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do "fast" instruction selection for the given LLVM IR instruction and append the generated machine instructions to the current block.</p>


<p>Returns true if selection was successful.</p>


<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1585 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#acc1e4ca49328979aa5ddd8e4285e23e3">fastSelectInstruction</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="#a376bebd788584bb9147314011dd769c9">getLastLocalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a06203f8be451bbf280e15b45a1b20224">LibInfo</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca8997c6b0930e2c05209e95e7172c6cf3">llvm::LLVMContext::OB_funclet</a>, <a href="#acb5337d3078000bf9b580b28031136af">recomputeInsertPt</a>, <a href="#a6066bf2100d34651261866662b42114e">removeDeadCode</a>, <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a> and <a href="#ab7759506c93231c973c2c96665bd6e73">SkipTargetIndependentISel</a>.</p>

</div>
</div>

### selectOperator() {#ab30094b924bc7333b5bf134d7985ca18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectOperator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * I, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do "fast" instruction selection for the given LLVM IR operator (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> or <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a>), and append generated machine instructions to the current block.</p>


<p>Return true if selection was successful.</p>


<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1794 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3ad406477784397709a339d5a2957b43">llvm::EVT::bitsGT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3bf257bfbd279ecfad670be03b00210e">llvm::EVT::bitsLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="#a813993b16270d29cb0d76fa76140e424">fastEmit_</a>, <a href="#a1b8715812b9f4dd2bd46163dd1b51128">fastEmitBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e">llvm::ISD::FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdd7bbb76dac7962dda6e116e33699da">llvm::ISD::FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#ad56f6a9b5cd05940017c4544df48bc30">llvm::BranchInst::isUnconditional</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="#ac399325c88de95b03c19e68e1229a8f7">selectBinaryOp</a>, <a href="#aedd7b25487ab7f0871e3d722c1766c18">selectBitCast</a>, <a href="#a9f7b01772fb64eab764bc071e84b860e">selectCall</a>, <a href="#a59ec796e4ddba85e210d5a226d56f16f">selectCast</a>, <a href="#a1434fc5d1782f15a392af0320f13f6c7">selectExtractValue</a>, <a href="#a9b79346e8152f683a6ad35f8049c74ea">selectFNeg</a>, <a href="#a5718bb42ac48e382b259cd668ad38e21">selectFreeze</a>, <a href="#a09eed569d7f0359be47433ca90532f81">selectGetElementPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a>, <a href="#ad1634563b73a5a9df8b459d913fa4943">TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac5fb8808f3dcb9f0a83f1fc2e7747485">llvm::ISD::TRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a935243867ee958b18b7d331014ecdca5">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastSelectInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyfastisel-cpp-/webassemblyfastisel/#ae25a877cd04006af164fa6d83e1e7972">anonymous{WebAssemblyFastISel.cpp}::WebAssemblyFastISel::fastSelectInstruction</a> and <a href="#a82e8b29a5326fe0dc88bf14c244a1b0d">selectInstruction</a>.</p>

</div>
</div>

### setLastLocalValue() {#a0bfa1f986356fdcdcab1c98dcf9a84e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastISel::setLastLocalValue (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * I)</td>
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

<p>Update the position of the last instruction emitted for materializing constants for use in the current block.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>References <a href="#a24f3e11725f5ce0ddf65a31783872863">EmitStartPt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ade66ed1ba84375d666af381e0153d038">LastLocalValue</a>.</p>

</div>
</div>

### startNewBlock() {#a6a4d1b2ae70640755d4942597b65376e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FastISel::startNewBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the current block to which generated machine instructions will be appended.</p>

<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a24f3e11725f5ce0ddf65a31783872863">EmitStartPt</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="#ade66ed1ba84375d666af381e0153d038">LastLocalValue</a> and <a href="#a1b59baac25d2130c5fde409d31c0f51c">LocalValueMap</a>.</p>

</div>
</div>

### tryToFoldLoad() {#a5a81ca548cc88df15a58aed766bdd890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::tryToFoldLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * FoldInst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We're checking to see if we can fold <span class="doxyComputerOutput">LI</span> into <span class="doxyComputerOutput">FoldInst</span>.</p>


<p>Note that we could have a sequence where multiple LLVM IR instructions are folded into the same machineinstr. For example we could have:</p>


<p>A: x = load i32 *P B: y = icmp A, 42 C: br y, ...</p>


<p>In this scenario, <span class="doxyComputerOutput">LI</span> is "A", and <span class="doxyComputerOutput">FoldInst</span> is "C". We know about "B" (and any other folded instructions) because it is between A and C.</p>


<p>If we succeed folding, return true.</p>


<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-iterator/#a58a1c3f21a96544fc062f9ec00ef808b">llvm::MachineRegisterInfo::defusechain_iterator&lt; ReturnUses, ReturnDefs, SkipDebug, ByOperand, ByInstr, ByBundle &gt;::getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2eccc19f9061eeb7ad1e30e21f76034d">llvm::LoadInst::isVolatile</a>, <a href="#a018554adfdbafed22851faa4e25cd4af">MRI</a>, <a href="#a73773042077892da5c7a6b3f8435a175">tryToFoldLoadIntoMI</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6609528bd67d5506a9bf9a2cce2d6f58">llvm::Instruction::user_back</a>.</p>

</div>
</div>

### tryToFoldLoadIntoMI() {#a73773042077892da5c7a6b3f8435a175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::FastISel::tryToFoldLoadIntoMI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *)</td>
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

<p>The specified machine instr operand is a vreg, and that vreg is being provided by the specified load instruction.</p>


<p>If possible, try to fold the load as an operand to the instruction, returning true if possible.</p>


<p>This method should be implemented by targets.</p>


<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a5a81ca548cc88df15a58aed766bdd890">tryToFoldLoad</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### canFoldAddIntoGEP() {#a7d784ad1fd74a55994d44d0d3ac39b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::canFoldAddIntoGEP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * GEP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Add)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">Add</span> is an add that can be safely folded into <span class="doxyComputerOutput">GEP</span>.</p>


<p><span class="doxyComputerOutput">Add</span> can be folded into <span class="doxyComputerOutput">GEP</span> if:</p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">Add</span> is an add,</li>
<li><span class="doxyComputerOutput">Add's</span> size matches <span class="doxyComputerOutput">GEP's</span>,</li>
<li><span class="doxyComputerOutput">Add</span> is in the same basic block as <span class="doxyComputerOutput">GEP</span>, and</li>
<li><span class="doxyComputerOutput">Add</span> has a constant operand.</li>
</ul>

<p>Declaration at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2376 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### constrainOperandRegClass() {#abb968323ca61fa5d8e99b4523a08f2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::constrainOperandRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; II, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Op, unsigned OpNum)</td>
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

<p>Try to constrain <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> so that it is usable by argument OpNum of the provided <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a>.</p>


<p>If this fails, create a new virtual register in the correct class and COPY the value there.</p>


<p>Declaration at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2020 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>, <a href="#a018554adfdbafed22851faa4e25cd4af">MRI</a>, <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a> and <a href="#afe0bba218f685c37e6c1ca4b49d2d1f1">TRI</a>.</p>


<p>Referenced by <a href="#a43873dfd861406dc9da68ddcd2bfe1bc">fastEmitInst_r</a>, <a href="#aef1cb331526de21d6b1729a42a72d74f">fastEmitInst_ri</a>, <a href="#a91124ff314dcb25457d0a4bd31fa5c52">fastEmitInst_rii</a>, <a href="#a8d85017ca59fd0d13bde23551dfc5f90">fastEmitInst_rr</a>, <a href="#ae348a9f69bb94b326d0e722c74dfaf7b">fastEmitInst_rri</a> and <a href="#afe20d43bd5edcb69d1a401105ad3d38e">fastEmitInst_rrr</a>.</p>

</div>
</div>

### createMachineMemOperandFor() {#a6bec3fdf48dcde80a42b76f09d151a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineMemOperand * FastISel::createMachineMemOperandFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Create a machine mem operand from the given instruction.</p>

<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2393 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7b999a936bc7a4d45dfadbe356e77b3f">llvm::MachineMemOperand::MODereferenceable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac63dd9c4fe69bfeaac7a363fda846ac6">llvm::MachineMemOperand::MOInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda8d09c51969b0954512ed65ee26551081">llvm::MachineMemOperand::MONonTemporal</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>.</p>

</div>
</div>

### createResultReg() {#a981679659ff46a72dc913da01553667a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::createResultReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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



<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2016 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>Reference <a href="#a018554adfdbafed22851faa4e25cd4af">MRI</a>.</p>


<p>Referenced by <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a2b5f2bc37d0cd978d8f38c2b14aabaf7">fastEmitInst_</a>, <a href="#a03ab338e9e5f4ea24b2049ab525525bf">fastEmitInst_extractsubreg</a>, <a href="#aba7be31f2606d1565335458953610fcd">fastEmitInst_f</a>, <a href="#a738eff0daa8e9f33ff056da16adefb4d">fastEmitInst_i</a>, <a href="#a43873dfd861406dc9da68ddcd2bfe1bc">fastEmitInst_r</a>, <a href="#aef1cb331526de21d6b1729a42a72d74f">fastEmitInst_ri</a>, <a href="#a91124ff314dcb25457d0a4bd31fa5c52">fastEmitInst_rii</a>, <a href="#a8d85017ca59fd0d13bde23551dfc5f90">fastEmitInst_rr</a>, <a href="#ae348a9f69bb94b326d0e722c74dfaf7b">fastEmitInst_rri</a>, <a href="#afe20d43bd5edcb69d1a401105ad3d38e">fastEmitInst_rrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a39e2fe24f8016760f80ca14ba3476ebc">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#aaf94fccaa261871e44881773bcdc5ee7">anonymous{MipsFastISel.cpp}::MipsFastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a246d108e7d516b651024d7ab2a75e9be">anonymous{X86FastISel.cpp}::X86FastISel::fastSelectInstruction</a>, <a href="#a5718bb42ac48e382b259cd668ad38e21">selectFreeze</a> and <a href="#ac8bc20b89a02f7d1d402a9fb561d1717">selectPatchpoint</a>.</p>

</div>
</div>

### fastEmit\_() {#a813993b16270d29cb0d76fa76140e424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FastISel::fastEmit_ (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> RetVT, unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called by target-independent code to request that an instruction with the given type and opcode be emitted.</p>

<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1952 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>Referenced by <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>.</p>

</div>
</div>

### fastEmit\_f() {#a987b8990145af270282c52928f7ed220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FastISel::fastEmit_f (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> RetVT, unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * FPImm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called by target-independent code to request that an instruction with the given type, opcode, and floating-point immediate operand be emitted.</p>

<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1967 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>

</div>
</div>

### fastEmit\_i() {#afb35ef59bf683a0ff72f447a5ae92f27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FastISel::fastEmit_i (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> RetVT, unsigned Opcode, uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called by target-independent code to request that an instruction with the given type, opcode, and immediate operand be emitted.</p>

<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1963 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>Referenced by <a href="#ad7a01123cf8a0e7acd2b089c65957b26">fastEmit_ri_</a>.</p>

</div>
</div>

### fastEmit\_r() {#af2202cab3109536077a683bcd326fe55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FastISel::fastEmit_r (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> RetVT, unsigned Opcode, unsigned Op0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called by target-independent code to request that an instruction with the given type, opcode, and register operand be emitted.</p>

<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1954 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="#a5997c4992589047ebc712b52b6e101cb">getRegForGEPIndex</a>, <a href="#aedd7b25487ab7f0871e3d722c1766c18">selectBitCast</a>, <a href="#a59ec796e4ddba85e210d5a226d56f16f">selectCast</a> and <a href="#a9b79346e8152f683a6ad35f8049c74ea">selectFNeg</a>.</p>

</div>
</div>

### fastEmit\_ri() {#a3c42eef34e00640e9c0edc553e50d5dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FastISel::fastEmit_ri (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> RetVT, unsigned Opcode, unsigned Op0, uint64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called by target-independent code to request that an instruction with the given type, opcode, and register and immediate operands be emitted.</p>

<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1972 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>Referenced by <a href="#ad7a01123cf8a0e7acd2b089c65957b26">fastEmit_ri_</a>, <a href="#ad9378963a44c6d0e07ea95c821442cc5">fastEmitZExtFromI1</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>.</p>

</div>
</div>

### fastEmit\_ri\_() {#ad7a01123cf8a0e7acd2b089c65957b26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmit_ri_ (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, unsigned Opcode, unsigned Op0, uint64_t Imm, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ImmType)</td>
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

<p>This method is a wrapper of fastEmit_ri.</p>


<p>It first tries to emit an instruction with an immediate operand using fastEmit_ri. If that fails, it materializes the immediate into a register and try fastEmit_rr instead.</p>


<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1981 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aac2f0a84dd2aa5ee4c3f1385e9565f5e">llvm::ISD::Constant</a>, <a href="#afb35ef59bf683a0ff72f447a5ae92f27">fastEmit_i</a>, <a href="#a3c42eef34e00640e9c0edc553e50d5dd">fastEmit_ri</a>, <a href="#acfe921ad48553b0de6fe092d66e54671">fastEmit_rr</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>.</p>


<p>Referenced by <a href="#ac399325c88de95b03c19e68e1229a8f7">selectBinaryOp</a>, <a href="#a9b79346e8152f683a6ad35f8049c74ea">selectFNeg</a> and <a href="#a09eed569d7f0359be47433ca90532f81">selectGetElementPtr</a>.</p>

</div>
</div>

### fastEmit\_rr() {#acfe921ad48553b0de6fe092d66e54671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FastISel::fastEmit_rr (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> RetVT, unsigned Opcode, unsigned Op0, unsigned Op1)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called by target-independent code to request that an instruction with the given type, opcode, and register operands be emitted.</p>

<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1958 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>Referenced by <a href="#ad7a01123cf8a0e7acd2b089c65957b26">fastEmit_ri_</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="#ac399325c88de95b03c19e68e1229a8f7">selectBinaryOp</a> and <a href="#a09eed569d7f0359be47433ca90532f81">selectGetElementPtr</a>.</p>

</div>
</div>

### fastEmitBranch() {#a1b8715812b9f4dd2bd46163dd1b51128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FastISel::fastEmitBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MSucc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DbgLoc)</td>
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

<p>Emit an unconditional branch to the given block, unless it is the immediate (fall-through) successor, and update the CFG.</p>

<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1669 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#afbc181ceecaec94bd0ea2eab8f23cbd8">llvm::BasicBlock::back</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4848d1a141ddc7cf0068460fba53ba37">llvm::BasicBlock::front</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#afc70e919c88c86159cc94cea29b6c210">llvm::BasicBlock::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a1901c01c9f1724db542f99882fb6ca48">llvm::Module::IsNewDbgInfoFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a96768456ed4add9aa5b9f56cdd3f6d7f">llvm::BasicBlock::sizeWithoutDebug</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>


<p>Referenced by <a href="#aebb4626a91d27266548cba7efedc6fe6">finishCondBranch</a> and <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>.</p>

</div>
</div>

### fastEmitInst\_() {#a2b5f2bc37d0cd978d8f38c2b14aabaf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmitInst_ (unsigned MachineInstOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with no operands and a result register in the given register class.</p>

<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2037 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>

</div>
</div>

### fastEmitInst\_extractsubreg() {#a03ab338e9e5f4ea24b2049ab525525bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmitInst_extractsubreg (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> RetVT, unsigned Op0, uint32_t Idx)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> for an extract_subreg from a specified index of a superregister to a specified type.</p>

<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ac6bf744f357352cde7578931007c0b6f">llvm::Register::isVirtualRegister</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>, <a href="#a018554adfdbafed22851faa4e25cd4af">MRI</a>, <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a> and <a href="#afe0bba218f685c37e6c1ca4b49d2d1f1">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>.</p>

</div>
</div>

### fastEmitInst\_f() {#aba7be31f2606d1565335458953610fcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmitInst_f (unsigned MachineInstOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * FPImm)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with a floating point immediate, and a result register in the given register class.</p>

<p>Declaration at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a95c7b5ed23471212aeaba1eee6501261">llvm::MachineInstrBuilder::addFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>

</div>
</div>

### fastEmitInst\_i() {#a738eff0daa8e9f33ff056da16adefb4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmitInst_i (unsigned MachineInstOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, uint64_t Imm)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with a single immediate operand, and a result register in the given register class.</p>

<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>

</div>
</div>

### fastEmitInst\_r() {#a43873dfd861406dc9da68ddcd2bfe1bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmitInst_r (unsigned MachineInstOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned Op0)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with one register operand and a result register in the given register class.</p>

<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2046 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a07fd59cf6f37dd8cc9b6f5f2d0ff3e59">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeFloatZero</a>.</p>

</div>
</div>

### fastEmitInst\_ri() {#aef1cb331526de21d6b1729a42a72d74f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmitInst_ri (unsigned MachineInstOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned Op0, uint64_t Imm)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with a register operand, an immediate, and a result register in the given register class.</p>

<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>.</p>

</div>
</div>

### fastEmitInst\_rii() {#a91124ff314dcb25457d0a4bd31fa5c52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmitInst_rii (unsigned MachineInstOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned Op0, uint64_t Imm1, uint64_t Imm2)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with one register operand and two immediate operands.</p>

<p>Declaration at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>

</div>
</div>

### fastEmitInst\_rr() {#a8d85017ca59fd0d13bde23551dfc5f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmitInst_rr (unsigned MachineInstOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned Op0, unsigned Op1)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with two register operands and a result register in the given register class.</p>

<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2067 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>.</p>

</div>
</div>

### fastEmitInst\_rri() {#ae348a9f69bb94b326d0e722c74dfaf7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmitInst_rri (unsigned MachineInstOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned Op0, unsigned Op1, uint64_t Imm)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with two register operands, an immediate, and a result register in the given register class.</p>

<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>

</div>
</div>

### fastEmitInst\_rrr() {#afe20d43bd5edcb69d1a401105ad3d38e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmitInst_rrr (unsigned MachineInstOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned Op0, unsigned Op1, unsigned Op2)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with three register operands and a result register in the given register class.</p>

<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2091 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>

</div>
</div>

### fastEmitZExtFromI1() {#ad9378963a44c6d0e07ea95c821442cc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::fastEmitZExtFromI1 (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, unsigned Op0)</td>
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

<p>Emit MachineInstrs to compute the value of <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> with all but the least significant bit set to zero.</p>

<p>Declaration at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2243 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a> and <a href="#a3c42eef34e00640e9c0edc553e50d5dd">fastEmit_ri</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>.</p>

</div>
</div>

### fastLowerArguments() {#a9b32a3c62f5c8ad8f9b9610cc3e5707c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::fastLowerArguments ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called by target-independent code to do target- specific argument lowering.</p>


<p>It returns true if it was successful.</p>


<p>Declaration at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1944 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>Referenced by <a href="#ae69b4cef553644304e69e8d671bd5c1c">lowerArguments</a>.</p>

</div>
</div>

### fastLowerCall() {#a8a6a1f860beb28f193b8313fee58df9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::fastLowerCall (<a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo">CallLoweringInfo</a> &amp; CLI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called by target-independent code to do target- specific call lowering.</p>


<p>It returns true if it was successful.</p>


<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1946 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>Referenced by <a href="#a284bf291d22c5fe81d9cae4b4f1a4fea">lowerCallTo</a>.</p>

</div>
</div>

### fastLowerIntrinsicCall() {#a3231fc07f21bf85a28500d24e157282c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::fastLowerIntrinsicCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called by target-independent code to do target- specific intrinsic lowering.</p>


<p>It returns true if it was successful.</p>


<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1948 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>Referenced by <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>.</p>

</div>
</div>

### fastMaterializeAlloca() {#af4de0df44bcf2e480a2005c6304d9fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::FastISel::fastMaterializeAlloca (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an alloca address in a register using target-specific logic.</p>

<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### fastMaterializeConstant() {#a85ab744fe6e49b1d9eaa927ec7e292b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::FastISel::fastMaterializeConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a constant in a register using target-specific logic, such as constant pool loads.</p>

<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### fastMaterializeFloatZero() {#a20ec9b646b1726ea156e23cb0f965840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::FastISel::fastMaterializeFloatZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * CF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the floating-point constant +0.0 in a register using target- specific logic.</p>

<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>

</div>
</div>

### fastSelectInstruction() {#acc1e4ca49328979aa5ddd8e4285e23e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::FastISel::fastSelectInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>This method is called by target-independent code when the normal <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> process fails to select an instruction.</p>


<p>This gives targets a chance to emit code for anything that doesn't fit into <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a>'s framework. It returns true if it was successful.</p>


<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a82e8b29a5326fe0dc88bf14c244a1b0d">selectInstruction</a>.</p>

</div>
</div>

### finishCondBranch() {#aebb4626a91d27266548cba7efedc6fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FastISel::finishCondBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BranchBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TrueMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FalseMBB)</td>
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

<p>Emit an unconditional branch to <span class="doxyComputerOutput">FalseMBB</span>, obtains the branch weight and adds TrueMBB and FalseMBB to the successor list.</p>

<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1693 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="#a1b8715812b9f4dd2bd46163dd1b51128">fastEmitBranch</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a> and <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>.</p>

</div>
</div>

### lowerCall() {#a3c0cdb3908fc8b0f795f411e32bb806e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::lowerCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * I)</td>
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



<p>Declaration at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4fb513d744ca72275932b2c7003f16f6">llvm::CallBase::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a259334992127b809a034f025fc2bd13f">llvm::diagnoseDontCall</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a8d13199cbf4d080d3b5dcf330dad5d2c">llvm::CallBase::getCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2fadbd4626ccfbf3d2cabd27003d597">llvm::isInTailCallPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#ad3c897ba734b78e973db4622dff7bdcb">llvm::CallInst::isMustTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a52104f0d6ca7bd74add63deb0cb7e2a7">llvm::CallInst::isTailCall</a>, <a href="#a429785d5b6015aff39a7a998d9e70fa3">lowerCallTo</a>, <a href="#a79d5f0dde17b382c909b9806e9436592">MF</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#afcc487710e7ad6fdc2a66bcc65bd233d">llvm::FastISel::CallLoweringInfo::setCallee</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a82dac221b85b98eb8f94ff32686bd160">llvm::FastISel::CallLoweringInfo::setTailCall</a> and <a href="#ad1634563b73a5a9df8b459d913fa4943">TM</a>.</p>


<p>Referenced by <a href="#a9f7b01772fb64eab764bc071e84b860e">selectCall</a>.</p>

</div>
</div>

### lowerCallTo() {#a429785d5b6015aff39a7a998d9e70fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::lowerCallTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, unsigned NumArgs)</td>
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



<p>Declaration at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a3ff92cec76009e859cb0c419d6e8ba5f">llvm::CallBase::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a429785d5b6015aff39a7a998d9e70fa3">lowerCallTo</a>, <a href="#a79d5f0dde17b382c909b9806e9436592">MF</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#afcc487710e7ad6fdc2a66bcc65bd233d">llvm::FastISel::CallLoweringInfo::setCallee</a> and <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="#a3c0cdb3908fc8b0f795f411e32bb806e">lowerCall</a>, <a href="#ac50c544ca2ade87e7ad0dd6afccdf84c">lowerCallTo</a> and <a href="#a429785d5b6015aff39a7a998d9e70fa3">lowerCallTo</a>.</p>

</div>
</div>

### lowerCallTo() {#ac50c544ca2ade87e7ad0dd6afccdf84c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::lowerCallTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * SymName, unsigned NumArgs)</td>
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



<p>Declaration at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="#a429785d5b6015aff39a7a998d9e70fa3">lowerCallTo</a> and <a href="#a79d5f0dde17b382c909b9806e9436592">MF</a>.</p>

</div>
</div>

### lowerCallTo() {#a284bf291d22c5fe81d9cae4b4f1a4fea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::lowerCallTo (<a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo">CallLoweringInfo</a> &amp; CLI)</td>
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



<p>Declaration at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg/#aada3fbab341597b0061de2f48db3a26d">llvm::ISD::InputArg::ArgVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a83235b3d69702bbb34da1aaf32c5d683">llvm::FastISel::CallLoweringInfo::Call</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a308acf766fe89d05cbfc2f59581439b3">llvm::FastISel::CallLoweringInfo::CallConv</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a72f539529045e72c96f0712e812e4168">llvm::FastISel::CallLoweringInfo::CB</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#aab6aed4bf8d8c73992fcfae25770a273">llvm::FastISel::CallLoweringInfo::clearIns</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a1f045e806aefd8c423cb530fccebd43a">llvm::FastISel::CallLoweringInfo::clearOuts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="#a8a6a1f860beb28f193b8313fee58df9b">fastLowerCall</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg/#ade84a7c18e5c4189eae57ebd21f77321">llvm::ISD::InputArg::Flags</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a9afd2f3cddf640b761675d0911849ed6">llvm::FastISel::CallLoweringInfo::getArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp/#ae7c1fa2a94f420cac743955c3db73b28">getReturnAttrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a175f10e8ec1c2ec4fa24431ac5429a36">llvm::GetReturnInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#ad174f5cc68bbbe72a8b902c289320b45">llvm::FastISel::CallLoweringInfo::InRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#afceb1c03b606771c10a049ef11f53d54">llvm::FastISel::CallLoweringInfo::Ins</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#aa83a71e99909a3ee88f1d987985768d3">llvm::FastISel::CallLoweringInfo::IsInReg</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a177568b8c8fe3fb99b101a01631574a4">llvm::FastISel::CallLoweringInfo::IsReturnValueUsed</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a3e2a0b115bdda6287fac43fb71ff7352">llvm::FastISel::CallLoweringInfo::IsVarArg</a>, <a href="#a79d5f0dde17b382c909b9806e9436592">MF</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a40c6e80d35c80d65edc16ffa7ab0d39d">llvm::FastISel::CallLoweringInfo::NumResultRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a333d2c82c193e4c258195e5f7ba3aed6">llvm::FastISel::CallLoweringInfo::OutFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a3d86d7e9ef4938e1192b4bb4e2a6507d">llvm::FastISel::CallLoweringInfo::OutVals</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a236216be5ea40fdc49efb658bf58e67b">llvm::FastISel::CallLoweringInfo::ResultReg</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a1e3d7941faeb1a9d4d95829e6639af2b">llvm::FastISel::CallLoweringInfo::RetSExt</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a35d74a4f3f503bb98e00ece4a618b2cf">llvm::FastISel::CallLoweringInfo::RetTy</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a01c98b4c7e3e37427d5ec2726a0c3f4c">llvm::FastISel::CallLoweringInfo::RetZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9a10f5acfd3fb2690d6bc2c78c26be13">llvm::MachineInstr::setHeapAllocMarker</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#ac8683d314a90a316cb67a685d42a8c28">llvm::ISD::ArgFlagsTy::setInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2afcfcff9187a2201549d75d4e16149">llvm::MachineInstr::setPhysRegsDeadExcept</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#a1134ea0aa4c8b2d3e344d48dca3c4d44">llvm::ISD::ArgFlagsTy::setSExt</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#a9d5e89b5f086590d776028ee2f095453">llvm::ISD::ArgFlagsTy::setZExt</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a>, <a href="#afe0bba218f685c37e6c1ca4b49d2d1f1">TRI</a>, <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg/#a27823260c8966d6aa13c133689efe757">llvm::ISD::InputArg::Used</a> and <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg/#a9b241995758f9cea8cecf597918d1488">llvm::ISD::InputArg::VT</a>.</p>

</div>
</div>

### lowerDbgDeclare() {#a352ccfab7392a21f5253bca1791022d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::lowerDbgDeclare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-independent lowering of debug information.</p>


<p>Returns false if the debug information couldn't be lowered and was instead discarded.</p>


<p>Declaration at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1322 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#ac8c4cb4dde7067286d3e3ce80bf77224">llvm::DILocalVariable::isValidLocationForIntrinsic</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aa01ecad5fa09c3afd2f9cdc2a50d707a">lookUpRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#af3a48df3735933cf1621760019e5fd8c">llvm::DIExpression::prependOpcodes</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>


<p>Referenced by <a href="#a52bb01c018d9c9a9bda3d127ab5c7189">handleDbgInfo</a> and <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>.</p>

</div>
</div>

### lowerDbgValue() {#a7eb536540d37a55860c52b81778b013e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::lowerDbgValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-independent lowering of debug information.</p>


<p>Returns false if the debug information couldn't be lowered and was instead discarded.</p>


<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1236 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3348f4e81264ccfe03832f141fdf44a3">llvm::MachineInstrBuilder::addCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a95c7b5ed23471212aeaba1eee6501261">llvm::MachineInstrBuilder::addFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7f54f5772ba80cc1f7c4a92203f14e57">llvm::MachineInstrBuilder::addMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a8e4ee2a70091fe36640fda28c69580c6">llvm::DIExpression::constantFold</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afda3f1971b3e44709267be818ffd3035">llvm::MachineOperand::CreateFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a012168d44e49d5120cf8919cd096fd3b">llvm::DIExpression::isEntryValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aa01ecad5fa09c3afd2f9cdc2a50d707a">lookUpRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#af3a48df3735933cf1621760019e5fd8c">llvm::DIExpression::prependOpcodes</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>


<p>Referenced by <a href="#a52bb01c018d9c9a9bda3d127ab5c7189">handleDbgInfo</a> and <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>.</p>

</div>
</div>

### optimizeCmpPredicate() {#aa26a7d0b19ce017fda518be95485fb8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate FastISel::optimizeCmpPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * CI)</td>
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



<p>Declaration at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d">llvm::CmpInst::FCMP_FALSE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">llvm::CmpInst::FCMP_OEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">llvm::CmpInst::FCMP_OLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">llvm::CmpInst::FCMP_ONE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5">llvm::CmpInst::FCMP_TRUE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">llvm::CmpInst::FCMP_UEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">llvm::CmpInst::FCMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">llvm::CmpInst::FCMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">llvm::CmpInst::FCMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">llvm::CmpInst::FCMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">llvm::CmpInst::FCMP_UNE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### selectBinaryOp() {#ac399325c88de95b03c19e68e1229a8f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectBinaryOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * I, unsigned ISDOpcode)</td>
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

<p>Select and emit code for a binary operator instruction, which has an opcode which directly corresponds to the given <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a> opcode.</p>

<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad7a01123cf8a0e7acd2b089c65957b26">fastEmit_ri_</a>, <a href="#acfe921ad48553b0de6fe092d66e54671">fastEmit_rr</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a6b220b2107d211a5db501de58981e214">llvm::ISD::isBitwiseLogicOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ab0da56db6da27340e5a7151a4676106a">isCommutative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a>, <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>.</p>


<p>Referenced by <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>.</p>

</div>
</div>

### selectBitCast() {#aedd7b25487ab7f0871e3d722c1766c18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectBitCast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * I)</td>
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



<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1516 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="#af2202cab3109536077a683bcd326fe55">fastEmit_r</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a> and <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a935243867ee958b18b7d331014ecdca5">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastSelectInstruction</a> and <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>.</p>

</div>
</div>

### selectCall() {#a9f7b01772fb64eab764bc071e84b860e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * I)</td>
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



<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7f54f5772ba80cc1f7c4a92203f14e57">llvm::MachineInstrBuilder::addMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370abff974c258dde829c1c6b6f32667be3a">llvm::InlineAsm::Extra_AsmDialect</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370a68a61079919e61d3af1002124c2f1ff9">llvm::InlineAsm::Extra_HasSideEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ada6152484586a08fa711d4b0d44c87e5">llvm::InlineAsm::Extra_IsAlignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370a9921f5d5868939f49675e7fe34d1be70">llvm::InlineAsm::Extra_IsConvergent</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a3c0cdb3908fc8b0f795f411e32bb806e">lowerCall</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>, <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a> and <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>.</p>


<p>Referenced by <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>.</p>

</div>
</div>

### selectCast() {#a59ec796e4ddba85e210d5a226d56f16f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectCast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * I, unsigned Opcode)</td>
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



<p>Declaration at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1485 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="#af2202cab3109536077a683bcd326fe55">fastEmit_r</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a> and <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a935243867ee958b18b7d331014ecdca5">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastSelectInstruction</a> and <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>.</p>

</div>
</div>

### selectExtractValue() {#a1434fc5d1782f15a392af0320f13f6c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectExtractValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * U)</td>
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



<p>Declaration at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1754 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#adf1f21f92016bd1845de84892761714a">llvm::ComputeLinearIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst/#a089f295919afbb059f9f745206094002">llvm::ExtractValueInst::getIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a> and <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a>.</p>


<p>Referenced by <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>.</p>

</div>
</div>

### selectFNeg() {#a9b79346e8152f683a6ad35f8049c74ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectFNeg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * In)</td>
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

<p>Emit an FNeg operation.</p>

<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1712 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="#af2202cab3109536077a683bcd326fe55">fastEmit_r</a>, <a href="#ad7a01123cf8a0e7acd2b089c65957b26">fastEmit_ri_</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a752372e170e4e7c595bf8810bb52adf2">llvm::EVT::getIntegerVT</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a>, <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>


<p>Referenced by <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>.</p>

</div>
</div>

### selectFreeze() {#a5718bb42ac48e382b259cd668ad38e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectFreeze (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * I)</td>
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



<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1545 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>, <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a> and <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a>.</p>


<p>Referenced by <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>.</p>

</div>
</div>

### selectGetElementPtr() {#a09eed569d7f0359be47433ca90532f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectGetElementPtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * I)</td>
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



<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad7a01123cf8a0e7acd2b089c65957b26">fastEmit_ri_</a>, <a href="#acfe921ad48553b0de6fe092d66e54671">fastEmit_rr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac828b9b52935f87659a4adf237f820a3">llvm::gep_type_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a43c6ebb4fd35ebd815d66a2df4eed0b9">llvm::gep_type_end</a>, <a href="#a5997c4992589047ebc712b52b6e101cb">getRegForGEPIndex</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a> and <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a>.</p>


<p>Referenced by <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>.</p>

</div>
</div>

### selectIntrinsicCall() {#a58217c3769fe3ee4ac0d221b836849f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectIntrinsicCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II)</td>
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



<p>Declaration at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7f54f5772ba80cc1f7c4a92203f14e57">llvm::MachineInstrBuilder::addMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a3231fc07f21bf85a28500d24e157282c">fastLowerIntrinsicCall</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgdeclareinst/#a3dd0197b425429468709af927dd71f08">llvm::DbgDeclareInst::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#ad1707c1c1ab1f3278424f265893c87fb">llvm::DbgVariableIntrinsic::getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelinst/#a8dc67566a99f01c9a9907c61108e0c7c">llvm::DbgLabelInst::getLabel</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst/#a82f5c63aa1e00276f988174976c57903">llvm::DbgValueInst::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a854857be09a21f27fb21ba872fe6f639">llvm::DbgVariableIntrinsic::getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#acfa0ffc95fedffcb2ac3cca51872af7a">llvm::DbgVariableIntrinsic::hasArgList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#ac8c4cb4dde7067286d3e3ce80bf77224">llvm::DILocalVariable::isValidLocationForIntrinsic</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a352ccfab7392a21f5253bca1791022d5">lowerDbgDeclare</a>, <a href="#a7eb536540d37a55860c52b81778b013e">lowerDbgValue</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>, <a href="#ac8bc20b89a02f7d1d402a9fb561d1717">selectPatchpoint</a>, <a href="#a0f9992c5e3a519e4128db320ba2d2e18">selectStackmap</a>, <a href="#a284276bdba816c71f6c16ee08e842b41">selectXRayCustomEvent</a>, <a href="#a8c80b7d55789b6712c22642d4f94b90d">selectXRayTypedEvent</a>, <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a> and <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a>.</p>


<p>Referenced by <a href="#a9f7b01772fb64eab764bc071e84b860e">selectCall</a>.</p>

</div>
</div>

### selectPatchpoint() {#ac8bc20b89a02f7d1d402a9fb561d1717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectPatchpoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * I)</td>
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



<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4f42667edde6e9cb80cfae6361e5e76a">llvm::CallingConv::AnyReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a83235b3d69702bbb34da1aaf32c5d683">llvm::FastISel::CallLoweringInfo::Call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a6892641fbb4193030fe2ad0108407e06a324a51adc0452a062355eff454118979">llvm::PatchPointOpers::CCPos</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ace112d8a86396bd55e99738cd41005b6">llvm::MachineOperand::CreateGA</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c01d756ca363aef75429d61d21c0c14">llvm::MachineOperand::CreateRegMask</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#a067a743bcdf919af7f64f48631be87fd">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a6892641fbb4193030fe2ad0108407e06a08353423e1d98722d846a7c35ac15dc5">llvm::PatchPointOpers::IDPos</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#ad174f5cc68bbbe72a8b902c289320b45">llvm::FastISel::CallLoweringInfo::InRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a6892641fbb4193030fe2ad0108407e06ae275100bf95af7c46359bfe61ba14152">llvm::PatchPointOpers::NArgPos</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a6892641fbb4193030fe2ad0108407e06a67a19d60d058a368934cc4e9a9df8121">llvm::PatchPointOpers::NBytesPos</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a40c6e80d35c80d65edc16ffa7ab0d39d">llvm::FastISel::CallLoweringInfo::NumResultRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a5370ad419a3bd87b4499e92b1e160736">llvm::FastISel::CallLoweringInfo::OutRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a236216be5ea40fdc49efb658bf58e67b">llvm::FastISel::CallLoweringInfo::ResultReg</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#af043061c95e2492fc9827f4a448bd098">llvm::FastISel::CallLoweringInfo::setIsPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2afcfcff9187a2201549d75d4e16149">llvm::MachineInstr::setPhysRegsDeadExcept</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a6892641fbb4193030fe2ad0108407e06a7c453e33050b23cf322d4c17b8912088">llvm::PatchPointOpers::TargetPos</a>, <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>, <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a>, <a href="#afe0bba218f685c37e6c1ca4b49d2d1f1">TRI</a> and <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a>.</p>


<p>Referenced by <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>.</p>

</div>
</div>

### selectStackmap() {#a0f9992c5e3a519e4128db320ba2d2e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectStackmap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * I)</td>
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



<p>Declaration at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a6892641fbb4193030fe2ad0108407e06a08353423e1d98722d846a7c35ac15dc5">llvm::PatchPointOpers::IDPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a6892641fbb4193030fe2ad0108407e06a67a19d60d058a368934cc4e9a9df8121">llvm::PatchPointOpers::NBytesPos</a>, <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a> and <a href="#accec713e7a93d7b67101624dadf04c98">TLI</a>.</p>


<p>Referenced by <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>.</p>

</div>
</div>

### selectXRayCustomEvent() {#a284276bdba816c71f6c16ee08e842b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectXRayCustomEvent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * II)</td>
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



<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ad953e410aea43848740978d9a6529a82">llvm::Triple::isAArch64</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>, <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>, <a href="#ad1634563b73a5a9df8b459d913fa4943">TM</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>.</p>

</div>
</div>

### selectXRayTypedEvent() {#a8c80b7d55789b6712c22642d4f94b90d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::selectXRayTypedEvent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * II)</td>
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



<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 920 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ad953e410aea43848740978d9a6529a82">llvm::Triple::isAArch64</a>, <a href="#ada788110c53e1082a0d10bb8cb379cce">MIMD</a>, <a href="#a9c3ffb1ecca8596b6653cc1ffdce8296">TII</a>, <a href="#ad1634563b73a5a9df8b459d913fa4943">TM</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>.</p>

</div>
</div>

### shouldOptForSize() {#acf5f7ebfb9fc299fc26be405cbc4e82f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastISel::shouldOptForSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Reference <a href="#a79d5f0dde17b382c909b9806e9436592">MF</a>.</p>

</div>
</div>

### updateValueMap() {#ac32081d2d2bf0593aebb564fd7e11d8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FastISel::updateValueMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * I, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned NumRegs=1)</td>
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

<p>Update the value map to include the new mapping for this instruction, or insert an extra copy to get the result in a previous determined register.</p>


<p>NOTE: This is only necessary because we might select a block that uses a value before we select the block that defines the value. It might be possible to fix this by selecting blocks in reverse postorder.</p>


<p>Declaration at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="#aaa436dd9de743a96bbb98e9ca6065973">FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a1b59baac25d2130c5fde409d31c0f51c">LocalValueMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a246d108e7d516b651024d7ab2a75e9be">anonymous{X86FastISel.cpp}::X86FastISel::fastSelectInstruction</a>, <a href="#a284bf291d22c5fe81d9cae4b4f1a4fea">lowerCallTo</a>, <a href="#ac399325c88de95b03c19e68e1229a8f7">selectBinaryOp</a>, <a href="#aedd7b25487ab7f0871e3d722c1766c18">selectBitCast</a>, <a href="#a59ec796e4ddba85e210d5a226d56f16f">selectCast</a>, <a href="#a1434fc5d1782f15a392af0320f13f6c7">selectExtractValue</a>, <a href="#a9b79346e8152f683a6ad35f8049c74ea">selectFNeg</a>, <a href="#a5718bb42ac48e382b259cd668ad38e21">selectFreeze</a>, <a href="#a09eed569d7f0359be47433ca90532f81">selectGetElementPtr</a>, <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>, <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a> and <a href="#ac8bc20b89a02f7d1d402a9fb561d1717">selectPatchpoint</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addStackMapLiveVars() {#ae5be01d3a07be840817fab33ea35d9e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::addStackMapLiveVars (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, unsigned StartIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a stackmap or patchpoint intrinsic call's live variable operands to a stackmap or patchpoint machine instruction.</p>

<p>Declaration at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>

</div>
</div>

### flushLocalValueMap() {#a15907e93c7ef14c7a6785de682ca38b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FastISel::flushLocalValueMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clears LocalValueMap and moves the area for the new local variables to the beginning of the block.</p>


<p>It helps to avoid spilling cached variables across heavy instructions like calls.</p>


<p>Declaration at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>

</div>
</div>

### handlePHINodesInSuccessorBlocks() {#a29191a0d9a9d50a378d445268e9bf93c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::handlePHINodesInSuccessorBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LLVMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle PHI nodes in successor blocks.</p>


<p>HandlePHINodesInSuccessorBlocks - Handle PHI nodes in successor blocks.</p>


<p>Emit code to ensure constants are copied into registers when needed. Remember the virtual registers that need to be added to the Machine PHI nodes as input. We cannot just directly add them, because expansion might result in multiple MBB's for one BB. As such, the start of the BB might correspond to a different MBB than the end.</p>


<p>Declaration at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 2253 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>

</div>
</div>

### lowerCallOperands() {#a9ebe817f1251f532120f40785ea326f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastISel::lowerCallOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, unsigned ArgIdx, unsigned NumArgs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Callee, bool ForceRetVoidTy, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo">CallLoweringInfo</a> &amp; CLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower an argument list according to the target calling convention.</p>


<p>This is a helper for lowering intrinsics that follow a target calling convention or require stack pointer adjustment. Only a subset of the intrinsic's operands need to participate in the calling convention.</p>


<p>Declaration at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>

</div>
</div>

### materializeConstant() {#a12ff6834a4ddd317a7b1ff922be35317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::materializeConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for materializeRegForValue to materialize a constant in a target-independent way.</p>

<p>Declaration at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>

</div>
</div>

### materializeRegForValue() {#ac682208151aca3dafa5a56cd60043a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FastISel::materializeRegForValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for getRegForVale.</p>


<p>Helper for getRegForValue.</p>


<p>This function is called when the value isn't already available in a register and must be materialized with new instructions.</p>


<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>

</div>
</div>

### removeDeadLocalValueCode() {#a1db188d7aed06e56642c5890fa5adc8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FastISel::removeDeadLocalValueCode (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * SavedLastLocalValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes dead local value instructions after SavedLastLocalvalue.</p>

<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 1568 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DL {#a067a743bcdf919af7f64f48631be87fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::FastISel::DL</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a7d784ad1fd74a55994d44d0d3ac39b5e">canFoldAddIntoGEP</a>, <a href="#a6bec3fdf48dcde80a42b76f09d151a03">createMachineMemOperandFor</a>, <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a39e2fe24f8016760f80ca14ba3476ebc">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#aaf94fccaa261871e44881773bcdc5ee7">anonymous{MipsFastISel.cpp}::MipsFastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#ac9784ca12ba090d5ab2924df8f535a86">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#a7fbc8a0e79b77a4eec73dceef97127a4">anonymous{MipsFastISel.cpp}::MipsFastISel::fastMaterializeConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a246d108e7d516b651024d7ab2a75e9be">anonymous{X86FastISel.cpp}::X86FastISel::fastSelectInstruction</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="#a284bf291d22c5fe81d9cae4b4f1a4fea">lowerCallTo</a>, <a href="#ac50c544ca2ade87e7ad0dd6afccdf84c">lowerCallTo</a>, <a href="#a352ccfab7392a21f5253bca1791022d5">lowerDbgDeclare</a>, <a href="#a7eb536540d37a55860c52b81778b013e">lowerDbgValue</a>, <a href="#aedd7b25487ab7f0871e3d722c1766c18">selectBitCast</a>, <a href="#a59ec796e4ddba85e210d5a226d56f16f">selectCast</a>, <a href="#a1434fc5d1782f15a392af0320f13f6c7">selectExtractValue</a>, <a href="#a9b79346e8152f683a6ad35f8049c74ea">selectFNeg</a>, <a href="#a5718bb42ac48e382b259cd668ad38e21">selectFreeze</a>, <a href="#a09eed569d7f0359be47433ca90532f81">selectGetElementPtr</a>, <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>, <a href="#ac8bc20b89a02f7d1d402a9fb561d1717">selectPatchpoint</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a68e52e8dcf5848c74cb89308b41cff89">llvm::FastISel::CallLoweringInfo::setCallee</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>.</p>

</div>
</div>

### EmitStartPt {#a24f3e11725f5ce0ddf65a31783872863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* llvm::FastISel::EmitStartPt = nullptr</td>
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

<p>The top most instruction in the current block that is allowed for emitting local variables.</p>


<p>LastLocalValue resets to EmitStartPt when it makes sense (for example, on function calls)</p>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a6066bf2100d34651261866662b42114e">removeDeadCode</a>, <a href="#a0bfa1f986356fdcdcab1c98dcf9a84e5">setLastLocalValue</a> and <a href="#a6a4d1b2ae70640755d4942597b65376e">startNewBlock</a>.</p>

</div>
</div>

### FuncInfo {#aaa436dd9de743a96bbb98e9ca6065973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionLoweringInfo&amp; llvm::FastISel::FuncInfo</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a1bc852ad7149319b7a54dccd62e77b8f">anonymous{AArch64FastISel.cpp}::AArch64FastISel::AArch64FastISel</a>, <a href="#a7d784ad1fd74a55994d44d0d3ac39b5e">canFoldAddIntoGEP</a>, <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a6bec3fdf48dcde80a42b76f09d151a03">createMachineMemOperandFor</a>, <a href="#aeb72b2e2b8be6ec3392c569dc53db16f">enterLocalValueArea</a>, <a href="#ad7a01123cf8a0e7acd2b089c65957b26">fastEmit_ri_</a>, <a href="#a1b8715812b9f4dd2bd46163dd1b51128">fastEmitBranch</a>, <a href="#a2b5f2bc37d0cd978d8f38c2b14aabaf7">fastEmitInst_</a>, <a href="#a03ab338e9e5f4ea24b2049ab525525bf">fastEmitInst_extractsubreg</a>, <a href="#aba7be31f2606d1565335458953610fcd">fastEmitInst_f</a>, <a href="#a738eff0daa8e9f33ff056da16adefb4d">fastEmitInst_i</a>, <a href="#a43873dfd861406dc9da68ddcd2bfe1bc">fastEmitInst_r</a>, <a href="#aef1cb331526de21d6b1729a42a72d74f">fastEmitInst_ri</a>, <a href="#a91124ff314dcb25457d0a4bd31fa5c52">fastEmitInst_rii</a>, <a href="#a8d85017ca59fd0d13bde23551dfc5f90">fastEmitInst_rr</a>, <a href="#ae348a9f69bb94b326d0e722c74dfaf7b">fastEmitInst_rri</a>, <a href="#afe20d43bd5edcb69d1a401105ad3d38e">fastEmitInst_rrr</a>, <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a39e2fe24f8016760f80ca14ba3476ebc">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#aaf94fccaa261871e44881773bcdc5ee7">anonymous{MipsFastISel.cpp}::MipsFastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a246d108e7d516b651024d7ab2a75e9be">anonymous{X86FastISel.cpp}::X86FastISel::fastSelectInstruction</a>, <a href="#aebb4626a91d27266548cba7efedc6fe6">finishCondBranch</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="#a52bb01c018d9c9a9bda3d127ab5c7189">handleDbgInfo</a>, <a href="#a3efed0ded914901e7d8741227dfcd249">leaveLocalValueArea</a>, <a href="#aa01ecad5fa09c3afd2f9cdc2a50d707a">lookUpRegForValue</a>, <a href="#ae69b4cef553644304e69e8d671bd5c1c">lowerArguments</a>, <a href="#a284bf291d22c5fe81d9cae4b4f1a4fea">lowerCallTo</a>, <a href="#a352ccfab7392a21f5253bca1791022d5">lowerDbgDeclare</a>, <a href="#a7eb536540d37a55860c52b81778b013e">lowerDbgValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcfastisel-cpp-/ppcfastisel/#a0bdf1d28924ab8477bdbdb193c29fb68">anonymous{PPCFastISel.cpp}::PPCFastISel::PPCFastISel</a>, <a href="#acb5337d3078000bf9b580b28031136af">recomputeInsertPt</a>, <a href="#a9f7b01772fb64eab764bc071e84b860e">selectCall</a>, <a href="#a1434fc5d1782f15a392af0320f13f6c7">selectExtractValue</a>, <a href="#a5718bb42ac48e382b259cd668ad38e21">selectFreeze</a>, <a href="#a82e8b29a5326fe0dc88bf14c244a1b0d">selectInstruction</a>, <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>, <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>, <a href="#ac8bc20b89a02f7d1d402a9fb561d1717">selectPatchpoint</a>, <a href="#a0f9992c5e3a519e4128db320ba2d2e18">selectStackmap</a>, <a href="#a284276bdba816c71f6c16ee08e842b41">selectXRayCustomEvent</a>, <a href="#a8c80b7d55789b6712c22642d4f94b90d">selectXRayTypedEvent</a>, <a href="#a6a4d1b2ae70640755d4942597b65376e">startNewBlock</a>, <a href="#a5a81ca548cc88df15a58aed766bdd890">tryToFoldLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>, <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyfastisel-cpp-/webassemblyfastisel/#a6e71c29d48aa6b75ec5a0ab52b28e67d">anonymous{WebAssemblyFastISel.cpp}::WebAssemblyFastISel::WebAssemblyFastISel</a>.</p>

</div>
</div>

### LastLocalValue {#ade66ed1ba84375d666af381e0153d038}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* llvm::FastISel::LastLocalValue = nullptr</td>
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

<p>The position of the last instruction for materializing constants for use in the current block.</p>


<p>It resets to EmitStartPt when it makes sense (for example, it's usually profitable to avoid function calls between the definition and the use)</p>


<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a376bebd788584bb9147314011dd769c9">getLastLocalValue</a>, <a href="#a3efed0ded914901e7d8741227dfcd249">leaveLocalValueArea</a>, <a href="#a6066bf2100d34651261866662b42114e">removeDeadCode</a>, <a href="#a0bfa1f986356fdcdcab1c98dcf9a84e5">setLastLocalValue</a> and <a href="#a6a4d1b2ae70640755d4942597b65376e">startNewBlock</a>.</p>

</div>
</div>

### LibInfo {#a06203f8be451bbf280e15b45a1b20224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::FastISel::LibInfo</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a1bc852ad7149319b7a54dccd62e77b8f">anonymous{AArch64FastISel.cpp}::AArch64FastISel::AArch64FastISel</a>, <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcfastisel-cpp-/ppcfastisel/#a0bdf1d28924ab8477bdbdb193c29fb68">anonymous{PPCFastISel.cpp}::PPCFastISel::PPCFastISel</a>, <a href="#a82e8b29a5326fe0dc88bf14c244a1b0d">selectInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyfastisel-cpp-/webassemblyfastisel/#a6e71c29d48aa6b75ec5a0ab52b28e67d">anonymous{WebAssemblyFastISel.cpp}::WebAssemblyFastISel::WebAssemblyFastISel</a>.</p>

</div>
</div>

### LocalValueMap {#a1b59baac25d2130c5fde409d31c0f51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, Register&gt; llvm::FastISel::LocalValueMap</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#aa01ecad5fa09c3afd2f9cdc2a50d707a">lookUpRegForValue</a>, <a href="#ae69b4cef553644304e69e8d671bd5c1c">lowerArguments</a>, <a href="#a6a4d1b2ae70640755d4942597b65376e">startNewBlock</a> and <a href="#ac32081d2d2bf0593aebb564fd7e11d8b">updateValueMap</a>.</p>

</div>
</div>

### MCP {#aacd2a710e355d42b82717424f14b1d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineConstantPool&amp; llvm::FastISel::MCP</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a>.</p>

</div>
</div>

### MF {#a79d5f0dde17b382c909b9806e9436592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::FastISel::MF</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armfastisel-cpp-/armfastisel/#ac8e1ee94bced949e039028f65dc5784d">anonymous{ARMFastISel.cpp}::ARMFastISel::ARMFastISel</a>, <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="#a3c0cdb3908fc8b0f795f411e32bb806e">lowerCall</a>, <a href="#a284bf291d22c5fe81d9cae4b4f1a4fea">lowerCallTo</a>, <a href="#ac50c544ca2ade87e7ad0dd6afccdf84c">lowerCallTo</a>, <a href="#a429785d5b6015aff39a7a998d9e70fa3">lowerCallTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#ae62d9e89cea91d950a28eee7e5a32088">anonymous{MipsFastISel.cpp}::MipsFastISel::MipsFastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcfastisel-cpp-/ppcfastisel/#a0bdf1d28924ab8477bdbdb193c29fb68">anonymous{PPCFastISel.cpp}::PPCFastISel::PPCFastISel</a> and <a href="#acf5f7ebfb9fc299fc26be405cbc4e82f">shouldOptForSize</a>.</p>

</div>
</div>

### MFI {#a79b79f09f234c1ef637c6d5a4b91e4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFrameInfo&amp; llvm::FastISel::MFI</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>.</p>

</div>
</div>

### MIMD {#ada788110c53e1082a0d10bb8cb379cce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIMetadata llvm::FastISel::MIMD</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a2b5f2bc37d0cd978d8f38c2b14aabaf7">fastEmitInst_</a>, <a href="#a03ab338e9e5f4ea24b2049ab525525bf">fastEmitInst_extractsubreg</a>, <a href="#aba7be31f2606d1565335458953610fcd">fastEmitInst_f</a>, <a href="#a738eff0daa8e9f33ff056da16adefb4d">fastEmitInst_i</a>, <a href="#a43873dfd861406dc9da68ddcd2bfe1bc">fastEmitInst_r</a>, <a href="#aef1cb331526de21d6b1729a42a72d74f">fastEmitInst_ri</a>, <a href="#a91124ff314dcb25457d0a4bd31fa5c52">fastEmitInst_rii</a>, <a href="#a8d85017ca59fd0d13bde23551dfc5f90">fastEmitInst_rr</a>, <a href="#ae348a9f69bb94b326d0e722c74dfaf7b">fastEmitInst_rri</a>, <a href="#afe20d43bd5edcb69d1a401105ad3d38e">fastEmitInst_rrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a39e2fe24f8016760f80ca14ba3476ebc">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#aaf94fccaa261871e44881773bcdc5ee7">anonymous{MipsFastISel.cpp}::MipsFastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a246d108e7d516b651024d7ab2a75e9be">anonymous{X86FastISel.cpp}::X86FastISel::fastSelectInstruction</a>, <a href="#aebb4626a91d27266548cba7efedc6fe6">finishCondBranch</a>, <a href="#a96b9c043f8fa0596f84e3bf6b25db66a">getCurDebugLoc</a>, <a href="#a52bb01c018d9c9a9bda3d127ab5c7189">handleDbgInfo</a>, <a href="#a9f7b01772fb64eab764bc071e84b860e">selectCall</a>, <a href="#a5718bb42ac48e382b259cd668ad38e21">selectFreeze</a>, <a href="#a82e8b29a5326fe0dc88bf14c244a1b0d">selectInstruction</a>, <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>, <a href="#ac8bc20b89a02f7d1d402a9fb561d1717">selectPatchpoint</a>, <a href="#a0f9992c5e3a519e4128db320ba2d2e18">selectStackmap</a>, <a href="#a284276bdba816c71f6c16ee08e842b41">selectXRayCustomEvent</a> and <a href="#a8c80b7d55789b6712c22642d4f94b90d">selectXRayTypedEvent</a>.</p>

</div>
</div>

### MRI {#a018554adfdbafed22851faa4e25cd4af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::FastISel::MRI</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a981679659ff46a72dc913da01553667a">createResultReg</a>, <a href="#a03ab338e9e5f4ea24b2049ab525525bf">fastEmitInst_extractsubreg</a>, <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a> and <a href="#a5a81ca548cc88df15a58aed766bdd890">tryToFoldLoad</a>.</p>

</div>
</div>

### SkipTargetIndependentISel {#ab7759506c93231c973c2c96665bd6e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastISel::SkipTargetIndependentISel</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a> and <a href="#a82e8b29a5326fe0dc88bf14c244a1b0d">selectInstruction</a>.</p>

</div>
</div>

### TII {#a9c3ffb1ecca8596b6653cc1ffdce8296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo&amp; llvm::FastISel::TII</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a1b8715812b9f4dd2bd46163dd1b51128">fastEmitBranch</a>, <a href="#a2b5f2bc37d0cd978d8f38c2b14aabaf7">fastEmitInst_</a>, <a href="#a03ab338e9e5f4ea24b2049ab525525bf">fastEmitInst_extractsubreg</a>, <a href="#aba7be31f2606d1565335458953610fcd">fastEmitInst_f</a>, <a href="#a738eff0daa8e9f33ff056da16adefb4d">fastEmitInst_i</a>, <a href="#a43873dfd861406dc9da68ddcd2bfe1bc">fastEmitInst_r</a>, <a href="#aef1cb331526de21d6b1729a42a72d74f">fastEmitInst_ri</a>, <a href="#a91124ff314dcb25457d0a4bd31fa5c52">fastEmitInst_rii</a>, <a href="#a8d85017ca59fd0d13bde23551dfc5f90">fastEmitInst_rr</a>, <a href="#ae348a9f69bb94b326d0e722c74dfaf7b">fastEmitInst_rri</a>, <a href="#afe20d43bd5edcb69d1a401105ad3d38e">fastEmitInst_rrr</a>, <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a39e2fe24f8016760f80ca14ba3476ebc">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a246d108e7d516b651024d7ab2a75e9be">anonymous{X86FastISel.cpp}::X86FastISel::fastSelectInstruction</a>, <a href="#a52bb01c018d9c9a9bda3d127ab5c7189">handleDbgInfo</a>, <a href="#a352ccfab7392a21f5253bca1791022d5">lowerDbgDeclare</a>, <a href="#a7eb536540d37a55860c52b81778b013e">lowerDbgValue</a>, <a href="#a9f7b01772fb64eab764bc071e84b860e">selectCall</a>, <a href="#a5718bb42ac48e382b259cd668ad38e21">selectFreeze</a>, <a href="#a58217c3769fe3ee4ac0d221b836849f0">selectIntrinsicCall</a>, <a href="#ac8bc20b89a02f7d1d402a9fb561d1717">selectPatchpoint</a>, <a href="#a0f9992c5e3a519e4128db320ba2d2e18">selectStackmap</a>, <a href="#a284276bdba816c71f6c16ee08e842b41">selectXRayCustomEvent</a>, <a href="#a8c80b7d55789b6712c22642d4f94b90d">selectXRayTypedEvent</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>.</p>

</div>
</div>

### TLI {#accec713e7a93d7b67101624dadf04c98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering&amp; llvm::FastISel::TLI</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a03ab338e9e5f4ea24b2049ab525525bf">fastEmitInst_extractsubreg</a>, <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a39e2fe24f8016760f80ca14ba3476ebc">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#ac9784ca12ba090d5ab2924df8f535a86">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a07fd59cf6f37dd8cc9b6f5f2d0ff3e59">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeFloatZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a935243867ee958b18b7d331014ecdca5">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastSelectInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a246d108e7d516b651024d7ab2a75e9be">anonymous{X86FastISel.cpp}::X86FastISel::fastSelectInstruction</a>, <a href="#a5cec24eb4eadf1232a1463fdbb1cc1a0">getRegForValue</a>, <a href="#a284bf291d22c5fe81d9cae4b4f1a4fea">lowerCallTo</a>, <a href="#a429785d5b6015aff39a7a998d9e70fa3">lowerCallTo</a>, <a href="#ac399325c88de95b03c19e68e1229a8f7">selectBinaryOp</a>, <a href="#aedd7b25487ab7f0871e3d722c1766c18">selectBitCast</a>, <a href="#a59ec796e4ddba85e210d5a226d56f16f">selectCast</a>, <a href="#a1434fc5d1782f15a392af0320f13f6c7">selectExtractValue</a>, <a href="#a9b79346e8152f683a6ad35f8049c74ea">selectFNeg</a>, <a href="#a5718bb42ac48e382b259cd668ad38e21">selectFreeze</a>, <a href="#a09eed569d7f0359be47433ca90532f81">selectGetElementPtr</a>, <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>, <a href="#ac8bc20b89a02f7d1d402a9fb561d1717">selectPatchpoint</a> and <a href="#a0f9992c5e3a519e4128db320ba2d2e18">selectStackmap</a>.</p>

</div>
</div>

### TM {#ad1634563b73a5a9df8b459d913fa4943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine&amp; llvm::FastISel::TM</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="#a3c0cdb3908fc8b0f795f411e32bb806e">lowerCall</a>, <a href="#ab30094b924bc7333b5bf134d7985ca18">selectOperator</a>, <a href="#a284276bdba816c71f6c16ee08e842b41">selectXRayCustomEvent</a> and <a href="#a8c80b7d55789b6712c22642d4f94b90d">selectXRayTypedEvent</a>.</p>

</div>
</div>

### TRI {#afe0bba218f685c37e6c1ca4b49d2d1f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; llvm::FastISel::TRI</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#abb968323ca61fa5d8e99b4523a08f2b2">constrainOperandRegClass</a>, <a href="#a03ab338e9e5f4ea24b2049ab525525bf">fastEmitInst_extractsubreg</a>, <a href="#ac447d383d507dc43c984bd02ff8e74ff">FastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="#a284bf291d22c5fe81d9cae4b4f1a4fea">lowerCallTo</a> and <a href="#ac8bc20b89a02f7d1d402a9fb561d1717">selectPatchpoint</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SavedInsertPt {#a35f55a36c2eb53a2ddda81148868dfd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::FastISel::SavedInsertPt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insertion point before trying to select the current instruction.</p>

<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
