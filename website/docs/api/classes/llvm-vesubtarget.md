---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vesubtarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VESubtarget` Class



## Declaration

<div class="doxyDeclaration">
class llvm::VESubtarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">Target/VE/VESubtarget.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/vegensubtargetinfo">VEGenSubtargetInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad30b4b6d4e3721ff97e97fb248ec4cf9">VESubtarget</a> (const Triple &amp;TT, const std::string &amp;CPU, const std::string &amp;FS, const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo">VEInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b42641fc5f60a36212147b75fe3669">getInstrInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/veframelowering">VEFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4a1aa0e342ede17960fb5f6f09ab2ef">getFrameLowering</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/veregisterinfo">VERegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecdc3319eb01ec80a69ace4e6111a284">getRegisterInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering">VETargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ac228c9a9549c1af3a761170034d30">getTargetLowering</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7c9b64ef05827af96d4847b8bf02c2e">getSelectionDAGInfo</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2804ca33c9d829911f72a0533dacb824">enableMachineScheduler</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27cb5a80d551b6dafd29ae91c6a67e72">enableVPU</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2238b9fd6c4557b037c645e664c1e6a0">ParseSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options. <a href="#a2238b9fd6c4557b037c645e664c1e6a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vesubtarget">VESubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93f03b43c499eb1e609399b721681624">initializeSubtargetDependencies</a> (StringRef CPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a73c3c6631ebcb090858d4cb244ac8">getAdjustedFrameSize</a> (uint64_t FrameSize) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a actual stack size as determined by FrameInfo, this function returns adjusted framesize which includes space for RSA, return address, and frame poitner. <a href="#a20a73c3c6631ebcb090858d4cb244ac8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b88357c6972aff211e829aee4da3658">getRsaSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of RSA, return address, and frame pointer as described in <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>. <a href="#a3b88357c6972aff211e829aee4da3658">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63574f2ac18f5b5cea01f1673c3ab39b">isTargetLinux</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765e6f0899384af01da609b476491709">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4d7a5de07e23b1d1db7754dcf3bb27a">TargetTriple</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a38ec828a2c77a14268149cc6bb99db">EnableVPU</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Features {. <a href="#a1a38ec828a2c77a14268149cc6bb99db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/veinstrinfo">VEInstrInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab09902afa0aa057127704d1cbb5a5be5">InstrInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} Features <a href="#ab09902afa0aa057127704d1cbb5a5be5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vetargetlowering">VETargetLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7754bf9c3dcfade1ae761772c4508304">TLInfo</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a285ea312b748d7fbb0338fdf648d7cc6">TSInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/veframelowering">VEFrameLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386c05f7da6c23293e38ee97fdc8272b">FrameLowering</a></td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VESubtarget() {#ad30b4b6d4e3721ff97e97fb248ec4cf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VESubtarget::VESubtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; CPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-cpp">VESubtarget.cpp</a>.</p>


<p>Reference <a href="#a93f03b43c499eb1e609399b721681624">initializeSubtargetDependencies</a>.</p>


<p>Referenced by <a href="#a93f03b43c499eb1e609399b721681624">initializeSubtargetDependencies</a> and <a href="#a2238b9fd6c4557b037c645e664c1e6a0">ParseSubtargetFeatures</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enableMachineScheduler() {#a2804ca33c9d829911f72a0533dacb824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VESubtarget::enableMachineScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-cpp">VESubtarget.cpp</a>.</p>

</div>
</div>

### enableVPU() {#a27cb5a80d551b6dafd29ae91c6a67e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VESubtarget::enableVPU ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>

</div>
</div>

### getAdjustedFrameSize() {#a20a73c3c6631ebcb090858d4cb244ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t VESubtarget::getAdjustedFrameSize (uint64_t FrameSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a actual stack size as determined by FrameInfo, this function returns adjusted framesize which includes space for RSA, return address, and frame poitner.</p>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-cpp">VESubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="#ad4a1aa0e342ede17960fb5f6f09ab2ef">getFrameLowering</a>, <a href="#a3b88357c6972aff211e829aee4da3658">getRsaSize</a> and <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#aec1517c8d806609cb368f431ddab1bc7">llvm::VEInstrInfo::expandGetStackTopPseudo</a>.</p>

</div>
</div>

### getFrameLowering() {#ad4a1aa0e342ede17960fb5f6f09ab2ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VEFrameLowering * llvm::VESubtarget::getFrameLowering ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#aec1517c8d806609cb368f431ddab1bc7">llvm::VEInstrInfo::expandGetStackTopPseudo</a> and <a href="#a20a73c3c6631ebcb090858d4cb244ac8">getAdjustedFrameSize</a>.</p>

</div>
</div>

### getInstrInfo() {#a96b42641fc5f60a36212147b75fe3669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VEInstrInfo * llvm::VESubtarget::getInstrInfo ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/veregisterinfo/#a6ab5420775a7cd360178e78c09f5774e">llvm::VERegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad99d6c93063cbfe0bf0f995a0cf12552">llvm::VEInstrInfo::expandExtendStackPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#aec1517c8d806609cb368f431ddab1bc7">llvm::VEInstrInfo::expandGetStackTopPseudo</a> and <a href="/web-llvm/docs/api/structs/anonymous-lvlgen-cpp-/lvlgen/#acb30fcc2737dba0be416d568af161070">anonymous{LVLGen.cpp}::LVLGen::runOnMachineFunction</a>.</p>

</div>
</div>

### getRegisterInfo() {#aecdc3319eb01ec80a69ace4e6111a284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VERegisterInfo * llvm::VESubtarget::getRegisterInfo ()</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/veregisterinfo/#a6ab5420775a7cd360178e78c09f5774e">llvm::VERegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#aa5d558f15e85ff1bdd92f481212ed368">lowerFRAMEADDR</a> and <a href="/web-llvm/docs/api/structs/anonymous-lvlgen-cpp-/lvlgen/#acb30fcc2737dba0be416d568af161070">anonymous{LVLGen.cpp}::LVLGen::runOnMachineFunction</a>.</p>

</div>
</div>

### getRsaSize() {#a3b88357c6972aff211e829aee4da3658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VESubtarget::getRsaSize ()</td>
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

<p>Get the size of RSA, return address, and frame pointer as described in <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veframelowering-cpp">VEFrameLowering.cpp</a>.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>


<p>Referenced by <a href="#a20a73c3c6631ebcb090858d4cb244ac8">getAdjustedFrameSize</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#aa7c9b64ef05827af96d4847b8bf02c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SelectionDAGTargetInfo * llvm::VESubtarget::getSelectionDAGInfo ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>

</div>
</div>

### getTargetLowering() {#ab9ac228c9a9549c1af3a761170034d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VETargetLowering * llvm::VESubtarget::getTargetLowering ()</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>

</div>
</div>

### initializeSubtargetDependencies() {#a93f03b43c499eb1e609399b721681624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VESubtarget &amp; VESubtarget::initializeSubtargetDependencies (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-cpp">VESubtarget.cpp</a>.</p>


<p>References <a href="#a2238b9fd6c4557b037c645e664c1e6a0">ParseSubtargetFeatures</a> and <a href="#ad30b4b6d4e3721ff97e97fb248ec4cf9">VESubtarget</a>.</p>


<p>Referenced by <a href="#ad30b4b6d4e3721ff97e97fb248ec4cf9">VESubtarget</a>.</p>

</div>
</div>

### isTargetLinux() {#a63574f2ac18f5b5cea01f1673c3ab39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VESubtarget::isTargetLinux ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>

</div>
</div>

### ParseSubtargetFeatures() {#a2238b9fd6c4557b037c645e664c1e6a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VESubtarget::ParseSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options.</p>


<p>Definition of function is auto generated by tblgen.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>


<p>Reference <a href="#ad30b4b6d4e3721ff97e97fb248ec4cf9">VESubtarget</a>.</p>


<p>Referenced by <a href="#a93f03b43c499eb1e609399b721681624">initializeSubtargetDependencies</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a765e6f0899384af01da609b476491709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VESubtarget::anchor ()</td>
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



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-cpp">VESubtarget.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EnableVPU {#a1a38ec828a2c77a14268149cc6bb99db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VESubtarget::EnableVPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Features {.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>

</div>
</div>

### FrameLowering {#a386c05f7da6c23293e38ee97fdc8272b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VEFrameLowering llvm::VESubtarget::FrameLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>

</div>
</div>

### InstrInfo {#ab09902afa0aa057127704d1cbb5a5be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VEInstrInfo llvm::VESubtarget::InstrInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>} Features</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>

</div>
</div>

### TargetTriple {#ae4d7a5de07e23b1d1db7754dcf3bb27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::VESubtarget::TargetTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>

</div>
</div>

### TLInfo {#a7754bf9c3dcfade1ae761772c4508304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VETargetLowering llvm::VESubtarget::TLInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>

</div>
</div>

### TSInfo {#a285ea312b748d7fbb0338fdf648d7cc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAGTargetInfo llvm::VESubtarget::TSInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-cpp">VESubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
