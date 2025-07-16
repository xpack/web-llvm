---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcnsubtarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GCNSubtarget` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::GCNSubtarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">Target/AMDGPU/GCNSubtarget.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/amdgpugensubtargetinfo">AMDGPUGenSubtargetInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget">AMDGPUSubtarget</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TrapHandlerAbi { <a href="#a347289a8e670a14bc5c60464df2f445c">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TrapID { <a href="#a80e7aa469ce27c761eef3c645e55ed88">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf1aa5ffc0b59dd205f5dc5142580771">GCNSubtarget</a> (const Triple &amp;TT, StringRef GPU, StringRef FS, const GCNTargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64d48dd1c0bf0bcdefdac099669a1fa">~GCNSubtarget</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a> (const Triple &amp;TT, StringRef GPU, StringRef FS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54ef9f214b4b023adbc4a66e2305666">checkSubtargetFeatures</a> (const Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnose inconsistent subtarget features before attempting to codegen function <span class="doxyComputerOutput">F</span>. <a href="#af54ef9f214b4b023adbc4a66e2305666">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32384420526a080b93cc98ab5a023001">getInstrInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siframelowering">SIFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b043b6a8bc5e976e72ac725a7be3d9">getFrameLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering">SITargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d34f15ff5049d93e832e39c3693b29f">getTargetLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e872608c63bfb1bed8f7d133d96c178">getRegisterInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8dc3dcdfa89ef9d400894ab264ec05a">getSelectionDAGInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe30a0d4fa09e937a7b86e983e7ccceb">getCallLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering">InlineAsmLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347c77a8c5972fe2d03150b5de682de9">getInlineAsmLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ffd74cd6b69bfe9614b624b94f0dc9">getInstructionSelector</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a4865aed3c7bdbdd3aa1cde206364a">getLegalizerInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo">AMDGPURegisterBankInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f6ce22a25ef1ddd72285891220b9205">getRegBankInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid">AMDGPU::IsaInfo::AMDGPUTargetID</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4d618b8e68e3ec2216c10bf66a18d1">getTargetID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38931c46f7a692029325e4dcdb3ca35c">getInstrItineraryData</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1de3db2a7fc8d25fd5bb863ff90f0fd7">ParseSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2">Generation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee63988db75cc1496914d73de1fc6440">getMaxWaveScratchSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a9471cfb6a3ad1bbe1296d31b716494">getKnownHighZeroBitsForFrameIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of high bits known to be zero for a frame index. <a href="#a8a9471cfb6a3ad1bbe1296d31b716494">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cfaf858a04f4c55a92005ab1ee5694c">getLDSBankCount</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c8834f883c6607231b902a1f37ddbc">getMaxPrivateElementSize</a> (bool ForBufferRSrc=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a600e1b2e066f85e6a2bb588a7f3f1">getConstantBusLimit</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a662ced5ddef5f29e53b545dfd51384e9">zeroesHigh16BitsOfDest</a> (unsigned Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns if the result of this instruction with a 16-bit result returned in a 32-bit register implicitly zeroes the high 16-bits, rather than preserve the original value. <a href="#a662ced5ddef5f29e53b545dfd51384e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa99f892ef918babd54c99742f34d6548">supportsWGP</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7af63ea0547908098ee65377e979d3ea">hasIntClamp</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae408833a27e3db45bd5d4b790cd1ba9f">hasFP64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab10ebfbc9a9e224662e1cc4fa218d5d8">hasMIMG_R128</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ba650a151ac898c90b1940ea3e951ff">hasHWFP64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab504c30d42758271e85ec4104b8ffa4">hasHalfRate64Ops</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8263d2c3a266941b3669828ecf1db53e">hasFullRate64Ops</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad773dab02c945afb0bc889ebd67649c0">hasAddr64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e78eae9b647e527c50749797367173">hasFlat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e686c7c8f5b335f3edce1e6711ec168">hasOnlyRevVALUShifts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec23a7dbd85b61497ca147984ce54cbe">hasFractBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe5c2cff6531de48bb6a70e1f3812f8c">hasBFE</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca681e25480ee5684196eb8641148ee">hasBFI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb6d1062f8ac41bba35b40d251d1860">hasBFM</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26eea6294674b212aef650094cdbd54e">hasBCNT</a> (unsigned Size) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ff0023a5060d98bbd31476beb658c50">hasFFBL</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7d61179e3d68402e9f9aca0a60f9053">hasFFBH</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977f7068e1dd00bcd2deab2075c5eac0">hasMed3_16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7af1360602eb146eabea6d2dce67dd17">hasMin3Max3_16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addfe5ff70771ccdda4ae3c6e282a5441">hasFmaMixInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae007c4b2c43d54e68a32fa29d8411ba5">hasCARRY</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3d326302b1b07150d09e0745a3e9bcc">hasFMA</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0640303601c270bb5913e56281c6ff92">hasSwap</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fbcbd9c9b04e70f819b814f6a02a669">hasScalarPackInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4dd4cfc2dbcd57221490dfc8b265592">hasScalarMulHiInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cb30b207966130ab1aa6998aaeadf07">hasScalarSubwordLoads</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a347289a8e670a14bc5c60464df2f445c">TrapHandlerAbi</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62a67f91a73c5a80be0a080a7d6f3c30">getTrapHandlerAbi</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49c35e81b626716f6e81656a7d301a2f">supportsGetDoorbellID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f2e810ecf2f7e2bb9150ed2c5b622a">hasUsableDSOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the offset field of DS instructions works as expected. <a href="#a10f2e810ecf2f7e2bb9150ed2c5b622a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a905685dd1e80d0d65b2d02865b365f">unsafeDSOffsetFoldingEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa696e47a30e77762a75d6eb8fe1e34">hasUsableDivScaleConditionOutput</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Condition output from div_scale is usable. <a href="#a0fa696e47a30e77762a75d6eb8fe1e34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada3be3eae9decd8077b5cd12f6586734">hasReadVCCZBug</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extra wait hazard is needed in some cases before s_cbranch_vccnz/s_cbranch_vccz. <a href="#ada3be3eae9decd8077b5cd12f6586734">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0556cb1a1cb30ebf22d337d400074b81">partialVCCWritesUpdateVCCZ</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes to VCC_LO/VCC_HI update the VCCZ flag. <a href="#a0556cb1a1cb30ebf22d337d400074b81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad35eeddb0b87d3542dcf6690a6fa655d">hasSMRDReadVALUDefHazard</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A read of an SGPR by SMRD instruction requires 4 wait states when the SGPR was written by a VALU instruction. <a href="#ad35eeddb0b87d3542dcf6690a6fa655d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5417712235e489ce3f1473cbf2cbb9a">hasVMEMReadSGPRVALUDefHazard</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A read of an SGPR by a VMEM instruction requires 5 wait states when the SGPR was written by a VALU <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#ad5417712235e489ce3f1473cbf2cbb9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad46aa9ecc42e11cb442f7ed98b57acd3">hasRFEHazards</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d22b584d54c1366ace6fb7fe3f972da">getSetRegWaitStates</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of hazard wait states for s_setreg_b32/s_setreg_imm32_b32. <a href="#a7d22b584d54c1366ace6fb7fe3f972da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74603d93fb144ec34a796f1f07eb39c2">dumpCode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a4d0d821e43aa63626b7f19b27dc189">getMaxLocalMemSizeWithWaveCount</a> (unsigned WaveCount, const Function &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the amount of LDS that can be used that will not restrict the occupancy lower than WaveCount. <a href="#a3a4d0d821e43aa63626b7f19b27dc189">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60e0e7438de97d15bba3e5963c5751d">supportsMinMaxDenormModes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c8b088118866709d3b6f35349b59b12">hasDenormModeInst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac984e6be051494d2f59e7bbe563b84b9">useFlatForGlobal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a569ef38e3e8f453282539783412c5601">useDS128</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac79093e78236587f3f298fd96a06947e">hasDS96AndDS128</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf0e7e914d5468cf242a422fb6a53070">haveRoundOpsF64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Have v_trunc_f64, v_ceil_f64, v_rndne_f64. <a href="#abf0e7e914d5468cf242a422fb6a53070">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c9cd4a438837eb5883a8b62107e8219">privateMemoryResourceIsRangeChecked</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92348ae76d31e89c8201b89c0eeb00cb">usePRTStrictNull</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a361e1bd0ac3e221a2fe75f68ea9d0d41">hasAutoWaitcntBeforeBarrier</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c45ffdf8326d1afb0a80c50837f1a4c">supportsBackOffBarrier</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c81e55bbb2fb239f904617a259befb">hasUnalignedBufferAccess</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d885cd49a333e11b7e405ccfc85c6f">hasUnalignedBufferAccessEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799cf5bdf244aef0f87065145a5f2c42">hasUnalignedDSAccess</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f352f203bb6d6cfd51c652e1c5132ee">hasUnalignedDSAccessEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64bb69b998fcff902312ba7d2eb7221c">hasUnalignedScratchAccess</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a998c1bf83ee1a55a120212a835e24c08">hasUnalignedScratchAccessEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8fdf957658ebd74fb9e95adfdb970a4">hasUnalignedAccessMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18ef501217029506f0ed9027ff266480">hasApertureRegs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83c4915f87ee24cf4648d46b2a2acf0a">isTrapHandlerEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0dd54f1f3e1eb169b00651cd3d61da6">isXNACKEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bec96c96006608cebef39898b836e81">isTgSplitEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62fb29606869fbd40b285c1cda4be12f">isCuModeEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec33da886213da6a50eb967bf8e4548b">isPreciseMemoryEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90fc707270386fb970207745d6675805">hasFlatAddressSpace</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4730d588468e16e01a6a2c475043c511">hasFlatScrRegister</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b42b67d0df8ad1a351bbdc503c115a1">hasFlatInstOffsets</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85d032a1f1dc4a077f3644b16a6a0243">hasFlatGlobalInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28caebd4d797207b1f5989ef56df5683">hasFlatScratchInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad626093afec474495db46935e79c515b">hasFlatScratchSTMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa828632df398b007b1107ea5a5fbfe23">hasFlatScratchSVSMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70afc9ab29667211c70055c992d1c797">hasScalarFlatScratchInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e8da3fb902e2e5c0443907cab82ba01">enableFlatScratch</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a451d3f382bdad515e0cb3e9f39de86aa">hasGlobalAddTidInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc3b60da830f13bd93a91b751d5cfaf3">hasAtomicCSub</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ecc5f8b91d701d17ec10a6b57686dcc">hasExportInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eebf04eb63bf98ee3d5ec4702b65564">hasVINTERPEncoding</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14fa006badbf638f83ae7fad1c6f2c23">hasLdsAtomicAddF64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297574b1f876682e29ea6ab099165998">hasMultiDwordFlatScratchAddressing</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c210fe3c1ded331101415c059606e2e">hasFlatSegmentOffsetBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16018a60d1570d987fea800451277bc6">hasFlatLgkmVMemCountInOrder</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089a31ad15fe70858cf096b66a61b53d">hasD16LoadStore</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596080bfe7eb1bc232a7c9381a5e784c">d16PreservesUnusedBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00fc2b6d813f3656e1715224472da22e">hasD16Images</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d0bd109d96d0faea4a639d43910eaa0">ldsRequiresM0Init</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if most LDS instructions have an m0 use that require m0 to be initialized. <a href="#a9d0bd109d96d0faea4a639d43910eaa0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8a8c0203088e3ec49d090aaaedca78">hasGWSAutoReplay</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6b3273818698235f76b04db7793dd12">hasGWSSemaReleaseAll</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae431b2e8fc0aee94b01cece42984d2dd">hasAddNoCarry</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1d2c1108654a77846036ac453ea20af">hasScalarAddSub64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a898e8b0b4ad260533cde26a99ae409a1">hasScalarSMulU64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad30b3c952ed576256171d49971ec9241">hasUnpackedD16VMem</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c9cce47bece7f780690af00f4924f40">isMesaGfxShader</a> (const Function &amp;F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a553d27729038fcbd05ec618b71feaf3d">hasMad64_32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0330bc04e02e5f966bb34b94faee3ea7">hasSDWAOmod</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af7bcad0087b2e7738d1636e5e4793e">hasSDWAScalar</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef1770dca2e75c8a049d7441802932f">hasSDWASdst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a175f25a33bfc2c593cf6eccc3a2bae67">hasSDWAMac</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67eda8a7f0b4516f8f08d82651207c91">hasSDWAOutModsVOPC</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24618695d970449f186b50c63648f674">hasDLInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ab2534372c0adc46a34c429cedbc05">hasFmacF64Inst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3381161b7a2623d70ebc79101439de62">hasDot1Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088b522817602bb6d879afbb1dd28d82">hasDot2Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a338f477b9e95f79dd790b1962ca6adc9">hasDot3Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0b7da2e35759b56235cc538ab7c0e1b">hasDot4Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab66fd170ebeaddc8ed07d4db2c2a77b4">hasDot5Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80150d52bbde3f5caaaf2d6d2a5b8122">hasDot6Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a182d4bc6088accdac52a4b4eb362abf6">hasDot7Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac39193e57744e29d333b5790b4d4e656">hasDot8Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98e76929ea61bb6075f5146cd2fe0fd">hasDot9Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3faef1a7ec189bbf0d27fbcd91b179c">hasDot10Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dcf980f5642f70d5cc92ad78107aa42">hasDot11Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac76360a6bc40d4eda96a8fa387aec898">hasDot12Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb42a977c1487218f417ea5bd4b8f85">hasDot13Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a278004c824cd46c7504e68ec7c5f2d57">hasMAIInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4e8213a552980916f041896c5989be">hasFP8Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d227c50874535df8d88c8256939a82">hasFP8ConversionInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06c09c7d429aaae637f401b51e855b5a">hasPkFmacF16Inst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a2942b35679bd8c4f413436f58b54f">hasAtomicFMinFMaxF32GlobalInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a968992bddefc74c03eda64e5889e7116">hasAtomicFMinFMaxF64GlobalInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba00ffdcbb35e817245f6903180e271">hasAtomicFMinFMaxF32FlatInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a143ff62a1e0eae583030d0787c1219ed">hasAtomicFMinFMaxF64FlatInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0318f31ec7d1b90f27b5413cd224663c">hasAtomicDsPkAdd16Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bce2aae2056dd71265b887b181e17c1">hasAtomicFlatPkAdd16Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab7b3ab8cbd1cf72b5e93d6983a748a1">hasAtomicFaddInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3779799f24ab110dc3a64ebfb9f472bb">hasAtomicFaddRtnInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7f9c6b88d7dd2493b9c6a68112a68c5">hasAtomicFaddNoRtnInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a8ac068b8f8aa548a3ce1fe90dad8a">hasAtomicBufferGlobalPkAddF16NoRtnInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfcf88257e77cb54415205652e2e88ee">hasAtomicBufferGlobalPkAddF16Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad71a92219d05963817490411ca445902">hasAtomicGlobalPkAddBF16Inst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34bcbfbfadd8de8a1172c659d3d2aa4">hasAtomicBufferPkAddBF16Inst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf85a994788b693f38928fdf8b7a48f">hasFlatAtomicFaddF32Inst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8a8ecf7c823363079b7b9e403908d5a">hasFlatBufferGlobalAtomicFaddF64Inst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0087efb42b61a14ba8975ab581ed5f5a">hasMemoryAtomicFaddF32DenormalSupport</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28542e778ba7389ffaf8b471585916a8">supportsAgentScopeFineGrainedRemoteMemoryAtomics</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e5c0a7c3425568c65564eb43572f6f1">hasDefaultComponentZero</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afca224687236c554e05ec7495f5f5b26">hasDefaultComponentBroadcast</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0569952d064262bc16c3052746013fc">hasNoSdstCMPX</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5458eb4f0d6001441653d15f37e101c2">hasVscnt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec9fcfe37ebfe9de9723d9909525634">hasGetWaveIdInst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eda17e3b44637b79a9aac0e47ab249f">hasSMemTimeInst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae733f0fbb575bf1a991461b1df4077a7">hasShaderCyclesRegister</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d831a339bf2cd8bf0b9e5996a3ed123">hasShaderCyclesHiLoRegisters</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfa61def62c3f39edaec6b28782f1992">hasVOP3Literal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a758cbecbfce67cc0a42af981d6f1755b">hasNoDataDepHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b77b5797ab78e2aeffa5e772286d9bc">vmemWriteNeedsExpWaitcnt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bdd904c6ad30cc78129f391b066c3d5">hasInstPrefetch</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a005c3432e3eef07f10653bf3dffccad6">hasPrefetch</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5c238e9ab9ed01ce6a652a90c57c570">hasSCmpK</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bcaef9c28343b5c427f24079ac6fcdf">getStackAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83e606b71127d3f1abc96140bebee8d6">enableMachineScheduler</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f0c2a9bd6fbb4b4f778c62d04098b3b">useAA</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d97981b4dcef721286fa350303111f">enableSubRegLiveness</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e48d4c68f1e7530e0381bb9e45f0a4">setScalarizeGlobalBehavior</a> (bool b)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87235fdebcb88e0c5646333d222dca22">getScalarizeGlobalBehavior</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3118cf5a69f99bc85608b5bd255dbf3">enableEarlyIfConversion</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec6845ed5bb22b096581b6887d6db618">overrideSchedPolicy</a> (MachineSchedPolicy &amp;Policy, unsigned NumRegionInstrs) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1073d2ae057af7a11684100247250fb1">mirFileLoaded</a> (MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab691b3244b89f5993decf425f570341c">getMaxNumUserSGPRs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9094c845e9359c8c1c873e14e1be18f5">hasSMemRealTime</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ce92019b9024b92d62341296eab008">hasMovrel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fae1c20909b13d71c4923a90967f74b">hasVGPRIndexMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021be99fec633060e46fd3c482c1c3bc">useVGPRIndexMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c71068f31a85453c97cfb17a44746b0">hasScalarCompareEq64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab952ba0f11fe329b25af21199f557611">hasScalarDwordx3Loads</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83477fe97fe7b3e570d433e24f71c371">hasScalarStores</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a634ca68c4b030c1871ab805adec13d11">hasScalarAtomics</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd18ad36f7c9ff894f439f5dd79f05de">hasLDSFPAtomicAddF32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85c22bc10e6e36bbe63c69bfb9638e09">hasLDSFPAtomicAddF64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab832422d655be69a3e9b05955e4a58c9">hasPermLaneX16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a481ac8ced7100d359c1619b2520db577">hasPermLane64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eebe2da3e17c5d7c4b4f4dfecdb4df4">hasDPP</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91bc08ab0ee415853bd31422d5ce4589">hasDPPBroadcasts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11f8b622001c4bba3eab4afb901643b8">hasDPPWavefrontShifts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6327e2570c1c58c44b5fc646ec82f6f">hasDPP8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6b35f7e88b68cba1844915dc16db9ec">hasDPALU_DPP</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedc86d07fcc0b61c6f1e138c76432aa4">hasDPPSrc1SGPR</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f1b4a610bfabed1dac80708d399d552">hasPackedFP32Ops</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3afde3a0eda49172cc0f673da8ab75ea">hasPkMovB32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53cf2f32851d6c5f192a752f853c581b">hasFmaakFmamkF32Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2caffdb8654b132f6f434c0fe9e1112">hasImageInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a254ad120b3ae58ca663832ba14592457">hasExtendedImageInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a426587719be9d9751e8c667734f0cc7a">hasR128A16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0985b28a440a19cc9e6b8229e75b5152">hasA16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaac87839eb0077c44120678bcab56bc9">hasG16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42ffba7488c6f98d42703852d9d83361">hasOffset3fBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e70db1e8483e587c41a315dfad8c88a">hasImageStoreD16Bug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa38a233aad5f337533309b4f04a4effd">hasImageGather4D16Bug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33fbbd04a4a2d81c229f0e613de73905">hasMADIntraFwdBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d1955bc658f8878e3746993d2e0530">hasMSAALoadDstSelBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc4098b4aa7563be99e6d57965966f1">hasPrivEnabledTrap2NopBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90329091d5d23e8a4bac1a2803d252b2">hasNSAEncoding</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f46612d8f5ca0825291c14c220c82ce">hasNonNSAEncoding</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af44e06d801c094cd657e62994746d62a">hasPartialNSAEncoding</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf548cba17900940ca7f8466e3d5ae3b">getNSAMaxSize</a> (bool HasSampler=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf65bf4917efcfd2afded9f48afcfee">hasGFX10_AEncoding</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd5cffaeaa2cffe0f336c6e9aca140b2">hasGFX10_BEncoding</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b70c1201c0b1688d7284174c11a5b77">hasGFX10_3Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f464e58eb8545a1261f5ef4be85ce95">hasMadF16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e0b317959309846ea919ad2cf08ffc">hasMovB64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a815b2f5ace41f35b5ca3534086af69af">hasLshlAddB64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6cff467fd7061aa3d14b86ebb25b426">enableSIScheduler</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1141c1288fa7d35e8ecde9bd1ebc9769">loadStoreOptEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a463d4dd9c6577a21b6edd9879d013113">hasSGPRInitBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e54f855ac47719c335add94e8a6620a">hasUserSGPRInit16Bug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31e93bb82e5ea95995efb52febbe0d8f">hasNegativeScratchOffsetBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa727d0bfbc501329be7c48c86d8bdb8c">hasNegativeUnalignedScratchOffsetBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2daa95e19ef6f3a5d3be7f175d5bde59">hasMFMAInlineLiteralBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7332cd9b9757b3209b60ff112ba7b528">has12DWordStoreHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437295c0cecbdbec197e655e34cab714">hasDwordx3LoadStores</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d725ba548e7482013418fef4d2917b2">hasReadM0MovRelInterpHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1d0d1c87789d65fa35257547aaa7435">hasReadM0SendMsgHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f43aaffee9d7ce03f6944a84f935c3">hasReadM0LdsDmaHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ee05cd6b4e404e5dc44eed03a2dd09">hasReadM0LdsDirectHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5de1edfcd129b2eb4325a889489ef633">hasVcmpxPermlaneHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa45af2117c2e8ab325c59f997e818f90">hasVMEMtoScalarWriteHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e531910f7c7133e8696a4dea9ff873a">hasSMEMtoVectorWriteHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b73e7766fb13e9033b8cc011e5d3ea">hasLDSMisalignedBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95c817fefbb5c1444ecadc1a790b1273">hasInstFwdPrefetchBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b700ecd2d736b769de16280afbca49a">hasVcmpxExecWARHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3aaf52cbaf44191f00656b774cdede">hasLdsBranchVmemWARHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1828e0b98df9d5cd61698e7585d8e7a7">hasShift64HighRegBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fdc7771608a86b53935f4f6fc101c39">hasTransForwardingHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2017ee435d93b4ec8c38e024d5cb9b30">hasDstSelForwardingHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fa10ba2f5551b22c35eecfa74b3296a">hasDOTOpSelHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab96225992445aceb04e50ab1e06f068e">hasVDecCoExecHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadb9bb3c036cfcddf3fc2634071fa163">hasNSAtoVMEMBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3633028daa01022eaf44181a9f5028a4">hasNSAClauseBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567e40fa5e04cc7a032e60e66044f470">hasHardClauses</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fc0ea9be83e3d4cb2aeb2d7b2363e73">hasGFX90AInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b16e18ec95818598ce11d30f59fec2a">hasFPAtomicToDenormModeHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2fdc3a5b7196e1e439d054ccf973e3a">hasVOP3DPP</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff5ba6e6e7a7b0ce7126d565ddd5c5cf">hasLdsDirect</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5255251aa57df7852a7be73345a627ac">hasLdsWaitVMSRC</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73adb50a215b03b117f99dee7bd1f744">hasVALUPartialForwardingHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c6edd32a125d77f3c55139393019b4">hasVALUTransUseHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1c82209fdf5c7efc8a19f003b60a9b">hasCvtScaleForwardingHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf635e2bc94a0c4f29a493833eb548c4">hasForceStoreSC0SC1</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd17b1239dc4bc597ba3b9fa0c54c6f0">requiresCodeObjectV6</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3430658dbad45a4b93412d69c57f76a7">hasVALUMaskWriteHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a908e982d292aa3598537c78f6cd21c72">hasVALUReadSGPRHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b3c319ca867b6775449a12b4623634a">needsAlignedVGPRs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if operations acting on VGPR tuples require even alignment. <a href="#a3b3c319ca867b6775449a12b4623634a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4097c8e7593fbd1a0b8cff5964fa5d7">hasSPackHL</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has the S_PACK_HL_B32_B16 instruction. <a href="#aa4097c8e7593fbd1a0b8cff5964fa5d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f222ef89ce8fb3fe994bd2c7103f843">hasCompressedExport</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target's EXP instruction has the COMPR flag, which affects the meaning of the EN (enable) bits. <a href="#a1f222ef89ce8fb3fe994bd2c7103f843">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6c28d83ad975e7eb5384641191d9bc">hasNullExportTarget</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target's EXP instruction supports the NULL export target. <a href="#a9a6c28d83ad975e7eb5384641191d9bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cc2fccd89413e7c79e54d4b657872c7">has1_5xVGPRs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc70c2a79f18b7d4cb774ae93df8c548">hasVOPDInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab85fb688a662d3962521663406317d17">hasFlatScratchSVSSwizzleBug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf65492620612e129dd3e847a2c4e57f">hasDelayAlu</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has the S_DELAY_ALU instruction. <a href="#abf65492620612e129dd3e847a2c4e57f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae133c0c692754b7a2e431eae75db8733">hasPackedTID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ef035f066bb00307e5cccb694e20e2">hasGFX940Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba0e36ee4fa0e5829ab468e0ad18627">hasGFX950Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27fceb81b4828d4bafbd5a97c71ef510">hasLDSLoadB96_B128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target supports global_load_lds_dwordx3/global_load_lds_dwordx4 or buffer_load_dwordx3/buffer_load_dwordx4 with the lds bit. <a href="#a27fceb81b4828d4bafbd5a97c71ef510">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea382e48834aaf8b5f0e334622faa197">hasSALUFloatInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac695674c0b51da8114892ef06e224ef3">hasPseudoScalarTrans</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a64fa91bbb4ff5f0417e16ad408e0c9">hasRestrictedSOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f7250d7950b6fb7e11b676b0d6a84ba">hasRequiredExportPriority</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263599c932efbe43f310b3924533ddad">hasVmemWriteVgprInOrder</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56c84f9bafede08443d6b28b3f9797f1">hasExtendedWaitCounts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8f2856d03fa63b54d82cb19936082c5">hasNoF16PseudoScalarTransInlineConstants</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bafa8f44616aca18624d36db7061d36">hasXF32Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae9d4320920b5bd1a193c69c22c1dbc">hasBitOp3Insts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacf87c06d72fdf7a23f5231ce3834fcb">hasPermlane16Swap</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f2b3a5ff8e0b8454a6d0c46cb63c98">hasPermlane32Swap</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c9b0d88a0394d2496b7aa56842f6def">hasAshrPkInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a017de56f30979f32ad941844f3e6d66f">hasMinimum3Maximum3F32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a663d34243037a886d4932750a3cd40d2">hasMinimum3Maximum3F16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57fd5bacadbf867edd08ea6551ef5df9">hasMinimum3Maximum3PKF16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c2b42a3405b2b4cb009beb1802caa32">maxHardClauseLength</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a438e29c27b814b7bcf58616cc57862b7">hasPrngInst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20982dc4ff887572a43754228a94fc0">getOccupancyWithNumSGPRs</a> (unsigned SGPRs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum number of waves per SIMD for kernels using <span class="doxyComputerOutput">SGPRs</span> SGPRs. <a href="#ab20982dc4ff887572a43754228a94fc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa19ea7d1223b3dbc9f1c432059f8e040">getOccupancyWithNumVGPRs</a> (unsigned VGPRs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum number of waves per SIMD for kernels using <span class="doxyComputerOutput">VGPRs</span> VGPRs. <a href="#aa19ea7d1223b3dbc9f1c432059f8e040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78f78fef97b3e953f2f4992c369026d8">computeOccupancy</a> (const Function &amp;F, unsigned LDSSize=0, unsigned NumSGPRs=0, unsigned NumVGPRs=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtarget's minimum/maximum occupancy, in number of waves per EU, that can be achieved when the only function running on a <a href="/web-llvm/docs/api/namespaces/cu">CU</a> is <span class="doxyComputerOutput">F</span>, each workgroup uses <span class="doxyComputerOutput">LDSSize</span> bytes of LDS, and each wave uses <span class="doxyComputerOutput">NumSGPRs</span> SGPRs and <span class="doxyComputerOutput">NumVGPRs</span> VGPRs. <a href="#a78f78fef97b3e953f2f4992c369026d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16a3a7cc1dff82b8227571c334bc68b7">flatScratchIsPointer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3fc4aac61bac7b5675218848b4b8e90">flatScratchIsArchitected</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297a2e0f9d548e720e1303be506ee7a4">hasArchitectedSGPRs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedfc0056986632c8d0462319b661d692">hasGDS</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a4a974fce95bb3f78e370f63d25a56">hasGWS</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0936b3343117af1096d10094f4cc47f5">hasMergedShaders</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60ef33c23289f161804eab76b43b6683">hasLegacyGeometry</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c1fca26ad6a387a03e4649095b7cdc7">hasKernargPreload</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29bdf407acea38fceff17cfc4159e3e">hasSplitBarriers</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f5adb4d0fdc24fcb3947f50a4c6645">hasCvtFP8VOP1Bug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a702e9540e27a17a550b4937032b939e0">hasAtomicCSubNoRtnInsts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86592a7b06bb03f50836dc6b7988aff6">hasDX10ClampMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab906a8b680c13e481cf016a0c111173a">hasIEEEMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9f234619d0fb3d8254f46b9f3dd001">hasIEEEMinMax</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad21fbf9dd106c4b149954abd1ddb0c85">hasIEEEMinMax3</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf7687022b74bf81427ae61cc828c7c">hasRrWGMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4426383e6ed12fbb51b44261e675b122">hasSignedScratchOffsets</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4800f21d7866329eeb7a6bbcef9cb9e7">hasGetPCZeroExtension</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a120ab447b09dc6bafd750961802ca264">getSGPRAllocGranule</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc464816b0b6f1497cbb07c51cb0a36">getSGPREncodingGranule</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a377dcbfe45feb26ed8654cfce84087af">getTotalNumSGPRs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9bf37eb3ab2ed467ed4489666c41d27">getAddressableNumSGPRs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c9934ccbee04b51f83a123e09ae9cf1">getMinNumSGPRs</a> (unsigned WavesPerEU) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf6141c742569e20d289c523560f8b00">getMaxNumSGPRs</a> (unsigned WavesPerEU, bool Addressable) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad65c004eab25ab815e6bc696b8fb8578">getBaseReservedNumSGPRs</a> (const bool HasFlatScratch) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a988c4c0176e7554762642cd4f0fa1b8a">getReservedNumSGPRs</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b81f06d449a6dc8b3d664b5edded261">getReservedNumSGPRs</a> (const Function &amp;F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b42f0492d630514943c345ab5eb4bc0">getBaseMaxNumSGPRs</a> (const Function &amp;F, std::pair&lt; unsigned, unsigned &gt; WavesPerEU, unsigned PreloadedSGPRs, unsigned ReservedNumSGPRs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6b158ec91f975b577a100bbc5fd8554">getMaxNumSGPRs</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a415e45063e973508aebd65b3e5824754">getMaxNumSGPRs</a> (const Function &amp;F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d631f933bed8f5b71e58638f024b87c">getVGPRAllocGranule</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5636afb498eec4770235c34d76f8e36f">getVGPREncodingGranule</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e649388bef9c44bc294dab940cd6b84">getTotalNumVGPRs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b1c07b42d5ebde1c910cfa0025d321d">getAddressableNumArchVGPRs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0db0ce6c2a59c442c60951a063e49b6">getAddressableNumVGPRs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d8866021383c037a029d77a3497f23">getMinNumVGPRs</a> (unsigned WavesPerEU) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f492fa16404497b8f15ea82c4b0a725">getMaxNumVGPRs</a> (unsigned WavesPerEU) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a293668f13d1c676db1d1b3be25b7115d">getBaseMaxNumVGPRs</a> (const Function &amp;F, std::pair&lt; unsigned, unsigned &gt; WavesPerEU) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a0790cfbae21408e8715d0ed098ed1">getMaxNumVGPRs</a> (const Function &amp;F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ccb66bcde5267a76db443eee0a601ac">getMaxNumAGPRs</a> (const Function &amp;F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adacbd1f740db810d1611b071359a2c3e">getMaxNumVGPRs</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f44cd05eefbb20a234a7e3b6369a7f8">isWave32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb983b483404f765e1716c96f4a42580">isWave64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1289175399e94194be94b32fb34c303">isWaveSizeKnown</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns if the wavesize of this subtarget is known reliable. <a href="#aa1289175399e94194be94b32fb34c303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a531864eddd4fb4fb020cf583a10507c1">getBoolRC</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e4f8d7e4a12870752efe1ff494c96d">getMaxWorkGroupsPerCU</a> (unsigned FlatWorkGroupSize) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa214881f596f9adddeef9df6600df144">getMinFlatWorkGroupSize</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5784d58015d7b40f2750f80f4ef6aeb">getMaxFlatWorkGroupSize</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd3d507136dc902e56d585a7dd9d729e">getWavesPerEUForWorkGroup</a> (unsigned FlatWorkGroupSize) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea42736115781162e371685322542f4">getMinWavesPerEU</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38ff3df1feb7915dfda6303a34484534">adjustSchedDependency</a> (SUnit *Def, int DefOpIdx, SUnit *Use, int UseOpIdx, SDep &amp;Dep, const TargetSchedModel *SchedModel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bf8a3ec8755ac759a9f8c54ea5cf3f0">shouldClusterStores</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86673715704dada21e3529d93a5376e8">getNSAThreshold</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49268fedde6b2d35a3b106ea50e5dc62">requiresNopBeforeDeallocVGPRs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9078d25e7337b0e6490e8662f3a281a5">requiresDisjointEarlyClobberAndUndef</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab96f321c806effcca947691e54b24784">getMaxWavesPerEU</a> () const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1761721d270309e56a4643963971c0">TargetTriple</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid">AMDGPU::IsaInfo::AMDGPUTargetID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6af409114a5e2da7bc8bedf9024cdc">TargetID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72d895427056e0f3e9147974a95d11f8">Gen</a> = <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a44ffb5f3120d0b92ed40f4ee48ada81e">INVALID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01b60a82cd5066b5e1d29757a80965ee">InstrItins</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d64bc81257fe4f2c899dc26a9c1660">LDSBankCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18efbf5a73b167d005a9d1004816ab00">MaxPrivateElementSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba3f51a2b0a671556f0ad51f2e8baf47">FastDenormalF32</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a948eae74cbc251ff4e8984a04ecbcdc6">HalfRate64Ops</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a621ba6bafe12da8a8af4288ef2c1040e">FullRate64Ops</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5bfbea25d0de2655684928e7d7aa2f1">FlatForGlobal</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3336ba2851ac5650dc025a8642214e35">AutoWaitcntBeforeBarrier</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80be78dfd225963436a255b4b9aadc3e">BackOffBarrier</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b54a7dcd00a95feec9a76aebca85508">UnalignedScratchAccess</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abce08ae709e3e15c39e3d8c6dd911af0">UnalignedAccessMode</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6001a0f135daa1bb722da2e6197aaa">HasApertureRegs</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f862392eb42d48e0ca0222d3d17ccb4">SupportsXNACK</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ea5e2eef6d396268f0b354c3c5ead45">KernargPreload</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c7aafc6dd938a9b5d40f1edf2d3eaf1">EnableXNACK</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e036c3eafba2aa898f7895579c8f39">EnableTgSplit</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a9a419e5ce5ddf54374dc797f765f6">EnableCuMode</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addf1e5060c2765ecd0a10ff16a1d44e4">TrapHandler</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a408fffe61eaab170cb661602f3471bc4">EnablePreciseMemory</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3970dc19cb63913985fac762d7320bf7">EnableLoadStoreOpt</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1997ce0ad03e335de0a4a5388185be">EnableUnsafeDSOffsetFolding</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a830227621ce04eaf78322896a0c79f29">EnableSIScheduler</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdff2a277a6b2747e2a283c9e7637119">EnableDS128</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a333dc075b3c226ce688cb79acc102c">EnablePRTStrictNull</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b2245d34fac299ea10ae1fd2cabff5d">DumpCode</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad989699f72d64cd5c12d52856532880a">FP64</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3ad8d1429472400a745a288263f1fa6">FMA</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ca7cf17cde165669ca2d983800d3701">MIMG_R128</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef4f045c922c0ae9c8a500e0e2c29d4">CIInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a953743f90862340f08cb9cd50174824b">GFX8Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a443df8396a86d96634419086278c7452">GFX9Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaae1852e68f40bf33e7f6f49c1fd1cff">GFX90AInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a167f1c9d969e90ea41a3dd52a37b32e6">GFX940Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac164adfdd62c69dbd820c417d2c24de0">GFX950Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00cf3c0a968bd5bff04c762c55336e53">GFX10Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23594b888d739de018ed2a227d711ced">GFX11Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee8f87ccf5572392018ca06a2080989f">GFX12Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a56363d4e58147e7df5adb4872c3ba">GFX10_3Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace75fcd5d3c4b1726d013754c80ae304">GFX7GFX8GFX9Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88ed5e21bdfe4710afa3fdd33981617">SGPRInitBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21359df698891d2466c68d8abf6b4e4c">UserSGPRInit16Bug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e15f45c8391c4606bf56f4cfc3be19d">NegativeScratchOffsetBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56675b4857e4f3f36f3aacbfc1e8f188">NegativeUnalignedScratchOffsetBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d2cfb5028990ce762ad06fbebd0b4f">HasSMemRealTime</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7bb96baf904d1d3c70e476a6cb4e488">HasIntClamp</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8050bb1b1445e617520f2a5bfad62e3b">HasFmaMixInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76168e6f26b0f7cada393b6baaf6d7aa">HasMovrel</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee2435b1a7b8c192632aeabdd325e7d">HasVGPRIndexMode</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18974200e120861ba26d24805f87bce7">HasScalarDwordx3Loads</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2438b345b76fa20009799525ecf82a16">HasScalarStores</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820f935a25ced4c881e7ca3b60d775f4">HasScalarAtomics</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a371756f715ae24e7c7d6ee87bfb6d9bb">HasSDWAOmod</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf3065241a25e6b9f9f1d2477e24ec7">HasSDWAScalar</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac714f4a5d78945bf0268b7e166781db9">HasSDWASdst</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffe84152bfba8302521f0f8c77671e8">HasSDWAMac</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7076d6c3ca7fb96840d61e52a0f0400b">HasSDWAOutModsVOPC</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a389b331031e56958a8f3da55723465fd">HasDPP</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23518644c73072ed1e0e8d627be8ba01">HasDPP8</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2447a5253106678c1dfe0bab536c7c9d">HasDPALU_DPP</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87170f8953730e15a8dfe935c37232dc">HasDPPSrc1SGPR</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5049a486074311dc22e29c08a0c60c">HasPackedFP32Ops</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d26cde5f690bf9459fc2f76865d030">HasImageInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08e442e1f7eb5131692ccd5bba77774c">HasExtendedImageInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b7cd3536956300a3e6246c7f876ae7">HasR128A16</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2670ded2f52b0a8abebe0bad06cf2fd">HasA16</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d0570029543761ca74c7df68fc59744">HasG16</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2847a61e28335ec96f3aba0aa582e23">HasNSAEncoding</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58c2025484c09d2f354f1f6b4b4a461e">HasPartialNSAEncoding</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c380b42afd78ccb7c178bc27ad0fb27">GFX10_AEncoding</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a9bffea45bd561499b442b0544ccb8">GFX10_BEncoding</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e04190f533d5235647a1e89f9d83014">HasDLInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a0aae30a368c4c91584185cc3ad6373">HasFmacF64Inst</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9f698137ecac3f8bfd57c1d2bd225bb">HasDot1Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9682ddcf41ed820be15cc7218775fe87">HasDot2Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3520574a8e86bbe157a34c179c9747da">HasDot3Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8694a6472636f253ac7a422066ee9e8d">HasDot4Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6ded25230b26b659566be69c769d464">HasDot5Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02ff9dd7be4e70091e99c1997741eda8">HasDot6Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3d3703aae398dc4469527df9c758e3">HasDot7Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a489d835ec8202127cea0eb9ce07dce">HasDot8Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c2b493bd4f475fb096ae324d582826">HasDot9Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb9f1d4990af79ac841d54ff4a51f6e">HasDot10Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04c4ff7828efe3cd1ba4a631f899299d">HasDot11Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0ba569ec8d5c4c8a1017745af2231fa">HasDot12Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bca337aa04112b4496e6a2569c92694">HasDot13Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1176e8f488b0bc45c6478cc494e8ba">HasMAIInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9207fa4cbccf18aa0b9be67d2a54d744">HasFP8Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a952f6917a737a034709d9c849dfb0d9d">HasFP8ConversionInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae790c1da8d9eba51c60d614ef837f80c">HasCvtFP8Vop1Bug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d7cdc43a6afa870465964d752b5072b">HasPkFmacF16Inst</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86f942a251a036fb225fb8f8f0deb555">HasAtomicFMinFMaxF32GlobalInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8a0f2f00bafd753b886d0c61cef8dd3">HasAtomicFMinFMaxF64GlobalInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8817af4d2308f9cdb31a8b57fc797007">HasAtomicFMinFMaxF32FlatInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07f6f1c9612fe2ec6fed7f949a8ebe26">HasAtomicFMinFMaxF64FlatInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3642c58f343c3c3a82877e1afb7db5e">HasAtomicDsPkAdd16Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85c2d01235c0d1375f99e77b6b604771">HasAtomicFlatPkAdd16Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adae5a837f4ede6853fdaec64c4892d51">HasAtomicFaddRtnInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e196e9035b546b74522a169d0a1c45f">HasAtomicFaddNoRtnInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeecfaf3b2b9359e37af4fe07166cb226">HasMemoryAtomicFaddF32DenormalSupport</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac211a8f705f61a60b6ced36b9731e3e">HasAtomicBufferGlobalPkAddF16NoRtnInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ad796f74734bb5b657a1f2d1a7ed44">HasAtomicBufferGlobalPkAddF16Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa295bd451d30d00f2fde59fa44045434">HasAtomicCSubNoRtnInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8bbc65850f15c486cc2cf5935c0c709">HasAtomicGlobalPkAddBF16Inst</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6afb3f2adf199a6465ae5f8015cfd79">HasAtomicBufferPkAddBF16Inst</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27da80ce11ad15a11fc4c41a33666a16">HasFlatAtomicFaddF32Inst</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff59c5a54f5886e497f9797030c67b7">HasFlatBufferGlobalAtomicFaddF64Inst</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee91c4560c47c3b5bb78a641a5559ba4">HasDefaultComponentZero</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab511aadc209e491aa6e33ad29de273df">HasAgentScopeFineGrainedRemoteMemoryAtomics</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8faff728ce71f6506ee26c230f8e9910">HasDefaultComponentBroadcast</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c8c4bbe976a53a477668131c2a965c2">HasXF32Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8297b266634f159ee9c659cb5467b38">MaxHardClauseLength</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum number of instructions that may be placed within an S_CLAUSE, which is one greater than the maximum argument to S_CLAUSE. <a href="#ab8297b266634f159ee9c659cb5467b38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd24222e78eeb62e9c800bfd2ccf6af0">SupportsSRAMECC</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36608dd76bfe6e185be691777b445ecf">EnableSRAMECC</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fb3a41719c2219a977c3aa110a29cc8">HasNoSdstCMPX</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a336cc2253badbe67950bd9fbb65fee57">HasVscnt</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4258d4c50ebe4adf47d1556d82fef254">HasGetWaveIdInst</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f4e1e3ad1d7eee4e740ad2e3c17658">HasSMemTimeInst</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c5c784b6b9621f4cdab3cd273c9124e">HasShaderCyclesRegister</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3929ea1c1954af1d4f5d2278638ba642">HasShaderCyclesHiLoRegisters</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a0feafb29b5f1d0c3e1a237f464ed3a">HasVOP3Literal</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6db4fbc67c6b520e52f966ff3bd992e8">HasNoDataDepHazard</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98d3431546e921d906556ab6b9d6cb5">FlatAddressSpace</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8caa14af5acb006632cfd31a4c28e78c">FlatInstOffsets</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4346f1426fe53905715ca0f0d2fd0e">FlatGlobalInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad737ff5de5197f759fd10988312481b8">FlatScratchInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4849ecfc6c6ef25d717ef19e6e40c2f">ScalarFlatScratchInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee498bf7e34783628f61d9aa83fead3">HasArchitectedFlatScratch</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac98f2bbf494891ca79075f7a9b052f80">EnableFlatScratch</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd8731d7f792b6ae461a3e677e853b9">HasArchitectedSGPRs</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa07db84b412bc41a23e2c1fff3f7efd1">HasGDS</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f7e4c82242d7fba786da95ea84f39dc">HasGWS</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238786700161fe23c5060ff610ee2968">AddNoCarryInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea0f6b19cef0ddc119a88ae60f5461d2">HasUnpackedD16VMem</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1980c0b9e254aaf640a1b11b37a077c9">LDSMisalignedBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae792f1ad039fd0a51607d85a03feca22">HasMFMAInlineLiteralBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae99450395d28349fc55c832de8510eda">UnalignedBufferAccess</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23393a7e958c2933deafa6bc181a0b0e">UnalignedDSAccess</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b5852cc8a419d0d0e5eed8ac1b6d1e">HasPackedTID</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f5630510fbbd84621962f555f9d697e">ScalarizeGlobal</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1548ff560030d89242f6bba6fc3f43e5">HasSALUFloatInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a887b1d13e204a49b28ba68b995176cab">HasPseudoScalarTrans</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf185c7be65b7b2a4df9fc24ac50e04">HasRestrictedSOffset</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8bdaf283ec09f2b9c47ced006837467">HasBitOp3Insts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bff28a332d5b309966a353003a80e2a">HasPrngInst</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53830d2988831622a620d9df123c93ea">HasPermlane16Swap</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af58a534c85df77c9d8b03d0ce88d622d">HasPermlane32Swap</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6b53b3aebc2a64f37b6317279fe2a4">HasVcmpxPermlaneHazard</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79687b8f51d5052254be71401ac0e64">HasVMEMtoScalarWriteHazard</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d59aff4310d57b0806f1abbcd12021d">HasSMEMtoVectorWriteHazard</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46635e054a2a083f592723ddb861aab">HasInstFwdPrefetchBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20ac61b7ca1deaf9f80e426552884a4">HasVcmpxExecWARHazard</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03acf80e335385e4af1e41537e843343">HasLdsBranchVmemWARHazard</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfaf0dbd880bc35fd34db18c5166370c">HasNSAtoVMEMBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ae3a84968e835cfb541a62de2007476">HasNSAClauseBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8660a471fd90d7d6e3abbb00a325bf5a">HasOffset3fBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29628d7d35aef1950da107293e9f68f2">HasFlatSegmentOffsetBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3af3f5d368b630f23f4dffdd0b46fd">HasImageStoreD16Bug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c980d76fd4aa2aedacdddcd3e275fc9">HasImageGather4D16Bug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf90f97cd99f018d4886dad8d49560c">HasMSAALoadDstSelBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a451a241ad87234390e77346e090cf035">HasPrivEnabledTrap2NopBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056c928381864fc1f037babbad25f392">Has1_5xVGPRs</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a272b4543c35465b19829ba03c72a4730">HasMADIntraFwdBug</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e2fb1b650236a6b1e2c80801da4285e">HasVOPDInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9ec63e4421f2fc8415717a86032e2c">HasVALUTransUseHazard</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b30160b1757f25c85752a1fe26e157e">HasForceStoreSC0SC1</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3c8ecafa08eb2849d23f7fe63a901e1">HasRequiredExportPriority</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d0d64b0d9f819c3246745e07e169c2">HasVmemWriteVgprInOrder</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da82d4d3ac2f557507d846bd9936a67">HasAshrPkInsts</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a551988d5dffbfba8cd48d910b7cc9b14">HasMinimum3Maximum3F32</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a676e72a69c1f0f7a4dc54a9b99e05d00">HasMinimum3Maximum3F16</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac44b0653c95e1c63358778a56937d2d">HasMinimum3Maximum3PKF16</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9aba4af084a7e0c89b55c62f8367d9">RequiresCOV6</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2eedff75f27bd6d78537155abac0f79">FeatureDisable</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1a0559113c7cfec0bc93c7a6cb73f23">TSInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> related APIs. <a href="#af1a0559113c7cfec0bc93c7a6cb73f23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering">AMDGPUCallLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a126b2f0a4a2e4bc3be7130db37c62ac0">CallLoweringInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GlobalISel related APIs. <a href="#a126b2f0a4a2e4bc3be7130db37c62ac0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering">InlineAsmLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15401ed0f02863f15eab262efeb2c7bd">InlineAsmLoweringInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5d4e2741c989c4d060720daada3939">InstSelector</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a343fe5061c158c9bb4f5b1acd99c99e5">Legalizer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo">AMDGPURegisterBankInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b78383688c7c6c8418c0ae4b7502ff">RegBankInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae85b6a0d300c4e5b17e94e435aa5ba1b">InstrInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sitargetlowering">SITargetLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674436c891b2c5dfb22af7e8248db8a7">TLInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/siframelowering">SIFrameLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2df337990e050abf3f1d519ace488b0">FrameLowering</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e9894ed5c61d2bba376dc93961bd71">hasHalfRate64Ops</a> (const TargetSubtargetInfo &amp;STI)</td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### TrapHandlerAbi {#a347289a8e670a14bc5c60464df2f445c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::GCNSubtarget::TrapHandlerAbi </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">NONE<a id="a347289a8e670a14bc5c60464df2f445cab50339a10e1de285ac99d4c3990b8693"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDHSA<a id="a347289a8e670a14bc5c60464df2f445caf778ffa73665e8e41448bf12f1350f02"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### TrapID {#a80e7aa469ce27c761eef3c645e55ed88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::GCNSubtarget::TrapID </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">LLVMAMDHSATrap<a id="a80e7aa469ce27c761eef3c645e55ed88a47de73eb7c73a07ac2cfc17fc3533f33"></a></td>
<td class="doxyEnumItemDescription"> (= 0x02)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMAMDHSADebugTrap<a id="a80e7aa469ce27c761eef3c645e55ed88a094657b2a471074638cef694d53f50d8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x03)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GCNSubtarget() {#acf1aa5ffc0b59dd205f5dc5142580771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNSubtarget::GCNSubtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine">GCNTargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#aad4744328912a86e07d71374296cb44e">llvm::AMDGPUSubtarget::AMDGPUSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a5443dc7c0f90739fe217013b0a6b6206">llvm::AMDGPUSubtarget::EUsPerCU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a705a7512f5b23ec9b3bb19f032040285">llvm::AMDGPU::IsaInfo::getEUsPerCU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a41a62eaa48728ca1d52dda5d0a9b08c1">llvm::AMDGPU::IsaInfo::getMaxWavesPerEU</a>, <a href="#a3bcaef9c28343b5c427f24079ac6fcdf">getStackAlignment</a>, <a href="#a7d34f15ff5049d93e832e39c3693b29f">getTargetLowering</a>, <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a>, <a href="#a01b60a82cd5066b5e1d29757a80965ee">InstrItins</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a94e255f5cda4e44bebeabdbf414e6248">llvm::AMDGPUSubtarget::MaxWavesPerEU</a>, <a href="#afc6af409114a5e2da7bc8bedf9024cdc">TargetID</a> and <a href="#aeb1761721d270309e56a4643963971c0">TargetTriple</a>.</p>


<p>Referenced by <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a> and <a href="#af64d48dd1c0bf0bcdefdac099669a1fa">~GCNSubtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GCNSubtarget() {#af64d48dd1c0bf0bcdefdac099669a1fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNSubtarget::~GCNSubtarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#acf1aa5ffc0b59dd205f5dc5142580771">GCNSubtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### adjustSchedDependency() {#a38ff3df1feb7915dfda6303a34484534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSubtarget::adjustSchedDependency (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Def, int DefOpIdx, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Use, int UseOpIdx, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; Dep, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * SchedModel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a38931c46f7a692029325e4dcdb3ca35c">getInstrItineraryData</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a055c65558a3e0f7d48f1ed3dde061199">llvm::SDep::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a5eca2019521fd47b79fe5ef66d02fd43">llvm::SDep::getLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a8b51361656ac436c2c02a20e6196cff1">llvm::SDep::getReg</a>, <a href="#a4e872608c63bfb1bed8f7d133d96c178">getRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acae72f6ab1071b7ec87b741a8bef582b">llvm::MachineBasicBlock::instr_end</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3e2f795dfcb9269e1263453796f4b994">llvm::MachineInstr::isBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a148b76c8f993d4a3d95ac19c60e2ebe0">llvm::SDep::setLatency</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### checkSubtargetFeatures() {#af54ef9f214b4b023adbc4a66e2305666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSubtarget::checkSubtargetFeatures (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Diagnose inconsistent subtarget features before attempting to codegen function <span class="doxyComputerOutput">F</span>.</p>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a60a7288af24c5de74d432973163470ac">llvm::AMDGPUDAGToDAGISel::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#aaa901c06b2f29c59d5afab0e47e83962">llvm::AMDGPUInstructionSelector::setupMF</a>.</p>

</div>
</div>

### computeOccupancy() {#a78f78fef97b3e953f2f4992c369026d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; GCNSubtarget::computeOccupancy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned LDSSize=0, unsigned NumSGPRs=0, unsigned NumVGPRs=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subtarget's minimum/maximum occupancy, in number of waves per EU, that can be achieved when the only function running on a <a href="/web-llvm/docs/api/namespaces/cu">CU</a> is <span class="doxyComputerOutput">F</span>, each workgroup uses <span class="doxyComputerOutput">LDSSize</span> bytes of LDS, and each wave uses <span class="doxyComputerOutput">NumSGPRs</span> SGPRs and <span class="doxyComputerOutput">NumVGPRs</span> VGPRs.</p>


<p>The flat workgroup sizes associated to the function are a range, so this returns a range as well.</p>


<p>Note that occupancy can be affected by the scratch allocation as well, but we do not have enough information to compute it.</p>


<p>Declaration at line 1379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ab20982dc4ff887572a43754228a94fc0">getOccupancyWithNumSGPRs</a>, <a href="#aa19ea7d1223b3dbc9f1c432059f8e040">getOccupancyWithNumVGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a0d3af39660fba65e1eb9f861b6e94822">llvm::AMDGPUSubtarget::getOccupancyWithWorkGroupSizes</a>.</p>

</div>
</div>

### d16PreservesUnusedBits() {#a596080bfe7eb1bc232a7c9381a5e784c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::d16PreservesUnusedBits ()</td>
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



<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#a089a31ad15fe70858cf096b66a61b53d">hasD16LoadStore</a> and <a href="#afc6af409114a5e2da7bc8bedf9024cdc">TargetID</a>.</p>

</div>
</div>

### dumpCode() {#a74603d93fb144ec34a796f1f07eb39c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::dumpCode ()</td>
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



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a1b2245d34fac299ea10ae1fd2cabff5d">DumpCode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### enableEarlyIfConversion() {#ad3118cf5a69f99bc85608b5bd255dbf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::enableEarlyIfConversion ()</td>
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



<p>Definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### enableFlatScratch() {#a3e8da3fb902e2e5c0443907cab82ba01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::enableFlatScratch ()</td>
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



<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ac98f2bbf494891ca79075f7a9b052f80">EnableFlatScratch</a>, <a href="#af3fc4aac61bac7b5675218848b4b8e90">flatScratchIsArchitected</a> and <a href="#a28caebd4d797207b1f5989ef56df5683">hasFlatScratchInsts</a>.</p>


<p>Referenced by <a href="#aa1c8834f883c6607231b902a1f37ddbc">getMaxPrivateElementSize</a>.</p>

</div>
</div>

### enableMachineScheduler() {#a83e606b71127d3f1abc96140bebee8d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::enableMachineScheduler ()</td>
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



<p>Definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### enableSIScheduler() {#ad6cff467fd7061aa3d14b86ebb25b426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::enableSIScheduler ()</td>
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



<p>Definition at line 1137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a830227621ce04eaf78322896a0c79f29">EnableSIScheduler</a>.</p>


<p>Referenced by <a href="#aec6845ed5bb22b096581b6887d6db618">overrideSchedPolicy</a>.</p>

</div>
</div>

### enableSubRegLiveness() {#a11d97981b4dcef721286fa350303111f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::enableSubRegLiveness ()</td>
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



<p>Definition at line 983 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### flatScratchIsArchitected() {#af3fc4aac61bac7b5675218848b4b8e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::flatScratchIsArchitected ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the flat_scratch register is initialized by the HW. In this case it is readonly.</p></dd>
</dl>


<p>Definition at line 1392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aaee498bf7e34783628f61d9aa83fead3">HasArchitectedFlatScratch</a>.</p>


<p>Referenced by <a href="#a3e8da3fb902e2e5c0443907cab82ba01">enableFlatScratch</a>.</p>

</div>
</div>

### flatScratchIsPointer() {#a16a3a7cc1dff82b8227571c334bc68b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::flatScratchIsPointer ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the flat_scratch register should be initialized with the pointer to the wave's scratch memory rather than a size and offset.</p></dd>
</dl>


<p>Definition at line 1386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### getAddressableNumArchVGPRs() {#a1b1c07b42d5ebde1c910cfa0025d321d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getAddressableNumArchVGPRs ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Addressable number of architectural VGPRs supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1535 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ae9f9c85e1bb9bf3a6a57b779dc3e4870">llvm::AMDGPU::IsaInfo::getAddressableNumArchVGPRs</a>.</p>

</div>
</div>

### getAddressableNumSGPRs() {#ad9bf37eb3ab2ed467ed4489666c41d27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getAddressableNumSGPRs ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Addressable number of SGPRs supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1464 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a7baaa91927748c04ac388e82788a973d">llvm::AMDGPU::IsaInfo::getAddressableNumSGPRs</a>.</p>

</div>
</div>

### getAddressableNumVGPRs() {#ad0db0ce6c2a59c442c60951a063e49b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getAddressableNumVGPRs ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Addressable number of VGPRs supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1540 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a842a99d2928e264423f0ac73b0910ec9">llvm::AMDGPU::IsaInfo::getAddressableNumVGPRs</a>.</p>

</div>
</div>

### getBaseMaxNumSGPRs() {#a6b42f0492d630514943c345ab5eb4bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getBaseMaxNumSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, std::pair&lt; unsigned, unsigned &gt; WavesPerEU, unsigned PreloadedSGPRs, unsigned ReservedNumSGPRs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>max num SGPRs. This is the common utility function called by <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> variants of getMaxNumSGPRs.</p></dd>
</dl>


<p>Declaration at line 1493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a130401d164d538061679e82aaa62716aa5b5c7c0eaf47f7ad83186812ec4198b3">llvm::AMDGPU::IsaInfo::FIXED_NUM_SGPRS_FOR_INIT_BUG</a>, <a href="#acf6141c742569e20d289c523560f8b00">getMaxNumSGPRs</a>, <a href="#a1c9934ccbee04b51f83a123e09ae9cf1">getMinNumSGPRs</a> and <a href="#a463d4dd9c6577a21b6edd9879d013113">hasSGPRInitBug</a>.</p>


<p>Referenced by <a href="#a415e45063e973508aebd65b3e5824754">getMaxNumSGPRs</a> and <a href="#aa6b158ec91f975b577a100bbc5fd8554">getMaxNumSGPRs</a>.</p>

</div>
</div>

### getBaseMaxNumVGPRs() {#a293668f13d1c676db1d1b3be25b7115d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getBaseMaxNumVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, std::pair&lt; unsigned, unsigned &gt; WavesPerEU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>max num VGPRs. This is the common utility function called by <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> variants of getMaxNumVGPRs.</p></dd>
</dl>


<p>Declaration at line 1558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a4f492fa16404497b8f15ea82c4b0a725">getMaxNumVGPRs</a>, <a href="#a61d8866021383c037a029d77a3497f23">getMinNumVGPRs</a> and <a href="#a1fc0ea9be83e3d4cb2aeb2d7b2363e73">hasGFX90AInsts</a>.</p>


<p>Referenced by <a href="#a89a0790cfbae21408e8715d0ed098ed1">getMaxNumVGPRs</a> and <a href="#adacbd1f740db810d1611b071359a2c3e">getMaxNumVGPRs</a>.</p>

</div>
</div>

### getBaseReservedNumSGPRs() {#ad65c004eab25ab815e6bc696b8fb8578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getBaseReservedNumSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool HasFlatScratch)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Reserved number of SGPRs. This is common utility function called by <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> variants of getReservedNumSGPRs.</p></dd>
</dl>


<p>Declaration at line 1483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>, <a href="#aaee498bf7e34783628f61d9aa83fead3">HasArchitectedFlatScratch</a>, <a href="#ad0dd54f1f3e1eb169b00651cd3d61da6">isXNACKEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a5a040cb5d61ebf76561fcb74c4a77970">llvm::AMDGPUSubtarget::SEA_ISLANDS</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>


<p>Referenced by <a href="#a0b81f06d449a6dc8b3d664b5edded261">getReservedNumSGPRs</a> and <a href="#a988c4c0176e7554762642cd4f0fa1b8a">getReservedNumSGPRs</a>.</p>

</div>
</div>

### getBoolRC() {#a531864eddd4fb4fb020cf583a10507c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * llvm::GCNSubtarget::getBoolRC ()</td>
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



<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ac3849d39b02d4071b4fca54e2c7f49c7">llvm::SIRegisterInfo::getBoolRC</a> and <a href="#a4e872608c63bfb1bed8f7d133d96c178">getRegisterInfo</a>.</p>

</div>
</div>

### getCallLowering() {#afe30a0d4fa09e937a7b86e983e7ccceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallLowering * llvm::GCNSubtarget::getCallLowering ()</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### getConstantBusLimit() {#a33a600e1b2e066f85e6a2bb588a7f3f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getConstantBusLimit (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>.</p>

</div>
</div>

### getFrameLowering() {#a63b043b6a8bc5e976e72ac725a7be3d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIFrameLowering * llvm::GCNSubtarget::getFrameLowering ()</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### getGeneration() {#ace4de1de19cbe837c578fb3654b6c998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Generation llvm::GCNSubtarget::getGeneration ()</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a72d895427056e0f3e9147974a95d11f8">Gen</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a528b669c7627f74c541a4800020df024">llvm::AMDGPUMCExpr::createOccupancy</a>, <a href="#a16a3a7cc1dff82b8227571c334bc68b7">flatScratchIsPointer</a>, <a href="#ad65c004eab25ab815e6bc696b8fb8578">getBaseReservedNumSGPRs</a>, <a href="#a33a600e1b2e066f85e6a2bb588a7f3f1">getConstantBusLimit</a>, <a href="#aee63988db75cc1496914d73de1fc6440">getMaxWaveScratchSize</a>, <a href="#a86673715704dada21e3529d93a5376e8">getNSAThreshold</a>, <a href="#ab20982dc4ff887572a43754228a94fc0">getOccupancyWithNumSGPRs</a>, <a href="#a7d22b584d54c1366ace6fb7fe3f972da">getSetRegWaitStates</a>, <a href="#a7332cd9b9757b3209b60ff112ba7b528">has12DWordStoreHazard</a>, <a href="#ad773dab02c945afb0bc889ebd67649c0">hasAddr64</a>, <a href="#a00fc2b6d813f3656e1715224472da22e">hasD16Images</a>, <a href="#a089a31ad15fe70858cf096b66a61b53d">hasD16LoadStore</a>, <a href="#a2c8b088118866709d3b6f35349b59b12">hasDenormModeInst</a>, <a href="#a91bc08ab0ee415853bd31422d5ce4589">hasDPPBroadcasts</a>, <a href="#a11f8b622001c4bba3eab4afb901643b8">hasDPPWavefrontShifts</a>, <a href="#a86592a7b06bb03f50836dc6b7988aff6">hasDX10ClampMode</a>, <a href="#a56c84f9bafede08443d6b28b3f9797f1">hasExtendedWaitCounts</a>, <a href="#a00e78eae9b647e527c50749797367173">hasFlat</a>, <a href="#a16018a60d1570d987fea800451277bc6">hasFlatLgkmVMemCountInOrder</a>, <a href="#ab85fb688a662d3962521663406317d17">hasFlatScratchSVSSwizzleBug</a>, <a href="#a53cf2f32851d6c5f192a752f853c581b">hasFmaakFmamkF32Insts</a>, <a href="#a1b16e18ec95818598ce11d30f59fec2a">hasFPAtomicToDenormModeHazard</a>, <a href="#aec23a7dbd85b61497ca147984ce54cbe">hasFractBug</a>, <a href="#aff8a8c0203088e3ec49d090aaaedca78">hasGWSAutoReplay</a>, <a href="#add9f234619d0fb3d8254f46b9f3dd001">hasIEEEMinMax</a>, <a href="#ab906a8b680c13e481cf016a0c111173a">hasIEEEMode</a>, <a href="#a5bdd904c6ad30cc78129f391b066c3d5">hasInstPrefetch</a>, <a href="#aff5ba6e6e7a7b0ce7126d565ddd5c5cf">hasLdsDirect</a>, <a href="#a5255251aa57df7852a7be73345a627ac">hasLdsWaitVMSRC</a>, <a href="#a60ef33c23289f161804eab76b43b6683">hasLegacyGeometry</a>, <a href="#a553d27729038fcbd05ec618b71feaf3d">hasMad64_32</a>, <a href="#a977f7068e1dd00bcd2deab2075c5eac0">hasMed3_16</a>, <a href="#a0936b3343117af1096d10094f4cc47f5">hasMergedShaders</a>, <a href="#a7af1360602eb146eabea6d2dce67dd17">hasMin3Max3_16</a>, <a href="#a297574b1f876682e29ea6ab099165998">hasMultiDwordFlatScratchAddressing</a>, <a href="#ab8f2856d03fa63b54d82cb19936082c5">hasNoF16PseudoScalarTransInlineConstants</a>, <a href="#a0f46612d8f5ca0825291c14c220c82ce">hasNonNSAEncoding</a>, <a href="#a0e686c7c8f5b335f3edce1e6711ec168">hasOnlyRevVALUShifts</a>, <a href="#a481ac8ced7100d359c1619b2520db577">hasPermLane64</a>, <a href="#ab832422d655be69a3e9b05955e4a58c9">hasPermLaneX16</a>, <a href="#ac8ee05cd6b4e404e5dc44eed03a2dd09">hasReadM0LdsDirectHazard</a>, <a href="#a88f43aaffee9d7ce03f6944a84f935c3">hasReadM0LdsDmaHazard</a>, <a href="#a4d725ba548e7482013418fef4d2917b2">hasReadM0MovRelInterpHazard</a>, <a href="#ac1d0d1c87789d65fa35257547aaa7435">hasReadM0SendMsgHazard</a>, <a href="#ada3be3eae9decd8077b5cd12f6586734">hasReadVCCZBug</a>, <a href="#ad46aa9ecc42e11cb442f7ed98b57acd3">hasRFEHazards</a>, <a href="#a0bf7687022b74bf81427ae61cc828c7c">hasRrWGMode</a>, <a href="#ad1d2c1108654a77846036ac453ea20af">hasScalarAddSub64</a>, <a href="#a0c71068f31a85453c97cfb17a44746b0">hasScalarCompareEq64</a>, <a href="#a898e8b0b4ad260533cde26a99ae409a1">hasScalarSMulU64</a>, <a href="#a3cb30b207966130ab1aa6998aaeadf07">hasScalarSubwordLoads</a>, <a href="#ac5c238e9ab9ed01ce6a652a90c57c570">hasSCmpK</a>, <a href="#a4426383e6ed12fbb51b44261e675b122">hasSignedScratchOffsets</a>, <a href="#ad35eeddb0b87d3542dcf6690a6fa655d">hasSMRDReadVALUDefHazard</a>, <a href="#ad29bdf407acea38fceff17cfc4159e3e">hasSplitBarriers</a>, <a href="#a0fa696e47a30e77762a75d6eb8fe1e34">hasUsableDivScaleConditionOutput</a>, <a href="#a10f2e810ecf2f7e2bb9150ed2c5b622a">hasUsableDSOffset</a>, <a href="#a3430658dbad45a4b93412d69c57f76a7">hasVALUMaskWriteHazard</a>, <a href="#a73adb50a215b03b117f99dee7bd1f744">hasVALUPartialForwardingHazard</a>, <a href="#a908e982d292aa3598537c78f6cd21c72">hasVALUReadSGPRHazard</a>, <a href="#ad5417712235e489ce3f1473cbf2cbb9a">hasVMEMReadSGPRVALUDefHazard</a>, <a href="#ab2fdc3a5b7196e1e439d054ccf973e3a">hasVOP3DPP</a>, <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a>, <a href="#a9d0bd109d96d0faea4a639d43910eaa0">ldsRequiresM0Init</a>, <a href="#a0556cb1a1cb30ebf22d337d400074b81">partialVCCWritesUpdateVCCZ</a>, <a href="#a3c9cd4a438837eb5883a8b62107e8219">privateMemoryResourceIsRangeChecked</a>, <a href="#a1bf8a3ec8755ac759a9f8c54ea5cf3f0">shouldClusterStores</a>, <a href="#a49c35e81b626716f6e81656a7d301a2f">supportsGetDoorbellID</a>, <a href="#aa60e0e7438de97d15bba3e5963c5751d">supportsMinMaxDenormModes</a>, <a href="#aa99f892ef918babd54c99742f34d6548">supportsWGP</a>, <a href="#a1b77b5797ab78e2aeffa5e772286d9bc">vmemWriteNeedsExpWaitcnt</a> and <a href="#a662ced5ddef5f29e53b545dfd51384e9">zeroesHigh16BitsOfDest</a>.</p>

</div>
</div>

### getInlineAsmLowering() {#a347c77a8c5972fe2d03150b5de682de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InlineAsmLowering * llvm::GCNSubtarget::getInlineAsmLowering ()</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### getInstrInfo() {#a32384420526a080b93cc98ab5a023001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo * llvm::GCNSubtarget::getInstrInfo ()</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a52716532c3562bbe9c3fc343761c3c8a">llvm::SITargetLowering::AddMemOpInit</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9fb0978a667242babb4778cdf091945c">llvm::SITargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1271e8babb762355bcb15d461f8f6a1c">llvm::SITargetLowering::bundleInstWithWaitcnt</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a82e453c9e7f441c185009164f0136fa8">llvm::SITargetLowering::emitGWSMemViolTestLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#af49d69e68344d6292702edca157e7eed">llvm::AMDGPUAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5b2c69041e8c83952d7cdd75cf7a36e8">llvm::SITargetLowering::getPrefLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9930ac25c4e4a7ff566e6301bade01e7">llvm::SITargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a00eceab7a08d0acc74a729ebd9660475">llvm::SITargetLowering::PostISelFolding</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloadstoreoptimizer-cpp-/siloadstoreoptimizer/#ab79827646b209ce331fda1c168b262e4">anonymous{SILoadStoreOptimizer.cpp}::SILoadStoreOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions/#a2d4969e8e07a8085b166f5b83efc5a8c">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnpreralongbranchreg-cpp-/gcnpreralongbranchreg/#a8b5ef68b98f901c64096eb633984c661">anonymous{GCNPreRALongBranchReg.cpp}::GCNPreRALongBranchReg::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siwholequadmode-cpp-/siwholequadmode/#ae53d8e40bdcb428165b0243af4be1dcc">anonymous{SIWholeQuadMode.cpp}::SIWholeQuadMode::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a8b55d1aa92c4d9f17904aa2c9d7c79a3">llvm::SITargetLowering::splitKillBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a085fd28c023f589357d388359f526de7">llvm::SITargetLowering::wrapAddr64Rsrc</a>.</p>

</div>
</div>

### getInstrItineraryData() {#a38931c46f7a692029325e4dcdb3ca35c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItineraryData * llvm::GCNSubtarget::getInstrItineraryData ()</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a01b60a82cd5066b5e1d29757a80965ee">InstrItins</a>.</p>


<p>Referenced by <a href="#a38ff3df1feb7915dfda6303a34484534">adjustSchedDependency</a>.</p>

</div>
</div>

### getInstructionSelector() {#a55ffd74cd6b69bfe9614b624b94f0dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector * llvm::GCNSubtarget::getInstructionSelector ()</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### getKnownHighZeroBitsForFrameIndex() {#a8a9471cfb6a3ad1bbe1296d31b716494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getKnownHighZeroBitsForFrameIndex ()</td>
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

<p>Return the number of high bits known to be zero for a frame index.</p>

<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="#aee63988db75cc1496914d73de1fc6440">getMaxWaveScratchSize</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a726f6e520aaa1372f3572d993e1027b1">llvm::AMDGPUSubtarget::getWavefrontSizeLog2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>.</p>

</div>
</div>

### getLDSBankCount() {#a0cfaf858a04f4c55a92005ab1ee5694c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::GCNSubtarget::getLDSBankCount ()</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a61d64bc81257fe4f2c899dc26a9c1660">LDSBankCount</a>.</p>

</div>
</div>

### getLegalizerInfo() {#ac6a4865aed3c7bdbdd3aa1cde206364a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo * llvm::GCNSubtarget::getLegalizerInfo ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### getMaxFlatWorkGroupSize() {#ab5784d58015d7b40f2750f80f4ef6aeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMaxFlatWorkGroupSize ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum flat work group size supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1616 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a329b5f490df50f14bf5c359c0a01e99a">llvm::AMDGPU::IsaInfo::getMaxFlatWorkGroupSize</a>.</p>

</div>
</div>

### getMaxLocalMemSizeWithWaveCount() {#a3a4d0d821e43aa63626b7f19b27dc189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMaxLocalMemSizeWithWaveCount (unsigned WaveCount, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the amount of LDS that can be used that will not restrict the occupancy lower than WaveCount.</p>

<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### getMaxNumAGPRs() {#a4ccb66bcde5267a76db443eee0a601ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMaxNumAGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 1570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a4f492fa16404497b8f15ea82c4b0a725">getMaxNumVGPRs</a>.</p>

</div>
</div>

### getMaxNumSGPRs() {#acf6141c742569e20d289c523560f8b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMaxNumSGPRs (unsigned WavesPerEU, bool Addressable)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum number of SGPRs that meets the given number of waves per execution unit requirement supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a98803f3d3a9a7e50ad0f40bdf8cd8190">llvm::AMDGPU::IsaInfo::getMaxNumSGPRs</a>.</p>


<p>Referenced by <a href="#a6b42f0492d630514943c345ab5eb4bc0">getBaseMaxNumSGPRs</a>.</p>

</div>
</div>

### getMaxNumSGPRs() {#aa6b158ec91f975b577a100bbc5fd8554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getMaxNumSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum number of SGPRs that meets number of waves per execution unit requirement for function <span class="doxyComputerOutput">MF</span>, or number of SGPRs explicitly requested using "amdgpu-num-sgpr" attribute attached to function <span class="doxyComputerOutput">MF</span>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that meets number of waves per execution unit requirement if explicitly requested value cannot be converted to integer, violates subtarget's specifications, or does not meet number of waves per execution unit requirement.</p></dd>
</dl>


<p>Declaration at line 1506 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a6b42f0492d630514943c345ab5eb4bc0">getBaseMaxNumSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a0ecfadb60fa955d669e8d7a0ad505c5b">llvm::SIMachineFunctionInfo::getNumPreloadedSGPRs</a>, <a href="#a988c4c0176e7554762642cd4f0fa1b8a">getReservedNumSGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1a8e6eb732007b918c42b4a15b55f0a4">llvm::SIMachineFunctionInfo::getWavesPerEU</a>.</p>

</div>
</div>

### getMaxNumSGPRs() {#a415e45063e973508aebd65b3e5824754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getMaxNumSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum number of SGPRs that meets number of waves per execution unit requirement for function <span class="doxyComputerOutput">F</span>, or number of SGPRs explicitly requested using "amdgpu-num-sgpr" attribute attached to function <span class="doxyComputerOutput">F</span>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that meets number of waves per execution unit requirement if explicitly requested value cannot be converted to integer, violates subtarget's specifications, or does not meet number of waves per execution unit requirement.</p></dd>
</dl>


<p>Declaration at line 1516 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a6b42f0492d630514943c345ab5eb4bc0">getBaseMaxNumSGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp/#aa8a25c2fa755917ce57785c5fdaf3ef3">getMaxNumPreloadedSGPRs</a>, <a href="#a988c4c0176e7554762642cd4f0fa1b8a">getReservedNumSGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a3861ef4f23f9a124d85adbdd063dab9c">llvm::AMDGPUSubtarget::getWavesPerEU</a>.</p>

</div>
</div>

### getMaxNumUserSGPRs() {#ab691b3244b89f5993decf425f570341c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMaxNumUserSGPRs ()</td>
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



<p>Definition at line 1003 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2b981a267feb0c817f91ab394b62699a">llvm::AMDGPU::getMaxNumUserSGPRs</a>.</p>

</div>
</div>

### getMaxNumVGPRs() {#a4f492fa16404497b8f15ea82c4b0a725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMaxNumVGPRs (unsigned WavesPerEU)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the maximum number of VGPRs that can be used and still achieved at least the specified number of waves <span class="doxyComputerOutput">WavesPerEU</span>.</p></dd>
</dl>


<p>Definition at line 1552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ac865befe5b2563e7df0c82f5ff5ba5f2">llvm::AMDGPU::IsaInfo::getMaxNumVGPRs</a>.</p>


<p>Referenced by <a href="#a293668f13d1c676db1d1b3be25b7115d">getBaseMaxNumVGPRs</a> and <a href="#a4ccb66bcde5267a76db443eee0a601ac">getMaxNumAGPRs</a>.</p>

</div>
</div>

### getMaxNumVGPRs() {#a89a0790cfbae21408e8715d0ed098ed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getMaxNumVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum number of VGPRs that meets number of waves per execution unit requirement for function <span class="doxyComputerOutput">F</span>, or number of VGPRs explicitly requested using "amdgpu-num-vgpr" attribute attached to function <span class="doxyComputerOutput">F</span>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that meets number of waves per execution unit requirement if explicitly requested value cannot be converted to integer, violates subtarget's specifications, or does not meet number of waves per execution unit requirement.</p></dd>
</dl>


<p>Declaration at line 1568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a293668f13d1c676db1d1b3be25b7115d">getBaseMaxNumVGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a3861ef4f23f9a124d85adbdd063dab9c">llvm::AMDGPUSubtarget::getWavesPerEU</a>.</p>

</div>
</div>

### getMaxNumVGPRs() {#adacbd1f740db810d1611b071359a2c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getMaxNumVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum number of VGPRs that meets number of waves per execution unit requirement for function <span class="doxyComputerOutput">MF</span>, or number of VGPRs explicitly requested using "amdgpu-num-vgpr" attribute attached to function <span class="doxyComputerOutput">MF</span>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that meets number of waves per execution unit requirement if explicitly requested value cannot be converted to integer, violates subtarget's specifications, or does not meet number of waves per execution unit requirement.</p></dd>
</dl>


<p>Declaration at line 1582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a293668f13d1c676db1d1b3be25b7115d">getBaseMaxNumVGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1a8e6eb732007b918c42b4a15b55f0a4">llvm::SIMachineFunctionInfo::getWavesPerEU</a>.</p>

</div>
</div>

### getMaxPrivateElementSize() {#aa1c8834f883c6607231b902a1f37ddbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMaxPrivateElementSize (bool ForBufferRSrc=false)</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#a3e8da3fb902e2e5c0443907cab82ba01">enableFlatScratch</a> and <a href="#a18efbf5a73b167d005a9d1004816ab00">MaxPrivateElementSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ac9c871c7f1222d14e8f90aca6f4c71f3">llvm::SITargetLowering::canMergeStoresTo</a>.</p>

</div>
</div>

### getMaxWaveScratchSize() {#aee63988db75cc1496914d73de1fc6440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMaxWaveScratchSize ()</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>


<p>Referenced by <a href="#a8a9471cfb6a3ad1bbe1296d31b716494">getKnownHighZeroBitsForFrameIndex</a>.</p>

</div>
</div>

### getMaxWavesPerEU() {#ab96f321c806effcca947691e54b24784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPUSubtarget::getMaxWavesPerEU ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum number of waves per execution unit supported by the subtarget without any kind of limitation.</p></dd>
</dl>


<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusubtarget-h">AMDGPUSubtarget.h</a>.</p>


<p>Referenced by <a href="#ab20982dc4ff887572a43754228a94fc0">getOccupancyWithNumSGPRs</a>.</p>

</div>
</div>

### getMaxWorkGroupsPerCU() {#a32e4f8d7e4a12870752efe1ff494c96d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMaxWorkGroupsPerCU (unsigned FlatWorkGroupSize)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum number of work groups per compute unit supported by the subtarget and limited by given <span class="doxyComputerOutput">FlatWorkGroupSize</span>.</p></dd>
</dl>


<p>Definition at line 1606 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a2d0c61cd3e4d53626ffdb34031766f08">llvm::AMDGPU::IsaInfo::getMaxWorkGroupsPerCU</a>.</p>

</div>
</div>

### getMinFlatWorkGroupSize() {#aa214881f596f9adddeef9df6600df144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMinFlatWorkGroupSize ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Minimum flat work group size supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a8dd1efaf10bea58df5259c9a0c223d9a">llvm::AMDGPU::IsaInfo::getMinFlatWorkGroupSize</a>.</p>

</div>
</div>

### getMinNumSGPRs() {#a1c9934ccbee04b51f83a123e09ae9cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMinNumSGPRs (unsigned WavesPerEU)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Minimum number of SGPRs that meets the given number of waves per execution unit requirement supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1470 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a8712096d79b8b76954f261f06351c34f">llvm::AMDGPU::IsaInfo::getMinNumSGPRs</a>.</p>


<p>Referenced by <a href="#a6b42f0492d630514943c345ab5eb4bc0">getBaseMaxNumSGPRs</a>.</p>

</div>
</div>

### getMinNumVGPRs() {#a61d8866021383c037a029d77a3497f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMinNumVGPRs (unsigned WavesPerEU)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the minimum number of VGPRs that will prevent achieving more than the specified number of waves <span class="doxyComputerOutput">WavesPerEU</span>.</p></dd>
</dl>


<p>Definition at line 1546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a6fd9b23b6adf6877d2baba38030b77c1">llvm::AMDGPU::IsaInfo::getMinNumVGPRs</a>.</p>


<p>Referenced by <a href="#a293668f13d1c676db1d1b3be25b7115d">getBaseMaxNumVGPRs</a>.</p>

</div>
</div>

### getMinWavesPerEU() {#a2ea42736115781162e371685322542f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getMinWavesPerEU ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Minimum number of waves per execution unit supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1629 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a9a0082c7f646f15a4a1a7fe1bad0ec89">llvm::AMDGPU::IsaInfo::getMinWavesPerEU</a>.</p>

</div>
</div>

### getNSAMaxSize() {#aaf548cba17900940ca7f8466e3d5ae3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getNSAMaxSize (bool HasSampler=false)</td>
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



<p>Definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a329c56090fef55473ff6ae5bc6e8d9b8">llvm::AMDGPU::getNSAMaxSize</a>.</p>

</div>
</div>

### getNSAThreshold() {#a86673715704dada21e3529d93a5376e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getNSAThreshold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a4c866d3504a1e0717c8152a590bd6203">llvm::Function::getFnAttributeAsParsedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp/#a3ca008fd6ff87e007f6613d9ce0cad53">NSAThreshold</a>.</p>

</div>
</div>

### getOccupancyWithNumSGPRs() {#ab20982dc4ff887572a43754228a94fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getOccupancyWithNumSGPRs (unsigned SGPRs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the maximum number of waves per SIMD for kernels using <span class="doxyComputerOutput">SGPRs</span> SGPRs.</p>

<p>Declaration at line 1365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a>, <a href="#ab96f321c806effcca947691e54b24784">getMaxWavesPerEU</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ad60a1f0eb9449d779a645ab620c4c36b">llvm::AMDGPU::IsaInfo::getOccupancyWithNumSGPRs</a>.</p>


<p>Referenced by <a href="#a78f78fef97b3e953f2f4992c369026d8">computeOccupancy</a>.</p>

</div>
</div>

### getOccupancyWithNumVGPRs() {#aa19ea7d1223b3dbc9f1c432059f8e040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getOccupancyWithNumVGPRs (unsigned VGPRs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the maximum number of waves per SIMD for kernels using <span class="doxyComputerOutput">VGPRs</span> VGPRs.</p>

<p>Declaration at line 1369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab56dd7bdfea0401c802b4c94cb76ef1e">llvm::AMDGPU::IsaInfo::getNumWavesPerEUWithNumVGPRs</a>.</p>


<p>Referenced by <a href="#a78f78fef97b3e953f2f4992c369026d8">computeOccupancy</a>.</p>

</div>
</div>

### getRegBankInfo() {#a5f6ce22a25ef1ddd72285891220b9205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPURegisterBankInfo * llvm::GCNSubtarget::getRegBankInfo ()</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### getRegisterInfo() {#a4e872608c63bfb1bed8f7d133d96c178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIRegisterInfo * llvm::GCNSubtarget::getRegisterInfo ()</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a38ff3df1feb7915dfda6303a34484534">adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a5f21271c9d2a610d15219c54ba44bef3">llvm::GCNTargetMachine::convertFuncInfoToYAML</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#af49d69e68344d6292702edca157e7eed">llvm::AMDGPUAsmPrinter::emitInstruction</a>, <a href="#a531864eddd4fb4fb020cf583a10507c1">getBoolRC</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1dfc6019f3ac9b3b50bfc020a60baf7c">llvm::SITargetLowering::insertCopiesSplitCSR</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9330a86a613cf892ee5c7f515713f200">llvm::SITargetLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a4119a7f5d262af0d89332b5c2d30abbc">llvm::AMDGPUCallLowering::lowerFormalArgumentsKernel</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmasking-cpp-/sioptimizeexecmasking/#a3f94a6aec90b35cbf3ae3345cba041de">anonymous{SIOptimizeExecMasking.cpp}::SIOptimizeExecMasking::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnpreralongbranchreg-cpp-/gcnpreralongbranchreg/#a8b5ef68b98f901c64096eb633984c661">anonymous{GCNPreRALongBranchReg.cpp}::GCNPreRALongBranchReg::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#acaca0c9ffff0d1cba0462a1daccf5f12">llvm::SITargetLowering::SITargetLowering</a>.</p>

</div>
</div>

### getReservedNumSGPRs() {#a988c4c0176e7554762642cd4f0fa1b8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getReservedNumSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Reserved number of SGPRs for given machine function <span class="doxyComputerOutput">MF</span>.</p></dd>
</dl>


<p>Declaration at line 1485 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="#ad65c004eab25ab815e6bc696b8fb8578">getBaseReservedNumSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1dc64be914cf9386846075f0c66c577b">llvm::SIMachineFunctionInfo::getUserSGPRInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnusersgprusageinfo/#af46f82034f9728539337d5c45e668642">llvm::GCNUserSGPRUsageInfo::hasFlatScratchInit</a>.</p>


<p>Referenced by <a href="#a415e45063e973508aebd65b3e5824754">getMaxNumSGPRs</a> and <a href="#aa6b158ec91f975b577a100bbc5fd8554">getMaxNumSGPRs</a>.</p>

</div>
</div>

### getReservedNumSGPRs() {#a0b81f06d449a6dc8b3d664b5edded261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSubtarget::getReservedNumSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Reserved number of SGPRs for given function <span class="doxyComputerOutput">F</span>.</p></dd>
</dl>


<p>Declaration at line 1488 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ad65c004eab25ab815e6bc696b8fb8578">getBaseReservedNumSGPRs</a> and <a href="#a90fc707270386fb970207745d6675805">hasFlatAddressSpace</a>.</p>

</div>
</div>

### getScalarizeGlobalBehavior() {#a87235fdebcb88e0c5646333d222dca22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::getScalarizeGlobalBehavior ()</td>
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



<p>Definition at line 988 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a4f5630510fbbd84621962f555f9d697e">ScalarizeGlobal</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#af8dc3dcdfa89ef9d400894ab264ec05a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SelectionDAGTargetInfo * GCNSubtarget::getSelectionDAGInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>

</div>
</div>

### getSetRegWaitStates() {#a7d22b584d54c1366ace6fb7fe3f972da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getSetRegWaitStates ()</td>
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

<p>Number of hazard wait states for s_setreg_b32/s_setreg_imm32_b32.</p>

<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a5a040cb5d61ebf76561fcb74c4a77970">llvm::AMDGPUSubtarget::SEA_ISLANDS</a>.</p>

</div>
</div>

### getSGPRAllocGranule() {#a120ab447b09dc6bafd750961802ca264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getSGPRAllocGranule ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>SGPR allocation granularity supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#aa82573eec93913f61c5fe97062d60c7e">llvm::AMDGPU::IsaInfo::getSGPRAllocGranule</a>.</p>

</div>
</div>

### getSGPREncodingGranule() {#a1cc464816b0b6f1497cbb07c51cb0a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getSGPREncodingGranule ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>SGPR encoding granularity supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a4f89565a53fec2d53160be82c292202e">llvm::AMDGPU::IsaInfo::getSGPREncodingGranule</a>.</p>

</div>
</div>

### getStackAlignment() {#a3bcaef9c28343b5c427f24079ac6fcdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::GCNSubtarget::getStackAlignment ()</td>
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



<p>Definition at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#acf1aa5ffc0b59dd205f5dc5142580771">GCNSubtarget</a>.</p>

</div>
</div>

### getTargetID() {#a6f4d618b8e68e3ec2216c10bf66a18d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPU::IsaInfo::AMDGPUTargetID &amp; llvm::GCNSubtarget::getTargetID ()</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#afc6af409114a5e2da7bc8bedf9024cdc">TargetID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### getTargetLowering() {#a7d34f15ff5049d93e832e39c3693b29f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SITargetLowering * llvm::GCNSubtarget::getTargetLowering ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#acf1aa5ffc0b59dd205f5dc5142580771">GCNSubtarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>.</p>

</div>
</div>

### getTotalNumSGPRs() {#a377dcbfe45feb26ed8654cfce84087af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getTotalNumSGPRs ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Total number of SGPRs supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1459 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#afeb7e0bccf88c9d23d02454609eb431a">llvm::AMDGPU::IsaInfo::getTotalNumSGPRs</a>.</p>

</div>
</div>

### getTotalNumVGPRs() {#a2e649388bef9c44bc294dab940cd6b84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getTotalNumVGPRs ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Total number of VGPRs supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a14accda22ecd133d48fa434165e690a0">llvm::AMDGPU::IsaInfo::getTotalNumVGPRs</a>.</p>

</div>
</div>

### getTrapHandlerAbi() {#a62a67f91a73c5a80be0a080a7d6f3c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrapHandlerAbi llvm::GCNSubtarget::getTrapHandlerAbi ()</td>
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



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#a347289a8e670a14bc5c60464df2f445caf778ffa73665e8e41448bf12f1350f02">AMDHSA</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#acf005b2695c64eb57157215562463116">llvm::AMDGPUSubtarget::isAmdHsaOS</a> and <a href="#a347289a8e670a14bc5c60464df2f445cab50339a10e1de285ac99d4c3990b8693">NONE</a>.</p>

</div>
</div>

### getVGPRAllocGranule() {#a4d631f933bed8f5b71e58638f024b87c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getVGPRAllocGranule ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>VGPR allocation granularity supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1519 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ae47a2723f63ec4e85b4228b56e5d759c">llvm::AMDGPU::IsaInfo::getVGPRAllocGranule</a>.</p>

</div>
</div>

### getVGPREncodingGranule() {#a5636afb498eec4770235c34d76f8e36f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getVGPREncodingGranule ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>VGPR encoding granularity supported by the subtarget.</p></dd>
</dl>


<p>Definition at line 1524 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a00ddec6f625f5fdc41b2ee64b272b5b9">llvm::AMDGPU::IsaInfo::getVGPREncodingGranule</a>.</p>

</div>
</div>

### getWavesPerEUForWorkGroup() {#abd3d507136dc902e56d585a7dd9d729e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::getWavesPerEUForWorkGroup (unsigned FlatWorkGroupSize)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of waves per execution unit required to support the given <span class="doxyComputerOutput">FlatWorkGroupSize</span>.</p></dd>
</dl>


<p>Definition at line 1623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a170ce837300501b1468ea55b3e5081a1">llvm::AMDGPU::IsaInfo::getWavesPerEUForWorkGroup</a>.</p>

</div>
</div>

### has1\_5xVGPRs() {#a0cc2fccd89413e7c79e54d4b657872c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::has1_5xVGPRs ()</td>
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



<p>Definition at line 1289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a056c928381864fc1f037babbad25f392">Has1_5xVGPRs</a>.</p>

</div>
</div>

### has12DWordStoreHazard() {#a7332cd9b9757b3209b60ff112ba7b528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::has12DWordStoreHazard ()</td>
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



<p>Definition at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aafd52d574f92cc47671a38d95bca9988">llvm::AMDGPUSubtarget::SOUTHERN_ISLANDS</a>.</p>

</div>
</div>

### hasA16() {#a0985b28a440a19cc9e6b8229e75b5152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasA16 ()</td>
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



<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ac2670ded2f52b0a8abebe0bad06cf2fd">HasA16</a>.</p>

</div>
</div>

### hasAddNoCarry() {#ae431b2e8fc0aee94b01cece42984d2dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAddNoCarry ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the target has integer add/sub instructions that do not produce a carry-out. This includes v_add_[iu]32, v_sub_[iu]32, v_add_[iu]16, and v_sub_[iu]16, all of which support the clamp modifier for saturation.</p></dd>
</dl>


<p>Definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a238786700161fe23c5060ff610ee2968">AddNoCarryInsts</a>.</p>

</div>
</div>

### hasAddr64() {#ad773dab02c945afb0bc889ebd67649c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAddr64 ()</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>


<p>Referenced by <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### hasApertureRegs() {#a18ef501217029506f0ed9027ff266480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasApertureRegs ()</td>
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



<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#abe6001a0f135daa1bb722da2e6197aaa">HasApertureRegs</a>.</p>

</div>
</div>

### hasArchitectedSGPRs() {#a297a2e0f9d548e720e1303be506ee7a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasArchitectedSGPRs ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the architected SGPRs are enabled.</p></dd>
</dl>


<p>Definition at line 1395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#addd8731d7f792b6ae461a3e677e853b9">HasArchitectedSGPRs</a>.</p>

</div>
</div>

### hasAshrPkInsts() {#a5c9b0d88a0394d2496b7aa56842f6def}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAshrPkInsts ()</td>
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



<p>Definition at line 1342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a9da82d4d3ac2f557507d846bd9936a67">HasAshrPkInsts</a>.</p>

</div>
</div>

### hasAtomicBufferGlobalPkAddF16Insts() {#acfcf88257e77cb54415205652e2e88ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicBufferGlobalPkAddF16Insts ()</td>
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



<p>Definition at line 883 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aa0ad796f74734bb5b657a1f2d1a7ed44">HasAtomicBufferGlobalPkAddF16Insts</a>.</p>

</div>
</div>

### hasAtomicBufferGlobalPkAddF16NoRtnInsts() {#ab0a8ac068b8f8aa548a3ce1fe90dad8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicBufferGlobalPkAddF16NoRtnInsts ()</td>
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



<p>Definition at line 879 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aac211a8f705f61a60b6ced36b9731e3e">HasAtomicBufferGlobalPkAddF16NoRtnInsts</a>.</p>

</div>
</div>

### hasAtomicBufferPkAddBF16Inst() {#ab34bcbfbfadd8de8a1172c659d3d2aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicBufferPkAddBF16Inst ()</td>
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



<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aa6afb3f2adf199a6465ae5f8015cfd79">HasAtomicBufferPkAddBF16Inst</a>.</p>

</div>
</div>

### hasAtomicCSub() {#afc3b60da830f13bd93a91b751d5cfaf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicCSub ()</td>
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



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a25a9bffea45bd561499b442b0544ccb8">GFX10_BEncoding</a>.</p>

</div>
</div>

### hasAtomicCSubNoRtnInsts() {#a702e9540e27a17a550b4937032b939e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicCSubNoRtnInsts ()</td>
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



<p>Definition at line 1423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aa295bd451d30d00f2fde59fa44045434">HasAtomicCSubNoRtnInsts</a>.</p>

</div>
</div>

### hasAtomicDsPkAdd16Insts() {#a0318f31ec7d1b90f27b5413cd224663c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicDsPkAdd16Insts ()</td>
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



<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aa3642c58f343c3c3a82877e1afb7db5e">HasAtomicDsPkAdd16Insts</a>.</p>

</div>
</div>

### hasAtomicFaddInsts() {#aab7b3ab8cbd1cf72b5e93d6983a748a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicFaddInsts ()</td>
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



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#a9e196e9035b546b74522a169d0a1c45f">HasAtomicFaddNoRtnInsts</a> and <a href="#adae5a837f4ede6853fdaec64c4892d51">HasAtomicFaddRtnInsts</a>.</p>

</div>
</div>

### hasAtomicFaddNoRtnInsts() {#ab7f9c6b88d7dd2493b9c6a68112a68c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicFaddNoRtnInsts ()</td>
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



<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a9e196e9035b546b74522a169d0a1c45f">HasAtomicFaddNoRtnInsts</a>.</p>

</div>
</div>

### hasAtomicFaddRtnInsts() {#a3779799f24ab110dc3a64ebfb9f472bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicFaddRtnInsts ()</td>
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



<p>Definition at line 875 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#adae5a837f4ede6853fdaec64c4892d51">HasAtomicFaddRtnInsts</a>.</p>

</div>
</div>

### hasAtomicFlatPkAdd16Insts() {#a9bce2aae2056dd71265b887b181e17c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicFlatPkAdd16Insts ()</td>
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



<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a85c2d01235c0d1375f99e77b6b604771">HasAtomicFlatPkAdd16Insts</a>.</p>

</div>
</div>

### hasAtomicFMinFMaxF32FlatInsts() {#a1ba00ffdcbb35e817245f6903180e271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicFMinFMaxF32FlatInsts ()</td>
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



<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a8817af4d2308f9cdb31a8b57fc797007">HasAtomicFMinFMaxF32FlatInsts</a>.</p>

</div>
</div>

### hasAtomicFMinFMaxF32GlobalInsts() {#a68a2942b35679bd8c4f413436f58b54f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicFMinFMaxF32GlobalInsts ()</td>
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



<p>Definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a86f942a251a036fb225fb8f8f0deb555">HasAtomicFMinFMaxF32GlobalInsts</a>.</p>

</div>
</div>

### hasAtomicFMinFMaxF64FlatInsts() {#a143ff62a1e0eae583030d0787c1219ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicFMinFMaxF64FlatInsts ()</td>
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



<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a07f6f1c9612fe2ec6fed7f949a8ebe26">HasAtomicFMinFMaxF64FlatInsts</a>.</p>

</div>
</div>

### hasAtomicFMinFMaxF64GlobalInsts() {#a968992bddefc74c03eda64e5889e7116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicFMinFMaxF64GlobalInsts ()</td>
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



<p>Definition at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ac8a0f2f00bafd753b886d0c61cef8dd3">HasAtomicFMinFMaxF64GlobalInsts</a>.</p>

</div>
</div>

### hasAtomicGlobalPkAddBF16Inst() {#ad71a92219d05963817490411ca445902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAtomicGlobalPkAddBF16Inst ()</td>
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



<p>Definition at line 887 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ad8bbc65850f15c486cc2cf5935c0c709">HasAtomicGlobalPkAddBF16Inst</a>.</p>

</div>
</div>

### hasAutoWaitcntBeforeBarrier() {#a361e1bd0ac3e221a2fe75f68ea9d0d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasAutoWaitcntBeforeBarrier ()</td>
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



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a3336ba2851ac5650dc025a8642214e35">AutoWaitcntBeforeBarrier</a>.</p>

</div>
</div>

### hasBCNT() {#a26eea6294674b212aef650094cdbd54e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasBCNT (unsigned Size)</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### hasBFE() {#afe5c2cff6531de48bb6a70e1f3812f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasBFE ()</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#abeb6d1062f8ac41bba35b40d251d1860">hasBFM</a>.</p>

</div>
</div>

### hasBFI() {#a9ca681e25480ee5684196eb8641148ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasBFI ()</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### hasBFM() {#abeb6d1062f8ac41bba35b40d251d1860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasBFM ()</td>
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



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#afe5c2cff6531de48bb6a70e1f3812f8c">hasBFE</a>.</p>

</div>
</div>

### hasBitOp3Insts() {#a1ae9d4320920b5bd1a193c69c22c1dbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasBitOp3Insts ()</td>
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



<p>Definition at line 1338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ac8bdaf283ec09f2b9c47ced006837467">HasBitOp3Insts</a>.</p>

</div>
</div>

### hasCARRY() {#ae007c4b2c43d54e68a32fa29d8411ba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasCARRY ()</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### hasCompressedExport() {#a1f222ef89ce8fb3fe994bd2c7103f843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasCompressedExport ()</td>
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

<p>Return true if the target's EXP instruction has the COMPR flag, which affects the meaning of the EN (enable) bits.</p>

<p>Definition at line 1283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a23594b888d739de018ed2a227d711ced">GFX11Insts</a>.</p>

</div>
</div>

### hasCvtFP8VOP1Bug() {#aa4f5adb4d0fdc24fcb3947f50a4c6645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasCvtFP8VOP1Bug ()</td>
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



<p>Definition at line 1419 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ae790c1da8d9eba51c60d614ef837f80c">HasCvtFP8Vop1Bug</a>.</p>

</div>
</div>

### hasCvtScaleForwardingHazard() {#a2e1c82209fdf5c7efc8a19f003b60a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasCvtScaleForwardingHazard ()</td>
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



<p>Definition at line 1265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ac164adfdd62c69dbd820c417d2c24de0">GFX950Insts</a>.</p>

</div>
</div>

### hasD16Images() {#a00fc2b6d813f3656e1715224472da22e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasD16Images ()</td>
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



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>

</div>
</div>

### hasD16LoadStore() {#a089a31ad15fe70858cf096b66a61b53d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasD16LoadStore ()</td>
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



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>


<p>Referenced by <a href="#a596080bfe7eb1bc232a7c9381a5e784c">d16PreservesUnusedBits</a>.</p>

</div>
</div>

### hasDefaultComponentBroadcast() {#afca224687236c554e05ec7495f5f5b26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDefaultComponentBroadcast ()</td>
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



<p>Definition at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a8faff728ce71f6506ee26c230f8e9910">HasDefaultComponentBroadcast</a>.</p>

</div>
</div>

### hasDefaultComponentZero() {#a1e5c0a7c3425568c65564eb43572f6f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDefaultComponentZero ()</td>
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



<p>Definition at line 916 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aee91c4560c47c3b5bb78a641a5559ba4">HasDefaultComponentZero</a>.</p>

</div>
</div>

### hasDelayAlu() {#abf65492620612e129dd3e847a2c4e57f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDelayAlu ()</td>
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

<p>Return true if the target has the S_DELAY_ALU instruction.</p>

<p>Definition at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a23594b888d739de018ed2a227d711ced">GFX11Insts</a>.</p>

</div>
</div>

### hasDenormModeInst() {#a2c8b088118866709d3b6f35349b59b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDenormModeInst ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>If target supports S_DENORM_MODE.</p></dd>
</dl>


<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>.</p>

</div>
</div>

### hasDLInsts() {#a24618695d970449f186b50c63648f674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDLInsts ()</td>
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



<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a5e04190f533d5235647a1e89f9d83014">HasDLInsts</a>.</p>

</div>
</div>

### hasDot10Insts() {#aa3faef1a7ec189bbf0d27fbcd91b179c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot10Insts ()</td>
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



<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#acfb9f1d4990af79ac841d54ff4a51f6e">HasDot10Insts</a>.</p>

</div>
</div>

### hasDot11Insts() {#a3dcf980f5642f70d5cc92ad78107aa42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot11Insts ()</td>
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



<p>Definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a04c4ff7828efe3cd1ba4a631f899299d">HasDot11Insts</a>.</p>

</div>
</div>

### hasDot12Insts() {#ac76360a6bc40d4eda96a8fa387aec898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot12Insts ()</td>
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



<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ad0ba569ec8d5c4c8a1017745af2231fa">HasDot12Insts</a>.</p>

</div>
</div>

### hasDot13Insts() {#a9cb42a977c1487218f417ea5bd4b8f85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot13Insts ()</td>
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



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a1bca337aa04112b4496e6a2569c92694">HasDot13Insts</a>.</p>

</div>
</div>

### hasDot1Insts() {#a3381161b7a2623d70ebc79101439de62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot1Insts ()</td>
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



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ad9f698137ecac3f8bfd57c1d2bd225bb">HasDot1Insts</a>.</p>

</div>
</div>

### hasDot2Insts() {#a088b522817602bb6d879afbb1dd28d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot2Insts ()</td>
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



<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a9682ddcf41ed820be15cc7218775fe87">HasDot2Insts</a>.</p>

</div>
</div>

### hasDot3Insts() {#a338f477b9e95f79dd790b1962ca6adc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot3Insts ()</td>
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



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a3520574a8e86bbe157a34c179c9747da">HasDot3Insts</a>.</p>

</div>
</div>

### hasDot4Insts() {#af0b7da2e35759b56235cc538ab7c0e1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot4Insts ()</td>
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



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a8694a6472636f253ac7a422066ee9e8d">HasDot4Insts</a>.</p>

</div>
</div>

### hasDot5Insts() {#ab66fd170ebeaddc8ed07d4db2c2a77b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot5Insts ()</td>
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



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ae6ded25230b26b659566be69c769d464">HasDot5Insts</a>.</p>

</div>
</div>

### hasDot6Insts() {#a80150d52bbde3f5caaaf2d6d2a5b8122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot6Insts ()</td>
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



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a02ff9dd7be4e70091e99c1997741eda8">HasDot6Insts</a>.</p>

</div>
</div>

### hasDot7Insts() {#a182d4bc6088accdac52a4b4eb362abf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot7Insts ()</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a6e3d3703aae398dc4469527df9c758e3">HasDot7Insts</a>.</p>

</div>
</div>

### hasDot8Insts() {#ac39193e57744e29d333b5790b4d4e656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot8Insts ()</td>
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



<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a8a489d835ec8202127cea0eb9ce07dce">HasDot8Insts</a>.</p>

</div>
</div>

### hasDot9Insts() {#af98e76929ea61bb6075f5146cd2fe0fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDot9Insts ()</td>
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



<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a86c2b493bd4f475fb096ae324d582826">HasDot9Insts</a>.</p>

</div>
</div>

### hasDOTOpSelHazard() {#a4fa10ba2f5551b22c35eecfa74b3296a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDOTOpSelHazard ()</td>
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



<p>Definition at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#a23594b888d739de018ed2a227d711ced">GFX11Insts</a> and <a href="#a167f1c9d969e90ea41a3dd52a37b32e6">GFX940Insts</a>.</p>

</div>
</div>

### hasDPALU\_DPP() {#ad6b35f7e88b68cba1844915dc16db9ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDPALU_DPP ()</td>
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



<p>Definition at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a2447a5253106678c1dfe0bab536c7c9d">HasDPALU_DPP</a>.</p>

</div>
</div>

### hasDPP() {#a5eebe2da3e17c5d7c4b4f4dfecdb4df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDPP ()</td>
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



<p>Definition at line 1044 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a389b331031e56958a8f3da55723465fd">HasDPP</a>.</p>

</div>
</div>

### hasDPP8() {#ab6327e2570c1c58c44b5fc646ec82f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDPP8 ()</td>
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



<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a23518644c73072ed1e0e8d627be8ba01">HasDPP8</a>.</p>

</div>
</div>

### hasDPPBroadcasts() {#a91bc08ab0ee415853bd31422d5ce4589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDPPBroadcasts ()</td>
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



<p>Definition at line 1048 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a> and <a href="#a389b331031e56958a8f3da55723465fd">HasDPP</a>.</p>

</div>
</div>

### hasDPPSrc1SGPR() {#aedc86d07fcc0b61c6f1e138c76432aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDPPSrc1SGPR ()</td>
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



<p>Definition at line 1064 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a87170f8953730e15a8dfe935c37232dc">HasDPPSrc1SGPR</a>.</p>

</div>
</div>

### hasDPPWavefrontShifts() {#a11f8b622001c4bba3eab4afb901643b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDPPWavefrontShifts ()</td>
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



<p>Definition at line 1052 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a> and <a href="#a389b331031e56958a8f3da55723465fd">HasDPP</a>.</p>

</div>
</div>

### hasDS96AndDS128() {#ac79093e78236587f3f298fd96a06947e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDS96AndDS128 ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>If target supports ds_read/write_b96/128.</p></dd>
</dl>


<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aaef4f045c922c0ae9c8a500e0e2c29d4">CIInsts</a>.</p>

</div>
</div>

### hasDstSelForwardingHazard() {#a2017ee435d93b4ec8c38e024d5cb9b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDstSelForwardingHazard ()</td>
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



<p>Definition at line 1229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a167f1c9d969e90ea41a3dd52a37b32e6">GFX940Insts</a>.</p>

</div>
</div>

### hasDwordx3LoadStores() {#a437295c0cecbdbec197e655e34cab714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDwordx3LoadStores ()</td>
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



<p>Definition at line 1168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aaef4f045c922c0ae9c8a500e0e2c29d4">CIInsts</a>.</p>

</div>
</div>

### hasDX10ClampMode() {#a86592a7b06bb03f50836dc6b7988aff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasDX10ClampMode ()</td>
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



<p>Definition at line 1426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasExportInsts() {#a5ecc5f8b91d701d17ec10a6b57686dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasExportInsts ()</td>
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



<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a80ef035f066bb00307e5cccb694e20e2">hasGFX940Insts</a>.</p>

</div>
</div>

### hasExtendedImageInsts() {#a254ad120b3ae58ca663832ba14592457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasExtendedImageInsts ()</td>
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



<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a08e442e1f7eb5131692ccd5bba77774c">HasExtendedImageInsts</a>.</p>

</div>
</div>

### hasExtendedWaitCounts() {#a56c84f9bafede08443d6b28b3f9797f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasExtendedWaitCounts ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the target uses LOADcnt/SAMPLEcnt/BVHcnt, DScnt/KMcnt and STOREcnt rather than VMcnt, LGKMcnt and VScnt respectively.</p></dd>
</dl>


<p>Definition at line 1327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasFFBH() {#aa7d61179e3d68402e9f9aca0a60f9053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFFBH ()</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### hasFFBL() {#a8ff0023a5060d98bbd31476beb658c50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFFBL ()</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### hasFlat() {#a00e78eae9b647e527c50749797367173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlat ()</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aafd52d574f92cc47671a38d95bca9988">llvm::AMDGPUSubtarget::SOUTHERN_ISLANDS</a>.</p>


<p>Referenced by <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### hasFlatAddressSpace() {#a90fc707270386fb970207745d6675805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatAddressSpace ()</td>
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



<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#af98d3431546e921d906556ab6b9d6cb5">FlatAddressSpace</a>.</p>


<p>Referenced by <a href="#a0b81f06d449a6dc8b3d664b5edded261">getReservedNumSGPRs</a> and <a href="#a4730d588468e16e01a6a2c475043c511">hasFlatScrRegister</a>.</p>

</div>
</div>

### hasFlatAtomicFaddF32Inst() {#a4bf85a994788b693f38928fdf8b7a48f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatAtomicFaddF32Inst ()</td>
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



<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a27da80ce11ad15a11fc4c41a33666a16">HasFlatAtomicFaddF32Inst</a>.</p>

</div>
</div>

### hasFlatBufferGlobalAtomicFaddF64Inst() {#ab8a8ecf7c823363079b7b9e403908d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatBufferGlobalAtomicFaddF64Inst ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the target has flat, global, and buffer atomic fadd for double.</p></dd>
</dl>


<p>Definition at line 899 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#afff59c5a54f5886e497f9797030c67b7">HasFlatBufferGlobalAtomicFaddF64Inst</a>.</p>

</div>
</div>

### hasFlatGlobalInsts() {#a85d032a1f1dc4a077f3644b16a6a0243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatGlobalInsts ()</td>
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



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a4c4346f1426fe53905715ca0f0d2fd0e">FlatGlobalInsts</a>.</p>

</div>
</div>

### hasFlatInstOffsets() {#a1b42b67d0df8ad1a351bbdc503c115a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatInstOffsets ()</td>
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



<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a8caa14af5acb006632cfd31a4c28e78c">FlatInstOffsets</a>.</p>

</div>
</div>

### hasFlatLgkmVMemCountInOrder() {#a16018a60d1570d987fea800451277bc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatLgkmVMemCountInOrder ()</td>
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



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### hasFlatScratchInsts() {#a28caebd4d797207b1f5989ef56df5683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatScratchInsts ()</td>
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



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ad737ff5de5197f759fd10988312481b8">FlatScratchInsts</a>.</p>


<p>Referenced by <a href="#a3e8da3fb902e2e5c0443907cab82ba01">enableFlatScratch</a> and <a href="#ad626093afec474495db46935e79c515b">hasFlatScratchSTMode</a>.</p>

</div>
</div>

### hasFlatScratchSTMode() {#ad626093afec474495db46935e79c515b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatScratchSTMode ()</td>
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



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#a28caebd4d797207b1f5989ef56df5683">hasFlatScratchInsts</a>, <a href="#a3b70c1201c0b1688d7284174c11a5b77">hasGFX10_3Insts</a> and <a href="#a80ef035f066bb00307e5cccb694e20e2">hasGFX940Insts</a>.</p>

</div>
</div>

### hasFlatScratchSVSMode() {#aa828632df398b007b1107ea5a5fbfe23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatScratchSVSMode ()</td>
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



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#a23594b888d739de018ed2a227d711ced">GFX11Insts</a> and <a href="#a167f1c9d969e90ea41a3dd52a37b32e6">GFX940Insts</a>.</p>

</div>
</div>

### hasFlatScratchSVSSwizzleBug() {#ab85fb688a662d3962521663406317d17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatScratchSVSSwizzleBug ()</td>
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



<p>Definition at line 1293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>.</p>

</div>
</div>

### hasFlatScrRegister() {#a4730d588468e16e01a6a2c475043c511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatScrRegister ()</td>
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



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a90fc707270386fb970207745d6675805">hasFlatAddressSpace</a>.</p>

</div>
</div>

### hasFlatSegmentOffsetBug() {#a7c210fe3c1ded331101415c059606e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFlatSegmentOffsetBug ()</td>
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



<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a29628d7d35aef1950da107293e9f68f2">HasFlatSegmentOffsetBug</a>.</p>

</div>
</div>

### hasFMA() {#aa3d326302b1b07150d09e0745a3e9bcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFMA ()</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aa3ad8d1429472400a745a288263f1fa6">FMA</a>.</p>

</div>
</div>

### hasFmaakFmamkF32Insts() {#a53cf2f32851d6c5f192a752f853c581b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFmaakFmamkF32Insts ()</td>
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



<p>Definition at line 1075 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a> and <a href="#a80ef035f066bb00307e5cccb694e20e2">hasGFX940Insts</a>.</p>

</div>
</div>

### hasFmacF64Inst() {#a59ab2534372c0adc46a34c429cedbc05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFmacF64Inst ()</td>
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



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a6a0aae30a368c4c91584185cc3ad6373">HasFmacF64Inst</a>.</p>

</div>
</div>

### hasFmaMixInsts() {#addfe5ff70771ccdda4ae3c6e282a5441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFmaMixInsts ()</td>
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



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a8050bb1b1445e617520f2a5bfad62e3b">HasFmaMixInsts</a>.</p>

</div>
</div>

### hasForceStoreSC0SC1() {#acf635e2bc94a0c4f29a493833eb548c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasForceStoreSC0SC1 ()</td>
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



<p>Definition at line 1267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a3b30160b1757f25c85752a1fe26e157e">HasForceStoreSC0SC1</a>.</p>

</div>
</div>

### hasFP64() {#ae408833a27e3db45bd5d4b790cd1ba9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFP64 ()</td>
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



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ad989699f72d64cd5c12d52856532880a">FP64</a>.</p>


<p>Referenced by <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### hasFP8ConversionInsts() {#a17d227c50874535df8d88c8256939a82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFP8ConversionInsts ()</td>
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



<p>Definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a952f6917a737a034709d9c849dfb0d9d">HasFP8ConversionInsts</a>.</p>

</div>
</div>

### hasFP8Insts() {#a4c4e8213a552980916f041896c5989be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFP8Insts ()</td>
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



<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a9207fa4cbccf18aa0b9be67d2a54d744">HasFP8Insts</a>.</p>

</div>
</div>

### hasFPAtomicToDenormModeHazard() {#a1b16e18ec95818598ce11d30f59fec2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFPAtomicToDenormModeHazard ()</td>
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



<p>Definition at line 1249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>.</p>

</div>
</div>

### hasFractBug() {#aec23a7dbd85b61497ca147984ce54cbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFractBug ()</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aafd52d574f92cc47671a38d95bca9988">llvm::AMDGPUSubtarget::SOUTHERN_ISLANDS</a>.</p>

</div>
</div>

### hasFullRate64Ops() {#a8263d2c3a266941b3669828ecf1db53e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasFullRate64Ops ()</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a621ba6bafe12da8a8af4288ef2c1040e">FullRate64Ops</a>.</p>

</div>
</div>

### hasG16() {#aaac87839eb0077c44120678bcab56bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasG16 ()</td>
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



<p>Definition at line 1093 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a0d0570029543761ca74c7df68fc59744">HasG16</a>.</p>

</div>
</div>

### hasGDS() {#aedfc0056986632c8d0462319b661d692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGDS ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if Global Data Share is supported.</p></dd>
</dl>


<p>Definition at line 1398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aa07db84b412bc41a23e2c1fff3f7efd1">HasGDS</a>.</p>

</div>
</div>

### hasGetPCZeroExtension() {#a4800f21d7866329eeb7a6bbcef9cb9e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGetPCZeroExtension ()</td>
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



<p>Definition at line 1446 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aee8f87ccf5572392018ca06a2080989f">GFX12Insts</a>.</p>

</div>
</div>

### hasGetWaveIdInst() {#a1ec9fcfe37ebfe9de9723d9909525634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGetWaveIdInst ()</td>
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



<p>Definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a4258d4c50ebe4adf47d1556d82fef254">HasGetWaveIdInst</a>.</p>

</div>
</div>

### hasGFX10\_3Insts() {#a3b70c1201c0b1688d7284174c11a5b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGFX10_3Insts ()</td>
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



<p>Definition at line 1127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a41a56363d4e58147e7df5adb4872c3ba">GFX10_3Insts</a>.</p>


<p>Referenced by <a href="#ad626093afec474495db46935e79c515b">hasFlatScratchSTMode</a>.</p>

</div>
</div>

### hasGFX10\_AEncoding() {#a7bf65bf4917efcfd2afded9f48afcfee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGFX10_AEncoding ()</td>
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



<p>Definition at line 1119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a7c380b42afd78ccb7c178bc27ad0fb27">GFX10_AEncoding</a>.</p>

</div>
</div>

### hasGFX10\_BEncoding() {#acd5cffaeaa2cffe0f336c6e9aca140b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGFX10_BEncoding ()</td>
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



<p>Definition at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a25a9bffea45bd561499b442b0544ccb8">GFX10_BEncoding</a>.</p>

</div>
</div>

### hasGFX90AInsts() {#a1fc0ea9be83e3d4cb2aeb2d7b2363e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGFX90AInsts ()</td>
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



<p>Definition at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aaae1852e68f40bf33e7f6f49c1fd1cff">GFX90AInsts</a>.</p>


<p>Referenced by <a href="#a293668f13d1c676db1d1b3be25b7115d">getBaseMaxNumVGPRs</a>, <a href="#a14fa006badbf638f83ae7fad1c6f2c23">hasLdsAtomicAddF64</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### hasGFX940Insts() {#a80ef035f066bb00307e5cccb694e20e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGFX940Insts ()</td>
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



<p>Definition at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a167f1c9d969e90ea41a3dd52a37b32e6">GFX940Insts</a>.</p>


<p>Referenced by <a href="#a5ecc5f8b91d701d17ec10a6b57686dcc">hasExportInsts</a>, <a href="#ad626093afec474495db46935e79c515b">hasFlatScratchSTMode</a> and <a href="#a53cf2f32851d6c5f192a752f853c581b">hasFmaakFmamkF32Insts</a>.</p>

</div>
</div>

### hasGFX950Insts() {#a6ba0e36ee4fa0e5829ab468e0ad18627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGFX950Insts ()</td>
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



<p>Definition at line 1306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ac164adfdd62c69dbd820c417d2c24de0">GFX950Insts</a>.</p>


<p>Referenced by <a href="#a27fceb81b4828d4bafbd5a97c71ef510">hasLDSLoadB96_B128</a>.</p>

</div>
</div>

### hasGlobalAddTidInsts() {#a451d3f382bdad515e0cb3e9f39de86aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGlobalAddTidInsts ()</td>
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



<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a25a9bffea45bd561499b442b0544ccb8">GFX10_BEncoding</a>.</p>

</div>
</div>

### hasGWS() {#ac7a4a974fce95bb3f78e370f63d25a56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGWS ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if Global Wave Sync is supported.</p></dd>
</dl>


<p>Definition at line 1401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a3f7e4c82242d7fba786da95ea84f39dc">HasGWS</a>.</p>

</div>
</div>

### hasGWSAutoReplay() {#aff8a8c0203088e3ec49d090aaaedca78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGWSAutoReplay ()</td>
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



<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### hasGWSSemaReleaseAll() {#ad6b3273818698235f76b04db7793dd12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasGWSSemaReleaseAll ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>if target has ds_gws_sema_release_all instruction.</p></dd>
</dl>


<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aaef4f045c922c0ae9c8a500e0e2c29d4">CIInsts</a>.</p>

</div>
</div>

### hasHalfRate64Ops() {#aab504c30d42758271e85ec4104b8ffa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasHalfRate64Ops ()</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a948eae74cbc251ff4e8984a04ecbcdc6">HalfRate64Ops</a>.</p>

</div>
</div>

### hasHardClauses() {#a567e40fa5e04cc7a032e60e66044f470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasHardClauses ()</td>
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



<p>Definition at line 1245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ab8297b266634f159ee9c659cb5467b38">MaxHardClauseLength</a>.</p>

</div>
</div>

### hasHWFP64() {#a2ba650a151ac898c90b1940ea3e951ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasHWFP64 ()</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ad989699f72d64cd5c12d52856532880a">FP64</a>.</p>

</div>
</div>

### hasIEEEMinMax() {#add9f234619d0fb3d8254f46b9f3dd001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasIEEEMinMax ()</td>
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



<p>Definition at line 1432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>


<p>Referenced by <a href="#ad21fbf9dd106c4b149954abd1ddb0c85">hasIEEEMinMax3</a>.</p>

</div>
</div>

### hasIEEEMinMax3() {#ad21fbf9dd106c4b149954abd1ddb0c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasIEEEMinMax3 ()</td>
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



<p>Definition at line 1435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#add9f234619d0fb3d8254f46b9f3dd001">hasIEEEMinMax</a>.</p>

</div>
</div>

### hasIEEEMode() {#ab906a8b680c13e481cf016a0c111173a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasIEEEMode ()</td>
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



<p>Definition at line 1429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasImageGather4D16Bug() {#aa38a233aad5f337533309b4f04a4effd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasImageGather4D16Bug ()</td>
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



<p>Definition at line 1101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a9c980d76fd4aa2aedacdddcd3e275fc9">HasImageGather4D16Bug</a>.</p>

</div>
</div>

### hasImageInsts() {#aa2caffdb8654b132f6f434c0fe9e1112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasImageInsts ()</td>
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



<p>Definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a56d26cde5f690bf9459fc2f76865d030">HasImageInsts</a>.</p>

</div>
</div>

### hasImageStoreD16Bug() {#a0e70db1e8483e587c41a315dfad8c88a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasImageStoreD16Bug ()</td>
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



<p>Definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#abc3af3f5d368b630f23f4dffdd0b46fd">HasImageStoreD16Bug</a>.</p>

</div>
</div>

### hasInstFwdPrefetchBug() {#a95c817fefbb5c1444ecadc1a790b1273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasInstFwdPrefetchBug ()</td>
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



<p>Definition at line 1205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#af46635e054a2a083f592723ddb861aab">HasInstFwdPrefetchBug</a>.</p>

</div>
</div>

### hasInstPrefetch() {#a5bdd904c6ad30cc78129f391b066c3d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasInstPrefetch ()</td>
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



<p>Definition at line 958 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>.</p>

</div>
</div>

### hasIntClamp() {#a7af63ea0547908098ee65377e979d3ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasIntClamp ()</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ae7bb96baf904d1d3c70e476a6cb4e488">HasIntClamp</a>.</p>

</div>
</div>

### hasKernargPreload() {#a4c1fca26ad6a387a03e4649095b7cdc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasKernargPreload ()</td>
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



<p>Definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a3ea5e2eef6d396268f0b354c3c5ead45">KernargPreload</a>.</p>

</div>
</div>

### hasLdsAtomicAddF64() {#a14fa006badbf638f83ae7fad1c6f2c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasLdsAtomicAddF64 ()</td>
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



<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a1fc0ea9be83e3d4cb2aeb2d7b2363e73">hasGFX90AInsts</a>.</p>

</div>
</div>

### hasLdsBranchVmemWARHazard() {#a1e3aaf52cbaf44191f00656b774cdede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasLdsBranchVmemWARHazard ()</td>
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



<p>Definition at line 1213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a03acf80e335385e4af1e41537e843343">HasLdsBranchVmemWARHazard</a>.</p>

</div>
</div>

### hasLdsDirect() {#aff5ba6e6e7a7b0ce7126d565ddd5c5cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasLdsDirect ()</td>
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



<p>Definition at line 1255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>.</p>

</div>
</div>

### hasLDSFPAtomicAddF32() {#abd18ad36f7c9ff894f439f5dd79f05de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasLDSFPAtomicAddF32 ()</td>
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



<p>Definition at line 1035 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a953743f90862340f08cb9cd50174824b">GFX8Insts</a>.</p>

</div>
</div>

### hasLDSFPAtomicAddF64() {#a85c22bc10e6e36bbe63c69bfb9638e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasLDSFPAtomicAddF64 ()</td>
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



<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aaae1852e68f40bf33e7f6f49c1fd1cff">GFX90AInsts</a>.</p>

</div>
</div>

### hasLDSLoadB96\_B128() {#a27fceb81b4828d4bafbd5a97c71ef510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasLDSLoadB96_B128 ()</td>
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

<p>Returns true if the target supports global_load_lds_dwordx3/global_load_lds_dwordx4 or buffer_load_dwordx3/buffer_load_dwordx4 with the lds bit.</p>

<p>Definition at line 1311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a6ba0e36ee4fa0e5829ab468e0ad18627">hasGFX950Insts</a>.</p>

</div>
</div>

### hasLDSMisalignedBug() {#a58b73e7766fb13e9033b8cc011e5d3ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasLDSMisalignedBug ()</td>
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



<p>Definition at line 1201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#a70a9a419e5ce5ddf54374dc797f765f6">EnableCuMode</a> and <a href="#a1980c0b9e254aaf640a1b11b37a077c9">LDSMisalignedBug</a>.</p>

</div>
</div>

### hasLdsWaitVMSRC() {#a5255251aa57df7852a7be73345a627ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasLdsWaitVMSRC ()</td>
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



<p>Definition at line 1257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasLegacyGeometry() {#a60ef33c23289f161804eab76b43b6683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasLegacyGeometry ()</td>
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



<p>Definition at line 1410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>.</p>

</div>
</div>

### hasLshlAddB64() {#a815b2f5ace41f35b5ca3534086af69af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasLshlAddB64 ()</td>
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



<p>Definition at line 1135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a167f1c9d969e90ea41a3dd52a37b32e6">GFX940Insts</a>.</p>

</div>
</div>

### hasMad64\_32() {#a553d27729038fcbd05ec618b71feaf3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMad64_32 ()</td>
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



<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a5a040cb5d61ebf76561fcb74c4a77970">llvm::AMDGPUSubtarget::SEA_ISLANDS</a>.</p>

</div>
</div>

### hasMadF16() {#a3f464e58eb8545a1261f5ef4be85ce95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNSubtarget::hasMadF16 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#acaca0c9ffff0d1cba0462a1daccf5f12">llvm::SITargetLowering::SITargetLowering</a>.</p>

</div>
</div>

### hasMADIntraFwdBug() {#a33fbbd04a4a2d81c229f0e613de73905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMADIntraFwdBug ()</td>
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



<p>Definition at line 1103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a272b4543c35465b19829ba03c72a4730">HasMADIntraFwdBug</a>.</p>

</div>
</div>

### hasMAIInsts() {#a278004c824cd46c7504e68ec7c5f2d57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMAIInsts ()</td>
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



<p>Definition at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a2f1176e8f488b0bc45c6478cc494e8ba">HasMAIInsts</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a22f77187b94b2e4b729590a1f9a6ba51">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getHSAKernelProps</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### hasMed3\_16() {#a977f7068e1dd00bcd2deab2075c5eac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMed3_16 ()</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### hasMemoryAtomicFaddF32DenormalSupport() {#a0087efb42b61a14ba8975ab581ed5f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMemoryAtomicFaddF32DenormalSupport ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the target's flat, global, and buffer atomic fadd for float supports denormal handling.</p></dd>
</dl>


<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aeecfaf3b2b9359e37af4fe07166cb226">HasMemoryAtomicFaddF32DenormalSupport</a>.</p>

</div>
</div>

### hasMergedShaders() {#a0936b3343117af1096d10094f4cc47f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMergedShaders ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the machine has merged shaders in which s0-s7 are reserved by the hardware and user SGPRs start at s8</p></dd>
</dl>


<p>Definition at line 1405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### hasMFMAInlineLiteralBug() {#a2daa95e19ef6f3a5d3be7f175d5bde59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMFMAInlineLiteralBug ()</td>
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



<p>Definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ae792f1ad039fd0a51607d85a03feca22">HasMFMAInlineLiteralBug</a>.</p>

</div>
</div>

### hasMIMG\_R128() {#ab10ebfbc9a9e224662e1cc4fa218d5d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMIMG_R128 ()</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a7ca7cf17cde165669ca2d983800d3701">MIMG_R128</a>.</p>

</div>
</div>

### hasMin3Max3\_16() {#a7af1360602eb146eabea6d2dce67dd17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMin3Max3_16 ()</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a35ed5c57b010d0e935d2eaeea257bfd5">supportsMin3Max3</a>.</p>

</div>
</div>

### hasMinimum3Maximum3F16() {#a663d34243037a886d4932750a3cd40d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMinimum3Maximum3F16 ()</td>
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



<p>Definition at line 1348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a676e72a69c1f0f7a4dc54a9b99e05d00">HasMinimum3Maximum3F16</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a35ed5c57b010d0e935d2eaeea257bfd5">supportsMin3Max3</a>.</p>

</div>
</div>

### hasMinimum3Maximum3F32() {#a017de56f30979f32ad941844f3e6d66f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMinimum3Maximum3F32 ()</td>
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



<p>Definition at line 1344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a551988d5dffbfba8cd48d910b7cc9b14">HasMinimum3Maximum3F32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a35ed5c57b010d0e935d2eaeea257bfd5">supportsMin3Max3</a>.</p>

</div>
</div>

### hasMinimum3Maximum3PKF16() {#a57fd5bacadbf867edd08ea6551ef5df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMinimum3Maximum3PKF16 ()</td>
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



<p>Definition at line 1352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aac44b0653c95e1c63358778a56937d2d">HasMinimum3Maximum3PKF16</a>.</p>

</div>
</div>

### hasMovB64() {#a92e0b317959309846ea919ad2cf08ffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMovB64 ()</td>
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



<p>Definition at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a167f1c9d969e90ea41a3dd52a37b32e6">GFX940Insts</a>.</p>

</div>
</div>

### hasMovrel() {#a99ce92019b9024b92d62341296eab008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMovrel ()</td>
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



<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a76168e6f26b0f7cada393b6baaf6d7aa">HasMovrel</a>.</p>


<p>Referenced by <a href="#a021be99fec633060e46fd3c482c1c3bc">useVGPRIndexMode</a>.</p>

</div>
</div>

### hasMSAALoadDstSelBug() {#a52d1955bc658f8878e3746993d2e0530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMSAALoadDstSelBug ()</td>
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



<p>Definition at line 1105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aaaf90f97cd99f018d4886dad8d49560c">HasMSAALoadDstSelBug</a>.</p>

</div>
</div>

### hasMultiDwordFlatScratchAddressing() {#a297574b1f876682e29ea6ab099165998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasMultiDwordFlatScratchAddressing ()</td>
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



<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### hasNegativeScratchOffsetBug() {#a31e93bb82e5ea95995efb52febbe0d8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasNegativeScratchOffsetBug ()</td>
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



<p>Definition at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a2e15f45c8391c4606bf56f4cfc3be19d">NegativeScratchOffsetBug</a>.</p>

</div>
</div>

### hasNegativeUnalignedScratchOffsetBug() {#aa727d0bfbc501329be7c48c86d8bdb8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasNegativeUnalignedScratchOffsetBug ()</td>
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



<p>Definition at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a56675b4857e4f3f36f3aacbfc1e8f188">NegativeUnalignedScratchOffsetBug</a>.</p>

</div>
</div>

### hasNoDataDepHazard() {#a758cbecbfce67cc0a42af981d6f1755b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasNoDataDepHazard ()</td>
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



<p>Definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a6db4fbc67c6b520e52f966ff3bd992e8">HasNoDataDepHazard</a>.</p>

</div>
</div>

### hasNoF16PseudoScalarTransInlineConstants() {#ab8f2856d03fa63b54d82cb19936082c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasNoF16PseudoScalarTransInlineConstants ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if inline constants are not supported for F16 pseudo scalar transcendentals.</p></dd>
</dl>


<p>Definition at line 1331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasNonNSAEncoding() {#a0f46612d8f5ca0825291c14c220c82ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasNonNSAEncoding ()</td>
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



<p>Definition at line 1111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasNoSdstCMPX() {#ad0569952d064262bc16c3052746013fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasNoSdstCMPX ()</td>
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



<p>Definition at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a8fb3a41719c2219a977c3aa110a29cc8">HasNoSdstCMPX</a>.</p>

</div>
</div>

### hasNSAClauseBug() {#a3633028daa01022eaf44181a9f5028a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasNSAClauseBug ()</td>
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



<p>Definition at line 1243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a4ae3a84968e835cfb541a62de2007476">HasNSAClauseBug</a>.</p>

</div>
</div>

### hasNSAEncoding() {#a90329091d5d23e8a4bac1a2803d252b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasNSAEncoding ()</td>
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



<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ae2847a61e28335ec96f3aba0aa582e23">HasNSAEncoding</a>.</p>

</div>
</div>

### hasNSAtoVMEMBug() {#aadb9bb3c036cfcddf3fc2634071fa163}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasNSAtoVMEMBug ()</td>
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



<p>Definition at line 1239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#abfaf0dbd880bc35fd34db18c5166370c">HasNSAtoVMEMBug</a>.</p>

</div>
</div>

### hasNullExportTarget() {#a9a6c28d83ad975e7eb5384641191d9bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasNullExportTarget ()</td>
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

<p>Return true if the target's EXP instruction supports the NULL export target.</p>

<p>Definition at line 1287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a23594b888d739de018ed2a227d711ced">GFX11Insts</a>.</p>

</div>
</div>

### hasOffset3fBug() {#a42ffba7488c6f98d42703852d9d83361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasOffset3fBug ()</td>
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



<p>Definition at line 1095 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a8660a471fd90d7d6e3abbb00a325bf5a">HasOffset3fBug</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#af49d69e68344d6292702edca157e7eed">llvm::AMDGPUAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### hasOnlyRevVALUShifts() {#a0e686c7c8f5b335f3edce1e6711ec168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasOnlyRevVALUShifts ()</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>

</div>
</div>

### hasPackedFP32Ops() {#a7f1b4a610bfabed1dac80708d399d552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPackedFP32Ops ()</td>
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



<p>Definition at line 1066 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aab5049a486074311dc22e29c08a0c60c">HasPackedFP32Ops</a>.</p>

</div>
</div>

### hasPackedTID() {#ae133c0c692754b7a2e431eae75db8733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPackedTID ()</td>
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



<p>Definition at line 1298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#af9b5852cc8a419d0d0e5eed8ac1b6d1e">HasPackedTID</a>.</p>

</div>
</div>

### hasPartialNSAEncoding() {#af44e06d801c094cd657e62994746d62a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPartialNSAEncoding ()</td>
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



<p>Definition at line 1113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a58c2025484c09d2f354f1f6b4b4a461e">HasPartialNSAEncoding</a>.</p>

</div>
</div>

### hasPermlane16Swap() {#aacf87c06d72fdf7a23f5231ce3834fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPermlane16Swap ()</td>
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



<p>Definition at line 1340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a53830d2988831622a620d9df123c93ea">HasPermlane16Swap</a>.</p>

</div>
</div>

### hasPermlane32Swap() {#a03f2b3a5ff8e0b8454a6d0c46cb63c98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPermlane32Swap ()</td>
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



<p>Definition at line 1341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#af58a534c85df77c9d8b03d0ce88d622d">HasPermlane32Swap</a>.</p>

</div>
</div>

### hasPermLane64() {#a481ac8ced7100d359c1619b2520db577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPermLane64 ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the subtarget has the v_permlane64_b32 instruction.</p></dd>
</dl>


<p>Definition at line 1042 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>.</p>

</div>
</div>

### hasPermLaneX16() {#ab832422d655be69a3e9b05955e4a58c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPermLaneX16 ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the subtarget has the v_permlanex16_b32 instruction.</p></dd>
</dl>


<p>Definition at line 1039 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>.</p>

</div>
</div>

### hasPkFmacF16Inst() {#a06c09c7d429aaae637f401b51e855b5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPkFmacF16Inst ()</td>
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



<p>Definition at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a2d7cdc43a6afa870465964d752b5072b">HasPkFmacF16Inst</a>.</p>

</div>
</div>

### hasPkMovB32() {#a3afde3a0eda49172cc0f673da8ab75ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPkMovB32 ()</td>
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



<p>Definition at line 1071 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aaae1852e68f40bf33e7f6f49c1fd1cff">GFX90AInsts</a>.</p>

</div>
</div>

### hasPrefetch() {#a005c3432e3eef07f10653bf3dffccad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPrefetch ()</td>
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



<p>Definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aee8f87ccf5572392018ca06a2080989f">GFX12Insts</a>.</p>

</div>
</div>

### hasPrivEnabledTrap2NopBug() {#a2cc4098b4aa7563be99e6d57965966f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPrivEnabledTrap2NopBug ()</td>
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



<p>Definition at line 1107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a451a241ad87234390e77346e090cf035">HasPrivEnabledTrap2NopBug</a>.</p>

</div>
</div>

### hasPrngInst() {#a438e29c27b814b7bcf58616cc57862b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPrngInst ()</td>
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



<p>Definition at line 1361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a9bff28a332d5b309966a353003a80e2a">HasPrngInst</a>.</p>

</div>
</div>

### hasPseudoScalarTrans() {#ac695674c0b51da8114892ef06e224ef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasPseudoScalarTrans ()</td>
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



<p>Definition at line 1317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a887b1d13e204a49b28ba68b995176cab">HasPseudoScalarTrans</a>.</p>

</div>
</div>

### hasR128A16() {#a426587719be9d9751e8c667734f0cc7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasR128A16 ()</td>
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



<p>Definition at line 1087 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a63b7cd3536956300a3e6246c7f876ae7">HasR128A16</a>.</p>

</div>
</div>

### hasReadM0LdsDirectHazard() {#ac8ee05cd6b4e404e5dc44eed03a2dd09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasReadM0LdsDirectHazard ()</td>
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



<p>Definition at line 1185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### hasReadM0LdsDmaHazard() {#a88f43aaffee9d7ce03f6944a84f935c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasReadM0LdsDmaHazard ()</td>
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



<p>Definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### hasReadM0MovRelInterpHazard() {#a4d725ba548e7482013418fef4d2917b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasReadM0MovRelInterpHazard ()</td>
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



<p>Definition at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### hasReadM0SendMsgHazard() {#ac1d0d1c87789d65fa35257547aaa7435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasReadM0SendMsgHazard ()</td>
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



<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>

</div>
</div>

### hasReadVCCZBug() {#ada3be3eae9decd8077b5cd12f6586734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasReadVCCZBug ()</td>
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

<p>Extra wait hazard is needed in some cases before s_cbranch_vccnz/s_cbranch_vccz.</p>

<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a5a040cb5d61ebf76561fcb74c4a77970">llvm::AMDGPUSubtarget::SEA_ISLANDS</a>.</p>

</div>
</div>

### hasRequiredExportPriority() {#a4f7250d7950b6fb7e11b676b0d6a84ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasRequiredExportPriority ()</td>
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



<p>Definition at line 1321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aa3c8ecafa08eb2849d23f7fe63a901e1">HasRequiredExportPriority</a>.</p>

</div>
</div>

### hasRestrictedSOffset() {#a7a64fa91bbb4ff5f0417e16ad408e0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasRestrictedSOffset ()</td>
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



<p>Definition at line 1319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#adbf185c7be65b7b2a4df9fc24ac50e04">HasRestrictedSOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a46c5311c4dcb42b840fb1a343e51365b">selectSOffset</a>.</p>

</div>
</div>

### hasRFEHazards() {#ad46aa9ecc42e11cb442f7ed98b57acd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasRFEHazards ()</td>
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



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>

</div>
</div>

### hasRrWGMode() {#a0bf7687022b74bf81427ae61cc828c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasRrWGMode ()</td>
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



<p>Definition at line 1438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasSALUFloatInsts() {#aea382e48834aaf8b5f0e334622faa197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSALUFloatInsts ()</td>
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



<p>Definition at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a1548ff560030d89242f6bba6fc3f43e5">HasSALUFloatInsts</a>.</p>

</div>
</div>

### hasScalarAddSub64() {#ad1d2c1108654a77846036ac453ea20af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasScalarAddSub64 ()</td>
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



<p>Definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasScalarAtomics() {#a634ca68c4b030c1871ab805adec13d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasScalarAtomics ()</td>
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



<p>Definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a820f935a25ced4c881e7ca3b60d775f4">HasScalarAtomics</a>.</p>

</div>
</div>

### hasScalarCompareEq64() {#a0c71068f31a85453c97cfb17a44746b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasScalarCompareEq64 ()</td>
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



<p>Definition at line 1021 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>

</div>
</div>

### hasScalarDwordx3Loads() {#ab952ba0f11fe329b25af21199f557611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasScalarDwordx3Loads ()</td>
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



<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a18974200e120861ba26d24805f87bce7">HasScalarDwordx3Loads</a>.</p>

</div>
</div>

### hasScalarFlatScratchInsts() {#a70afc9ab29667211c70055c992d1c797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasScalarFlatScratchInsts ()</td>
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



<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ae4849ecfc6c6ef25d717ef19e6e40c2f">ScalarFlatScratchInsts</a>.</p>

</div>
</div>

### hasScalarMulHiInsts() {#ac4dd4cfc2dbcd57221490dfc8b265592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasScalarMulHiInsts ()</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a443df8396a86d96634419086278c7452">GFX9Insts</a>.</p>

</div>
</div>

### hasScalarPackInsts() {#a8fbcbd9c9b04e70f819b814f6a02a669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasScalarPackInsts ()</td>
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



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a443df8396a86d96634419086278c7452">GFX9Insts</a>.</p>

</div>
</div>

### hasScalarSMulU64() {#a898e8b0b4ad260533cde26a99ae409a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasScalarSMulU64 ()</td>
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



<p>Definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasScalarStores() {#a83477fe97fe7b3e570d433e24f71c371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasScalarStores ()</td>
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



<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a2438b345b76fa20009799525ecf82a16">HasScalarStores</a>.</p>

</div>
</div>

### hasScalarSubwordLoads() {#a3cb30b207966130ab1aa6998aaeadf07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasScalarSubwordLoads ()</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasSCmpK() {#ac5c238e9ab9ed01ce6a652a90c57c570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSCmpK ()</td>
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



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasSDWAMac() {#a175f25a33bfc2c593cf6eccc3a2bae67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSDWAMac ()</td>
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



<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#acffe84152bfba8302521f0f8c77671e8">HasSDWAMac</a>.</p>

</div>
</div>

### hasSDWAOmod() {#a0330bc04e02e5f966bb34b94faee3ea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSDWAOmod ()</td>
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



<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a371756f715ae24e7c7d6ee87bfb6d9bb">HasSDWAOmod</a>.</p>

</div>
</div>

### hasSDWAOutModsVOPC() {#a67eda8a7f0b4516f8f08d82651207c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSDWAOutModsVOPC ()</td>
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



<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a7076d6c3ca7fb96840d61e52a0f0400b">HasSDWAOutModsVOPC</a>.</p>

</div>
</div>

### hasSDWAScalar() {#a0af7bcad0087b2e7738d1636e5e4793e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSDWAScalar ()</td>
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



<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a1cf3065241a25e6b9f9f1d2477e24ec7">HasSDWAScalar</a>.</p>

</div>
</div>

### hasSDWASdst() {#a8ef1770dca2e75c8a049d7441802932f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSDWASdst ()</td>
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



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ac714f4a5d78945bf0268b7e166781db9">HasSDWASdst</a>.</p>

</div>
</div>

### hasSGPRInitBug() {#a463d4dd9c6577a21b6edd9879d013113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSGPRInitBug ()</td>
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



<p>Definition at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ad88ed5e21bdfe4710afa3fdd33981617">SGPRInitBug</a>.</p>


<p>Referenced by <a href="#a6b42f0492d630514943c345ab5eb4bc0">getBaseMaxNumSGPRs</a>.</p>

</div>
</div>

### hasShaderCyclesHiLoRegisters() {#a8d831a339bf2cd8bf0b9e5996a3ed123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasShaderCyclesHiLoRegisters ()</td>
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



<p>Definition at line 942 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a3929ea1c1954af1d4f5d2278638ba642">HasShaderCyclesHiLoRegisters</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### hasShaderCyclesRegister() {#ae733f0fbb575bf1a991461b1df4077a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasShaderCyclesRegister ()</td>
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



<p>Definition at line 938 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a8c5c784b6b9621f4cdab3cd273c9124e">HasShaderCyclesRegister</a>.</p>

</div>
</div>

### hasShift64HighRegBug() {#a1828e0b98df9d5cd61698e7585d8e7a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasShift64HighRegBug ()</td>
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



<p>Definition at line 1219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#aaae1852e68f40bf33e7f6f49c1fd1cff">GFX90AInsts</a> and <a href="#a167f1c9d969e90ea41a3dd52a37b32e6">GFX940Insts</a>.</p>

</div>
</div>

### hasSignedScratchOffsets() {#a4426383e6ed12fbb51b44261e675b122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSignedScratchOffsets ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if VADDR and SADDR fields in VSCRATCH can use negative values.</p></dd>
</dl>


<p>Definition at line 1442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasSMemRealTime() {#a9094c845e9359c8c1c873e14e1be18f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSMemRealTime ()</td>
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



<p>Definition at line 1007 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ae0d2cfb5028990ce762ad06fbebd0b4f">HasSMemRealTime</a>.</p>

</div>
</div>

### hasSMemTimeInst() {#a2eda17e3b44637b79a9aac0e47ab249f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSMemTimeInst ()</td>
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



<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a94f4e1e3ad1d7eee4e740ad2e3c17658">HasSMemTimeInst</a>.</p>

</div>
</div>

### hasSMEMtoVectorWriteHazard() {#a9e531910f7c7133e8696a4dea9ff873a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSMEMtoVectorWriteHazard ()</td>
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



<p>Definition at line 1197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a9d59aff4310d57b0806f1abbcd12021d">HasSMEMtoVectorWriteHazard</a>.</p>

</div>
</div>

### hasSMRDReadVALUDefHazard() {#ad35eeddb0b87d3542dcf6690a6fa655d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSMRDReadVALUDefHazard ()</td>
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

<p>A read of an SGPR by SMRD instruction requires 4 wait states when the SGPR was written by a VALU instruction.</p>

<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aafd52d574f92cc47671a38d95bca9988">llvm::AMDGPUSubtarget::SOUTHERN_ISLANDS</a>.</p>

</div>
</div>

### hasSPackHL() {#aa4097c8e7593fbd1a0b8cff5964fa5d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSPackHL ()</td>
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

<p>Return true if the target has the S_PACK_HL_B32_B16 instruction.</p>

<p>Definition at line 1279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a23594b888d739de018ed2a227d711ced">GFX11Insts</a>.</p>

</div>
</div>

### hasSplitBarriers() {#ad29bdf407acea38fceff17cfc4159e3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSplitBarriers ()</td>
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



<p>Definition at line 1416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasSwap() {#a0640303601c270bb5913e56281c6ff92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasSwap ()</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a443df8396a86d96634419086278c7452">GFX9Insts</a>.</p>

</div>
</div>

### hasTransForwardingHazard() {#a7fdc7771608a86b53935f4f6fc101c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasTransForwardingHazard ()</td>
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



<p>Definition at line 1225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a167f1c9d969e90ea41a3dd52a37b32e6">GFX940Insts</a>.</p>

</div>
</div>

### hasUnalignedAccessMode() {#ad8fdf957658ebd74fb9e95adfdb970a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasUnalignedAccessMode ()</td>
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



<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#abce08ae709e3e15c39e3d8c6dd911af0">UnalignedAccessMode</a>.</p>

</div>
</div>

### hasUnalignedBufferAccess() {#a40c81e55bbb2fb239f904617a259befb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasUnalignedBufferAccess ()</td>
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



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ae99450395d28349fc55c832de8510eda">UnalignedBufferAccess</a>.</p>

</div>
</div>

### hasUnalignedBufferAccessEnabled() {#aa0d885cd49a333e11b7e405ccfc85c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasUnalignedBufferAccessEnabled ()</td>
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



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#abce08ae709e3e15c39e3d8c6dd911af0">UnalignedAccessMode</a> and <a href="#ae99450395d28349fc55c832de8510eda">UnalignedBufferAccess</a>.</p>

</div>
</div>

### hasUnalignedDSAccess() {#a799cf5bdf244aef0f87065145a5f2c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasUnalignedDSAccess ()</td>
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



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a23393a7e958c2933deafa6bc181a0b0e">UnalignedDSAccess</a>.</p>

</div>
</div>

### hasUnalignedDSAccessEnabled() {#a2f352f203bb6d6cfd51c652e1c5132ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasUnalignedDSAccessEnabled ()</td>
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



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#abce08ae709e3e15c39e3d8c6dd911af0">UnalignedAccessMode</a> and <a href="#a23393a7e958c2933deafa6bc181a0b0e">UnalignedDSAccess</a>.</p>

</div>
</div>

### hasUnalignedScratchAccess() {#a64bb69b998fcff902312ba7d2eb7221c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasUnalignedScratchAccess ()</td>
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



<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a9b54a7dcd00a95feec9a76aebca85508">UnalignedScratchAccess</a>.</p>

</div>
</div>

### hasUnalignedScratchAccessEnabled() {#a998c1bf83ee1a55a120212a835e24c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasUnalignedScratchAccessEnabled ()</td>
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



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#abce08ae709e3e15c39e3d8c6dd911af0">UnalignedAccessMode</a> and <a href="#a9b54a7dcd00a95feec9a76aebca85508">UnalignedScratchAccess</a>.</p>

</div>
</div>

### hasUnpackedD16VMem() {#ad30b3c952ed576256171d49971ec9241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasUnpackedD16VMem ()</td>
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



<p>Definition at line 746 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aea0f6b19cef0ddc119a88ae60f5461d2">HasUnpackedD16VMem</a>.</p>

</div>
</div>

### hasUsableDivScaleConditionOutput() {#a0fa696e47a30e77762a75d6eb8fe1e34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasUsableDivScaleConditionOutput ()</td>
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

<p>Condition output from div_scale is usable.</p>

<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aafd52d574f92cc47671a38d95bca9988">llvm::AMDGPUSubtarget::SOUTHERN_ISLANDS</a>.</p>

</div>
</div>

### hasUsableDSOffset() {#a10f2e810ecf2f7e2bb9150ed2c5b622a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasUsableDSOffset ()</td>
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

<p>True if the offset field of DS instructions works as expected.</p>


<p>On <a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a>, the offset uses a 16-bit adder and does not always wrap properly.</p>


<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a5a040cb5d61ebf76561fcb74c4a77970">llvm::AMDGPUSubtarget::SEA_ISLANDS</a>.</p>

</div>
</div>

### hasUserSGPRInit16Bug() {#a5e54f855ac47719c335add94e8a6620a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasUserSGPRInit16Bug ()</td>
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



<p>Definition at line 1149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#a9f44cd05eefbb20a234a7e3b6369a7f8">isWave32</a> and <a href="#a21359df698891d2466c68d8abf6b4e4c">UserSGPRInit16Bug</a>.</p>

</div>
</div>

### hasVALUMaskWriteHazard() {#a3430658dbad45a4b93412d69c57f76a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVALUMaskWriteHazard ()</td>
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



<p>Definition at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>.</p>

</div>
</div>

### hasVALUPartialForwardingHazard() {#a73adb50a215b03b117f99dee7bd1f744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVALUPartialForwardingHazard ()</td>
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



<p>Definition at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>.</p>

</div>
</div>

### hasVALUReadSGPRHazard() {#a908e982d292aa3598537c78f6cd21c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVALUReadSGPRHazard ()</td>
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



<p>Definition at line 1273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>.</p>

</div>
</div>

### hasVALUTransUseHazard() {#ae6c6edd32a125d77f3c55139393019b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVALUTransUseHazard ()</td>
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



<p>Definition at line 1263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ade9ec63e4421f2fc8415717a86032e2c">HasVALUTransUseHazard</a>.</p>

</div>
</div>

### hasVcmpxExecWARHazard() {#a4b700ecd2d736b769de16280afbca49a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVcmpxExecWARHazard ()</td>
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



<p>Definition at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ae20ac61b7ca1deaf9f80e426552884a4">HasVcmpxExecWARHazard</a>.</p>

</div>
</div>

### hasVcmpxPermlaneHazard() {#a5de1edfcd129b2eb4325a889489ef633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVcmpxPermlaneHazard ()</td>
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



<p>Definition at line 1189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a7d6b53b3aebc2a64f37b6317279fe2a4">HasVcmpxPermlaneHazard</a>.</p>

</div>
</div>

### hasVDecCoExecHazard() {#ab96225992445aceb04e50ab1e06f068e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVDecCoExecHazard ()</td>
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



<p>Definition at line 1235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a167f1c9d969e90ea41a3dd52a37b32e6">GFX940Insts</a>.</p>

</div>
</div>

### hasVGPRIndexMode() {#a9fae1c20909b13d71c4923a90967f74b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVGPRIndexMode ()</td>
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



<p>Definition at line 1015 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a2ee2435b1a7b8c192632aeabdd325e7d">HasVGPRIndexMode</a>.</p>


<p>Referenced by <a href="#a021be99fec633060e46fd3c482c1c3bc">useVGPRIndexMode</a>.</p>

</div>
</div>

### hasVINTERPEncoding() {#a5eebf04eb63bf98ee3d5ec4702b65564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVINTERPEncoding ()</td>
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



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a23594b888d739de018ed2a227d711ced">GFX11Insts</a>.</p>

</div>
</div>

### hasVMEMReadSGPRVALUDefHazard() {#ad5417712235e489ce3f1473cbf2cbb9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVMEMReadSGPRVALUDefHazard ()</td>
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

<p>A read of an SGPR by a VMEM instruction requires 5 wait states when the SGPR was written by a VALU <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>

<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>

</div>
</div>

### hasVMEMtoScalarWriteHazard() {#aa45af2117c2e8ab325c59f997e818f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVMEMtoScalarWriteHazard ()</td>
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



<p>Definition at line 1193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ad79687b8f51d5052254be71401ac0e64">HasVMEMtoScalarWriteHazard</a>.</p>

</div>
</div>

### hasVmemWriteVgprInOrder() {#a263599c932efbe43f310b3924533ddad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVmemWriteVgprInOrder ()</td>
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



<p>Definition at line 1323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ae8d0d64b0d9f819c3246745e07e169c2">HasVmemWriteVgprInOrder</a>.</p>

</div>
</div>

### hasVOP3DPP() {#ab2fdc3a5b7196e1e439d054ccf973e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVOP3DPP ()</td>
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



<p>Definition at line 1253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>.</p>

</div>
</div>

### hasVOP3Literal() {#acfa61def62c3f39edaec6b28782f1992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVOP3Literal ()</td>
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



<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a9a0feafb29b5f1d0c3e1a237f464ed3a">HasVOP3Literal</a>.</p>

</div>
</div>

### hasVOPDInsts() {#acc70c2a79f18b7d4cb774ae93df8c548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVOPDInsts ()</td>
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



<p>Definition at line 1291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a6e2fb1b650236a6b1e2c80801da4285e">HasVOPDInsts</a>.</p>

</div>
</div>

### hasVscnt() {#a5458eb4f0d6001441653d15f37e101c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasVscnt ()</td>
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



<p>Definition at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a336cc2253badbe67950bd9fbb65fee57">HasVscnt</a>.</p>

</div>
</div>

### hasXF32Insts() {#a5bafa8f44616aca18624d36db7061d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasXF32Insts ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the target has instructions with xf32 format support.</p></dd>
</dl>


<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a1c8c4bbe976a53a477668131c2a965c2">HasXF32Insts</a>.</p>

</div>
</div>

### haveRoundOpsF64() {#abf0e7e914d5468cf242a422fb6a53070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::haveRoundOpsF64 ()</td>
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

<p>Have v_trunc_f64, v_ceil_f64, v_rndne_f64.</p>

<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aaef4f045c922c0ae9c8a500e0e2c29d4">CIInsts</a>.</p>

</div>
</div>

### initializeSubtargetDependencies() {#a716b165edca27031ffb7a20ea48e41e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNSubtarget &amp; GCNSubtarget::initializeSubtargetDependencies (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#ac8a473e77f57a3e0d70375277e45c6b7">llvm::AMDGPUSubtarget::AddressableLocalMemorySize</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">llvm::Triple::amdgcn</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0a0dddcf03f8f66f7c13558b3c81d845">llvm::Triple::AMDHSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ad5bfbea25d0de2655684928e7d7aa2f1">FlatForGlobal</a>, <a href="#acf1aa5ffc0b59dd205f5dc5142580771">GCNSubtarget</a>, <a href="#a72d895427056e0f3e9147974a95d11f8">Gen</a>, <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a726f6e520aaa1372f3572d993e1027b1">llvm::AMDGPUSubtarget::getWavefrontSizeLog2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>, <a href="#ad773dab02c945afb0bc889ebd67649c0">hasAddr64</a>, <a href="#a00e78eae9b647e527c50749797367173">hasFlat</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a0f40e9682781a1c311ff686ff29a573a">llvm::AMDGPUSubtarget::HasFminFmaxLegacy</a>, <a href="#ae408833a27e3db45bd5d4b790cd1ba9f">hasFP64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a752e3e8e514e13b70cf1d092b9746e89">llvm::AMDGPUSubtarget::HasSMulHi</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a44ffb5f3120d0b92ed40f4ee48ada81e">llvm::AMDGPUSubtarget::INVALID</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#acf005b2695c64eb57157215562463116">llvm::AMDGPUSubtarget::isAmdHsaOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a>, <a href="#a61d64bc81257fe4f2c899dc26a9c1660">LDSBankCount</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a943378cfc586b0e07ae5899d72c522db">llvm::AMDGPUSubtarget::LocalMemorySize</a>, <a href="#a18efbf5a73b167d005a9d1004816ab00">MaxPrivateElementSize</a>, <a href="#a1de3db2a7fc8d25fd5bb863ff90f0fd7">ParseSubtargetFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a5a040cb5d61ebf76561fcb74c4a77970">llvm::AMDGPUSubtarget::SEA_ISLANDS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aafd52d574f92cc47671a38d95bca9988">llvm::AMDGPUSubtarget::SOUTHERN_ISLANDS</a>, <a href="#afc6af409114a5e2da7bc8bedf9024cdc">TargetID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a1a16fa16d81293a0114e664d9f290114">llvm::AMDGPUSubtarget::WavefrontSizeLog2</a>.</p>


<p>Referenced by <a href="#acf1aa5ffc0b59dd205f5dc5142580771">GCNSubtarget</a>.</p>

</div>
</div>

### isCuModeEnabled() {#a62fb29606869fbd40b285c1cda4be12f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::isCuModeEnabled ()</td>
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



<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a70a9a419e5ce5ddf54374dc797f765f6">EnableCuMode</a>.</p>

</div>
</div>

### isMesaGfxShader() {#a5c9cce47bece7f780690af00f4924f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::isMesaGfxShader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a0972f69944edd9b5edb80bab11002a3c">llvm::AMDGPUSubtarget::isMesa3DOS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa813940c0ad88b3c4419f65af3e89e5e">llvm::AMDGPU::isShader</a>.</p>

</div>
</div>

### isPreciseMemoryEnabled() {#aec33da886213da6a50eb967bf8e4548b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::isPreciseMemoryEnabled ()</td>
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



<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a408fffe61eaab170cb661602f3471bc4">EnablePreciseMemory</a>.</p>

</div>
</div>

### isTgSplitEnabled() {#a4bec96c96006608cebef39898b836e81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::isTgSplitEnabled ()</td>
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



<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a90e036c3eafba2aa898f7895579c8f39">EnableTgSplit</a>.</p>

</div>
</div>

### isTrapHandlerEnabled() {#a83c4915f87ee24cf4648d46b2a2acf0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::isTrapHandlerEnabled ()</td>
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



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#addf1e5060c2765ecd0a10ff16a1d44e4">TrapHandler</a>.</p>

</div>
</div>

### isWave32() {#a9f44cd05eefbb20a234a7e3b6369a7f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::isWave32 ()</td>
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



<p>Definition at line 1584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#ae66cd705df2870244a05921f551ff131">llvm::AMDGPUSubtarget::getWavefrontSize</a>.</p>


<p>Referenced by <a href="#a5e54f855ac47719c335add94e8a6620a">hasUserSGPRInit16Bug</a> and <a href="#a1073d2ae057af7a11684100247250fb1">mirFileLoaded</a>.</p>

</div>
</div>

### isWave64() {#adb983b483404f765e1716c96f4a42580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::isWave64 ()</td>
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



<p>Definition at line 1588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#ae66cd705df2870244a05921f551ff131">llvm::AMDGPUSubtarget::getWavefrontSize</a>.</p>

</div>
</div>

### isWaveSizeKnown() {#aa1289175399e94194be94b32fb34c303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::isWaveSizeKnown ()</td>
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

<p>Returns if the wavesize of this subtarget is known reliable.</p>


<p>This is false only for the a default target-cpu that does not have an explicit +wavefrontsize target feature.</p>


<p>Definition at line 1595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### isXNACKEnabled() {#ad0dd54f1f3e1eb169b00651cd3d61da6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::isXNACKEnabled ()</td>
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



<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#afc6af409114a5e2da7bc8bedf9024cdc">TargetID</a>.</p>


<p>Referenced by <a href="#ad65c004eab25ab815e6bc696b8fb8578">getBaseReservedNumSGPRs</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloadstoreoptimizer-cpp/#a36f341897beb949904185df801dcc02a">needsConstrainedOpcode</a>.</p>

</div>
</div>

### ldsRequiresM0Init() {#a9d0bd109d96d0faea4a639d43910eaa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::ldsRequiresM0Init ()</td>
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

<p>Return if most LDS instructions have an m0 use that require m0 to be initialized.</p>

<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### loadStoreOptEnabled() {#a1141c1288fa7d35e8ecde9bd1ebc9769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::loadStoreOptEnabled ()</td>
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



<p>Definition at line 1141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a3970dc19cb63913985fac762d7320bf7">EnableLoadStoreOpt</a>.</p>

</div>
</div>

### maxHardClauseLength() {#a5c2b42a3405b2b4cb009beb1802caa32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::maxHardClauseLength ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The maximum number of instructions that can be enclosed in an S_CLAUSE on the given subtarget, or 0 for targets that do not support that instruction.</p></dd>
</dl>


<p>Definition at line 1359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ab8297b266634f159ee9c659cb5467b38">MaxHardClauseLength</a>.</p>

</div>
</div>

### mirFileLoaded() {#a1073d2ae057af7a11684100247250fb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSubtarget::mirFileLoaded (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1001 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="#a9f44cd05eefbb20a234a7e3b6369a7f8">isWave32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### needsAlignedVGPRs() {#a3b3c319ca867b6775449a12b4623634a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::needsAlignedVGPRs ()</td>
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

<p>Return if operations acting on VGPR tuples require even alignment.</p>

<p>Definition at line 1276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aaae1852e68f40bf33e7f6f49c1fd1cff">GFX90AInsts</a>.</p>

</div>
</div>

### overrideSchedPolicy() {#aec6845ed5bb22b096581b6887d6db618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSubtarget::overrideSchedPolicy (<a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy">MachineSchedPolicy</a> &amp; Policy, unsigned NumRegionInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 998 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="#ad6cff467fd7061aa3d14b86ebb25b426">enableSIScheduler</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#a47ee8ec29daa3551f798ff4449fbf4d5">llvm::MachineSchedPolicy::OnlyBottomUp</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#a0f609dd4ed94ea69ab680a7228f8786b">llvm::MachineSchedPolicy::OnlyTopDown</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#af3e6dd2ea28909a7bdc5fefae67766b9">llvm::MachineSchedPolicy::ShouldTrackLaneMasks</a> and <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#aee4e3964174cee8cf362508ccef135ca">llvm::MachineSchedPolicy::ShouldTrackPressure</a>.</p>

</div>
</div>

### ParseSubtargetFeatures() {#a1de3db2a7fc8d25fd5bb863ff90f0fd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNSubtarget::ParseSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### partialVCCWritesUpdateVCCZ() {#a0556cb1a1cb30ebf22d337d400074b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::partialVCCWritesUpdateVCCZ ()</td>
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

<p>Writes to VCC_LO/VCC_HI update the VCCZ flag.</p>

<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>.</p>

</div>
</div>

### privateMemoryResourceIsRangeChecked() {#a3c9cd4a438837eb5883a8b62107e8219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::privateMemoryResourceIsRangeChecked ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>If MUBUF instructions always perform range checking, even for buffer resources used for private memory access.</p></dd>
</dl>


<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### requiresCodeObjectV6() {#afd17b1239dc4bc597ba3b9fa0c54c6f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::requiresCodeObjectV6 ()</td>
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



<p>Definition at line 1269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#adc9aba4af084a7e0c89b55c62f8367d9">RequiresCOV6</a>.</p>

</div>
</div>

### requiresDisjointEarlyClobberAndUndef() {#a9078d25e7337b0e6490e8662f3a281a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::requiresDisjointEarlyClobberAndUndef ()</td>
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



<p>Definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### requiresNopBeforeDeallocVGPRs() {#a49268fedde6b2d35a3b106ea50e5dc62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::requiresNopBeforeDeallocVGPRs ()</td>
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



<p>Definition at line 1647 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### setScalarizeGlobalBehavior() {#a21e48d4c68f1e7530e0381bb9e45f0a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNSubtarget::setScalarizeGlobalBehavior (bool b)</td>
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



<p>Definition at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a4f5630510fbbd84621962f555f9d697e">ScalarizeGlobal</a>.</p>

</div>
</div>

### shouldClusterStores() {#a1bf8a3ec8755ac759a9f8c54ea5cf3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::shouldClusterStores ()</td>
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



<p>Definition at line 1639 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>.</p>

</div>
</div>

### supportsAgentScopeFineGrainedRemoteMemoryAtomics() {#a28542e778ba7389ffaf8b471585916a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::supportsAgentScopeFineGrainedRemoteMemoryAtomics ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if atomic operations targeting fine-grained memory work correctly at device scope, in allocations in host or peer PCIe device memory.</p></dd>
</dl>


<p>Definition at line 912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ab511aadc209e491aa6e33ad29de273df">HasAgentScopeFineGrainedRemoteMemoryAtomics</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a4ee4255870ff1c70530958a72fc246dd">globalMemoryFPAtomicIsLegal</a>.</p>

</div>
</div>

### supportsBackOffBarrier() {#a0c45ffdf8326d1afb0a80c50837f1a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::supportsBackOffBarrier ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the target supports backing off of s_barrier instructions when an exception is raised.</p></dd>
</dl>


<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a80be78dfd225963436a255b4b9aadc3e">BackOffBarrier</a>.</p>

</div>
</div>

### supportsGetDoorbellID() {#a49c35e81b626716f6e81656a7d301a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::supportsGetDoorbellID ()</td>
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



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### supportsMinMaxDenormModes() {#aa60e0e7438de97d15bba3e5963c5751d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::supportsMinMaxDenormModes ()</td>
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



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a>.</p>

</div>
</div>

### supportsWGP() {#aa99f892ef918babd54c99742f34d6548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::supportsWGP ()</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a22f77187b94b2e4b729590a1f9a6ba51">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getHSAKernelProps</a>.</p>

</div>
</div>

### unsafeDSOffsetFoldingEnabled() {#a1a905685dd1e80d0d65b2d02865b365f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::unsafeDSOffsetFoldingEnabled ()</td>
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



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#aeb1997ce0ad03e335de0a4a5388185be">EnableUnsafeDSOffsetFolding</a>.</p>

</div>
</div>

### useAA() {#a9f0c2a9bd6fbb4b4f778c62d04098b3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNSubtarget::useAA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#ad59a2062ef349882aa9c631277e37a74">UseAA</a>.</p>

</div>
</div>

### useDS128() {#a569ef38e3e8f453282539783412c5601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::useDS128 ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>If target supports ds_read/write_b128 and user enables generation of ds_read/write_b128.</p></dd>
</dl>


<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#aaef4f045c922c0ae9c8a500e0e2c29d4">CIInsts</a> and <a href="#abdff2a277a6b2747e2a283c9e7637119">EnableDS128</a>.</p>

</div>
</div>

### useFlatForGlobal() {#ac984e6be051494d2f59e7bbe563b84b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::useFlatForGlobal ()</td>
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



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#ad5bfbea25d0de2655684928e7d7aa2f1">FlatForGlobal</a>.</p>

</div>
</div>

### usePRTStrictNull() {#a92348ae76d31e89c8201b89c0eeb00cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::usePRTStrictNull ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>If target requires PRT Struct NULL support (zero result registers for sparse texture support).</p></dd>
</dl>


<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Reference <a href="#a5a333dc075b3c226ce688cb79acc102c">EnablePRTStrictNull</a>.</p>

</div>
</div>

### useVGPRIndexMode() {#a021be99fec633060e46fd3c482c1c3bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNSubtarget::useVGPRIndexMode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1019 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp/#a62fb5775660d8ff104047ac41cb5a252">EnableVGPRIndexMode</a>, <a href="#a99ce92019b9024b92d62341296eab008">hasMovrel</a> and <a href="#a9fae1c20909b13d71c4923a90967f74b">hasVGPRIndexMode</a>.</p>

</div>
</div>

### vmemWriteNeedsExpWaitcnt() {#a1b77b5797ab78e2aeffa5e772286d9bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::vmemWriteNeedsExpWaitcnt ()</td>
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



<p>Definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a5a040cb5d61ebf76561fcb74c4a77970">llvm::AMDGPUSubtarget::SEA_ISLANDS</a>.</p>

</div>
</div>

### zeroesHigh16BitsOfDest() {#a662ced5ddef5f29e53b545dfd51384e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNSubtarget::zeroesHigh16BitsOfDest (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns if the result of this instruction with a 16-bit result returned in a 32-bit register implicitly zeroes the high 16-bits, rather than preserve the original value.</p>


<p>This list was mostly derived from experimentation.</p>


<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a27bbb8548ee933d0231565d6ed407307">llvm::AMDGPUSubtarget::GFX9</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AddNoCarryInsts {#a238786700161fe23c5060ff610ee2968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::AddNoCarryInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae431b2e8fc0aee94b01cece42984d2dd">hasAddNoCarry</a>.</p>

</div>
</div>

### AutoWaitcntBeforeBarrier {#a3336ba2851ac5650dc025a8642214e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::AutoWaitcntBeforeBarrier = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a361e1bd0ac3e221a2fe75f68ea9d0d41">hasAutoWaitcntBeforeBarrier</a>.</p>

</div>
</div>

### BackOffBarrier {#a80be78dfd225963436a255b4b9aadc3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::BackOffBarrier = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a0c45ffdf8326d1afb0a80c50837f1a4c">supportsBackOffBarrier</a>.</p>

</div>
</div>

### CIInsts {#aaef4f045c922c0ae9c8a500e0e2c29d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::CIInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ac79093e78236587f3f298fd96a06947e">hasDS96AndDS128</a>, <a href="#a437295c0cecbdbec197e655e34cab714">hasDwordx3LoadStores</a>, <a href="#ad6b3273818698235f76b04db7793dd12">hasGWSSemaReleaseAll</a>, <a href="#abf0e7e914d5468cf242a422fb6a53070">haveRoundOpsF64</a> and <a href="#a569ef38e3e8f453282539783412c5601">useDS128</a>.</p>

</div>
</div>

### DumpCode {#a1b2245d34fac299ea10ae1fd2cabff5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::DumpCode = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a74603d93fb144ec34a796f1f07eb39c2">dumpCode</a>.</p>

</div>
</div>

### EnableCuMode {#a70a9a419e5ce5ddf54374dc797f765f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::EnableCuMode = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a58b73e7766fb13e9033b8cc011e5d3ea">hasLDSMisalignedBug</a> and <a href="#a62fb29606869fbd40b285c1cda4be12f">isCuModeEnabled</a>.</p>

</div>
</div>

### EnableDS128 {#abdff2a277a6b2747e2a283c9e7637119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::EnableDS128 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a569ef38e3e8f453282539783412c5601">useDS128</a>.</p>

</div>
</div>

### EnableFlatScratch {#ac98f2bbf494891ca79075f7a9b052f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::EnableFlatScratch = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a3e8da3fb902e2e5c0443907cab82ba01">enableFlatScratch</a>.</p>

</div>
</div>

### EnableLoadStoreOpt {#a3970dc19cb63913985fac762d7320bf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::EnableLoadStoreOpt = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a1141c1288fa7d35e8ecde9bd1ebc9769">loadStoreOptEnabled</a>.</p>

</div>
</div>

### EnablePreciseMemory {#a408fffe61eaab170cb661602f3471bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::EnablePreciseMemory = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aec33da886213da6a50eb967bf8e4548b">isPreciseMemoryEnabled</a>.</p>

</div>
</div>

### EnablePRTStrictNull {#a5a333dc075b3c226ce688cb79acc102c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::EnablePRTStrictNull = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a92348ae76d31e89c8201b89c0eeb00cb">usePRTStrictNull</a>.</p>

</div>
</div>

### EnableSIScheduler {#a830227621ce04eaf78322896a0c79f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::EnableSIScheduler = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ad6cff467fd7061aa3d14b86ebb25b426">enableSIScheduler</a>.</p>

</div>
</div>

### EnableSRAMECC {#a36608dd76bfe6e185be691777b445ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::EnableSRAMECC = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### EnableTgSplit {#a90e036c3eafba2aa898f7895579c8f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::EnableTgSplit = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a4bec96c96006608cebef39898b836e81">isTgSplitEnabled</a>.</p>

</div>
</div>

### EnableUnsafeDSOffsetFolding {#aeb1997ce0ad03e335de0a4a5388185be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::EnableUnsafeDSOffsetFolding = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a1a905685dd1e80d0d65b2d02865b365f">unsafeDSOffsetFoldingEnabled</a>.</p>

</div>
</div>

### EnableXNACK {#a0c7aafc6dd938a9b5d40f1edf2d3eaf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::EnableXNACK = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### FastDenormalF32 {#aba3f51a2b0a671556f0ad51f2e8baf47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::FastDenormalF32 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### FeatureDisable {#af2eedff75f27bd6d78537155abac0f79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::FeatureDisable = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### FlatAddressSpace {#af98d3431546e921d906556ab6b9d6cb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::FlatAddressSpace = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a90fc707270386fb970207745d6675805">hasFlatAddressSpace</a>.</p>

</div>
</div>

### FlatForGlobal {#ad5bfbea25d0de2655684928e7d7aa2f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::FlatForGlobal = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a> and <a href="#ac984e6be051494d2f59e7bbe563b84b9">useFlatForGlobal</a>.</p>

</div>
</div>

### FlatGlobalInsts {#a4c4346f1426fe53905715ca0f0d2fd0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::FlatGlobalInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a85d032a1f1dc4a077f3644b16a6a0243">hasFlatGlobalInsts</a>.</p>

</div>
</div>

### FlatInstOffsets {#a8caa14af5acb006632cfd31a4c28e78c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::FlatInstOffsets = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a1b42b67d0df8ad1a351bbdc503c115a1">hasFlatInstOffsets</a>.</p>

</div>
</div>

### FlatScratchInsts {#ad737ff5de5197f759fd10988312481b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::FlatScratchInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a28caebd4d797207b1f5989ef56df5683">hasFlatScratchInsts</a>.</p>

</div>
</div>

### FMA {#aa3ad8d1429472400a745a288263f1fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::FMA = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa3d326302b1b07150d09e0745a3e9bcc">hasFMA</a>.</p>

</div>
</div>

### FP64 {#ad989699f72d64cd5c12d52856532880a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::FP64 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae408833a27e3db45bd5d4b790cd1ba9f">hasFP64</a> and <a href="#a2ba650a151ac898c90b1940ea3e951ff">hasHWFP64</a>.</p>

</div>
</div>

### FullRate64Ops {#a621ba6bafe12da8a8af4288ef2c1040e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::FullRate64Ops = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a8263d2c3a266941b3669828ecf1db53e">hasFullRate64Ops</a>.</p>

</div>
</div>

### Gen {#a72d895427056e0f3e9147974a95d11f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::Gen = <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a44ffb5f3120d0b92ed40f4ee48ada81e">INVALID</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ace4de1de19cbe837c578fb3654b6c998">getGeneration</a> and <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### GFX10\_3Insts {#a41a56363d4e58147e7df5adb4872c3ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX10_3Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a3b70c1201c0b1688d7284174c11a5b77">hasGFX10_3Insts</a>.</p>

</div>
</div>

### GFX10\_AEncoding {#a7c380b42afd78ccb7c178bc27ad0fb27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX10_AEncoding = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a7bf65bf4917efcfd2afded9f48afcfee">hasGFX10_AEncoding</a>.</p>

</div>
</div>

### GFX10\_BEncoding {#a25a9bffea45bd561499b442b0544ccb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX10_BEncoding = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#afc3b60da830f13bd93a91b751d5cfaf3">hasAtomicCSub</a>, <a href="#acd5cffaeaa2cffe0f336c6e9aca140b2">hasGFX10_BEncoding</a> and <a href="#a451d3f382bdad515e0cb3e9f39de86aa">hasGlobalAddTidInsts</a>.</p>

</div>
</div>

### GFX10Insts {#a00cf3c0a968bd5bff04c762c55336e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX10Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### GFX11Insts {#a23594b888d739de018ed2a227d711ced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX11Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a1f222ef89ce8fb3fe994bd2c7103f843">hasCompressedExport</a>, <a href="#abf65492620612e129dd3e847a2c4e57f">hasDelayAlu</a>, <a href="#a4fa10ba2f5551b22c35eecfa74b3296a">hasDOTOpSelHazard</a>, <a href="#aa828632df398b007b1107ea5a5fbfe23">hasFlatScratchSVSMode</a>, <a href="#a9a6c28d83ad975e7eb5384641191d9bc">hasNullExportTarget</a>, <a href="#aa4097c8e7593fbd1a0b8cff5964fa5d7">hasSPackHL</a> and <a href="#a5eebf04eb63bf98ee3d5ec4702b65564">hasVINTERPEncoding</a>.</p>

</div>
</div>

### GFX12Insts {#aee8f87ccf5572392018ca06a2080989f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX12Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a4800f21d7866329eeb7a6bbcef9cb9e7">hasGetPCZeroExtension</a> and <a href="#a005c3432e3eef07f10653bf3dffccad6">hasPrefetch</a>.</p>

</div>
</div>

### GFX7GFX8GFX9Insts {#ace75fcd5d3c4b1726d013754c80ae304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX7GFX8GFX9Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### GFX8Insts {#a953743f90862340f08cb9cd50174824b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX8Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#abd18ad36f7c9ff894f439f5dd79f05de">hasLDSFPAtomicAddF32</a>.</p>

</div>
</div>

### GFX90AInsts {#aaae1852e68f40bf33e7f6f49c1fd1cff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX90AInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a1fc0ea9be83e3d4cb2aeb2d7b2363e73">hasGFX90AInsts</a>, <a href="#a85c22bc10e6e36bbe63c69bfb9638e09">hasLDSFPAtomicAddF64</a>, <a href="#a3afde3a0eda49172cc0f673da8ab75ea">hasPkMovB32</a>, <a href="#a1828e0b98df9d5cd61698e7585d8e7a7">hasShift64HighRegBug</a> and <a href="#a3b3c319ca867b6775449a12b4623634a">needsAlignedVGPRs</a>.</p>

</div>
</div>

### GFX940Insts {#a167f1c9d969e90ea41a3dd52a37b32e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX940Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a4fa10ba2f5551b22c35eecfa74b3296a">hasDOTOpSelHazard</a>, <a href="#a2017ee435d93b4ec8c38e024d5cb9b30">hasDstSelForwardingHazard</a>, <a href="#aa828632df398b007b1107ea5a5fbfe23">hasFlatScratchSVSMode</a>, <a href="#a80ef035f066bb00307e5cccb694e20e2">hasGFX940Insts</a>, <a href="#a815b2f5ace41f35b5ca3534086af69af">hasLshlAddB64</a>, <a href="#a92e0b317959309846ea919ad2cf08ffc">hasMovB64</a>, <a href="#a1828e0b98df9d5cd61698e7585d8e7a7">hasShift64HighRegBug</a>, <a href="#a7fdc7771608a86b53935f4f6fc101c39">hasTransForwardingHazard</a> and <a href="#ab96225992445aceb04e50ab1e06f068e">hasVDecCoExecHazard</a>.</p>

</div>
</div>

### GFX950Insts {#ac164adfdd62c69dbd820c417d2c24de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX950Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a2e1c82209fdf5c7efc8a19f003b60a9b">hasCvtScaleForwardingHazard</a> and <a href="#a6ba0e36ee4fa0e5829ab468e0ad18627">hasGFX950Insts</a>.</p>

</div>
</div>

### GFX9Insts {#a443df8396a86d96634419086278c7452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::GFX9Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ac4dd4cfc2dbcd57221490dfc8b265592">hasScalarMulHiInsts</a>, <a href="#a8fbcbd9c9b04e70f819b814f6a02a669">hasScalarPackInsts</a> and <a href="#a0640303601c270bb5913e56281c6ff92">hasSwap</a>.</p>

</div>
</div>

### HalfRate64Ops {#a948eae74cbc251ff4e8984a04ecbcdc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HalfRate64Ops = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aab504c30d42758271e85ec4104b8ffa4">hasHalfRate64Ops</a>.</p>

</div>
</div>

### Has1\_5xVGPRs {#a056c928381864fc1f037babbad25f392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::Has1_5xVGPRs = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a0cc2fccd89413e7c79e54d4b657872c7">has1_5xVGPRs</a>.</p>

</div>
</div>

### HasA16 {#ac2670ded2f52b0a8abebe0bad06cf2fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasA16 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a0985b28a440a19cc9e6b8229e75b5152">hasA16</a>.</p>

</div>
</div>

### HasAgentScopeFineGrainedRemoteMemoryAtomics {#ab511aadc209e491aa6e33ad29de273df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAgentScopeFineGrainedRemoteMemoryAtomics = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a28542e778ba7389ffaf8b471585916a8">supportsAgentScopeFineGrainedRemoteMemoryAtomics</a>.</p>

</div>
</div>

### HasApertureRegs {#abe6001a0f135daa1bb722da2e6197aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasApertureRegs = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a18ef501217029506f0ed9027ff266480">hasApertureRegs</a>.</p>

</div>
</div>

### HasArchitectedFlatScratch {#aaee498bf7e34783628f61d9aa83fead3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasArchitectedFlatScratch = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#af3fc4aac61bac7b5675218848b4b8e90">flatScratchIsArchitected</a> and <a href="#ad65c004eab25ab815e6bc696b8fb8578">getBaseReservedNumSGPRs</a>.</p>

</div>
</div>

### HasArchitectedSGPRs {#addd8731d7f792b6ae461a3e677e853b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasArchitectedSGPRs = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a297a2e0f9d548e720e1303be506ee7a4">hasArchitectedSGPRs</a>.</p>

</div>
</div>

### HasAshrPkInsts {#a9da82d4d3ac2f557507d846bd9936a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAshrPkInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a5c9b0d88a0394d2496b7aa56842f6def">hasAshrPkInsts</a>.</p>

</div>
</div>

### HasAtomicBufferGlobalPkAddF16Insts {#aa0ad796f74734bb5b657a1f2d1a7ed44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicBufferGlobalPkAddF16Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#acfcf88257e77cb54415205652e2e88ee">hasAtomicBufferGlobalPkAddF16Insts</a>.</p>

</div>
</div>

### HasAtomicBufferGlobalPkAddF16NoRtnInsts {#aac211a8f705f61a60b6ced36b9731e3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicBufferGlobalPkAddF16NoRtnInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ab0a8ac068b8f8aa548a3ce1fe90dad8a">hasAtomicBufferGlobalPkAddF16NoRtnInsts</a>.</p>

</div>
</div>

### HasAtomicBufferPkAddBF16Inst {#aa6afb3f2adf199a6465ae5f8015cfd79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicBufferPkAddBF16Inst = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ab34bcbfbfadd8de8a1172c659d3d2aa4">hasAtomicBufferPkAddBF16Inst</a>.</p>

</div>
</div>

### HasAtomicCSubNoRtnInsts {#aa295bd451d30d00f2fde59fa44045434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicCSubNoRtnInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a702e9540e27a17a550b4937032b939e0">hasAtomicCSubNoRtnInsts</a>.</p>

</div>
</div>

### HasAtomicDsPkAdd16Insts {#aa3642c58f343c3c3a82877e1afb7db5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicDsPkAdd16Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a0318f31ec7d1b90f27b5413cd224663c">hasAtomicDsPkAdd16Insts</a>.</p>

</div>
</div>

### HasAtomicFaddNoRtnInsts {#a9e196e9035b546b74522a169d0a1c45f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicFaddNoRtnInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aab7b3ab8cbd1cf72b5e93d6983a748a1">hasAtomicFaddInsts</a> and <a href="#ab7f9c6b88d7dd2493b9c6a68112a68c5">hasAtomicFaddNoRtnInsts</a>.</p>

</div>
</div>

### HasAtomicFaddRtnInsts {#adae5a837f4ede6853fdaec64c4892d51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicFaddRtnInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aab7b3ab8cbd1cf72b5e93d6983a748a1">hasAtomicFaddInsts</a> and <a href="#a3779799f24ab110dc3a64ebfb9f472bb">hasAtomicFaddRtnInsts</a>.</p>

</div>
</div>

### HasAtomicFlatPkAdd16Insts {#a85c2d01235c0d1375f99e77b6b604771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicFlatPkAdd16Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a9bce2aae2056dd71265b887b181e17c1">hasAtomicFlatPkAdd16Insts</a>.</p>

</div>
</div>

### HasAtomicFMinFMaxF32FlatInsts {#a8817af4d2308f9cdb31a8b57fc797007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicFMinFMaxF32FlatInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a1ba00ffdcbb35e817245f6903180e271">hasAtomicFMinFMaxF32FlatInsts</a>.</p>

</div>
</div>

### HasAtomicFMinFMaxF32GlobalInsts {#a86f942a251a036fb225fb8f8f0deb555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicFMinFMaxF32GlobalInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a68a2942b35679bd8c4f413436f58b54f">hasAtomicFMinFMaxF32GlobalInsts</a>.</p>

</div>
</div>

### HasAtomicFMinFMaxF64FlatInsts {#a07f6f1c9612fe2ec6fed7f949a8ebe26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicFMinFMaxF64FlatInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a143ff62a1e0eae583030d0787c1219ed">hasAtomicFMinFMaxF64FlatInsts</a>.</p>

</div>
</div>

### HasAtomicFMinFMaxF64GlobalInsts {#ac8a0f2f00bafd753b886d0c61cef8dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicFMinFMaxF64GlobalInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a968992bddefc74c03eda64e5889e7116">hasAtomicFMinFMaxF64GlobalInsts</a>.</p>

</div>
</div>

### HasAtomicGlobalPkAddBF16Inst {#ad8bbc65850f15c486cc2cf5935c0c709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasAtomicGlobalPkAddBF16Inst = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ad71a92219d05963817490411ca445902">hasAtomicGlobalPkAddBF16Inst</a>.</p>

</div>
</div>

### HasBitOp3Insts {#ac8bdaf283ec09f2b9c47ced006837467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasBitOp3Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a1ae9d4320920b5bd1a193c69c22c1dbc">hasBitOp3Insts</a>.</p>

</div>
</div>

### HasCvtFP8Vop1Bug {#ae790c1da8d9eba51c60d614ef837f80c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasCvtFP8Vop1Bug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa4f5adb4d0fdc24fcb3947f50a4c6645">hasCvtFP8VOP1Bug</a>.</p>

</div>
</div>

### HasDefaultComponentBroadcast {#a8faff728ce71f6506ee26c230f8e9910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDefaultComponentBroadcast = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#afca224687236c554e05ec7495f5f5b26">hasDefaultComponentBroadcast</a>.</p>

</div>
</div>

### HasDefaultComponentZero {#aee91c4560c47c3b5bb78a641a5559ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDefaultComponentZero = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a1e5c0a7c3425568c65564eb43572f6f1">hasDefaultComponentZero</a>.</p>

</div>
</div>

### HasDLInsts {#a5e04190f533d5235647a1e89f9d83014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDLInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a24618695d970449f186b50c63648f674">hasDLInsts</a>.</p>

</div>
</div>

### HasDot10Insts {#acfb9f1d4990af79ac841d54ff4a51f6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot10Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa3faef1a7ec189bbf0d27fbcd91b179c">hasDot10Insts</a>.</p>

</div>
</div>

### HasDot11Insts {#a04c4ff7828efe3cd1ba4a631f899299d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot11Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a3dcf980f5642f70d5cc92ad78107aa42">hasDot11Insts</a>.</p>

</div>
</div>

### HasDot12Insts {#ad0ba569ec8d5c4c8a1017745af2231fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot12Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ac76360a6bc40d4eda96a8fa387aec898">hasDot12Insts</a>.</p>

</div>
</div>

### HasDot13Insts {#a1bca337aa04112b4496e6a2569c92694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot13Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a9cb42a977c1487218f417ea5bd4b8f85">hasDot13Insts</a>.</p>

</div>
</div>

### HasDot1Insts {#ad9f698137ecac3f8bfd57c1d2bd225bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot1Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a3381161b7a2623d70ebc79101439de62">hasDot1Insts</a>.</p>

</div>
</div>

### HasDot2Insts {#a9682ddcf41ed820be15cc7218775fe87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot2Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a088b522817602bb6d879afbb1dd28d82">hasDot2Insts</a>.</p>

</div>
</div>

### HasDot3Insts {#a3520574a8e86bbe157a34c179c9747da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot3Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a338f477b9e95f79dd790b1962ca6adc9">hasDot3Insts</a>.</p>

</div>
</div>

### HasDot4Insts {#a8694a6472636f253ac7a422066ee9e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot4Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#af0b7da2e35759b56235cc538ab7c0e1b">hasDot4Insts</a>.</p>

</div>
</div>

### HasDot5Insts {#ae6ded25230b26b659566be69c769d464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot5Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ab66fd170ebeaddc8ed07d4db2c2a77b4">hasDot5Insts</a>.</p>

</div>
</div>

### HasDot6Insts {#a02ff9dd7be4e70091e99c1997741eda8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot6Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a80150d52bbde3f5caaaf2d6d2a5b8122">hasDot6Insts</a>.</p>

</div>
</div>

### HasDot7Insts {#a6e3d3703aae398dc4469527df9c758e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot7Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a182d4bc6088accdac52a4b4eb362abf6">hasDot7Insts</a>.</p>

</div>
</div>

### HasDot8Insts {#a8a489d835ec8202127cea0eb9ce07dce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot8Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ac39193e57744e29d333b5790b4d4e656">hasDot8Insts</a>.</p>

</div>
</div>

### HasDot9Insts {#a86c2b493bd4f475fb096ae324d582826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDot9Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#af98e76929ea61bb6075f5146cd2fe0fd">hasDot9Insts</a>.</p>

</div>
</div>

### HasDPALU\_DPP {#a2447a5253106678c1dfe0bab536c7c9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDPALU_DPP = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ad6b35f7e88b68cba1844915dc16db9ec">hasDPALU_DPP</a>.</p>

</div>
</div>

### HasDPP {#a389b331031e56958a8f3da55723465fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDPP = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a5eebe2da3e17c5d7c4b4f4dfecdb4df4">hasDPP</a>, <a href="#a91bc08ab0ee415853bd31422d5ce4589">hasDPPBroadcasts</a> and <a href="#a11f8b622001c4bba3eab4afb901643b8">hasDPPWavefrontShifts</a>.</p>

</div>
</div>

### HasDPP8 {#a23518644c73072ed1e0e8d627be8ba01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDPP8 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ab6327e2570c1c58c44b5fc646ec82f6f">hasDPP8</a>.</p>

</div>
</div>

### HasDPPSrc1SGPR {#a87170f8953730e15a8dfe935c37232dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasDPPSrc1SGPR = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aedc86d07fcc0b61c6f1e138c76432aa4">hasDPPSrc1SGPR</a>.</p>

</div>
</div>

### HasExtendedImageInsts {#a08e442e1f7eb5131692ccd5bba77774c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasExtendedImageInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a254ad120b3ae58ca663832ba14592457">hasExtendedImageInsts</a>.</p>

</div>
</div>

### HasFlatAtomicFaddF32Inst {#a27da80ce11ad15a11fc4c41a33666a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasFlatAtomicFaddF32Inst = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a4bf85a994788b693f38928fdf8b7a48f">hasFlatAtomicFaddF32Inst</a>.</p>

</div>
</div>

### HasFlatBufferGlobalAtomicFaddF64Inst {#afff59c5a54f5886e497f9797030c67b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasFlatBufferGlobalAtomicFaddF64Inst = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ab8a8ecf7c823363079b7b9e403908d5a">hasFlatBufferGlobalAtomicFaddF64Inst</a>.</p>

</div>
</div>

### HasFlatSegmentOffsetBug {#a29628d7d35aef1950da107293e9f68f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasFlatSegmentOffsetBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a7c210fe3c1ded331101415c059606e2e">hasFlatSegmentOffsetBug</a>.</p>

</div>
</div>

### HasFmacF64Inst {#a6a0aae30a368c4c91584185cc3ad6373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasFmacF64Inst = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a59ab2534372c0adc46a34c429cedbc05">hasFmacF64Inst</a>.</p>

</div>
</div>

### HasFmaMixInsts {#a8050bb1b1445e617520f2a5bfad62e3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasFmaMixInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#addfe5ff70771ccdda4ae3c6e282a5441">hasFmaMixInsts</a>.</p>

</div>
</div>

### HasForceStoreSC0SC1 {#a3b30160b1757f25c85752a1fe26e157e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasForceStoreSC0SC1 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#acf635e2bc94a0c4f29a493833eb548c4">hasForceStoreSC0SC1</a>.</p>

</div>
</div>

### HasFP8ConversionInsts {#a952f6917a737a034709d9c849dfb0d9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasFP8ConversionInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a17d227c50874535df8d88c8256939a82">hasFP8ConversionInsts</a>.</p>

</div>
</div>

### HasFP8Insts {#a9207fa4cbccf18aa0b9be67d2a54d744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasFP8Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a4c4e8213a552980916f041896c5989be">hasFP8Insts</a>.</p>

</div>
</div>

### HasG16 {#a0d0570029543761ca74c7df68fc59744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasG16 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aaac87839eb0077c44120678bcab56bc9">hasG16</a>.</p>

</div>
</div>

### HasGDS {#aa07db84b412bc41a23e2c1fff3f7efd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasGDS = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aedfc0056986632c8d0462319b661d692">hasGDS</a>.</p>

</div>
</div>

### HasGetWaveIdInst {#a4258d4c50ebe4adf47d1556d82fef254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasGetWaveIdInst = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a1ec9fcfe37ebfe9de9723d9909525634">hasGetWaveIdInst</a>.</p>

</div>
</div>

### HasGWS {#a3f7e4c82242d7fba786da95ea84f39dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasGWS = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ac7a4a974fce95bb3f78e370f63d25a56">hasGWS</a>.</p>

</div>
</div>

### HasImageGather4D16Bug {#a9c980d76fd4aa2aedacdddcd3e275fc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasImageGather4D16Bug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa38a233aad5f337533309b4f04a4effd">hasImageGather4D16Bug</a>.</p>

</div>
</div>

### HasImageInsts {#a56d26cde5f690bf9459fc2f76865d030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasImageInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa2caffdb8654b132f6f434c0fe9e1112">hasImageInsts</a>.</p>

</div>
</div>

### HasImageStoreD16Bug {#abc3af3f5d368b630f23f4dffdd0b46fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasImageStoreD16Bug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a0e70db1e8483e587c41a315dfad8c88a">hasImageStoreD16Bug</a>.</p>

</div>
</div>

### HasInstFwdPrefetchBug {#af46635e054a2a083f592723ddb861aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasInstFwdPrefetchBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a95c817fefbb5c1444ecadc1a790b1273">hasInstFwdPrefetchBug</a>.</p>

</div>
</div>

### HasIntClamp {#ae7bb96baf904d1d3c70e476a6cb4e488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasIntClamp = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a7af63ea0547908098ee65377e979d3ea">hasIntClamp</a>.</p>

</div>
</div>

### HasLdsBranchVmemWARHazard {#a03acf80e335385e4af1e41537e843343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasLdsBranchVmemWARHazard = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a1e3aaf52cbaf44191f00656b774cdede">hasLdsBranchVmemWARHazard</a>.</p>

</div>
</div>

### HasMADIntraFwdBug {#a272b4543c35465b19829ba03c72a4730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasMADIntraFwdBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a33fbbd04a4a2d81c229f0e613de73905">hasMADIntraFwdBug</a>.</p>

</div>
</div>

### HasMAIInsts {#a2f1176e8f488b0bc45c6478cc494e8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasMAIInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a278004c824cd46c7504e68ec7c5f2d57">hasMAIInsts</a>.</p>

</div>
</div>

### HasMemoryAtomicFaddF32DenormalSupport {#aeecfaf3b2b9359e37af4fe07166cb226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasMemoryAtomicFaddF32DenormalSupport = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a0087efb42b61a14ba8975ab581ed5f5a">hasMemoryAtomicFaddF32DenormalSupport</a>.</p>

</div>
</div>

### HasMFMAInlineLiteralBug {#ae792f1ad039fd0a51607d85a03feca22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasMFMAInlineLiteralBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a2daa95e19ef6f3a5d3be7f175d5bde59">hasMFMAInlineLiteralBug</a>.</p>

</div>
</div>

### HasMinimum3Maximum3F16 {#a676e72a69c1f0f7a4dc54a9b99e05d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasMinimum3Maximum3F16 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a663d34243037a886d4932750a3cd40d2">hasMinimum3Maximum3F16</a>.</p>

</div>
</div>

### HasMinimum3Maximum3F32 {#a551988d5dffbfba8cd48d910b7cc9b14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasMinimum3Maximum3F32 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a017de56f30979f32ad941844f3e6d66f">hasMinimum3Maximum3F32</a>.</p>

</div>
</div>

### HasMinimum3Maximum3PKF16 {#aac44b0653c95e1c63358778a56937d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasMinimum3Maximum3PKF16 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a57fd5bacadbf867edd08ea6551ef5df9">hasMinimum3Maximum3PKF16</a>.</p>

</div>
</div>

### HasMovrel {#a76168e6f26b0f7cada393b6baaf6d7aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasMovrel = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a99ce92019b9024b92d62341296eab008">hasMovrel</a>.</p>

</div>
</div>

### HasMSAALoadDstSelBug {#aaaf90f97cd99f018d4886dad8d49560c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasMSAALoadDstSelBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a52d1955bc658f8878e3746993d2e0530">hasMSAALoadDstSelBug</a>.</p>

</div>
</div>

### HasNoDataDepHazard {#a6db4fbc67c6b520e52f966ff3bd992e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasNoDataDepHazard = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a758cbecbfce67cc0a42af981d6f1755b">hasNoDataDepHazard</a>.</p>

</div>
</div>

### HasNoSdstCMPX {#a8fb3a41719c2219a977c3aa110a29cc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasNoSdstCMPX = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ad0569952d064262bc16c3052746013fc">hasNoSdstCMPX</a>.</p>

</div>
</div>

### HasNSAClauseBug {#a4ae3a84968e835cfb541a62de2007476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasNSAClauseBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a3633028daa01022eaf44181a9f5028a4">hasNSAClauseBug</a>.</p>

</div>
</div>

### HasNSAEncoding {#ae2847a61e28335ec96f3aba0aa582e23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasNSAEncoding = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a90329091d5d23e8a4bac1a2803d252b2">hasNSAEncoding</a>.</p>

</div>
</div>

### HasNSAtoVMEMBug {#abfaf0dbd880bc35fd34db18c5166370c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasNSAtoVMEMBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aadb9bb3c036cfcddf3fc2634071fa163">hasNSAtoVMEMBug</a>.</p>

</div>
</div>

### HasOffset3fBug {#a8660a471fd90d7d6e3abbb00a325bf5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasOffset3fBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a42ffba7488c6f98d42703852d9d83361">hasOffset3fBug</a>.</p>

</div>
</div>

### HasPackedFP32Ops {#aab5049a486074311dc22e29c08a0c60c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasPackedFP32Ops = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a7f1b4a610bfabed1dac80708d399d552">hasPackedFP32Ops</a>.</p>

</div>
</div>

### HasPackedTID {#af9b5852cc8a419d0d0e5eed8ac1b6d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasPackedTID = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae133c0c692754b7a2e431eae75db8733">hasPackedTID</a>.</p>

</div>
</div>

### HasPartialNSAEncoding {#a58c2025484c09d2f354f1f6b4b4a461e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasPartialNSAEncoding = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#af44e06d801c094cd657e62994746d62a">hasPartialNSAEncoding</a>.</p>

</div>
</div>

### HasPermlane16Swap {#a53830d2988831622a620d9df123c93ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasPermlane16Swap = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aacf87c06d72fdf7a23f5231ce3834fcb">hasPermlane16Swap</a>.</p>

</div>
</div>

### HasPermlane32Swap {#af58a534c85df77c9d8b03d0ce88d622d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasPermlane32Swap = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a03f2b3a5ff8e0b8454a6d0c46cb63c98">hasPermlane32Swap</a>.</p>

</div>
</div>

### HasPkFmacF16Inst {#a2d7cdc43a6afa870465964d752b5072b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasPkFmacF16Inst = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a06c09c7d429aaae637f401b51e855b5a">hasPkFmacF16Inst</a>.</p>

</div>
</div>

### HasPrivEnabledTrap2NopBug {#a451a241ad87234390e77346e090cf035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasPrivEnabledTrap2NopBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a2cc4098b4aa7563be99e6d57965966f1">hasPrivEnabledTrap2NopBug</a>.</p>

</div>
</div>

### HasPrngInst {#a9bff28a332d5b309966a353003a80e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasPrngInst = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a438e29c27b814b7bcf58616cc57862b7">hasPrngInst</a>.</p>

</div>
</div>

### HasPseudoScalarTrans {#a887b1d13e204a49b28ba68b995176cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasPseudoScalarTrans = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ac695674c0b51da8114892ef06e224ef3">hasPseudoScalarTrans</a>.</p>

</div>
</div>

### HasR128A16 {#a63b7cd3536956300a3e6246c7f876ae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasR128A16 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a426587719be9d9751e8c667734f0cc7a">hasR128A16</a>.</p>

</div>
</div>

### HasRequiredExportPriority {#aa3c8ecafa08eb2849d23f7fe63a901e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasRequiredExportPriority = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a4f7250d7950b6fb7e11b676b0d6a84ba">hasRequiredExportPriority</a>.</p>

</div>
</div>

### HasRestrictedSOffset {#adbf185c7be65b7b2a4df9fc24ac50e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasRestrictedSOffset = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a7a64fa91bbb4ff5f0417e16ad408e0c9">hasRestrictedSOffset</a>.</p>

</div>
</div>

### HasSALUFloatInsts {#a1548ff560030d89242f6bba6fc3f43e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasSALUFloatInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aea382e48834aaf8b5f0e334622faa197">hasSALUFloatInsts</a>.</p>

</div>
</div>

### HasScalarAtomics {#a820f935a25ced4c881e7ca3b60d775f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasScalarAtomics = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a634ca68c4b030c1871ab805adec13d11">hasScalarAtomics</a>.</p>

</div>
</div>

### HasScalarDwordx3Loads {#a18974200e120861ba26d24805f87bce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasScalarDwordx3Loads = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ab952ba0f11fe329b25af21199f557611">hasScalarDwordx3Loads</a>.</p>

</div>
</div>

### HasScalarStores {#a2438b345b76fa20009799525ecf82a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasScalarStores = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a83477fe97fe7b3e570d433e24f71c371">hasScalarStores</a>.</p>

</div>
</div>

### HasSDWAMac {#acffe84152bfba8302521f0f8c77671e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasSDWAMac = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a175f25a33bfc2c593cf6eccc3a2bae67">hasSDWAMac</a>.</p>

</div>
</div>

### HasSDWAOmod {#a371756f715ae24e7c7d6ee87bfb6d9bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasSDWAOmod = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a0330bc04e02e5f966bb34b94faee3ea7">hasSDWAOmod</a>.</p>

</div>
</div>

### HasSDWAOutModsVOPC {#a7076d6c3ca7fb96840d61e52a0f0400b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasSDWAOutModsVOPC = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a67eda8a7f0b4516f8f08d82651207c91">hasSDWAOutModsVOPC</a>.</p>

</div>
</div>

### HasSDWAScalar {#a1cf3065241a25e6b9f9f1d2477e24ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasSDWAScalar = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a0af7bcad0087b2e7738d1636e5e4793e">hasSDWAScalar</a>.</p>

</div>
</div>

### HasSDWASdst {#ac714f4a5d78945bf0268b7e166781db9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasSDWASdst = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a8ef1770dca2e75c8a049d7441802932f">hasSDWASdst</a>.</p>

</div>
</div>

### HasShaderCyclesHiLoRegisters {#a3929ea1c1954af1d4f5d2278638ba642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasShaderCyclesHiLoRegisters = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a8d831a339bf2cd8bf0b9e5996a3ed123">hasShaderCyclesHiLoRegisters</a>.</p>

</div>
</div>

### HasShaderCyclesRegister {#a8c5c784b6b9621f4cdab3cd273c9124e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasShaderCyclesRegister = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae733f0fbb575bf1a991461b1df4077a7">hasShaderCyclesRegister</a>.</p>

</div>
</div>

### HasSMemRealTime {#ae0d2cfb5028990ce762ad06fbebd0b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasSMemRealTime = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a9094c845e9359c8c1c873e14e1be18f5">hasSMemRealTime</a>.</p>

</div>
</div>

### HasSMemTimeInst {#a94f4e1e3ad1d7eee4e740ad2e3c17658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasSMemTimeInst = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a2eda17e3b44637b79a9aac0e47ab249f">hasSMemTimeInst</a>.</p>

</div>
</div>

### HasSMEMtoVectorWriteHazard {#a9d59aff4310d57b0806f1abbcd12021d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasSMEMtoVectorWriteHazard = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a9e531910f7c7133e8696a4dea9ff873a">hasSMEMtoVectorWriteHazard</a>.</p>

</div>
</div>

### HasUnpackedD16VMem {#aea0f6b19cef0ddc119a88ae60f5461d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasUnpackedD16VMem = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ad30b3c952ed576256171d49971ec9241">hasUnpackedD16VMem</a>.</p>

</div>
</div>

### HasVALUTransUseHazard {#ade9ec63e4421f2fc8415717a86032e2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasVALUTransUseHazard = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae6c6edd32a125d77f3c55139393019b4">hasVALUTransUseHazard</a>.</p>

</div>
</div>

### HasVcmpxExecWARHazard {#ae20ac61b7ca1deaf9f80e426552884a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasVcmpxExecWARHazard = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a4b700ecd2d736b769de16280afbca49a">hasVcmpxExecWARHazard</a>.</p>

</div>
</div>

### HasVcmpxPermlaneHazard {#a7d6b53b3aebc2a64f37b6317279fe2a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasVcmpxPermlaneHazard = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a5de1edfcd129b2eb4325a889489ef633">hasVcmpxPermlaneHazard</a>.</p>

</div>
</div>

### HasVGPRIndexMode {#a2ee2435b1a7b8c192632aeabdd325e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasVGPRIndexMode = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a9fae1c20909b13d71c4923a90967f74b">hasVGPRIndexMode</a>.</p>

</div>
</div>

### HasVMEMtoScalarWriteHazard {#ad79687b8f51d5052254be71401ac0e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasVMEMtoScalarWriteHazard = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa45af2117c2e8ab325c59f997e818f90">hasVMEMtoScalarWriteHazard</a>.</p>

</div>
</div>

### HasVmemWriteVgprInOrder {#ae8d0d64b0d9f819c3246745e07e169c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasVmemWriteVgprInOrder = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a263599c932efbe43f310b3924533ddad">hasVmemWriteVgprInOrder</a>.</p>

</div>
</div>

### HasVOP3Literal {#a9a0feafb29b5f1d0c3e1a237f464ed3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasVOP3Literal = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#acfa61def62c3f39edaec6b28782f1992">hasVOP3Literal</a>.</p>

</div>
</div>

### HasVOPDInsts {#a6e2fb1b650236a6b1e2c80801da4285e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasVOPDInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#acc70c2a79f18b7d4cb774ae93df8c548">hasVOPDInsts</a>.</p>

</div>
</div>

### HasVscnt {#a336cc2253badbe67950bd9fbb65fee57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasVscnt = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a5458eb4f0d6001441653d15f37e101c2">hasVscnt</a>.</p>

</div>
</div>

### HasXF32Insts {#a1c8c4bbe976a53a477668131c2a965c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::HasXF32Insts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a5bafa8f44616aca18624d36db7061d36">hasXF32Insts</a>.</p>

</div>
</div>

### InstrItins {#a01b60a82cd5066b5e1d29757a80965ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrItineraryData llvm::GCNSubtarget::InstrItins</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#acf1aa5ffc0b59dd205f5dc5142580771">GCNSubtarget</a> and <a href="#a38931c46f7a692029325e4dcdb3ca35c">getInstrItineraryData</a>.</p>

</div>
</div>

### KernargPreload {#a3ea5e2eef6d396268f0b354c3c5ead45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::KernargPreload = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a4c1fca26ad6a387a03e4649095b7cdc7">hasKernargPreload</a>.</p>

</div>
</div>

### LDSBankCount {#a61d64bc81257fe4f2c899dc26a9c1660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::GCNSubtarget::LDSBankCount = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a0cfaf858a04f4c55a92005ab1ee5694c">getLDSBankCount</a> and <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### LDSMisalignedBug {#a1980c0b9e254aaf640a1b11b37a077c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::LDSMisalignedBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a58b73e7766fb13e9033b8cc011e5d3ea">hasLDSMisalignedBug</a>.</p>

</div>
</div>

### MaxHardClauseLength {#ab8297b266634f159ee9c659cb5467b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::MaxHardClauseLength = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum number of instructions that may be placed within an S_CLAUSE, which is one greater than the maximum argument to S_CLAUSE.</p>


<p>A value of 0 indicates a lack of S_CLAUSE support.</p>


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a567e40fa5e04cc7a032e60e66044f470">hasHardClauses</a> and <a href="#a5c2b42a3405b2b4cb009beb1802caa32">maxHardClauseLength</a>.</p>

</div>
</div>

### MaxPrivateElementSize {#a18efbf5a73b167d005a9d1004816ab00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSubtarget::MaxPrivateElementSize = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa1c8834f883c6607231b902a1f37ddbc">getMaxPrivateElementSize</a> and <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### MIMG\_R128 {#a7ca7cf17cde165669ca2d983800d3701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::MIMG_R128 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ab10ebfbc9a9e224662e1cc4fa218d5d8">hasMIMG_R128</a>.</p>

</div>
</div>

### NegativeScratchOffsetBug {#a2e15f45c8391c4606bf56f4cfc3be19d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::NegativeScratchOffsetBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a31e93bb82e5ea95995efb52febbe0d8f">hasNegativeScratchOffsetBug</a>.</p>

</div>
</div>

### NegativeUnalignedScratchOffsetBug {#a56675b4857e4f3f36f3aacbfc1e8f188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::NegativeUnalignedScratchOffsetBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa727d0bfbc501329be7c48c86d8bdb8c">hasNegativeUnalignedScratchOffsetBug</a>.</p>

</div>
</div>

### RequiresCOV6 {#adc9aba4af084a7e0c89b55c62f8367d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::RequiresCOV6 = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#afd17b1239dc4bc597ba3b9fa0c54c6f0">requiresCodeObjectV6</a>.</p>

</div>
</div>

### ScalarFlatScratchInsts {#ae4849ecfc6c6ef25d717ef19e6e40c2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::ScalarFlatScratchInsts = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a70afc9ab29667211c70055c992d1c797">hasScalarFlatScratchInsts</a>.</p>

</div>
</div>

### ScalarizeGlobal {#a4f5630510fbbd84621962f555f9d697e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::ScalarizeGlobal = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a87235fdebcb88e0c5646333d222dca22">getScalarizeGlobalBehavior</a> and <a href="#a21e48d4c68f1e7530e0381bb9e45f0a4">setScalarizeGlobalBehavior</a>.</p>

</div>
</div>

### SGPRInitBug {#ad88ed5e21bdfe4710afa3fdd33981617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::SGPRInitBug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a463d4dd9c6577a21b6edd9879d013113">hasSGPRInitBug</a>.</p>

</div>
</div>

### SupportsSRAMECC {#afd24222e78eeb62e9c800bfd2ccf6af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::SupportsSRAMECC = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### SupportsXNACK {#a7f862392eb42d48e0ca0222d3d17ccb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::SupportsXNACK = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### TargetID {#afc6af409114a5e2da7bc8bedf9024cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPU::IsaInfo::AMDGPUTargetID llvm::GCNSubtarget::TargetID</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a596080bfe7eb1bc232a7c9381a5e784c">d16PreservesUnusedBits</a>, <a href="#acf1aa5ffc0b59dd205f5dc5142580771">GCNSubtarget</a>, <a href="#a6f4d618b8e68e3ec2216c10bf66a18d1">getTargetID</a>, <a href="#a716b165edca27031ffb7a20ea48e41e3">initializeSubtargetDependencies</a> and <a href="#ad0dd54f1f3e1eb169b00651cd3d61da6">isXNACKEnabled</a>.</p>

</div>
</div>

### TargetTriple {#aeb1761721d270309e56a4643963971c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::GCNSubtarget::TargetTriple</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#acf1aa5ffc0b59dd205f5dc5142580771">GCNSubtarget</a>.</p>

</div>
</div>

### TrapHandler {#addf1e5060c2765ecd0a10ff16a1d44e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::TrapHandler = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a83c4915f87ee24cf4648d46b2a2acf0a">isTrapHandlerEnabled</a>.</p>

</div>
</div>

### UnalignedAccessMode {#abce08ae709e3e15c39e3d8c6dd911af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::UnalignedAccessMode = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#ad8fdf957658ebd74fb9e95adfdb970a4">hasUnalignedAccessMode</a>, <a href="#aa0d885cd49a333e11b7e405ccfc85c6f">hasUnalignedBufferAccessEnabled</a>, <a href="#a2f352f203bb6d6cfd51c652e1c5132ee">hasUnalignedDSAccessEnabled</a> and <a href="#a998c1bf83ee1a55a120212a835e24c08">hasUnalignedScratchAccessEnabled</a>.</p>

</div>
</div>

### UnalignedBufferAccess {#ae99450395d28349fc55c832de8510eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::UnalignedBufferAccess = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a40c81e55bbb2fb239f904617a259befb">hasUnalignedBufferAccess</a> and <a href="#aa0d885cd49a333e11b7e405ccfc85c6f">hasUnalignedBufferAccessEnabled</a>.</p>

</div>
</div>

### UnalignedDSAccess {#a23393a7e958c2933deafa6bc181a0b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::UnalignedDSAccess = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a799cf5bdf244aef0f87065145a5f2c42">hasUnalignedDSAccess</a> and <a href="#a2f352f203bb6d6cfd51c652e1c5132ee">hasUnalignedDSAccessEnabled</a>.</p>

</div>
</div>

### UnalignedScratchAccess {#a9b54a7dcd00a95feec9a76aebca85508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::UnalignedScratchAccess = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a64bb69b998fcff902312ba7d2eb7221c">hasUnalignedScratchAccess</a> and <a href="#a998c1bf83ee1a55a120212a835e24c08">hasUnalignedScratchAccessEnabled</a>.</p>

</div>
</div>

### UserSGPRInit16Bug {#a21359df698891d2466c68d8abf6b4e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::UserSGPRInit16Bug = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="#a5e54f855ac47719c335add94e8a6620a">hasUserSGPRInit16Bug</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallLoweringInfo {#a126b2f0a4a2e4bc3be7130db37c62ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AMDGPUCallLowering&gt; llvm::GCNSubtarget::CallLoweringInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GlobalISel related APIs.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### FrameLowering {#aa2df337990e050abf3f1d519ace488b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIFrameLowering llvm::GCNSubtarget::FrameLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### InlineAsmLoweringInfo {#a15401ed0f02863f15eab262efeb2c7bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InlineAsmLowering&gt; llvm::GCNSubtarget::InlineAsmLoweringInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### InstrInfo {#ae85b6a0d300c4e5b17e94e435aa5ba1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIInstrInfo llvm::GCNSubtarget::InstrInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### InstSelector {#acb5d4e2741c989c4d060720daada3939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InstructionSelector&gt; llvm::GCNSubtarget::InstSelector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### Legalizer {#a343fe5061c158c9bb4f5b1acd99c99e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LegalizerInfo&gt; llvm::GCNSubtarget::Legalizer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### RegBankInfo {#a37b78383688c7c6c8418c0ae4b7502ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AMDGPURegisterBankInfo&gt; llvm::GCNSubtarget::RegBankInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### TLInfo {#a674436c891b2c5dfb22af7e8248db8a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SITargetLowering llvm::GCNSubtarget::TLInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### TSInfo {#af1a0559113c7cfec0bc93c7a6cb73f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const SelectionDAGTargetInfo&gt; llvm::GCNSubtarget::TSInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> related APIs.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hasHalfRate64Ops() {#ac9e9894ed5c61d2bba376dc93961bd71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSubtarget::hasHalfRate64Ops (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 991 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusubtarget-h">AMDGPUSubtarget.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
