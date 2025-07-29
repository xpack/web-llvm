---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loongarchexpandpseudoinsts-cpp-/loongarchexpandpseudo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoongArchExpandPseudo` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchExpandPseudo { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf26b7fa05388dd3d67b2c062f5c2104">LoongArchExpandPseudo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f79f17188d76a8543069890303ae451">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a7f79f17188d76a8543069890303ae451">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01acb7f61cf339804c07ae674b75bf18">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a01acb7f61cf339804c07ae674b75bf18">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50282a916f76c44fa3a3bce331ceb3c1">expandMBB</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9273d6bc691b70dcdef92333ab694688">expandMI</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, MachineBasicBlock::iterator &amp;NextMBBI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0059a46aec87412609d36b58f50368e">expandCopyCFR</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, MachineBasicBlock::iterator &amp;NextMBBI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7468358a1ac1dace390d73cfe9a3229a">expandFunctionCALL</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, MachineBasicBlock::iterator &amp;NextMBBI, bool IsTailCall)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo">LoongArchInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ce2b9425a9328c8424c961c949bc6fe">TII</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd06dcf649233dba3b36b443d026aa3">ID</a> = 0</td>
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


<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp">LoongArchExpandPseudoInsts.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoongArchExpandPseudo() {#acf26b7fa05388dd3d67b2c062f5c2104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchExpandPseudo::LoongArchExpandPseudo ()</td>
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



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp">LoongArchExpandPseudoInsts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a2fd06dcf649233dba3b36b443d026aa3">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f9b49857afc217bd0f68e9d41a47102">llvm::initializeLoongArchExpandPseudoPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acd84cff4a39c3526773c808a400d42b7">llvm::createLoongArchExpandPseudoPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPassName() {#a01acb7f61cf339804c07ae674b75bf18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchExpandPseudo::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp">LoongArchExpandPseudoInsts.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp/#ab1d84b7f6a2720c0b67ca45fe3f9bfae">LOONGARCH_EXPAND_PSEUDO_NAME</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a7f79f17188d76a8543069890303ae451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchExpandPseudo::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp">LoongArchExpandPseudoInsts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a35e0c8c0b180c95d4e122e55ed62cc64">Modified</a> and <a href="#a0ce2b9425a9328c8424c961c949bc6fe">TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### expandCopyCFR() {#ac0059a46aec87412609d36b58f50368e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchExpandPseudo::expandCopyCFR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; NextMBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp">LoongArchExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandFunctionCALL() {#a7468358a1ac1dace390d73cfe9a3229a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchExpandPseudo::expandFunctionCALL (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; NextMBBI, bool IsTailCall)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp">LoongArchExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandMBB() {#a50282a916f76c44fa3a3bce331ceb3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchExpandPseudo::expandMBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp">LoongArchExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandMI() {#a9273d6bc691b70dcdef92333ab694688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchExpandPseudo::expandMI (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; NextMBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp">LoongArchExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### TII {#a0ce2b9425a9328c8424c961c949bc6fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoongArchInstrInfo* anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchExpandPseudo::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp">LoongArchExpandPseudoInsts.cpp</a>.</p>


<p>Referenced by <a href="#a7f79f17188d76a8543069890303ae451">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a2fd06dcf649233dba3b36b443d026aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char anonymous{LoongArchExpandPseudoInsts.cpp}::LoongArchExpandPseudo::ID = 0</td>
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



<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp">LoongArchExpandPseudoInsts.cpp</a>.</p>


<p>Referenced by <a href="#acf26b7fa05388dd3d67b2c062f5c2104">LoongArchExpandPseudo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp">LoongArchExpandPseudoInsts.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
