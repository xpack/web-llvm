---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/m68ksubtarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `M68kSubtarget` Class



## Declaration

<div class="doxyDeclaration">
class llvm::M68kSubtarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">Target/M68k/M68kSubtarget.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/m68kgensubtargetinfo">M68kGenSubtargetInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SubtargetEnum { <a href="#a3e08e796415db68db09a89fbac110854">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">FPKindEnum { <a href="#a17d29effba0c783a43c0269b1d22aca4">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a> (const Triple &amp;TT, StringRef CPU, StringRef FS, const M68kTargetMachine &amp;_TM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor initializes the data members to match that of the specified triple. <a href="#a354c9b3558a69622cbcbd3d7f32730ed">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d0f2ef2893c90937e49f451c469e5d2">ParseSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses features string setting specified subtarget options. <a href="#a7d0f2ef2893c90937e49f451c469e5d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf27395c3301b22c5be794ec0016f515">atLeastM68000</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5305349832a95730232c2ccc3153e44">atLeastM68010</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e6893f3310a84fe9b62098d8d9c8ee">atLeastM68020</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64d0873845e1183f99d9290df65339c">atLeastM68030</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c800ad6f467ea69b0ede3e84b3dbbd2">atLeastM68040</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f3a2e6be55789bc750fe56501a27a38">atLeastM68060</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e7df9801336c4b431a870203bb33cd">hasFPU</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Floating point support. <a href="#a87e7df9801336c4b431a870203bb33cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a776f7c2e630dc21f3fb1394e4c40e77b">atLeastM68881</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2237e53d68a72fb9f62224ad8a2538bd">atLeastM68882</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd27b26d2f85c507893fc784a1073a2a">useSmallSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9125638c704b3dd51015f11b0c1b6c56">getTargetTriple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b44b6b0df87a94622717c8a8559547">isTargetELF</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a712206899f06c86a0216c00713ecb053">isLegalToCallImmediateAddr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the subtarget allows calls to immediate address. <a href="#a712206899f06c86a0216c00713ecb053">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf5c5e04d2155397699ac6977e8a9f9c">isPositionIndependent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accef3e3df7d94aedf1a7aab8ecf8bd40">isRegisterReservedByUser</a> (Register R) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91ce9a25d780116e557aacb80e8be00">classifyLocalReference</a> (const GlobalValue *GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Classify a global variable reference for the current subtarget according to how we should reference it in a non-pcrel context. <a href="#ac91ce9a25d780116e557aacb80e8be00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad702e10e7d2950cb6cfb571a2dddd1d">classifyGlobalReference</a> (const GlobalValue *GV, const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Classify a global variable reference for the current subtarget according to how we should reference it in a non-pcrel context. <a href="#aad702e10e7d2950cb6cfb571a2dddd1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcb8d02bb64a997fa76a9d566b9b2816">classifyGlobalReference</a> (const GlobalValue *GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e59ad505dc01aac3afce8bf62bd948">classifyExternalReference</a> (const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Classify a external variable reference for the current subtarget according to how we should reference it in a non-pcrel context. <a href="#a21e59ad505dc01aac3afce8bf62bd948">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd7cd9f26f83bf8a9b75572b6fb7c75">classifyGlobalFunctionReference</a> (const GlobalValue *GV, const Module &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Classify a global function reference for the current subtarget. <a href="#aefd7cd9f26f83bf8a9b75572b6fb7c75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3c2fef3c61959152fccd82f06d3f59">classifyGlobalFunctionReference</a> (const GlobalValue *GV) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a469baae35d6f52f0a01f03f13faba992">classifyBlockAddressReference</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Classify a blockaddress reference for the current subtarget according to how we should reference it in a non-pcrel context. <a href="#a469baae35d6f52f0a01f03f13faba992">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9b77cf3d4903e5d99c084e4a09ae7fb">getJumpTableEncoding</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a184c4c6153b92f54e32998afd32050f1">getStackAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TODO this must be controlled by options like -malign-int and -mshort. <a href="#a184c4c6153b92f54e32998afd32050f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b38190d70ca6f52984a3b6793ed81d4">getSlotSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSlotSize - Stack slot size in bytes. <a href="#a8b38190d70ca6f52984a3b6793ed81d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/m68ksubtarget">M68kSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3337a826c5ca8fe41a7434b9d028943">initializeSubtargetDependencies</a> (StringRef CPU, Triple TT, StringRef FS, const M68kTargetMachine &amp;TM)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab96f714528d2891aac3537214fc3a7c6">getSelectionDAGInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo">M68kInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6202d7bf1d02aafd7cd6576dc7c4b03">getInstrInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering">M68kFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff5264b89b98c1409fe2ab3137ca4fed">getFrameLowering</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo">M68kRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad37055600593cd4b591df42904012061">getRegisterInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering">M68kTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29c6fdf8471ace3690788857e4d9a8bd">getTargetLowering</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65a3aecdb282f800cb548da4a38e67af">getInstrItineraryData</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4401f6fa6688e269c8d4393c9a35e8a">getCallLowering</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf6092cff04d11cde639c05425242af">getInstructionSelector</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a489f9f6efa7feaeec084866592c1d14c">getLegalizerInfo</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ace610ea65a3d398e730c3248e08101">getRegBankInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99f0c7df2b60b4316fac003d88fab460">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3e08e796415db68db09a89fbac110854">SubtargetEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a458064b0de00d07bcc3b7fefb02dda">SubtargetKind</a> = <a href="#a3e08e796415db68db09a89fbac110854acccb0e62e055d92ef8015793186c2af5">M00</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a17d29effba0c783a43c0269b1d22aca4">FPKindEnum</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a307bfdbbe1f7e5910262a09a5c9524ef">FPUKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::bitset&lt; M68k::NUM_TARGET_REGS &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67f547ca05d077489e0526079345fff4">UserReservedRegister</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27dbf15232208a2c6715dd5cdd0b01b5">InstrItins</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70686cd734402136e07aac16b920f1d4">UseSmallSection</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Small section is used. <a href="#a70686cd734402136e07aac16b920f1d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine">M68kTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8395ba3f6a62aca972d7ab84ab2f84b6">TM</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aa7e2e789c67eff38bded293ca07412">TSInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo">M68kInstrInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a523fea9bc9816baef78598f00930a719">InstrInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/m68kframelowering">M68kFrameLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5a8148659f3fc4b2413401bc6be0408">FrameLowering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering">M68kTargetLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a2acf820e3bdbf8c04921eec32ce21">TLInfo</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd047227f62bfbc2b220d66440cf3a9d">stackAlignment</a> = 8</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function. <a href="#acd047227f62bfbc2b220d66440cf3a9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5e710e25efca4af480f34c9db58deb0">TargetTriple</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d23f224fac2a282137c2ca7d927b9b">CallLoweringInfo</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6dbae0e87bae59f24d6dd9e925d8e4a">InstSelector</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad96cbb45408d224a6badee6de85a8b34">Legalizer</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d8a66a2b639623b8bfa44d84108b45">RegBankInfo</a></td>
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


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### FPKindEnum {#a17d29effba0c783a43c0269b1d22aca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::M68kSubtarget::FPKindEnum </td>
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
<td class="doxyEnumItemName">M881<a id="a17d29effba0c783a43c0269b1d22aca4abfe6f248c3f06a53353dee395230a273"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">M882<a id="a17d29effba0c783a43c0269b1d22aca4a64877067448447e0c0f6a8e217649482"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>

</div>
</div>

### SubtargetEnum {#a3e08e796415db68db09a89fbac110854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::M68kSubtarget::SubtargetEnum </td>
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
<td class="doxyEnumItemName">M00<a id="a3e08e796415db68db09a89fbac110854acccb0e62e055d92ef8015793186c2af5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">M10<a id="a3e08e796415db68db09a89fbac110854ae8a74f1ffdc5ad31a2e42de3f9dfbf80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">M20<a id="a3e08e796415db68db09a89fbac110854a9e369055763e517cdf3c719624569b9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">M30<a id="a3e08e796415db68db09a89fbac110854a302746a96a87baace532b972be5c0181"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">M40<a id="a3e08e796415db68db09a89fbac110854a8739e9f75a0e8f9f2050649da1375540"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">M60<a id="a3e08e796415db68db09a89fbac110854a3502cdcedec80bf73f813bccfc6b6897"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### M68kSubtarget() {#a354c9b3558a69622cbcbd3d7f32730ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">M68kSubtarget::M68kSubtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine">M68kTargetMachine</a> &amp; _TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This constructor initializes the data members to match that of the specified triple.</p>

<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>References <a href="#a73d23f224fac2a282137c2ca7d927b9b">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2fbeb7516f4c4d9a2d7ea43b8d6d303">llvm::createM68kInstructionSelector</a>, <a href="#ae5a8148659f3fc4b2413401bc6be0408">FrameLowering</a>, <a href="#ad37055600593cd4b591df42904012061">getRegisterInfo</a>, <a href="#a184c4c6153b92f54e32998afd32050f1">getStackAlignment</a>, <a href="#a29c6fdf8471ace3690788857e4d9a8bd">getTargetLowering</a>, <a href="#ae3337a826c5ca8fe41a7434b9d028943">initializeSubtargetDependencies</a>, <a href="#a523fea9bc9816baef78598f00930a719">InstrInfo</a>, <a href="#af6dbae0e87bae59f24d6dd9e925d8e4a">InstSelector</a>, <a href="#ad96cbb45408d224a6badee6de85a8b34">Legalizer</a>, <a href="#ac8d8a66a2b639623b8bfa44d84108b45">RegBankInfo</a>, <a href="#ad5e710e25efca4af480f34c9db58deb0">TargetTriple</a>, <a href="#a95a2acf820e3bdbf8c04921eec32ce21">TLInfo</a>, <a href="#a8395ba3f6a62aca972d7ab84ab2f84b6">TM</a> and <a href="#a9aa7e2e789c67eff38bded293ca07412">TSInfo</a>.</p>


<p>Referenced by <a href="#ae3337a826c5ca8fe41a7434b9d028943">initializeSubtargetDependencies</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### atLeastM68000() {#aaf27395c3301b22c5be794ec0016f515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::atLeastM68000 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>References <a href="#a3e08e796415db68db09a89fbac110854acccb0e62e055d92ef8015793186c2af5">M00</a> and <a href="#a3a458064b0de00d07bcc3b7fefb02dda">SubtargetKind</a>.</p>

</div>
</div>

### atLeastM68010() {#ac5305349832a95730232c2ccc3153e44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::atLeastM68010 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>References <a href="#a3e08e796415db68db09a89fbac110854ae8a74f1ffdc5ad31a2e42de3f9dfbf80">M10</a> and <a href="#a3a458064b0de00d07bcc3b7fefb02dda">SubtargetKind</a>.</p>

</div>
</div>

### atLeastM68020() {#ad9e6893f3310a84fe9b62098d8d9c8ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::atLeastM68020 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>References <a href="#a3e08e796415db68db09a89fbac110854a9e369055763e517cdf3c719624569b9c">M20</a> and <a href="#a3a458064b0de00d07bcc3b7fefb02dda">SubtargetKind</a>.</p>


<p>Referenced by <a href="#aad702e10e7d2950cb6cfb571a2dddd1d">classifyGlobalReference</a>, <a href="#ac91ce9a25d780116e557aacb80e8be00">classifyLocalReference</a> and <a href="#ab9b77cf3d4903e5d99c084e4a09ae7fb">getJumpTableEncoding</a>.</p>

</div>
</div>

### atLeastM68030() {#ae64d0873845e1183f99d9290df65339c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::atLeastM68030 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>References <a href="#a3e08e796415db68db09a89fbac110854a302746a96a87baace532b972be5c0181">M30</a> and <a href="#a3a458064b0de00d07bcc3b7fefb02dda">SubtargetKind</a>.</p>

</div>
</div>

### atLeastM68040() {#a3c800ad6f467ea69b0ede3e84b3dbbd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::atLeastM68040 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>References <a href="#a3e08e796415db68db09a89fbac110854a8739e9f75a0e8f9f2050649da1375540">M40</a> and <a href="#a3a458064b0de00d07bcc3b7fefb02dda">SubtargetKind</a>.</p>

</div>
</div>

### atLeastM68060() {#a2f3a2e6be55789bc750fe56501a27a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::atLeastM68060 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>References <a href="#a3e08e796415db68db09a89fbac110854a3502cdcedec80bf73f813bccfc6b6897">M60</a> and <a href="#a3a458064b0de00d07bcc3b7fefb02dda">SubtargetKind</a>.</p>

</div>
</div>

### atLeastM68881() {#a776f7c2e630dc21f3fb1394e4c40e77b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::atLeastM68881 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>References <a href="#a307bfdbbe1f7e5910262a09a5c9524ef">FPUKind</a>, <a href="#a87e7df9801336c4b431a870203bb33cd">hasFPU</a> and <a href="#a17d29effba0c783a43c0269b1d22aca4abfe6f248c3f06a53353dee395230a273">M881</a>.</p>

</div>
</div>

### atLeastM68882() {#a2237e53d68a72fb9f62224ad8a2538bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::atLeastM68882 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>References <a href="#a307bfdbbe1f7e5910262a09a5c9524ef">FPUKind</a>, <a href="#a87e7df9801336c4b431a870203bb33cd">hasFPU</a> and <a href="#a17d29effba0c783a43c0269b1d22aca4a64877067448447e0c0f6a8e217649482">M882</a>.</p>

</div>
</div>

### classifyBlockAddressReference() {#a469baae35d6f52f0a01f03f13faba992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char M68kSubtarget::classifyBlockAddressReference ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Classify a blockaddress reference for the current subtarget according to how we should reference it in a non-pcrel context.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>References <a href="#adf5c5e04d2155397699ac6977e8a9f9c">isPositionIndependent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa6a2e45ae404e3f797d2d7e9f3a48949">llvm::CodeModel::Kernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a79ada893fa3a7cbe1b2d180bedcf2ba9">llvm::M68kII::MO_ABSOLUTE_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a9b5b1d8ef02f8f95a63b78aa46bc9f15">llvm::M68kII::MO_PC_RELATIVE_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a> and <a href="#a8395ba3f6a62aca972d7ab84ab2f84b6">TM</a>.</p>

</div>
</div>

### classifyExternalReference() {#a21e59ad505dc01aac3afce8bf62bd948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char M68kSubtarget::classifyExternalReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Classify a external variable reference for the current subtarget according to how we should reference it in a non-pcrel context.</p>

<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>References <a href="#ac91ce9a25d780116e557aacb80e8be00">classifyLocalReference</a>, <a href="#adf5c5e04d2155397699ac6977e8a9f9c">isPositionIndependent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a6da451e267e7fa37d09e4f116d7a0f56">llvm::M68kII::MO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a7c9861e5ad1a38ababe5a78c1c0c95f6">llvm::M68kII::MO_GOTPCREL</a> and <a href="#a8395ba3f6a62aca972d7ab84ab2f84b6">TM</a>.</p>

</div>
</div>

### classifyGlobalFunctionReference() {#aefd7cd9f26f83bf8a9b75572b6fb7c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char M68kSubtarget::classifyGlobalFunctionReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Classify a global function reference for the current subtarget.</p>

<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#adf5c5e04d2155397699ac6977e8a9f9c">isPositionIndependent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a79ada893fa3a7cbe1b2d180bedcf2ba9">llvm::M68kII::MO_ABSOLUTE_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a7c9861e5ad1a38ababe5a78c1c0c95f6">llvm::M68kII::MO_GOTPCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88ae40504bd63df1c211500fcd35a29a601">llvm::M68kII::MO_NO_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a57e0e9fc5c5f19541861ef8dd3161679">llvm::M68kII::MO_PLT</a> and <a href="#a8395ba3f6a62aca972d7ab84ab2f84b6">TM</a>.</p>


<p>Referenced by <a href="#a6e3c2fef3c61959152fccd82f06d3f59">classifyGlobalFunctionReference</a>.</p>

</div>
</div>

### classifyGlobalFunctionReference() {#a6e3c2fef3c61959152fccd82f06d3f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char M68kSubtarget::classifyGlobalFunctionReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>References <a href="#aefd7cd9f26f83bf8a9b75572b6fb7c75">classifyGlobalFunctionReference</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>.</p>

</div>
</div>

### classifyGlobalReference() {#aad702e10e7d2950cb6cfb571a2dddd1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char M68kSubtarget::classifyGlobalReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Classify a global variable reference for the current subtarget according to how we should reference it in a non-pcrel context.</p>

<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>References <a href="#ad9e6893f3310a84fe9b62098d8d9c8ee">atLeastM68020</a>, <a href="#ac91ce9a25d780116e557aacb80e8be00">classifyLocalReference</a>, <a href="#adf5c5e04d2155397699ac6977e8a9f9c">isPositionIndependent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa6a2e45ae404e3f797d2d7e9f3a48949">llvm::CodeModel::Kernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a79ada893fa3a7cbe1b2d180bedcf2ba9">llvm::M68kII::MO_ABSOLUTE_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a14de646b08b938d4b58469a685923fd7">llvm::M68kII::MO_GOTOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a7c9861e5ad1a38ababe5a78c1c0c95f6">llvm::M68kII::MO_GOTPCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a9b5b1d8ef02f8f95a63b78aa46bc9f15">llvm::M68kII::MO_PC_RELATIVE_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a> and <a href="#a8395ba3f6a62aca972d7ab84ab2f84b6">TM</a>.</p>


<p>Referenced by <a href="#adcb8d02bb64a997fa76a9d566b9b2816">classifyGlobalReference</a>.</p>

</div>
</div>

### classifyGlobalReference() {#adcb8d02bb64a997fa76a9d566b9b2816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char M68kSubtarget::classifyGlobalReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>References <a href="#aad702e10e7d2950cb6cfb571a2dddd1d">classifyGlobalReference</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>.</p>

</div>
</div>

### classifyLocalReference() {#ac91ce9a25d780116e557aacb80e8be00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char M68kSubtarget::classifyLocalReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Classify a global variable reference for the current subtarget according to how we should reference it in a non-pcrel context.</p>

<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>References <a href="#ad9e6893f3310a84fe9b62098d8d9c8ee">atLeastM68020</a>, <a href="#adf5c5e04d2155397699ac6977e8a9f9c">isPositionIndependent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa6a2e45ae404e3f797d2d7e9f3a48949">llvm::CodeModel::Kernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a79ada893fa3a7cbe1b2d180bedcf2ba9">llvm::M68kII::MO_ABSOLUTE_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a14de646b08b938d4b58469a685923fd7">llvm::M68kII::MO_GOTOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68kii/#adb1ef011f9833415094dce191a23ad88a9b5b1d8ef02f8f95a63b78aa46bc9f15">llvm::M68kII::MO_PC_RELATIVE_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a> and <a href="#a8395ba3f6a62aca972d7ab84ab2f84b6">TM</a>.</p>


<p>Referenced by <a href="#a21e59ad505dc01aac3afce8bf62bd948">classifyExternalReference</a> and <a href="#aad702e10e7d2950cb6cfb571a2dddd1d">classifyGlobalReference</a>.</p>

</div>
</div>

### getCallLowering() {#ab4401f6fa6688e269c8d4393c9a35e8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallLowering * M68kSubtarget::getCallLowering ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>Reference <a href="#a73d23f224fac2a282137c2ca7d927b9b">CallLoweringInfo</a>.</p>

</div>
</div>

### getFrameLowering() {#aff5264b89b98c1409fe2ab3137ca4fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const M68kFrameLowering * llvm::M68kSubtarget::getFrameLowering ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Reference <a href="#ae5a8148659f3fc4b2413401bc6be0408">FrameLowering</a>.</p>

</div>
</div>

### getInstrInfo() {#aa6202d7bf1d02aafd7cd6576dc7c4b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const M68kInstrInfo * llvm::M68kSubtarget::getInstrInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Reference <a href="#a523fea9bc9816baef78598f00930a719">InstrInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/structs/anonymous-m68kinstrinfo-cpp-/m68kglobalbasereg/#a04412e72586680e6bfb4ced5a69102c2">anonymous{M68kInstrInfo.cpp}::M68kGlobalBaseReg::runOnMachineFunction</a>.</p>

</div>
</div>

### getInstrItineraryData() {#a65a3aecdb282f800cb548da4a38e67af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItineraryData * llvm::M68kSubtarget::getInstrItineraryData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Reference <a href="#a27dbf15232208a2c6715dd5cdd0b01b5">InstrItins</a>.</p>

</div>
</div>

### getInstructionSelector() {#abcf6092cff04d11cde639c05425242af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector * M68kSubtarget::getInstructionSelector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>Reference <a href="#af6dbae0e87bae59f24d6dd9e925d8e4a">InstSelector</a>.</p>

</div>
</div>

### getJumpTableEncoding() {#ab9b77cf3d4903e5d99c084e4a09ae7fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned M68kSubtarget::getJumpTableEncoding ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>References <a href="#ad9e6893f3310a84fe9b62098d8d9c8ee">atLeastM68020</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3ab0c4687afc1a6858d37711a814f8f5b3">llvm::MachineJumpTableInfo::EK_BlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3a9e655fb625d744f96e03aed78ca85707">llvm::MachineJumpTableInfo::EK_Custom32</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3a6e05991949952d4e85600b0868dcd803">llvm::MachineJumpTableInfo::EK_LabelDifference32</a>, <a href="#adf5c5e04d2155397699ac6977e8a9f9c">isPositionIndependent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a> and <a href="#a8395ba3f6a62aca972d7ab84ab2f84b6">TM</a>.</p>

</div>
</div>

### getLegalizerInfo() {#a489f9f6efa7feaeec084866592c1d14c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo * M68kSubtarget::getLegalizerInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>Reference <a href="#ad96cbb45408d224a6badee6de85a8b34">Legalizer</a>.</p>

</div>
</div>

### getRegBankInfo() {#a6ace610ea65a3d398e730c3248e08101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo * M68kSubtarget::getRegBankInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>Reference <a href="#ac8d8a66a2b639623b8bfa44d84108b45">RegBankInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a>.</p>

</div>
</div>

### getRegisterInfo() {#ad37055600593cd4b591df42904012061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const M68kRegisterInfo * llvm::M68kSubtarget::getRegisterInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Reference <a href="#a523fea9bc9816baef78598f00930a719">InstrInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a>, <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#ac0498ce2d07f3439f81c743d63348181">llvm::M68kTargetLowering::M68kTargetLowering</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#ab96f714528d2891aac3537214fc3a7c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SelectionDAGTargetInfo * llvm::M68kSubtarget::getSelectionDAGInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Reference <a href="#a9aa7e2e789c67eff38bded293ca07412">TSInfo</a>.</p>

</div>
</div>

### getSlotSize() {#a8b38190d70ca6f52984a3b6793ed81d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kSubtarget::getSlotSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getSlotSize - Stack slot size in bytes.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>

</div>
</div>

### getStackAlignment() {#a184c4c6153b92f54e32998afd32050f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::M68kSubtarget::getStackAlignment ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TODO this must be controlled by options like -malign-int and -mshort.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Reference <a href="#acd047227f62bfbc2b220d66440cf3a9d">stackAlignment</a>.</p>


<p>Referenced by <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### getTargetLowering() {#a29c6fdf8471ace3690788857e4d9a8bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const M68kTargetLowering * llvm::M68kSubtarget::getTargetLowering ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Reference <a href="#a95a2acf820e3bdbf8c04921eec32ce21">TLInfo</a>.</p>


<p>Referenced by <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### getTargetTriple() {#a9125638c704b3dd51015f11b0c1b6c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::M68kSubtarget::getTargetTriple ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Reference <a href="#ad5e710e25efca4af480f34c9db58deb0">TargetTriple</a>.</p>

</div>
</div>

### hasFPU() {#a87e7df9801336c4b431a870203bb33cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::hasFPU ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Floating point support.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Reference <a href="#a307bfdbbe1f7e5910262a09a5c9524ef">FPUKind</a>.</p>


<p>Referenced by <a href="#a776f7c2e630dc21f3fb1394e4c40e77b">atLeastM68881</a> and <a href="#a2237e53d68a72fb9f62224ad8a2538bd">atLeastM68882</a>.</p>

</div>
</div>

### initializeSubtargetDependencies() {#ae3337a826c5ca8fe41a7434b9d028943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">M68kSubtarget &amp; M68kSubtarget::initializeSubtargetDependencies (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine">M68kTargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>References <a href="#a27dbf15232208a2c6715dd5cdd0b01b5">InstrItins</a>, <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>, <a href="#a7d0f2ef2893c90937e49f451c469e5d2">ParseSubtargetFeatures</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp/#ad12a5c5a3a72f487cb9d60f4a66b0cd2">selectM68kCPU</a>, <a href="#acd047227f62bfbc2b220d66440cf3a9d">stackAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="#a8395ba3f6a62aca972d7ab84ab2f84b6">TM</a>.</p>


<p>Referenced by <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### isLegalToCallImmediateAddr() {#a712206899f06c86a0216c00713ecb053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kSubtarget::isLegalToCallImmediateAddr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the subtarget allows calls to immediate address.</p>

<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>

</div>
</div>

### isPositionIndependent() {#adf5c5e04d2155397699ac6977e8a9f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kSubtarget::isPositionIndependent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>


<p>Reference <a href="#a8395ba3f6a62aca972d7ab84ab2f84b6">TM</a>.</p>


<p>Referenced by <a href="#a469baae35d6f52f0a01f03f13faba992">classifyBlockAddressReference</a>, <a href="#a21e59ad505dc01aac3afce8bf62bd948">classifyExternalReference</a>, <a href="#aefd7cd9f26f83bf8a9b75572b6fb7c75">classifyGlobalFunctionReference</a>, <a href="#aad702e10e7d2950cb6cfb571a2dddd1d">classifyGlobalReference</a>, <a href="#ac91ce9a25d780116e557aacb80e8be00">classifyLocalReference</a> and <a href="#ab9b77cf3d4903e5d99c084e4a09ae7fb">getJumpTableEncoding</a>.</p>

</div>
</div>

### isRegisterReservedByUser() {#accef3e3df7d94aedf1a7aab8ecf8bd40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::isRegisterReservedByUser (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a67f547ca05d077489e0526079345fff4">UserReservedRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#affb039caf886de8fc67678e1dfd83b83">llvm::M68kRegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### isTargetELF() {#af2b44b6b0df87a94622717c8a8559547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::isTargetELF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Reference <a href="#ad5e710e25efca4af480f34c9db58deb0">TargetTriple</a>.</p>

</div>
</div>

### ParseSubtargetFeatures() {#a7d0f2ef2893c90937e49f451c469e5d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::M68kSubtarget::ParseSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses features string setting specified subtarget options.</p>


<p>Definition of function is auto generated by tblgen.</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae3337a826c5ca8fe41a7434b9d028943">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### useSmallSection() {#abd27b26d2f85c507893fc784a1073a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::useSmallSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Reference <a href="#a70686cd734402136e07aac16b920f1d4">UseSmallSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a99f0c7df2b60b4316fac003d88fab460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kSubtarget::anchor ()</td>
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



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CallLoweringInfo {#a73d23f224fac2a282137c2ca7d927b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CallLowering&gt; llvm::M68kSubtarget::CallLoweringInfo</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#ab4401f6fa6688e269c8d4393c9a35e8a">getCallLowering</a> and <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### FPUKind {#a307bfdbbe1f7e5910262a09a5c9524ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;FPKindEnum&gt; llvm::M68kSubtarget::FPUKind</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#a776f7c2e630dc21f3fb1394e4c40e77b">atLeastM68881</a>, <a href="#a2237e53d68a72fb9f62224ad8a2538bd">atLeastM68882</a> and <a href="#a87e7df9801336c4b431a870203bb33cd">hasFPU</a>.</p>

</div>
</div>

### FrameLowering {#ae5a8148659f3fc4b2413401bc6be0408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">M68kFrameLowering llvm::M68kSubtarget::FrameLowering</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#aff5264b89b98c1409fe2ab3137ca4fed">getFrameLowering</a> and <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### InstrInfo {#a523fea9bc9816baef78598f00930a719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">M68kInstrInfo llvm::M68kSubtarget::InstrInfo</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa6202d7bf1d02aafd7cd6576dc7c4b03">getInstrInfo</a>, <a href="#ad37055600593cd4b591df42904012061">getRegisterInfo</a> and <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### InstrItins {#a27dbf15232208a2c6715dd5cdd0b01b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrItineraryData llvm::M68kSubtarget::InstrItins</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#a65a3aecdb282f800cb548da4a38e67af">getInstrItineraryData</a> and <a href="#ae3337a826c5ca8fe41a7434b9d028943">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### InstSelector {#af6dbae0e87bae59f24d6dd9e925d8e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InstructionSelector&gt; llvm::M68kSubtarget::InstSelector</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#abcf6092cff04d11cde639c05425242af">getInstructionSelector</a> and <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### Legalizer {#ad96cbb45408d224a6badee6de85a8b34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LegalizerInfo&gt; llvm::M68kSubtarget::Legalizer</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#a489f9f6efa7feaeec084866592c1d14c">getLegalizerInfo</a> and <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### RegBankInfo {#ac8d8a66a2b639623b8bfa44d84108b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;RegisterBankInfo&gt; llvm::M68kSubtarget::RegBankInfo</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#a6ace610ea65a3d398e730c3248e08101">getRegBankInfo</a> and <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### stackAlignment {#acd047227f62bfbc2b220d66440cf3a9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kSubtarget::stackAlignment = 8</td>
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

<p>The minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#a184c4c6153b92f54e32998afd32050f1">getStackAlignment</a> and <a href="#ae3337a826c5ca8fe41a7434b9d028943">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### SubtargetKind {#a3a458064b0de00d07bcc3b7fefb02dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubtargetEnum llvm::M68kSubtarget::SubtargetKind = <a href="#a3e08e796415db68db09a89fbac110854acccb0e62e055d92ef8015793186c2af5">M00</a></td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#aaf27395c3301b22c5be794ec0016f515">atLeastM68000</a>, <a href="#ac5305349832a95730232c2ccc3153e44">atLeastM68010</a>, <a href="#ad9e6893f3310a84fe9b62098d8d9c8ee">atLeastM68020</a>, <a href="#ae64d0873845e1183f99d9290df65339c">atLeastM68030</a>, <a href="#a3c800ad6f467ea69b0ede3e84b3dbbd2">atLeastM68040</a> and <a href="#a2f3a2e6be55789bc750fe56501a27a38">atLeastM68060</a>.</p>

</div>
</div>

### TargetTriple {#ad5e710e25efca4af480f34c9db58deb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::M68kSubtarget::TargetTriple</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#a9125638c704b3dd51015f11b0c1b6c56">getTargetTriple</a>, <a href="#af2b44b6b0df87a94622717c8a8559547">isTargetELF</a> and <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### TLInfo {#a95a2acf820e3bdbf8c04921eec32ce21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">M68kTargetLowering llvm::M68kSubtarget::TLInfo</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#a29c6fdf8471ace3690788857e4d9a8bd">getTargetLowering</a> and <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### TM {#a8395ba3f6a62aca972d7ab84ab2f84b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const M68kTargetMachine&amp; llvm::M68kSubtarget::TM</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#a469baae35d6f52f0a01f03f13faba992">classifyBlockAddressReference</a>, <a href="#a21e59ad505dc01aac3afce8bf62bd948">classifyExternalReference</a>, <a href="#aefd7cd9f26f83bf8a9b75572b6fb7c75">classifyGlobalFunctionReference</a>, <a href="#aad702e10e7d2950cb6cfb571a2dddd1d">classifyGlobalReference</a>, <a href="#ac91ce9a25d780116e557aacb80e8be00">classifyLocalReference</a>, <a href="#ab9b77cf3d4903e5d99c084e4a09ae7fb">getJumpTableEncoding</a>, <a href="#ae3337a826c5ca8fe41a7434b9d028943">initializeSubtargetDependencies</a>, <a href="#adf5c5e04d2155397699ac6977e8a9f9c">isPositionIndependent</a> and <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### TSInfo {#a9aa7e2e789c67eff38bded293ca07412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAGTargetInfo llvm::M68kSubtarget::TSInfo</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#ab96f714528d2891aac3537214fc3a7c6">getSelectionDAGInfo</a> and <a href="#a354c9b3558a69622cbcbd3d7f32730ed">M68kSubtarget</a>.</p>

</div>
</div>

### UserReservedRegister {#a67f547ca05d077489e0526079345fff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::bitset&lt;M68k::NUM_TARGET_REGS&gt; llvm::M68kSubtarget::UserReservedRegister</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#accef3e3df7d94aedf1a7aab8ecf8bd40">isRegisterReservedByUser</a>.</p>

</div>
</div>

### UseSmallSection {#a70686cd734402136e07aac16b920f1d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kSubtarget::UseSmallSection = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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

<p>Small section is used.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a>.</p>


<p>Referenced by <a href="#abd27b26d2f85c507893fc784a1073a2a">useSmallSection</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-cpp">M68kSubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ksubtarget-h">M68kSubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
