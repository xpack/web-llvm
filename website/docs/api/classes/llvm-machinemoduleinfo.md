---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinemoduleinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineModuleInfo` Class

<p>This class contains meta information specific to a module. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineModuleInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77069a976edd49aec368bb55d1b88ad8">MachineModuleInfoWrapperPass</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3adeb4b2a92ed079b126f7f92899eee3">MachineModuleAnalysis</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1affa4301d540171553df80570290f18">MachineModuleInfo</a> (const TargetMachine *TM=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aade9275d95ae9f4c13e7ca45f6e4e609">MachineModuleInfo</a> (const TargetMachine *TM, MCContext *ExtContext)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a327d5c7bec384a54c746d6172c7cd746">MachineModuleInfo</a> (MachineModuleInfo &amp;&amp;MMII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9167fd88b6fe11fe044d4303a837a9f5">~MachineModuleInfo</a> ()</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a814dd62d5eb2f698bf558b3962c3bbf4">operator=</a> (MachineModuleInfo &amp;&amp;MMII)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3274599e96368049f8a8e977ad9fce33">initialize</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af704df1e418c5e7a916adb2a217cb55d">finalize</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9ff5ea479131ab7fa913ceb779bd875">getTarget</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51904840e3bcc15ef2b99a101e972b02">getContext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90b2a34a9ee6b09614b28286dac3d90e">getContext</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a05f73ad80e58a532ea879ccc166b66">getModule</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89ccc89e9bd5881953bd1524a0d29f84">getOrCreateMachineFunction</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> constructed for the IR function <span class="doxyComputerOutput">F</span>. <a href="#a89ccc89e9bd5881953bd1524a0d29f84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a4ac2dc30f53dff05d2c7b2d8ebaef">getMachineFunction</a> (const Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> associated to IR function <span class="doxyComputerOutput">F</span> if there is one, otherwise nullptr. <a href="#ac1a4ac2dc30f53dff05d2c7b2d8ebaef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9bbdfe50af72a053dcce39a50ba5399">deleteMachineFunctionFor</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> <span class="doxyComputerOutput">MF</span> and reset the link in the IR <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to Machine <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> map. <a href="#af9bbdfe50af72a053dcce39a50ba5399">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e25573d45fb624fde3da5906679053">insertFunction</a> (const Function &amp;F, std::unique_ptr&lt; MachineFunction &gt; &amp;&amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an externally created <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> <span class="doxyComputerOutput">MF</span> for <span class="doxyComputerOutput">F</span>. <a href="#a36e25573d45fb624fde3da5906679053">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Ty&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Ty &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a92d88d2c22a932066d294be13e2baf55">getObjFileInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of various per-module pieces of information for backends that would like to do so. <a href="#a92d88d2c22a932066d294be13e2baf55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Ty&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Ty &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4528d1ef63f1dbd3326208f5f9f5ec59">getObjFileInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ee3b43d1d4729bdd69486667e7a98e">TM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac84bf5fc555da846b0ac0b64d6a64c16">Context</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> used for the entire code generator. <a href="#ac84bf5fc555da846b0ac0b64d6a64c16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadcc0d59d9023c515bb79a392f0b3127">ExternalContext</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a195034a21da4063df64f80580c999413">TheModule</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the LLVM <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> being worked on. <a href="#a195034a21da4063df64f80580c999413">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2590107d9dd9879ba188c41fe4f50bc6">ObjFileMMI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the object-file-format-specific implementation of <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a>, which lets targets accumulate whatever info they want. <a href="#a2590107d9dd9879ba188c41fe4f50bc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b232ce41e98e7efbf0df50189cbf902">MachineFunctions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps IR Functions to their corresponding MachineFunctions. <a href="#a2b232ce41e98e7efbf0df50189cbf902">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc2e3fda76986c02996854e25bc50e87">NextFnNum</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Next unique number available for a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="#abc2e3fda76986c02996854e25bc50e87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae78062dba9db5950d25c98f045186741">LastRequest</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used for shortcut/cache. <a href="#ae78062dba9db5950d25c98f045186741">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a872c3492eac7d6acf3dfb79336f01ae8">LastResult</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used for shortcut/cache. <a href="#a872c3492eac7d6acf3dfb79336f01ae8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class contains meta information specific to a module.</p>


<p>Queries can be made by different debugging and exception handling schemes and reformated for specific use.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>


<div class="doxySectionDef">

## Friends

### MachineModuleAnalysis {#a3adeb4b2a92ed079b126f7f92899eee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/machinemoduleanalysis">MachineModuleAnalysis</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>


<p>References <a href="#a3adeb4b2a92ed079b126f7f92899eee3">MachineModuleAnalysis</a> and <a href="#a1affa4301d540171553df80570290f18">MachineModuleInfo</a>.</p>


<p>Referenced by <a href="#a3adeb4b2a92ed079b126f7f92899eee3">MachineModuleAnalysis</a>.</p>

</div>
</div>

### MachineModuleInfoWrapperPass {#a77069a976edd49aec368bb55d1b88ad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowrapperpass">MachineModuleInfoWrapperPass</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>


<p>Reference <a href="#a77069a976edd49aec368bb55d1b88ad8">MachineModuleInfoWrapperPass</a>.</p>


<p>Referenced by <a href="#a77069a976edd49aec368bb55d1b88ad8">MachineModuleInfoWrapperPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineModuleInfo() {#a1affa4301d540171553df80570290f18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfo::MachineModuleInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM=nullptr)</td>
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



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp">MachineModuleInfo.cpp</a>.</p>


<p>References <a href="#a3274599e96368049f8a8e977ad9fce33">initialize</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="#a4528d1ef63f1dbd3326208f5f9f5ec59">getObjFileInfo</a>, <a href="#a3adeb4b2a92ed079b126f7f92899eee3">MachineModuleAnalysis</a> and <a href="#a327d5c7bec384a54c746d6172c7cd746">MachineModuleInfo</a>.</p>

</div>
</div>

### MachineModuleInfo() {#aade9275d95ae9f4c13e7ca45f6e4e609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfo::MachineModuleInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * ExtContext)</td>
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



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp">MachineModuleInfo.cpp</a>.</p>


<p>References <a href="#a3274599e96368049f8a8e977ad9fce33">initialize</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### MachineModuleInfo() {#a327d5c7bec384a54c746d6172c7cd746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfo::MachineModuleInfo (<a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp;&amp; MMII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp">MachineModuleInfo.cpp</a>.</p>


<p>References <a href="#a1affa4301d540171553df80570290f18">MachineModuleInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineModuleInfo() {#a9167fd88b6fe11fe044d4303a837a9f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfo::~MachineModuleInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp">MachineModuleInfo.cpp</a>.</p>


<p>Reference <a href="#af704df1e418c5e7a916adb2a217cb55d">finalize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#a814dd62d5eb2f698bf558b3962c3bbf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfo &amp; llvm::MachineModuleInfo::operator= (<a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp;&amp; MMII)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deleteMachineFunctionFor() {#af9bbdfe50af72a053dcce39a50ba5399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineModuleInfo::deleteMachineFunctionFor (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> <span class="doxyComputerOutput">MF</span> and reset the link in the IR <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to Machine <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> map.</p>

<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp">MachineModuleInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ae986afe2285d3980b27aa9763f3203e9">llvm::MachineFunction::erase</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinemoduleinfo-cpp-/freemachinefunction/#a8214aae5e0ab52ed3978bbba9265778b">anonymous{MachineModuleInfo.cpp}::FreeMachineFunction::runOnFunction</a>.</p>

</div>
</div>

### finalize() {#af704df1e418c5e7a916adb2a217cb55d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineModuleInfo::finalize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp">MachineModuleInfo.cpp</a>.</p>


<p>Referenced by <a href="#a9167fd88b6fe11fe044d4303a837a9f5">~MachineModuleInfo</a>.</p>

</div>
</div>

### getContext() {#a51904840e3bcc15ef2b99a101e972b02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCContext &amp; llvm::MachineModuleInfo::getContext ()</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a407b9cf0cf2cf2eead54ec1ffac0fa77">llvm::CodeGenTargetMachineImpl::addPassesToEmitFile</a>, <a href="/web-llvm/docs/api/classes/llvm/directxtargetmachine/#ac9ec6dcf573b94dece0bcd8511579e4d">llvm::DirectXTargetMachine::addPassesToEmitFile</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterinlineasm-cpp/#a362579106cd14231f459ca8c00af60ca">EmitInlineAsmStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#acda48e0ba94e27f00cbe44c1585fcfe7">emitNonLazyStubs</a> and <a href="#a89ccc89e9bd5881953bd1524a0d29f84">getOrCreateMachineFunction</a>.</p>

</div>
</div>

### getContext() {#a90b2a34a9ee6b09614b28286dac3d90e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext &amp; llvm::MachineModuleInfo::getContext ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

### getMachineFunction() {#ac1a4ac2dc30f53dff05d2c7b2d8ebaef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction * MachineModuleInfo::getMachineFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> associated to IR function <span class="doxyComputerOutput">F</span> if there is one, otherwise nullptr.</p>


<p>NOTE: New pass manager clients shall not use this method to get the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a></span>, use <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionanalysis">MachineFunctionAnalysis</a></span> instead.</p>


<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp">MachineModuleInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a72a70493afafbf4374226300289c04b9">llvm::AArch64InstrInfo::getOutliningTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abffddc65a79eca0830b7dd232ff74dc5">llvm::ARMBaseInstrInfo::getOutliningTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#afbccb941c0215a918667f3a574b976b9">llvm::MIRParserImpl::parseMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinecheckdebugify-cpp-/checkdebugmachinemodule/#a326b0f33afafa16b37d37f736e52bf5e">anonymous{MachineCheckDebugify.cpp}::CheckDebugMachineModule::runOnModule</a> and <a href="/web-llvm/docs/api/structs/anonymous-machinestripdebug-cpp-/stripdebugmachinemodule/#af68a3711fb7b940ff150244b5892be4e">anonymous{MachineStripDebug.cpp}::StripDebugMachineModule::runOnModule</a>.</p>

</div>
</div>

### getModule() {#a6a05f73ad80e58a532ea879ccc166b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module * llvm::MachineModuleInfo::getModule ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinemoduleinfo/#ae8cd76b599873138cddf10f91e7bcad0">llvm::AMDGPUMachineModuleInfo::AMDGPUMachineModuleInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/thunkinserter/#a1a95b72d4c28ba76251171967da03b01">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::createThunkFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp/#a0e2890f613a1a43228dec112d337340d">getAuthPtrSlotSymbolHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a> and <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoelf/#a10fcc9cad3c4fe08af16f7ca8c14110d">llvm::MachineModuleInfoELF::MachineModuleInfoELF</a>.</p>

</div>
</div>

### getObjFileInfo() {#a92d88d2c22a932066d294be13e2baf55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Ty&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Ty &amp; llvm::MachineModuleInfo::getObjFileInfo ()</td>
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

<p>Keep track of various per-module pieces of information for backends that would like to do so.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#acda48e0ba94e27f00cbe44c1585fcfe7">emitNonLazyStubs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#a50239bad1326b962fc58f1b311e7e255">llvm::AArch64_ELFTargetObjectFile::emitPersonalityValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#afa8c25d9479e583055f8cd02df823840">llvm::AArch64_ELFTargetObjectFile::getAuthPtrSlotSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#a74cb396080d0202745507029ad8d65c5">llvm::AArch64_MachoTargetObjectFile::getAuthPtrSlotSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a3e7ee01bba0aa270863ab1e06502f374">llvm::TargetLoweringObjectFileMachO::getCFIPersonalitySymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="#a4528d1ef63f1dbd3326208f5f9f5ec59">getObjFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelftargetobjectfile/#a953050dfdd0d33bc59eb08438aa5d88c">llvm::SparcELFTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a726934c33655de3d8c59b38d0e946a62">llvm::TargetLoweringObjectFileELF::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#ae41814965809c6fb6403ca6338710a25">llvm::TargetLoweringObjectFileMachO::getTTypeGlobalReference</a> and <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemorylegalizer/#a599c4517601e4b05d04b3093a7968a91">anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::runOnMachineFunction</a>.</p>

</div>
</div>

### getObjFileInfo() {#a4528d1ef63f1dbd3326208f5f9f5ec59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Ty&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Ty &amp; llvm::MachineModuleInfo::getObjFileInfo ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>


<p>References <a href="#a92d88d2c22a932066d294be13e2baf55">getObjFileInfo</a> and <a href="#a1affa4301d540171553df80570290f18">MachineModuleInfo</a>.</p>

</div>
</div>

### getOrCreateMachineFunction() {#a89ccc89e9bd5881953bd1524a0d29f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction &amp; MachineModuleInfo::getOrCreateMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> constructed for the IR function <span class="doxyComputerOutput">F</span>.</p>


<p>Creates a new <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> if none exists yet. NOTE: New pass manager clients shall not use this method to get the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a></span>, use <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionanalysis">MachineFunctionAnalysis</a></span> instead.</p>


<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp">MachineModuleInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a51904840e3bcc15ef2b99a101e972b02">getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a679dec37d40bdc781a69beef91a8ac13">llvm::MachineFunction::initTargetMachineFunctionInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#acb76fa37c3f506da974ee1932b37eeaa">createFrameHelperMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/thunkinserter/#a1a95b72d4c28ba76251171967da03b01">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::createThunkFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#afbccb941c0215a918667f3a574b976b9">llvm::MIRParserImpl::parseMachineFunction</a>.</p>

</div>
</div>

### getTarget() {#aa9ff5ea479131ab7fa913ceb779bd875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine &amp; llvm::MachineModuleInfo::getTarget ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterinlineasm-cpp/#a362579106cd14231f459ca8c00af60ca">EmitInlineAsmStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#a623777b0f29b96919b50ce21c13aa6ae">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::insertThunks</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#afbccb941c0215a918667f3a574b976b9">llvm::MIRParserImpl::parseMachineFunction</a>.</p>

</div>
</div>

### initialize() {#a3274599e96368049f8a8e977ad9fce33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineModuleInfo::initialize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp">MachineModuleInfo.cpp</a>.</p>


<p>Referenced by <a href="#aade9275d95ae9f4c13e7ca45f6e4e609">MachineModuleInfo</a> and <a href="#a1affa4301d540171553df80570290f18">MachineModuleInfo</a>.</p>

</div>
</div>

### insertFunction() {#a36e25573d45fb624fde3da5906679053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineModuleInfo::insertFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &gt; &amp;&amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an externally created <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> <span class="doxyComputerOutput">MF</span> for <span class="doxyComputerOutput">F</span>.</p>

<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp">MachineModuleInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Context {#ac84bf5fc555da846b0ac0b64d6a64c16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext llvm::MachineModuleInfo::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> used for the entire code generator.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

### ExternalContext {#aadcc0d59d9023c515bb79a392f0b3127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext* llvm::MachineModuleInfo::ExternalContext = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

### LastRequest {#ae78062dba9db5950d25c98f045186741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function* llvm::MachineModuleInfo::LastRequest = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used for shortcut/cache.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

### LastResult {#a872c3492eac7d6acf3dfb79336f01ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::MachineModuleInfo::LastResult = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used for shortcut/cache.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

### MachineFunctions {#a2b232ce41e98e7efbf0df50189cbf902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Function*, std::unique_ptr&lt;MachineFunction&gt; &gt; llvm::MachineModuleInfo::MachineFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps IR Functions to their corresponding MachineFunctions.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

### NextFnNum {#abc2e3fda76986c02996854e25bc50e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineModuleInfo::NextFnNum = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Next unique number available for a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

### ObjFileMMI {#a2590107d9dd9879ba188c41fe4f50bc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfoImpl* llvm::MachineModuleInfo::ObjFileMMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the object-file-format-specific implementation of <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a>, which lets targets accumulate whatever info they want.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

### TheModule {#a195034a21da4063df64f80580c999413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module* llvm::MachineModuleInfo::TheModule = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the LLVM <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> being worked on.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

### TM {#a33ee3b43d1d4729bdd69486667e7a98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine&amp; llvm::MachineModuleInfo::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp">MachineModuleInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
