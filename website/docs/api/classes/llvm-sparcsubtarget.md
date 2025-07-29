---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sparcsubtarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SparcSubtarget` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SparcSubtarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">Target/Sparc/SparcSubtarget.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/sparcgensubtargetinfo">SparcGenSubtargetInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a43b3ddac43983efd358ce37662807">SparcSubtarget</a> (const StringRef &amp;CPU, const StringRef &amp;TuneCPU, const StringRef &amp;FS, const TargetMachine &amp;TM, bool is64bit)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo">SparcInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae020fa66f18a67f9136a09bf074a28ee">getInstrInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetframelowering">TargetFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76cf726da2adea389a4e1ab3170e970d">getFrameLowering</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sparcregisterinfo">SparcRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bca6a9cd0e58cf68334997f07739658">getRegisterInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering">SparcTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ccdf5e899491a2c59e7aeb6cc949ff">getTargetLowering</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0330735b81962a965e8c92d4ff2e794">getSelectionDAGInfo</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f99a8689f81e1ad6f1de953d21d6540">enableMachineScheduler</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd94c8282ae48d68bf3374596956a61e">ParseSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options. <a href="#acd94c8282ae48d68bf3374596956a61e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparcsubtarget">SparcSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad55eb63496266a67be2cd32515446e57">initializeSubtargetDependencies</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8302f5e3165c69b082f18b56abf8a6b">is64Bit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ecd5e4ac0477e60d25858e8c758a669">getStackPointerBias</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The 64-bit ABI uses biased stack and frame pointers, so the stack frame of the current function is the area from [sp+BIAS] to [fp+BIAS]. <a href="#a0ecd5e4ac0477e60d25858e8c758a669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad568f7f47221378a1a8a49372b89b981">isRegisterReserved</a> (MCPhysReg PhysReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f46b3be7b0b8d54ffd86ab4ac8e2c55">getAdjustedFrameSize</a> (int stackSize) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a actual stack size as determined by FrameInfo, this function returns adjusted framesize which includes space for register window spills and arguments. <a href="#a3f46b3be7b0b8d54ffd86ab4ac8e2c55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c44693a97a032f747327cbf3d340bb6">isTargetLinux</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e44f0001a06505b616d72d54447780d">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2c655af6f785e47b4282604198c8e6">ReserveRegister</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad45b7e6e9b3117e6f8839b1ff79b3fe6">TargetTriple</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fe071384f01da9aa2d3c84494e02b98">Is64Bit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo">SparcInstrInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac45bdb1af38ad8f9740102b472aaf21">InstrInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering">SparcTargetLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd47264d8c05f237f4109a0e2467423">TLInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2586839086dea0d3cabe4f773015f30">TSInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparcframelowering">SparcFrameLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b4d160fe55fd72686c40ab7f184484e">FrameLowering</a></td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SparcSubtarget() {#a30a43b3ddac43983efd358ce37662807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparcSubtarget::SparcSubtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; CPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; TuneCPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, bool is64bit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-cpp">SparcSubtarget.cpp</a>.</p>


<p>References <a href="#ad55eb63496266a67be2cd32515446e57">initializeSubtargetDependencies</a> and <a href="#aa8302f5e3165c69b082f18b56abf8a6b">is64Bit</a>.</p>


<p>Referenced by <a href="#ad55eb63496266a67be2cd32515446e57">initializeSubtargetDependencies</a> and <a href="#acd94c8282ae48d68bf3374596956a61e">ParseSubtargetFeatures</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enableMachineScheduler() {#a5f99a8689f81e1ad6f1de953d21d6540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SparcSubtarget::enableMachineScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-cpp">SparcSubtarget.cpp</a>.</p>

</div>
</div>

### getAdjustedFrameSize() {#a3f46b3be7b0b8d54ffd86ab4ac8e2c55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SparcSubtarget::getAdjustedFrameSize (int stackSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a actual stack size as determined by FrameInfo, this function returns adjusted framesize which includes space for register window spills and arguments.</p>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-cpp">SparcSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a> and <a href="#aa8302f5e3165c69b082f18b56abf8a6b">is64Bit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### getFrameLowering() {#a76cf726da2adea389a4e1ab3170e970d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetFrameLowering * llvm::SparcSubtarget::getFrameLowering ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>

</div>
</div>

### getInstrInfo() {#ae020fa66f18a67f9136a09bf074a28ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SparcInstrInfo * llvm::SparcSubtarget::getInstrInfo ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/sparcregisterinfo/#a5e8cc743ac1b84dd6f00bcee3c9e125d">llvm::SparcRegisterInfo::eliminateFrameIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### getRegisterInfo() {#a0bca6a9cd0e58cf68334997f07739658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SparcRegisterInfo * llvm::SparcSubtarget::getRegisterInfo ()</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#ac3af49ca4a1c47f7c01abaae4e8092bf">llvm::SparcFrameLowering::getFrameIndexReference</a> and <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#a23bf1a3ca7dacaf7d37090cc7816dfe1">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::PrintAsmOperand</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#ae0330735b81962a965e8c92d4ff2e794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SelectionDAGTargetInfo * llvm::SparcSubtarget::getSelectionDAGInfo ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>

</div>
</div>

### getStackPointerBias() {#a0ecd5e4ac0477e60d25858e8c758a669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::SparcSubtarget::getStackPointerBias ()</td>
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

<p>The 64-bit ABI uses biased stack and frame pointers, so the stack frame of the current function is the area from [sp+BIAS] to [fp+BIAS].</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>


<p>Reference <a href="#aa8302f5e3165c69b082f18b56abf8a6b">is64Bit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a13f1c4a0ad3bb43fd704953f000211b9">getFRAMEADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#ac3af49ca4a1c47f7c01abaae4e8092bf">llvm::SparcFrameLowering::getFrameIndexReference</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a5a204a396ded16cd692c0dc91ce216f4">LowerDYNAMIC_STACKALLOC</a>.</p>

</div>
</div>

### getTargetLowering() {#a21ccdf5e899491a2c59e7aeb6cc949ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SparcTargetLowering * llvm::SparcSubtarget::getTargetLowering ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>

</div>
</div>

### initializeSubtargetDependencies() {#ad55eb63496266a67be2cd32515446e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparcSubtarget &amp; SparcSubtarget::initializeSubtargetDependencies (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-cpp">SparcSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#acd94c8282ae48d68bf3374596956a61e">ParseSubtargetFeatures</a> and <a href="#a30a43b3ddac43983efd358ce37662807">SparcSubtarget</a>.</p>


<p>Referenced by <a href="#a30a43b3ddac43983efd358ce37662807">SparcSubtarget</a>.</p>

</div>
</div>

### is64Bit() {#aa8302f5e3165c69b082f18b56abf8a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparcSubtarget::is64Bit ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#a1bceb770fac96abbd821f09214c5d321">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::emitFunctionBodyStart</a>, <a href="#a3f46b3be7b0b8d54ffd86ab4ac8e2c55">getAdjustedFrameSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a13f1c4a0ad3bb43fd704953f000211b9">getFRAMEADDR</a>, <a href="/web-llvm/docs/api/structs/llvm/sparcregisterinfo/#a808307b2f47008bb7af6d439eab6f9d7">llvm::SparcRegisterInfo::getPointerRegClass</a>, <a href="/web-llvm/docs/api/structs/llvm/sparcregisterinfo/#aa433f99693e51b79b0ed2d9209427aab">llvm::SparcRegisterInfo::getReservedRegs</a>, <a href="#a0ecd5e4ac0477e60d25858e8c758a669">getStackPointerBias</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a5a204a396ded16cd692c0dc91ce216f4">LowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afa7dd71b99cc3f038bc3f91104cf66ee">LowerRETURNADDR</a> and <a href="#a30a43b3ddac43983efd358ce37662807">SparcSubtarget</a>.</p>

</div>
</div>

### isRegisterReserved() {#ad568f7f47221378a1a8a49372b89b981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparcSubtarget::isRegisterReserved (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/sparcregisterinfo/#aa433f99693e51b79b0ed2d9209427aab">llvm::SparcRegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### isTargetLinux() {#a9c44693a97a032f747327cbf3d340bb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparcSubtarget::isTargetLinux ()</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>

</div>
</div>

### ParseSubtargetFeatures() {#acd94c8282ae48d68bf3374596956a61e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SparcSubtarget::ParseSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options.</p>


<p>Definition of function is auto generated by tblgen.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>


<p>Reference <a href="#a30a43b3ddac43983efd358ce37662807">SparcSubtarget</a>.</p>


<p>Referenced by <a href="#ad55eb63496266a67be2cd32515446e57">initializeSubtargetDependencies</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a2e44f0001a06505b616d72d54447780d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SparcSubtarget::anchor ()</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-cpp">SparcSubtarget.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FrameLowering {#a2b4d160fe55fd72686c40ab7f184484e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparcFrameLowering llvm::SparcSubtarget::FrameLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>

</div>
</div>

### InstrInfo {#aac45bdb1af38ad8f9740102b472aaf21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparcInstrInfo llvm::SparcSubtarget::InstrInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>

</div>
</div>

### Is64Bit {#a8fe071384f01da9aa2d3c84494e02b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparcSubtarget::Is64Bit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>

</div>
</div>

### ReserveRegister {#a4b2c655af6f785e47b4282604198c8e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::SparcSubtarget::ReserveRegister</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>

</div>
</div>

### TargetTriple {#ad45b7e6e9b3117e6f8839b1ff79b3fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::SparcSubtarget::TargetTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>

</div>
</div>

### TLInfo {#adbd47264d8c05f237f4109a0e2467423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparcTargetLowering llvm::SparcSubtarget::TLInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>

</div>
</div>

### TSInfo {#ad2586839086dea0d3cabe4f773015f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAGTargetInfo llvm::SparcSubtarget::TSInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-cpp">SparcSubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
