---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinefunction/variabledbginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VariableDbgInfo` Class Reference

<p>Description of the location of a variable whose Address is valid and unchanging during function execution. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineFunction::VariableDbgInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acab52a2e3ac991ea57b9355bf7f8deea">VariableDbgInfo</a> (const DILocalVariable *Var, const DIExpression *Expr, int Slot, const DILocation *Loc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa3058f8a0996d47ea422f5f556fc09f">VariableDbgInfo</a> (const DILocalVariable *Var, const DIExpression *Expr, MCRegister EntryValReg, const DILocation *Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bec5f8b6d16632f94baa782837156db">inStackSlot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this variable is in a stack slot. <a href="#a2bec5f8b6d16632f94baa782837156db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa74bc8f8755bfc50feda754ac53200f4">inEntryValueRegister</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this variable is in the entry value of a register. <a href="#aa74bc8f8755bfc50feda754ac53200f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4c645fcc102e4a2c7486f9c20464eb0">getStackSlot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the stack slot of this variable, assuming <span class="doxyComputerOutput"><a href="#a2bec5f8b6d16632f94baa782837156db">inStackSlot()</a></span> is true. <a href="#ad4c645fcc102e4a2c7486f9c20464eb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58611c96e9793b8609745153a9ab88ec">getEntryValueRegister</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> of this variable, assuming <span class="doxyComputerOutput"><a href="#aa74bc8f8755bfc50feda754ac53200f4">inEntryValueRegister()</a></span> is true. <a href="#a58611c96e9793b8609745153a9ab88ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5549e5d6a5871adae7ac4a63d462913e">updateStackSlot</a> (int NewSlot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the stack slot of this variable, assuming <span class="doxyComputerOutput"><a href="#a2bec5f8b6d16632f94baa782837156db">inStackSlot()</a></span> is true. <a href="#a5549e5d6a5871adae7ac4a63d462913e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0f6c13dd0f326802404c14b6b4748f7">Var</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5b036d243411a4bb295f5b9c1c54bef">Expr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352f06047a69f1e4c9f7716982be0a61">Loc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::variant&lt; int, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab217a8fc8762512496930d391a20eff2">Address</a></td>
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

<p>Description of the location of a variable whose Address is valid and unchanging during function execution.</p>


<p>The Address may be:</p>


<ul class="doxyList ">
<li>A stack index, which can be negative for fixed stack objects.</li>
<li>A <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>, whose entry value contains the address of the variable.</li>
</ul>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VariableDbgInfo() {#acab52a2e3ac991ea57b9355bf7f8deea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineFunction::VariableDbgInfo::VariableDbgInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, int Slot, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * Loc)</td>
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



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>References <a href="#ad5b036d243411a4bb295f5b9c1c54bef">Expr</a>, <a href="#a352f06047a69f1e4c9f7716982be0a61">Loc</a> and <a href="#ac0f6c13dd0f326802404c14b6b4748f7">Var</a>.</p>

</div>
</div>

### VariableDbgInfo() {#afa3058f8a0996d47ea422f5f556fc09f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineFunction::VariableDbgInfo::VariableDbgInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> EntryValReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * Loc)</td>
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



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>References <a href="#ad5b036d243411a4bb295f5b9c1c54bef">Expr</a>, <a href="#a352f06047a69f1e4c9f7716982be0a61">Loc</a> and <a href="#ac0f6c13dd0f326802404c14b6b4748f7">Var</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEntryValueRegister() {#a58611c96e9793b8609745153a9ab88ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::MachineFunction::VariableDbgInfo::getEntryValueRegister ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> of this variable, assuming <span class="doxyComputerOutput"><a href="#aa74bc8f8755bfc50feda754ac53200f4">inEntryValueRegister()</a></span> is true.</p>

<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>

</div>
</div>

### getStackSlot() {#ad4c645fcc102e4a2c7486f9c20464eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MachineFunction::VariableDbgInfo::getStackSlot ()</td>
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

<p>Returns the stack slot of this variable, assuming <span class="doxyComputerOutput"><a href="#a2bec5f8b6d16632f94baa782837156db">inStackSlot()</a></span> is true.</p>

<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>

</div>
</div>

### inEntryValueRegister() {#aa74bc8f8755bfc50feda754ac53200f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFunction::VariableDbgInfo::inEntryValueRegister ()</td>
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

<p>Return true if this variable is in the entry value of a register.</p>

<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>

</div>
</div>

### inStackSlot() {#a2bec5f8b6d16632f94baa782837156db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFunction::VariableDbgInfo::inStackSlot ()</td>
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

<p>Return true if this variable is in a stack slot.</p>

<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Referenced by <a href="#a5549e5d6a5871adae7ac4a63d462913e">updateStackSlot</a>.</p>

</div>
</div>

### updateStackSlot() {#a5549e5d6a5871adae7ac4a63d462913e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFunction::VariableDbgInfo::updateStackSlot (int NewSlot)</td>
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

<p>Updates the stack slot of this variable, assuming <span class="doxyComputerOutput"><a href="#a2bec5f8b6d16632f94baa782837156db">inStackSlot()</a></span> is true.</p>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a2bec5f8b6d16632f94baa782837156db">inStackSlot</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Expr {#ad5b036d243411a4bb295f5b9c1c54bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIExpression* llvm::MachineFunction::VariableDbgInfo::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a86f57e7a60bb7ee3c2c7b44edd900081">printStackObjectDbgInfo</a>, <a href="#acab52a2e3ac991ea57b9355bf7f8deea">VariableDbgInfo</a> and <a href="#afa3058f8a0996d47ea422f5f556fc09f">VariableDbgInfo</a>.</p>

</div>
</div>

### Loc {#a352f06047a69f1e4c9f7716982be0a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DILocation* llvm::MachineFunction::VariableDbgInfo::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a86f57e7a60bb7ee3c2c7b44edd900081">printStackObjectDbgInfo</a>, <a href="#acab52a2e3ac991ea57b9355bf7f8deea">VariableDbgInfo</a> and <a href="#afa3058f8a0996d47ea422f5f556fc09f">VariableDbgInfo</a>.</p>

</div>
</div>

### Var {#ac0f6c13dd0f326802404c14b6b4748f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DILocalVariable* llvm::MachineFunction::VariableDbgInfo::Var</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a86f57e7a60bb7ee3c2c7b44edd900081">printStackObjectDbgInfo</a>, <a href="#acab52a2e3ac991ea57b9355bf7f8deea">VariableDbgInfo</a> and <a href="#afa3058f8a0996d47ea422f5f556fc09f">VariableDbgInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Address {#ab217a8fc8762512496930d391a20eff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::variant&lt;int, MCRegister&gt; llvm::MachineFunction::VariableDbgInfo::Address</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">MachineFunction.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
