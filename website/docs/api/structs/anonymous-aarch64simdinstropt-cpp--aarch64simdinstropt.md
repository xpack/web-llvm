---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AArch64SIMDInstrOpt` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt { ... }
</div>

## Base struct

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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Subpass { <a href="#ae6a9da5892d37573f09d9d63c80b85a9">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa4405aa609fc3cebea46e423a471c1">AArch64SIMDInstrOpt</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60304883d8f734890e4b824b28b9ad9e">shouldReplaceInst</a> (MachineFunction *MF, const MCInstrDesc *InstDesc, SmallVectorImpl&lt; const MCInstrDesc * &gt; &amp;ReplInstrMCID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Based only on latency of instructions, determine if it is cost efficient to replace the instruction InstDesc by the instructions stored in the array InstDescRepl. <a href="#a60304883d8f734890e4b824b28b9ad9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b87d9f9d3ea5fcffea02f2f8e9bb55f">shouldExitEarly</a> (MachineFunction *MF, Subpass SP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if we need to exit the instruction replacement optimization passes early. <a href="#a3b87d9f9d3ea5fcffea02f2f8e9bb55f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5536577e4a955f5327410bda9cf3e7ed">reuseDUP</a> (MachineInstr &amp;MI, unsigned DupOpcode, unsigned SrcReg, unsigned LaneNumber, unsigned *DestReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether an equivalent DUP instruction has already been created or not. <a href="#a5536577e4a955f5327410bda9cf3e7ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370295a9498306cec66248f1c1fd8416">optimizeVectElement</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Certain SIMD instructions with vector element operand are not efficient. <a href="#a370295a9498306cec66248f1c1fd8416">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b6112b4ae42ce9cd677fcb2bb1af19">processSeqRegInst</a> (MachineInstr *DefiningMI, unsigned *StReg, unsigned *StRegKill, unsigned NumArg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> The REG_SEQUENCE instruction, and extract the source operands of the ST2/4 instruction from it. <a href="#a51b6112b4ae42ce9cd677fcb2bb1af19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa26fba7384acba48becbf2f67547c437">optimizeLdStInterleave</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load/Store Interleaving instructions are not always beneficial. <a href="#aa26fba7384acba48becbf2f67547c437">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89aacbc7e01458ec72953b9edab0558b">determineSrcReg</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of useful source registers for this instruction (2 for ST2 and 4 for ST4). <a href="#a89aacbc7e01458ec72953b9edab0558b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ab07fceeb056e44371448f9650b9ae5">runOnMachineFunction</a> (MachineFunction &amp;Fn) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a9ab07fceeb056e44371448f9650b9ae5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9369961f2bf07ea2c0b287b695b1a0">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#abb9369961f2bf07ea2c0b287b695b1a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b0830d2fada1d3d9b14ba3a6a76d0d">TII</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f313b513f3f58a20a97f75e960bc684">MRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade86add59ad89d5435c7530b98f82249">SchedModel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::pair&lt; unsigned, std::string &gt;, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a3e5f1f85fae6ece35b3acf5563361">SIMDInstrTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96caef8064bb3913d19439c864fedd9b">InterlEarlyExit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/instreplinfo">InstReplInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addec728e7ca539ab310903052ab94846">IRT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab49fdc69d0520e24eb7c266e3fc1c1eb">ID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc9d2e2146ca2b8379866cbb56cfe00">MaxNumRepl</a> = 10</td>
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


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Subpass {#ae6a9da5892d37573f09d9d63c80b85a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::Subpass </td>
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
<td class="doxyEnumItemName">VectorElem<a id="ae6a9da5892d37573f09d9d63c80b85a9ae1ab7d337587b351cb6a6dc7a660d300"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Interleave<a id="ae6a9da5892d37573f09d9d63c80b85a9aae88eb6bd761da8be9a60a00cf30c141"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AArch64SIMDInstrOpt() {#aaaa4405aa609fc3cebea46e423a471c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::AArch64SIMDInstrOpt ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#ab49fdc69d0520e24eb7c266e3fc1c1eb">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace01ea1de28709257e8236ec413931f1">llvm::initializeAArch64SIMDInstrOptPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7d5499e1f8ca95f2c88ceeb2b045a9c4">llvm::createAArch64SIMDInstrOptPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### determineSrcReg() {#a89aacbc7e01458ec72953b9edab0558b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64SIMDInstrOpt::determineSrcReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of useful source registers for this instruction (2 for ST2 and 4 for ST4).</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aa26fba7384acba48becbf2f67547c437">optimizeLdStInterleave</a> and <a href="#a60304883d8f734890e4b824b28b9ad9e">shouldReplaceInst</a>.</p>

</div>
</div>

### getPassName() {#abb9369961f2bf07ea2c0b287b695b1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::getPassName ()</td>
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


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp/#ac028784db22d35a4cf814bfaff176e6d">AARCH64_VECTOR_BY_ELEMENT_OPT_NAME</a>.</p>

</div>
</div>

### optimizeLdStInterleave() {#aa26fba7384acba48becbf2f67547c437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64SIMDInstrOpt::optimizeLdStInterleave (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Load/Store Interleaving instructions are not always beneficial.</p>


<p>Replace them by ZIP instructionand classical load/store. Return true if the SIMD instruction is modified.</p>


<p>Replace them by ZIP instructions and classical load/store.</p>


<p>For example: st2 {v0.4s, v1.4s}, addr</p>


<p>Is rewritten into: zip1 v2.4s, v0.4s, v1.4s zip2 v3.4s, v0.4s, v1.4s stp q2, q3, addr For example: st4 {v0.4s, v1.4s, v2.4s, v3.4s}, addr</p>


<p>Is rewritten into: zip1 v4.4s, v0.4s, v2.4s zip2 v5.4s, v0.4s, v2.4s zip1 v6.4s, v1.4s, v3.4s zip2 v7.4s, v1.4s, v3.4s zip1 v8.4s, v4.4s, v6.4s zip2 v9.4s, v4.4s, v6.4s zip1 v10.4s, v5.4s, v7.4s zip2 v11.4s, v5.4s, v7.4s stp q8, q9, addr stp q10, q11, addr+32</p>


<p>Currently only instructions related to ST2 and ST4 are considered. Other may be added later. Return true if the SIMD instruction is modified.</p>


<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a89aacbc7e01458ec72953b9edab0558b">determineSrcReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#addec728e7ca539ab310903052ab94846">IRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a0f313b513f3f58a20a97f75e960bc684">MRI</a>, <a href="#a51b6112b4ae42ce9cd677fcb2bb1af19">processSeqRegInst</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a60304883d8f734890e4b824b28b9ad9e">shouldReplaceInst</a> and <a href="#a71b0830d2fada1d3d9b14ba3a6a76d0d">TII</a>.</p>


<p>Referenced by <a href="#a9ab07fceeb056e44371448f9650b9ae5">runOnMachineFunction</a> and <a href="#a60304883d8f734890e4b824b28b9ad9e">shouldReplaceInst</a>.</p>

</div>
</div>

### optimizeVectElement() {#a370295a9498306cec66248f1c1fd8416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64SIMDInstrOpt::optimizeVectElement (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Certain SIMD instructions with vector element operand are not efficient.</p>


<p>Rewrite them into SIMD instructions with vector operands. This rewrite is driven by the latency of the instructions. Return true if the SIMD instruction is modified.</p>


<p>Rewrite them into SIMD instructions with vector operands. This rewrite is driven by the latency of the instructions. The instruction of concerns are for the time being FMLA, FMLS, FMUL, and FMULX and hence they are hardcoded.</p>


<p>For example: fmla v0.4s, v1.4s, v2.s[1]</p>


<p>Is rewritten into dup v3.4s, v2.s[1] // DUP not necessary if redundant fmla v0.4s, v1.4s, v3.4s</p>


<p>Return true if the SIMD instruction is modified.</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#aee50fcacb786c1fc56168a0c55a4e934">llvm::MCInstrDesc::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a0f313b513f3f58a20a97f75e960bc684">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a5536577e4a955f5327410bda9cf3e7ed">reuseDUP</a>, <a href="#a60304883d8f734890e4b824b28b9ad9e">shouldReplaceInst</a> and <a href="#a71b0830d2fada1d3d9b14ba3a6a76d0d">TII</a>.</p>


<p>Referenced by <a href="#a9ab07fceeb056e44371448f9650b9ae5">runOnMachineFunction</a> and <a href="#a60304883d8f734890e4b824b28b9ad9e">shouldReplaceInst</a>.</p>

</div>
</div>

### processSeqRegInst() {#a51b6112b4ae42ce9cd677fcb2bb1af19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64SIMDInstrOpt::processSeqRegInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DefiningMI, unsigned * StReg, unsigned * StRegKill, unsigned NumArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> The REG_SEQUENCE instruction, and extract the source operands of the ST2/4 instruction from it.</p>


<p>Example of such instructions. dest = REG_SEQUENCE st2_src1, dsub0, st2_src2, dsub1; Return true when the instruction is processed successfully.</p>


<p>Example of such instruction. dest = REG_SEQUENCE st2_src1, dsub0, st2_src2, dsub1; Return true when the instruction is processed successfully.</p>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>.</p>


<p>Referenced by <a href="#aa26fba7384acba48becbf2f67547c437">optimizeLdStInterleave</a> and <a href="#a60304883d8f734890e4b824b28b9ad9e">shouldReplaceInst</a>.</p>

</div>
</div>

### reuseDUP() {#a5536577e4a955f5327410bda9cf3e7ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64SIMDInstrOpt::reuseDUP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DupOpcode, unsigned SrcReg, unsigned LaneNumber, unsigned * DestReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check whether an equivalent DUP instruction has already been created or not.</p>


<p>Return true when the DUP instruction already exists. In this case, DestReg will point to the destination of the already created DUP.</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a370295a9498306cec66248f1c1fd8416">optimizeVectElement</a> and <a href="#a60304883d8f734890e4b824b28b9ad9e">shouldReplaceInst</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a9ab07fceeb056e44371448f9650b9ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64SIMDInstrOpt::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#ae6a9da5892d37573f09d9d63c80b85a9aae88eb6bd761da8be9a60a00cf30c141">Interleave</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a0f313b513f3f58a20a97f75e960bc684">MRI</a>, <a href="#aa26fba7384acba48becbf2f67547c437">optimizeLdStInterleave</a>, <a href="#a370295a9498306cec66248f1c1fd8416">optimizeVectElement</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ade86add59ad89d5435c7530b98f82249">SchedModel</a>, <a href="#a3b87d9f9d3ea5fcffea02f2f8e9bb55f">shouldExitEarly</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>, <a href="#a71b0830d2fada1d3d9b14ba3a6a76d0d">TII</a> and <a href="#ae6a9da5892d37573f09d9d63c80b85a9ae1ab7d337587b351cb6a6dc7a660d300">VectorElem</a>.</p>


<p>Referenced by <a href="#a60304883d8f734890e4b824b28b9ad9e">shouldReplaceInst</a>.</p>

</div>
</div>

### shouldExitEarly() {#a3b87d9f9d3ea5fcffea02f2f8e9bb55f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64SIMDInstrOpt::shouldExitEarly (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="#ae6a9da5892d37573f09d9d63c80b85a9">Subpass</a> SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if we need to exit the instruction replacement optimization passes early.</p>


<p>Determine if we need to exit this pass for a kind of instruction replacement early.</p>


<p>This makes sure that no compile time is spent in this pass for targets with no need for any of these optimizations. Return true if early exit of the pass is recommended.</p>


<p>This makes sure that no compile time is spent in this pass for targets with no need for any of these optimizations beyond performing this check. Return true if early exit of this pass for a kind of instruction replacement is recommended for a target.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a96caef8064bb3913d19439c864fedd9b">InterlEarlyExit</a>, <a href="#ae6a9da5892d37573f09d9d63c80b85a9aae88eb6bd761da8be9a60a00cf30c141">Interleave</a>, <a href="#addec728e7ca539ab310903052ab94846">IRT</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ade86add59ad89d5435c7530b98f82249">SchedModel</a>, <a href="#a60304883d8f734890e4b824b28b9ad9e">shouldReplaceInst</a>, <a href="#a71b0830d2fada1d3d9b14ba3a6a76d0d">TII</a> and <a href="#ae6a9da5892d37573f09d9d63c80b85a9ae1ab7d337587b351cb6a6dc7a660d300">VectorElem</a>.</p>


<p>Referenced by <a href="#a9ab07fceeb056e44371448f9650b9ae5">runOnMachineFunction</a> and <a href="#a60304883d8f734890e4b824b28b9ad9e">shouldReplaceInst</a>.</p>

</div>
</div>

### shouldReplaceInst() {#a60304883d8f734890e4b824b28b9ad9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::shouldReplaceInst (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> * InstDesc, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> * &gt; &amp; ReplInstrMCID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Based only on latency of instructions, determine if it is cost efficient to replace the instruction InstDesc by the instructions stored in the array InstDescRepl.</p>


<p>Return true if replacement is expected to be faster.</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>References <a href="#a89aacbc7e01458ec72953b9edab0558b">determineSrcReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#aa26fba7384acba48becbf2f67547c437">optimizeLdStInterleave</a>, <a href="#a370295a9498306cec66248f1c1fd8416">optimizeVectElement</a>, <a href="#a51b6112b4ae42ce9cd677fcb2bb1af19">processSeqRegInst</a>, <a href="#a5536577e4a955f5327410bda9cf3e7ed">reuseDUP</a>, <a href="#a9ab07fceeb056e44371448f9650b9ae5">runOnMachineFunction</a> and <a href="#a3b87d9f9d3ea5fcffea02f2f8e9bb55f">shouldExitEarly</a>.</p>


<p>Referenced by <a href="#aa26fba7384acba48becbf2f67547c437">optimizeLdStInterleave</a>, <a href="#a370295a9498306cec66248f1c1fd8416">optimizeVectElement</a> and <a href="#a3b87d9f9d3ea5fcffea02f2f8e9bb55f">shouldExitEarly</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### InterlEarlyExit {#a96caef8064bb3913d19439c864fedd9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string, bool&gt; anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::InterlEarlyExit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>Referenced by <a href="#a3b87d9f9d3ea5fcffea02f2f8e9bb55f">shouldExitEarly</a>.</p>

</div>
</div>

### IRT {#addec728e7ca539ab310903052ab94846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;InstReplInfo&gt; anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::IRT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>Referenced by <a href="#aa26fba7384acba48becbf2f67547c437">optimizeLdStInterleave</a> and <a href="#a3b87d9f9d3ea5fcffea02f2f8e9bb55f">shouldExitEarly</a>.</p>

</div>
</div>

### MRI {#a0f313b513f3f58a20a97f75e960bc684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>Referenced by <a href="#aa26fba7384acba48becbf2f67547c437">optimizeLdStInterleave</a>, <a href="#a370295a9498306cec66248f1c1fd8416">optimizeVectElement</a> and <a href="#a9ab07fceeb056e44371448f9650b9ae5">runOnMachineFunction</a>.</p>

</div>
</div>

### SchedModel {#ade86add59ad89d5435c7530b98f82249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetSchedModel anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::SchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>Referenced by <a href="#a9ab07fceeb056e44371448f9650b9ae5">runOnMachineFunction</a> and <a href="#a3b87d9f9d3ea5fcffea02f2f8e9bb55f">shouldExitEarly</a>.</p>

</div>
</div>

### SIMDInstrTable {#a20a3e5f1f85fae6ece35b3acf5563361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::pair&lt;unsigned, std::string&gt;, bool&gt; anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::SIMDInstrTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>

</div>
</div>

### TII {#a71b0830d2fada1d3d9b14ba3a6a76d0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>Referenced by <a href="#aa26fba7384acba48becbf2f67547c437">optimizeLdStInterleave</a>, <a href="#a370295a9498306cec66248f1c1fd8416">optimizeVectElement</a>, <a href="#a9ab07fceeb056e44371448f9650b9ae5">runOnMachineFunction</a> and <a href="#a3b87d9f9d3ea5fcffea02f2f8e9bb55f">shouldExitEarly</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ab49fdc69d0520e24eb7c266e3fc1c1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::ID = 0</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>


<p>Referenced by <a href="#aaaa4405aa609fc3cebea46e423a471c1">AArch64SIMDInstrOpt</a>.</p>

</div>
</div>

### MaxNumRepl {#a4dc9d2e2146ca2b8379866cbb56cfe00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::MaxNumRepl = 10</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp">AArch64SIMDInstrOpt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
