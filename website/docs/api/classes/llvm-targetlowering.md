---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targetlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TargetLowering` Class Reference

<p>This class defines information used to lower LLVM code to legal <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operators that the target instruction selector can accept natively. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TargetLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase">TargetLoweringBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This base class for <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> contains the SelectionDAG-independent parts that can be used from the rest of CodeGen. <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering">AArch64TargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering">AMDGPUTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arctargetlowering">ARCTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armtargetlowering">ARMTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering">AVRTargetLowering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Performs target lowering for the <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a>. <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering">BPFTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cskytargetlowering">CSKYTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/directxtargetlowering">DirectXTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering">HexagonTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering">LanaiTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering">LoongArchTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering">M68kTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering">MSP430TargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering">MipsTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering">NVPTXTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering">PPCTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering">RISCVTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering">SPIRVTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering">SparcTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering">SystemZTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vetargetlowering">VETargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/webassemblytargetlowering">WebAssemblyTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86targetlowering">X86TargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering">XCoreTargetLowering</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering">XtensaTargetLowering</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db162658a7687e8a5df34f5a6aaa840">AsmOperandInfoVector</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94865930eb23376a76409e18190f615d">ConstraintPair</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="#a0b0176781cd4fd9f45cc739f1d007116">TargetLowering::ConstraintType</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c572d6810211a80e26729c2d3cb0a6d">ConstraintGroup</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a94865930eb23376a76409e18190f615d">ConstraintPair</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ConstraintType { <a href="#a0b0176781cd4fd9f45cc739f1d007116">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ConstraintWeight { <a href="#a7f5cab5437026605269663cda7389abc">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa96f111a59a7a2e7f9c689b344543df">TargetLowering</a> (const TargetLowering &amp;)=delete</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49680d92d476c9adc1452ca8e9948f8a">TargetLowering</a> (const TargetMachine &amp;TM)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876bc04d23f1888f4a807eefcc2fa2a7">operator=</a> (const TargetLowering &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ab0804ddb40450da6549e1943817a2">isPositionIndependent</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa17502133164c96bd0943f2241171ead">isSDNodeSourceOfDivergence</a> (const SDNode *N, FunctionLoweringInfo *FLI, UniformityInfo *UA) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa7972a9fb95298bb1f59cf65ec46e9">isReassocProfitable</a> (SelectionDAG &amp;DAG, SDValue N0, SDValue N1) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae21fd7066178a309d6f89521e1ceb247">isReassocProfitable</a> (MachineRegisterInfo &amp;MRI, Register N0, Register N1) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa67e0a840aaf40e6406d7be705f44af5">isSDNodeAlwaysUniform</a> (const SDNode *N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d63fccccfc98800dc7c8bb11356e90">getPreIndexedAddressParts</a> (SDNode *, SDValue &amp;, SDValue &amp;, ISD::MemIndexedMode &amp;, SelectionDAG &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true by value, base pointer and offset pointer and addressing mode by reference if the node's address can be legally represented as pre-indexed load / store address. <a href="#ad9d63fccccfc98800dc7c8bb11356e90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac01f44d948268acd41c5994ea6cc1369">getPostIndexedAddressParts</a> (SDNode *, SDNode *, SDValue &amp;, SDValue &amp;, ISD::MemIndexedMode &amp;, SelectionDAG &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true by value, base pointer and offset pointer and addressing mode by reference if this node can be combined with a load / store to form a post-indexed load / store. <a href="#ac01f44d948268acd41c5994ea6cc1369">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97f597434d447bcc927007f32b35d3d4">isIndexingLegal</a> (MachineInstr &amp;MI, Register Base, Register Offset, bool IsPre, MachineRegisterInfo &amp;MRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified base+offset is a legal indexed addressing mode for this target. <a href="#a97f597434d447bcc927007f32b35d3d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded686370215fda472fa7b38ccbba458">getJumpTableEncoding</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the entry encoding for a jump table in the current function. <a href="#aded686370215fda472fa7b38ccbba458">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c7c474fbd3717354a6297baa84a478">getJumpTableRegTy</a> (const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf30ced2ac2474a0dd5af2e3417c7b7d">LowerCustomJumpTableEntry</a> (const MachineJumpTableInfo *, const MachineBasicBlock *, unsigned, MCContext &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4681990679f127bf757790e59678f80">getPICJumpTableRelocBase</a> (SDValue Table, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns relocation base for the given PIC jumptable. <a href="#ab4681990679f127bf757790e59678f80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a993d38cd5b37a6ee0c9c3cb24ada5392">getPICJumpTableRelocBaseExpr</a> (const MachineFunction *MF, unsigned JTI, MCContext &amp;Ctx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This returns the relocation base for the given PIC jumptable, the same as getPICJumpTableRelocBase, but as an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a>. <a href="#a993d38cd5b37a6ee0c9c3cb24ada5392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74dabfbe18cbb61e4a1935eb1bf4942b">isOffsetFoldingLegal</a> (const GlobalAddressSDNode *GA) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if folding a constant offset with the given GlobalAddress is legal. <a href="#a74dabfbe18cbb61e4a1935eb1bf4942b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebfdd629d9e82d02230d041fadfa540c">isInlineAsmTargetBranch</a> (const SmallVectorImpl&lt; StringRef &gt; &amp;AsmStrs, unsigned OpNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>On x86, return true if the operand with index OpNo is a CALL or JUMP instruction, which can use either a memory constraint or an address constraint. <a href="#aebfdd629d9e82d02230d041fadfa540c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e6f8d5c56365fe5e9a6e4f9581ddb94">isInTailCallPosition</a> (SelectionDAG &amp;DAG, SDNode *Node, SDValue &amp;Chain) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f2d0a1eebd818fb037a64c40cf0521">softenSetCCOperands</a> (SelectionDAG &amp;DAG, EVT VT, SDValue &amp;NewLHS, SDValue &amp;NewRHS, ISD::CondCode &amp;CCCode, const SDLoc &amp;DL, const SDValue OldLHS, const SDValue OldRHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a518caa772bb677e2e590fad18c6d07ce">softenSetCCOperands</a> (SelectionDAG &amp;DAG, EVT VT, SDValue &amp;NewLHS, SDValue &amp;NewRHS, ISD::CondCode &amp;CCCode, const SDLoc &amp;DL, const SDValue OldLHS, const SDValue OldRHS, SDValue &amp;Chain, bool IsSignaling=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18dbec68fb7d9eadbe98106caa943e51">visitMaskedLoad</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, MachineMemOperand *MMO, SDValue &amp;NewLoad, SDValue Ptr, SDValue PassThru, SDValue Mask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace423253c9f88eb6f6f395daa4bf02b7">visitMaskedStore</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, MachineMemOperand *MMO, SDValue Ptr, SDValue Val, SDValue Mask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4a2abb087afa577d8f4239b01acbea0">makeLibCall</a> (SelectionDAG &amp;DAG, RTLIB::Libcall LC, EVT RetVT, ArrayRef&lt; SDValue &gt; Ops, MakeLibCallOptions CallOptions, const SDLoc &amp;dl, SDValue Chain=SDValue()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pair of (return value, chain). <a href="#ad4a2abb087afa577d8f4239b01acbea0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac11ad16fa22b9e7a5a04849e52b34fef">parametersInCSRMatch</a> (const MachineRegisterInfo &amp;MRI, const uint32_t *CallerPreservedMask, const SmallVectorImpl&lt; CCValAssign &gt; &amp;ArgLocs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether parameters to a call that are passed in callee saved registers are the same as from the calling function. <a href="#ac11ad16fa22b9e7a5a04849e52b34fef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e48d09cc181b603b17d4e385cc4bb7">findOptimalMemOpLowering</a> (std::vector&lt; EVT &gt; &amp;MemOps, unsigned Limit, const MemOp &amp;Op, unsigned DstAS, unsigned SrcAS, const AttributeList &amp;FuncAttributes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines the optimal series of memory ops to replace the memset / memcpy. <a href="#a60e48d09cc181b603b17d4e385cc4bb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a3aaac8faabe7dc09114d716a93eba">ShrinkDemandedConstant</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, TargetLoweringOpt &amp;TLO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if the specified operand of the specified instruction is a constant integer. <a href="#ac6a3aaac8faabe7dc09114d716a93eba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bfa6eb6976f71f59de24f14085056b9">ShrinkDemandedConstant</a> (SDValue Op, const APInt &amp;DemandedBits, TargetLoweringOpt &amp;TLO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper wrapper around ShrinkDemandedConstant, demanding all elements. <a href="#a0bfa6eb6976f71f59de24f14085056b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b1a3e65e45ccd3664f44797e7e061ab">targetShrinkDemandedConstant</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, TargetLoweringOpt &amp;TLO) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c2837ca8052c0432179f52148da7c2">ShrinkDemandedOp</a> (SDValue Op, unsigned BitWidth, const APInt &amp;DemandedBits, TargetLoweringOpt &amp;TLO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert x+y to (VT)((SmallVT)x+(SmallVT)y) if the casts are free. <a href="#a60c2837ca8052c0432179f52148da7c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2fd70d9aeac9343fa8f00ccdeff7f0b">SimplifyDemandedBits</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, KnownBits &amp;Known, TargetLoweringOpt &amp;TLO, unsigned Depth=0, bool AssumeSingleUse=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look at <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>. <a href="#ab2fd70d9aeac9343fa8f00ccdeff7f0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e35b84c574900228ebd4b735176fece">SimplifyDemandedBits</a> (SDValue Op, const APInt &amp;DemandedBits, KnownBits &amp;Known, TargetLoweringOpt &amp;TLO, unsigned Depth=0, bool AssumeSingleUse=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper wrapper around SimplifyDemandedBits, demanding all elements. <a href="#a5e35b84c574900228ebd4b735176fece">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7ff8987a5190c8fbac02b359dffa536">SimplifyDemandedBits</a> (SDValue Op, const APInt &amp;DemandedBits, DAGCombinerInfo &amp;DCI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper wrapper around SimplifyDemandedBits. <a href="#aa7ff8987a5190c8fbac02b359dffa536">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9eb27b027f4a319ed244f2da8dbb9cc">SimplifyDemandedBits</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, DAGCombinerInfo &amp;DCI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper wrapper around SimplifyDemandedBits. <a href="#ac9eb27b027f4a319ed244f2da8dbb9cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0338302ee706a6cd16534e768210b0b2">SimplifyMultipleUseDemandedBits</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, SelectionDAG &amp;DAG, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>More limited version of SimplifyDemandedBits that can be used to "look
through" ops that don't contribute to the DemandedBits/DemandedElts - bitwise ops etc. <a href="#a0338302ee706a6cd16534e768210b0b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb81fb8d18522d12e39a60c3b43cf291">SimplifyMultipleUseDemandedBits</a> (SDValue Op, const APInt &amp;DemandedBits, SelectionDAG &amp;DAG, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper wrapper around SimplifyMultipleUseDemandedBits, demanding all elements. <a href="#afb81fb8d18522d12e39a60c3b43cf291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a480a8e3181c852945f597bad4fd0d9c3">SimplifyMultipleUseDemandedVectorElts</a> (SDValue Op, const APInt &amp;DemandedElts, SelectionDAG &amp;DAG, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper wrapper around SimplifyMultipleUseDemandedBits, demanding all bits from only some vector elements. <a href="#a480a8e3181c852945f597bad4fd0d9c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45a058376b4d2b008f7ea5ca16cecf55">SimplifyDemandedVectorElts</a> (SDValue Op, const APInt &amp;DemandedEltMask, APInt &amp;KnownUndef, APInt &amp;KnownZero, TargetLoweringOpt &amp;TLO, unsigned Depth=0, bool AssumeSingleUse=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look at Vector <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>. <a href="#a45a058376b4d2b008f7ea5ca16cecf55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0df0d85885c52c23edc2df2964dda688">SimplifyDemandedVectorElts</a> (SDValue Op, const APInt &amp;DemandedElts, DAGCombinerInfo &amp;DCI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper wrapper around SimplifyDemandedVectorElts. <a href="#a0df0d85885c52c23edc2df2964dda688">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad0d7dc149e145475abe9f7c9769d93">shouldSimplifyDemandedVectorElts</a> (SDValue Op, const TargetLoweringOpt &amp;TLO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports simplifying demanded vector elements by converting them to undefs. <a href="#aaad0d7dc149e145475abe9f7c9769d93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c00d269d51235a7579e37163eeb3edc">computeKnownBitsForTargetNode</a> (const SDValue Op, KnownBits &amp;Known, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which of the bits specified in Mask are known to be either zero or one and return them in the KnownZero/KnownOne bitsets. <a href="#a8c00d269d51235a7579e37163eeb3edc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b6795985b3405f69339661de5d860c">computeKnownBitsForTargetInstr</a> (GISelKnownBits &amp;Analysis, Register R, KnownBits &amp;Known, const APInt &amp;DemandedElts, const MachineRegisterInfo &amp;MRI, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which of the bits specified in Mask are known to be either zero or one and return them in the KnownZero/KnownOne bitsets. <a href="#af7b6795985b3405f69339661de5d860c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae917d897ff4613b4cfdc9cd4dadade41">computeKnownAlignForTargetInstr</a> (GISelKnownBits &amp;Analysis, Register R, const MachineRegisterInfo &amp;MRI, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the known alignment for the pointer value <span class="doxyComputerOutput">R</span>. <a href="#ae917d897ff4613b4cfdc9cd4dadade41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89837a1ae285b93a15adff98bbb21efb">computeKnownBitsForFrameIndex</a> (int FIOp, KnownBits &amp;Known, const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which of the bits of FrameIndex <span class="doxyComputerOutput">FIOp</span> are known to be 0. <a href="#a89837a1ae285b93a15adff98bbb21efb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e478aced9c847bcb02f8a94e498c2e7">ComputeNumSignBitsForTargetNode</a> (SDValue Op, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method can be implemented by targets that want to expose additional information about sign bits to the DAG <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a>. <a href="#a6e478aced9c847bcb02f8a94e498c2e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b359fbfa123fbf333095817e902cf0c">computeNumSignBitsForTargetInstr</a> (GISelKnownBits &amp;Analysis, Register R, const APInt &amp;DemandedElts, const MachineRegisterInfo &amp;MRI, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method can be implemented by targets that want to expose additional information about sign bits to GlobalISel combiners. <a href="#a9b359fbfa123fbf333095817e902cf0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af44b4b9c14768bdaaafa69cd6d5c3d46">SimplifyDemandedVectorEltsForTargetNode</a> (SDValue Op, const APInt &amp;DemandedElts, APInt &amp;KnownUndef, APInt &amp;KnownZero, TargetLoweringOpt &amp;TLO, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to simplify any target nodes based on the demanded vector elements, returning true on success. <a href="#af44b4b9c14768bdaaafa69cd6d5c3d46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bb3f6ea028996773613a5f135b4d083">SimplifyDemandedBitsForTargetNode</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, KnownBits &amp;Known, TargetLoweringOpt &amp;TLO, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to simplify any target nodes based on the demanded bits/elts, returning true on success. <a href="#a1bb3f6ea028996773613a5f135b4d083">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f40e066df2407ab1e901ca999d717e">SimplifyMultipleUseDemandedBitsForTargetNode</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, SelectionDAG &amp;DAG, unsigned Depth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>More limited version of SimplifyDemandedBits that can be used to "look
through" ops that don't contribute to the DemandedBits/DemandedElts - bitwise ops etc. <a href="#a03f40e066df2407ab1e901ca999d717e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb1ad8b21c9956ffb90121e24f8bc116">isGuaranteedNotToBeUndefOrPoisonForTargetNode</a> (SDValue Op, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, bool PoisonOnly, unsigned Depth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this function can prove that <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is never poison and, if <span class="doxyComputerOutput">PoisonOnly</span> is false, does not have undef bits. <a href="#abb1ad8b21c9956ffb90121e24f8bc116">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a690ecd418854c4f2bea36d278c8cb7a2">canCreateUndefOrPoisonForTargetNode</a> (SDValue Op, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, bool PoisonOnly, bool ConsiderFlags, unsigned Depth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> can create undef or poison from non-undef &amp; non-poison operands. <a href="#a690ecd418854c4f2bea36d278c8cb7a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a696ff12171c8e0cf9f749fe7365ab40d">buildLegalVectorShuffle</a> (EVT VT, const SDLoc &amp;DL, SDValue N0, SDValue N1, MutableArrayRef&lt; int &gt; Mask, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to build a legal vector shuffle using the provided parameters or equivalent variations. <a href="#a696ff12171c8e0cf9f749fe7365ab40d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b2f46b93af4466b33909730c2b2e6b">getTargetConstantFromLoad</a> (LoadSDNode *LD) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns the constant pool value that will be loaded by LD. <a href="#a18b2f46b93af4466b33909730c2b2e6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a1d4426a85849e75f56ef9d3b13fecc">isKnownNeverNaNForTargetNode</a> (SDValue Op, const SelectionDAG &amp;DAG, bool SNaN=false, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">SNaN</span> is false,. <a href="#a3a1d4426a85849e75f56ef9d3b13fecc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa31fb5c8038b82f00b3a1d19144c0516">isSplatValueForTargetNode</a> (SDValue Op, const APInt &amp;DemandedElts, APInt &amp;UndefElts, const SelectionDAG &amp;DAG, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if vector <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> has the same value across all <span class="doxyComputerOutput">DemandedElts</span>, indicating any elements which may be undef in the output <span class="doxyComputerOutput">UndefElts</span>. <a href="#aa31fb5c8038b82f00b3a1d19144c0516">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4568c6fee399b92f6971aa10266a89b0">isTargetCanonicalConstantNode</a> (SDValue Op) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given Opc is considered a canonical constant for the target, which should not be transformed back into a BUILD_VECTOR. <a href="#a4568c6fee399b92f6971aa10266a89b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49086baced6151325ba4b88ecdd5383f">isConstTrueVal</a> (SDValue N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if the N is a constant or constant vector equal to the true value from <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a79adbcc34e24b86ef8a216a34ccf5af8">getBooleanContents()</a>. <a href="#a49086baced6151325ba4b88ecdd5383f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a485c321d878ce722bb8d19a4b9d81657">isConstFalseVal</a> (SDValue N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if the N is a constant or constant vector equal to the false value from <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a79adbcc34e24b86ef8a216a34ccf5af8">getBooleanContents()</a>. <a href="#a485c321d878ce722bb8d19a4b9d81657">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dc906a01997a28f62fd05f6470d7dd7">isExtendedTrueVal</a> (const ConstantSDNode *N, EVT VT, bool SExt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if <span class="doxyComputerOutput">N</span> is a True value when extended to <span class="doxyComputerOutput">VT</span>. <a href="#a2dc906a01997a28f62fd05f6470d7dd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32a31ce1e9f6e4b965d11feb2501fc47">SimplifySetCC</a> (EVT VT, SDValue N0, SDValue N1, ISD::CondCode Cond, bool foldBooleans, DAGCombinerInfo &amp;DCI, const SDLoc &amp;dl) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to simplify a setcc built with the specified operands and cc. <a href="#a32a31ce1e9f6e4b965d11feb2501fc47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb3dd542dde309c8e94f2a54f041814">unwrapAddress</a> (SDValue N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe66a168970ddd74cce6fbc9a40589c7">isGAPlusOffset</a> (SDNode *N, const GlobalValue *&amp;GA, int64_t &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true (and the <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> and the offset) if the node is a GlobalAddress + offset. <a href="#abe66a168970ddd74cce6fbc9a40589c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a041dc0924ebd52a3eda7e1a22c00310b">PerformDAGCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be invoked for all target nodes and for any target-independent nodes that the target has registered with invoke it for. <a href="#a041dc0924ebd52a3eda7e1a22c00310b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acadf633df07f9e11330ae99edf3e1bb7">isDesirableToCommuteWithShift</a> (const SDNode *N, CombineLevel Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to move this shift by a constant amount through its operand, adjusting any immediate operands as necessary to preserve semantics. <a href="#acadf633df07f9e11330ae99edf3e1bb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10338eadd129baf2b64756673c1ea883">isDesirableToCommuteWithShift</a> (const MachineInstr &amp;MI, bool IsAfterLegal) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GlobalISel - return true if it is profitable to move this shift by a constant amount through its operand, adjusting any immediate operands as necessary to preserve semantics. <a href="#a10338eadd129baf2b64756673c1ea883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f691332d3b84bef71821427b0c676dd">isDesirableToPullExtFromShl</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GlobalISel - return true if it's profitable to perform the combine: shl ([sza]ext x), y =&gt; zext (shl x, y) <a href="#a8f691332d3b84bef71821427b0c676dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac14a71b7c36f34100de107aadccc5578">AndOrSETCCFoldKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79ec6f151d15fbecd05a6d0c47c3729">isDesirableToCombineLogicOpOfSETCC</a> (const SDNode *LogicOp, const SDNode *SETCC0, const SDNode *SETCC1) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa536ba062854f0951a19b7457665c96">isDesirableToCommuteXorWithShift</a> (const SDNode *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to combine an XOR of a logical shift to create a logical shift of NOT. <a href="#aaa536ba062854f0951a19b7457665c96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c66bde62e1fbe747611b8d385ad6c9a">isTypeDesirableForOp</a> (unsigned, EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has native support for the specified value type and it is 'desirable' to use the type for the given node type. <a href="#a7c66bde62e1fbe747611b8d385ad6c9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7c382c626528004a59c365a2bc7e98">isDesirableToTransformToIntegerOp</a> (unsigned, EVT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable for dag combiner to transform a floating point op of specified opcode to a equivalent op of an integer type. <a href="#aff7c382c626528004a59c365a2bc7e98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67dd43e2dfeed538828a0028fef372d3">IsDesirableToPromoteOp</a> (SDValue, EVT &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method query the target whether it is beneficial for dag combiner to promote the specified node. <a href="#a67dd43e2dfeed538828a0028fef372d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17694ad399c24aae0d2c0ecfbecfea5a">supportSwiftError</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports swifterror attribute. <a href="#a17694ad399c24aae0d2c0ecfbecfea5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf63d5761e47f6e642a82cab1abda28f">supportSplitCSR</a> (MachineFunction *MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports that a subset of CSRs for the given machine function is handled explicitly via copies. <a href="#adf63d5761e47f6e642a82cab1abda28f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0160cf5c2cae2754444db153907790a2">supportKCFIBundles</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports kcfi operand bundles. <a href="#a0160cf5c2cae2754444db153907790a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12cbb115116dd32eb6c32ba191761093">supportPtrAuthBundles</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports ptrauth operand bundles. <a href="#a12cbb115116dd32eb6c32ba191761093">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa15229fc1a15ce3693166d66a0994334">initializeSplitCSR</a> (MachineBasicBlock *Entry) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform necessary initialization to handle a subset of CSRs explicitly via copies. <a href="#aa15229fc1a15ce3693166d66a0994334">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73bf38dbdcdff5a2befaff46205f3541">insertCopiesSplitCSR</a> (MachineBasicBlock *Entry, const SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;Exits) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert explicit copies in entry and exit blocks. <a href="#a73bf38dbdcdff5a2befaff46205f3541">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3e575b3cff4eb444567d50959b929c">getNegatedExpression</a> (SDValue Op, SelectionDAG &amp;DAG, bool LegalOps, bool OptForSize, NegatibleCost &amp;Cost, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the newly negated expression if the cost is not expensive and set the cost in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a></span> to indicate that if it is cheaper or neutral to do the negation. <a href="#aea3e575b3cff4eb444567d50959b929c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1e2f811ae9139b9543751585239443">getCheaperOrNeutralNegatedExpression</a> (SDValue Op, SelectionDAG &amp;DAG, bool LegalOps, bool OptForSize, const NegatibleCost CostThreshold=NegatibleCost::Neutral, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48fe15bdf777438d3ff912a613650642">getCheaperNegatedExpression</a> (SDValue Op, SelectionDAG &amp;DAG, bool LegalOps, bool OptForSize, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the helper function to return the newly negated expression only when the cost is cheaper. <a href="#a48fe15bdf777438d3ff912a613650642">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235b6c220471b5f4e283c7ed685e0005">getNegatedExpression</a> (SDValue Op, SelectionDAG &amp;DAG, bool LegalOps, bool OptForSize, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the helper function to return the newly negated expression if the cost is not expensive. <a href="#a235b6c220471b5f4e283c7ed685e0005">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67bcd59b7c8b892b3252d10a6ebf8370">splitValueIntoRegisterParts</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Val, SDValue *Parts, unsigned NumParts, MVT PartVT, std::optional&lt; CallingConv::ID &gt; CC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-specific splitting of values into parts that fit a register storing a legal type. <a href="#a67bcd59b7c8b892b3252d10a6ebf8370">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade4fa73063019f286fb23ac86df8839e">checkForPhysRegDependency</a> (SDNode *Def, SDNode *User, unsigned Op, const TargetRegisterInfo *TRI, const TargetInstrInfo *TII, unsigned &amp;PhysReg, int &amp;Cost) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows the target to handle physreg-carried dependency in target-specific way. <a href="#ade4fa73063019f286fb23ac86df8839e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7271d32a363f6f4c4d632f1bf4986b33">joinRegisterPartsIntoValue</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, const SDValue *Parts, unsigned NumParts, MVT PartVT, EVT ValueVT, std::optional&lt; CallingConv::ID &gt; CC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-specific combining of register parts into its original value. <a href="#a7271d32a363f6f4c4d632f1bf4986b33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0296381d01e49bf5c4cbe0f3dc07187">LowerFormalArguments</a> (SDValue, CallingConv::ID, bool, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;, const SDLoc &amp;, SelectionDAG &amp;, SmallVectorImpl&lt; SDValue &gt; &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the incoming (formal) arguments, described by the Ins array, into the specified DAG. <a href="#ab0296381d01e49bf5c4cbe0f3dc07187">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabd42a6eddc3daec9153679b54f79300">LowerCallTo</a> (CallLoweringInfo &amp;CLI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function lowers an abstract call to a function into an actual call. <a href="#aabd42a6eddc3daec9153679b54f79300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7446faa85fb7b6ebdbd136f514eee0af">LowerCall</a> (CallLoweringInfo &amp;, SmallVectorImpl&lt; SDValue &gt; &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower calls into the specified DAG. <a href="#a7446faa85fb7b6ebdbd136f514eee0af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7c36d5b8de34e8f925d02cc2c4000e3">HandleByVal</a> (CCState *, unsigned &amp;, Align) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-specific cleanup for formal ByVal parameters. <a href="#ad7c36d5b8de34e8f925d02cc2c4000e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc21228b6db4542de1339af252b2a725">CanLowerReturn</a> (CallingConv::ID, MachineFunction &amp;, bool, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;, LLVMContext &amp;, const Type *RetTy) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook should be implemented to check whether the return values described by the Outs array can fit into the return registers. <a href="#afc21228b6db4542de1339af252b2a725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7ab87c087e9c55f4acc89ebe8ecbd5c">LowerReturn</a> (SDValue, CallingConv::ID, bool, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;, const SmallVectorImpl&lt; SDValue &gt; &amp;, const SDLoc &amp;, SelectionDAG &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by the Outs array, into the specified DAG. <a href="#ac7ab87c087e9c55f4acc89ebe8ecbd5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a138a6e09184eae2d1d412cd4e8d60e11">isUsedByReturnOnly</a> (SDNode *, SDValue &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if result of the specified node is used by a return node only. <a href="#a138a6e09184eae2d1d412cd4e8d60e11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4502810d1edc3d8931681159af36d3b">mayBeEmittedAsTailCall</a> (const CallInst *) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target may be able emit the call instruction as a tail call. <a href="#ae4502810d1edc3d8931681159af36d3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a349007dec8d5a6ab5e7d338c282003ca">getRegisterByName</a> (const char *RegName, LLT Ty, const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the name passed in. <a href="#a349007dec8d5a6ab5e7d338c282003ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b10a312e4ab7eb05f1b88f6e5eb8e56">getTypeForExtReturn</a> (LLVMContext &amp;Context, EVT VT, ISD::NodeType) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type that should be used to zero or sign extend a zeroext/signext integer return value. <a href="#a2b10a312e4ab7eb05f1b88f6e5eb8e56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9df75d2d0cb54ed147aaf46cd2b1e84">functionArgumentNeedsConsecutiveRegisters</a> (Type *Ty, CallingConv::ID CallConv, bool isVarArg, const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For some targets, an LLVM struct type must be broken down into multiple simple types, but the calling convention specifies that the entire struct must be passed in a block of consecutive registers. <a href="#ac9df75d2d0cb54ed147aaf46cd2b1e84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac030eb4ba5f177779c4f903fabfdb285">shouldSplitFunctionArgumentsAsLittleEndian</a> (const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For most targets, an LLVM type must be broken down into multiple smaller types. <a href="#ac030eb4ba5f177779c4f903fabfdb285">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad87e9267a35f4fd6e8e3b66910ac5dea">getScratchRegisters</a> (CallingConv::ID CC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a 0 terminated array of registers that can be safely used as scratch registers. <a href="#ad87e9267a35f4fd6e8e3b66910ac5dea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac62b35c70e62f4a9d4c3e9117de615e4">getRoundingControlRegisters</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a 0 terminated array of rounding control registers that can be attached into strict FP call. <a href="#ac62b35c70e62f4a9d4c3e9117de615e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c8ebb50f3043a4715d5a182288e8c82">prepareVolatileOrAtomicLoad</a> (SDValue Chain, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is used to prepare for a volatile or atomic load. <a href="#a4c8ebb50f3043a4715d5a182288e8c82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12431703c17466d24d4bf388ce467ea3">LowerOperationWrapper</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is invoked by the type legalizer to legalize nodes with an illegal operand type but legal result types. <a href="#a12431703c17466d24d4bf388ce467ea3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04403a336136814ab74d9e2315bcfe23">LowerOperation</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is invoked for operations that are unsupported by the target, which are registered to use 'custom' lowering, and whose defined values are all legal. <a href="#a04403a336136814ab74d9e2315bcfe23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a134fd88697c3564433ba71a0202153e6">ReplaceNodeResults</a> (SDNode *, SmallVectorImpl&lt; SDValue &gt; &amp;, SelectionDAG &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is invoked when a node result type is illegal for the target, and the operation was registered to use 'custom' lowering for that result type. <a href="#a134fd88697c3564433ba71a0202153e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa07a74d942f49b11a81baf6dba21726e">getTargetNodeName</a> (unsigned Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns the name of a target specific DAG node. <a href="#aa07a74d942f49b11a81baf6dba21726e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb05aefedc1e93f32b6061a23542d508">createFastISel</a> (FunctionLoweringInfo &amp;, const TargetLibraryInfo *) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns a target specific <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> object, or null if the target does not support "fast" ISel. <a href="#adb05aefedc1e93f32b6061a23542d508">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25df8af0900b4a664055a7ccba026531">verifyReturnAddressArgumentIsConstant</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a4ecad8579717395c05ad1218d440b9">verifyTargetSDNode</a> (const SDNode *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the given <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. Aborts if it is invalid. <a href="#a5a4ecad8579717395c05ad1218d440b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa394506e609b72337e9c664ef264db8b">ExpandInlineAsm</a> (CallInst *) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook allows the target to expand an inline asm call to be explicit llvm code if it wants to. <a href="#aa394506e609b72337e9c664ef264db8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3db162658a7687e8a5df34f5a6aaa840">AsmOperandInfoVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c5e8b6aef41aead06d61ff0530ed9c2">ParseConstraints</a> (const DataLayout &amp;DL, const TargetRegisterInfo *TRI, const CallBase &amp;Call) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split up the constraint string from the inline assembly value into the specific constraints and their prefixes, and also tie in the associated operand values. <a href="#a1c5e8b6aef41aead06d61ff0530ed9c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7f5cab5437026605269663cda7389abc">ConstraintWeight</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a242f3e03f104dc030614c21db016e206">getMultipleConstraintMatchWeight</a> (AsmOperandInfo &amp;info, int maIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine constraint type and operand type and determine a weight value. <a href="#a242f3e03f104dc030614c21db016e206">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7f5cab5437026605269663cda7389abc">ConstraintWeight</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa66a325b7b8c5c79eb2c8e9822ffd2">getSingleConstraintMatchWeight</a> (AsmOperandInfo &amp;info, const char *constraint) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine constraint string and operand type and determine a weight value. <a href="#afaa66a325b7b8c5c79eb2c8e9822ffd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a279a7f92d056886ac713c0f06cc73045">ComputeConstraintToUse</a> (AsmOperandInfo &amp;OpInfo, SDValue Op, SelectionDAG *DAG=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines the constraint code and constraint type to use for the specific <a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a>, setting OpInfo.ConstraintCode and OpInfo.ConstraintType. <a href="#a279a7f92d056886ac713c0f06cc73045">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0b0176781cd4fd9f45cc739f1d007116">ConstraintType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b2deb637d370d68d3bd3786c21e415">getConstraintType</a> (StringRef Constraint) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a constraint, return the type of constraint it is for this target. <a href="#a45b2deb637d370d68d3bd3786c21e415">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0c572d6810211a80e26729c2d3cb0a6d">ConstraintGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09429106263aff7968fde2119706fd42">getConstraintPreferences</a> (AsmOperandInfo &amp;OpInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an OpInfo with list of constraints codes as strings, return a sorted Vector of pairs of constraint codes and their types in priority of what we'd prefer to lower them as. <a href="#a09429106263aff7968fde2119706fd42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af09507c47dcb4cdb2a13064aaa6d5243">getRegForInlineAsmConstraint</a> (const TargetRegisterInfo *TRI, StringRef Constraint, MVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a physical register constraint (e.g. <a href="#af09507c47dcb4cdb2a13064aaa6d5243">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3acbc2d34d9a6d35b63a04f0ae20136c">getInlineAsmMemConstraint</a> (StringRef ConstraintCode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeca75f6b346035626e8849863671e02d">LowerXConstraint</a> (EVT ConstraintVT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to replace an X constraint, which matches anything, with another that has more specific requirements based on the type of the corresponding operand. <a href="#aeca75f6b346035626e8849863671e02d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3f2eb78e627fd0d785fd4119d299558">LowerAsmOperandForConstraint</a> (SDValue Op, StringRef Constraint, std::vector&lt; SDValue &gt; &amp;Ops, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower the specified operand into the Ops vector. <a href="#ad3f2eb78e627fd0d785fd4119d299558">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91072af01cf52109f52a15ea367157bf">LowerAsmOutputForConstraint</a> (SDValue &amp;Chain, SDValue &amp;Glue, const SDLoc &amp;DL, const AsmOperandInfo &amp;OpInfo, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79bdddcacb7e2e24a0ba20714b80c18a">CollectTargetIntrinsicOperands</a> (const CallInst &amp;I, SmallVectorImpl&lt; SDValue &gt; &amp;Ops, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36c8f3817aaf6184163227ef33e08032">BuildSDIV</a> (SDNode *N, SelectionDAG &amp;DAG, bool IsAfterLegalization, bool IsAfterLegalTypes, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a634e703cb950d5425ce8594ea59ef3bd">BuildUDIV</a> (SDNode *N, SelectionDAG &amp;DAG, bool IsAfterLegalization, bool IsAfterLegalTypes, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac059b1ca86f2540e9fcfbee0a0da1c7c">buildSDIVPow2WithCMov</a> (SDNode *N, const APInt &amp;Divisor, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10e676263a198d8cd480918492893dcb">BuildSDIVPow2</a> (SDNode *N, const APInt &amp;Divisor, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets may override this function to provide custom SDIV lowering for power-of-2 denominators. <a href="#a10e676263a198d8cd480918492893dcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe774a33e51c905a23e19b7b9803e8eb">BuildSREMPow2</a> (SDNode *N, const APInt &amp;Divisor, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets may override this function to provide custom SREM lowering for power-of-2 denominators. <a href="#abe774a33e51c905a23e19b7b9803e8eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad540ba702458038e9dfc70c04d4286ec">combineRepeatedFPDivisors</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate whether this target prefers to combine FDIVs with the same divisor. <a href="#ad540ba702458038e9dfc70c04d4286ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5c79ba78f8b97824689ec83267d746">getSqrtEstimate</a> (SDValue Operand, SelectionDAG &amp;DAG, int Enabled, int &amp;RefinementSteps, bool &amp;UseOneConstNR, bool Reciprocal) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hooks for building estimates in place of slower divisions and square roots. <a href="#a0f5c79ba78f8b97824689ec83267d746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb677d589b9b39e03a0f38a86411ad3b">createSelectForFMINNUM_FMAXNUM</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to convert the fminnum/fmaxnum to a compare/select sequence. <a href="#afb677d589b9b39e03a0f38a86411ad3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4e4a07bf2d469f04b430edb380ee1b5">getRecipEstimate</a> (SDValue Operand, SelectionDAG &amp;DAG, int Enabled, int &amp;RefinementSteps) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reciprocal estimate value for the input operand. <a href="#aa4e4a07bf2d469f04b430edb380ee1b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89e60908750fd1cca69d96e7aa41ba5b">getSqrtInputTest</a> (SDValue Operand, SelectionDAG &amp;DAG, const DenormalMode &amp;Mode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target-dependent comparison result if the input operand is suitable for use with a square root estimate calculation. <a href="#a89e60908750fd1cca69d96e7aa41ba5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd1a92af13465b269b22fb6b1cddffaf">getSqrtResultForDenormInput</a> (SDValue Operand, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target-dependent result if the input operand is not suitable for use with a square root estimate calculation. <a href="#abd1a92af13465b269b22fb6b1cddffaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7581f7a7740ac3c1dc73fd7aeeccc63">expandMUL_LOHI</a> (unsigned Opcode, EVT VT, const SDLoc &amp;dl, SDValue LHS, SDValue RHS, SmallVectorImpl&lt; SDValue &gt; &amp;Result, EVT HiLoVT, SelectionDAG &amp;DAG, MulExpansionKind Kind, SDValue LL=SDValue(), SDValue LH=SDValue(), SDValue RL=SDValue(), SDValue RH=SDValue()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand a MUL or [US]MUL_LOHI of n-bit values into two or four nodes, respectively, each computing an n/2-bit part of the result. <a href="#ac7581f7a7740ac3c1dc73fd7aeeccc63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab707d083b764fa474237a76bc4b05694">expandMUL</a> (SDNode *N, SDValue &amp;Lo, SDValue &amp;Hi, EVT HiLoVT, SelectionDAG &amp;DAG, MulExpansionKind Kind, SDValue LL=SDValue(), SDValue LH=SDValue(), SDValue RL=SDValue(), SDValue RH=SDValue()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand a MUL into two nodes. <a href="#ab707d083b764fa474237a76bc4b05694">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abddef937939ecbe4cff930c60b055176">expandDIVREMByConstant</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Result, EVT HiLoVT, SelectionDAG &amp;DAG, SDValue LL=SDValue(), SDValue LH=SDValue()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to expand an n-bit div/rem/divrem by constant using a n/2-bit urem by constant and other arithmetic ops. <a href="#abddef937939ecbe4cff930c60b055176">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6277730d715a362deb5bd89ed0e17f53">expandFunnelShift</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand funnel shift. <a href="#a6277730d715a362deb5bd89ed0e17f53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdf8e533128a4e28f6720f70ab726376">expandROT</a> (SDNode *N, bool AllowVectorOps, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand rotations. <a href="#afdf8e533128a4e28f6720f70ab726376">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7c6044f8250efb3a9da26bcb6b1db62">expandShiftParts</a> (SDNode *N, SDValue &amp;Lo, SDValue &amp;Hi, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand shift-by-parts. <a href="#ad7c6044f8250efb3a9da26bcb6b1db62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88a98f9b6ef7661ed256aaaaea7455c">expandFP_TO_SINT</a> (SDNode *N, SDValue &amp;Result, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand float(f32) to SINT(i64) conversion. <a href="#ae88a98f9b6ef7661ed256aaaaea7455c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3bdbef1c14de11ac53ef2736000e900">expandFP_TO_UINT</a> (SDNode *N, SDValue &amp;Result, SDValue &amp;Chain, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand float to UINT conversion. <a href="#ac3bdbef1c14de11ac53ef2736000e900">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d9e993d1512edc0f76c3545a7730444">expandUINT_TO_FP</a> (SDNode *N, SDValue &amp;Result, SDValue &amp;Chain, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand UINT(i64) to double(f64) conversion. <a href="#a1d9e993d1512edc0f76c3545a7730444">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2615b4208115a17e0cc88dc5e7142ee9">expandFMINNUM_FMAXNUM</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand fminnum/fmaxnum into fminnum_ieee/fmaxnum_ieee with quieted inputs. <a href="#a2615b4208115a17e0cc88dc5e7142ee9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942902db44f41703d4055454e2b39332">expandFMINIMUM_FMAXIMUM</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand fminimum/fmaximum into multiple comparison with selects. <a href="#a942902db44f41703d4055454e2b39332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4b58e5ebed5507d40b5e4c0e5e5d19a">expandFMINIMUMNUM_FMAXIMUMNUM</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand fminimumnum/fmaximumnum into multiple comparison with selects. <a href="#ab4b58e5ebed5507d40b5e4c0e5e5d19a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a606e204a6a530a50176f469e79f23832">expandFP_TO_INT_SAT</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand FP_TO_[US]INT_SAT into FP_TO_[US]INT and selects or min/max. <a href="#a606e204a6a530a50176f469e79f23832">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a107eaea57b1ba73458df31dcd0d41c01">expandRoundInexactToOdd</a> (EVT ResultVT, SDValue Op, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Truncate <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> to ResultVT. <a href="#a107eaea57b1ba73458df31dcd0d41c01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077a3e5315f5c8e800b858c179a73f86">expandFP_ROUND</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand round(fp) to fp conversion. <a href="#a077a3e5315f5c8e800b858c179a73f86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada1945ca82da7a7861f21485db1994c9">expandIS_FPCLASS</a> (EVT ResultVT, SDValue Op, FPClassTest Test, SDNodeFlags Flags, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand check for floating point class. <a href="#ada1945ca82da7a7861f21485db1994c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fc0254299bd69d2edbd4bf7949292dc">expandCTPOP</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand CTPOP nodes. <a href="#a4fc0254299bd69d2edbd4bf7949292dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63399fefaac1b73b4c1a56c0c941004d">expandVPCTPOP</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand VP_CTPOP nodes. <a href="#a63399fefaac1b73b4c1a56c0c941004d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7fb5a0db40a7dbc4a0ac57bda71b893">expandCTLZ</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand CTLZ/CTLZ_ZERO_UNDEF nodes. <a href="#aa7fb5a0db40a7dbc4a0ac57bda71b893">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d7ed5e11454a58e268bc32c6794a26f">expandVPCTLZ</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand VP_CTLZ/VP_CTLZ_ZERO_UNDEF nodes. <a href="#a3d7ed5e11454a58e268bc32c6794a26f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ab2e1ac81721435d73f03617e59fc7">CTTZTableLookup</a> (SDNode *N, SelectionDAG &amp;DAG, const SDLoc &amp;DL, EVT VT, SDValue Op, unsigned NumBitsPerElt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand CTTZ via Table Lookup. <a href="#ae4ab2e1ac81721435d73f03617e59fc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3060b73c758e36617520472f85e8a66d">expandCTTZ</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand CTTZ/CTTZ_ZERO_UNDEF nodes. <a href="#a3060b73c758e36617520472f85e8a66d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7abea2a5b5251eb10473c9c610d6490">expandVPCTTZ</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand VP_CTTZ/VP_CTTZ_ZERO_UNDEF nodes. <a href="#ab7abea2a5b5251eb10473c9c610d6490">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f29c194ef5edad7c896b8b1ea1b3637">expandVPCTTZElements</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand VP_CTTZ_ELTS/VP_CTTZ_ELTS_ZERO_UNDEF nodes. <a href="#a6f29c194ef5edad7c896b8b1ea1b3637">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dfdb0c505a77dd707e9e9d4a439d656">expandVectorFindLastActive</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand VECTOR_FIND_LAST_ACTIVE nodes. <a href="#a5dfdb0c505a77dd707e9e9d4a439d656">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52e90a14f4d03b8959c096086b1bca73">expandABS</a> (SDNode *N, SelectionDAG &amp;DAG, bool IsNegative=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand ABS nodes. <a href="#a52e90a14f4d03b8959c096086b1bca73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010da65f0320c4a35d573ae07071b786">expandABD</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand ABDS/ABDU nodes. <a href="#a010da65f0320c4a35d573ae07071b786">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e0c74abf7ed800cb60f1bf840efe42">expandAVG</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand vector/scalar AVGCEILS/AVGCEILU/AVGFLOORS/AVGFLOORU nodes. <a href="#a39e0c74abf7ed800cb60f1bf840efe42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdc2ae0ea51276d42cf58621158bb7b6">expandBSWAP</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand BSWAP nodes. <a href="#afdc2ae0ea51276d42cf58621158bb7b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a249598a307c825ac80d22a45d863d3e4">expandVPBSWAP</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand VP_BSWAP nodes. <a href="#a249598a307c825ac80d22a45d863d3e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad103ae2c1e3a3e2451ea8ab5febf7075">expandBITREVERSE</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand BITREVERSE nodes. <a href="#ad103ae2c1e3a3e2451ea8ab5febf7075">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6a46c05752cd363e5c254403d30965">expandVPBITREVERSE</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand VP_BITREVERSE nodes. <a href="#afa6a46c05752cd363e5c254403d30965">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9335df3ffa4731120eb2ddc78c2b2eaa">scalarizeVectorLoad</a> (LoadSDNode *LD, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn load of vector type into a load of the individual elements. <a href="#a9335df3ffa4731120eb2ddc78c2b2eaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa226678963cfca06221c67886a7354f9">scalarizeVectorStore</a> (StoreSDNode *ST, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48eecfa931988559b1d70ad5b60b4511">expandUnalignedLoad</a> (LoadSDNode *LD, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands an unaligned load to 2 half-size loads for an integer, and possibly more for vectors. <a href="#a48eecfa931988559b1d70ad5b60b4511">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac0c36cc1d8c43244b007e09b5a221ae">expandUnalignedStore</a> (StoreSDNode *ST, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands an unaligned store to 2 half-size stores for integer values, and possibly more for vectors. <a href="#aac0c36cc1d8c43244b007e09b5a221ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b0bbe65dfcc05e091da9a4eec90d95">IncrementMemoryAddress</a> (SDValue Addr, SDValue Mask, const SDLoc &amp;DL, EVT DataVT, SelectionDAG &amp;DAG, bool IsCompressedMemory) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Increments memory address <span class="doxyComputerOutput">Addr</span> according to the type of the value <span class="doxyComputerOutput">DataVT</span> that should be stored. <a href="#a25b0bbe65dfcc05e091da9a4eec90d95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7600a96e79f99a6787e181c6168acbdc">getVectorElementPointer</a> (SelectionDAG &amp;DAG, SDValue VecPtr, EVT VecVT, SDValue Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to vector element <span class="doxyComputerOutput">Idx</span> located in memory for a vector of type <span class="doxyComputerOutput">VecVT</span> starting at a base address of <span class="doxyComputerOutput">VecPtr</span>. <a href="#a7600a96e79f99a6787e181c6168acbdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52585a36dd68f2eb54f278948b8013c5">getVectorSubVecPointer</a> (SelectionDAG &amp;DAG, SDValue VecPtr, EVT VecVT, EVT SubVecVT, SDValue Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to a sub-vector of type <span class="doxyComputerOutput">SubVecVT</span> at index <span class="doxyComputerOutput">Idx</span> located in memory for a vector of type <span class="doxyComputerOutput">VecVT</span> starting at a base address of <span class="doxyComputerOutput">VecPtr</span>. <a href="#a52585a36dd68f2eb54f278948b8013c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6940d92310c4c204d393e4049e6b4173">expandIntMINMAX</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US][MIN|MAX]. <a href="#a6940d92310c4c204d393e4049e6b4173">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcc11ebf4e4f4b44bd9bfb47b73ecaf5">expandAddSubSat</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US][ADD|SUB]SAT. <a href="#afcc11ebf4e4f4b44bd9bfb47b73ecaf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a2ce744686eaa8a78e89a0274802f0">expandCMP</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US]CMP. <a href="#a80a2ce744686eaa8a78e89a0274802f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25374963a6923b45451d8fae2fd7a841">expandShlSat</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US]SHLSAT. <a href="#a25374963a6923b45451d8fae2fd7a841">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a8a58df56ed203d8d45b4c79ea6baa2">expandFixedPointMul</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[U|S]MULFIX[SAT]. <a href="#a1a8a58df56ed203d8d45b4c79ea6baa2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec038c8a7d2972492d874496d2a02ad">expandFixedPointDiv</a> (unsigned Opcode, const SDLoc &amp;dl, SDValue LHS, SDValue RHS, unsigned Scale, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US]DIVFIX[SAT]. <a href="#a0ec038c8a7d2972492d874496d2a02ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d69e6a9860a2705c6d47e94028fbe1">expandUADDSUBO</a> (SDNode *Node, SDValue &amp;Result, SDValue &amp;Overflow, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method for building the DAG expansion of ISD::U(ADD|SUB)O. <a href="#a97d69e6a9860a2705c6d47e94028fbe1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0936c394ae9dcff8bf79032da7eb9472">expandSADDSUBO</a> (SDNode *Node, SDValue &amp;Result, SDValue &amp;Overflow, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method for building the DAG expansion of ISD::S(ADD|SUB)O. <a href="#a0936c394ae9dcff8bf79032da7eb9472">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79f607ce587b5b9f4ea493d88ba54845">expandMULO</a> (SDNode *Node, SDValue &amp;Result, SDValue &amp;Overflow, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US]MULO. <a href="#a79f607ce587b5b9f4ea493d88ba54845">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fc58a8c37cc23c116a72bc282fe9972">forceExpandMultiply</a> (SelectionDAG &amp;DAG, const SDLoc &amp;dl, bool Signed, SDValue &amp;Lo, SDValue &amp;Hi, SDValue LHS, SDValue RHS, SDValue HiLHS=SDValue(), SDValue HiRHS=SDValue()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the product twice the width of LHS and RHS. <a href="#a7fc58a8c37cc23c116a72bc282fe9972">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5693e1f9607ffe47618c90830bb5d919">forceExpandWideMUL</a> (SelectionDAG &amp;DAG, const SDLoc &amp;dl, bool Signed, const SDValue LHS, const SDValue RHS, SDValue &amp;Lo, SDValue &amp;Hi) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate full product of LHS and RHS either via a libcall or through brute force expansion of the multiplication. <a href="#a5693e1f9607ffe47618c90830bb5d919">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad70774809672f50432f4caba1d7c4018">expandVecReduce</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand a VECREDUCE_* into an explicit calculation. <a href="#ad70774809672f50432f4caba1d7c4018">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26774cf193c8fc0a6f65a22f1481c6cd">expandVecReduceSeq</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand a VECREDUCE_SEQ_* into an explicit ordered calculation. <a href="#a26774cf193c8fc0a6f65a22f1481c6cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83103b2084518ce8c8eaff7fa20c89e4">expandREM</a> (SDNode *Node, SDValue &amp;Result, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand an SREM or UREM using SDIV/UDIV or SDIVREM/UDIVREM, if legal. <a href="#a83103b2084518ce8c8eaff7fa20c89e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d282b6f6a3825d043eb576c1ab5553">expandVectorSplice</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad55a17543ef86f6d46aebb45028a9067">ISD::VECTOR_SPLICE</a>. <a href="#af0d282b6f6a3825d043eb576c1ab5553">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a367e029393fe61621674a8d22eddfbd9">expandVECTOR_COMPRESS</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand a vector VECTOR_COMPRESS into a sequence of extract element, store temporarily, advance store position, before re-loading the final vector. <a href="#a367e029393fe61621674a8d22eddfbd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28d371ce48274d70bac961a1000c6a9a">LegalizeSetCCCondCode</a> (SelectionDAG &amp;DAG, EVT VT, SDValue &amp;LHS, SDValue &amp;RHS, SDValue &amp;CC, SDValue Mask, SDValue EVL, bool &amp;NeedInvert, const SDLoc &amp;dl, SDValue &amp;Chain, bool IsSignaling=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize a SETCC or VP_SETCC with given LHS and RHS and condition code CC on the current target. <a href="#a28d371ce48274d70bac961a1000c6a9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca4f1936569be6534e77b709039afc21">EmitInstrWithCustomInserter</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag. <a href="#aca4f1936569be6534e77b709039afc21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb18ab539e6140e63924b8294e62bef">AdjustInstrPostInstrSelection</a> (MachineInstr &amp;MI, SDNode *Node) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'hasPostISelHook' flag. <a href="#a4fb18ab539e6140e63924b8294e62bef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b27b633b21a362571660ad09273d52">useLoadStackGuardNode</a> (const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this function returns true, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> emits a LOAD_STACK_GUARD node when it is lowering Intrinsic::stackprotector. <a href="#ad2b27b633b21a362571660ad09273d52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee0110a687cf5a9bdb9e8596d9ca3fb">emitStackGuardXorFP</a> (SelectionDAG &amp;DAG, SDValue Val, const SDLoc &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdea2f06c6c1098b324fa2e2a1b9b2f4">LowerToTLSEmulatedModel</a> (const GlobalAddressSDNode *GA, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower TLS global address <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> for target independent emulated TLS model. <a href="#afdea2f06c6c1098b324fa2e2a1b9b2f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad19715a9c62a6c91102ac12bbe18b63a">expandIndirectJTBranch</a> (const SDLoc &amp;dl, SDValue Value, SDValue Addr, int JTI, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands target specific indirect branch for the case of <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> expansion. <a href="#ad19715a9c62a6c91102ac12bbe18b63a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ad899ace945b24e3ef91384f4faeba">lowerCmpEqZeroToCtlzSrl</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeaa822c364e50b66ee8c683136934fd">isXAndYEqZeroPreferableToXAndYEqY</a> (ISD::CondCode, EVT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7cedb434f2206acccff18f3b653999b">expandVectorNaryOpBySplitting</a> (SDNode *Node, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7011ad40466921625b5f10b38753fb1">foldSetCCWithAnd</a> (EVT VT, SDValue N0, SDValue N1, ISD::CondCode Cond, const SDLoc &amp;DL, DAGCombinerInfo &amp;DCI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33b4592c3de00d9152cca06551702cf3">foldSetCCWithBinOp</a> (EVT VT, SDValue N0, SDValue N1, ISD::CondCode Cond, const SDLoc &amp;DL, DAGCombinerInfo &amp;DCI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6826180f440716b7cb16c9fafa1763">optimizeSetCCOfSignedTruncationCheck</a> (EVT SCCVT, SDValue N0, SDValue N1, ISD::CondCode Cond, DAGCombinerInfo &amp;DCI, const SDLoc &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc5cfd1ddb384da50e778223a24ef810">optimizeSetCCByHoistingAndByConstFromLogicalShift</a> (EVT SCCVT, SDValue N0, SDValue N1C, ISD::CondCode Cond, DAGCombinerInfo &amp;DCI, const SDLoc &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e5d2af01a293dc8faa840dc01c61791">prepareUREMEqFold</a> (EVT SETCCVT, SDValue REMNode, SDValue CompTargetNode, ISD::CondCode Cond, DAGCombinerInfo &amp;DCI, const SDLoc &amp;DL, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af35295204758d3ef527c98a8962de064">buildUREMEqFold</a> (EVT SETCCVT, SDValue REMNode, SDValue CompTargetNode, ISD::CondCode Cond, DAGCombinerInfo &amp;DCI, const SDLoc &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826160c1a7b93cbd109bcf90dc6f8a75">prepareSREMEqFold</a> (EVT SETCCVT, SDValue REMNode, SDValue CompTargetNode, ISD::CondCode Cond, DAGCombinerInfo &amp;DCI, const SDLoc &amp;DL, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d7a30d2401bc903b60de496f314601e">buildSREMEqFold</a> (EVT SETCCVT, SDValue REMNode, SDValue CompTargetNode, ISD::CondCode Cond, DAGCombinerInfo &amp;DCI, const SDLoc &amp;DL) const</td>
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

<p>This class defines information used to lower LLVM code to legal <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operators that the target instruction selector can accept natively.</p>


<p>This class also defines callbacks that targets must implement to lower target-specific constructs to <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operators.</p>


<p>Definition at line 3780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AsmOperandInfoVector {#a3db162658a7687e8a5df34f5a6aaa840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TargetLowering::AsmOperandInfoVector =  std::vector&lt;AsmOperandInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5008 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### ConstraintGroup {#a0c572d6810211a80e26729c2d3cb0a6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TargetLowering::ConstraintGroup =  SmallVector&lt;ConstraintPair&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### ConstraintPair {#a94865930eb23376a76409e18190f615d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TargetLowering::ConstraintPair =  std::pair&lt;StringRef, TargetLowering::ConstraintType&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5039 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ConstraintType {#a0b0176781cd4fd9f45cc739f1d007116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetLowering::ConstraintType </td>
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
<td class="doxyEnumItemName">C_Register<a id="a0b0176781cd4fd9f45cc739f1d007116a85f9b8131f0608c03c58e4e23d875dfc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_RegisterClass<a id="a0b0176781cd4fd9f45cc739f1d007116a1d7718fd43ac0a5c715686a76f9cfd89"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_Memory<a id="a0b0176781cd4fd9f45cc739f1d007116a420d729d2e7d056ec884c094ccdc4467"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_Address<a id="a0b0176781cd4fd9f45cc739f1d007116abd588753884964e239e61d80ebc2f039"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_Immediate<a id="a0b0176781cd4fd9f45cc739f1d007116a7bc0fe0fa6be5eaabb77e46c8d9ab2c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_Other<a id="a0b0176781cd4fd9f45cc739f1d007116abc9c279d343d2f957ab51b37ff39e88e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_Unknown<a id="a0b0176781cd4fd9f45cc739f1d007116ad4cd486b7360ed34c9553b6c9056b764"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 4950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### ConstraintWeight {#a7f5cab5437026605269663cda7389abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetLowering::ConstraintWeight </td>
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
<td class="doxyEnumItemName">CW_Invalid<a id="a7f5cab5437026605269663cda7389abca2a03cc05a305d0cd861ff2d070da40ca"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CW_Okay<a id="a7f5cab5437026605269663cda7389abcad2cf3d9c529f93c9afe82c16053bc0e3"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CW_Good<a id="a7f5cab5437026605269663cda7389abca69e2895d90783dc2ab3efe070397cbea"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CW_Better<a id="a7f5cab5437026605269663cda7389abca3054688f1464c0691ef2ef5e581276a8"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CW_Best<a id="a7f5cab5437026605269663cda7389abcaeadafdb6717a390cbe0c3ee93a0b1a2c"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CW_SpecificReg<a id="a7f5cab5437026605269663cda7389abca8f769b6cac1ebb4de9412ecfe92fe20d"></a></td>
<td class="doxyEnumItemDescription"> (= CW_Okay)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CW_Register<a id="a7f5cab5437026605269663cda7389abcaa36ab38b266c612487d9ff61df7475af"></a></td>
<td class="doxyEnumItemDescription"> (= CW_Good)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CW_Memory<a id="a7f5cab5437026605269663cda7389abca5b8290e7824d2be12d9886e17c7aedd6"></a></td>
<td class="doxyEnumItemDescription"> (= CW_Better)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CW_Constant<a id="a7f5cab5437026605269663cda7389abca632c68154579a54426d0841e490ddb40"></a></td>
<td class="doxyEnumItemDescription"> (= CW_Best)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CW_Default<a id="a7f5cab5437026605269663cda7389abcad4df0dd48c58dea43776a5a77e74ba76"></a></td>
<td class="doxyEnumItemDescription"> (= CW_Okay)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 4960 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TargetLowering() {#aaa96f111a59a7a2e7f9c689b344543df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetLowering::TargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;)</td>
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



<p>Definition at line 3785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="#aaa96f111a59a7a2e7f9c689b344543df">TargetLowering</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acf8f1219dc8b656e8e11c4b08edc8979">llvm::AArch64TargetLowering::AArch64TargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#abb9af8521eda1de8847a48e54ef33453">llvm::AMDGPUTargetLowering::AMDGPUTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/arctargetlowering/#aba7395bbd137a8b13d527f3279da8bf9">llvm::ARCTargetLowering::ARCTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa782c58995f9a6e00cf5a8500a9a8508">llvm::ARMTargetLowering::ARMTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#ac14830797eaee15361f1585a2126def2">llvm::AVRTargetLowering::AVRTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#a96722a41714a1c1b003e935c4e6c2133">llvm::BPFTargetLowering::BPFTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetlowering/#a394ec6c77b281252ab7d5dffb757ce7f">llvm::CSKYTargetLowering::CSKYTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/directxtargetlowering/#aa494cfe8b244c96538dcb6b31d7d61ad">llvm::DirectXTargetLowering::DirectXTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ab0f312a890f3aa47e480f40c67df30fe">llvm::HexagonTargetLowering::HexagonTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a6243792a40ae8baf41b2b216909a81ea">llvm::LanaiTargetLowering::LanaiTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ae88df257bb50084c96393d09161583e6">llvm::LoongArchTargetLowering::LoongArchTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6107db1593ae7bb4074d606368898747">llvm::NVPTXTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#ac0498ce2d07f3439f81c743d63348181">llvm::M68kTargetLowering::M68kTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a4baae7363a2379cc1714f47c6f0404aa">llvm::MipsTargetLowering::MipsTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a14766c6eac532550a66c5126b696fbaf">llvm::MSP430TargetLowering::MSP430TargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a33b621d73d340142fde30013311b9dd6">llvm::NVPTXTargetLowering::NVPTXTargetLowering</a>, <a href="#a876bc04d23f1888f4a807eefcc2fa2a7">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ac6cddb4c330de0e51a5977de243a3ded">llvm::PPCTargetLowering::PPCTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a190dd3c890042807e4008b5bdd04927a">llvm::RISCVTargetLowering::RISCVTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#aecea65c9daf59dcfdbeff434056d8a0c">llvm::SparcTargetLowering::SparcTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#af1351821179467af346577d6a3b481d1">llvm::SPIRVTargetLowering::SPIRVTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a805802990016512f5ad544f9afce1c1d">llvm::SystemZTargetLowering::SystemZTargetLowering</a>, <a href="#aaa96f111a59a7a2e7f9c689b344543df">TargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a4b0ef24ed3dd1e80dc7cabca3a07cb2b">llvm::VETargetLowering::VETargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetlowering/#a53bf53c283cb63c59df745398d515f45">llvm::WebAssemblyTargetLowering::WebAssemblyTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae9e81fca4b22706c50ad62e3241b6286">llvm::X86TargetLowering::X86TargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#ae577208e0dbd82f23fe240dda09a777d">llvm::XCoreTargetLowering::XCoreTargetLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#aba6b81d79ae2a26a70f9dedd4a21aee9">llvm::XtensaTargetLowering::XtensaTargetLowering</a>.</p>

</div>
</div>

### TargetLowering() {#a49680d92d476c9adc1452ca8e9948f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetLowering::TargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a876bc04d23f1888f4a807eefcc2fa2a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering &amp; llvm::TargetLowering::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;)</td>
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



<p>Definition at line 3786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="#aaa96f111a59a7a2e7f9c689b344543df">TargetLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AdjustInstrPostInstrSelection() {#a4fb18ab539e6140e63924b8294e62bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::AdjustInstrPostInstrSelection (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
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

<p>This method should be implemented by targets that mark instructions with the 'hasPostISelHook' flag.</p>


<p>These instructions must be adjusted after instruction selection by target hooks. e.g. To fill in optional defs for <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> 's' setting instructions.</p>


<p>Definition at line 5588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### buildLegalVectorShuffle() {#a696ff12171c8e0cf9f749fe7365ab40d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::buildLegalVectorShuffle (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N1, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to build a legal vector shuffle using the provided parameters or equivalent variations.</p>


<p>The Mask argument maybe be modified as the function tries different variations. Returns an empty <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if the operation fails.</p>


<p>Definition at line 4198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a670c95cba653503ce21f4abeea37cd2f">combineConcatVectorOfExtracts</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2c166ebb81953ce2aa531c18213e0011">reduceBuildVecToShuffleWithZero</a>.</p>

</div>
</div>

### BuildSDIV() {#a36c8f3817aaf6184163227ef33e08032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::BuildSDIV (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool IsAfterLegalization, bool IsAfterLegalTypes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### BuildSDIVPow2() {#a10e676263a198d8cd480918492893dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::BuildSDIVPow2 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Divisor, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
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

<p>Targets may override this function to provide custom SDIV lowering for power-of-2 denominators.</p>


<p>If the target returns an empty <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, LLVM assumes SDIV is expensive and replaces it with a series of other integer operations.</p>


<p>Definition at line 5116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### buildSDIVPow2WithCMov() {#ac059b1ca86f2540e9fcfbee0a0da1c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::buildSDIVPow2WithCMov (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Divisor, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### BuildSREMPow2() {#abe774a33e51c905a23e19b7b9803e8eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::BuildSREMPow2 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Divisor, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
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

<p>Targets may override this function to provide custom SREM lowering for power-of-2 denominators.</p>


<p>If the target returns an empty <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, LLVM assumes SREM is expensive and replaces it with a series of other integer operations.</p>


<p>Definition at line 5124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### BuildUDIV() {#a634e703cb950d5425ce8594ea59ef3bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::BuildUDIV (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool IsAfterLegalization, bool IsAfterLegalTypes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### canCreateUndefOrPoisonForTargetNode() {#a690ecd418854c4f2bea36d278c8cb7a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::canCreateUndefOrPoisonForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool PoisonOnly, bool ConsiderFlags, unsigned Depth)</td>
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

<p>Return true if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> can create undef or poison from non-undef &amp; non-poison operands.</p>


<p>The DemandedElts argument limits the check to the requested vector elements.</p>


<p>Definition at line 4190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a4346f62e0e1ee37b8c7877df168057f5aaa2fad9a8387f8d5f005f3e308ae676f">PoisonOnly</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ad04d835131d2859ce803f7f5a33e5c04">llvm::RISCVTargetLowering::canCreateUndefOrPoisonForTargetNode</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af2d807474cb0bf45eccd77f335159b8f">llvm::X86TargetLowering::canCreateUndefOrPoisonForTargetNode</a>.</p>

</div>
</div>

### CanLowerReturn() {#afc21228b6db4542de1339af252b2a725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::CanLowerReturn (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
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

<p>This hook should be implemented to check whether the return values described by the Outs array can fit into the return registers.</p>


<p>If false is returned, an sret-demotion is performed.</p>


<p>Definition at line 4781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### checkForPhysRegDependency() {#ade4fa73063019f286fb23ac86df8839e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::checkForPhysRegDependency (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * User, unsigned Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, unsigned &amp; PhysReg, int &amp; Cost)</td>
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

<p>Allows the target to handle physreg-carried dependency in target-specific way.</p>


<p>Used from the <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes">ScheduleDAGSDNodes</a> to decide whether to add the edge to the dependency graph. Def - input: Selection DAG node defininfg physical register <a href="/web-llvm/docs/api/classes/llvm/user">User</a> - input: Selection DAG node using physical register <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> - input: Number of <a href="/web-llvm/docs/api/classes/llvm/user">User</a> operand PhysReg - inout: set to the physical register if the edge is necessary, unchanged otherwise <a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> - inout: physical register copy cost. Returns 'true' is the edge is necessary, 'false' otherwise</p>


<p>Definition at line 4490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a7d574da13bc65b93810a42059eada04f">CheckForPhysRegDependency</a>.</p>

</div>
</div>

### CollectTargetIntrinsicOperands() {#a79bdddcacb7e2e24a0ba20714b80c18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::CollectTargetIntrinsicOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Definition at line 5093 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### combineRepeatedFPDivisors() {#ad540ba702458038e9dfc70c04d4286ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetLowering::combineRepeatedFPDivisors ()</td>
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

<p>Indicate whether this target prefers to combine FDIVs with the same divisor.</p>


<p>If the transform should never be done, return zero. If the transform should be done, return the minimum number of divisor uses that must exist.</p>


<p>Definition at line 5132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### ComputeConstraintToUse() {#a279a7f92d056886ac713c0f06cc73045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::ComputeConstraintToUse (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; OpInfo, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * DAG=nullptr)</td>
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

<p>Determines the constraint code and constraint type to use for the specific <a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a>, setting OpInfo.ConstraintCode and OpInfo.ConstraintType.</p>


<p>If the actual operand being passed in is available, it can be passed in as <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>, otherwise an empty <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> can be passed.</p>


<p>Definition at line 5032 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a86026627b644e50527898aad0747b3e5">IsOperandAMemoryOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a10799c8833054017c6ab052c8b9c1aa2">llvm::SITargetLowering::requiresUniformRegister</a>.</p>

</div>
</div>

### computeKnownAlignForTargetInstr() {#ae917d897ff4613b4cfdc9cd4dadade41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Align llvm::TargetLowering::computeKnownAlignForTargetInstr (<a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> &amp; Analysis, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, unsigned Depth=0)</td>
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

<p>Determine the known alignment for the pointer value <span class="doxyComputerOutput">R</span>.</p>


<p>This is can typically be inferred from the number of low known 0 bits. However, for a pointer with a non-integral address space, the alignment value may be independent from the known low bits.</p>


<p>Definition at line 4120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### computeKnownBitsForFrameIndex() {#a89837a1ae285b93a15adff98bbb21efb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::computeKnownBitsForFrameIndex (int FIOp, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Determine which of the bits of FrameIndex <span class="doxyComputerOutput">FIOp</span> are known to be 0.</p>


<p>Default implementation computes low bits based on alignment information. This should preserve known bits passed into it.</p>


<p>Definition at line 4128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a59eb700f7620c6a3ebbdc281bc00d3bd">llvm::SITargetLowering::computeKnownBitsForFrameIndex</a>.</p>

</div>
</div>

### computeKnownBitsForTargetInstr() {#af7b6795985b3405f69339661de5d860c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::computeKnownBitsForTargetInstr (<a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> &amp; Analysis, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, unsigned Depth=0)</td>
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

<p>Determine which of the bits specified in Mask are known to be either zero or one and return them in the KnownZero/KnownOne bitsets.</p>


<p>The DemandedElts argument allows us to only collect the known bits that are shared by the requested vector elements. This is for GISel.</p>


<p>Definition at line 4110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### computeKnownBitsForTargetNode() {#a8c00d269d51235a7579e37163eeb3edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::computeKnownBitsForTargetNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth=0)</td>
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

<p>Determine which of the bits specified in Mask are known to be either zero or one and return them in the KnownZero/KnownOne bitsets.</p>


<p>The DemandedElts argument allows us to only collect the known bits that are shared by the requested vector elements.</p>


<p>Definition at line 4100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>

</div>
</div>

### computeNumSignBitsForTargetInstr() {#a9b359fbfa123fbf333095817e902cf0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetLowering::computeNumSignBitsForTargetInstr (<a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> &amp; Analysis, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, unsigned Depth=0)</td>
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

<p>This method can be implemented by targets that want to expose additional information about sign bits to GlobalISel combiners.</p>


<p>The DemandedElts argument allows us to only collect the minimum sign bits that are shared by the requested vector elements.</p>


<p>Definition at line 4145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### ComputeNumSignBitsForTargetNode() {#a6e478aced9c847bcb02f8a94e498c2e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetLowering::ComputeNumSignBitsForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth=0)</td>
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

<p>This method can be implemented by targets that want to expose additional information about sign bits to the DAG <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a>.</p>


<p>The DemandedElts argument allows us to only collect the minimum sign bits that are shared by the requested vector elements.</p>


<p>Definition at line 4136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>

</div>
</div>

### createFastISel() {#adb05aefedc1e93f32b6061a23542d508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual FastISel * llvm::TargetLowering::createFastISel (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *)</td>
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

<p>This method returns a target specific <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> object, or null if the target does not support "fast" ISel.</p>

<p>Definition at line 4925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### createSelectForFMINNUM\_FMAXNUM() {#afb677d589b9b39e03a0f38a86411ad3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::createSelectForFMINNUM_FMAXNUM (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to convert the fminnum/fmaxnum to a compare/select sequence.</p>


<p>This is required for correctness since InstCombine might have canonicalized a fcmp+select sequence to a FMINNUM/FMAXNUM intrinsic. If we were to fall through to the default expansion/soften to libcall, we might introduce a link-time dependency on libm into a file that originally did not have one.</p>


<p>Definition at line 5165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### CTTZTableLookup() {#ae4ab2e1ac81721435d73f03617e59fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::CTTZTableLookup (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, unsigned NumBitsPerElt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand CTTZ via Table Lookup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### EmitInstrWithCustomInserter() {#aca4f1936569be6534e77b709039afc21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineBasicBlock * llvm::TargetLowering::EmitInstrWithCustomInserter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag.</p>


<p>These instructions are special in various ways, which require special support to insert. The specified <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> is created but not inserted into any basic blocks, and this method is called to expand it into a sequence of instructions, potentially also creating new basic blocks and control flow. As long as the returned basic block is different (i.e., we created a new one), the custom inserter is free to modify the rest of <span class="doxyComputerOutput">MBB</span>.</p>


<p>Definition at line 5582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a3098f3c7fe942574303f81224b526094">llvm::R600TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/finalizeisel-cpp/#a6395b072c4fb781dca4789de8aba1f55">runImpl</a>.</p>

</div>
</div>

### emitStackGuardXorFP() {#a1ee0110a687cf5a9bdb9e8596d9ca3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::emitStackGuardXorFP (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
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



<p>Definition at line 5595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### expandABD() {#a010da65f0320c4a35d573ae07071b786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandABD (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand ABDS/ABDU nodes.</p>


<p>Expands vector/scalar ABDS/ABDU nodes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandABS() {#a52e90a14f4d03b8959c096086b1bca73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandABS (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool IsNegative=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand ABS nodes.</p>


<p>Expands vector/scalar ABS nodes, vector nodes can only succeed if all operations are legal/custom. (ABS x) -&gt; (XOR (ADD x, (SRA x, type_size)), (SRA x, type_size))</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsNegative</td>
<td class="doxyParamItemDescription"><p>indicate negated abs</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandAddSubSat() {#afcc11ebf4e4f4b44bd9bfb47b73ecaf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandAddSubSat (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US][ADD|SUB]SAT.</p>


<p>This method accepts integers as its arguments.</p>


<p>Definition at line 5469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>.</p>

</div>
</div>

### expandAVG() {#a39e0c74abf7ed800cb60f1bf840efe42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandAVG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand vector/scalar AVGCEILS/AVGCEILU/AVGFLOORS/AVGFLOORU nodes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandBITREVERSE() {#ad103ae2c1e3a3e2451ea8ab5febf7075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandBITREVERSE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand BITREVERSE nodes.</p>


<p>Expands scalar/vector BITREVERSE nodes. Returns SDValue() if expand fails.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandBSWAP() {#afdc2ae0ea51276d42cf58621158bb7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandBSWAP (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand BSWAP nodes.</p>


<p>Expands scalar/vector BSWAP nodes with i16/i32/i64 scalar types. Returns SDValue() if expand fails.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandCMP() {#a80a2ce744686eaa8a78e89a0274802f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandCMP (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US]CMP.</p>


<p>This method accepts integers as its arguments</p>


<p>Definition at line 5473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandCTLZ() {#aa7fb5a0db40a7dbc4a0ac57bda71b893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandCTLZ (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand CTLZ/CTLZ_ZERO_UNDEF nodes.</p>


<p>Expands vector/scalar CTLZ nodes, vector nodes can only succeed if all operations are legal/custom.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandCTPOP() {#a4fc0254299bd69d2edbd4bf7949292dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandCTPOP (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand CTPOP nodes.</p>


<p>Expands vector/scalar CTPOP nodes, vector nodes can only succeed if all operations are legal/custom.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandCTTZ() {#a3060b73c758e36617520472f85e8a66d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandCTTZ (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand CTTZ/CTTZ_ZERO_UNDEF nodes.</p>


<p>Expands vector/scalar CTTZ nodes, vector nodes can only succeed if all operations are legal/custom.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandDIVREMByConstant() {#abddef937939ecbe4cff930c60b055176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::expandDIVREMByConstant (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Result, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> HiLoVT, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LL=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>(), <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LH=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to expand an n-bit div/rem/divrem by constant using a n/2-bit urem by constant and other arithmetic ops.</p>


<p>The n/2-bit urem by constant will be expanded by DAGCombiner. This is not possible for all constant divisors.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>A vector that will be filled with the lo and high parts of the results. For *DIVREM, this will be the quotient parts followed by the remainder parts.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HiLoVT</td>
<td class="doxyParamItemDescription"><p>The value type to use for the Lo and Hi parts. Should be half of VT.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LL</td>
<td class="doxyParamItemDescription"><p>Low bits of the LHS of the operation. You can use this parameter if you want to control how low bits are extracted from the LHS.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LH</td>
<td class="doxyParamItemDescription"><p>High bits of the LHS of the operation. See LL for meaning.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the node has been expanded, false if it has not.</p></dd>
</dl>


<p>Definition at line 5245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandFixedPointDiv() {#a0ec038c8a7d2972492d874496d2a02ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandFixedPointDiv (unsigned Opcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, unsigned Scale, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US]DIVFIX[SAT].</p>


<p>This method accepts integers as its arguments. Note: This method may fail if the division could not be performed within the type. Clients must retry with a wider type if this happens.</p>


<p>Definition at line 5487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizeintegertypes-cpp/#a296983d97d1ba11410248b9965b244e8">earlyExpandDIVFIX</a>.</p>

</div>
</div>

### expandFixedPointMul() {#a1a8a58df56ed203d8d45b4c79ea6baa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandFixedPointMul (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[U|S]MULFIX[SAT].</p>


<p>This method accepts integers as its arguments.</p>


<p>Definition at line 5481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandFMINIMUM\_FMAXIMUM() {#a942902db44f41703d4055454e2b39332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandFMINIMUM_FMAXIMUM (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand fminimum/fmaximum into multiple comparison with selects.</p>

<p>Definition at line 5295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandFMINIMUMNUM\_FMAXIMUMNUM() {#ab4b58e5ebed5507d40b5e4c0e5e5d19a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandFMINIMUMNUM_FMAXIMUMNUM (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand fminimumnum/fmaximumnum into multiple comparison with selects.</p>

<p>Definition at line 5298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandFMINNUM\_FMAXNUM() {#a2615b4208115a17e0cc88dc5e7142ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandFMINNUM_FMAXNUM (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand fminnum/fmaxnum into fminnum_ieee/fmaxnum_ieee with quieted inputs.</p>

<p>Definition at line 5292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandFP\_ROUND() {#a077a3e5315f5c8e800b858c179a73f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandFP_ROUND (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand round(fp) to fp conversion.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result</p></dd>
</dl>


<p>Definition at line 5316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandFP\_TO\_INT\_SAT() {#a606e204a6a530a50176f469e79f23832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandFP_TO_INT_SAT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand FP_TO_[US]INT_SAT into FP_TO_[US]INT and selects or min/max.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result</p></dd>
</dl>


<p>Definition at line 5303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandFP\_TO\_SINT() {#ae88a98f9b6ef7661ed256aaaaea7455c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::expandFP_TO_SINT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand float(f32) to SINT(i64) conversion.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>output after conversion</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True, if the expansion was successful, false otherwise</p></dd>
</dl>


<p>Definition at line 5273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#aa52bac1dc0a8f251721e5702c4f81a50">llvm::R600TargetLowering::ReplaceNodeResults</a>.</p>

</div>
</div>

### expandFP\_TO\_UINT() {#ac3bdbef1c14de11ac53ef2736000e900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::expandFP_TO_UINT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand float to UINT conversion.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>output after conversion</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Chain</td>
<td class="doxyParamItemDescription"><p>output chain after conversion</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True, if the expansion was successful, false otherwise</p></dd>
</dl>


<p>Definition at line 5280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandFunnelShift() {#a6277730d715a362deb5bd89ed0e17f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandFunnelShift (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand funnel shift.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion if successful, SDValue() otherwise</p></dd>
</dl>


<p>Definition at line 5253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandIndirectJTBranch() {#ad19715a9c62a6c91102ac12bbe18b63a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::expandIndirectJTBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Value, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, int JTI, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Expands target specific indirect branch for the case of <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> expansion.</p>

<p>Definition at line 5606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adb745982e84f05a0d48b878d998d47c7">llvm::RISCVTargetLowering::expandIndirectJTBranch</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adfbecc9eaa3da520aafda5f3078baf3f">llvm::X86TargetLowering::expandIndirectJTBranch</a>.</p>

</div>
</div>

### ExpandInlineAsm() {#aa394506e609b72337e9c664ef264db8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::ExpandInlineAsm (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *)</td>
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

<p>This hook allows the target to expand an inline asm call to be explicit llvm code if it wants to.</p>


<p>This is useful for turning simple inline asms into LLVM intrinsics, which gives the compiler more information about the behavior of the code.</p>


<p>Definition at line 4946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandIntMINMAX() {#a6940d92310c4c204d393e4049e6b4173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandIntMINMAX (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US][MIN|MAX].</p>


<p>This method accepts integers as its arguments.</p>


<p>Definition at line 5465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandIS\_FPCLASS() {#ada1945ca82da7a7861f21485db1994c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandIS_FPCLASS (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ResultVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> Test, <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a> Flags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand check for floating point class.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ResultVT</td>
<td class="doxyParamItemDescription"><p>The type of intrinsic call result.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6"&gt;Op&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The tested value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Test</td>
<td class="doxyParamItemDescription"><p>The test to perform.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>The optimization flags.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aec7c967a5416fa6e154433965357a50ea0cbc6611f5540bd0809a388dc95a615b">llvm::Test</a>.</p>

</div>
</div>

### expandMUL() {#ab707d083b764fa474237a76bc4b05694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::expandMUL (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Lo, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Hi, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> HiLoVT, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aff813db965c76a7e0f64c426cded6534">MulExpansionKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LL=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>(), <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LH=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>(), <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RL=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>(), <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RH=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand a MUL into two nodes.</p>


<p>One that computes the high bits of the result and one that computes the low bits.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">HiLoVT</td>
<td class="doxyParamItemDescription"><p>The value type to use for the Lo and Hi nodes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LL</td>
<td class="doxyParamItemDescription"><p>Low bits of the LHS of the MUL. You can use this parameter if you want to control how low bits are extracted from the LHS.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LH</td>
<td class="doxyParamItemDescription"><p>High bits of the LHS of the MUL. See LL for meaning.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RL</td>
<td class="doxyParamItemDescription"><p>Low bits of the RHS of the MUL. See LL for meaning</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RH</td>
<td class="doxyParamItemDescription"><p>High bits of the RHS of the MUL. See LL for meaning.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the node has been expanded. false if it has not</p></dd>
</dl>


<p>Definition at line 5225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandMUL\_LOHI() {#ac7581f7a7740ac3c1dc73fd7aeeccc63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::expandMUL_LOHI (unsigned Opcode, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Result, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> HiLoVT, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aff813db965c76a7e0f64c426cded6534">MulExpansionKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LL=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>(), <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LH=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>(), <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RL=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>(), <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RH=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand a MUL or [US]MUL_LOHI of n-bit values into two or four nodes, respectively, each computing an n/2-bit part of the result.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>A vector that will be filled with the parts of the result in little-endian order.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LL</td>
<td class="doxyParamItemDescription"><p>Low bits of the LHS of the MUL. You can use this parameter if you want to control how low bits are extracted from the LHS.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LH</td>
<td class="doxyParamItemDescription"><p>High bits of the LHS of the MUL. See LL for meaning.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RL</td>
<td class="doxyParamItemDescription"><p>Low bits of the RHS of the MUL. See LL for meaning</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RH</td>
<td class="doxyParamItemDescription"><p>High bits of the RHS of the MUL. See LL for meaning.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the node has been expanded, false if it has not</p></dd>
</dl>


<p>Definition at line 5210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### expandMULO() {#a79f607ce587b5b9f4ea493d88ba54845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::expandMULO (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Overflow, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US]MULO.</p>


<p>Returns whether expansion was successful and populates the Result and Overflow arguments.</p>


<p>Definition at line 5503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandREM() {#a83103b2084518ce8c8eaff7fa20c89e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::expandREM (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand an SREM or UREM using SDIV/UDIV or SDIVREM/UDIVREM, if legal.</p>


<p>Returns true if the expansion was successful.</p>


<p>Definition at line 5532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandROT() {#afdf8e533128a4e28f6720f70ab726376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandROT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, bool AllowVectorOps, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand rotations.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllowVectorOps</td>
<td class="doxyParamItemDescription"><p>expand vector rotate, this should only be performed if the legalization is happening outside of LegalizeVectorOps</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion if successful, SDValue() otherwise</p></dd>
</dl>


<p>Definition at line 5260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandRoundInexactToOdd() {#a107eaea57b1ba73458df31dcd0d41c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandRoundInexactToOdd (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ResultVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Truncate <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> to ResultVT.</p>


<p>If the result is exact, leave it alone. If it is not exact, force the result to be odd.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ResultVT</td>
<td class="doxyParamItemDescription"><p>The type of result.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6"&gt;Op&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The value to round.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result</p></dd>
</dl>


<p>Definition at line 5310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### expandSADDSUBO() {#a0936c394ae9dcff8bf79032da7eb9472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLowering::expandSADDSUBO (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Overflow, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method for building the DAG expansion of ISD::S(ADD|SUB)O.</p>


<p>Expansion always suceeds and populates the Result and Overflow arguments.</p>


<p>Definition at line 5498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandShiftParts() {#ad7c6044f8250efb3a9da26bcb6b1db62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLowering::expandShiftParts (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Lo, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Hi, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand shift-by-parts.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Lo</td>
<td class="doxyParamItemDescription"><p>lower-output-part after conversion</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Hi</td>
<td class="doxyParamItemDescription"><p>upper-output-part after conversion</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 5266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a63812eb1fe4e44df46b0b789597a8b5f">LowerShiftParts</a>.</p>

</div>
</div>

### expandShlSat() {#a25374963a6923b45451d8fae2fd7a841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandShlSat (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::[US]SHLSAT.</p>


<p>This method accepts integers as its arguments.</p>


<p>Definition at line 5477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandUADDSUBO() {#a97d69e6a9860a2705c6d47e94028fbe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLowering::expandUADDSUBO (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Overflow, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method for building the DAG expansion of ISD::U(ADD|SUB)O.</p>


<p>Expansion always suceeds and populates the Result and Overflow arguments.</p>


<p>Definition at line 5493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandUINT\_TO\_FP() {#a1d9e993d1512edc0f76c3545a7730444}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::expandUINT_TO_FP (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand UINT(i64) to double(f64) conversion.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>output after conversion</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Chain</td>
<td class="doxyParamItemDescription"><p>output chain after conversion</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True, if the expansion was successful, false otherwise</p></dd>
</dl>


<p>Definition at line 5288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandUnalignedLoad() {#a48eecfa931988559b1d70ad5b60b4511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; llvm::TargetLowering::expandUnalignedLoad (<a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> * LD, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expands an unaligned load to 2 half-size loads for an integer, and possibly more for vectors.</p>

<p>Definition at line 5430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a39595844bf818c3700df1bd898912dcb">llvm::HexagonTargetLowering::LowerUnalignedLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>.</p>

</div>
</div>

### expandUnalignedStore() {#aac0c36cc1d8c43244b007e09b5a221ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandUnalignedStore (<a href="/web-llvm/docs/api/classes/llvm/storesdnode">StoreSDNode</a> * ST, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expands an unaligned store to 2 half-size stores for integer values, and possibly more for vectors.</p>

<p>Definition at line 5435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a946850e76d96e9deaab8c5053a86f02b">llvm::HexagonTargetLowering::LowerStore</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>.</p>

</div>
</div>

### expandVecReduce() {#ad70774809672f50432f4caba1d7c4018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVecReduce (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand a VECREDUCE_* into an explicit calculation.</p>


<p>If Count is specified, only the first Count elements of the vector are used.</p>


<p>Definition at line 5525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandVecReduceSeq() {#a26774cf193c8fc0a6f65a22f1481c6cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVecReduceSeq (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand a VECREDUCE_SEQ_* into an explicit ordered calculation.</p>

<p>Definition at line 5528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandVECTOR\_COMPRESS() {#a367e029393fe61621674a8d22eddfbd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVECTOR_COMPRESS (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand a vector VECTOR_COMPRESS into a sequence of extract element, store temporarily, advance store position, before re-loading the final vector.</p>

<p>Definition at line 5540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandVectorFindLastActive() {#a5dfdb0c505a77dd707e9e9d4a439d656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVectorFindLastActive (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand VECTOR_FIND_LAST_ACTIVE nodes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandVectorNaryOpBySplitting() {#ab7cedb434f2206acccff18f3b653999b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVectorNaryOpBySplitting (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### expandVectorSplice() {#af0d282b6f6a3825d043eb576c1ab5553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVectorSplice (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method for building the DAG expansion of <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad55a17543ef86f6d46aebb45028a9067">ISD::VECTOR_SPLICE</a>.</p>


<p>This method accepts vectors as its arguments.</p>


<p>Definition at line 5536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### expandVPBITREVERSE() {#afa6a46c05752cd363e5c254403d30965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVPBITREVERSE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand VP_BITREVERSE nodes.</p>


<p>Expands VP_BITREVERSE nodes with i8/i16/i32/i64 scalar types.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandVPBSWAP() {#a249598a307c825ac80d22a45d863d3e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVPBSWAP (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand VP_BSWAP nodes.</p>


<p>Expands VP_BSWAP nodes with i16/i32/i64 scalar types. Returns SDValue() if expand fails.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandVPCTLZ() {#a3d7ed5e11454a58e268bc32c6794a26f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVPCTLZ (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand VP_CTLZ/VP_CTLZ_ZERO_UNDEF nodes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandVPCTPOP() {#a63399fefaac1b73b4c1a56c0c941004d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVPCTPOP (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand VP_CTPOP nodes.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandVPCTTZ() {#ab7abea2a5b5251eb10473c9c610d6490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVPCTTZ (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand VP_CTTZ/VP_CTTZ_ZERO_UNDEF nodes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### expandVPCTTZElements() {#a6f29c194ef5edad7c896b8b1ea1b3637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::expandVPCTTZElements (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand VP_CTTZ_ELTS/VP_CTTZ_ELTS_ZERO_UNDEF nodes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The expansion result or SDValue() if it fails.</p></dd>
</dl>


<p>Definition at line 5369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### findOptimalMemOpLowering() {#a60e48d09cc181b603b17d4e385cc4bb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::findOptimalMemOpLowering (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> &gt; &amp; MemOps, unsigned Limit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memop">MemOp</a> &amp; Op, unsigned DstAS, unsigned SrcAS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp; FuncAttributes)</td>
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

<p>Determines the optimal series of memory ops to replace the memset / memcpy.</p>


<p>Return true if the number of memory ops is below the threshold (Limit). Note that this is always the case when Limit is ~0. It returns the types of the sequence of memory ops to perform memset / memcpy by reference.</p>


<p>Definition at line 3973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a4b3e491ab48bb3f6160f0745f08ce61a">llvm::SystemZTargetLowering::findOptimalMemOpLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>.</p>

</div>
</div>

### forceExpandMultiply() {#a7fc58a8c37cc23c116a72bc282fe9972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLowering::forceExpandMultiply (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, bool Signed, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Lo, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Hi, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> HiLHS=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>(), <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> HiRHS=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the product twice the width of LHS and RHS.</p>


<p>If HiLHS/HiRHS are non-null they will be included in the multiplication. The expansion works by splitting the 2 inputs into 4 pieces that we can multiply and add together without neding MULH or MUL_LOHI.</p>


<p>Definition at line 5510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>

</div>
</div>

### forceExpandWideMUL() {#a5693e1f9607ffe47618c90830bb5d919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLowering::forceExpandWideMUL (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, bool Signed, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Lo, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Hi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate full product of LHS and RHS either via a libcall or through brute force expansion of the multiplication.</p>


<p>The expansion works by splitting the 2 inputs into 4 pieces that we can multiply and add together without needing MULH or MUL_LOHI.</p>


<p>Definition at line 5519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>

</div>
</div>

### functionArgumentNeedsConsecutiveRegisters() {#ac9df75d2d0cb54ed147aaf46cd2b1e84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::functionArgumentNeedsConsecutiveRegisters (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>For some targets, an LLVM struct type must be broken down into multiple simple types, but the calling convention specifies that the entire struct must be passed in a block of consecutive registers.</p>

<p>Definition at line 4842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### getCheaperNegatedExpression() {#a48fe15bdf777438d3ff912a613650642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::getCheaperNegatedExpression (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool LegalOps, bool OptForSize, unsigned Depth=0)</td>
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

<p>This is the helper function to return the newly negated expression only when the cost is cheaper.</p>

<p>Definition at line 4452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84a4691542279fb918ac8c43619d77aefdf">llvm::TargetLoweringBase::Cheaper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="#a2f1e2f811ae9139b9543751585239443">getCheaperOrNeutralNegatedExpression</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8dae5a29dc37de048a59e5bab5e30af2">combineFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0f13d1cf96cb32fba6d7ed4bd50ba5f">combineFMADDSUB</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a402c372a2886c19770de2cc65b41a7e0">llvm::X86TargetLowering::getNegatedExpression</a>.</p>

</div>
</div>

### getCheaperOrNeutralNegatedExpression() {#a2f1e2f811ae9139b9543751585239443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::getCheaperOrNeutralNegatedExpression (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool LegalOps, bool OptForSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84">NegatibleCost</a> CostThreshold=<a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84ae9bb5320b3890b6747c91b5a71ae5a01">NegatibleCost::Neutral</a>, unsigned Depth=0)</td>
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



<p>Definition at line 4431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dfajumpthreading-cpp/#aa7c006860d37cf6192a6339a35743888">CostThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84a920c5f62b372ce8ed1056422a02c356a">llvm::TargetLoweringBase::Expensive</a>, <a href="#aea3e575b3cff4eb444567d50959b929c">getNegatedExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84ae9bb5320b3890b6747c91b5a71ae5a01">llvm::TargetLoweringBase::Neutral</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a935ace76cef67c6da10cf0633371efe1">llvm::SelectionDAG::RemoveDeadNode</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7d150e94e3cd7f6681fa07ea2b72da14">llvm::SDNode::use_empty</a>.</p>


<p>Referenced by <a href="#a48fe15bdf777438d3ff912a613650642">getCheaperNegatedExpression</a>.</p>

</div>
</div>

### getConstraintPreferences() {#a09429106263aff7968fde2119706fd42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstraintGroup llvm::TargetLowering::getConstraintPreferences (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; OpInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an OpInfo with list of constraints codes as strings, return a sorted Vector of pairs of constraint codes and their types in priority of what we'd prefer to lower them as.</p>


<p>This may contain immediates that cannot be lowered, but it is meant to be a machine agnostic order of preferences.</p>


<p>Definition at line 5046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#ace43e7f4b3e0e3d46309ffaf8eb07208">computeConstraintToUse</a>.</p>

</div>
</div>

### getConstraintType() {#a45b2deb637d370d68d3bd3786c21e415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ConstraintType llvm::TargetLowering::getConstraintType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint)</td>
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

<p>Given a constraint, return the type of constraint it is for this target.</p>

<p>Definition at line 5037 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#ace43e7f4b3e0e3d46309ffaf8eb07208">computeConstraintToUse</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a367c0fd240000e247269dee3f2db8d7f">llvm::ARMTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a36633fb5c5538d177823d2dbe18458a6">llvm::AVRTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#a00fc80b3fa328fbe28fd9c3e7c336049">llvm::BPFTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a1fe5332b6f233790067eae16a9f88847">llvm::HexagonTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#a0d3c5019618fbdd5dbe8f321aa4e9967">llvm::M68kTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#addbf547ea90bdc1d1e496461455cdc06">llvm::MSP430TargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a0aaad9f7863f88d9aed611bf5f1c92a5">llvm::NVPTXTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a97e1f4e021dcba5a7795f823781e04df">llvm::PPCTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aca527d26f925265f5d193625eeb7bf0c">llvm::RISCVTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4cc2e446c8b94f69ff81fd22efc5d630">llvm::SITargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a2c5a958743bc5a86564032ba9a3aaa58">llvm::SparcTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a9701afa66d8ab97582acbffe33ca3e96">llvm::SystemZTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#afa53b350dc3624841e65fbb4a7011e91">llvm::VETargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a370d811aff2e392f420421995d439701">llvm::X86TargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a4f4aafb669c7b8966f8d921d0c8970ba">llvm::XtensaTargetLowering::getConstraintType</a> and <a href="/web-llvm/docs/api/classes/anonymous-selectiondagbuilder-cpp-/sdiselasmoperandinfo/#a4720526a8ca364f5afe46d3fd069c108">anonymous{SelectionDAGBuilder.cpp}::SDISelAsmOperandInfo::hasMemory</a>.</p>

</div>
</div>

### getInlineAsmMemConstraint() {#a3acbc2d34d9a6d35b63a04f0ae20136c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual InlineAsm::ConstraintCode llvm::TargetLowering::getInlineAsmMemConstraint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ConstraintCode)</td>
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



<p>Definition at line 5062 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a6f8f57715090da2632453988d9a1501b">llvm::InlineAsm::m</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0ad95679752134a2d9eb61dbd7b91c4bcc">llvm::InlineAsm::o</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a83878c91171338902e0fe0fb97a8c47a">llvm::InlineAsm::p</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::InlineAsm::Unknown</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a02129bb861061d1a052c592e2dc6b383">llvm::InlineAsm::X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a2543fc561fd405e07d0d993a7854b34f">llvm::ARMTargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a5c640d443e4dc001255da9b55a167301">llvm::AVRTargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#ac6c58901e3cf6a8800abd157924a0166">llvm::M68kTargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a73a300242af50ce9daeda4a2e002df27">llvm::PPCTargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a12fc0d82abf1a7842d4295464c88a4e8">llvm::RISCVTargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac00b359e5af562d4db70ff852b38a7e">llvm::SystemZTargetLowering::getInlineAsmMemConstraint</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a3ba8881f3b3a742488705f0d17bb2db5">llvm::X86TargetLowering::getInlineAsmMemConstraint</a>.</p>

</div>
</div>

### getJumpTableEncoding() {#aded686370215fda472fa7b38ccbba458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetLowering::getJumpTableEncoding ()</td>
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

<p>Return the entry encoding for a jump table in the current function.</p>


<p>The returned value is a member of the <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3">MachineJumpTableInfo::JTEntryKind</a> enum.</p>


<p>Definition at line 3855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a76ee5e788bf1969bd98f670b3471a12b">llvm::PPCTargetLowering::getJumpTableEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a64f329924a93b193a9c728cd90f581cf">llvm::RISCVTargetLowering::getJumpTableEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ae09ccbff702238ba328e645205aadfad">llvm::VETargetLowering::getJumpTableEncoding</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a14ba729e50c70d2bff3f12c884209140">llvm::X86TargetLowering::getJumpTableEncoding</a>.</p>

</div>
</div>

### getJumpTableRegTy() {#af2c7c474fbd3717354a6297baa84a478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MVT llvm::TargetLowering::getJumpTableRegTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 3857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ac85aa2ebc935e3c87ec7f9e54183cddf">llvm::SelectionDAGBuilder::visitJumpTableHeader</a>.</p>

</div>
</div>

### getMultipleConstraintMatchWeight() {#a242f3e03f104dc030614c21db016e206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ConstraintWeight llvm::TargetLowering::getMultipleConstraintMatchWeight (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; info, int maIndex)</td>
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

<p>Examine constraint type and operand type and determine a weight value.</p>


<p>The operand object must already have been set up with the operand type.</p>


<p>Definition at line 5020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>.</p>

</div>
</div>

### getNegatedExpression() {#aea3e575b3cff4eb444567d50959b929c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::getNegatedExpression (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool LegalOps, bool OptForSize, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84">NegatibleCost</a> &amp; Cost, unsigned Depth=0)</td>
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

<p>Return the newly negated expression if the cost is not expensive and set the cost in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a></span> to indicate that if it is cheaper or neutral to do the negation.</p>

<p>Definition at line 4426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7a388b8e71542c8223c73a0d99691c71">combineFneg</a>, <a href="#a2f1e2f811ae9139b9543751585239443">getCheaperOrNeutralNegatedExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aaea9e6e5e0dec58e46e4ffe57898fb90">llvm::AMDGPUTargetLowering::getNegatedExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2fd734bb5606f5c8bd7bd6ef49683e1e">llvm::PPCTargetLowering::getNegatedExpression</a>, <a href="#a235b6c220471b5f4e283c7ed685e0005">getNegatedExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a402c372a2886c19770de2cc65b41a7e0">llvm::X86TargetLowering::getNegatedExpression</a>.</p>

</div>
</div>

### getNegatedExpression() {#a235b6c220471b5f4e283c7ed685e0005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::getNegatedExpression (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool LegalOps, bool OptForSize, unsigned Depth=0)</td>
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

<p>This is the helper function to return the newly negated expression if the cost is not expensive.</p>

<p>Definition at line 4461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84a920c5f62b372ce8ed1056422a02c356a">llvm::TargetLoweringBase::Expensive</a> and <a href="#aea3e575b3cff4eb444567d50959b929c">getNegatedExpression</a>.</p>

</div>
</div>

### getPICJumpTableRelocBase() {#ab4681990679f127bf757790e59678f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::getPICJumpTableRelocBase (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Table, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Returns relocation base for the given PIC jumptable.</p>

<p>Definition at line 3869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a64ca42c56843a34b11476e34d5941628">llvm::PPCTargetLowering::getPICJumpTableRelocBase</a>.</p>

</div>
</div>

### getPICJumpTableRelocBaseExpr() {#a993d38cd5b37a6ee0c9c3cb24ada5392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MCExpr * llvm::TargetLowering::getPICJumpTableRelocBaseExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, unsigned JTI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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

<p>This returns the relocation base for the given PIC jumptable, the same as getPICJumpTableRelocBase, but as an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a>.</p>

<p>Definition at line 3875 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af5e6261283ef663e0a0c083aede97931">llvm::AsmPrinter::getCodeViewJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a9e8d81b42a228a0a2e89454cf7a3d017">llvm::PPCTargetLowering::getPICJumpTableRelocBaseExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a424abc19654b712885d63747e7f5b4db">llvm::X86TargetLowering::getPICJumpTableRelocBaseExpr</a>.</p>

</div>
</div>

### getPostIndexedAddressParts() {#ac01f44d948268acd41c5994ea6cc1369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::getPostIndexedAddressParts (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31">ISD::MemIndexedMode</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
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

<p>Returns true by value, base pointer and offset pointer and addressing mode by reference if this node can be combined with a load / store to form a post-indexed load / store.</p>

<p>Definition at line 3837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac6c9b791cef5925e123539fb2934316b">shouldCombineToPostInc</a>.</p>

</div>
</div>

### getPreIndexedAddressParts() {#ad9d63fccccfc98800dc7c8bb11356e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::getPreIndexedAddressParts (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31">ISD::MemIndexedMode</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
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

<p>Returns true by value, base pointer and offset pointer and addressing mode by reference if the node's address can be legally represented as pre-indexed load / store address.</p>

<p>Definition at line 3827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### getRecipEstimate() {#aa4e4a07bf2d469f04b430edb380ee1b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::getRecipEstimate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int Enabled, int &amp; RefinementSteps)</td>
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

<p>Return a reciprocal estimate value for the input operand.</p>


<p><span class="doxyComputerOutput">Enabled</span> is a <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33f">ReciprocalEstimate</a> enum with value either 'Unspecified' or 'Enabled' as set by a potential default override attribute. If <span class="doxyComputerOutput">RefinementSteps</span> is 'Unspecified', the number of Newton-Raphson refinement iterations required to generate a sufficient (though not necessarily IEEE-754 compliant) estimate is returned in that parameter. A target may choose to implement its own refinement within this function. If that's true, then return '0' as the number of RefinementSteps to avoid any further refinement of the estimate. An empty <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> return means no estimate sequence can be created.</p>


<p>Definition at line 5177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33fa8e243db2e3806dcf4997c408a355ddfc">llvm::TargetLoweringBase::Enabled</a>.</p>

</div>
</div>

### getRegForInlineAsmConstraint() {#af09507c47dcb4cdb2a13064aaa6d5243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::pair&lt; unsigned, const TargetRegisterClass * &gt; llvm::TargetLowering::getRegForInlineAsmConstraint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
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

<p>Given a physical register constraint (e.g.</p>


<p>{edx}), return the register number and the register class for the register.</p>


<p>Given a register class constraint, like 'r', if this corresponds directly to an LLVM register class, return a register of 0 and the register class pointer.</p>


<p>This should only be used for C_Register constraints. On error, this returns a register number of 0 and a null register class pointer.</p>


<p>Definition at line 5058 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ae36dfcf0bacb4009b75fb2323aba6869">llvm::ARMTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a27c6ef6dacc842737370d22c1f7ed946">llvm::AVRTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#aeb5e73aa86ef5c3747a4fa348274ad20">llvm::BPFTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ad1de76d884688c0714045295511132af">llvm::HexagonTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#af08f3cc8369f10594ea18265dde0cab7">llvm::LanaiTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#afd1e3e4aa43dd55aaf713d32f108a3de">llvm::M68kTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a17109faa1b23afe706771effb725d9fb">llvm::MSP430TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ab18a78c277667a151b0cb707c7e80a02">llvm::NVPTXTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#add923d3128dce4cad95ce5ad642f6946">llvm::PPCTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7ade77bdee8e8fe0f6694d0ef8fda0ad">llvm::RISCVTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a299e5debf3d108b71fc6642ecd31e5e7">llvm::SparcTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a8b056a961f0931f4e64f0bddf07ba784">llvm::SystemZTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a04b839fdbef86703e2716838602c37aa">llvm::VETargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a7a7237cd5cb35f9159b32a96f4b14541">llvm::X86TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ae09e10149c0fdd82a96ee9252d48354f">llvm::XtensaTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#a43762e6a22fd0e7b98b8115946fc87b6">getRegistersForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#aa2b5a0a0f6bf1b5480337a01257df8b6">getRegistersForValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a5ec1b0ffb0fbbbc5d74381b0b1d38ae1">patchMatchingInput</a>.</p>

</div>
</div>

### getRegisterByName() {#a349007dec8d5a6ab5e7d338c282003ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Register llvm::TargetLowering::getRegisterByName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RegName, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Return the register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the name passed in.</p>


<p>Used by named register global variables extension. There is no target-independent behaviour so the default action is to bail.</p>


<p>Definition at line 4821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getRoundingControlRegisters() {#ac62b35c70e62f4a9d4c3e9117de615e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ArrayRef&lt; MCPhysReg &gt; llvm::TargetLowering::getRoundingControlRegisters ()</td>
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

<p>Returns a 0 terminated array of rounding control registers that can be attached into strict FP call.</p>

<p>Definition at line 4865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### getScratchRegisters() {#ad87e9267a35f4fd6e8e3b66910ac5dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MCPhysReg * llvm::TargetLowering::getScratchRegisters (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
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

<p>Returns a 0 terminated array of registers that can be safely used as scratch registers.</p>

<p>Definition at line 4859 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>.</p>

</div>
</div>

### getSingleConstraintMatchWeight() {#afaa66a325b7b8c5c79eb2c8e9822ffd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ConstraintWeight llvm::TargetLowering::getSingleConstraintMatchWeight (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * constraint)</td>
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

<p>Examine constraint string and operand type and determine a weight value.</p>


<p>The operand object must already have been set up with the operand type.</p>


<p>Definition at line 5025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0f12063b62264c753e65abb8e9ff29d8">llvm::ARMTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a7bab53d05e5532f9b9d89f3427b1c5e7">llvm::AVRTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#ab747ced2e4628cb6b97736ba02902c7d">llvm::LanaiTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a685bfe474ca920468f17fc82cf4664e6">llvm::PPCTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a237a27aeef06752d11d7ab1dc1560239">llvm::SparcTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a900def112d7e109823a5bb89a3c01dd8">llvm::SystemZTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ac437e7230f2990fd60bf089f20ea2e78">llvm::X86TargetLowering::getSingleConstraintMatchWeight</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a1050308e21901d5abbab72e0d6e1423a">llvm::XtensaTargetLowering::getSingleConstraintMatchWeight</a>.</p>

</div>
</div>

### getSqrtEstimate() {#a0f5c79ba78f8b97824689ec83267d746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::getSqrtEstimate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int Enabled, int &amp; RefinementSteps, bool &amp; UseOneConstNR, bool Reciprocal)</td>
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

<p>Hooks for building estimates in place of slower divisions and square roots.</p>


<p>Return either a square root or its reciprocal estimate value for the input operand. <span class="doxyComputerOutput">Enabled</span> is a <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33f">ReciprocalEstimate</a> enum with value either 'Unspecified' or 'Enabled' as set by a potential default override attribute. If <span class="doxyComputerOutput">RefinementSteps</span> is 'Unspecified', the number of Newton-Raphson refinement iterations required to generate a sufficient (though not necessarily IEEE-754 compliant) estimate is returned in that parameter. The boolean UseOneConstNR output is used to select a Newton-Raphson algorithm implementation that uses either one or two constants. The boolean Reciprocal is used to select whether the estimate is for the square root of the input operand or the reciprocal of its square root. A target may choose to implement its own refinement within this function. If that's true, then return '0' as the number of RefinementSteps to avoid any further refinement of the estimate. An empty <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> return means no estimate sequence can be created.</p>


<p>Definition at line 5154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33fa8e243db2e3806dcf4997c408a355ddfc">llvm::TargetLoweringBase::Enabled</a>.</p>

</div>
</div>

### getSqrtInputTest() {#a89e60908750fd1cca69d96e7aa41ba5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::getSqrtInputTest (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> &amp; Mode)</td>
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

<p>Return a target-dependent comparison result if the input operand is suitable for use with a square root estimate calculation.</p>


<p>For example, the comparison may check if the operand is NAN, INF, zero, normal, etc. The result should be used as the condition operand for a select or branch.</p>


<p>Definition at line 5186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>.</p>

</div>
</div>

### getSqrtResultForDenormInput() {#abd1a92af13465b269b22fb6b1cddffaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::getSqrtResultForDenormInput (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Return a target-dependent result if the input operand is not suitable for use with a square root estimate calculation.</p>

<p>Definition at line 5191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a354aae224911d4dab66e34bfa10cf5d6">llvm::SelectionDAG::getConstantFP</a> and <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>.</p>

</div>
</div>

### getTargetConstantFromLoad() {#a18b2f46b93af4466b33909730c2b2e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const Constant * llvm::TargetLowering::getTargetConstantFromLoad (<a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> * LD)</td>
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

<p>This method returns the constant pool value that will be loaded by LD.</p>


<p>NOTE: You must check for implicit extensions of the constant by LD.</p>


<p>Definition at line 4204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### getTargetNodeName() {#aa07a74d942f49b11a81baf6dba21726e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const char * llvm::TargetLowering::getTargetNodeName (unsigned Opcode)</td>
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

<p>This method returns the name of a target specific DAG node.</p>

<p>Definition at line 4921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a59192c42d4cbf804fbcc1deff8edb614">llvm::SDNode::getOperationName</a>.</p>

</div>
</div>

### getTypeForExtReturn() {#a2b10a312e4ab7eb05f1b88f6e5eb8e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual EVT llvm::TargetLowering::getTypeForExtReturn (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a>)</td>
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

<p>Return the type that should be used to zero or sign extend a zeroext/signext integer return value.</p>


<p>FIXME: Some C calling conventions require the return type to be promoted, but this is not true all the time, e.g. i1/i8/i16 on x86/x86_64. It is also not necessary for non-C calling conventions. The frontend should handle this and include all of the necessary information.</p>


<p>Definition at line 4832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a3bf257bfbd279ecfad670be03b00210e">llvm::EVT::bitsLT</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af344c6bd2d070c999525df85be7688cf">llvm::TargetLoweringBase::getRegisterType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a175f10e8ec1c2ec4fa24431ac5429a36">llvm::GetReturnInfo</a>.</p>

</div>
</div>

### getVectorElementPointer() {#a7600a96e79f99a6787e181c6168acbdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::getVectorElementPointer (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> VecPtr, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VecVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to vector element <span class="doxyComputerOutput">Idx</span> located in memory for a vector of type <span class="doxyComputerOutput">VecVT</span> starting at a base address of <span class="doxyComputerOutput">VecPtr</span>.</p>


<p>If <span class="doxyComputerOutput">Idx</span> is out of bounds the returned pointer is unspecified, but will be within the vector bounds.</p>


<p>Definition at line 5452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa9fca969da56000134dc248f8d676e3a">combineExtractFromVectorLoad</a>.</p>

</div>
</div>

### getVectorSubVecPointer() {#a52585a36dd68f2eb54f278948b8013c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::getVectorSubVecPointer (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> VecPtr, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VecVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SubVecVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to a sub-vector of type <span class="doxyComputerOutput">SubVecVT</span> at index <span class="doxyComputerOutput">Idx</span> located in memory for a vector of type <span class="doxyComputerOutput">VecVT</span> starting at a base address of <span class="doxyComputerOutput">VecPtr</span>.</p>


<p>If <span class="doxyComputerOutput">Idx</span> plus the size of <span class="doxyComputerOutput">SubVecVT</span> is out of bounds the returned pointer is unspecified, but the value returned will be such that the entire subvector would be within the vector bounds.</p>


<p>Definition at line 5460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### HandleByVal() {#ad7c36d5b8de34e8f925d02cc2c4000e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::HandleByVal (<a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> *, unsigned &amp;, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>)</td>
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

<p>Target-specific cleanup for formal ByVal parameters.</p>

<p>Definition at line 4776 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### IncrementMemoryAddress() {#a25b0bbe65dfcc05e091da9a4eec90d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::IncrementMemoryAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Mask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DataVT, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool IsCompressedMemory)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Increments memory address <span class="doxyComputerOutput">Addr</span> according to the type of the value <span class="doxyComputerOutput">DataVT</span> that should be stored.</p>


<p>If the data is stored in compressed form, the memory address should be incremented according to the number of the stored elements. This number is equal to the number of '1's bits in the <span class="doxyComputerOutput">Mask</span>. <span class="doxyComputerOutput">DataVT</span> is a vector type. <span class="doxyComputerOutput">Mask</span> is a vector value. <span class="doxyComputerOutput">DataVT</span> and <span class="doxyComputerOutput">Mask</span> have the same number of vector elements.</p>


<p>Definition at line 5444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### initializeSplitCSR() {#aa15229fc1a15ce3693166d66a0994334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::initializeSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Entry)</td>
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

<p>Perform necessary initialization to handle a subset of CSRs explicitly via copies.</p>


<p>This function is called at the beginning of instruction selection.</p>


<p>Definition at line 4409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### insertCopiesSplitCSR() {#a73bf38dbdcdff5a2befaff46205f3541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::insertCopiesSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Entry, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Exits)</td>
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

<p>Insert explicit copies in entry and exit blocks.</p>


<p>We copy a subset of CSRs to virtual registers in the entry block, and copy them back to physical registers in the exit blocks. This function is called at the end of instruction selection.</p>


<p>Definition at line 4417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isConstFalseVal() {#a485c321d878ce722bb8d19a4b9d81657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::isConstFalseVal (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return if the N is a constant or constant vector equal to the false value from <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a79adbcc34e24b86ef8a216a34ccf5af8">getBooleanContents()</a>.</p>

<p>Definition at line 4261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isConstTrueVal() {#a49086baced6151325ba4b88ecdd5383f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::isConstTrueVal (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return if the N is a constant or constant vector equal to the true value from <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a79adbcc34e24b86ef8a216a34ccf5af8">getBooleanContents()</a>.</p>

<p>Definition at line 4257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1399030f41bb48286cffbbfddb29a3f">PerformXORCombine</a>.</p>

</div>
</div>

### isDesirableToCombineLogicOpOfSETCC() {#ad79ec6f151d15fbecd05a6d0c47c3729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual AndOrSETCCFoldKind llvm::TargetLowering::isDesirableToCombineLogicOpOfSETCC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * LogicOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * SETCC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * SETCC1)</td>
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



<p>Definition at line 4351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac14a71b7c36f34100de107aadccc5578af13d639dc869a95fce88b087dc66856e">llvm::TargetLoweringBase::None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>.</p>

</div>
</div>

### isDesirableToCommuteWithShift() {#acadf633df07f9e11330ae99edf3e1bb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isDesirableToCommuteWithShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7a">CombineLevel</a> Level)</td>
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

<p>Return true if it is profitable to move this shift by a constant amount through its operand, adjusting any immediate operands as necessary to preserve semantics.</p>


<p>This transformation may not be desirable if it disrupts a particularly auspicious target-specific tree (e.g. bitfield extraction in <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a>). By default, it returns true.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p>the shift node</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>the current DAGCombine legalization level.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 4303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a295d0b84f4e63438c0edb0021c41d47a">llvm::SDNode::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>.</p>

</div>
</div>

### isDesirableToCommuteWithShift() {#a10338eadd129baf2b64756673c1ea883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isDesirableToCommuteWithShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool IsAfterLegal)</td>
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

<p>GlobalISel - return true if it is profitable to move this shift by a constant amount through its operand, adjusting any immediate operands as necessary to preserve semantics.</p>


<p>This transformation may not be desirable if it disrupts a particularly auspicious target-specific tree (e.g. bitfield extraction in <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a>). By default, it returns true.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MI</td>
<td class="doxyParamItemDescription"><p>the shift instruction</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsAfterLegal</td>
<td class="doxyParamItemDescription"><p>true if running after legalization.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 4322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isDesirableToCommuteXorWithShift() {#aaa536ba062854f0951a19b7457665c96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isDesirableToCommuteXorWithShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Return true if it is profitable to combine an XOR of a logical shift to create a logical shift of NOT.</p>


<p>This transformation may not be desirable if it disrupts a particularly auspicious target-specific tree (e.g. BIC on ARM/AArch64). By default, it returns true.</p>


<p>Definition at line 4360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### IsDesirableToPromoteOp() {#a67dd43e2dfeed538828a0028fef372d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::IsDesirableToPromoteOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> &amp;)</td>
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

<p>This method query the target whether it is beneficial for dag combiner to promote the specified node.</p>


<p>If true, it should return the desired promotion type by reference.</p>


<p>Definition at line 4384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### isDesirableToPullExtFromShl() {#a8f691332d3b84bef71821427b0c676dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isDesirableToPullExtFromShl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>GlobalISel - return true if it's profitable to perform the combine: shl ([sza]ext x), y =&gt; zext (shl x, y)</p>

<p>Definition at line 4329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isDesirableToTransformToIntegerOp() {#aff7c382c626528004a59c365a2bc7e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isDesirableToTransformToIntegerOp (unsigned, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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

<p>Return true if it is profitable for dag combiner to transform a floating point op of specified opcode to a equivalent op of an integer type.</p>


<p>e.g. f32 load -&gt; i32 load can be profitable on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>.</p>


<p>Definition at line 4376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### isExtendedTrueVal() {#a2dc906a01997a28f62fd05f6470d7dd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::isExtendedTrueVal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, bool SExt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return if <span class="doxyComputerOutput">N</span> is a True value when extended to <span class="doxyComputerOutput">VT</span>.</p>

<p>Definition at line 4264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isGAPlusOffset() {#abe66a168970ddd74cce6fbc9a40589c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isGAPlusOffset (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *&amp; GA, int64_t &amp; Offset)</td>
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

<p>Returns true (and the <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> and the offset) if the node is a GlobalAddress + offset.</p>

<p>Definition at line 4278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a7d9494014ff9dbd992928542dee2e477">isConsecutiveLSLoc</a>.</p>

</div>
</div>

### isGuaranteedNotToBeUndefOrPoisonForTargetNode() {#abb1ad8b21c9956ffb90121e24f8bc116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isGuaranteedNotToBeUndefOrPoisonForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool PoisonOnly, unsigned Depth)</td>
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

<p>Return true if this function can prove that <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is never poison and, if <span class="doxyComputerOutput">PoisonOnly</span> is false, does not have undef bits.</p>


<p>The DemandedElts argument limits the check to the requested vector elements.</p>


<p>Definition at line 4182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a4346f62e0e1ee37b8c7877df168057f5aaa2fad9a8387f8d5f005f3e308ae676f">PoisonOnly</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae2cb6bf0817b8dbe415405c7498b8ce7">llvm::X86TargetLowering::isGuaranteedNotToBeUndefOrPoisonForTargetNode</a>.</p>

</div>
</div>

### isIndexingLegal() {#a97f597434d447bcc927007f32b35d3d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isIndexingLegal (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Base, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Offset, bool IsPre, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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

<p>Returns true if the specified base+offset is a legal indexed addressing mode for this target.</p>


<p><span class="doxyComputerOutput">MI</span> is the load or store instruction that is being considered for transformation.</p>


<p>Definition at line 3848 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### isInlineAsmTargetBranch() {#aebfdd629d9e82d02230d041fadfa540c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isInlineAsmTargetBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; AsmStrs, unsigned OpNo)</td>
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

<p>On x86, return true if the operand with index OpNo is a CALL or JUMP instruction, which can use either a memory constraint or an address constraint.</p>


<p>-fasm-blocks "__asm call foo" lowers to call void asm sideeffect inteldialect "call ${0:P}", "*m..."</p>


<p>This function is used by a hack to choose the address constraint, lowering to a direct call.</p>


<p>Definition at line 3890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### isInTailCallPosition() {#a6e6f8d5c56365fe5e9a6e4f9581ddb94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::isInTailCallPosition (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### isKnownNeverNaNForTargetNode() {#a3a1d4426a85849e75f56ef9d3b13fecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isKnownNeverNaNForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool SNaN=false, unsigned Depth=0)</td>
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

<p>If <span class="doxyComputerOutput">SNaN</span> is false,.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is known to never be any NaN. If <span class="doxyComputerOutput">sNaN</span> is true, returns if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is known to never be a signaling NaN.</p></dd>
</dl>


<p>Definition at line 4209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>

</div>
</div>

### isOffsetFoldingLegal() {#a74dabfbe18cbb61e4a1935eb1bf4942b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isOffsetFoldingLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * GA)</td>
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

<p>Return true if folding a constant offset with the given GlobalAddress is legal.</p>


<p>It is frequently not legal in PIC relocation models.</p>


<p>Definition at line 3880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### isPositionIndependent() {#aa8ab0804ddb40450da6549e1943817a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::isPositionIndependent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a8c0a6f5ad327c20349f2a2e0a5845b3e">llvm::MipsTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a056f22c11083630d8bcc82299cb783af">llvm::PPCTargetLowering::emitEHSjLjLongJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a64f329924a93b193a9c728cd90f581cf">llvm::RISCVTargetLowering::getJumpTableEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ae09ccbff702238ba328e645205aadfad">llvm::VETargetLowering::getJumpTableEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a14ba729e50c70d2bff3f12c884209140">llvm::X86TargetLowering::getJumpTableEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a1f130fccfd94dc59362cfcd4d1a4f6d8">llvm::VETargetLowering::getPICJumpTableRelocBase</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad1a79970217e7be886648d06d5fded3c">llvm::X86TargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a5098d901f0c198948883d51adc575bcf">llvm::HexagonTargetLowering::LowerConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a3857be1416dafbc76e2e00df1cb1fc74">llvm::RISCVTargetLowering::LowerCustomJumpTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ad81befa82353e9ee9e205edffbe77d4e">llvm::VETargetLowering::LowerCustomJumpTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af3e16079a117749c3a3ab03753982e0e">llvm::X86TargetLowering::LowerCustomJumpTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#afba4c90a08e96da7d4339f8af8d9f390">llvm::VETargetLowering::lowerINTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a695aaa8a3d818788b6c4ea4375527154">llvm::HexagonTargetLowering::LowerJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#afe0e23691695d8248375255976aa5aaf">llvm::VETargetLowering::lowerToTLSGeneralDynamicModel</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a521a7e7403f755b2fc9fccd869eb4ed8">llvm::HexagonTargetLowering::LowerToTLSInitialExecModel</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a8c1423d81607a5548a57bf11a3ab447c">llvm::SparcTargetLowering::makeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaa7a460999303677345922560c5db47e">llvm::VETargetLowering::makeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a7bb08436f2b077eb1cd53997a9d9b2b2">llvm::VETargetLowering::prepareMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ab997f379e36469df72be3d7c59f17d2a">llvm::VETargetLowering::prepareSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a>.</p>

</div>
</div>

### isReassocProfitable() {#a2aa7972a9fb95298bb1f59cf65ec46e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isReassocProfitable (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N1)</td>
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



<p>Definition at line 3804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a342c0d4e8e59b30daefe9a05bc2098bd">llvm::SDValue::hasOneUse</a>.</p>

</div>
</div>

### isReassocProfitable() {#ae21fd7066178a309d6f89521e1ceb247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isReassocProfitable (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> N0, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> N1)</td>
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



<p>Definition at line 3815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isSDNodeAlwaysUniform() {#aa67e0a840aaf40e6406d7be705f44af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isSDNodeAlwaysUniform (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Definition at line 3820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isSDNodeSourceOfDivergence() {#aa17502133164c96bd0943f2241171ead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isSDNodeSourceOfDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> * FLI, <a href="/web-llvm/docs/api/namespaces/llvm/#a00a2f5a62b5d5d5b6b0e143c4d30041f">UniformityInfo</a> * UA)</td>
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



<p>Definition at line 3792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isSplatValueForTargetNode() {#aa31fb5c8038b82f00b3a1d19144c0516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isSplatValueForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth=0)</td>
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

<p>Return true if vector <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> has the same value across all <span class="doxyComputerOutput">DemandedElts</span>, indicating any elements which may be undef in the output <span class="doxyComputerOutput">UndefElts</span>.</p>

<p>Definition at line 4216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a34faa94759387be0a4881a7e227f6caf">llvm::X86TargetLowering::isSplatValueForTargetNode</a>.</p>

</div>
</div>

### isTargetCanonicalConstantNode() {#a4568c6fee399b92f6971aa10266a89b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isTargetCanonicalConstantNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
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

<p>Returns true if the given Opc is considered a canonical constant for the target, which should not be transformed back into a BUILD_VECTOR.</p>

<p>Definition at line 4223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">llvm::ISD::SPLAT_VECTOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad358f0823a936bde7edd419ab1058bd4">llvm::ISD::SPLAT_VECTOR_PARTS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a1f8c7f0a720b2569599c36794b5ef80d">llvm::HexagonTargetLowering::isTargetCanonicalConstantNode</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad0914ba5d0ef25eca489b81cbf981517">llvm::X86TargetLowering::isTargetCanonicalConstantNode</a>.</p>

</div>
</div>

### isTypeDesirableForOp() {#a7c66bde62e1fbe747611b8d385ad6c9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isTypeDesirableForOp (unsigned, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if the target has native support for the specified value type and it is 'desirable' to use the type for the given node type.</p>


<p>e.g. On x86 i16 is legal, but undesirable since i16 instruction encodings are longer and some i16 instructions are slow.</p>


<p>Definition at line 4368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a98bf352a29693de3c4292f15ee698d79">foldToSaturated</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a7a4450c23fda81ec84bce1eed78f67d4">llvm::AArch64TargetLowering::isTypeDesirableForOp</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a00c85693fe30c4ddff7e08b2d84ca7df">llvm::SITargetLowering::isTypeDesirableForOp</a>.</p>

</div>
</div>

### isUsedByReturnOnly() {#a138a6e09184eae2d1d412cd4e8d60e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isUsedByReturnOnly (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;)</td>
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

<p>Return true if result of the specified node is used by a return node only.</p>


<p>It also compute and return the input chain for the tail call.</p>


<p>This is used to determine whether it is possible to codegen a libcall as tail call at legalization time.</p>


<p>Definition at line 4807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### isXAndYEqZeroPreferableToXAndYEqY() {#afeaa822c364e50b66ee8c683136934fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::isXAndYEqZeroPreferableToXAndYEqY (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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



<p>Definition at line 5617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### joinRegisterPartsIntoValue() {#a7271d32a363f6f4c4d632f1bf4986b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::joinRegisterPartsIntoValue (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * Parts, unsigned NumParts, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> PartVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ValueVT, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> &gt; CC)</td>
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

<p>Target-specific combining of register parts into its original value.</p>

<p>Definition at line 4499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#acb8cf9e50c3979193572ea36f327d0a4">getCopyFromParts</a>.</p>

</div>
</div>

### LegalizeSetCCCondCode() {#a28d371ce48274d70bac961a1000c6a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::LegalizeSetCCCondCode (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; CC, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Mask, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> EVL, bool &amp; NeedInvert, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, bool IsSignaling=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize a SETCC or VP_SETCC with given LHS and RHS and condition code CC on the current target.</p>


<p>A VP_SETCC will additionally be given a Mask and/or EVL not equal to SDValue().</p>


<p>If the SETCC has been legalized using AND / OR, then the legalized node will be stored in LHS. RHS and CC will be set to SDValue(). NeedInvert will be set to false. This will also hold if the VP_SETCC has been legalized using VP_AND / VP_OR.</p>


<p>If the SETCC / VP_SETCC has been legalized by using getSetCCSwappedOperands(), then the values of LHS and RHS will be swapped, CC will be set to the new condition, and NeedInvert will be set to false.</p>


<p>If the SETCC / VP_SETCC has been legalized using the inverse condcode, then LHS and RHS will be unchanged, CC will set to the inverted condcode, and NeedInvert will be set to true. The caller must invert the result of the SETCC with <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afd9ac842f542adb5aec80d8141f91b68">SelectionDAG::getLogicalNOT()</a> or take equivalent action to swap the effect of a true/false result.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the SETCC / VP_SETCC has been legalized, false if it hasn't.</p></dd>
</dl>


<p>Definition at line 5564 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### LowerAsmOperandForConstraint() {#ad3f2eb78e627fd0d785fd4119d299558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::LowerAsmOperandForConstraint (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Lower the specified operand into the Ops vector.</p>


<p>If it is invalid, don't add anything to Ops.</p>


<p>Definition at line 5081 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#adb4ff7051f9fd7cfa91a1b20be1ac880">llvm::ARMTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#ac81e19ad39432150ba023a5d0d4a9d03">llvm::AVRTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#acb1a5b7cd343c725179259bb749f4257">llvm::LanaiTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#a12a4baec6fb389a927821d9ae85bb75e">llvm::M68kTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6e231b2a711b732f0508170edd8d6492">llvm::NVPTXTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a46ae06ee635d7e06d852c36093a4d20e">llvm::PPCTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac77a28c2acd753d94ba0342ebccb58a7">llvm::RISCVTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a6bb4374ad909cee64af61c8e6859fc8f">llvm::SITargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af4eec9eb2d2c80156afb3788f2361f14">llvm::SparcTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#acacf32699b860563db81e48146e1efe5">llvm::SystemZTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af8cc1f957026a793e58fec505e47a7c5">llvm::X86TargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ade4062a36853bbacfea3d28b1ae76bf5">llvm::XtensaTargetLowering::LowerAsmOperandForConstraint</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a090b7c264f35ed6b224b38783e1d46fb">lowerImmediateIfPossible</a>.</p>

</div>
</div>

### LowerAsmOutputForConstraint() {#a91072af01cf52109f52a15ea367157bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::LowerAsmOutputForConstraint (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Glue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; OpInfo, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Definition at line 5086 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### LowerCall() {#a7446faa85fb7b6ebdbd136f514eee0af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::LowerCall (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
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

<p>This hook must be implemented to lower calls into the specified DAG.</p>


<p>The outgoing arguments to the call are described by the Outs array, and the values to be returned by the call are described by the Ins array. The implementation should fill in the InVals array with legal-type return values from the call, and return the resulting token chain value.</p>


<p>Definition at line 4770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### LowerCallTo() {#aabd42a6eddc3daec9153679b54f79300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; llvm::TargetLowering::LowerCallTo (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp; CLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function lowers an abstract call to a function into an actual call.</p>


<p>This returns a pair of operands. The first element is the return value for the function (if RetTy is not VoidTy). The second element is the outgoing token chain. It calls LowerCall to do the actual lowering.</p>


<p>Definition at line 4762 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af13091d8b3eced08538be82392dc7d43">emitSMEStateSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonselectiondaginfo/#a10a0dbb2ae8f208929d1f453d84cb101">llvm::HexagonSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreselectiondaginfo/#af87dbf9e0c8190963043ea6154532c25">llvm::XCoreSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a034082eea623803b4fa593f2e29f0d96">llvm::VETargetLowering::lowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af92646d30b3f15471c866cd83fadfb62">llvm::SparcTargetLowering::LowerF128Compare</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a85b82d7c69a744603ea8eccd2c40d52e">llvm::SparcTargetLowering::LowerF128Op</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a51e11fac59331e5e9704295214a2d5ee">LowerFSINCOS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ab29b69c993fbb9a4b9d28c3600df005d">llvm::SelectionDAGBuilder::lowerInvokable</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a54af997c0e800a9cdfb65dabe296f7c4">llvm::SystemZTargetLowering::makeExternalCall</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### lowerCmpEqZeroToCtlzSrl() {#a16ad899ace945b24e3ef91384f4faeba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::lowerCmpEqZeroToCtlzSrl (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### LowerCustomJumpTableEntry() {#acf30ced2ac2474a0dd5af2e3417c7b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MCExpr * llvm::TargetLowering::LowerCustomJumpTableEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo">MachineJumpTableInfo</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, unsigned, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;)</td>
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



<p>Definition at line 3862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### LowerFormalArguments() {#ab0296381d01e49bf5c4cbe0f3dc07187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::LowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
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

<p>This hook must be implemented to lower the incoming (formal) arguments, described by the Ins array, into the specified DAG.</p>


<p>The implementation should fill in the InVals array with legal-type argument values, and return the resulting token chain value.</p>


<p>Definition at line 4510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### LowerOperation() {#a04403a336136814ab74d9e2315bcfe23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::LowerOperation (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>This callback is invoked for operations that are unsupported by the target, which are registered to use 'custom' lowering, and whose defined values are all legal.</p>


<p>If the target has no operations that require custom lowering, it need not implement this. The default implementation of this aborts.</p>


<p>Definition at line 4903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### LowerOperationWrapper() {#a12431703c17466d24d4bf388ce467ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::LowerOperationWrapper (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>This callback is invoked by the type legalizer to legalize nodes with an illegal operand type but legal result types.</p>


<p>It replaces the LowerOperation callback in the type <a href="/web-llvm/docs/api/classes/llvm/legalizer">Legalizer</a>. The reason we can not do away with LowerOperation entirely is that LegalizeDAG isn't yet ready to use this callback.</p>


<p>TODO: Consider merging with ReplaceNodeResults.</p>


<p>The target places new result values for the node in Results (their number and types must exactly match those of the original return values of the node), or leaves Results empty, which indicates that the node is not to be custom lowered after all. The default implementation calls LowerOperation.</p>


<p>Definition at line 4894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ab6b1675dcd59de9c26f2e5c51b6a9ee3">llvm::HexagonTargetLowering::LowerOperationWrapper</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a73afb942bbe9f13347f351f28ac2fe2c">llvm::MipsTargetLowering::ReplaceNodeResults</a>.</p>

</div>
</div>

### LowerReturn() {#ac7ab87c087e9c55f4acc89ebe8ecbd5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::LowerReturn (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
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

<p>This hook must be implemented to lower outgoing return values, described by the Outs array, into the specified DAG.</p>


<p>The implementation should return the resulting token chain value.</p>


<p>Definition at line 4793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### LowerToTLSEmulatedModel() {#afdea2f06c6c1098b324fa2e2a1b9b2f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::LowerToTLSEmulatedModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * GA, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Lower TLS global address <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> for target independent emulated TLS model.</p>

<p>Definition at line 5601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ab44a5ddbc927f9b63731bf050dee8048">llvm::SparcTargetLowering::LowerGlobalTLSAddress</a>.</p>

</div>
</div>

### LowerXConstraint() {#aeca75f6b346035626e8849863671e02d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const char * llvm::TargetLowering::LowerXConstraint (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ConstraintVT)</td>
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

<p>Try to replace an X constraint, which matches anything, with another that has more specific requirements based on the type of the corresponding operand.</p>


<p>This returns null if there is no replacement to make.</p>


<p>Definition at line 5077 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#ace43e7f4b3e0e3d46309ffaf8eb07208">computeConstraintToUse</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a2aa47f16031986718a30310f73c8c90c">llvm::X86TargetLowering::LowerXConstraint</a>.</p>

</div>
</div>

### makeLibCall() {#ad4a2abb087afa577d8f4239b01acbea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; llvm::TargetLowering::makeLibCall (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> LC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; Ops, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/makelibcalloptions">MakeLibCallOptions</a> CallOptions, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pair of (return value, chain).</p>


<p>It is an error to pass RTLIB::UNKNOWN_LIBCALL as <span class="doxyComputerOutput">LC</span>.</p>


<p>Definition at line 3925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ac83ceb8e67e1ee6ca693e3ff1ffbac0f">llvm::LoongArchTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afff13ac7b2e92fc0ad596603592298bd">llvm::SelectionDAGBuilder::visitSPDescriptorFailure</a>.</p>

</div>
</div>

### mayBeEmittedAsTailCall() {#ae4502810d1edc3d8931681159af36d3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::mayBeEmittedAsTailCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *)</td>
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

<p>Return true if the target may be able emit the call instruction as a tail call.</p>


<p>This is used by optimization passes to determine if it's profitable to duplicate return instructions to enable tailcall optimization.</p>


<p>Definition at line 4814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### parametersInCSRMatch() {#ac11ad16fa22b9e7a5a04849e52b34fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::parametersInCSRMatch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * CallerPreservedMask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &gt; &amp; ArgLocs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether parameters to a call that are passed in callee saved registers are the same as from the calling function.</p>


<p>This needs to be checked for tail call eligibility.</p>


<p>Definition at line 3934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9330a86a613cf892ee5c7f515713f200">llvm::SITargetLowering::isEligibleForTailCallOptimization</a>.</p>

</div>
</div>

### ParseConstraints() {#a1c5e8b6aef41aead06d61ff0530ed9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual AsmOperandInfoVector llvm::TargetLowering::ParseConstraints (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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

<p>Split up the constraint string from the inline assembly value into the specific constraints and their prefixes, and also tie in the associated operand values.</p>


<p>If this returns an empty vector, and if the constraint string itself isn't empty, there was an error parsing.</p>


<p>Definition at line 5014 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a86026627b644e50527898aad0747b3e5">IsOperandAMemoryOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a10799c8833054017c6ab052c8b9c1aa2">llvm::SITargetLowering::requiresUniformRegister</a>.</p>

</div>
</div>

### PerformDAGCombine() {#a041dc0924ebd52a3eda7e1a22c00310b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::PerformDAGCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
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

<p>This method will be invoked for all target nodes and for any target-independent nodes that the target has registered with invoke it for.</p>


<p>The semantics are as follows: Return <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>: SDValue.Val == 0 - No change was made SDValue.Val == N - N was replaced, is dead, and is already handled. otherwise - N should be replaced by the returned Operand.</p>


<p>In addition, methods provided by <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> may be used to perform more complex transformations.</p>


<p>Definition at line 4293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### prepareVolatileOrAtomicLoad() {#a4c8ebb50f3043a4715d5a182288e8c82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::prepareVolatileOrAtomicLoad (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>This callback is used to prepare for a volatile or atomic load.</p>


<p>It takes a chain node as input and returns the chain for the load itself.</p>


<p>Having a callback like this is necessary for targets like <a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a>, which allows a CPU to reuse the result of a previous load indefinitely, even if a cache-coherent store is performed by another CPU. The default implementation does nothing.</p>


<p>Definition at line 4876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### ReplaceNodeResults() {#a134fd88697c3564433ba71a0202153e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::ReplaceNodeResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
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

<p>This callback is invoked when a node result type is illegal for the target, and the operation was registered to use 'custom' lowering for that result type.</p>


<p>The target places new result values for the node in Results (their number and types must exactly match those of the original return values of the node), or leaves Results empty, which indicates that the node is not to be custom lowered after all.</p>


<p>If the target has no operations that require custom lowering, it need not implement this. The default implementation aborts.</p>


<p>Definition at line 4914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### scalarizeVectorLoad() {#a9335df3ffa4731120eb2ddc78c2b2eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; llvm::TargetLowering::scalarizeVectorLoad (<a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> * LD, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Turn load of vector type into a load of the individual elements.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LD</td>
<td class="doxyParamItemDescription"><p>load to expand</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>BUILD_VECTOR and TokenFactor nodes.</p></dd>
</dl>


<p>Definition at line 5420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a0bd751c4c85d494e52e578b6bc10f8bc">llvm::AMDGPUTargetLowering::SplitVectorLoad</a>.</p>

</div>
</div>

### scalarizeVectorStore() {#aa226678963cfca06221c67886a7354f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::scalarizeVectorStore (<a href="/web-llvm/docs/api/classes/llvm/storesdnode">StoreSDNode</a> * ST, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ST</td>
<td class="doxyParamItemDescription"><p>Store with a vector value type</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>TokenFactor of the individual store chains.</p></dd>
</dl>


<p>Definition at line 5426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aad3b6954334c350e17f08d707e1f102f">llvm::AMDGPUTargetLowering::SplitVectorStore</a>.</p>

</div>
</div>

### shouldSimplifyDemandedVectorElts() {#aaad0d7dc149e145475abe9f7c9769d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::shouldSimplifyDemandedVectorElts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO)</td>
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

<p>Return true if the target supports simplifying demanded vector elements by converting them to undefs.</p>

<p>Definition at line 4091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### shouldSplitFunctionArgumentsAsLittleEndian() {#ac030eb4ba5f177779c4f903fabfdb285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::shouldSplitFunctionArgumentsAsLittleEndian (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>For most targets, an LLVM type must be broken down into multiple smaller types.</p>


<p>Usually the halves are ordered according to the endianness but for some platform that would break. So this method will default to matching the endianness but can be overridden.</p>


<p>Definition at line 4853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### ShrinkDemandedConstant() {#ac6a3aaac8faabe7dc09114d716a93eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::ShrinkDemandedConstant (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if the specified operand of the specified instruction is a constant integer.</p>


<p>If so, check to see if there are any bits set in the constant that are not demanded. If so, shrink the constant and return true.</p>


<p>Definition at line 3981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>.</p>

</div>
</div>

### ShrinkDemandedConstant() {#a0bfa6eb6976f71f59de24f14085056b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::ShrinkDemandedConstant (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper wrapper around ShrinkDemandedConstant, demanding all elements.</p>

<p>Definition at line 3986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### ShrinkDemandedOp() {#a60c2837ca8052c0432179f52148da7c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::ShrinkDemandedOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, unsigned BitWidth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert x+y to (VT)((SmallVT)x+(SmallVT)y) if the casts are free.</p>


<p>This uses isTruncateFree/isZExtFree and ANY_EXTEND for the widening cast, but it could be generalized for targets with other types of implicit widening casts.</p>


<p>Definition at line 4003 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>.</p>

</div>
</div>

### SimplifyDemandedBits() {#ab2fd70d9aeac9343fa8f00ccdeff7f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::SimplifyDemandedBits (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO, unsigned Depth=0, bool AssumeSingleUse=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look at <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>.</p>


<p>At this point, we know that only the <a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> bits of the result of <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> are ever used downstream. If we can use this information to simplify <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>, create a new simplified DAG node and return true, returning the original and new nodes in Old and New. Otherwise, analyze the expression and return a mask of KnownOne and KnownZero bits for the expression (used to simplify the caller). The KnownZero/One bits may only be accurate for those bits in the Demanded masks. <span class="doxyComputerOutput">AssumeSingleUse</span> When this parameter is true, this function will attempt to simplify <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> even if there are multiple uses. Callers are responsible for correctly updating the DAG based on the results of this function, because simply replacing TLO.Old with TLO.New will be incorrect when this parameter is true and TLO.Old has multiple uses.</p>


<p>Definition at line 4020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0e0d5fc4a01d9f412064a5448052330">combineBEXTR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afab7e380356e4b22d23f87fa2f45daf9">combineBT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a6a2af7640ee8f9e66287e024d0f6b8">combineMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a44f727169247a0359f485216a83265ac">combineMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab6a2c45af55afc1bf183cbafc577fd03">combineMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad27c58fe609558af3d02f6eb59c0d075">combinePDEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a92cb7f91737deedc3c70fb0ec0b70807">combinePMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a619d32c3e94bf8ee0348f9611590dd90">combineTESTP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a611e5eca9f470030689ec3f7d71c8e20">combineVectorInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a45f59ac6b0a55fb1b92f4b3bfd5ce327">combineVTRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae6535f37686895d8ab294ce06ffe2f15">combineX86GatherScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a960012b61a9977dc7c2d3af3943da953">llvm::AArch64TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a8e96878324f2ca0f847e369f839cfd23">llvm::ARMTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a42aa092f2811f72cad69b42cc2e4bb64">llvm::ARMTargetLowering::PerformIntrinsicCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1d0f22bfc290fd2cb53c9486286359df">PerformPREDICATE_CASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af4aeb38e252532a5362ac68998d0af93">performTBISimplification</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7e495837f173dea1e6919b589d315f67">performVectorShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a19d36e331487399aaac4f18bac0c7956">PerformVMOVhrCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#abbdb66ef7655ebae91e2bbfab4320f23">simplifyMul24</a>.</p>

</div>
</div>

### SimplifyDemandedBits() {#a5e35b84c574900228ebd4b735176fece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::SimplifyDemandedBits (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO, unsigned Depth=0, bool AssumeSingleUse=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper wrapper around SimplifyDemandedBits, demanding all elements.</p>


<p>Adds <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> back to the worklist upon success.</p>


<p>Definition at line 4027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>

</div>
</div>

### SimplifyDemandedBits() {#aa7ff8987a5190c8fbac02b359dffa536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::SimplifyDemandedBits (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper wrapper around SimplifyDemandedBits.</p>


<p>Adds <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> back to the worklist upon success.</p>


<p>Definition at line 4034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### SimplifyDemandedBits() {#ac9eb27b027f4a319ed244f2da8dbb9cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::SimplifyDemandedBits (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper wrapper around SimplifyDemandedBits.</p>


<p>Adds <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> back to the worklist upon success.</p>


<p>Definition at line 4039 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### SimplifyDemandedBitsForTargetNode() {#a1bb3f6ea028996773613a5f135b4d083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::SimplifyDemandedBitsForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO, unsigned Depth=0)</td>
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

<p>Attempt to simplify any target nodes based on the demanded bits/elts, returning true on success.</p>


<p>Otherwise, analyze the expression and return a mask of KnownOne and KnownZero bits for the expression (used to simplify the caller). The KnownZero/One bits may only be accurate for those bits in the Demanded masks.</p>


<p>Definition at line 4165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a655de0b9ba51c463a01a23651abb0cf7">llvm::ARMTargetLowering::SimplifyDemandedBitsForTargetNode</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>.</p>

</div>
</div>

### SimplifyDemandedVectorElts() {#a45a058376b4d2b008f7ea5ca16cecf55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::SimplifyDemandedVectorElts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedEltMask, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; KnownUndef, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; KnownZero, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO, unsigned Depth=0, bool AssumeSingleUse=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look at Vector <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>.</p>


<p>At this point, we know that only the DemandedElts elements of the result of <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> are ever used downstream. If we can use this information to simplify <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>, create a new simplified DAG node and return true, storing the original and new nodes in TLO. Otherwise, analyze the expression and return a mask of KnownUndef and KnownZero elements for the expression (used to simplify the caller). The KnownUndef/Zero elements may only be accurate for those bits in the DemandedMask. <span class="doxyComputerOutput">AssumeSingleUse</span> When this parameter is true, this function will attempt to simplify <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> even if there are multiple uses. Callers are responsible for correctly updating the DAG based on the results of this function, because simply replacing TLO.Old with TLO.New will be incorrect when this parameter is true and TLO.Old has multiple uses.</p>


<p>Definition at line 4078 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a24cdc31f225e6b17b30c139085b064">combineCVTPH2PS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a886d3292e22e113b2f04c1c35811bd0c">combineKSHIFT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae9b4450314b8e4acb9f937389b349fce">combineShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a66295c004fc51403028ea1933b66642a">combineVectorShiftVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9ac1db32c7172ebb71d45a6ece209b53">combineVEXTRACT_STORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c6a560bbaa7931f6375fd838fcfbaa8">combineVPMADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0185d63d243a248f5bc69dfc943c88a">combineX86INT_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaec24048b5502da3e426b474be7e6b4d">PerformVMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a87f35b3974b7d383ff5cd70bdfa090ab">PerformVQMOVNCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5681faab09fa140f67d47577193f2665">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetShuffle</a>.</p>

</div>
</div>

### SimplifyDemandedVectorElts() {#a0df0d85885c52c23edc2df2964dda688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::SimplifyDemandedVectorElts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper wrapper around SimplifyDemandedVectorElts.</p>


<p>Adds <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> back to the worklist upon success.</p>


<p>Definition at line 4085 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### SimplifyDemandedVectorEltsForTargetNode() {#af44b4b9c14768bdaaafa69cd6d5c3d46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::SimplifyDemandedVectorEltsForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; KnownUndef, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; KnownZero, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO, unsigned Depth=0)</td>
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

<p>Attempt to simplify any target nodes based on the demanded vector elements, returning true on success.</p>


<p>Otherwise, analyze the expression and return a mask of KnownUndef and KnownZero elements for the expression (used to simplify the caller). The KnownUndef/Zero elements may only be accurate for those bits in the DemandedMask.</p>


<p>Definition at line 4156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>

</div>
</div>

### SimplifyMultipleUseDemandedBits() {#a0338302ee706a6cd16534e768210b0b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::SimplifyMultipleUseDemandedBits (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>More limited version of SimplifyDemandedBits that can be used to "look
through" ops that don't contribute to the DemandedBits/DemandedElts - bitwise ops etc.</p>

<p>Definition at line 4046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a6a2af7640ee8f9e66287e024d0f6b8">combineMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a44f727169247a0359f485216a83265ac">combineMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a19158530c7e8bd08610180be814ec9b1">combinePTESTCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abfd7c524b17cd29c6470d1780f06d460">matchRotateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#abbdb66ef7655ebae91e2bbfab4320f23">simplifyMul24</a>.</p>

</div>
</div>

### SimplifyMultipleUseDemandedBits() {#afb81fb8d18522d12e39a60c3b43cf291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::SimplifyMultipleUseDemandedBits (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper wrapper around SimplifyMultipleUseDemandedBits, demanding all elements.</p>

<p>Definition at line 4053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>

</div>
</div>

### SimplifyMultipleUseDemandedBitsForTargetNode() {#a03f40e066df2407ab1e901ca999d717e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth)</td>
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

<p>More limited version of SimplifyDemandedBits that can be used to "look
through" ops that don't contribute to the DemandedBits/DemandedElts - bitwise ops etc.</p>

<p>Definition at line 4175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>.</p>

</div>
</div>

### SimplifyMultipleUseDemandedVectorElts() {#a480a8e3181c852945f597bad4fd0d9c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::SimplifyMultipleUseDemandedVectorElts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper wrapper around SimplifyMultipleUseDemandedBits, demanding all bits from only some vector elements.</p>

<p>Definition at line 4059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>.</p>

</div>
</div>

### SimplifySetCC() {#a32a31ce1e9f6e4b965d11feb2501fc47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::SimplifySetCC (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N1, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> Cond, bool foldBooleans, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to simplify a setcc built with the specified operands and cc.</p>


<p>If it is unable to simplify it, return a null <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>.</p>


<p>Definition at line 4268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>.</p>

</div>
</div>

### softenSetCCOperands() {#a62f2d0a1eebd818fb037a64c40cf0521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLowering::softenSetCCOperands (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; NewLHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; NewRHS, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> &amp; CCCode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> OldLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> OldRHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### softenSetCCOperands() {#a518caa772bb677e2e590fad18c6d07ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetLowering::softenSetCCOperands (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; NewLHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; NewRHS, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> &amp; CCCode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> OldLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> OldRHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, bool IsSignaling=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### splitValueIntoRegisterParts() {#a67bcd59b7c8b892b3252d10a6ebf8370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::splitValueIntoRegisterParts (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * Parts, unsigned NumParts, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> PartVT, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> &gt; CC)</td>
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

<p>Target-specific splitting of values into parts that fit a register storing a legal type.</p>

<p>Definition at line 4474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8910923e28ba24c5abedb60c66c86cc5">getCopyToParts</a>.</p>

</div>
</div>

### supportKCFIBundles() {#a0160cf5c2cae2754444db153907790a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::supportKCFIBundles ()</td>
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

<p>Return true if the target supports kcfi operand bundles.</p>

<p>Definition at line 4401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>.</p>

</div>
</div>

### supportPtrAuthBundles() {#a12cbb115116dd32eb6c32ba191761093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::supportPtrAuthBundles ()</td>
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

<p>Return true if the target supports ptrauth operand bundles.</p>

<p>Definition at line 4404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>.</p>

</div>
</div>

### supportSplitCSR() {#adf63d5761e47f6e642a82cab1abda28f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::supportSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Return true if the target supports that a subset of CSRs for the given machine function is handled explicitly via copies.</p>

<p>Definition at line 4396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### supportSwiftError() {#a17694ad399c24aae0d2c0ecfbecfea5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::supportSwiftError ()</td>
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

<p>Return true if the target supports swifterror attribute.</p>


<p>It optimizes loads and stores to reading and writing a specific register.</p>


<p>Definition at line 4390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzelfregisters/#a948f65c38b613d36deb501eb8b8476c8">llvm::SystemZELFRegisters::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfregisters/#af9a3f20abd67b17fdb105aa2fe63e08d">llvm::SystemZELFRegisters::getCallPreservedMask</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>.</p>

</div>
</div>

### targetShrinkDemandedConstant() {#a3b1a3e65e45ccd3664f44797e7e061ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::targetShrinkDemandedConstant (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO)</td>
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



<p>Definition at line 3992 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### unwrapAddress() {#a5fb3dd542dde309c8e94f2a54f041814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::unwrapAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 4273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagaddressanalysis-cpp/#a54243aacf632aa264d595914deb5ad08">matchLSNode</a>.</p>

</div>
</div>

### useLoadStackGuardNode() {#ad2b27b633b21a362571660ad09273d52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetLowering::useLoadStackGuardNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>If this function returns true, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> emits a LOAD_STACK_GUARD node when it is lowering Intrinsic::stackprotector.</p>

<p>Definition at line 5593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#adc38e57cd913199ae05e57970421f100">llvm::AArch64TargetLowering::useLoadStackGuardNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ad022667ae203c4c91fca45e3c9f568d9">llvm::PPCTargetLowering::useLoadStackGuardNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#adbada954ccf57e9f3a90869f740419b2">llvm::SparcTargetLowering::useLoadStackGuardNode</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### verifyReturnAddressArgumentIsConstant() {#a25df8af0900b4a664055a7ccba026531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::verifyReturnAddressArgumentIsConstant (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ac34b44e6d66ff1778af7b93db6d3cf23">llvm::HexagonTargetLowering::LowerRETURNADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a94ec50da525b52281c1d4bbde196c520">llvm::MSP430TargetLowering::LowerRETURNADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afa7dd71b99cc3f038bc3f91104cf66ee">LowerRETURNADDR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#ae6503e6c0724d0ae0cb7854ba5c5a9f6">lowerRETURNADDR</a>.</p>

</div>
</div>

### verifyTargetSDNode() {#a5a4ecad8579717395c05ad1218d440b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetLowering::verifyTargetSDNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the given <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. Aborts if it is invalid.</p>

<p>Definition at line 4935 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acd50ad0e12fc082d49c38ea80985c612">VerifySDNode</a>.</p>

</div>
</div>

### visitMaskedLoad() {#a18dbec68fb7d9eadbe98106caa943e51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::visitMaskedLoad (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; NewLoad, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Ptr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> PassThru, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Mask)</td>
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



<p>Definition at line 3909 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### visitMaskedStore() {#ace423253c9f88eb6f6f395daa4bf02b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SDValue llvm::TargetLowering::visitMaskedStore (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Ptr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Mask)</td>
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



<p>Definition at line 3916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildSREMEqFold() {#a2d7a30d2401bc903b60de496f314601e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::buildSREMEqFold (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SETCCVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> REMNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> CompTargetNode, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> Cond, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### buildUREMEqFold() {#af35295204758d3ef527c98a8962de064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::buildUREMEqFold (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SETCCVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> REMNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> CompTargetNode, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> Cond, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### foldSetCCWithAnd() {#ab7011ad40466921625b5f10b38753fb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::foldSetCCWithAnd (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N1, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### foldSetCCWithBinOp() {#a33b4592c3de00d9152cca06551702cf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::foldSetCCWithBinOp (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N1, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### optimizeSetCCByHoistingAndByConstFromLogicalShift() {#afc5cfd1ddb384da50e778223a24ef810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::optimizeSetCCByHoistingAndByConstFromLogicalShift (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SCCVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N1C, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> Cond, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### optimizeSetCCOfSignedTruncationCheck() {#a5d6826180f440716b7cb16c9fafa1763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::optimizeSetCCOfSignedTruncationCheck (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SCCVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N1, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> Cond, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### prepareSREMEqFold() {#a826160c1a7b93cbd109bcf90dc6f8a75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::prepareSREMEqFold (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SETCCVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> REMNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> CompTargetNode, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> Cond, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### prepareUREMEqFold() {#a6e5d2af01a293dc8faa840dc01c61791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::prepareUREMEqFold (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SETCCVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> REMNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> CompTargetNode, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> Cond, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
