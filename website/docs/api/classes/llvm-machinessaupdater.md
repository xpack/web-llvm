---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinessaupdater
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineSSAUpdater` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> - This class updates SSA form for a set of virtual registers defined in multiple blocks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineSSAUpdater { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">llvm/CodeGen/MachineSSAUpdater.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c4f1d23e625395190b8de6909904904">SSAUpdaterTraits&lt; MachineSSAUpdater &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adac4fc5dcc0c846aeadc57eecb56a2bd">MachineSSAUpdater</a> (MachineFunction &amp;MF, SmallVectorImpl&lt; MachineInstr * &gt; *NewPHI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> constructor. <a href="#adac4fc5dcc0c846aeadc57eecb56a2bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d3972fe0749dd2d651caf3c81910293">MachineSSAUpdater</a> (const MachineSSAUpdater &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a4733b21460575878065857fe5fd11">~MachineSSAUpdater</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3135c5347ab315950fc2b2b1f6a76f">operator=</a> (const MachineSSAUpdater &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00117e47ce48a2a6e82e852dbb342202">Initialize</a> (Register V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize - Reset this object to get ready for a new set of SSA updates. <a href="#a00117e47ce48a2a6e82e852dbb342202">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01bfdaa2826542f165fa1ff6a2aacf1">AddAvailableValue</a> (MachineBasicBlock *BB, Register V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddAvailableValue - Indicate that a rewritten value is available at the end of the specified block with the specified value. <a href="#ab01bfdaa2826542f165fa1ff6a2aacf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac49404ed3c1f98c0889f6b164c39af60">HasValueForBlock</a> (MachineBasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HasValueForBlock - Return true if the <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> already has a value for the specified block. <a href="#ac49404ed3c1f98c0889f6b164c39af60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7bb344ec6cbf767f3fa163c13b4e883">GetValueAtEndOfBlock</a> (MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetValueAtEndOfBlock - Construct SSA form, materializing a value that is live at the end of the specified block. <a href="#aa7bb344ec6cbf767f3fa163c13b4e883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670da7741129c7d591dc19951ecce6c3">GetValueInMiddleOfBlock</a> (MachineBasicBlock *BB, bool ExistingValueOnly=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetValueInMiddleOfBlock - Construct SSA form, materializing a value that is live in the middle of the specified block. <a href="#a670da7741129c7d591dc19951ecce6c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71a08885f7838dc5a544816a357e2ec7">RewriteUse</a> (MachineOperand &amp;U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RewriteUse - Rewrite a use of the symbolic value. <a href="#a71a08885f7838dc5a544816a357e2ec7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a522923da0cd46304c2e8a56dc3e99018">GetValueAtEndOfBlockInternal</a> (MachineBasicBlock *BB, bool ExistingValueOnly=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetValueAtEndOfBlockInternal - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if AvailableVals has an entry for the specified BB and if so, return it. <a href="#a522923da0cd46304c2e8a56dc3e99018">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af19546e032a1694edf3f8a04527d5253">AV</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AvailableVals - This keeps track of which value to use on a per-block basis. <a href="#af19546e032a1694edf3f8a04527d5253">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineregisterinfo/vregattrs">MachineRegisterInfo::VRegAttrs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a447aff697b9e92219a24e15e9f68a13a">RegAttrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> class or bank and <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> of current virtual register. <a href="#a447aff697b9e92219a24e15e9f68a13a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac932e30ce5951acc103c6afc9012c815">InsertedPHIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InsertedPHIs - If this is non-null, the <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> adds all PHI nodes that it creates to the vector. <a href="#ac932e30ce5951acc103c6afc9012c815">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ebf6612d3c634a4fa2085410bef057b">TII</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d4e916dc3ad528fa8dcc02f6aca8169">MRI</a> = nullptr</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> - This class updates SSA form for a set of virtual registers defined in multiple blocks.</p>


<p>This is used when code duplication or another unstructured transformation wants to rewrite a set of uses of one vreg with uses of a set of vregs.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>.</p>


<div class="doxySectionDef">

## Friends

### SSAUpdaterTraits&lt; MachineSSAUpdater &gt; {#a7c4f1d23e625395190b8de6909904904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits">SSAUpdaterTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineSSAUpdater() {#adac4fc5dcc0c846aeadc57eecb56a2bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSSAUpdater::MachineSSAUpdater (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; * NewPHI=nullptr)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> constructor.</p>


<p>If InsertedPHIs is specified, it will be filled in with all PHI Nodes created by rewriting.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>Referenced by <a href="#a6d3972fe0749dd2d651caf3c81910293">MachineSSAUpdater</a> and <a href="#a8d3135c5347ab315950fc2b2b1f6a76f">operator=</a>.</p>

</div>
</div>

### MachineSSAUpdater() {#a6d3972fe0749dd2d651caf3c81910293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineSSAUpdater::MachineSSAUpdater (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> &amp;)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>.</p>


<p>Reference <a href="#adac4fc5dcc0c846aeadc57eecb56a2bd">MachineSSAUpdater</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineSSAUpdater() {#a39a4733b21460575878065857fe5fd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSSAUpdater::~MachineSSAUpdater ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a8d3135c5347ab315950fc2b2b1f6a76f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSSAUpdater &amp; llvm::MachineSSAUpdater::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> &amp;)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>.</p>


<p>Reference <a href="#adac4fc5dcc0c846aeadc57eecb56a2bd">MachineSSAUpdater</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddAvailableValue() {#ab01bfdaa2826542f165fa1ff6a2aacf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineSSAUpdater::AddAvailableValue (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddAvailableValue - Indicate that a rewritten value is available at the end of the specified block with the specified value.</p>


<p>AddAvailableValue - Indicate that a rewritten value is available in the specified block with the specified value.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a8c3648be397b04fce3a02bd44212659e">getAvailableVals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a1c0f17f40e0399c6d151a50e99797e58">llvm::TailDuplicator::tailDuplicateAndUpdate</a>.</p>

</div>
</div>

### GetValueAtEndOfBlock() {#aa7bb344ec6cbf767f3fa163c13b4e883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MachineSSAUpdater::GetValueAtEndOfBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetValueAtEndOfBlock - Construct SSA form, materializing a value that is live at the end of the specified block.</p>

<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>

</div>
</div>

### GetValueInMiddleOfBlock() {#a670da7741129c7d591dc19951ecce6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MachineSSAUpdater::GetValueInMiddleOfBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, bool ExistingValueOnly=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetValueInMiddleOfBlock - Construct SSA form, materializing a value that is live in the middle of the specified block.</p>


<p>If ExistingValueOnly is true then this will only return an existing value or $noreg; otherwise new instructions may be inserted to materialize a value.</p>


<p>GetValueInMiddleOfBlock is the same as GetValueAtEndOfBlock except in one important case: if there is a definition of the rewritten value after the 'use' in BB. Consider code like this:</p>



<pre><code> X1 = ...
</code></pre>


<p>SomeBB: <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use(X)</a> X2 = ... br Cond, SomeBB, OutBB</p>


<p>In this case, there are two values (X1 and X2) added to the AvailableVals set by the client of the rewriter, and those values are both live out of their respective blocks. However, the use of X happens in the <em>middle</em> of a block. Because of this, we need to insert a new PHI node in SomeBB to merge the appropriate values, and this value isn't live out of the block.</p>


<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a095ce2d870dadf620a4c887ecc0efef8">llvm::MachineBasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a7f0521fa2de44271fd4b909ea7351ef3">llvm::MachineBasicBlock::getFirstTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#ac49404ed3c1f98c0889f6b164c39af60">HasValueForBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a18679ba04ac07baa9c502ce555b48859">InsertNewDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a37fa340555fb189bce42efadf42c5253">llvm::MachineInstr::isConstantValuePHI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a43b22ba78d684fd69b551c4c04426e3d">LookForIdenticalPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a877507fda31c207ec36a018784369708">llvm::MachineBasicBlock::pred_empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#addd80df79ba902914c7d8a52e3896b79">llvm::MachineBasicBlock::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>


<p>Referenced by <a href="#a71a08885f7838dc5a544816a357e2ec7">RewriteUse</a> and <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a1c0f17f40e0399c6d151a50e99797e58">llvm::TailDuplicator::tailDuplicateAndUpdate</a>.</p>

</div>
</div>

### HasValueForBlock() {#ac49404ed3c1f98c0889f6b164c39af60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineSSAUpdater::HasValueForBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HasValueForBlock - Return true if the <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> already has a value for the specified block.</p>

<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a8c3648be397b04fce3a02bd44212659e">getAvailableVals</a>.</p>


<p>Referenced by <a href="#a670da7741129c7d591dc19951ecce6c3">GetValueInMiddleOfBlock</a>.</p>

</div>
</div>

### Initialize() {#a00117e47ce48a2a6e82e852dbb342202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineSSAUpdater::Initialize (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize - Reset this object to get ready for a new set of SSA updates.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adf4e7878fc0b3b8dcde545178564190d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::clear</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a8c3648be397b04fce3a02bd44212659e">getAvailableVals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a1c0f17f40e0399c6d151a50e99797e58">llvm::TailDuplicator::tailDuplicateAndUpdate</a>.</p>

</div>
</div>

### RewriteUse() {#a71a08885f7838dc5a544816a357e2ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineSSAUpdater::RewriteUse (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RewriteUse - Rewrite a use of the symbolic value.</p>


<p>This handles PHI nodes, which use their value in the corresponding predecessor. Note that this will not work if the use is supposed to be rewritten to a value defined in the same block as the use, but above it. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> 'AddAvailableValue's added for the use's block will be considered to be below it.</p>


<p>This handles PHI nodes, which use their value in the corresponding predecessor.</p>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a222437d73da212a119632c8fe307813d">findCorrespondingPred</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa7dc7faaab4856b8f0014b8283e26c7b">llvm::MachineBasicBlock::getFirstNonPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a670da7741129c7d591dc19951ecce6c3">GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a18679ba04ac07baa9c502ce555b48859">InsertNewDef</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a1c0f17f40e0399c6d151a50e99797e58">llvm::TailDuplicator::tailDuplicateAndUpdate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### GetValueAtEndOfBlockInternal() {#a522923da0cd46304c2e8a56dc3e99018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MachineSSAUpdater::GetValueAtEndOfBlockInternal (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, bool ExistingValueOnly=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetValueAtEndOfBlockInternal - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if AvailableVals has an entry for the specified BB and if so, return it.</p>


<p>If not, construct SSA form by first calculating the required placement of PHIs and then inserting new PHIs where needed.</p>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AV {#af19546e032a1694edf3f8a04527d5253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::MachineSSAUpdater::AV = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AvailableVals - This keeps track of which value to use on a per-block basis.</p>


<p>When we insert PHI nodes, we keep track of them here.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>.</p>

</div>
</div>

### InsertedPHIs {#ac932e30ce5951acc103c6afc9012c815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;MachineInstr*&gt;* llvm::MachineSSAUpdater::InsertedPHIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>InsertedPHIs - If this is non-null, the <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> adds all PHI nodes that it creates to the vector.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>.</p>

</div>
</div>

### MRI {#a6d4e916dc3ad528fa8dcc02f6aca8169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::MachineSSAUpdater::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>.</p>

</div>
</div>

### RegAttrs {#a447aff697b9e92219a24e15e9f68a13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo::VRegAttrs llvm::MachineSSAUpdater::RegAttrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> class or bank and <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> of current virtual register.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>.</p>

</div>
</div>

### TII {#a8ebf6612d3c634a4fa2085410bef057b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::MachineSSAUpdater::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessaupdater-h">MachineSSAUpdater.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
