---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/statepointopers
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StatepointOpers` Class Reference

<p>MI-level Statepoint operands. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::StatepointOpers { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">llvm/CodeGen/StackMaps.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a2d6d58a6fe60631ebcf02aa80ee18a78">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a731014bf8fd868b7c311b5b9c50e53cc">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a051a976c9ed4271490fdeef74ae90c93">StatepointOpers</a> (const MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a289e1a5ef6161b0fadbbf111e2202b63">getIDPos</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of statepoint <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> operand. <a href="#a289e1a5ef6161b0fadbbf111e2202b63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd9e6bbd445b4fa79a9cc1495c522a51">getNBytesPos</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of Num Patch Bytes operand. <a href="#abd9e6bbd445b4fa79a9cc1495c522a51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eac7e12c3d75912cbabca5d885486d5">getNCallArgsPos</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of Num Call Arguments operand. <a href="#a6eac7e12c3d75912cbabca5d885486d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdfbc7a83c5d0400c01becf8ff27eba3">getVarIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get starting index of non call related arguments (calling convention, statepoint flags, vm state and gc state). <a href="#afdfbc7a83c5d0400c01becf8ff27eba3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a561d1afc8f2935939a4a113510bd7c96">getCCIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of Calling Convention operand. <a href="#a561d1afc8f2935939a4a113510bd7c96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d95624b4914f95a0a9c37c3c51007d">getFlagsIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of Flags operand. <a href="#ae7d95624b4914f95a0a9c37c3c51007d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ccc324192981f7ce3091453bb0b68a5">getNumDeoptArgsIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of Number Deopt Arguments operand. <a href="#a9ccc324192981f7ce3091453bb0b68a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af92f104836fb6bba872e578682a0e65f">getID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the given statepoint. <a href="#af92f104836fb6bba872e578682a0e65f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eeee60ca2931edc9e1f653fbc66373c">getNumPatchBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of patchable bytes the given statepoint should emit. <a href="#a0eeee60ca2931edc9e1f653fbc66373c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95c1e25f9b75ebe8647c3576add3c8b3">getCallTarget</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the target of the underlying call. <a href="#a95c1e25f9b75ebe8647c3576add3c8b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b33b20fc6eff19f9b382c97ee7482b7">getCallingConv</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the calling convention. <a href="#a3b33b20fc6eff19f9b382c97ee7482b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f1c9d432bb4e063d215f60efd296f2">getFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the statepoint flags. <a href="#ad1f1c9d432bb4e063d215f60efd296f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6e1d46e941251cb8eb8653fd58515e6">getNumDeoptArgs</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74489068197c4dc2f59abb1ee9da80e2">getNumGcMapEntriesIdx</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of number of gc map entries. <a href="#a74489068197c4dc2f59abb1ee9da80e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72f688fbc467b422cbaa2863879853b0">getNumAllocaIdx</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of number of gc allocas. <a href="#a72f688fbc467b422cbaa2863879853b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afec1cbe3c73e6d6b86e5d6b00815dc2e">getNumGCPtrIdx</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of number of GC pointers. <a href="#afec1cbe3c73e6d6b86e5d6b00815dc2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ea607a43ea9b3eb84ed72058693d4a">getFirstGCPtrIdx</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of first GC pointer operand of -1 if there are none. <a href="#a85ea607a43ea9b3eb84ed72058693d4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670096de4a32a058514ddba685ececfe">getGCPointerMap</a> (SmallVectorImpl&lt; std::pair&lt; unsigned, unsigned &gt; &gt; &amp;GCMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get vector of base/derived pairs from statepoint. <a href="#a670096de4a32a058514ddba685ececfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa5a7e5f9b626c9fb0b9d66235146ac3">isFoldableReg</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if Reg is used only in operands which can be folded to stack usage. <a href="#afa5a7e5f9b626c9fb0b9d66235146ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac48c50805ee5213ac182658797eec379">MI</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c2120c941870fb121b356d9f173e69">NumDefs</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98142b54421704d5cd35e164563391e">isFoldableReg</a> (const MachineInstr *MI, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if Reg is used only in operands of MI which can be folded to stack usage and MI is a statepoint instruction. <a href="#af98142b54421704d5cd35e164563391e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>MI-level Statepoint operands.</p>


<p>Statepoint operands take the form: &lt;id&gt;, &lt;num patch bytes &gt;, &lt;num call arguments&gt;, &lt;call target&gt;, [call arguments...], &lt;StackMaps::ConstantOp&gt;, &lt;calling convention&gt;, &lt;StackMaps::ConstantOp&gt;, &lt;statepoint flags&gt;, &lt;StackMaps::ConstantOp&gt;, &lt;num deopt args&gt;, [deopt args...], &lt;StackMaps::ConstantOp&gt;, &lt;num gc pointer args&gt;, [gc pointer args...], &lt;StackMaps::ConstantOp&gt;, &lt;num gc allocas&gt;, [gc allocas args...], &lt;StackMaps::ConstantOp&gt;, &lt;num  entries in gc map&gt;, [base/derived pairs] base/derived pairs in gc map are logical indices into &lt;gc pointer args&gt; section. All gc pointers assigned to VRegs produce new value (in form of MI Def operand) and are tied to it.</p>


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a2d6d58a6fe60631ebcf02aa80ee18a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">IDPos<a id="a2d6d58a6fe60631ebcf02aa80ee18a78a9bbecb89af184f1fed77a1c2da4904b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NBytesPos<a id="a2d6d58a6fe60631ebcf02aa80ee18a78a7bebe4a946634233fd55663c6f64e94d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NCallArgsPos<a id="a2d6d58a6fe60631ebcf02aa80ee18a78a605ee98764e053ff86bdaed7d68fa3e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallTargetPos<a id="a2d6d58a6fe60631ebcf02aa80ee18a78a42ad089d4ce0f50efb16beb1c718abb6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MetaEnd<a id="a2d6d58a6fe60631ebcf02aa80ee18a78a352a7478b9a25f316d01ed60d8c5ff4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### anonymous enum  {#a731014bf8fd868b7c311b5b9c50e53cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">CCOffset<a id="a731014bf8fd868b7c311b5b9c50e53cca5f08674883ceeb29a017cec5e99dd9c8"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FlagsOffset<a id="a731014bf8fd868b7c311b5b9c50e53ccac811aed677b40efbe1693a2a91c0865c"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumDeoptOperandsOffset<a id="a731014bf8fd868b7c311b5b9c50e53ccaa2d177682126d680654bb6c714d5ca6c"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### StatepointOpers() {#a051a976c9ed4271490fdeef74ae90c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StatepointOpers::StatepointOpers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Referenced by <a href="#af98142b54421704d5cd35e164563391e">isFoldableReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCallingConv() {#a3b33b20fc6eff19f9b382c97ee7482b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallingConv::ID llvm::StatepointOpers::getCallingConv ()</td>
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

<p>Return the calling convention.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#a561d1afc8f2935939a4a113510bd7c96">getCCIdx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointprocessor/#add4104e44eed414e68aa92637129b7e1">anonymous{FixupStatepointCallerSaved.cpp}::StatepointProcessor::process</a>.</p>

</div>
</div>

### getCallTarget() {#a95c1e25f9b75ebe8647c3576add3c8b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand &amp; llvm::StatepointOpers::getCallTarget ()</td>
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

<p>Return the target of the underlying call.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a010b554002b5c2fdbc6e2d2b64afedb9">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a50863928ef6e46cfbe213995fd4974c2">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerSTATEPOINT</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#a8022309e0fcca527f4a1a49b8a8ba922">llvm::LoongArchAsmPrinter::LowerSTATEPOINT</a>.</p>

</div>
</div>

### getCCIdx() {#a561d1afc8f2935939a4a113510bd7c96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StatepointOpers::getCCIdx ()</td>
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

<p>Get index of Calling Convention operand.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#afdfbc7a83c5d0400c01becf8ff27eba3">getVarIdx</a>.</p>


<p>Referenced by <a href="#a3b33b20fc6eff19f9b382c97ee7482b7">getCallingConv</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getFirstGCPtrIdx() {#a85ea607a43ea9b3eb84ed72058693d4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int StatepointOpers::getFirstGCPtrIdx ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get index of first GC pointer operand of -1 if there are none.</p>

<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp/#a1c968131e0fad022dfb30816a44bf31d">getConstMetaVal</a> and <a href="#afec1cbe3c73e6d6b86e5d6b00815dc2e">getNumGCPtrIdx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa2dfd6ae7ded046f5e5e03e0f745d5c3">llvm::MachineInstr::findTiedOperandIdx</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getFlags() {#ad1f1c9d432bb4e063d215f60efd296f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::StatepointOpers::getFlags ()</td>
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

<p>Return the statepoint flags.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#ae7d95624b4914f95a0a9c37c3c51007d">getFlagsIdx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#a801fcd2cb84f0d0292a77e675c7c492c">hasLiveThroughUse</a> and <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointprocessor/#add4104e44eed414e68aa92637129b7e1">anonymous{FixupStatepointCallerSaved.cpp}::StatepointProcessor::process</a>.</p>

</div>
</div>

### getFlagsIdx() {#ae7d95624b4914f95a0a9c37c3c51007d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StatepointOpers::getFlagsIdx ()</td>
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

<p>Get index of Flags operand.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#afdfbc7a83c5d0400c01becf8ff27eba3">getVarIdx</a>.</p>


<p>Referenced by <a href="#ad1f1c9d432bb4e063d215f60efd296f2">getFlags</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getGCPointerMap() {#a670096de4a32a058514ddba685ececfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StatepointOpers::getGCPointerMap (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; unsigned, unsigned &gt; &gt; &amp; GCMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get vector of base/derived pairs from statepoint.</p>


<p>Elements are indices into GC Pointer operand list (logical). Returns number of elements in GCMap.</p>


<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp/#a1c968131e0fad022dfb30816a44bf31d">getConstMetaVal</a>, <a href="#a74489068197c4dc2f59abb1ee9da80e2">getNumGcMapEntriesIdx</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getID() {#af92f104836fb6bba872e578682a0e65f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::StatepointOpers::getID ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the given statepoint.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#abf7e8cc29c69ba598ca74cdaf4684f1b">llvm::StackMaps::recordStatepoint</a>.</p>

</div>
</div>

### getIDPos() {#a289e1a5ef6161b0fadbbf111e2202b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StatepointOpers::getIDPos ()</td>
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

<p>Get index of statepoint <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> operand.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getNBytesPos() {#abd9e6bbd445b4fa79a9cc1495c522a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StatepointOpers::getNBytesPos ()</td>
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

<p>Get index of Num Patch Bytes operand.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getNCallArgsPos() {#a6eac7e12c3d75912cbabca5d885486d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StatepointOpers::getNCallArgsPos ()</td>
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

<p>Get index of Num Call Arguments operand.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getNumAllocaIdx() {#a72f688fbc467b422cbaa2863879853b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StatepointOpers::getNumAllocaIdx ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get index of number of gc allocas.</p>

<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp/#a1c968131e0fad022dfb30816a44bf31d">getConstMetaVal</a>, <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#a0678a1f52ff04158310e4157e81282f6">llvm::StackMaps::getNextMetaArgIdx</a> and <a href="#afec1cbe3c73e6d6b86e5d6b00815dc2e">getNumGCPtrIdx</a>.</p>


<p>Referenced by <a href="#a74489068197c4dc2f59abb1ee9da80e2">getNumGcMapEntriesIdx</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getNumDeoptArgs() {#ac6e1d46e941251cb8eb8653fd58515e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::StatepointOpers::getNumDeoptArgs ()</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#a9ccc324192981f7ce3091453bb0b68a5">getNumDeoptArgsIdx</a>.</p>

</div>
</div>

### getNumDeoptArgsIdx() {#a9ccc324192981f7ce3091453bb0b68a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StatepointOpers::getNumDeoptArgsIdx ()</td>
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

<p>Get index of Number Deopt Arguments operand.</p>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#afdfbc7a83c5d0400c01becf8ff27eba3">getVarIdx</a>.</p>


<p>Referenced by <a href="#ac6e1d46e941251cb8eb8653fd58515e6">getNumDeoptArgs</a>, <a href="#afec1cbe3c73e6d6b86e5d6b00815dc2e">getNumGCPtrIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#a801fcd2cb84f0d0292a77e675c7c492c">hasLiveThroughUse</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getNumGcMapEntriesIdx() {#a74489068197c4dc2f59abb1ee9da80e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StatepointOpers::getNumGcMapEntriesIdx ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get index of number of gc map entries.</p>

<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp/#a1c968131e0fad022dfb30816a44bf31d">getConstMetaVal</a>, <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#a0678a1f52ff04158310e4157e81282f6">llvm::StackMaps::getNextMetaArgIdx</a> and <a href="#a72f688fbc467b422cbaa2863879853b0">getNumAllocaIdx</a>.</p>


<p>Referenced by <a href="#a670096de4a32a058514ddba685ececfe">getGCPointerMap</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getNumGCPtrIdx() {#afec1cbe3c73e6d6b86e5d6b00815dc2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StatepointOpers::getNumGCPtrIdx ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get index of number of GC pointers.</p>

<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp/#a1c968131e0fad022dfb30816a44bf31d">getConstMetaVal</a>, <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#a0678a1f52ff04158310e4157e81282f6">llvm::StackMaps::getNextMetaArgIdx</a> and <a href="#a9ccc324192981f7ce3091453bb0b68a5">getNumDeoptArgsIdx</a>.</p>


<p>Referenced by <a href="#a85ea607a43ea9b3eb84ed72058693d4a">getFirstGCPtrIdx</a>, <a href="#a72f688fbc467b422cbaa2863879853b0">getNumAllocaIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#a801fcd2cb84f0d0292a77e675c7c492c">hasLiveThroughUse</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getNumPatchBytes() {#a0eeee60ca2931edc9e1f653fbc66373c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::StatepointOpers::getNumPatchBytes ()</td>
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

<p>Return the number of patchable bytes the given statepoint should emit.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a1bf38b3bbe867377cde6e530a0256b29">llvm::AArch64InstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#ae4bbae04e39720c0cdd662233f32613d">llvm::LoongArchInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a8424c147a24cf4d707de1b7392597e48">llvm::RISCVInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a010b554002b5c2fdbc6e2d2b64afedb9">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a50863928ef6e46cfbe213995fd4974c2">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerSTATEPOINT</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#a8022309e0fcca527f4a1a49b8a8ba922">llvm::LoongArchAsmPrinter::LowerSTATEPOINT</a>.</p>

</div>
</div>

### getVarIdx() {#afdfbc7a83c5d0400c01becf8ff27eba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StatepointOpers::getVarIdx ()</td>
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

<p>Get starting index of non call related arguments (calling convention, statepoint flags, vm state and gc state).</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Referenced by <a href="#a561d1afc8f2935939a4a113510bd7c96">getCCIdx</a>, <a href="#ae7d95624b4914f95a0a9c37c3c51007d">getFlagsIdx</a>, <a href="#a9ccc324192981f7ce3091453bb0b68a5">getNumDeoptArgsIdx</a>, <a href="#afa5a7e5f9b626c9fb0b9d66235146ac3">isFoldableReg</a> and <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#abf7e8cc29c69ba598ca74cdaf4684f1b">llvm::StackMaps::recordStatepoint</a>.</p>

</div>
</div>

### isFoldableReg() {#afa5a7e5f9b626c9fb0b9d66235146ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StatepointOpers::isFoldableReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if Reg is used only in operands which can be folded to stack usage.</p>

<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>Reference <a href="#afdfbc7a83c5d0400c01becf8ff27eba3">getVarIdx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MI {#ac48c50805ee5213ac182658797eec379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* llvm::StatepointOpers::MI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### NumDefs {#ab9c2120c941870fb121b356d9f173e69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StatepointOpers::NumDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isFoldableReg() {#af98142b54421704d5cd35e164563391e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StatepointOpers::isFoldableReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Return true if Reg is used only in operands of MI which can be folded to stack usage and MI is a statepoint instruction.</p>

<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>Reference <a href="#a051a976c9ed4271490fdeef74ae90c93">StatepointOpers</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
