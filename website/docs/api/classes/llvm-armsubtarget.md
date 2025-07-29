---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armsubtarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARMSubtarget` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ARMSubtarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">Target/ARM/ARMSubtarget.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/armgensubtargetinfo">ARMGenSubtargetInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ARMProcFamilyEnum { <a href="#a1f30745dc0351a55935d08768ad5471f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ARMProcClassEnum { <a href="#a043911b5c0dbf63092e5e31dd3a44350">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ARMArchEnum { <a href="#aa55a2803a7e70b3cee33cb7951bb162e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ARMLdStMultipleTiming { <a href="#ac7324b67d7e3be270177e6590f0bb1e5">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>What kind of timing do load multiple/store multiple instructions have. <a href="#ac7324b67d7e3be270177e6590f0bb1e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PushPopSplitVariation { <a href="#ab3f7c70dd539567001e35caea74ade4b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How the push and pop instructions of callee saved general-purpose registers should be split. <a href="#ab3f7c70dd539567001e35caea74ade4b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a> (const Triple &amp;TT, const std::string &amp;CPU, const std::string &amp;FS, const ARMBaseTargetMachine &amp;TM, bool IsLittle, bool MinSize=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor initializes the data members to match that of the specified triple. <a href="#a16350880c9e7c3b3c6f960644b0abd6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6956835a06343b455ce7ddc93338e68d">isCortexA5</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08caeec4314d2a3983d98789d7559e80">isCortexA7</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac43b07f1b3f6ed64f7bfc6d864bd7465">isCortexA8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a27a74eec3db7120b851ebc2d98b33">isCortexA9</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad22a711cea737ea6b5fd7cada552e049">isCortexA15</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eef6de6958d76e6b151164c5b419650">isSwift</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcc3f0c87647ca51e1e66789f21e5c3f">isCortexM3</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bd3b2c686ea4cbf7d14e3f5c17ad0dd">isCortexM55</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345f83983694394198f7fd0cbd01263f">isCortexM7</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ab5747677e158d871483a440f2ffcca">isCortexM85</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60117a5fbb52ea9f70b5015e7740f7ca">isLikeA9</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ec2e41ef180b9e32a9cb810db27071">isCortexR5</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67cb506ce9fe0e6a5441cbe784397c73">isKrait</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819d13e401dbf1301acb495576c812c3">getMaxInlineSizeThreshold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMaxInlineSizeThreshold - Returns the maximum memset / memcpy size that still makes it profitable to inline the call. <a href="#a819d13e401dbf1301acb495576c812c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77f8d562867710b25b1202aa703ad2ce">getMaxMemcpyTPInlineSizeThreshold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMaxMemcpyTPInlineSizeThreshold - Returns the maximum size that still makes it profitable to inline a llvm.memcpy as a Tail Predicated loop. <a href="#a77f8d562867710b25b1202aa703ad2ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaea1baccb33d11d647a906dd1ae5e76">ParseSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options. <a href="#acaea1baccb33d11d647a906dd1ae5e76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab350a605a0177796108c2364c678ccdb">initializeSubtargetDependencies</a> (StringRef CPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>initializeSubtargetDependencies - Initializes using a CPU and feature string so that we can use initializer lists for subtarget initialization. <a href="#ab350a605a0177796108c2364c678ccdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo">ARMSelectionDAGInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aad2949e49d1a27a2294fa15d0016cc">getSelectionDAGInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo">ARMBaseInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e1a46e82adb0b55dc3fa6dd15c8984">getInstrInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering">ARMTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47487469642dbc444927b5e2f5f22ba2">getTargetLowering</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armframelowering">ARMFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afefee6690d33aad93d701ffebf6fecc8">getFrameLowering</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo">ARMBaseRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628369d8ea7ff61dc2202e6aa147155c">getRegisterInfo</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7235be90dc59a51a6bb25bd8827144f">getCallLowering</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c3b13f075bc8f93ee480941b2318bfd">getInstructionSelector</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb6ef96fd0574f7a6225ceee6cb63081">getLegalizerInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204ddbcb57192f931789f22e835aa26e">getRegBankInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18ff0b01bdb57bf15f1879917450bba6">hasARMOps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf250d4cc8d087660064261ee727a9f">useNEONForSinglePrecisionFP</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a8b4e2c26c2c0aad751c5bf296858c6">hasVFP2Base</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dafebdd8729d3f5b64ea61d8bdcc650">hasVFP3Base</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f6489afbec421c829ed918b777abe53">hasVFP4Base</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352126476d5cd9d9930030f261203074">hasFPARMv8Base</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbbb330e8817f52f88262fac3e887600">hasAnyDataBarrier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af08fd693b813f5df7880bfee47fb24a8">useMulOps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a9a6d8b7443a4500a4f6e0758847113">useFPVMLx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30cfb7b9ae6531d4ab27e6ea0995c053">useFPVFMx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4772b23bccc0e8235027510b6d6c5b0">useFPVFMx16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91a737d59f7b36ae704dab9be3c359f5">useFPVFMx64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a499dae244f5b646551e74460a354060c">useSjLjEH</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46dd3406fa0822bf0dd24b0e068a1469">hasBaseDSP</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a1c2676e9eb103fa0263a709d80764">hasFusion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the CPU supports any kind of instruction fusion. <a href="#a06a1c2676e9eb103fa0263a709d80764">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e33acc8570da51f655ba63ac62e2a21">getTargetTriple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60b8559634130214660d6f0270369838">isTargetDarwin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab72e4138f74d00bef2662c937b4feb98">isTargetIOS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2802f820d033f21552997521d832903">isTargetWatchOS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda7127aefed4c41b1aee1143325191e">isTargetWatchABI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf1c6825852c8e24775a39c347aab406">isTargetDriverKit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc1b5e30ed9bf38be74c079ac97b2f44">isTargetLinux</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc057142d9cff01f1e8a6e6d64c0b082">isTargetNaCl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98eb945133f19e22752163b6d1030d36">isTargetNetBSD</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f058939ca1c84b29fba5c96ff4a0f02">isTargetWindows</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cb6c1cd7f4f7a9e971b6bd9fe5888fc">isTargetCOFF</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af12f0426ec29a607f20c3fd5164c5f28">isTargetELF</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0456a35c1b666bd1b89defc942aed435">isTargetMachO</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ce652b063221a5f090015a29a78781">isTargetAEABI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a890bfc321e0be900181291cc6e0a5d5e">isTargetGNUAEABI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada748952ed0b0e22d2903f74f4bc44e4">isTargetMuslAEABI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b5d7e697776edc0052281f59e05f87">isTargetEHABICompatible</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9cc9ded3318f987b2d3a623a4ae584">isTargetHardFloat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38b67bc95d128a7f872bda14b3ce1945">isReadTPSoft</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7037b3527a86ebfdee2382de62fcfd2e">isTargetAndroid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4a9faae0101445ec286f433ec4e2629">isXRaySupported</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ff14194f77a2cd0afb651a97acf27f">isAPCS_ABI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b122c9e993cea45116667c05e04988">isAAPCS_ABI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bda6b04debe6e44dc3f255e069c01e8">isAAPCS16_ABI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a717186a2492b294d33a8a33fd85be6bf">isROPI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a88643e75be7b1d422605b591ab291">isRWPI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b49699b3961f3ffc391633d3d975de">useMachineScheduler</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc59368a716c973ff5601a7e27bed962">useMachinePipeliner</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae326d7c694f98af61c453f4a9a5098a">hasMinSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dc8447e2cf1376dbeebf919c0cddc9a">isThumb1Only</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a366b7fda111b63c2bf86c1b81a9cc362">isThumb2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae477aca96efeb96f5ad038393073a70c">isMClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2705f3ce479c934bc57a03188d949cc7">isRClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35da413e7feffe5fcdf1cbbded5fd08c">isAClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90763d262e1a8ae31f254f901a105c06">isR9Reserved</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d0de6c30c8e5b1342e3f238e765221c">getFramePointerReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#ab3f7c70dd539567001e35caea74ade4b">PushPopSplitVariation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aada6bb4af36a2736480f0c51fced2d58">getPushPopSplitVariation</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63af308efea4b9571d7a8aaf419fa2ee">useStride4VFPs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d600261ff016d44ce2c769ba0726224">useMovt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a9091351224b05c4bc72baa2ae1914f">supportsTailCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5c4b25ea5c8e4051a1a82170f7dd4c2">allowsUnalignedMem</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb3dca30645bc25c91679fa0b7c8b3bf">restrictIT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb8ca7757251436e96910fa926b168c">getCPUString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad581715436b127116b9bc9a1fffa8665">isLittle</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f7d9339ba6fd6b1cd9dedc400378355">getMispredictionPenalty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b31f085b2d49f1fccf00f5109307a51">enableMachineScheduler</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if machine scheduler should be enabled. <a href="#a5b31f085b2d49f1fccf00f5109307a51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c115385fe95b53102bbfceb5d70e3a3">enableMachinePipeliner</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if machine pipeliner should be enabled. <a href="#a7c115385fe95b53102bbfceb5d70e3a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383625e4ecded16fd5bfed6c69a8130d">useDFAforSMS</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1531f96825254c3ef8b1b9272894290f">enablePostRAScheduler</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True for some subtargets at &gt; -O0. <a href="#a1531f96825254c3ef8b1b9272894290f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cad87ded3b08ef87a178e7189c084c5">enablePostRAMachineScheduler</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True for some subtargets at &gt; -O0. <a href="#a7cad87ded3b08ef87a178e7189c084c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41f0a90bcbd2fdd8a141ca48a8f05810">enableSubRegLiveness</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this subtarget wants to use subregister liveness. <a href="#a41f0a90bcbd2fdd8a141ca48a8f05810">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de349696d146aa1d3af80b3470ae6f4">useAA</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable use of alias analysis during code generation (during MI scheduling, DAGCombine, etc.). <a href="#a6de349696d146aa1d3af80b3470ae6f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc865dab96e62f0620415c26ef9daf4a">getInstrItineraryData</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getInstrItins - Return the instruction itineraries based on subtarget selection. <a href="#abc865dab96e62f0620415c26ef9daf4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66662d23168fc7ef438ee5e05366bae1">getStackAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStackAlignment - Returns the minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function for this subtarget. <a href="#a66662d23168fc7ef438ee5e05366bae1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4fd5764047f64c7a2fc0bea16a0645">getDualLoadStoreAlignment</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d67f7585b636734bd556a436b109a9c">getMaxInterleaveFactor</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94a1e306f6a8f058fa1174c78eab41d4">getPartialUpdateClearance</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac7324b67d7e3be270177e6590f0bb1e5">ARMLdStMultipleTiming</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a288ce2c947e6872de3578a3a431ac880">getLdStMultipleTiming</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0ab8fda6506b4c85c9c41ac9695604a">getPreISelOperandLatencyAdjustment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43deb1b2c2e73ff4adac8e70e91b672b">isGVIndirectSymbol</a> (const GlobalValue *GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the GV will be accessed via an indirect symbol. <a href="#a43deb1b2c2e73ff4adac8e70e91b672b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb09db483ec58bc265994fd4924592d5">isGVInGOT</a> (const GlobalValue *GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the constant pool modifier needed to access the GV. <a href="#abb09db483ec58bc265994fd4924592d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02f4499189ec049069fb68de00a7b551">useFastISel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if fast-isel is used. <a href="#a02f4499189ec049069fb68de00a7b551">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ef9b30db7ac5f303c9b692188e0308">getReturnOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the correct return opcode for the current feature set. <a href="#a65ef9b30db7ac5f303c9b692188e0308">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb55ae4a6dd8e8e5b6b631a348f927b">allowPositionIndependentMovt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow movt+movw for PIC global address calculation. <a href="#abfb55ae4a6dd8e8e5b6b631a348f927b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa61c4bf89ca23382c1b6776fb739ee46">getPreferBranchLogAlignment</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdce0e5134718d45046f01f8f26a4ea8">getMVEVectorCostFactor</a> (TargetTransformInfo::TargetCostKind CostKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a5ef234051f5fe582e5fa53d655d3d9">ignoreCSRForAllocationOrder</a> (const MachineFunction &amp;MF, MCRegister PhysReg) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20228b431bb0e2852055ea7815a46743">getGPRAllocationOrder</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91f9da5266c84d3e62a97d689e77cfd2">initializeEnvironment</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b396ebaa226b66f2cc60068f9bfc578">initSubtargetFeatures</a> (StringRef CPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armframelowering">ARMFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1168b68c2a5e4f6e9307aa361f829842">initializeFrameLowering</a> (StringRef CPU, StringRef FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f30745dc0351a55935d08768ad5471f">ARMProcFamilyEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a> = <a href="#a1f30745dc0351a55935d08768ad5471faeb05712cf7ca7c7cdb51e33fc266a5b3">Others</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ARMProcFamily - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> processor family: Cortex-A8, Cortex-A9, and others. <a href="#a305f7bdd75fb674c665306eed2a6dcde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a043911b5c0dbf63092e5e31dd3a44350">ARMProcClassEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392ec2cf3b1f4eb78b8fb83588b32d59">ARMProcClass</a> = <a href="#a043911b5c0dbf63092e5e31dd3a44350a4dd2edaabfdcef503954040697f7cc92">None</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ARMProcClass - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> processor class: None, AClass, RClass or MClass. <a href="#a392ec2cf3b1f4eb78b8fb83588b32d59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa55a2803a7e70b3cee33cb7951bb162e">ARMArchEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3282354eb8d2ae94ce6b9d004c39f9da">ARMArch</a> = ARMv4t</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ARMArch - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> architecture. <a href="#a3282354eb8d2ae94ce6b9d004c39f9da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac598e25a4489f49f0edcfd929e0fedd4">UseMulOps</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UseMulOps - True if non-microcoded fused integer multiply-add and multiply-subtract instructions should be used. <a href="#ac598e25a4489f49f0edcfd929e0fedd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae97e07d14d7e5aec61a9f299f9793036">SupportsTailCall</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SupportsTailCall - True if the OS supports tail call. <a href="#ae97e07d14d7e5aec61a9f299f9793036">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ffddf9935139cf113d2a4b43173bc0">RestrictIT</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RestrictIT - If true, the subtarget disallows generation of complex IT blocks. <a href="#a65ffddf9935139cf113d2a4b43173bc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef1ab2ddea61481fc5d146420e6a736">UseSjLjEH</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UseSjLjEH - If true, the target uses SjLj exception handling (e.g. iOS). <a href="#a1ef1ab2ddea61481fc5d146420e6a736">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7349230a719441eff31e1c8651ae9e21">stackAlignment</a> = <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(4)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>stackAlignment - The minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function. <a href="#a7349230a719441eff31e1c8651ae9e21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e77a418bcc57002a5041ac7c98ddcb2">CPUString</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CPUString - String name of used CPU. <a href="#a4e77a418bcc57002a5041ac7c98ddcb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2087132740838f877daf6cf7e33ce756">MaxInterleaveFactor</a> = 1</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7afee8c81c6cada000d6ed7e3b7f2044">PartialUpdateClearance</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clearance before partial register updates (in number of instructions) <a href="#a7afee8c81c6cada000d6ed7e3b7f2044">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac7324b67d7e3be270177e6590f0bb1e5">ARMLdStMultipleTiming</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a154d5066ba40a202a471928dd415c9c2">LdStMultipleTiming</a> = <a href="#ac7324b67d7e3be270177e6590f0bb1e5a4036c7f30f9ea851473b06416cbbc160">SingleIssue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>What kind of timing do load multiple/store multiple have (double issue, single issue etc). <a href="#a154d5066ba40a202a471928dd415c9c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec40a1e3aa8d47e424dd1db21dfbbce0">PreISelOperandLatencyAdjustment</a> = 2</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The adjustment that we need to apply to get the operand latency from the operand cycle returned by the itinerary data for pre-ISel operands. <a href="#aec40a1e3aa8d47e424dd1db21dfbbce0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f95e07b0b688a534dfae30619946d55">PreferBranchLogAlignment</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>What alignment is preferred for loop bodies and functions, in log2(bytes). <a href="#a4f95e07b0b688a534dfae30619946d55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44372fedd70001a500198ddf6f28edc3">MVEVectorCostFactor</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost factor for MVE instructions, representing the multiple beats an. <a href="#a44372fedd70001a500198ddf6f28edc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6551f0a9aa4e4f8b96dcc6961b337cd9">OptMinSize</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptMinSize - True if we're optimising for minimum code size, equal to the function attribute. <a href="#a6551f0a9aa4e4f8b96dcc6961b337cd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a1a6e0eefe6c7dc18a625e2e8514143">IsLittle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsLittle - The target is Little Endian. <a href="#a0a1a6e0eefe6c7dc18a625e2e8514143">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TargetTriple - What processor and OS we're targeting. <a href="#a5869c3a07ea856e0df85ac190af3c02e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cd3222767747226351eebf8488f74c2">SchedModel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SchedModel - Processor specific instruction costs. <a href="#a4cd3222767747226351eebf8488f74c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b68a81d2aae79d68d64fac49cbe252">InstrItins</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Selected instruction itineraries (one entry per itinerary class.) <a href="#a62b68a81d2aae79d68d64fac49cbe252">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5c330415d1cbbde2aff5b41aca13880">Options</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Options passed via command line that could influence the target. <a href="#ac5c330415d1cbbde2aff5b41aca13880">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine">ARMBaseTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24d45118cad8c395285772b053965420">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo">ARMSelectionDAGInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88dfb82b099834fc01fb3c7d39fe1a08">TSInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/armframelowering">ARMFrameLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a726f90af68504309411d8b85cdcb04">FrameLowering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo">ARMBaseInstrInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae99c5469461e3b46d87e209256e93dc8">InstrInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armtargetlowering">ARMTargetLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a0e988e0dfe8be49b5e130548ea9da">TLInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab59db205e0e515e0aead0c30185ba704">CallLoweringInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GlobalISel related APIs. <a href="#ab59db205e0e515e0aead0c30185ba704">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3de60ce476ea6dac316afa70e1a0f80">InstSelector</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e9edff4d610e3ee955f18db5ee0023">Legalizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9c154d5cd0c66895353d4e1b1781371">RegBankInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::bitset&lt; 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318a6a58de5b0a04ebdae9a9edece3e7">CoprocCDE</a> = {}</td>
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


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ARMArchEnum {#aa55a2803a7e70b3cee33cb7951bb162e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMSubtarget::ARMArchEnum </td>
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


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### ARMLdStMultipleTiming {#ac7324b67d7e3be270177e6590f0bb1e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMSubtarget::ARMLdStMultipleTiming </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>What kind of timing do load multiple/store multiple instructions have.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DoubleIssue<a id="ac7324b67d7e3be270177e6590f0bb1e5a97d6452d484864e16c59e4c1032af8dc"></a></td>
<td class="doxyEnumItemDescription">Can load/store 2 registers/cycle</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DoubleIssueCheckUnalignedAccess<a id="ac7324b67d7e3be270177e6590f0bb1e5a15d56a42a3f8569bb24a0cdc215d9729"></a></td>
<td class="doxyEnumItemDescription">Can load/store 2 registers/cycle, but needs an extra cycle if the access is not 64-bit aligned</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SingleIssue<a id="ac7324b67d7e3be270177e6590f0bb1e5a4036c7f30f9ea851473b06416cbbc160"></a></td>
<td class="doxyEnumItemDescription">Can load/store 1 register/cycle</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SingleIssuePlusExtras<a id="ac7324b67d7e3be270177e6590f0bb1e5aeeb858b21b645dd260c1c4b16ccb5e23"></a></td>
<td class="doxyEnumItemDescription">Can load/store 1 register/cycle, but needs an extra cycle for address computation and potentially also for register writeback</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### ARMProcClassEnum {#a043911b5c0dbf63092e5e31dd3a44350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMSubtarget::ARMProcClassEnum </td>
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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="a043911b5c0dbf63092e5e31dd3a44350a4dd2edaabfdcef503954040697f7cc92"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AClass<a id="a043911b5c0dbf63092e5e31dd3a44350a134f3d9cf5c9532aea332c7fb8c82842"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MClass<a id="a043911b5c0dbf63092e5e31dd3a44350a6bf2cd4495916d9da1be2f52f58cc05d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RClass<a id="a043911b5c0dbf63092e5e31dd3a44350a76c12ac5ad54f8afe626c73709ae53a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### ARMProcFamilyEnum {#a1f30745dc0351a55935d08768ad5471f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMSubtarget::ARMProcFamilyEnum </td>
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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Others<a id="a1f30745dc0351a55935d08768ad5471faeb05712cf7ca7c7cdb51e33fc266a5b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### PushPopSplitVariation {#ab3f7c70dd539567001e35caea74ade4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMSubtarget::PushPopSplitVariation </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How the push and pop instructions of callee saved general-purpose registers should be split.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoSplit<a id="ab3f7c70dd539567001e35caea74ade4bafba6217ab4616d2f03a247754157ed96"></a></td>
<td class="doxyEnumItemDescription">All GPRs can be pushed in a single instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SplitR7<a id="ab3f7c70dd539567001e35caea74ade4ba5ba862e3a9b6eca2a66b539bd990761c"></a></td>
<td class="doxyEnumItemDescription">R7 and LR must be adjacent, because R7 is the frame pointer, and must point to a frame record consisting of the previous frame pointer and the return address</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SplitR11WindowsSEH<a id="ab3f7c70dd539567001e35caea74ade4ba2fba6120097ea9615c4a13a82fe8042d"></a></td>
<td class="doxyEnumItemDescription">When the stack frame size is not known (because of variable-sized objects or realignment), Windows SEH requires the callee-saved registers to be stored in three regions, with R11 and LR below the floating-point registers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SplitR11AAPCSSignRA<a id="ab3f7c70dd539567001e35caea74ade4ba79139b30a7b6a6caf15fe7c26898cb1c"></a></td>
<td class="doxyEnumItemDescription">When generating AAPCS-compilant frame chains, R11 is the frame pointer, and must be pushed adjacent to the return address (LR)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ARMSubtarget() {#a16350880c9e7c3b3c6f960644b0abd6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMSubtarget::ARMSubtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; CPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine">ARMBaseTargetMachine</a> &amp; TM, bool IsLittle, bool MinSize=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This constructor initializes the data members to match that of the specified triple.</p>

<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="#a4e77a418bcc57002a5041ac7c98ddcb2">CPUString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1b5635f4f0c8888f850fccb4769d8bff">llvm::createARMInstructionSelector</a>, <a href="#a628369d8ea7ff61dc2202e6aa147155c">getRegisterInfo</a>, <a href="#a47487469642dbc444927b5e2f5f22ba2">getTargetLowering</a>, <a href="#a0a1a6e0eefe6c7dc18a625e2e8514143">IsLittle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>, <a href="#a2dc8447e2cf1376dbeebf919c0cddc9a">isThumb1Only</a>, <a href="#ac5c330415d1cbbde2aff5b41aca13880">Options</a>, <a href="#a6551f0a9aa4e4f8b96dcc6961b337cd9">OptMinSize</a>, <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>, <a href="#a24d45118cad8c395285772b053965420">TM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a29aeb362090e8b5d8b19dbc92c4fb0d7">UseFusedMulOps</a> and <a href="#ac598e25a4489f49f0edcfd929e0fedd4">UseMulOps</a>.</p>


<p>Referenced by <a href="#ab350a605a0177796108c2364c678ccdb">initializeSubtargetDependencies</a> and <a href="#acaea1baccb33d11d647a906dd1ae5e76">ParseSubtargetFeatures</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### isCortexA15() {#ad22a711cea737ea6b5fd7cada552e049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isCortexA15 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a>.</p>


<p>Referenced by <a href="#a60117a5fbb52ea9f70b5015e7740f7ca">isLikeA9</a>.</p>

</div>
</div>

### isCortexA5() {#a6956835a06343b455ce7ddc93338e68d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isCortexA5 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>These functions are obsolete, please consider adding subtarget features or properties instead of calling them.</p>


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a>.</p>

</div>
</div>

### isCortexA7() {#a08caeec4314d2a3983d98789d7559e80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isCortexA7 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a3ab21c6ee9d6c29942b0bb3e7f2c2806">adjustDefLatency</a>.</p>

</div>
</div>

### isCortexA8() {#ac43b07f1b3f6ed64f7bfc6d864bd7465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isCortexA8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a3ab21c6ee9d6c29942b0bb3e7f2c2806">adjustDefLatency</a>.</p>

</div>
</div>

### isCortexA9() {#ae3a27a74eec3db7120b851ebc2d98b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isCortexA9 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a>.</p>


<p>Referenced by <a href="#a60117a5fbb52ea9f70b5015e7740f7ca">isLikeA9</a>.</p>

</div>
</div>

### isCortexM3() {#abcc3f0c87647ca51e1e66789f21e5c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isCortexM3 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a>.</p>

</div>
</div>

### isCortexM55() {#a5bd3b2c686ea4cbf7d14e3f5c17ad0dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isCortexM55 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a>.</p>

</div>
</div>

### isCortexM7() {#a345f83983694394198f7fd0cbd01263f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isCortexM7 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a>.</p>

</div>
</div>

### isCortexM85() {#a2ab5747677e158d871483a440f2ffcca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isCortexM85 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a>.</p>

</div>
</div>

### isCortexR5() {#a41ec2e41ef180b9e32a9cb810db27071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isCortexR5 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a>.</p>

</div>
</div>

### isKrait() {#a67cb506ce9fe0e6a5441cbe784397c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isKrait ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a>.</p>


<p>Referenced by <a href="#a60117a5fbb52ea9f70b5015e7740f7ca">isLikeA9</a>.</p>

</div>
</div>

### isLikeA9() {#a60117a5fbb52ea9f70b5015e7740f7ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isLikeA9 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="#ad22a711cea737ea6b5fd7cada552e049">isCortexA15</a>, <a href="#ae3a27a74eec3db7120b851ebc2d98b33">isCortexA9</a> and <a href="#a67cb506ce9fe0e6a5441cbe784397c73">isKrait</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a3ab21c6ee9d6c29942b0bb3e7f2c2806">adjustDefLatency</a> and <a href="/web-llvm/docs/api/structs/anonymous-mlxexpansionpass-cpp-/mlxexpansion/#a097b0b80206a11244f399de6de333399">anonymous{MLxExpansionPass.cpp}::MLxExpansion::runOnMachineFunction</a>.</p>

</div>
</div>

### isSwift() {#a0eef6de6958d76e6b151164c5b419650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isSwift ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="#a305f7bdd75fb674c665306eed2a6dcde">ARMProcFamily</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca2740493172a4ce246941c8cff95e0f83">llvm::CallingConv::Swift</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a3ab21c6ee9d6c29942b0bb3e7f2c2806">adjustDefLatency</a> and <a href="/web-llvm/docs/api/structs/anonymous-mlxexpansionpass-cpp-/mlxexpansion/#a097b0b80206a11244f399de6de333399">anonymous{MLxExpansionPass.cpp}::MLxExpansion::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allowPositionIndependentMovt() {#abfb55ae4a6dd8e8e5b6b631a348f927b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::allowPositionIndependentMovt ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow movt+movw for PIC global address calculation.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> does not have GOT relocations for movt+movw. ROPI does not use GOT.</p>


<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="#a717186a2492b294d33a8a33fd85be6bf">isROPI</a> and <a href="#af12f0426ec29a607f20c3fd5164c5f28">isTargetELF</a>.</p>

</div>
</div>

### allowsUnalignedMem() {#ad5c4b25ea5c8e4051a1a82170f7dd4c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::allowsUnalignedMem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#aff4fd5764047f64c7a2fc0bea16a0645">getDualLoadStoreAlignment</a>.</p>

</div>
</div>

### enableMachinePipeliner() {#a7c115385fe95b53102bbfceb5d70e3a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::enableMachinePipeliner ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if machine pipeliner should be enabled.</p>

<p>Declaration at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>Reference <a href="#acc59368a716c973ff5601a7e27bed962">useMachinePipeliner</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a9c27deca75181d5b0986eb74bc38a1b1">llvm::ARMBaseInstrInfo::analyzeBranch</a>.</p>

</div>
</div>

### enableMachineScheduler() {#a5b31f085b2d49f1fccf00f5109307a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::enableMachineScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if machine scheduler should be enabled.</p>

<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="#aae326d7c694f98af61c453f4a9a5098a">hasMinSize</a>, <a href="#ae477aca96efeb96f5ad038393073a70c">isMClass</a> and <a href="#ad0b49699b3961f3ffc391633d3d975de">useMachineScheduler</a>.</p>


<p>Referenced by <a href="#a7cad87ded3b08ef87a178e7189c084c5">enablePostRAMachineScheduler</a> and <a href="#a1531f96825254c3ef8b1b9272894290f">enablePostRAScheduler</a>.</p>

</div>
</div>

### enablePostRAMachineScheduler() {#a7cad87ded3b08ef87a178e7189c084c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::enablePostRAMachineScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True for some subtargets at &gt; -O0.</p>

<p>Declaration at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="#a5b31f085b2d49f1fccf00f5109307a51">enableMachineScheduler</a> and <a href="#a2dc8447e2cf1376dbeebf919c0cddc9a">isThumb1Only</a>.</p>

</div>
</div>

### enablePostRAScheduler() {#a1531f96825254c3ef8b1b9272894290f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::enablePostRAScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True for some subtargets at &gt; -O0.</p>

<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="#a5b31f085b2d49f1fccf00f5109307a51">enableMachineScheduler</a> and <a href="#a2dc8447e2cf1376dbeebf919c0cddc9a">isThumb1Only</a>.</p>

</div>
</div>

### enableSubRegLiveness() {#a41f0a90bcbd2fdd8a141ca48a8f05810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::enableSubRegLiveness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this subtarget wants to use subregister liveness.</p>

<p>Declaration at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

### getCallLowering() {#aa7235be90dc59a51a6bb25bd8827144f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallLowering * ARMSubtarget::getCallLowering ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

### getCPUString() {#a8bb8ca7757251436e96910fa926b168c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::ARMSubtarget::getCPUString ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a4e77a418bcc57002a5041ac7c98ddcb2">CPUString</a>.</p>

</div>
</div>

### getDualLoadStoreAlignment() {#aff4fd5764047f64c7a2fc0bea16a0645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::ARMSubtarget::getDualLoadStoreAlignment ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#ad5c4b25ea5c8e4051a1a82170f7dd4c2">allowsUnalignedMem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#adb9776e3c9f8cf35e243fe5585cdafd3">LowerSTORE</a>.</p>

</div>
</div>

### getFrameLowering() {#afefee6690d33aad93d701ffebf6fecc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMFrameLowering * llvm::ARMSubtarget::getFrameLowering ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a8fbe3f2774ccaaf41bd80a092a9f73e5">llvm::ThumbRegisterInfo::eliminateFrameIndex</a>.</p>

</div>
</div>

### getFramePointerReg() {#a3d0de6c30c8e5b1342e3f238e765221c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCPhysReg llvm::ARMSubtarget::getFramePointerReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="#a60b8559634130214660d6f0270369838">isTargetDarwin</a>, <a href="#a3f058939ca1c84b29fba5c96ff4a0f02">isTargetWindows</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#aee75d3e9f0900bee26680be79a90f9a3">llvm::ARMBaseRegisterInfo::canRealignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#ab064b648d7048dcfa869dc4021c54859">llvm::ARMBaseRegisterInfo::getFrameRegister</a>, <a href="#aada6bb4af36a2736480f0c51fced2d58">getPushPopSplitVariation</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a185c9e3a52cfad64d466568e38c70308">llvm::ARMBaseRegisterInfo::getReservedRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#adb3bbd8da3d2794c25c551a779fef663">llvm::ARMBaseRegisterInfo::isInlineAsmReadOnlyReg</a>.</p>

</div>
</div>

### getGPRAllocationOrder() {#a20228b431bb0e2852055ea7815a46743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMSubtarget::getGPRAllocationOrder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a548cfb9440f36ba67fc5566b8e967fc6">llvm::Function::hasMinSize</a>, <a href="#a2dc8447e2cf1376dbeebf919c0cddc9a">isThumb1Only</a> and <a href="#a366b7fda111b63c2bf86c1b81a9cc362">isThumb2</a>.</p>

</div>
</div>

### getInstrInfo() {#a29e1a46e82adb0b55dc3fa6dd15c8984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMBaseInstrInfo * llvm::ARMSubtarget::getInstrInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a8fbe3f2774ccaaf41bd80a092a9f73e5">llvm::ThumbRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a55668c464aef1136badb1b58eeec19c6">emitThumb1LoadConstPool</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#ab8e6b81acb0eec0b1d8ccda6db37697d">llvm::ThumbRegisterInfo::resolveFrameIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-a15sdoptimizer-cpp-/a15sdoptimizer/#a3f35adf953f8bebb2505e841a4349c03">anonymous{A15SDOptimizer.cpp}::A15SDOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armconstantislandpass-cpp-/armconstantislands/#aaf4297850ccff6052205f45bc2ba2f87">anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvetpandvptoptimisationspass-cpp-/mvetpandvptoptimisations/#a583bacd9cc15714c083c599b7e45cbb6">anonymous{MVETPAndVPTOptimisationsPass.cpp}::MVETPAndVPTOptimisations::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvevptblockpass-cpp-/mvevptblock/#ab605a2a73e0835e3eed53af0819582f0">anonymous{MVEVPTBlockPass.cpp}::MVEVPTBlock::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-thumb2itblockpass-cpp-/thumb2itblock/#a5477944b7d70dd3c998b38a43e88f041">anonymous{Thumb2ITBlockPass.cpp}::Thumb2ITBlock::runOnMachineFunction</a>.</p>

</div>
</div>

### getInstrItineraryData() {#abc865dab96e62f0620415c26ef9daf4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItineraryData * llvm::ARMSubtarget::getInstrItineraryData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getInstrItins - Return the instruction itineraries based on subtarget selection.</p>

<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a62b68a81d2aae79d68d64fac49cbe252">InstrItins</a>.</p>

</div>
</div>

### getInstructionSelector() {#a8c3b13f075bc8f93ee480941b2318bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector * ARMSubtarget::getInstructionSelector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

### getLdStMultipleTiming() {#a288ce2c947e6872de3578a3a431ac880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMLdStMultipleTiming llvm::ARMSubtarget::getLdStMultipleTiming ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a154d5066ba40a202a471928dd415c9c2">LdStMultipleTiming</a>.</p>

</div>
</div>

### getLegalizerInfo() {#adb6ef96fd0574f7a6225ceee6cb63081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo * ARMSubtarget::getLegalizerInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

### getMaxInlineSizeThreshold() {#a819d13e401dbf1301acb495576c812c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMSubtarget::getMaxInlineSizeThreshold ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMaxInlineSizeThreshold - Returns the maximum memset / memcpy size that still makes it profitable to inline the call.</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a4d3a29c0e2103ce92ec80ac1f6eee78a">llvm::ARMSelectionDAGInfo::EmitTargetCodeForMemcpy</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armselectiondaginfo-cpp/#a0558cf546b4384bd63343c79e8b9f198">shouldGenerateInlineTPLoop</a>.</p>

</div>
</div>

### getMaxInterleaveFactor() {#a8d67f7585b636734bd556a436b109a9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMSubtarget::getMaxInterleaveFactor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a2087132740838f877daf6cf7e33ce756">MaxInterleaveFactor</a>.</p>

</div>
</div>

### getMaxMemcpyTPInlineSizeThreshold() {#a77f8d562867710b25b1202aa703ad2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMSubtarget::getMaxMemcpyTPInlineSizeThreshold ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMaxMemcpyTPInlineSizeThreshold - Returns the maximum size that still makes it profitable to inline a llvm.memcpy as a Tail Predicated loop.</p>


<p>This threshold should only be used for constant size inputs.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armselectiondaginfo-cpp/#a0558cf546b4384bd63343c79e8b9f198">shouldGenerateInlineTPLoop</a>.</p>

</div>
</div>

### getMispredictionPenalty() {#a4f7d9339ba6fd6b1cd9dedc400378355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMSubtarget::getMispredictionPenalty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>Reference <a href="#a4cd3222767747226351eebf8488f74c2">SchedModel</a>.</p>

</div>
</div>

### getMVEVectorCostFactor() {#afdce0e5134718d45046f01f8f26a4ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMSubtarget::getMVEVectorCostFactor (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TargetTransformInfo::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="#a44372fedd70001a500198ddf6f28edc3">MVEVectorCostFactor</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba737cfc93e5a2ff961677d57186167e7c">llvm::TargetTransformInfo::TCK_CodeSize</a>.</p>

</div>
</div>

### getPartialUpdateClearance() {#a94a1e306f6a8f058fa1174c78eab41d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMSubtarget::getPartialUpdateClearance ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a7afee8c81c6cada000d6ed7e3b7f2044">PartialUpdateClearance</a>.</p>

</div>
</div>

### getPreferBranchLogAlignment() {#aa61c4bf89ca23382c1b6776fb739ee46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMSubtarget::getPreferBranchLogAlignment ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a4f95e07b0b688a534dfae30619946d55">PreferBranchLogAlignment</a>.</p>

</div>
</div>

### getPreISelOperandLatencyAdjustment() {#ad0ab8fda6506b4c85c9c41ac9695604a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARMSubtarget::getPreISelOperandLatencyAdjustment ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#aec40a1e3aa8d47e424dd1db21dfbbce0">PreISelOperandLatencyAdjustment</a>.</p>

</div>
</div>

### getPushPopSplitVariation() {#aada6bb4af36a2736480f0c51fced2d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMSubtarget::PushPopSplitVariation ARMSubtarget::getPushPopSplitVariation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aa56ae8efa388a7840c07b61e6a03b33e">llvm::TargetOptions::FramePointerIsReserved</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="#a3d0de6c30c8e5b1342e3f238e765221c">getFramePointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afb72c5626afbc815284e2b26bb0663f8">llvm::TargetMachine::getMCAsmInfo</a>, <a href="#a628369d8ea7ff61dc2202e6aa147155c">getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="#a2dc8447e2cf1376dbeebf919c0cddc9a">isThumb1Only</a>, <a href="#ab3f7c70dd539567001e35caea74ade4bafba6217ab4616d2f03a247754157ed96">NoSplit</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a7f7b602a20180dd5d46065c354ae9902">llvm::ARMFunctionInfo::shouldSignReturnAddress</a>, <a href="#ab3f7c70dd539567001e35caea74ade4ba79139b30a7b6a6caf15fe7c26898cb1c">SplitR11AAPCSSignRA</a>, <a href="#ab3f7c70dd539567001e35caea74ade4ba2fba6120097ea9615c4a13a82fe8042d">SplitR11WindowsSEH</a>, <a href="#ab3f7c70dd539567001e35caea74ade4ba5ba862e3a9b6eca2a66b539bd990761c">SplitR7</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac158349781823fe8ff9e02d3a3533d55">llvm::MCAsmInfo::usesWindowsCFI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a8ae827683289cd88fddbe641f8608b9b">llvm::ARMBaseRegisterInfo::getCalleeSavedRegs</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a91f8cc6b8028d57ce1153c7d36c5cc92">getMaxFPOffset</a>.</p>

</div>
</div>

### getRegBankInfo() {#a204ddbcb57192f931789f22e835aa26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo * ARMSubtarget::getRegBankInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

### getRegisterInfo() {#a628369d8ea7ff61dc2202e6aa147155c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMBaseRegisterInfo * llvm::ARMSubtarget::getRegisterInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a3f2267000e9691f1bd4584f4eb4e0cc4">llvm::Thumb1InstrInfo::copyPhysReg</a>, <a href="#aada6bb4af36a2736480f0c51fced2d58">getPushPopSplitVariation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a5c50c1e0000377affb5eec391c213df1">insertSEH</a>, <a href="/web-llvm/docs/api/structs/anonymous-a15sdoptimizer-cpp-/a15sdoptimizer/#a3f35adf953f8bebb2505e841a4349c03">anonymous{A15SDOptimizer.cpp}::A15SDOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvevptblockpass-cpp-/mvevptblock/#ab605a2a73e0835e3eed53af0819582f0">anonymous{MVEVPTBlockPass.cpp}::MVEVPTBlock::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-thumb2itblockpass-cpp-/thumb2itblock/#a5477944b7d70dd3c998b38a43e88f041">anonymous{Thumb2ITBlockPass.cpp}::Thumb2ITBlock::runOnMachineFunction</a>.</p>

</div>
</div>

### getReturnOpcode() {#a65ef9b30db7ac5f303c9b692188e0308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMSubtarget::getReturnOpcode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the correct return opcode for the current feature set.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> BX if available to allow mixing thumb/arm code, but fall back to plain mov pc,lr on ARMv4.</p>


<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#a8aad2949e49d1a27a2294fa15d0016cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMSelectionDAGInfo * llvm::ARMSubtarget::getSelectionDAGInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### getStackAlignment() {#a66662d23168fc7ef438ee5e05366bae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::ARMSubtarget::getStackAlignment ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getStackAlignment - Returns the minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function for this subtarget.</p>

<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a7349230a719441eff31e1c8651ae9e21">stackAlignment</a>.</p>

</div>
</div>

### getTargetLowering() {#a47487469642dbc444927b5e2f5f22ba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMTargetLowering * llvm::ARMSubtarget::getTargetLowering ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#aa71d343a68eaa436458cd76f349f399a">AlignBlocks</a>, <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a3ef56098772bca9a4ca38bf149aa872c">llvm::ARMSelectionDAGInfo::EmitSpecializedLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a8ae827683289cd88fddbe641f8608b9b">llvm::ARMBaseRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#abb9d03a862069b7f3c4f446e0be8b826">llvm::ARMBaseRegisterInfo::getCallPreservedMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1399030f41bb48286cffbbfddb29a3f">PerformXORCombine</a>.</p>

</div>
</div>

### getTargetTriple() {#a1e33acc8570da51f655ba63ac62e2a21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::ARMSubtarget::getTargetTriple ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>

</div>
</div>

### hasAnyDataBarrier() {#acbbb330e8817f52f88262fac3e887600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::hasAnyDataBarrier ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>.</p>

</div>
</div>

### hasARMOps() {#a18ff0b01bdb57bf15f1879917450bba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::hasARMOps ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa4a9faae0101445ec286f433ec4e2629">isXRaySupported</a>.</p>

</div>
</div>

### hasBaseDSP() {#a46dd3406fa0822bf0dd24b0e068a1469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::hasBaseDSP ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af20aaa3827f50046072a07327167aee5">AddCombineTo64BitSMLAL16</a>.</p>

</div>
</div>

### hasFPARMv8Base() {#a352126476d5cd9d9930030f261203074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::hasFPARMv8Base ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### hasFusion() {#a06a1c2676e9eb103fa0263a709d80764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::hasFusion ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the CPU supports any kind of instruction fusion.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### hasMinSize() {#aae326d7c694f98af61c453f4a9a5098a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::hasMinSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a6551f0a9aa4e4f8b96dcc6961b337cd9">OptMinSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a4d3a29c0e2103ce92ec80ac1f6eee78a">llvm::ARMSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="#a5b31f085b2d49f1fccf00f5109307a51">enableMachineScheduler</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a66436eae766ca32356bb075ec31ac449">llvm::tryFoldSPUpdateIntoPushPop</a>.</p>

</div>
</div>

### hasVFP2Base() {#a6a8b4e2c26c2c0aad751c5bf296858c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::hasVFP2Base ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armregisterbankinfo/#af59ec25334715d44d5eecd8568b29e36">llvm::ARMRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a5e55ddeb12d25d6b87b3237661967c62">llvm::ARMBaseRegisterInfo::getSjLjDispatchPreservedMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad09933ec95486d26cd31cf1536190091">isLegalAddressImmediate</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a81f0b427ff9a532ec2b6bf98c132db26">isLegalT2AddressImmediate</a>.</p>

</div>
</div>

### hasVFP3Base() {#a8dafebdd8729d3f5b64ea61d8bdcc650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::hasVFP3Base ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### hasVFP4Base() {#a1f6489afbec421c829ed918b777abe53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::hasVFP4Base ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a30cfb7b9ae6531d4ab27e6ea0995c053">useFPVFMx</a>.</p>

</div>
</div>

### ignoreCSRForAllocationOrder() {#a6a5ef234051f5fe582e5fa53d655d3d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::ignoreCSRForAllocationOrder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a548cfb9440f36ba67fc5566b8e967fc6">llvm::Function::hasMinSize</a> and <a href="#a366b7fda111b63c2bf86c1b81a9cc362">isThumb2</a>.</p>

</div>
</div>

### initializeSubtargetDependencies() {#ab350a605a0177796108c2364c678ccdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMSubtarget &amp; ARMSubtarget::initializeSubtargetDependencies (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>initializeSubtargetDependencies - Initializes using a CPU and feature string so that we can use initializer lists for subtarget initialization.</p>

<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>Reference <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a>.</p>

</div>
</div>

### isAAPCS\_ABI() {#ad0b122c9e993cea45116667c05e04988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::isAAPCS_ABI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102a686afcd1d06fbc117abe52c54c5a3798">llvm::ARMBaseTargetMachine::ARM_ABI_AAPCS</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102af871cdc1efbb58999dd6b201aeb9f28a">llvm::ARMBaseTargetMachine::ARM_ABI_AAPCS16</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102a5db5a8ac18cb47ad6f78ed8b3694b462">llvm::ARMBaseTargetMachine::ARM_ABI_UNKNOWN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a24d45118cad8c395285772b053965420">TM</a>.</p>

</div>
</div>

### isAAPCS16\_ABI() {#a3bda6b04debe6e44dc3f255e069c01e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::isAAPCS16_ABI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102af871cdc1efbb58999dd6b201aeb9f28a">llvm::ARMBaseTargetMachine::ARM_ABI_AAPCS16</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102a5db5a8ac18cb47ad6f78ed8b3694b462">llvm::ARMBaseTargetMachine::ARM_ABI_UNKNOWN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a24d45118cad8c395285772b053965420">TM</a>.</p>

</div>
</div>

### isAClass() {#a35da413e7feffe5fcdf1cbbded5fd08c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isAClass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="#a043911b5c0dbf63092e5e31dd3a44350a134f3d9cf5c9532aea332c7fb8c82842">AClass</a> and <a href="#a392ec2cf3b1f4eb78b8fb83588b32d59">ARMProcClass</a>.</p>

</div>
</div>

### isAPCS\_ABI() {#a90ff14194f77a2cd0afb651a97acf27f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::isAPCS_ABI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102a7424602c00cf8320e081c29111bdeef7">llvm::ARMBaseTargetMachine::ARM_ABI_APCS</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102a5db5a8ac18cb47ad6f78ed8b3694b462">llvm::ARMBaseTargetMachine::ARM_ABI_UNKNOWN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a24d45118cad8c395285772b053965420">TM</a>.</p>

</div>
</div>

### isGVIndirectSymbol() {#a43deb1b2c2e73ff4adac8e70e91b672b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::isGVIndirectSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the GV will be accessed via an indirect symbol.</p>

<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ac10ac4576e030b231e1fbb5a8272f01f">llvm::GlobalValue::hasCommonLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6b66f492cbea5f4b4f434d7178477116">llvm::GlobalValue::isDeclarationForLinker</a>, <a href="#a0456a35c1b666bd1b89defc942aed435">isTargetMachO</a> and <a href="#a24d45118cad8c395285772b053965420">TM</a>.</p>

</div>
</div>

### isGVInGOT() {#abb09db483ec58bc265994fd4924592d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::isGVInGOT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the constant pool modifier needed to access the GV.</p>

<p>Declaration at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a19db81b6f3d3ab342972dce7756fb077">llvm::GlobalValue::isDSOLocal</a>, <a href="#af12f0426ec29a607f20c3fd5164c5f28">isTargetELF</a> and <a href="#a24d45118cad8c395285772b053965420">TM</a>.</p>

</div>
</div>

### isLittle() {#ad581715436b127116b9bc9a1fffa8665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isLittle ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a0a1a6e0eefe6c7dc18a625e2e8514143">IsLittle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4d6307dece29d3f347afff0ba4f2c2cd">PerformMVEVMULLCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa98ade29969ff63557a3a9594f95891a">PerformVMOVRRDCombine</a>.</p>

</div>
</div>

### isMClass() {#ae477aca96efeb96f5ad038393073a70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isMClass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="#a392ec2cf3b1f4eb78b8fb83588b32d59">ARMProcClass</a> and <a href="#a043911b5c0dbf63092e5e31dd3a44350a6bf2cd4495916d9da1be2f52f58cc05d">MClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a7d92597de5281fe585514518711079fd">llvm::ARMFunctionInfo::ARMFunctionInfo</a>, <a href="#a5b31f085b2d49f1fccf00f5109307a51">enableMachineScheduler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-cpp/#ab26269c5b1d30642badc6b2dd3728226">GetBranchTargetEnforcement</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a8ae827683289cd88fddbe641f8608b9b">llvm::ARMBaseRegisterInfo::getCalleeSavedRegs</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a44afdb77dfc5779686a8da6ffda6abab">LowerATOMIC_FENCE</a>.</p>

</div>
</div>

### isR9Reserved() {#a90763d262e1a8ae31f254f901a105c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isR9Reserved ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a0456a35c1b666bd1b89defc942aed435">isTargetMachO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#afe522c5b4605ba12fa3167e7959b6645">llvm::ARMBaseRegisterInfo::getRegPressureLimit</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a185c9e3a52cfad64d466568e38c70308">llvm::ARMBaseRegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### isRClass() {#a2705f3ce479c934bc57a03188d949cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isRClass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="#a392ec2cf3b1f4eb78b8fb83588b32d59">ARMProcClass</a> and <a href="#a043911b5c0dbf63092e5e31dd3a44350a76c12ac5ad54f8afe626c73709ae53a6">RClass</a>.</p>

</div>
</div>

### isReadTPSoft() {#a38b67bc95d128a7f872bda14b3ce1945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isReadTPSoft ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### isROPI() {#a717186a2492b294d33a8a33fd85be6bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::isROPI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a5580e4c06cf7c1cc2d1c2ef00534ac17">llvm::Reloc::ROPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a593b80c5ddf9a5f0c06860e6711955d5">llvm::Reloc::ROPI_RWPI</a> and <a href="#a24d45118cad8c395285772b053965420">TM</a>.</p>


<p>Referenced by <a href="#abfb55ae4a6dd8e8e5b6b631a348f927b">allowPositionIndependentMovt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a>.</p>

</div>
</div>

### isRWPI() {#ad3a88643e75be7b1d422605b591ab291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::isRWPI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a593b80c5ddf9a5f0c06860e6711955d5">llvm::Reloc::ROPI_RWPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a33108d181242a6b5c92f1bdb81d38128">llvm::Reloc::RWPI</a> and <a href="#a24d45118cad8c395285772b053965420">TM</a>.</p>

</div>
</div>

### isTargetAEABI() {#a12ce652b063221a5f090015a29a78781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetAEABI ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a847a953f3f994ab5453f075cea9ca7af">llvm::Triple::EABI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324af2b02c10c51141fdaa4cb49402e20169">llvm::Triple::EABIHF</a>, <a href="#a60b8559634130214660d6f0270369838">isTargetDarwin</a>, <a href="#a3f058939ca1c84b29fba5c96ff4a0f02">isTargetWindows</a> and <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a6790e830edd3f7940cc257f01a794604">CC_ARM_AAPCS_Custom_Aggregate</a>.</p>

</div>
</div>

### isTargetAndroid() {#a7037b3527a86ebfdee2382de62fcfd2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetAndroid ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>

</div>
</div>

### isTargetCOFF() {#a7cb6c1cd7f4f7a9e971b6bd9fe5888fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetCOFF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>

</div>
</div>

### isTargetDarwin() {#a60b8559634130214660d6f0270369838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetDarwin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a8ae827683289cd88fddbe641f8608b9b">llvm::ARMBaseRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#abb9d03a862069b7f3c4f446e0be8b826">llvm::ARMBaseRegisterInfo::getCallPreservedMask</a>, <a href="#a3d0de6c30c8e5b1342e3f238e765221c">getFramePointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#aee22c8e9e9eb4ac9413ce2adf676379c">llvm::ARMBaseRegisterInfo::getThisReturnPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#ac429f32d6cfbb8ea856855221d7b0324">llvm::ARMBaseRegisterInfo::getTLSCallPreservedMask</a>, <a href="#a12ce652b063221a5f090015a29a78781">isTargetAEABI</a>, <a href="#a890bfc321e0be900181291cc6e0a5d5e">isTargetGNUAEABI</a>, <a href="#ada748952ed0b0e22d2903f74f4bc44e4">isTargetMuslAEABI</a> and <a href="#a30cfb7b9ae6531d4ab27e6ea0995c053">useFPVFMx</a>.</p>

</div>
</div>

### isTargetDriverKit() {#acf1c6825852c8e24775a39c347aab406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetDriverKit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>

</div>
</div>

### isTargetEHABICompatible() {#a40b5d7e697776edc0052281f59e05f87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetEHABICompatible ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>

</div>
</div>

### isTargetELF() {#af12f0426ec29a607f20c3fd5164c5f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetELF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>


<p>Referenced by <a href="#abfb55ae4a6dd8e8e5b6b631a348f927b">allowPositionIndependentMovt</a> and <a href="#abb09db483ec58bc265994fd4924592d5">isGVInGOT</a>.</p>

</div>
</div>

### isTargetGNUAEABI() {#a890bfc321e0be900181291cc6e0a5d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetGNUAEABI ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a73b4a675dd734e1efcab33de0d217a37">llvm::Triple::GNUEABI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a699fcd7db202863a2a82143681dadb85">llvm::Triple::GNUEABIHF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ae5c77cfc976654fac7f3f50ee1352a8e">llvm::Triple::GNUEABIHFT64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a2343e70ca8369c9a61e3e25aa4e08216">llvm::Triple::GNUEABIT64</a>, <a href="#a60b8559634130214660d6f0270369838">isTargetDarwin</a>, <a href="#a3f058939ca1c84b29fba5c96ff4a0f02">isTargetWindows</a> and <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>

</div>
</div>

### isTargetHardFloat() {#aef9cc9ded3318f987b2d3a623a4ae584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::isTargetHardFloat ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>Reference <a href="#a24d45118cad8c395285772b053965420">TM</a>.</p>

</div>
</div>

### isTargetIOS() {#ab72e4138f74d00bef2662c937b4feb98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetIOS ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>

</div>
</div>

### isTargetLinux() {#adc1b5e30ed9bf38be74c079ac97b2f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetLinux ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>


<p>Referenced by <a href="#a02f4499189ec049069fb68de00a7b551">useFastISel</a>.</p>

</div>
</div>

### isTargetMachO() {#a0456a35c1b666bd1b89defc942aed435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetMachO ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>


<p>Referenced by <a href="#a43deb1b2c2e73ff4adac8e70e91b672b">isGVIndirectSymbol</a>, <a href="#a90763d262e1a8ae31f254f901a105c06">isR9Reserved</a> and <a href="#a02f4499189ec049069fb68de00a7b551">useFastISel</a>.</p>

</div>
</div>

### isTargetMuslAEABI() {#ada748952ed0b0e22d2903f74f4bc44e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetMuslAEABI ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="#a60b8559634130214660d6f0270369838">isTargetDarwin</a>, <a href="#a3f058939ca1c84b29fba5c96ff4a0f02">isTargetWindows</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a8a7dd3fc84b97dc5b1a677d60e46df80">llvm::Triple::MuslEABI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ab711c5b8f1cd078c75864af125d07fef">llvm::Triple::MuslEABIHF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a582eb6a495698055109b21d02b959c2e">llvm::Triple::OpenHOS</a> and <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>

</div>
</div>

### isTargetNaCl() {#abc057142d9cff01f1e8a6e6d64c0b082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetNaCl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>


<p>Referenced by <a href="#a02f4499189ec049069fb68de00a7b551">useFastISel</a>.</p>

</div>
</div>

### isTargetNetBSD() {#a98eb945133f19e22752163b6d1030d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetNetBSD ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>

</div>
</div>

### isTargetWatchABI() {#abda7127aefed4c41b1aee1143325191e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetWatchABI ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>


<p>Referenced by <a href="#a63af308efea4b9571d7a8aaf419fa2ee">useStride4VFPs</a>.</p>

</div>
</div>

### isTargetWatchOS() {#aa2802f820d033f21552997521d832903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetWatchOS ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>

</div>
</div>

### isTargetWindows() {#a3f058939ca1c84b29fba5c96ff4a0f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isTargetWindows ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a5869c3a07ea856e0df85ac190af3c02e">TargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8fb36df786ff6728049d25647092c350">getDivRemArgList</a>, <a href="#a3d0de6c30c8e5b1342e3f238e765221c">getFramePointerReg</a>, <a href="#a12ce652b063221a5f090015a29a78781">isTargetAEABI</a>, <a href="#a890bfc321e0be900181291cc6e0a5d5e">isTargetGNUAEABI</a>, <a href="#ada748952ed0b0e22d2903f74f4bc44e4">isTargetMuslAEABI</a>, <a href="#aa4a9faae0101445ec286f433ec4e2629">isXRaySupported</a> and <a href="#a0d600261ff016d44ce2c769ba0726224">useMovt</a>.</p>

</div>
</div>

### isThumb1Only() {#a2dc8447e2cf1376dbeebf919c0cddc9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isThumb1Only ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>.</p>


<p>Referenced by <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af4262eaffe5f263e48ab59372d7c8acb">attachMEMCPYScratchRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a8fbe3f2774ccaaf41bd80a092a9f73e5">llvm::ThumbRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a6b20576c7fe76b2d05f77b4d9d5005c6">llvm::ThumbRegisterInfo::emitLoadConstPool</a>, <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a4d3a29c0e2103ce92ec80ac1f6eee78a">llvm::ARMSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="#a7cad87ded3b08ef87a178e7189c084c5">enablePostRAMachineScheduler</a>, <a href="#a1531f96825254c3ef8b1b9272894290f">enablePostRAScheduler</a>, <a href="#a20228b431bb0e2852055ea7815a46743">getGPRAllocationOrder</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a9d1c3b55fe994ae967b25764ba0633cf">llvm::ThumbRegisterInfo::getLargestLegalSuperClass</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#aa10f0318d1d7bc44fb8df71b4e928124">llvm::ThumbRegisterInfo::getPointerRegClass</a>, <a href="#aada6bb4af36a2736480f0c51fced2d58">getPushPopSplitVariation</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a5e55ddeb12d25d6b87b3237661967c62">llvm::ARMBaseRegisterInfo::getSjLjDispatchPreservedMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad09933ec95486d26cd31cf1536190091">isLegalAddressImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6512c9219b1c585d57adf5bbf276cba6">LowerADDSUBSAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a43f5cf1f7d1e858ac4049d848f2553fe">LowerPREFETCH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#adb9776e3c9f8cf35e243fe5585cdafd3">LowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8e48c97fe5cefbf70aa4e9fa0138c99d">PerformAddcSubcCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad951ca5aa57e9482c9d5edfcf7cd1e46">PerformADDECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9dbbe6acb79ab1e69a57634d58edcf4f">PerformAddeSubeCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aec3ab4d2802494bdb8b2c3c5343f8254">PerformANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae57c77c91d8ca534534565c26afee2da">PerformMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab81a857a51f1d25a352fc51569f079a0">PerformORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a963a08f31bbf8cb9396ff5214bc7ae26">PerformORCombineToBFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1399030f41bb48286cffbbfddb29a3f">PerformXORCombine</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#ab8e6b81acb0eec0b1d8ccda6db37697d">llvm::ThumbRegisterInfo::resolveFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#acb75d3ebfc904675aed50ee39f619373">llvm::ThumbRegisterInfo::rewriteFrameIndex</a>, <a href="#a02f4499189ec049069fb68de00a7b551">useFastISel</a> and <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a4bb122f51e78c7107ac461d1adf44906">llvm::ThumbRegisterInfo::useFPForScavengingIndex</a>.</p>

</div>
</div>

### isThumb2() {#a366b7fda111b63c2bf86c1b81a9cc362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::isThumb2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>.</p>


<p>Referenced by <a href="#a20228b431bb0e2852055ea7815a46743">getGPRAllocationOrder</a>, <a href="#a6a5ef234051f5fe582e5fa53d655d3d9">ignoreCSRForAllocationOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad09933ec95486d26cd31cf1536190091">isLegalAddressImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a43f5cf1f7d1e858ac4049d848f2553fe">LowerPREFETCH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac0d7b6ab8ce9dce97d728aef673b1eed">PerformMinMaxToSatCombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvetpandvptoptimisationspass-cpp-/mvetpandvptoptimisations/#a583bacd9cc15714c083c599b7e45cbb6">anonymous{MVETPAndVPTOptimisationsPass.cpp}::MVETPAndVPTOptimisations::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvevptblockpass-cpp-/mvevptblock/#ab605a2a73e0835e3eed53af0819582f0">anonymous{MVEVPTBlockPass.cpp}::MVEVPTBlock::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-thumb2itblockpass-cpp-/thumb2itblock/#a5477944b7d70dd3c998b38a43e88f041">anonymous{Thumb2ITBlockPass.cpp}::Thumb2ITBlock::runOnMachineFunction</a>.</p>

</div>
</div>

### isXRaySupported() {#aa4a9faae0101445ec286f433ec4e2629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::isXRaySupported ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="#a18ff0b01bdb57bf15f1879917450bba6">hasARMOps</a> and <a href="#a3f058939ca1c84b29fba5c96ff4a0f02">isTargetWindows</a>.</p>

</div>
</div>

### ParseSubtargetFeatures() {#acaea1baccb33d11d647a906dd1ae5e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ARMSubtarget::ParseSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options.</p>


<p>Definition of function is auto generated by tblgen.</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a>.</p>

</div>
</div>

### restrictIT() {#afb3dca30645bc25c91679fa0b7c8b3bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::restrictIT ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a65ffddf9935139cf113d2a4b43173bc0">RestrictIT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-thumb2itblockpass-cpp-/thumb2itblock/#a5477944b7d70dd3c998b38a43e88f041">anonymous{Thumb2ITBlockPass.cpp}::Thumb2ITBlock::runOnMachineFunction</a>.</p>

</div>
</div>

### supportsTailCall() {#a1a9091351224b05c4bc72baa2ae1914f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::supportsTailCall ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#ae97e07d14d7e5aec61a9f299f9793036">SupportsTailCall</a>.</p>

</div>
</div>

### useAA() {#a6de349696d146aa1d3af80b3470ae6f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::useAA ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable use of alias analysis during code generation (during MI scheduling, DAGCombine, etc.).</p>

<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### useDFAforSMS() {#a383625e4ecded16fd5bfed6c69a8130d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::useDFAforSMS ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

### useFastISel() {#a02f4499189ec049069fb68de00a7b551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::useFastISel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if fast-isel is used.</p>

<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a65323d3fd11159039f504dde80f10968">ForceFastISel</a>, <a href="#adc1b5e30ed9bf38be74c079ac97b2f44">isTargetLinux</a>, <a href="#a0456a35c1b666bd1b89defc942aed435">isTargetMachO</a>, <a href="#abc057142d9cff01f1e8a6e6d64c0b082">isTargetNaCl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>, <a href="#a2dc8447e2cf1376dbeebf919c0cddc9a">isThumb1Only</a> and <a href="#a24d45118cad8c395285772b053965420">TM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa23959d9b3463aec95209a1fe73c1e3f">llvm::ARM::createFastISel</a>.</p>

</div>
</div>

### useFPVFMx() {#a30cfb7b9ae6531d4ab27e6ea0995c053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::useFPVFMx ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>References <a href="#a1f6489afbec421c829ed918b777abe53">hasVFP4Base</a> and <a href="#a60b8559634130214660d6f0270369838">isTargetDarwin</a>.</p>


<p>Referenced by <a href="#ae4772b23bccc0e8235027510b6d6c5b0">useFPVFMx16</a> and <a href="#a91a737d59f7b36ae704dab9be3c359f5">useFPVFMx64</a>.</p>

</div>
</div>

### useFPVFMx16() {#ae4772b23bccc0e8235027510b6d6c5b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::useFPVFMx16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a30cfb7b9ae6531d4ab27e6ea0995c053">useFPVFMx</a>.</p>

</div>
</div>

### useFPVFMx64() {#a91a737d59f7b36ae704dab9be3c359f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::useFPVFMx64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a30cfb7b9ae6531d4ab27e6ea0995c053">useFPVFMx</a>.</p>

</div>
</div>

### useFPVMLx() {#a2a9a6d8b7443a4500a4f6e0758847113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::useFPVMLx ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### useMachinePipeliner() {#acc59368a716c973ff5601a7e27bed962}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::useMachinePipeliner ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a7c115385fe95b53102bbfceb5d70e3a3">enableMachinePipeliner</a>.</p>

</div>
</div>

### useMachineScheduler() {#ad0b49699b3961f3ffc391633d3d975de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::useMachineScheduler ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a5b31f085b2d49f1fccf00f5109307a51">enableMachineScheduler</a>.</p>

</div>
</div>

### useMovt() {#a0d600261ff016d44ce2c769ba0726224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::useMovt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="#a3f058939ca1c84b29fba5c96ff4a0f02">isTargetWindows</a> and <a href="#a6551f0a9aa4e4f8b96dcc6961b337cd9">OptMinSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aabff304f51525ece8028bf8e9b1c3614">llvm::ConstantMaterializationCost</a>.</p>

</div>
</div>

### useMulOps() {#af08fd693b813f5df7880bfee47fb24a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::useMulOps ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#ac598e25a4489f49f0edcfd929e0fedd4">UseMulOps</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5425376fb8bb34c4f59a84a3ee70c790">AddCombineTo64bitMLAL</a>.</p>

</div>
</div>

### useNEONForSinglePrecisionFP() {#abbf250d4cc8d087660064261ee727a9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::useNEONForSinglePrecisionFP ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### useSjLjEH() {#a499dae244f5b646551e74460a354060c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::useSjLjEH ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Reference <a href="#a1ef1ab2ddea61481fc5d146420e6a736">UseSjLjEH</a>.</p>

</div>
</div>

### useStride4VFPs() {#a63af308efea4b9571d7a8aaf419fa2ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMSubtarget::useStride4VFPs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>


<p>References <a href="#abda7127aefed4c41b1aee1143325191e">isTargetWatchABI</a> and <a href="#a6551f0a9aa4e4f8b96dcc6961b337cd9">OptMinSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### initializeEnvironment() {#a91f9da5266c84d3e62a97d689e77cfd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMSubtarget::initializeEnvironment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

### initializeFrameLowering() {#a1168b68c2a5e4f6e9307aa361f829842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMFrameLowering * ARMSubtarget::initializeFrameLowering (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

### initSubtargetFeatures() {#a0b396ebaa226b66f2cc60068f9bfc578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMSubtarget::initSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ARMArch {#a3282354eb8d2ae94ce6b9d004c39f9da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMArchEnum llvm::ARMSubtarget::ARMArch = ARMv4t</td>
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

<p>ARMArch - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> architecture.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### ARMProcClass {#a392ec2cf3b1f4eb78b8fb83588b32d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMProcClassEnum llvm::ARMSubtarget::ARMProcClass = <a href="#a043911b5c0dbf63092e5e31dd3a44350a4dd2edaabfdcef503954040697f7cc92">None</a></td>
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

<p>ARMProcClass - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> processor class: None, AClass, RClass or MClass.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a35da413e7feffe5fcdf1cbbded5fd08c">isAClass</a>, <a href="#ae477aca96efeb96f5ad038393073a70c">isMClass</a> and <a href="#a2705f3ce479c934bc57a03188d949cc7">isRClass</a>.</p>

</div>
</div>

### ARMProcFamily {#a305f7bdd75fb674c665306eed2a6dcde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMProcFamilyEnum llvm::ARMSubtarget::ARMProcFamily = <a href="#a1f30745dc0351a55935d08768ad5471faeb05712cf7ca7c7cdb51e33fc266a5b3">Others</a></td>
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

<p>ARMProcFamily - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> processor family: Cortex-A8, Cortex-A9, and others.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#ad22a711cea737ea6b5fd7cada552e049">isCortexA15</a>, <a href="#a6956835a06343b455ce7ddc93338e68d">isCortexA5</a>, <a href="#a08caeec4314d2a3983d98789d7559e80">isCortexA7</a>, <a href="#ac43b07f1b3f6ed64f7bfc6d864bd7465">isCortexA8</a>, <a href="#ae3a27a74eec3db7120b851ebc2d98b33">isCortexA9</a>, <a href="#abcc3f0c87647ca51e1e66789f21e5c3f">isCortexM3</a>, <a href="#a5bd3b2c686ea4cbf7d14e3f5c17ad0dd">isCortexM55</a>, <a href="#a345f83983694394198f7fd0cbd01263f">isCortexM7</a>, <a href="#a2ab5747677e158d871483a440f2ffcca">isCortexM85</a>, <a href="#a41ec2e41ef180b9e32a9cb810db27071">isCortexR5</a>, <a href="#a67cb506ce9fe0e6a5441cbe784397c73">isKrait</a> and <a href="#a0eef6de6958d76e6b151164c5b419650">isSwift</a>.</p>

</div>
</div>

### CPUString {#a4e77a418bcc57002a5041ac7c98ddcb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::ARMSubtarget::CPUString</td>
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

<p>CPUString - String name of used CPU.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a> and <a href="#a8bb8ca7757251436e96910fa926b168c">getCPUString</a>.</p>

</div>
</div>

### InstrItins {#a62b68a81d2aae79d68d64fac49cbe252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrItineraryData llvm::ARMSubtarget::InstrItins</td>
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

<p>Selected instruction itineraries (one entry per itinerary class.)</p>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#abc865dab96e62f0620415c26ef9daf4a">getInstrItineraryData</a>.</p>

</div>
</div>

### IsLittle {#a0a1a6e0eefe6c7dc18a625e2e8514143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::IsLittle</td>
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

<p>IsLittle - The target is Little Endian.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a> and <a href="#ad581715436b127116b9bc9a1fffa8665">isLittle</a>.</p>

</div>
</div>

### LdStMultipleTiming {#a154d5066ba40a202a471928dd415c9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMLdStMultipleTiming llvm::ARMSubtarget::LdStMultipleTiming = <a href="#ac7324b67d7e3be270177e6590f0bb1e5a4036c7f30f9ea851473b06416cbbc160">SingleIssue</a></td>
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

<p>What kind of timing do load multiple/store multiple have (double issue, single issue etc).</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a288ce2c947e6872de3578a3a431ac880">getLdStMultipleTiming</a>.</p>

</div>
</div>

### MaxInterleaveFactor {#a2087132740838f877daf6cf7e33ce756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMSubtarget::MaxInterleaveFactor = 1</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a8d67f7585b636734bd556a436b109a9c">getMaxInterleaveFactor</a>.</p>

</div>
</div>

### MVEVectorCostFactor {#a44372fedd70001a500198ddf6f28edc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMSubtarget::MVEVectorCostFactor = 0</td>
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

<p>The cost factor for MVE instructions, representing the multiple beats an.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#afdce0e5134718d45046f01f8f26a4ea8">getMVEVectorCostFactor</a>.</p>

</div>
</div>

### Options {#ac5c330415d1cbbde2aff5b41aca13880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetOptions&amp; llvm::ARMSubtarget::Options</td>
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

<p>Options passed via command line that could influence the target.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a>.</p>

</div>
</div>

### OptMinSize {#a6551f0a9aa4e4f8b96dcc6961b337cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::OptMinSize = false</td>
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

<p>OptMinSize - True if we're optimising for minimum code size, equal to the function attribute.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a>, <a href="#aae326d7c694f98af61c453f4a9a5098a">hasMinSize</a>, <a href="#a0d600261ff016d44ce2c769ba0726224">useMovt</a> and <a href="#a63af308efea4b9571d7a8aaf419fa2ee">useStride4VFPs</a>.</p>

</div>
</div>

### PartialUpdateClearance {#a7afee8c81c6cada000d6ed7e3b7f2044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMSubtarget::PartialUpdateClearance = 0</td>
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

<p>Clearance before partial register updates (in number of instructions)</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a94a1e306f6a8f058fa1174c78eab41d4">getPartialUpdateClearance</a>.</p>

</div>
</div>

### PreferBranchLogAlignment {#a4f95e07b0b688a534dfae30619946d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMSubtarget::PreferBranchLogAlignment = 0</td>
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

<p>What alignment is preferred for loop bodies and functions, in log2(bytes).</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa61c4bf89ca23382c1b6776fb739ee46">getPreferBranchLogAlignment</a>.</p>

</div>
</div>

### PreISelOperandLatencyAdjustment {#aec40a1e3aa8d47e424dd1db21dfbbce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARMSubtarget::PreISelOperandLatencyAdjustment = 2</td>
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

<p>The adjustment that we need to apply to get the operand latency from the operand cycle returned by the itinerary data for pre-ISel operands.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#ad0ab8fda6506b4c85c9c41ac9695604a">getPreISelOperandLatencyAdjustment</a>.</p>

</div>
</div>

### RestrictIT {#a65ffddf9935139cf113d2a4b43173bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::RestrictIT = false</td>
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

<p>RestrictIT - If true, the subtarget disallows generation of complex IT blocks.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#afb3dca30645bc25c91679fa0b7c8b3bf">restrictIT</a>.</p>

</div>
</div>

### SchedModel {#a4cd3222767747226351eebf8488f74c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSchedModel llvm::ARMSubtarget::SchedModel</td>
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

<p>SchedModel - Processor specific instruction costs.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a4f7d9339ba6fd6b1cd9dedc400378355">getMispredictionPenalty</a>.</p>

</div>
</div>

### stackAlignment {#a7349230a719441eff31e1c8651ae9e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::ARMSubtarget::stackAlignment = <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(4)</td>
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

<p>stackAlignment - The minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a66662d23168fc7ef438ee5e05366bae1">getStackAlignment</a>.</p>

</div>
</div>

### SupportsTailCall {#ae97e07d14d7e5aec61a9f299f9793036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::SupportsTailCall = false</td>
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

<p>SupportsTailCall - True if the OS supports tail call.</p>


<p>The dynamic linker must be able to synthesize call stubs for interworking between <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> and Thumb.</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a1a9091351224b05c4bc72baa2ae1914f">supportsTailCall</a>.</p>

</div>
</div>

### TargetTriple {#a5869c3a07ea856e0df85ac190af3c02e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::ARMSubtarget::TargetTriple</td>
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

<p>TargetTriple - What processor and OS we're targeting.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a>, <a href="#a1e33acc8570da51f655ba63ac62e2a21">getTargetTriple</a>, <a href="#a12ce652b063221a5f090015a29a78781">isTargetAEABI</a>, <a href="#a7037b3527a86ebfdee2382de62fcfd2e">isTargetAndroid</a>, <a href="#a7cb6c1cd7f4f7a9e971b6bd9fe5888fc">isTargetCOFF</a>, <a href="#a60b8559634130214660d6f0270369838">isTargetDarwin</a>, <a href="#acf1c6825852c8e24775a39c347aab406">isTargetDriverKit</a>, <a href="#a40b5d7e697776edc0052281f59e05f87">isTargetEHABICompatible</a>, <a href="#af12f0426ec29a607f20c3fd5164c5f28">isTargetELF</a>, <a href="#a890bfc321e0be900181291cc6e0a5d5e">isTargetGNUAEABI</a>, <a href="#ab72e4138f74d00bef2662c937b4feb98">isTargetIOS</a>, <a href="#adc1b5e30ed9bf38be74c079ac97b2f44">isTargetLinux</a>, <a href="#a0456a35c1b666bd1b89defc942aed435">isTargetMachO</a>, <a href="#ada748952ed0b0e22d2903f74f4bc44e4">isTargetMuslAEABI</a>, <a href="#abc057142d9cff01f1e8a6e6d64c0b082">isTargetNaCl</a>, <a href="#a98eb945133f19e22752163b6d1030d36">isTargetNetBSD</a>, <a href="#abda7127aefed4c41b1aee1143325191e">isTargetWatchABI</a>, <a href="#aa2802f820d033f21552997521d832903">isTargetWatchOS</a> and <a href="#a3f058939ca1c84b29fba5c96ff4a0f02">isTargetWindows</a>.</p>

</div>
</div>

### TM {#a24d45118cad8c395285772b053965420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMBaseTargetMachine&amp; llvm::ARMSubtarget::TM</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a>, <a href="#a3bda6b04debe6e44dc3f255e069c01e8">isAAPCS16_ABI</a>, <a href="#ad0b122c9e993cea45116667c05e04988">isAAPCS_ABI</a>, <a href="#a90ff14194f77a2cd0afb651a97acf27f">isAPCS_ABI</a>, <a href="#a43deb1b2c2e73ff4adac8e70e91b672b">isGVIndirectSymbol</a>, <a href="#abb09db483ec58bc265994fd4924592d5">isGVInGOT</a>, <a href="#a717186a2492b294d33a8a33fd85be6bf">isROPI</a>, <a href="#ad3a88643e75be7b1d422605b591ab291">isRWPI</a>, <a href="#aef9cc9ded3318f987b2d3a623a4ae584">isTargetHardFloat</a> and <a href="#a02f4499189ec049069fb68de00a7b551">useFastISel</a>.</p>

</div>
</div>

### UseMulOps {#ac598e25a4489f49f0edcfd929e0fedd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::UseMulOps = false</td>
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

<p>UseMulOps - True if non-microcoded fused integer multiply-add and multiply-subtract instructions should be used.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a16350880c9e7c3b3c6f960644b0abd6c">ARMSubtarget</a> and <a href="#af08fd693b813f5df7880bfee47fb24a8">useMulOps</a>.</p>

</div>
</div>

### UseSjLjEH {#a1ef1ab2ddea61481fc5d146420e6a736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMSubtarget::UseSjLjEH = false</td>
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

<p>UseSjLjEH - If true, the target uses SjLj exception handling (e.g. iOS).</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>


<p>Referenced by <a href="#a499dae244f5b646551e74460a354060c">useSjLjEH</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallLoweringInfo {#ab59db205e0e515e0aead0c30185ba704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CallLowering&gt; llvm::ARMSubtarget::CallLoweringInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GlobalISel related APIs.</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### CoprocCDE {#a318a6a58de5b0a04ebdae9a9edece3e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::bitset&lt;8&gt; llvm::ARMSubtarget::CoprocCDE = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### FrameLowering {#a6a726f90af68504309411d8b85cdcb04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ARMFrameLowering&gt; llvm::ARMSubtarget::FrameLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### InstrInfo {#ae99c5469461e3b46d87e209256e93dc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ARMBaseInstrInfo&gt; llvm::ARMSubtarget::InstrInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### InstSelector {#aa3de60ce476ea6dac316afa70e1a0f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InstructionSelector&gt; llvm::ARMSubtarget::InstSelector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### Legalizer {#a90e9edff4d610e3ee955f18db5ee0023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LegalizerInfo&gt; llvm::ARMSubtarget::Legalizer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### RegBankInfo {#aa9c154d5cd0c66895353d4e1b1781371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;RegisterBankInfo&gt; llvm::ARMSubtarget::RegBankInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### TLInfo {#a82a0e988e0dfe8be49b5e130548ea9da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMTargetLowering llvm::ARMSubtarget::TLInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

### TSInfo {#a88dfb82b099834fc01fb3c7d39fe1a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMSelectionDAGInfo llvm::ARMSubtarget::TSInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp">ARMSubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
