---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/spirvglobalregistry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SPIRVGlobalRegistry` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SPIRVGlobalRegistry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">Target/SPIRV/SPIRVGlobalRegistry.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a555f67f9597935ac2c30b0361ee3c43c">SPIRVGlobalRegistry</a> (unsigned PointerSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a7b1a0e9b3e67dc8152bd7f26f7bb7c">add</a> (const Constant *C, MachineFunction *MF, Register R)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ca938db958f8cccaafd482c62e9323">add</a> (const GlobalVariable *GV, MachineFunction *MF, Register R)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88555d28be5c8e5381bd051d9cad5c42">add</a> (const Function *F, MachineFunction *MF, Register R)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ee79808e300427db6520af2883a24c9">add</a> (const Argument *Arg, MachineFunction *MF, Register R)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c9e455332151378771d756a5ffc568c">add</a> (const MachineInstr *MI, MachineFunction *MF, Register R)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf51033e8bd031899d7e51435b78bb5b">find</a> (const MachineInstr *MI, MachineFunction *MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ff93727348b66a7857b15361ccad15">find</a> (const Constant *C, MachineFunction *MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f23d16abbebbb81a2670e5bfc79eb20">find</a> (const GlobalVariable *GV, MachineFunction *MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87ccf83f80c94783102715e56ef50082">find</a> (const Function *F, MachineFunction *MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a280ad3b23c2e3ffd2aa810afdaac12b1">setBound</a> (unsigned V)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1400c803160f702d9476c0610073a4b3">getBound</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c12a8c76f90eef79dc4a985b0007503">addGlobalObject</a> (const Value *V, const MachineFunction *MF, Register R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1083a23584b3d85540bd521ac67564df">getGlobalObject</a> (const MachineFunction *MF, Register R)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674354e9de4ecc50090837bcad1f3936">addReturnType</a> (const Function *ArgF, TypedPointerType *DerivedTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/typedpointertype">TypedPointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06724e2fb3d99c573396f9e6e97bf372">findReturnType</a> (const Function *ArgF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0acb08d88c738a882f24bebf2ddd0a0d">addAssignPtrTypeInstr</a> (Value *Val, CallInst *AssignPtrTyCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f6ee60206f6ab5be7346e8125c3327">findAssignPtrTypeInstr</a> (const Value *Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f6cbbfa318b48e44bd1d86a483b05a">updateIfExistAssignPtrTypeInstr</a> (Value *OldVal, Value *NewVal, bool DeleteOld)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a797b7143b1b61fcf9445079c949e5d83">addMutated</a> (Value *Val, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a928d32be153c2a7382697834cb0b7910">findMutated</a> (const Value *Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae04bcaba5390c68684b77cfe297433af">addValueAttrs</a> (MachineInstr *Key, std::pair&lt; Type *, std::string &gt; Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8983f2f2201e62922443e9571b3d05a4">findValueAttrs</a> (const MachineInstr *Key, Type *&amp;Ty, StringRef &amp;Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f378a50d2b190cb85f8d1f953c3f93f">addDeducedElementType</a> (Value *Val, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af010c154d556626f5516148c1a7ed57b">findDeducedElementType</a> (const Value *Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ea813b70176abfec916e721ae8570f3">updateIfExistDeducedElementType</a> (Value *OldVal, Value *NewVal, bool DeleteOld)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3bfecae058769fb427c2953e455c310">addDeducedCompositeType</a> (Value *Val, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aa9ba7d1e6752aad26fa2756d5701c6">findDeducedCompositeType</a> (const Value *Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad66b2a904c889bc1fab75ac287adb5d4">getDeducedGlobalValueType</a> (const GlobalValue *Global)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67f8d12aab3ebb0bf0c24bc39b2ac2b1">getFunctionDefinitionByUse</a> (const MachineOperand *Use)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6154e5a73b50ec0dbf9d6790b70da1a2">getFunctionDefinition</a> (const Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae28c9f37f79168be8e13396da72d35ff">getFunctionByDefinition</a> (const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadfb369a3dd5eaa5f5b443c7c8b83ede">recordFunctionPointer</a> (const MachineOperand *MO, const Function *F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00d35e3f57b5ac9407316ad4161c83e4">recordFunctionDefinition</a> (const Function *F, const MachineOperand *MO)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6979fe82f502c4648493263f37d136fa">hasConstFunPtr</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088dabce389b169b6428434b3fee2153">addForwardCall</a> (const Function *F, MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2637a305be723fc30c48c240afa63ff">getForwardCalls</a> (const Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa66e13122dec2a32f7d1b1f7240048e2">assignTypeToVReg</a> (const Type *Type, Register VReg, MachineIRBuilder &amp;MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AQ=SPIRV::AccessQualifier::ReadWrite, bool EmitIR=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f2b05d25ba2010b0c306071730fe01">assignIntTypeToVReg</a> (unsigned BitWidth, Register VReg, MachineInstr &amp;I, const SPIRVInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a224cd42d0c6c318274c1696e74b63b51">assignFloatTypeToVReg</a> (unsigned BitWidth, Register VReg, MachineInstr &amp;I, const SPIRVInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29a63a69f9d2a425a5fbef3e0104399e">assignVectTypeToVReg</a> (SPIRVType *BaseType, unsigned NumElements, Register VReg, MachineInstr &amp;I, const SPIRVInstrInfo &amp;TII)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a8bf11a7b9112db6517027fcd834e8">assignSPIRVTypeToVReg</a> (SPIRVType *Type, Register VReg, const MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7712aacb3f4a1a860a15ca4de83e6a9f">getOrCreateSPIRVType</a> (const Type *Type, MachineIRBuilder &amp;MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AQ=SPIRV::AccessQualifier::ReadWrite, bool EmitIR=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a> (const SPIRVType *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d986da977a884fc79751da79c4e6f84">getPointeeType</a> (SPIRVType *PtrType)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c80c43434acec4d262a13013d993dd3">getPointeeTypeOp</a> (Register PtrReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f17d3e92f855f675577a021e9bc2a35">getOrCreateSPIRVTypeByName</a> (StringRef TypeStr, MachineIRBuilder &amp;MIRBuilder, SPIRV::StorageClass::StorageClass SC=SPIRV::StorageClass::Function, SPIRV::AccessQualifier::AccessQualifier AQ=SPIRV::AccessQualifier::ReadWrite)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a> (Register VReg, const MachineFunction *MF=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0abb9ee0d1c0872f76cea9d9b6c1396e">getResultType</a> (Register VReg, MachineFunction *MF=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa04e30da4fa3f1602a4728cd88c62e7e">hasSPIRVTypeForVReg</a> (Register VReg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a> (const SPIRVType *SpirvType) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe2132b08f73f4e1715fbefbddfacb55">setCurrentFunc</a> (MachineFunction &amp;MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4143059b879c9d0fef2e028e20dddb4">isAggregateType</a> (SPIRVType *Type) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ec44625f429790b5ed7e3f67a70fdab">isScalarOfType</a> (Register VReg, unsigned TypeOpcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab91827a04a8d97aa04d5fd0d86ec790e">isScalarOrVectorOfType</a> (Register VReg, unsigned TypeOpcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48be4a06ef828d5cfa75a2447fe95202">getScalarOrVectorComponentCount</a> (Register VReg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d67d14155aa4291adf0aa842ef5e3ba">getScalarOrVectorComponentCount</a> (SPIRVType *Type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d47327f9572ae6739e9a75d52c71dc1">getScalarOrVectorComponentType</a> (Register VReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625767127423cea458550a1505f80d39">getScalarOrVectorComponentType</a> (SPIRVType *Type) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa7b871b453a7e248c0231fb9550e1d7">getScalarOrVectorBitWidth</a> (const SPIRVType *Type) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04977130fc7ce99ac97940d9b6b3fde6">getNumScalarOrVectorTotalBitWidth</a> (const SPIRVType *Type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff378412481afe6008a257ca9afade7">retrieveScalarOrVectorIntType</a> (const SPIRVType *Type) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eb4dcdccf96e4fd24c31db70617c00e">isScalarOrVectorSigned</a> (const SPIRVType *Type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SPIRV::StorageClass::StorageClass</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea90d9f0d1cf03f79d678050beaf922e">getPointerStorageClass</a> (Register VReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SPIRV::StorageClass::StorageClass</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8545705eb22c4e30c0868a578d745e8a">getPointerStorageClass</a> (const SPIRVType *Type) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b040ee6ba795930a71373a06b8dd8c7">getPointerSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4760bd5cfc1e3283253a7b0d06beaf90">isBitcastCompatible</a> (const SPIRVType *Type1, const SPIRVType *Type2) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72f93953efc4bafcbb048af4dd6fdaaa">invalidateMachineInstr</a> (MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affb04c244423615aa0df24ee36f2de20">buildConstantInt</a> (uint64_t Val, MachineIRBuilder &amp;MIRBuilder, SPIRVType *SpvType, bool EmitIR=true, bool ZeroAsNull=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f607435df14840793b848f2b3c0257">getOrCreateConstInt</a> (uint64_t Val, MachineInstr &amp;I, SPIRVType *SpvType, const SPIRVInstrInfo &amp;TII, bool ZeroAsNull=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54e9ce01961e65d9b74fef2193a8d95">getOrCreateConstFP</a> (APFloat Val, MachineInstr &amp;I, SPIRVType *SpvType, const SPIRVInstrInfo &amp;TII, bool ZeroAsNull=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aee777d2869b23ba59b88b9ceb32cfe">buildConstantFP</a> (APFloat Val, MachineIRBuilder &amp;MIRBuilder, SPIRVType *SpvType=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea0d5a07369a9502280335b276b3ccb">getOrCreateConstVector</a> (uint64_t Val, MachineInstr &amp;I, SPIRVType *SpvType, const SPIRVInstrInfo &amp;TII, bool ZeroAsNull=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea5285dbe63b422dcaf313ec0fe7473d">getOrCreateConstVector</a> (APFloat Val, MachineInstr &amp;I, SPIRVType *SpvType, const SPIRVInstrInfo &amp;TII, bool ZeroAsNull=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abab34b1cb73af8519772979270773492">getOrCreateConstIntArray</a> (uint64_t Val, size_t Num, MachineInstr &amp;I, SPIRVType *SpvType, const SPIRVInstrInfo &amp;TII)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dddf52f700258ac37fa137527588809">getOrCreateConsIntVector</a> (uint64_t Val, MachineIRBuilder &amp;MIRBuilder, SPIRVType *SpvType, bool EmitIR=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af99db04834e1ae3fc23466a80045a4d9">getOrCreateConstNullPtr</a> (MachineIRBuilder &amp;MIRBuilder, SPIRVType *SpvType)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4280c0cdf83d31309a8ad8d0d6815e66">buildConstantSampler</a> (Register Res, unsigned AddrMode, unsigned Param, unsigned FilerMode, MachineIRBuilder &amp;MIRBuilder, SPIRVType *SpvType)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35c2ba2ad91e2fe027f8f64e92a7502f">getOrCreateUndef</a> (MachineInstr &amp;I, SPIRVType *SpvType, const SPIRVInstrInfo &amp;TII)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a881c9e75128e7e943b6d8f33606ccc74">buildGlobalVariable</a> (Register Reg, SPIRVType *BaseType, StringRef Name, const GlobalValue *GV, SPIRV::StorageClass::StorageClass Storage, const MachineInstr *Init, bool IsConst, bool HasLinkageTy, SPIRV::LinkageType::LinkageType LinkageType, MachineIRBuilder &amp;MIRBuilder, bool IsInstSelector)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d65d879a707f0fcaa221e60be3a1a54">getOrCreateGlobalVariableWithBinding</a> (const SPIRVType *VarType, uint32_t Set, uint32_t Binding, MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdec96f14d81b2043e31f3452e440a4b">getOrCreateSPIRVIntegerType</a> (unsigned BitWidth, MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18fd6615429a508c934bc1cff0f49319">getOrCreateSPIRVIntegerType</a> (unsigned BitWidth, MachineInstr &amp;I, const SPIRVInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f224f7bdbbd3667e44b205c571b30d2">getOrCreateSPIRVType</a> (unsigned BitWidth, MachineInstr &amp;I, const SPIRVInstrInfo &amp;TII, unsigned SPIRVOPcode, Type *LLVMTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b607e6993b349291749a0e177c52fbb">getOrCreateSPIRVFloatType</a> (unsigned BitWidth, MachineInstr &amp;I, const SPIRVInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d6978ae20178c8f9414ff980fd4e3b2">getOrCreateSPIRVBoolType</a> (MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bdd4c60453b10074293349820f8bdcf">getOrCreateSPIRVBoolType</a> (MachineInstr &amp;I, const SPIRVInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd545bc376f8f5880178094a2d165476">getOrCreateSPIRVVectorType</a> (SPIRVType *BaseType, unsigned NumElements, MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4791c0c5f18aaa298445226456f15547">getOrCreateSPIRVVectorType</a> (SPIRVType *BaseType, unsigned NumElements, MachineInstr &amp;I, const SPIRVInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5869468359515f460a588357f1737cf">getOrCreateSPIRVArrayType</a> (SPIRVType *BaseType, unsigned NumElements, MachineInstr &amp;I, const SPIRVInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acab67f583801f5c01ee9ac2162f5e27d">getOrCreateSPIRVPointerType</a> (SPIRVType *BaseType, MachineIRBuilder &amp;MIRBuilder, SPIRV::StorageClass::StorageClass SClass=SPIRV::StorageClass::Function)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bde676c37078e2ffb74ce2814f11048">getOrCreateSPIRVPointerType</a> (SPIRVType *BaseType, MachineInstr &amp;I, const SPIRVInstrInfo &amp;TII, SPIRV::StorageClass::StorageClass SClass=SPIRV::StorageClass::Function)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cd2c03c778450920cd3b53acdcb4fba">getOrCreateOpTypeImage</a> (MachineIRBuilder &amp;MIRBuilder, SPIRVType *SampledType, SPIRV::Dim::Dim Dim, uint32_t Depth, uint32_t Arrayed, uint32_t Multisampled, uint32_t Sampled, SPIRV::ImageFormat::ImageFormat ImageFormat, SPIRV::AccessQualifier::AccessQualifier AccQual)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea914eb511a3b8ebf605c62c07e8ab44">getOrCreateOpTypeSampler</a> (MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cdc39b963a62003cd157541feca56f6">getOrCreateOpTypeSampledImage</a> (SPIRVType *ImageType, MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbccd3fb66e9075690f45dea7440cf9e">getOrCreateOpTypeCoopMatr</a> (MachineIRBuilder &amp;MIRBuilder, const TargetExtType *ExtensionType, const SPIRVType *ElemType, uint32_t Scope, uint32_t Rows, uint32_t Columns, uint32_t Use)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0067190a151de0ad367e8d1e56c1016a">getOrCreateOpTypePipe</a> (MachineIRBuilder &amp;MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AccQual)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeddeff35f8dd231213915a6f77f0920">getOrCreateOpTypeDeviceEvent</a> (MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac40b88bee839e32d4f0f860282d0fc4">getOrCreateOpTypeFunctionWithArgs</a> (const Type *Ty, SPIRVType *RetType, const SmallVectorImpl&lt; SPIRVType * &gt; &amp;ArgTypes, MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69f73e1b5f8a3e376c63293408b6786e">getOrCreateOpTypeByOpcode</a> (const Type *Ty, MachineIRBuilder &amp;MIRBuilder, unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6e454de3dfa112cc7e30219ac7298cd">getRegClass</a> (SPIRVType *SpvType) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad864cdbeb2b8c6a7cf87d8141abc5735">getRegType</a> (SPIRVType *SpvType) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb0c1292851b9e5fcb97c69b6e520905">checkSpecialInstr</a> (const SPIRV::SpecialTypeDescriptor &amp;TD, MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ad075083a50745fb933b73688fedf5">createSPIRVType</a> (const Type *Type, MachineIRBuilder &amp;MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AQ=SPIRV::AccessQualifier::ReadWrite, bool EmitIR=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4088abadea295426d4597f021b713cac">findSPIRVType</a> (const Type *Ty, MachineIRBuilder &amp;MIRBuilder, SPIRV::AccessQualifier::AccessQualifier accessQual=SPIRV::AccessQualifier::ReadWrite, bool EmitIR=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec19bbaaa10e66b0a2c9eb44d661017">restOfCreateSPIRVType</a> (const Type *Type, MachineIRBuilder &amp;MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AccessQual, bool EmitIR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1e2308f49caa30613fdd66ea523f39">createOpType</a> (MachineIRBuilder &amp;MIRBuilder, std::function&lt; MachineInstr *(MachineIRBuilder &amp;)&gt; Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ecbc449274806f96febe11a462bfcfa">getOpTypeBool</a> (MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7380d60aeab7bd7c320dcc6983c63e18">adjustIntTypeByWidth</a> (const Type *Ty) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b5e4e68613771e719ab0ec92dc91b75">adjustOpTypeIntWidth</a> (unsigned Width) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284aa95f7a27c3efdf9178a22f8aadcd">getOpTypeInt</a> (unsigned Width, MachineIRBuilder &amp;MIRBuilder, bool IsSigned=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef2b8363588a3576e6154e834842034">getOpTypeFloat</a> (uint32_t Width, MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a887ada042d63eb70807dc15aefcd6390">getOpTypeVoid</a> (MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4235d1b6d11a7696ce70d0066d35ab28">getOpTypeVector</a> (uint32_t NumElems, SPIRVType *ElemType, MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f51d642ceeb354a0231a8d33195101">getOpTypeArray</a> (uint32_t NumElems, SPIRVType *ElemType, MachineIRBuilder &amp;MIRBuilder, bool EmitIR=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac496f60fc469db05370eaceb9fda4517">getOpTypeOpaque</a> (const StructType *Ty, MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd584c22dfc805dde1b05d63617e3b4e">getOpTypeStruct</a> (const StructType *Ty, MachineIRBuilder &amp;MIRBuilder, bool EmitIR=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6973e6b9843f2c8a2bf32a4721cf27ea">getOpTypePointer</a> (SPIRV::StorageClass::StorageClass SC, SPIRVType *ElemType, MachineIRBuilder &amp;MIRBuilder, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b674d651ac3e4016eeb5a26939666f3">getOpTypeForwardPointer</a> (SPIRV::StorageClass::StorageClass SC, MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34bb0d8b9e700802f8655fa9732b5e82">getOpTypeFunction</a> (SPIRVType *RetType, const SmallVectorImpl&lt; SPIRVType * &gt; &amp;ArgTypes, MachineIRBuilder &amp;MIRBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c8a2183f36a6f7e486606a75bf96ee">getOrCreateSpecialType</a> (const Type *Ty, MachineIRBuilder &amp;MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AccQual)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *, bool, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95cd72c33e8e06b8bcfda5595e7cb638">getOrCreateConstIntReg</a> (uint64_t Val, SPIRVType *SpvType, MachineIRBuilder *MIRBuilder, MachineInstr *I=nullptr, const SPIRVInstrInfo *TII=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> *, bool, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a539c49ee376324e7bc129fa59444a704">getOrCreateConstFloatReg</a> (APFloat Val, SPIRVType *SpvType, MachineIRBuilder *MIRBuilder, MachineInstr *I=nullptr, const SPIRVInstrInfo *TII=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6f1ebc75bb9daa9e67a9a0a20f7acef">finishCreatingSPIRVType</a> (const Type *LLVMTy, SPIRVType *SpirvType)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5802f07ff75bd2855e70ea0d71ae107">getOrCreateBaseRegister</a> (Constant *Val, MachineInstr &amp;I, SPIRVType *SpvType, const SPIRVInstrInfo &amp;TII, unsigned BitWidth, bool ZeroAsNull)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e776a4eac8e6f8e0885db97ee4fad4c">getOrCreateCompositeOrNull</a> (Constant *Val, MachineInstr &amp;I, SPIRVType *SpvType, const SPIRVInstrInfo &amp;TII, Constant *CA, unsigned BitWidth, unsigned ElemCnt, bool ZeroAsNull=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03e3caae340beeb82a742d90d753865f">getOrCreateIntCompositeOrNull</a> (uint64_t Val, MachineIRBuilder &amp;MIRBuilder, SPIRVType *SpvType, bool EmitIR, Constant *CA, unsigned BitWidth, unsigned ElemCnt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2d25cc81033e84d315fedab8f088c91">VRegToTypeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spirvgeneralduplicatestracker">SPIRVGeneralDuplicatesTracker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cb05aaaed3e45867183b2d488d295a1">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8b8d75f6e61e82b2df980a0be8cc66">SPIRVToLLVMType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48078c7d946e2f3db8e32bea68e44a13">FunctionToInstr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e87f79b02218130f8c46daa90dee590">FunctionToInstrRev</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9ce46ff92a76d497a830c240e504ad7">InstrToFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af444a9cadf65534dc57e577dda71a98a">ForwardCalls</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97ea15a5fa1c21f0a451d6648c9fb005">MutatedAggRet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0cfc0609b0b055e6a88abbe584ea8c">ValueAttrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a211dd4c363894f27b091c8006d0b55ee">TypesInProcessing</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1db98fa9a90b44fe8af4788a6852ef8">ForwardPointerTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3bb5af1a5b9998a74c9040d2c041e94">LastInsertedTypeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype">TypedPointerType</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0ce2b489e1162f3897e094191ba3e1">FunResPointerTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c798abd3a1685b10c7aacc8f434fe81">PointerSize</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2565ea5642d8e49e66c056c41cc18910">Bound</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a506c0d945cef7429ac7e87206a11234b">DeducedElTys</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae519640411fbbd7e6f9d6f59359619a4">DeducedNestedTys</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96a68bf8f098e836a073f4ea5950ccad">AssignPtrTypeInstr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17784db68d81bd1893724b2f1ca8e5d7">Reg2GO</a></td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SPIRVGlobalRegistry() {#a555f67f9597935ac2c30b0361ee3c43c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVGlobalRegistry::SPIRVGlobalRegistry (unsigned PointerSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a3a7b1a0e9b3e67dc8152bd7f26f7bb7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>.</p>

</div>
</div>

### add() {#a53ca938db958f8cccaafd482c62e9323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### add() {#a88555d28be5c8e5381bd051d9cad5c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### add() {#a5ee79808e300427db6520af2883a24c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * Arg, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### add() {#a3c9e455332151378771d756a5ffc568c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### addAssignPtrTypeInstr() {#a0acb08d88c738a882f24bebf2ddd0a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::addAssignPtrTypeInstr (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * AssignPtrTyCI)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### addDeducedCompositeType() {#aa3bfecae058769fb427c2953e455c310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::addDeducedCompositeType (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### addDeducedElementType() {#a4f378a50d2b190cb85f8d1f953c3f93f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::addDeducedElementType (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### addForwardCall() {#a088dabce389b169b6428434b3fee2153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::addForwardCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a>.</p>

</div>
</div>

### addGlobalObject() {#a9c12a8c76f90eef79dc4a985b0007503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::addGlobalObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a> and <a href="#a881c9e75128e7e943b6d8f33606ccc74">buildGlobalVariable</a>.</p>

</div>
</div>

### addMutated() {#a797b7143b1b61fcf9445079c949e5d83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::addMutated (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### addReturnType() {#a674354e9de4ecc50090837bcad1f3936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::addReturnType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * ArgF, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype">TypedPointerType</a> * DerivedTy)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### addValueAttrs() {#ae04bcaba5390c68684b77cfe297433af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::addValueAttrs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Key, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, std::string &gt; Val)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>.</p>

</div>
</div>

### assignFloatTypeToVReg() {#a224cd42d0c6c318274c1696e74b63b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::assignFloatTypeToVReg (unsigned BitWidth, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a24a8bf11a7b9112db6517027fcd834e8">assignSPIRVTypeToVReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="#a4b607e6993b349291749a0e177c52fbb">getOrCreateSPIRVFloatType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### assignIntTypeToVReg() {#a88f2b05d25ba2010b0c306071730fe01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::assignIntTypeToVReg (unsigned BitWidth, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a24a8bf11a7b9112db6517027fcd834e8">assignSPIRVTypeToVReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="#acdec96f14d81b2043e31f3452e440a4b">getOrCreateSPIRVIntegerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### assignSPIRVTypeToVReg() {#a24a8bf11a7b9112db6517027fcd834e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVGlobalRegistry::assignSPIRVTypeToVReg (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>Referenced by <a href="#a224cd42d0c6c318274c1696e74b63b51">assignFloatTypeToVReg</a>, <a href="#a88f2b05d25ba2010b0c306071730fe01">assignIntTypeToVReg</a>, <a href="#aa66e13122dec2a32f7d1b1f7240048e2">assignTypeToVReg</a>, <a href="#a29a63a69f9d2a425a5fbef3e0104399e">assignVectTypeToVReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acec38968fb25d9da84d9d606eca35d7d">llvm::buildAtomicRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a191e4c250748ed5043795f6bf3caf4e9">llvm::buildBuiltinVariableLoad</a>, <a href="#a6aee777d2869b23ba59b88b9ceb32cfe">buildConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="#a881c9e75128e7e943b6d8f33606ccc74">buildGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp/#a3b8f2c8dafaf2b1007b8661546ce5aca">convertPtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c02a62be344861d8a7598e08d1021b6">llvm::createVirtualRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3abab01a19c99b6700cc0aadde16edc2">llvm::generateICarryBorrowInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>, <a href="#af99db04834e1ae3fc23466a80045a4d9">getOrCreateConstNullPtr</a>, <a href="#a35c2ba2ad91e2fe027f8f64e92a7502f">getOrCreateUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a2222b2a89839a157c1b2992743effe">llvm::insertAssignInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a5457cbda7e9b1866c1c16af5ac330273">insertBitcasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3f9bac9bdd3f5fc36a5f5e13480d4a">llvm::setRegClassType</a>.</p>

</div>
</div>

### assignTypeToVReg() {#aa66e13122dec2a32f7d1b1f7240048e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::assignTypeToVReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Type, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AQ=SPIRV::AccessQualifier::ReadWrite, bool EmitIR=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a24a8bf11a7b9112db6517027fcd834e8">assignSPIRVTypeToVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a> and <a href="#a7712aacb3f4a1a860a15ca4de83e6a9f">getOrCreateSPIRVType</a>.</p>


<p>Referenced by <a href="#affb04c244423615aa0df24ee36f2de20">buildConstantInt</a>.</p>

</div>
</div>

### assignVectTypeToVReg() {#a29a63a69f9d2a425a5fbef3e0104399e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::assignVectTypeToVReg (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * BaseType, unsigned NumElements, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a24a8bf11a7b9112db6517027fcd834e8">assignSPIRVTypeToVReg</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="#acd545bc376f8f5880178094a2d165476">getOrCreateSPIRVVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### buildConstantFP() {#a6aee777d2869b23ba59b88b9ceb32cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::buildConstantFP (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2426fcc21a9819b2f48f2f7db8a23844">llvm::addNumImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="#a24a8bf11a7b9112db6517027fcd834e8">assignSPIRVTypeToVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="#a7712aacb3f4a1a860a15ca4de83e6a9f">getOrCreateSPIRVType</a>, <a href="#afa7b871b453a7e248c0231fb9550e1d7">getScalarOrVectorBitWidth</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>.</p>

</div>
</div>

### buildConstantInt() {#affb04c244423615aa0df24ee36f2de20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::buildConstantInt (uint64_t Val, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, bool EmitIR=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool ZeroAsNull=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2426fcc21a9819b2f48f2f7db8a23844">llvm::addNumImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa66e13122dec2a32f7d1b1f7240048e2">assignTypeToVReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="#afa7b871b453a7e248c0231fb9550e1d7">getScalarOrVectorBitWidth</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4bea99b3e688d30239a66e3d1f972d6a">llvm::buildConstantIntReg32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a813af4f625c1b136c991637d08bf9087">llvm::buildSelectInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a> and <a href="#acbccd3fb66e9075690f45dea7440cf9e">getOrCreateOpTypeCoopMatr</a>.</p>

</div>
</div>

### buildConstantSampler() {#a4280c0cdf83d31309a8ad8d0d6815e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::buildConstantSampler (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Res, unsigned AddrMode, unsigned Param, unsigned FilerMode, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5c77792a06583e0fe7a0379ad94a2809">llvm::MachineRegisterInfo::createVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="#a7712aacb3f4a1a860a15ca4de83e6a9f">getOrCreateSPIRVType</a>, <a href="#a8f17d3e92f855f675577a021e9bc2a35">getOrCreateSPIRVTypeByName</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a>.</p>

</div>
</div>

### buildGlobalVariable() {#a881c9e75128e7e943b6d8f33606ccc74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::buildGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * BaseType, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, SPIRV::StorageClass::StorageClass Storage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Init, bool IsConst, bool HasLinkageTy, SPIRV::LinkageType::LinkageType LinkageType, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, bool IsInstSelector)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="#a9c12a8c76f90eef79dc4a985b0007503">addGlobalObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="#a24a8bf11a7b9112db6517027fcd834e8">assignSPIRVTypeToVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae32b6e2213ad3119a124e6e0673a5898">llvm::MachineIRBuilder::buildCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a686587ed0b5b8437aa621630cf56d147">llvm::buildOpDecorate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a01f1b2c1fbaec02e4f0d0af133830ca6">llvm::buildOpName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec2c920f97cffa508fee51ee5e722056">llvm::buildOpSpirvDecorations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a115ac0121663aa8365e095d095d0c633">llvm::GlobalObject::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#aef569d822dbf572ae71954d6831ce8a9">llvm::GlobalObject::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="#a5b040ee6ba795930a71373a06b8dd8c7">getPointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5035b6aeddaebb56d028b974f1a3679d">llvm::getSpirvBuiltInIdByName</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a> and <a href="/web-llvm/docs/api/structs/llvm/maybealign/#a06846474be3ab85f8d30c388faf3b116">llvm::MaybeAlign::valueOrOne</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a191e4c250748ed5043795f6bf3caf4e9">llvm::buildBuiltinVariableLoad</a> and <a href="#a0d65d879a707f0fcaa221e60be3a1a54">getOrCreateGlobalVariableWithBinding</a>.</p>

</div>
</div>

### find() {#abf51033e8bd031899d7e51435b78bb5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SPIRVGlobalRegistry::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>.</p>

</div>
</div>

### find() {#a53ff93727348b66a7857b15361ccad15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SPIRVGlobalRegistry::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### find() {#a9f23d16abbebbb81a2670e5bfc79eb20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SPIRVGlobalRegistry::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### find() {#a87ccf83f80c94783102715e56ef50082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SPIRVGlobalRegistry::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### findAssignPtrTypeInstr() {#af5f6ee60206f6ab5be7346e8125c3327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * llvm::SPIRVGlobalRegistry::findAssignPtrTypeInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Referenced by <a href="#ab6f6cbbfa318b48e44bd1d86a483b05a">updateIfExistAssignPtrTypeInstr</a>.</p>

</div>
</div>

### findDeducedCompositeType() {#a3aa9ba7d1e6752aad26fa2756d5701c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::SPIRVGlobalRegistry::findDeducedCompositeType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Referenced by <a href="#ad66b2a904c889bc1fab75ac287adb5d4">getDeducedGlobalValueType</a>.</p>

</div>
</div>

### findDeducedElementType() {#af010c154d556626f5516148c1a7ed57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::SPIRVGlobalRegistry::findDeducedElementType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#a2620de54f960e5950d1135d96f55f48d">getAtomicElemTy</a>, <a href="#ad66b2a904c889bc1fab75ac287adb5d4">getDeducedGlobalValueType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#ac2f8a243eec640b2ebf8e022d57c9411">getFunctionPointerElemType</a> and <a href="#a7ea813b70176abfec916e721ae8570f3">updateIfExistDeducedElementType</a>.</p>

</div>
</div>

### findMutated() {#a928d32be153c2a7382697834cb0b7910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::SPIRVGlobalRegistry::findMutated (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#aff18d7e34536cf38b7a43d7c42fa743c">restoreMutatedType</a>.</p>

</div>
</div>

### findReturnType() {#a06724e2fb3d99c573396f9e6e97bf372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TypedPointerType * llvm::SPIRVGlobalRegistry::findReturnType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * ArgF)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### findValueAttrs() {#a8983f2f2201e62922443e9571b3d05a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SPIRVGlobalRegistry::findValueAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Key, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; Ty, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### getBound() {#a1400c803160f702d9476c0610073a4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SPIRVGlobalRegistry::getBound ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### getDeducedGlobalValueType() {#ad66b2a904c889bc1fab75ac287adb5d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::SPIRVGlobalRegistry::getDeducedGlobalValueType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * Global)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>References <a href="#a3aa9ba7d1e6752aad26fa2756d5701c6">findDeducedCompositeType</a>, <a href="#af010c154d556626f5516148c1a7ed57b">findDeducedElementType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa6dce3613309b3509522a00d6569bfa4cc6684df7b4a92b1dec6fce3264fac8">llvm::Global</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>.</p>

</div>
</div>

### getForwardCalls() {#ab2637a305be723fc30c48c240afa63ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt; MachineInstr *, 8 &gt; * llvm::SPIRVGlobalRegistry::getForwardCalls (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a153ea412ff7a0ba105111155d1e16128">llvm::SmallPtrSetImpl&lt; PtrType &gt;::find</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#adb82a49ed4e56654b9200b97535f637e">validateForwardCalls</a>.</p>

</div>
</div>

### getFunctionByDefinition() {#ae28c9f37f79168be8e13396da72d35ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function * llvm::SPIRVGlobalRegistry::getFunctionByDefinition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#ae4ca2261b8b901e415fda7feac5051ea">llvm::Function::end</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#adb82a49ed4e56654b9200b97535f637e">validateForwardCalls</a>.</p>

</div>
</div>

### getFunctionDefinition() {#a6154e5a73b50ec0dbf9d6790b70da1a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr * llvm::SPIRVGlobalRegistry::getFunctionDefinition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#adc3ecee5ecd3f86b45e6779653ca10da">validateFunCall</a>.</p>

</div>
</div>

### getFunctionDefinitionByUse() {#a67f8d12aab3ebb0bf0c24bc39b2ac2b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand * llvm::SPIRVGlobalRegistry::getFunctionDefinitionByUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * Use)</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### getGlobalObject() {#a1083a23584b3d85540bd521ac67564df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::SPIRVGlobalRegistry::getGlobalObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### getNumScalarOrVectorTotalBitWidth() {#a04977130fc7ce99ac97940d9b6b3fde6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SPIRVGlobalRegistry::getNumScalarOrVectorTotalBitWidth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>.</p>


<p>Referenced by <a href="#a4760bd5cfc1e3283253a7b0d06beaf90">isBitcastCompatible</a>.</p>

</div>
</div>

### getOrCreateConsIntVector() {#a3dddf52f700258ac37fa137527588809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateConsIntVector (uint64_t Val, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, bool EmitIR=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#afa7b871b453a7e248c0231fb9550e1d7">getScalarOrVectorBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a813af4f625c1b136c991637d08bf9087">llvm::buildSelectInst</a>.</p>

</div>
</div>

### getOrCreateConstFP() {#af54e9ce01961e65d9b74fef2193a8d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateConstFP (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII, bool ZeroAsNull=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2426fcc21a9819b2f48f2f7db8a23844">llvm::addNumImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ac37cd93f2c41a818a278e99de784ba1d">llvm::APFloat::isPosZero</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getOrCreateConstInt() {#a08f607435df14840793b848f2b3c0257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateConstInt (uint64_t Val, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII, bool ZeroAsNull=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2426fcc21a9819b2f48f2f7db8a23844">llvm::addNumImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#ae5869468359515f460a588357f1737cf">getOrCreateSPIRVArrayType</a>.</p>

</div>
</div>

### getOrCreateConstIntArray() {#abab34b1cb73af8519772979270773492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateConstIntArray (uint64_t Val, size_t Num, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#ab154936bb49a215c32bdbd18254fc477">llvm::ConstantStruct::getAnon</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#aed75da684d36221f1f7b9fbf5aa3aed8">llvm::ArrayType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a1c35bd7a4fa08845607033aecc94423d">llvm::ArrayType::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#afa7b871b453a7e248c0231fb9550e1d7">getScalarOrVectorBitWidth</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a2a394517076e7dd2bdcd7dde33dfcb7d">llvm::Type::isArrayTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>.</p>

</div>
</div>

### getOrCreateConstNullPtr() {#af99db04834e1ae3fc23466a80045a4d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateConstNullPtr (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="#a24a8bf11a7b9112db6517027fcd834e8">assignSPIRVTypeToVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#af3bdf39332eb22f67b968fd688417964">typeToAddressSpace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>.</p>

</div>
</div>

### getOrCreateConstVector() {#abea0d5a07369a9502280335b276b3ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateConstVector (uint64_t Val, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII, bool ZeroAsNull=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#afa7b871b453a7e248c0231fb9550e1d7">getScalarOrVectorBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getOrCreateConstVector() {#aea5285dbe63b422dcaf313ec0fe7473d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateConstVector (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII, bool ZeroAsNull=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#afa7b871b453a7e248c0231fb9550e1d7">getScalarOrVectorBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getOrCreateGlobalVariableWithBinding() {#a0d65d879a707f0fcaa221e60be3a1a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateGlobalVariableWithBinding (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * VarType, uint32_t Set, uint32_t Binding, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 828 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a881c9e75128e7e943b6d8f33606ccc74">buildGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a686587ed0b5b8437aa621630cf56d147">llvm::buildOpDecorate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a665946cb74a98ed20ca7e0acf68d9b03">buildSpirvTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5c77792a06583e0fe7a0379ad94a2809">llvm::MachineRegisterInfo::createVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a> and <a href="#acab67f583801f5c01ee9ac2162f5e27d">getOrCreateSPIRVPointerType</a>.</p>

</div>
</div>

### getOrCreateOpTypeByOpcode() {#a69f73e1b5f8a3e376c63293408b6786e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateOpTypeByOpcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#af988c2b4f62506108843a0fdc04b43a2">llvm::MachineRegisterInfo::getUniqueVRegDef</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aedebd920fb229c558792273ecdf419f7">llvm::getNonParameterizedType</a>.</p>

</div>
</div>

### getOrCreateOpTypeCoopMatr() {#acbccd3fb66e9075690f45dea7440cf9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateOpTypeCoopMatr (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> * ExtensionType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * ElemType, uint32_t Scope, uint32_t Rows, uint32_t Columns, uint32_t Use)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="#affb04c244423615aa0df24ee36f2de20">buildConstantInt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="#acdec96f14d81b2043e31f3452e440a4b">getOrCreateSPIRVIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#af988c2b4f62506108843a0fdc04b43a2">llvm::MachineRegisterInfo::getUniqueVRegDef</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a578e0fb2076c8c2e0b0a656c26c6f7fb">llvm::getCoopMatrType</a>.</p>

</div>
</div>

### getOrCreateOpTypeDeviceEvent() {#abeddeff35f8dd231213915a6f77f0920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateOpTypeDeviceEvent (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a582210ea79057b429894c7a211153d17">llvm::SPIRV::make_descr_event</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aac0431719235a7ccda58a3df4894d130">llvm::SPIRV::lowerBuiltinType</a>.</p>

</div>
</div>

### getOrCreateOpTypeFunctionWithArgs() {#aac40b88bee839e32d4f0f860282d0fc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateOpTypeFunctionWithArgs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * RetType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * &gt; &amp; ArgTypes, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 945 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a> and <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>.</p>

</div>
</div>

### getOrCreateOpTypeImage() {#a4cd2c03c778450920cd3b53acdcb4fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateOpTypeImage (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SampledType, SPIRV::Dim::Dim Dim, uint32_t Depth, uint32_t Arrayed, uint32_t Multisampled, uint32_t Sampled, SPIRV::ImageFormat::ImageFormat ImageFormat, SPIRV::AccessQualifier::AccessQualifier AccQual)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a74c92a14f9b97ca69c697a25524e2048">llvm::SPIRV::make_descr_image</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a676a94469d462533ab86319e910ab716">llvm::getImageType</a>.</p>

</div>
</div>

### getOrCreateOpTypePipe() {#a0067190a151de0ad367e8d1e56c1016a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateOpTypePipe (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AccQual)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a140f876f57e6b084dacd0e43736d4863">llvm::SPIRV::make_descr_pipe</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#adad7d79fe6ccdc6a524ee8680b853617">llvm::getPipeType</a>.</p>

</div>
</div>

### getOrCreateOpTypeSampledImage() {#a8cdc39b963a62003cd157541feca56f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateOpTypeSampledImage (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * ImageType, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a40d954b9cf9ee8b545a78725f2549cba">llvm::MachineRegisterInfo::getVRegDef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aeb5e4e41c7dda3b942168ed881fa1d13">llvm::SPIRV::make_descr_sampled_image</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4df28b3ff57ec9b6b4dd5d7d21b77e1f">llvm::getSampledImageType</a>.</p>

</div>
</div>

### getOrCreateOpTypeSampler() {#aea914eb511a3b8ebf605c62c07e8ab44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateOpTypeSampler (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a15409264d4bd36a372e37c8d1f9e76ac">llvm::SPIRV::make_descr_sampler</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7a310ee6589ff3b9c65206f71ea32f04">llvm::getSamplerType</a>.</p>

</div>
</div>

### getOrCreateSPIRVArrayType() {#ae5869468359515f460a588357f1737cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVArrayType (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * BaseType, unsigned NumElements, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="#a08f607435df14840793b848f2b3c0257">getOrCreateConstInt</a>, <a href="#acdec96f14d81b2043e31f3452e440a4b">getOrCreateSPIRVIntegerType</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getOrCreateSPIRVBoolType() {#a3d6978ae20178c8f9414ff980fd4e3b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVBoolType (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1530 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a> and <a href="#a7712aacb3f4a1a860a15ca4de83e6a9f">getOrCreateSPIRVType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>.</p>

</div>
</div>

### getOrCreateSPIRVBoolType() {#a8bdd4c60453b10074293349820f8bdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVBoolType (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getOrCreateSPIRVFloatType() {#a4b607e6993b349291749a0e177c52fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVFloatType (unsigned BitWidth, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1509 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acb145f988329d1d621f73abcafea21d8">llvm::Type::getDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae550f2e9436b395b614b4377ba27007f">llvm::Type::getHalfTy</a>, <a href="#a7712aacb3f4a1a860a15ca4de83e6a9f">getOrCreateSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#a224cd42d0c6c318274c1696e74b63b51">assignFloatTypeToVReg</a>.</p>

</div>
</div>

### getOrCreateSPIRVIntegerType() {#acdec96f14d81b2043e31f3452e440a4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVIntegerType (unsigned BitWidth, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a> and <a href="#a7712aacb3f4a1a860a15ca4de83e6a9f">getOrCreateSPIRVType</a>.</p>


<p>Referenced by <a href="#a88f2b05d25ba2010b0c306071730fe01">assignIntTypeToVReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4bea99b3e688d30239a66e3d1f972d6a">llvm::buildConstantIntReg32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>, <a href="#acbccd3fb66e9075690f45dea7440cf9e">getOrCreateOpTypeCoopMatr</a>, <a href="#ae5869468359515f460a588357f1737cf">getOrCreateSPIRVArrayType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>.</p>

</div>
</div>

### getOrCreateSPIRVIntegerType() {#a18fd6615429a508c934bc1cff0f49319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVIntegerType (unsigned BitWidth, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#a7712aacb3f4a1a860a15ca4de83e6a9f">getOrCreateSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getOrCreateSPIRVPointerType() {#acab67f583801f5c01ee9ac2162f5e27d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVPointerType (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * BaseType, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, SPIRV::StorageClass::StorageClass SClass=SPIRV::StorageClass::Function)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#ad0b317acb44e242226165a34d550702d">llvm::TypedPointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acfe60198abd7ecf64270c987689c6c1b">llvm::MachineIRBuilder::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a430daa77692b7b25f93a72d83e51964f">llvm::MachineIRBuilder::getInsertPt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ac8f6c5b9180bd630c92e1126877d0b08">llvm::MachineIRBuilder::getMBB</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a35384c47e5ca9690216b1aa8fed5a8c9">llvm::MachineIRBuilder::getTII</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4f3d8bc8938733ce077d2fe798d3a49a">llvm::storageClassToAddressSpace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a191e4c250748ed5043795f6bf3caf4e9">llvm::buildBuiltinVariableLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#af8d1a82d797c4263012ca5d7675c4c19">createNewPtrType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ab5e88a19352e7dce1b0115f5e6b37b47">getArgSPIRVType</a>, <a href="#a0d65d879a707f0fcaa221e60be3a1a54">getOrCreateGlobalVariableWithBinding</a>, <a href="#a8bde676c37078e2ffb74ce2814f11048">getOrCreateSPIRVPointerType</a>, <a href="#a8f17d3e92f855f675577a021e9bc2a35">getOrCreateSPIRVTypeByName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a5457cbda7e9b1866c1c16af5ac330273">insertBitcasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a5ab01ee14799ff74e4ff5e6c5ce8d50c">validateLifetimeStart</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ac6789e73101dcf0d746feb6343f4aae6">validatePtrUnwrapStructField</a>.</p>

</div>
</div>

### getOrCreateSPIRVPointerType() {#a8bde676c37078e2ffb74ce2814f11048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVPointerType (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * BaseType, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII, SPIRV::StorageClass::StorageClass SClass=SPIRV::StorageClass::Function)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1619 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#acab67f583801f5c01ee9ac2162f5e27d">getOrCreateSPIRVPointerType</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getOrCreateSPIRVType() {#a7712aacb3f4a1a860a15ca4de83e6a9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Type, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AQ=SPIRV::AccessQualifier::ReadWrite, bool EmitIR=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21b1f2d0effa0506f01cb146823de6a2">llvm::getPointerAddressSpace</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7db94a9fa353cc7a297edd4e8601b184">llvm::isPointerTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c2bc1b1bb26faf847a721e6eea38f97">llvm::isSpecialOpaqueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f35bb3287437ddd0f4c1fc432b2c7d9">llvm::isTypedPointerTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a15fe5c2fae3f394855b6290a19a88f59">llvm::isTypedPointerWrapper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a>, <a href="#aa66e13122dec2a32f7d1b1f7240048e2">assignTypeToVReg</a>, <a href="#a6aee777d2869b23ba59b88b9ceb32cfe">buildConstantFP</a>, <a href="#a4280c0cdf83d31309a8ad8d0d6815e66">buildConstantSampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#af8d1a82d797c4263012ca5d7675c4c19">createNewPtrType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a787d9beda2fd4b52be04a225f89e0270">llvm::createVirtualRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ab5e88a19352e7dce1b0115f5e6b37b47">getArgSPIRVType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a578e0fb2076c8c2e0b0a656c26c6f7fb">llvm::getCoopMatrType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a676a94469d462533ab86319e910ab716">llvm::getImageType</a>, <a href="#a3d6978ae20178c8f9414ff980fd4e3b2">getOrCreateSPIRVBoolType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadf38ec8e97afd05668e524d9ab0e60d">llvm::getOrCreateSPIRVDeviceEventPointer</a>, <a href="#a4b607e6993b349291749a0e177c52fbb">getOrCreateSPIRVFloatType</a>, <a href="#a18fd6615429a508c934bc1cff0f49319">getOrCreateSPIRVIntegerType</a>, <a href="#acdec96f14d81b2043e31f3452e440a4b">getOrCreateSPIRVIntegerType</a>, <a href="#a8f17d3e92f855f675577a021e9bc2a35">getOrCreateSPIRVTypeByName</a>, <a href="#acd545bc376f8f5880178094a2d165476">getOrCreateSPIRVVectorType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a2222b2a89839a157c1b2992743effe">llvm::insertAssignInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a5457cbda7e9b1866c1c16af5ac330273">insertBitcasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d4f8e3bb109dd110769f33e9c00e89f">llvm::setRegClassType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a5ab01ee14799ff74e4ff5e6c5ce8d50c">validateLifetimeStart</a>.</p>

</div>
</div>

### getOrCreateSPIRVType() {#a8f224f7bdbbd3667e44b205c571b30d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVType (unsigned BitWidth, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII, unsigned SPIRVOPcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LLVMTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getOrCreateSPIRVTypeByName() {#a8f17d3e92f855f675577a021e9bc2a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVTypeByName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeStr, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, SPIRV::StorageClass::StorageClass SC=SPIRV::StorageClass::Function, SPIRV::AccessQualifier::AccessQualifier AQ=SPIRV::AccessQualifier::ReadWrite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1419 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a14180977794bfc2a37dbffeef3ca20de">llvm::StringRef::consume_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a120dbb8d0a1ad4437456001a302a1da7">llvm::MachineIRBuilder::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="#acab67f583801f5c01ee9ac2162f5e27d">getOrCreateSPIRVPointerType</a>, <a href="#a7712aacb3f4a1a860a15ca4de83e6a9f">getOrCreateSPIRVType</a>, <a href="#acd545bc376f8f5880178094a2d165476">getOrCreateSPIRVVectorType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac543427f78c6934a75c29dfe91a5070f">llvm::hasBuiltinTypePrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1d439cfb41770f7499b28e4ac49280d">llvm::parseBasicTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a9249200d14424808c822103928fe7fdc">llvm::SPIRV::parseBuiltinTypeNameToTargetExtType</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#a4280c0cdf83d31309a8ad8d0d6815e66">buildConstantSampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748bbd916eb5b48b009f8ee2e6a6afc9">llvm::generateAsyncCopy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a>.</p>

</div>
</div>

### getOrCreateSPIRVVectorType() {#acd545bc376f8f5880178094a2d165476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVVectorType (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * BaseType, unsigned NumElements, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1550 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="#a7712aacb3f4a1a860a15ca4de83e6a9f">getOrCreateSPIRVType</a> and <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a>.</p>


<p>Referenced by <a href="#a29a63a69f9d2a425a5fbef3e0104399e">assignVectTypeToVReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>, <a href="#a8f17d3e92f855f675577a021e9bc2a35">getOrCreateSPIRVTypeByName</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>.</p>

</div>
</div>

### getOrCreateSPIRVVectorType() {#a4791c0c5f18aaa298445226456f15547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSPIRVVectorType (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * BaseType, unsigned NumElements, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getOrCreateUndef() {#a35c2ba2ad91e2fe027f8f64e92a7502f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateUndef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1626 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a24a8bf11a7b9112db6517027fcd834e8">assignSPIRVTypeToVReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="#a7685ee8f0cb0ee9e255a169a8765e54f">getSPIRVTypeID</a>, <a href="#a41f12865aaeb736dd52ec49bd8955f95">getTypeForSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getPointeeType() {#a6d986da977a884fc79751da79c4e6f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getPointeeType (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * PtrType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3abab01a19c99b6700cc0aadde16edc2">llvm::generateICarryBorrowInst</a>, <a href="#a8c80c43434acec4d262a13013d993dd3">getPointeeTypeOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a5ab01ee14799ff74e4ff5e6c5ce8d50c">validateLifetimeStart</a>.</p>

</div>
</div>

### getPointeeTypeOp() {#a8c80c43434acec4d262a13013d993dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SPIRVGlobalRegistry::getPointeeTypeOp (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> PtrReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="#a6d986da977a884fc79751da79c4e6f84">getPointeeType</a> and <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>.</p>

</div>
</div>

### getPointerSize() {#a5b040ee6ba795930a71373a06b8dd8c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SPIRVGlobalRegistry::getPointerSize ()</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a191e4c250748ed5043795f6bf3caf4e9">llvm::buildBuiltinVariableLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="#a881c9e75128e7e943b6d8f33606ccc74">buildGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a> and <a href="#ad864cdbeb2b8c6a7cf87d8141abc5735">getRegType</a>.</p>

</div>
</div>

### getPointerStorageClass() {#aea90d9f0d1cf03f79d678050beaf922e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRV::StorageClass::StorageClass SPIRVGlobalRegistry::getPointerStorageClass (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aea90d9f0d1cf03f79d678050beaf922e">getPointerStorageClass</a> and <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa24e8200fb460e1454ce71de5921fc7b">llvm::buildAtomicLoadInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1e86010cc9381660c973391ab0034e00">llvm::buildAtomicStoreInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92b7677cd4ee158a68f41214d43bfae4">llvm::buildMemSemanticsReg</a>, <a href="#aea90d9f0d1cf03f79d678050beaf922e">getPointerStorageClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>.</p>

</div>
</div>

### getPointerStorageClass() {#a8545705eb22c4e30c0868a578d745e8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRV::StorageClass::StorageClass SPIRVGlobalRegistry::getPointerStorageClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getRegClass() {#ab6e454de3dfa112cc7e30219ac7298cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * SPIRVGlobalRegistry::getRegClass (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1654 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acec38968fb25d9da84d9d606eca35d7d">llvm::buildAtomicRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a8dcc4e0c146cff251e73a2a59123683b">buildOpBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp/#a3b8f2c8dafaf2b1007b8661546ce5aca">convertPtrToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#aec7962818f16c459fa68050e1dab39ff">createNewIdReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c02a62be344861d8a7598e08d1021b6">llvm::createVirtualRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a2222b2a89839a157c1b2992743effe">llvm::insertAssignInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d5aaa74bb3796fbcd85861222730ab">llvm::processInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eac561775786f17cc1201349328bf5d">llvm::setRegClassIfNull</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3f9bac9bdd3f5fc36a5f5e13480d4a">llvm::setRegClassType</a>.</p>

</div>
</div>

### getRegType() {#ad864cdbeb2b8c6a7cf87d8141abc5735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT SPIRVGlobalRegistry::getRegType (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1680 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a4b49090437c0021f09fa86c3965bb855">getAS</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a5b040ee6ba795930a71373a06b8dd8c7">getPointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#afa7b871b453a7e248c0231fb9550e1d7">getScalarOrVectorBitWidth</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#aec7962818f16c459fa68050e1dab39ff">createNewIdReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c02a62be344861d8a7598e08d1021b6">llvm::createVirtualRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3f9bac9bdd3f5fc36a5f5e13480d4a">llvm::setRegClassType</a>.</p>

</div>
</div>

### getResultType() {#a0abb9ee0d1c0872f76cea9d9b6c1396e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getResultType (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae7c6fd268e11e2eb6e8d13ed32b1820c">llvm::getVRegDef</a>.</p>

</div>
</div>

### getScalarOrVectorBitWidth() {#afa7b871b453a7e248c0231fb9550e1d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SPIRVGlobalRegistry::getScalarOrVectorBitWidth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a6aee777d2869b23ba59b88b9ceb32cfe">buildConstantFP</a>, <a href="#affb04c244423615aa0df24ee36f2de20">buildConstantInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a813af4f625c1b136c991637d08bf9087">llvm::buildSelectInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4bf8d79fb617413b09980966a60e5a">llvm::generateBuiltinVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a63b94467b9a18c31a4ee6d6ec4c34425">llvm::generateWaveInst</a>, <a href="#a3dddf52f700258ac37fa137527588809">getOrCreateConsIntVector</a>, <a href="#abab34b1cb73af8519772979270773492">getOrCreateConstIntArray</a>, <a href="#aea5285dbe63b422dcaf313ec0fe7473d">getOrCreateConstVector</a>, <a href="#abea0d5a07369a9502280335b276b3ccb">getOrCreateConstVector</a>, <a href="#ad864cdbeb2b8c6a7cf87d8141abc5735">getRegType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>.</p>

</div>
</div>

### getScalarOrVectorComponentCount() {#a48be4a06ef828d5cfa75a2447fe95202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SPIRVGlobalRegistry::getScalarOrVectorComponentCount (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a48be4a06ef828d5cfa75a2447fe95202">getScalarOrVectorComponentCount</a> and <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a884a65fc47e7cf521d37505e1548e9ca">llvm::generateConvertInst</a>, <a href="#a48be4a06ef828d5cfa75a2447fe95202">getScalarOrVectorComponentCount</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>.</p>

</div>
</div>

### getScalarOrVectorComponentCount() {#a3d67d14155aa4291adf0aa842ef5e3ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SPIRVGlobalRegistry::getScalarOrVectorComponentCount (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getScalarOrVectorComponentType() {#a9d47327f9572ae6739e9a75d52c71dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getScalarOrVectorComponentType (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a9d47327f9572ae6739e9a75d52c71dc1">getScalarOrVectorComponentType</a> and <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>.</p>


<p>Referenced by <a href="#a9d47327f9572ae6739e9a75d52c71dc1">getScalarOrVectorComponentType</a>.</p>

</div>
</div>

### getScalarOrVectorComponentType() {#a625767127423cea458550a1505f80d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getScalarOrVectorComponentType (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a> and <a href="#ab91827a04a8d97aa04d5fd0d86ec790e">isScalarOrVectorOfType</a>.</p>

</div>
</div>

### getSPIRVTypeForVReg() {#a05b34a70cde1fcbdcb0767cf218c1752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getSPIRVTypeForVReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>Reference <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="#a881c9e75128e7e943b6d8f33606ccc74">buildGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a8dcc4e0c146cff251e73a2a59123683b">buildOpBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#aec7962818f16c459fa68050e1dab39ff">createNewIdReg</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d2d83de91f5be342b9beeb36a6e8c2">llvm::generateCoopMatrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515c6055dea0a74d18c4549511921e8c">llvm::generateDotOrFMulInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3abab01a19c99b6700cc0aadde16edc2">llvm::generateICarryBorrowInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa2920e81d3e11168548e83a60ddaaf">llvm::generateImageMiscQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa258d22bc5ca54e36dc15a8c3e724e52">llvm::generateIntelSubgroupsInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>, <a href="#a04977130fc7ce99ac97940d9b6b3fde6">getNumScalarOrVectorTotalBitWidth</a>, <a href="#abab34b1cb73af8519772979270773492">getOrCreateConstIntArray</a>, <a href="#aac40b88bee839e32d4f0f860282d0fc4">getOrCreateOpTypeFunctionWithArgs</a>, <a href="#ae5869468359515f460a588357f1737cf">getOrCreateSPIRVArrayType</a>, <a href="#a8bdd4c60453b10074293349820f8bdcf">getOrCreateSPIRVBoolType</a>, <a href="#acab67f583801f5c01ee9ac2162f5e27d">getOrCreateSPIRVPointerType</a>, <a href="#a7712aacb3f4a1a860a15ca4de83e6a9f">getOrCreateSPIRVType</a>, <a href="#a8f224f7bdbbd3667e44b205c571b30d2">getOrCreateSPIRVType</a>, <a href="#a4791c0c5f18aaa298445226456f15547">getOrCreateSPIRVVectorType</a>, <a href="#a6d986da977a884fc79751da79c4e6f84">getPointeeType</a>, <a href="#a8c80c43434acec4d262a13013d993dd3">getPointeeTypeOp</a>, <a href="#aea90d9f0d1cf03f79d678050beaf922e">getPointerStorageClass</a>, <a href="#ab6e454de3dfa112cc7e30219ac7298cd">getRegClass</a>, <a href="#ad864cdbeb2b8c6a7cf87d8141abc5735">getRegType</a>, <a href="#a0abb9ee0d1c0872f76cea9d9b6c1396e">getResultType</a>, <a href="#afa7b871b453a7e248c0231fb9550e1d7">getScalarOrVectorBitWidth</a>, <a href="#a48be4a06ef828d5cfa75a2447fe95202">getScalarOrVectorComponentCount</a>, <a href="#a9d47327f9572ae6739e9a75d52c71dc1">getScalarOrVectorComponentType</a>, <a href="#a625767127423cea458550a1505f80d39">getScalarOrVectorComponentType</a>, <a href="#aa04e30da4fa3f1602a4728cd88c62e7e">hasSPIRVTypeForVReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a5457cbda7e9b1866c1c16af5ac330273">insertBitcasts</a>, <a href="#a7ec44625f429790b5ed7e3f67a70fdab">isScalarOfType</a>, <a href="#ab91827a04a8d97aa04d5fd0d86ec790e">isScalarOrVectorOfType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aa4175e495404e2fa9c8236262d7aae09">llvm::SPIRV::lowerBuiltin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d5aaa74bb3796fbcd85861222730ab">llvm::processInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#af352e338e2b9a8cd58a97aca55d421e4">processNewInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>, <a href="#afff378412481afe6008a257ca9afade7">retrieveScalarOrVectorIntType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eac561775786f17cc1201349328bf5d">llvm::setRegClassIfNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad6611e7ee084ecf0ef7b23ca25b50db0">validateAccessChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad7fdf3fa9ec7e0c43067799e690529c1">validateFunCallMachineDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#abbe8c4ff227aafd9e016eeb143490bcc">validateGroupWaitEventsPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a5ab01ee14799ff74e4ff5e6c5ce8d50c">validateLifetimeStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#af60628c2329ed3a894bf3d9fc1c5ec51">validatePtrTypes</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ac6789e73101dcf0d746feb6343f4aae6">validatePtrUnwrapStructField</a>.</p>

</div>
</div>

### getSPIRVTypeID() {#a7685ee8f0cb0ee9e255a169a8765e54f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getSPIRVTypeID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpirvType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa3b9fba7fd848bb37e43040b66f6c051">llvm::MachineInstr::defs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3949f157e1034f6cb5d16ad708059aa3">llvm::MachineInstr::uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17fda1a191d8f69587355e32c5f15618">llvm::buildAtomicFlagInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abaf31a84826d881e8cebb369b37c6ff1">llvm::buildAtomicFloatingRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa24e8200fb460e1454ce71de5921fc7b">llvm::buildAtomicLoadInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acec38968fb25d9da84d9d606eca35d7d">llvm::buildAtomicRMWInst</a>, <a href="#a6aee777d2869b23ba59b88b9ceb32cfe">buildConstantFP</a>, <a href="#affb04c244423615aa0df24ee36f2de20">buildConstantInt</a>, <a href="#a4280c0cdf83d31309a8ad8d0d6815e66">buildConstantSampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="#a881c9e75128e7e943b6d8f33606ccc74">buildGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a8dcc4e0c146cff251e73a2a59123683b">buildOpBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a2abcc0dade6e762f2145f49e3158a71c">doInsertBitcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748bbd916eb5b48b009f8ee2e6a6afc9">llvm::generateAsyncCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84c389b358e787b743a7baec94986bff">llvm::generateAtomicInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14afcdbeb1f13ff775293bb6f0efd3c2">llvm::generateConstructInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a884a65fc47e7cf521d37505e1548e9ca">llvm::generateConvertInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d2d83de91f5be342b9beeb36a6e8c2">llvm::generateCoopMatrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515c6055dea0a74d18c4549511921e8c">llvm::generateDotOrFMulInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e92ead0d298bfaef08370c3877e05c9">llvm::generateEnqueueInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aebcace45f75d5389e0c72effb52530b6">llvm::generateExtInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a610c7b58032f5eac1b06aa0c66cadb6a">llvm::generateGroupUniformInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3abab01a19c99b6700cc0aadde16edc2">llvm::generateICarryBorrowInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa2920e81d3e11168548e83a60ddaaf">llvm::generateImageMiscQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa258d22bc5ca54e36dc15a8c3e724e52">llvm::generateIntelSubgroupsInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9c060a884e9461f06d7601681d2bcf">llvm::generateKernelClockInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fc9e18e3a0aeb8c6426eae57a1ab61e">llvm::generateLoadStoreInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfd0973871508362181539a1e103e0ed">llvm::generateRelationalInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabf50e80c80c98fd130ff1cb70553742">llvm::generateSpecConstantInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab25d01b38cf3d0b9e22fe06c673243d6">llvm::generateVectorLoadStoreInst</a>, <a href="#af54e9ce01961e65d9b74fef2193a8d95">getOrCreateConstFP</a>, <a href="#a08f607435df14840793b848f2b3c0257">getOrCreateConstInt</a>, <a href="#af99db04834e1ae3fc23466a80045a4d9">getOrCreateConstNullPtr</a>, <a href="#acbccd3fb66e9075690f45dea7440cf9e">getOrCreateOpTypeCoopMatr</a>, <a href="#aac40b88bee839e32d4f0f860282d0fc4">getOrCreateOpTypeFunctionWithArgs</a>, <a href="#a4cd2c03c778450920cd3b53acdcb4fba">getOrCreateOpTypeImage</a>, <a href="#a8cdc39b963a62003cd157541feca56f6">getOrCreateOpTypeSampledImage</a>, <a href="#ae5869468359515f460a588357f1737cf">getOrCreateSPIRVArrayType</a>, <a href="#a8bdd4c60453b10074293349820f8bdcf">getOrCreateSPIRVBoolType</a>, <a href="#acab67f583801f5c01ee9ac2162f5e27d">getOrCreateSPIRVPointerType</a>, <a href="#a8f224f7bdbbd3667e44b205c571b30d2">getOrCreateSPIRVType</a>, <a href="#a4791c0c5f18aaa298445226456f15547">getOrCreateSPIRVVectorType</a>, <a href="#a35c2ba2ad91e2fe027f8f64e92a7502f">getOrCreateUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a2222b2a89839a157c1b2992743effe">llvm::insertAssignInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a> and <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aac0431719235a7ccda58a3df4894d130">llvm::SPIRV::lowerBuiltinType</a>.</p>

</div>
</div>

### getTypeForSPIRVType() {#a41f12865aaeb736dd52ec49bd8955f95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Type * llvm::SPIRVGlobalRegistry::getTypeForSPIRVType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Ty)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="#affb04c244423615aa0df24ee36f2de20">buildConstantInt</a>, <a href="#a4280c0cdf83d31309a8ad8d0d6815e66">buildConstantSampler</a>, <a href="#a881c9e75128e7e943b6d8f33606ccc74">buildGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ad57fd622877d2a50e1a312be6b4a409d">fixFunctionTypeIfPtrArgs</a>, <a href="#a3dddf52f700258ac37fa137527588809">getOrCreateConsIntVector</a>, <a href="#abab34b1cb73af8519772979270773492">getOrCreateConstIntArray</a>, <a href="#af99db04834e1ae3fc23466a80045a4d9">getOrCreateConstNullPtr</a>, <a href="#aea5285dbe63b422dcaf313ec0fe7473d">getOrCreateConstVector</a>, <a href="#abea0d5a07369a9502280335b276b3ccb">getOrCreateConstVector</a>, <a href="#ae5869468359515f460a588357f1737cf">getOrCreateSPIRVArrayType</a>, <a href="#acab67f583801f5c01ee9ac2162f5e27d">getOrCreateSPIRVPointerType</a>, <a href="#a4791c0c5f18aaa298445226456f15547">getOrCreateSPIRVVectorType</a>, <a href="#acd545bc376f8f5880178094a2d165476">getOrCreateSPIRVVectorType</a>, <a href="#a35c2ba2ad91e2fe027f8f64e92a7502f">getOrCreateUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad7fdf3fa9ec7e0c43067799e690529c1">validateFunCallMachineDef</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#af60628c2329ed3a894bf3d9fc1c5ec51">validatePtrTypes</a>.</p>

</div>
</div>

### hasConstFunPtr() {#a6979fe82f502c4648493263f37d136fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SPIRVGlobalRegistry::hasConstFunPtr ()</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### hasSPIRVTypeForVReg() {#aa04e30da4fa3f1602a4728cd88c62e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SPIRVGlobalRegistry::hasSPIRVTypeForVReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>.</p>

</div>
</div>

### invalidateMachineInstr() {#a72f93953efc4bafcbb048af4dd6fdaaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVGlobalRegistry::invalidateMachineInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isAggregateType() {#ab4143059b879c9d0fef2e028e20dddb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SPIRVGlobalRegistry::isAggregateType (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type)</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### isBitcastCompatible() {#a4760bd5cfc1e3283253a7b0d06beaf90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVGlobalRegistry::isBitcastCompatible (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="#a04977130fc7ce99ac97940d9b6b3fde6">getNumScalarOrVectorTotalBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a> and <a href="#afff378412481afe6008a257ca9afade7">retrieveScalarOrVectorIntType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a8dcc4e0c146cff251e73a2a59123683b">buildOpBitcast</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#af60628c2329ed3a894bf3d9fc1c5ec51">validatePtrTypes</a>.</p>

</div>
</div>

### isScalarOfType() {#a7ec44625f429790b5ed7e3f67a70fdab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVGlobalRegistry::isScalarOfType (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, unsigned TypeOpcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>.</p>

</div>
</div>

### isScalarOrVectorOfType() {#ab91827a04a8d97aa04d5fd0d86ec790e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVGlobalRegistry::isScalarOrVectorOfType (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, unsigned TypeOpcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a> and <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a884a65fc47e7cf521d37505e1548e9ca">llvm::generateConvertInst</a> and <a href="#a625767127423cea458550a1505f80d39">getScalarOrVectorComponentType</a>.</p>

</div>
</div>

### isScalarOrVectorSigned() {#a4eb4dcdccf96e4fd24c31db70617c00e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVGlobalRegistry::isScalarOrVectorSigned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a> and <a href="#afff378412481afe6008a257ca9afade7">retrieveScalarOrVectorIntType</a>.</p>

</div>
</div>

### recordFunctionDefinition() {#a00d35e3f57b5ac9407316ad4161c83e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::recordFunctionDefinition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>.</p>

</div>
</div>

### recordFunctionPointer() {#aadfb369a3dd5eaa5f5b443c7c8b83ede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::recordFunctionPointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### retrieveScalarOrVectorIntType() {#afff378412481afe6008a257ca9afade7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SPIRVType * SPIRVGlobalRegistry::retrieveScalarOrVectorIntType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>


<p>Reference <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>.</p>


<p>Referenced by <a href="#a4760bd5cfc1e3283253a7b0d06beaf90">isBitcastCompatible</a> and <a href="#a4eb4dcdccf96e4fd24c31db70617c00e">isScalarOrVectorSigned</a>.</p>

</div>
</div>

### setBound() {#a280ad3b23c2e3ffd2aa810afdaac12b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::setBound (unsigned V)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### setCurrentFunc() {#abe2132b08f73f4e1715fbefbddfacb55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction * llvm::SPIRVGlobalRegistry::setCurrentFunc (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="#a7692d43a010892d4aeb5e6e81a083b3e">CurMF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad7fdf3fa9ec7e0c43067799e690529c1">validateFunCallMachineDef</a>.</p>

</div>
</div>

### updateIfExistAssignPtrTypeInstr() {#ab6f6cbbfa318b48e44bd1d86a483b05a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::updateIfExistAssignPtrTypeInstr (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OldVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewVal, bool DeleteOld)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="#af5f6ee60206f6ab5be7346e8125c3327">findAssignPtrTypeInstr</a>.</p>

</div>
</div>

### updateIfExistDeducedElementType() {#a7ea813b70176abfec916e721ae8570f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVGlobalRegistry::updateIfExistDeducedElementType (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OldVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewVal, bool DeleteOld)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Reference <a href="#af010c154d556626f5516148c1a7ed57b">findDeducedElementType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### adjustIntTypeByWidth() {#a7380d60aeab7bd7c320dcc6983c63e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Type * SPIRVGlobalRegistry::adjustIntTypeByWidth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 984 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### adjustOpTypeIntWidth() {#a5b5e4e68613771e719ab0ec92dc91b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SPIRVGlobalRegistry::adjustOpTypeIntWidth (unsigned Width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### checkSpecialInstr() {#adb0c1292851b9e5fcb97c69b6e520905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr * SPIRVGlobalRegistry::checkSpecialInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2bf0a77e1bc83d6aed4daca21b16a813">SPIRV::SpecialTypeDescriptor</a> &amp; TD, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### createOpType() {#a3c1e2308f49caa30613fdd66ea523f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::createOpType (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *(<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp;)&gt; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### createSPIRVType() {#ab3ad075083a50745fb933b73688fedf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::createSPIRVType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Type, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AQ=SPIRV::AccessQualifier::ReadWrite, bool EmitIR=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### findSPIRVType() {#a4088abadea295426d4597f021b713cac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::findSPIRVType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, SPIRV::AccessQualifier::AccessQualifier accessQual=SPIRV::AccessQualifier::ReadWrite, bool EmitIR=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 957 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### finishCreatingSPIRVType() {#ad6f1ebc75bb9daa9e67a9a0a20f7acef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::finishCreatingSPIRVType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LLVMTy, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpirvType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOpTypeArray() {#a22f51d642ceeb354a0231a8d33195101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOpTypeArray (uint32_t NumElems, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * ElemType, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, bool EmitIR=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOpTypeBool() {#a8ecbc449274806f96febe11a462bfcfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOpTypeBool (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOpTypeFloat() {#a3ef2b8363588a3576e6154e834842034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOpTypeFloat (uint32_t Width, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOpTypeForwardPointer() {#a5b674d651ac3e4016eeb5a26939666f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOpTypeForwardPointer (SPIRV::StorageClass::StorageClass SC, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 925 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOpTypeFunction() {#a34bb0d8b9e700802f8655fa9732b5e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOpTypeFunction (<a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * RetType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * &gt; &amp; ArgTypes, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 934 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOpTypeInt() {#a284aa95f7a27c3efdf9178a22f8aadcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOpTypeInt (unsigned Width, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, bool IsSigned=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOpTypeOpaque() {#ac496f60fc469db05370eaceb9fda4517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOpTypeOpaque (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 868 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOpTypePointer() {#a6973e6b9843f2c8a2bf32a4721cf27ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOpTypePointer (SPIRV::StorageClass::StorageClass SC, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * ElemType, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 911 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOpTypeStruct() {#acd584c22dfc805dde1b05d63617e3b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOpTypeStruct (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, bool EmitIR=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOpTypeVector() {#a4235d1b6d11a7696ce70d0066d35ab28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOpTypeVector (uint32_t NumElems, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * ElemType, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOpTypeVoid() {#a887ada042d63eb70807dc15aefcd6390}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOpTypeVoid (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOrCreateBaseRegister() {#ab5802f07ff75bd2855e70ea0d71ae107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateBaseRegister (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII, unsigned BitWidth, bool ZeroAsNull)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOrCreateCompositeOrNull() {#a6e776a4eac8e6f8e0885db97ee4fad4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateCompositeOrNull (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> &amp; TII, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * CA, unsigned BitWidth, unsigned ElemCnt, bool ZeroAsNull=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOrCreateConstFloatReg() {#a539c49ee376324e7bc129fa59444a704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Register, ConstantFP *, bool, unsigned &gt; SPIRVGlobalRegistry::getOrCreateConstFloatReg (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> Val, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> * MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * I=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> * TII=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOrCreateConstIntReg() {#a95cd72c33e8e06b8bcfda5595e7cb638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Register, ConstantInt *, bool, unsigned &gt; SPIRVGlobalRegistry::getOrCreateConstIntReg (uint64_t Val, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> * MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * I=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> * TII=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOrCreateIntCompositeOrNull() {#a03e3caae340beeb82a742d90d753865f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPIRVGlobalRegistry::getOrCreateIntCompositeOrNull (uint64_t Val, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, bool EmitIR, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * CA, unsigned BitWidth, unsigned ElemCnt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### getOrCreateSpecialType() {#a33c8a2183f36a6f7e486606a75bf96ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::getOrCreateSpecialType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AccQual)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

### restOfCreateSPIRVType() {#adec19bbaaa10e66b0a2c9eb44d661017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVType * SPIRVGlobalRegistry::restOfCreateSPIRVType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Type, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, SPIRV::AccessQualifier::AccessQualifier AccessQual, bool EmitIR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>, definition at line 1071 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CurMF {#a7692d43a010892d4aeb5e6e81a083b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::SPIRVGlobalRegistry::CurMF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>


<p>Referenced by <a href="#a224cd42d0c6c318274c1696e74b63b51">assignFloatTypeToVReg</a>, <a href="#a88f2b05d25ba2010b0c306071730fe01">assignIntTypeToVReg</a>, <a href="#a29a63a69f9d2a425a5fbef3e0104399e">assignVectTypeToVReg</a>, <a href="#affb04c244423615aa0df24ee36f2de20">buildConstantInt</a>, <a href="#a881c9e75128e7e943b6d8f33606ccc74">buildGlobalVariable</a>, <a href="#af54e9ce01961e65d9b74fef2193a8d95">getOrCreateConstFP</a>, <a href="#a08f607435df14840793b848f2b3c0257">getOrCreateConstInt</a>, <a href="#af99db04834e1ae3fc23466a80045a4d9">getOrCreateConstNullPtr</a>, <a href="#aac40b88bee839e32d4f0f860282d0fc4">getOrCreateOpTypeFunctionWithArgs</a>, <a href="#ae5869468359515f460a588357f1737cf">getOrCreateSPIRVArrayType</a>, <a href="#a8bdd4c60453b10074293349820f8bdcf">getOrCreateSPIRVBoolType</a>, <a href="#a4b607e6993b349291749a0e177c52fbb">getOrCreateSPIRVFloatType</a>, <a href="#a18fd6615429a508c934bc1cff0f49319">getOrCreateSPIRVIntegerType</a>, <a href="#acab67f583801f5c01ee9ac2162f5e27d">getOrCreateSPIRVPointerType</a>, <a href="#a8f224f7bdbbd3667e44b205c571b30d2">getOrCreateSPIRVType</a>, <a href="#a4791c0c5f18aaa298445226456f15547">getOrCreateSPIRVVectorType</a>, <a href="#a35c2ba2ad91e2fe027f8f64e92a7502f">getOrCreateUndef</a>, <a href="#a0abb9ee0d1c0872f76cea9d9b6c1396e">getResultType</a>, <a href="#a05b34a70cde1fcbdcb0767cf218c1752">getSPIRVTypeForVReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#af352e338e2b9a8cd58a97aca55d421e4">processNewInstrs</a> and <a href="#abe2132b08f73f4e1715fbefbddfacb55">setCurrentFunc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AssignPtrTypeInstr {#a96a68bf8f098e836a073f4ea5950ccad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, CallInst *&gt; llvm::SPIRVGlobalRegistry::AssignPtrTypeInstr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### Bound {#a2565ea5642d8e49e66c056c41cc18910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SPIRVGlobalRegistry::Bound</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### DeducedElTys {#a506c0d945cef7429ac7e87206a11234b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, Type *&gt; llvm::SPIRVGlobalRegistry::DeducedElTys</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### DeducedNestedTys {#ae519640411fbbd7e6f9d6f59359619a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, Type *&gt; llvm::SPIRVGlobalRegistry::DeducedNestedTys</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### DT {#a3cb05aaaed3e45867183b2d488d295a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVGeneralDuplicatesTracker llvm::SPIRVGlobalRegistry::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### ForwardCalls {#af444a9cadf65534dc57e577dda71a98a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Function *, SmallPtrSet&lt;MachineInstr *, 8&gt; &gt; llvm::SPIRVGlobalRegistry::ForwardCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### ForwardPointerTypes {#ad1db98fa9a90b44fe8af4788a6852ef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Type *, SPIRVType *&gt; llvm::SPIRVGlobalRegistry::ForwardPointerTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### FunctionToInstr {#a48078c7d946e2f3db8e32bea68e44a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Function *, const MachineOperand *&gt; llvm::SPIRVGlobalRegistry::FunctionToInstr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### FunctionToInstrRev {#a3e87f79b02218130f8c46daa90dee590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineInstr *, const Function *&gt; llvm::SPIRVGlobalRegistry::FunctionToInstrRev</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### FunResPointerTypes {#a8c0ce2b489e1162f3897e094191ba3e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Function *, TypedPointerType *&gt; llvm::SPIRVGlobalRegistry::FunResPointerTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### InstrToFunction {#ad9ce46ff92a76d497a830c240e504ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineOperand *, const Function *&gt; llvm::SPIRVGlobalRegistry::InstrToFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### LastInsertedTypeMap {#af3bb5af1a5b9998a74c9040d2c041e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineFunction *, MachineInstr *&gt; llvm::SPIRVGlobalRegistry::LastInsertedTypeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### MutatedAggRet {#a97ea15a5fa1c21f0a451d6648c9fb005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, Type *&gt; llvm::SPIRVGlobalRegistry::MutatedAggRet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### PointerSize {#a3c798abd3a1685b10c7aacc8f434fe81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SPIRVGlobalRegistry::PointerSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### Reg2GO {#a17784db68d81bd1893724b2f1ca8e5d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;const MachineFunction *, Register&gt;, const Value *&gt; llvm::SPIRVGlobalRegistry::Reg2GO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### SPIRVToLLVMType {#a3f8b8d75f6e61e82b2df980a0be8cc66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;SPIRVType *, const Type *&gt; llvm::SPIRVGlobalRegistry::SPIRVToLLVMType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### TypesInProcessing {#a211dd4c363894f27b091c8006d0b55ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const Type *, 4&gt; llvm::SPIRVGlobalRegistry::TypesInProcessing</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### ValueAttrs {#aec0cfc0609b0b055e6a88abbe584ea8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineInstr *, std::pair&lt;Type *, std::string&gt; &gt; llvm::SPIRVGlobalRegistry::ValueAttrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

### VRegToTypeMap {#ad2d25cc81033e84d315fedab8f088c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineFunction *, DenseMap&lt;Register, SPIRVType *&gt; &gt; llvm::SPIRVGlobalRegistry::VRegToTypeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp">SPIRVGlobalRegistry.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
