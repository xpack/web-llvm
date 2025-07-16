---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-r600controlflowfinalizer-cpp-/cfstack
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CFStack` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{R600ControlFlowFinalizer.cpp}::CFStack { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">StackItem { <a href="#a4066b999c18627d7eac0fc1c4d9384ef">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26e829789813fb5b0bc2fed20a18bdca">CFStack</a> (const R600Subtarget *st, CallingConv::ID cc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb1f0aa19af4c9fa59e9de12cbe4c0b">getLoopDepth</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f4682ddddf2be78feb32493c77024f0">branchStackContains</a> (CFStack::StackItem)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb42fc4dd57f5e04e5b1520d1665aa58">requiresWorkAroundForInst</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4df2561ac919dbdcf9f6beb463e0a8">getSubEntrySize</a> (CFStack::StackItem Item)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d43bcc97eac8433787efbfc5190ffb5">updateMaxStackSize</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ef55f76ee048b15e914278b184aea6">pushBranch</a> (unsigned Opcode, bool isWQM=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace0acee50018dfffbd3bd808cd72106f">pushLoop</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb00b7a7dd2c04b404cbb1c3d59102b">popBranch</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a258f83b2a91f1105db6188191b6983ee">popLoop</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/r600subtarget">R600Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa583b6f0bb7d7628904418b08f95e375">ST</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="#a4066b999c18627d7eac0fc1c4d9384ef">StackItem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c7c6337354524e9bc0c649d5c9221c0">BranchStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="#a4066b999c18627d7eac0fc1c4d9384ef">StackItem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc36a88519e7d83bbe67bc620a80c2d0">LoopStack</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cbd8d5baba03b690bd10714597d7317">MaxStackSize</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5a7f9b3c46cba55ae60e31d4b92a9c2">CurrentEntries</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56be9baa345c65370427d48d82135a6e">CurrentSubEntries</a> = 0</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### StackItem {#a4066b999c18627d7eac0fc1c4d9384ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{R600ControlFlowFinalizer.cpp}::CFStack::StackItem </td>
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
<td class="doxyEnumItemName">ENTRY<a id="a4066b999c18627d7eac0fc1c4d9384efa30fc97b5ba018d22d227bfe143cdba44"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUB_ENTRY<a id="a4066b999c18627d7eac0fc1c4d9384efa27832201689639025b3461de01ef5049"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_NON_WQM_PUSH<a id="a4066b999c18627d7eac0fc1c4d9384efa97b53dd664b6c0420ad0e060514b418a"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_NON_WQM_PUSH_W_FULL_ENTRY<a id="a4066b999c18627d7eac0fc1c4d9384efa0676126a725fdfa946faae97a852c04c"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CFStack() {#a26e829789813fb5b0bc2fed20a18bdca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{R600ControlFlowFinalizer.cpp}::CFStack::CFStack (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/r600subtarget">R600Subtarget</a> * st, CallingConv::ID cc)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca1a9f243b16678fc294567b72bbe87223">llvm::CallingConv::AMDGPU_VS</a>, <a href="#a3cbd8d5baba03b690bd10714597d7317">MaxStackSize</a> and <a href="#aa583b6f0bb7d7628904418b08f95e375">ST</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### branchStackContains() {#a5f4682ddddf2be78feb32493c77024f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{R600ControlFlowFinalizer.cpp}::CFStack::branchStackContains (<a href="#a4066b999c18627d7eac0fc1c4d9384ef">CFStack::StackItem</a> Item)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>References <a href="#a3c7c6337354524e9bc0c649d5c9221c0">BranchStack</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="#af6ef55f76ee048b15e914278b184aea6">pushBranch</a>.</p>

</div>
</div>

### getLoopDepth() {#afdb1f0aa19af4c9fa59e9de12cbe4c0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{R600ControlFlowFinalizer.cpp}::CFStack::getLoopDepth ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>Reference <a href="#acc36a88519e7d83bbe67bc620a80c2d0">LoopStack</a>.</p>


<p>Referenced by <a href="#afb42fc4dd57f5e04e5b1520d1665aa58">requiresWorkAroundForInst</a>.</p>

</div>
</div>

### getSubEntrySize() {#afc4df2561ac919dbdcf9f6beb463e0a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{R600ControlFlowFinalizer.cpp}::CFStack::getSubEntrySize (<a href="#a4066b999c18627d7eac0fc1c4d9384ef">CFStack::StackItem</a> Item)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a2c2ada0fee5d63ea6a21e292bf24c815">llvm::AMDGPUSubtarget::EVERGREEN</a>, <a href="#a4066b999c18627d7eac0fc1c4d9384efa97b53dd664b6c0420ad0e060514b418a">FIRST_NON_WQM_PUSH</a>, <a href="#a4066b999c18627d7eac0fc1c4d9384efa0676126a725fdfa946faae97a852c04c">FIRST_NON_WQM_PUSH_W_FULL_ENTRY</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a596455aad4b8b4c3aa649e5b227c2ee8">llvm::AMDGPUSubtarget::R700</a>, <a href="#aa583b6f0bb7d7628904418b08f95e375">ST</a> and <a href="#a4066b999c18627d7eac0fc1c4d9384efa27832201689639025b3461de01ef5049">SUB_ENTRY</a>.</p>


<p>Referenced by <a href="#a8cb00b7a7dd2c04b404cbb1c3d59102b">popBranch</a> and <a href="#af6ef55f76ee048b15e914278b184aea6">pushBranch</a>.</p>

</div>
</div>

### popBranch() {#a8cb00b7a7dd2c04b404cbb1c3d59102b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600ControlFlowFinalizer.cpp}::CFStack::popBranch ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>References <a href="#a3c7c6337354524e9bc0c649d5c9221c0">BranchStack</a>, <a href="#ac5a7f9b3c46cba55ae60e31d4b92a9c2">CurrentEntries</a>, <a href="#a56be9baa345c65370427d48d82135a6e">CurrentSubEntries</a>, <a href="#a4066b999c18627d7eac0fc1c4d9384efa30fc97b5ba018d22d227bfe143cdba44">ENTRY</a> and <a href="#afc4df2561ac919dbdcf9f6beb463e0a8">getSubEntrySize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer/#aab0c0f47a6a686867561fa0275a393b1">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction</a>.</p>

</div>
</div>

### popLoop() {#a258f83b2a91f1105db6188191b6983ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600ControlFlowFinalizer.cpp}::CFStack::popLoop ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>References <a href="#ac5a7f9b3c46cba55ae60e31d4b92a9c2">CurrentEntries</a> and <a href="#acc36a88519e7d83bbe67bc620a80c2d0">LoopStack</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer/#aab0c0f47a6a686867561fa0275a393b1">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction</a>.</p>

</div>
</div>

### pushBranch() {#af6ef55f76ee048b15e914278b184aea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600ControlFlowFinalizer.cpp}::CFStack::pushBranch (unsigned Opcode, bool isWQM=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>References <a href="#a3c7c6337354524e9bc0c649d5c9221c0">BranchStack</a>, <a href="#a5f4682ddddf2be78feb32493c77024f0">branchStackContains</a>, <a href="#ac5a7f9b3c46cba55ae60e31d4b92a9c2">CurrentEntries</a>, <a href="#a56be9baa345c65370427d48d82135a6e">CurrentSubEntries</a>, <a href="#a4066b999c18627d7eac0fc1c4d9384efa30fc97b5ba018d22d227bfe143cdba44">ENTRY</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a2c2ada0fee5d63ea6a21e292bf24c815">llvm::AMDGPUSubtarget::EVERGREEN</a>, <a href="#a4066b999c18627d7eac0fc1c4d9384efa97b53dd664b6c0420ad0e060514b418a">FIRST_NON_WQM_PUSH</a>, <a href="#a4066b999c18627d7eac0fc1c4d9384efa0676126a725fdfa946faae97a852c04c">FIRST_NON_WQM_PUSH_W_FULL_ENTRY</a>, <a href="#afc4df2561ac919dbdcf9f6beb463e0a8">getSubEntrySize</a>, <a href="#aa583b6f0bb7d7628904418b08f95e375">ST</a>, <a href="#a4066b999c18627d7eac0fc1c4d9384efa27832201689639025b3461de01ef5049">SUB_ENTRY</a> and <a href="#a1d43bcc97eac8433787efbfc5190ffb5">updateMaxStackSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer/#aab0c0f47a6a686867561fa0275a393b1">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction</a>.</p>

</div>
</div>

### pushLoop() {#ace0acee50018dfffbd3bd808cd72106f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600ControlFlowFinalizer.cpp}::CFStack::pushLoop ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>References <a href="#ac5a7f9b3c46cba55ae60e31d4b92a9c2">CurrentEntries</a>, <a href="#a4066b999c18627d7eac0fc1c4d9384efa30fc97b5ba018d22d227bfe143cdba44">ENTRY</a>, <a href="#acc36a88519e7d83bbe67bc620a80c2d0">LoopStack</a> and <a href="#a1d43bcc97eac8433787efbfc5190ffb5">updateMaxStackSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer/#aab0c0f47a6a686867561fa0275a393b1">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction</a>.</p>

</div>
</div>

### requiresWorkAroundForInst() {#afb42fc4dd57f5e04e5b1520d1665aa58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{R600ControlFlowFinalizer.cpp}::CFStack::requiresWorkAroundForInst (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a56be9baa345c65370427d48d82135a6e">CurrentSubEntries</a>, <a href="#afdb1f0aa19af4c9fa59e9de12cbe4c0b">getLoopDepth</a> and <a href="#aa583b6f0bb7d7628904418b08f95e375">ST</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer/#aab0c0f47a6a686867561fa0275a393b1">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction</a>.</p>

</div>
</div>

### updateMaxStackSize() {#a1d43bcc97eac8433787efbfc5190ffb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600ControlFlowFinalizer.cpp}::CFStack::updateMaxStackSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>References <a href="#ac5a7f9b3c46cba55ae60e31d4b92a9c2">CurrentEntries</a>, <a href="#a56be9baa345c65370427d48d82135a6e">CurrentSubEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a> and <a href="#a3cbd8d5baba03b690bd10714597d7317">MaxStackSize</a>.</p>


<p>Referenced by <a href="#af6ef55f76ee048b15e914278b184aea6">pushBranch</a> and <a href="#ace0acee50018dfffbd3bd808cd72106f">pushLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BranchStack {#a3c7c6337354524e9bc0c649d5c9221c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;StackItem&gt; anonymous{R600ControlFlowFinalizer.cpp}::CFStack::BranchStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>Referenced by <a href="#a5f4682ddddf2be78feb32493c77024f0">branchStackContains</a>, <a href="#a8cb00b7a7dd2c04b404cbb1c3d59102b">popBranch</a> and <a href="#af6ef55f76ee048b15e914278b184aea6">pushBranch</a>.</p>

</div>
</div>

### CurrentEntries {#ac5a7f9b3c46cba55ae60e31d4b92a9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{R600ControlFlowFinalizer.cpp}::CFStack::CurrentEntries = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>Referenced by <a href="#a8cb00b7a7dd2c04b404cbb1c3d59102b">popBranch</a>, <a href="#a258f83b2a91f1105db6188191b6983ee">popLoop</a>, <a href="#af6ef55f76ee048b15e914278b184aea6">pushBranch</a>, <a href="#ace0acee50018dfffbd3bd808cd72106f">pushLoop</a> and <a href="#a1d43bcc97eac8433787efbfc5190ffb5">updateMaxStackSize</a>.</p>

</div>
</div>

### CurrentSubEntries {#a56be9baa345c65370427d48d82135a6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{R600ControlFlowFinalizer.cpp}::CFStack::CurrentSubEntries = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>Referenced by <a href="#a8cb00b7a7dd2c04b404cbb1c3d59102b">popBranch</a>, <a href="#af6ef55f76ee048b15e914278b184aea6">pushBranch</a>, <a href="#afb42fc4dd57f5e04e5b1520d1665aa58">requiresWorkAroundForInst</a> and <a href="#a1d43bcc97eac8433787efbfc5190ffb5">updateMaxStackSize</a>.</p>

</div>
</div>

### LoopStack {#acc36a88519e7d83bbe67bc620a80c2d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;StackItem&gt; anonymous{R600ControlFlowFinalizer.cpp}::CFStack::LoopStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>Referenced by <a href="#afdb1f0aa19af4c9fa59e9de12cbe4c0b">getLoopDepth</a>, <a href="#a258f83b2a91f1105db6188191b6983ee">popLoop</a> and <a href="#ace0acee50018dfffbd3bd808cd72106f">pushLoop</a>.</p>

</div>
</div>

### MaxStackSize {#a3cbd8d5baba03b690bd10714597d7317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{R600ControlFlowFinalizer.cpp}::CFStack::MaxStackSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>Referenced by <a href="#a26e829789813fb5b0bc2fed20a18bdca">CFStack</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer/#aab0c0f47a6a686867561fa0275a393b1">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction</a> and <a href="#a1d43bcc97eac8433787efbfc5190ffb5">updateMaxStackSize</a>.</p>

</div>
</div>

### ST {#aa583b6f0bb7d7628904418b08f95e375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R600Subtarget* anonymous{R600ControlFlowFinalizer.cpp}::CFStack::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>Referenced by <a href="#a26e829789813fb5b0bc2fed20a18bdca">CFStack</a>, <a href="#afc4df2561ac919dbdcf9f6beb463e0a8">getSubEntrySize</a>, <a href="#af6ef55f76ee048b15e914278b184aea6">pushBranch</a> and <a href="#afb42fc4dd57f5e04e5b1520d1665aa58">requiresWorkAroundForInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
