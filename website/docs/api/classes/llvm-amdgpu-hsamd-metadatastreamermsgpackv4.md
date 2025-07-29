---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MetadataStreamerMsgPackV4` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">Target/AMDGPU/AMDGPUHSAMetadataStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamer">MetadataStreamer</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5">MetadataStreamerMsgPackV5</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eb65ed492c68bd9d20d5203c5e85c48">MetadataStreamerMsgPackV4</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ff815479f22e7490dfcdf74080d2c0">~MetadataStreamerMsgPackV4</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60682ebeccc6d8a4c4fb8458c6ed186e">emitTo</a> (AMDGPUTargetStreamer &amp;TargetStreamer) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e4f1ee036e76220fa5c2b0e021a829c">begin</a> (const Module &amp;Mod, const IsaInfo::AMDGPUTargetID &amp;TargetID) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6bd85a0e2d2b53c2f59708830ba3c6b">end</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae84e80460e1a14732ae49e64b8bbf9f6">emitKernel</a> (const MachineFunction &amp;MF, const SIProgramInfo &amp;ProgramInfo) override</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bb3067fda5d6c61a6061d7b309a6637">dump</a> (StringRef HSAMetadataString) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab08f2a767eab0b5eb8db953d35d80b03">verify</a> (StringRef HSAMetadataString) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14772fdd5684682678e840fcee863a55">getAccessQualifier</a> (StringRef AccQual) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f43a155ccf31ff80ae9800335e1d00b">getAddressSpaceQualifier</a> (unsigned AddressSpace) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb7bfed2c40e61784a27f7a7ccb150a8">getValueKind</a> (Type *Ty, StringRef TypeQual, StringRef BaseTypeName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7054658e60a8af1dad40ecdd024effd1">getTypeName</a> (Type *Ty, bool Signed) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode">msgpack::ArrayDocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa4b05292a7268cac4e8261332c3706">getWorkGroupDimensions</a> (MDNode *Node) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f77187b94b2e4b729590a1f9a6ba51">getHSAKernelProps</a> (const MachineFunction &amp;MF, const SIProgramInfo &amp;ProgramInfo, unsigned CodeObjectVersion) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a229d7465aca8cd0ed22b48fee261acd7">emitVersion</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a935ca0164610567e453bd629e5f6da0e">emitTargetID</a> (const IsaInfo::AMDGPUTargetID &amp;TargetID)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc867d6ad46b3c88e5d98f3554c23e17">emitPrintf</a> (const Module &amp;Mod)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a161232fcda35d33312029e1d80015b77">emitKernelLanguage</a> (const Function &amp;Func, msgpack::MapDocNode Kern)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2877b4f51a65483c451edd59a4704df6">emitKernelAttrs</a> (const Function &amp;Func, msgpack::MapDocNode Kern) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b03142a1121fe88b2532c8240d0145">emitKernelArgs</a> (const MachineFunction &amp;MF, msgpack::MapDocNode Kern)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e6dc274c7730d43ef8505856e984fa4">emitKernelArg</a> (const Argument &amp;Arg, unsigned &amp;Offset, msgpack::ArrayDocNode Args)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684f6b8b5cfa3d9d70c557c1d019ac62">emitKernelArg</a> (const DataLayout &amp;DL, Type *Ty, Align Alignment, StringRef ValueKind, unsigned &amp;Offset, msgpack::ArrayDocNode Args, MaybeAlign PointeeAlign=std::nullopt, StringRef Name="", StringRef TypeName="", StringRef BaseTypeName="", StringRef ActAccQual="", StringRef AccQual="", StringRef TypeQual="")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25976638e06c5f87d1dd439602f1f8c">emitHiddenKernelArgs</a> (const MachineFunction &amp;MF, unsigned &amp;Offset, msgpack::ArrayDocNode Args) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf300e8da7dffcd11a0a3d1081af1e1">getRootMetadata</a> (StringRef Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f4772f8f6ef6016d6ab24b6857d645">getHSAMetadataRoot</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/delayedmcexprs">DelayedMCExprs</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a148871537413916a535e572612a48529">DelayedExprs</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">msgpack::Document</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a> = ...</td>
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


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MetadataStreamerMsgPackV4() {#a3eb65ed492c68bd9d20d5203c5e85c48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::MetadataStreamerMsgPackV4 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MetadataStreamerMsgPackV4() {#a25ff815479f22e7490dfcdf74080d2c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::~MetadataStreamerMsgPackV4 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>.</p>


<p>References <a href="#a8e4f1ee036e76220fa5c2b0e021a829c">begin</a>, <a href="#ae84e80460e1a14732ae49e64b8bbf9f6">emitKernel</a>, <a href="#a60682ebeccc6d8a4c4fb8458c6ed186e">emitTo</a>, <a href="#aa6bd85a0e2d2b53c2f59708830ba3c6b">end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a8e4f1ee036e76220fa5c2b0e021a829c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::begin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid">IsaInfo::AMDGPUTargetID</a> &amp; TargetID)</td>
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



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="#a148871537413916a535e572612a48529">DelayedExprs</a>, <a href="#afc867d6ad46b3c88e5d98f3554c23e17">emitPrintf</a>, <a href="#a935ca0164610567e453bd629e5f6da0e">emitTargetID</a>, <a href="#a229d7465aca8cd0ed22b48fee261acd7">emitVersion</a>, <a href="#aeaf300e8da7dffcd11a0a3d1081af1e1">getRootMetadata</a>, <a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>.</p>


<p>Referenced by <a href="#a25ff815479f22e7490dfcdf74080d2c0">~MetadataStreamerMsgPackV4</a>.</p>

</div>
</div>

### emitKernel() {#ae84e80460e1a14732ae49e64b8bbf9f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/siprograminfo">SIProgramInfo</a> &amp; ProgramInfo)</td>
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



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca27a385675142c462571165c839e41aa0">llvm::CallingConv::AMDGPU_KERNEL</a>, <a href="#a64b03142a1121fe88b2532c8240d0145">emitKernelArgs</a>, <a href="#a2877b4f51a65483c451edd59a4704df6">emitKernelAttrs</a>, <a href="#a161232fcda35d33312029e1d80015b77">emitKernelLanguage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f9a0bcc6ecfeef7109258c6a8012978">llvm::AMDGPU::getAMDHSACodeObjectVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a83e993c73d12663a129d46cd3e1fb1b5">llvm::msgpack::DocNode::getArray</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="#a22f77187b94b2e4b729590a1f9a6ba51">getHSAKernelProps</a>, <a href="#aeaf300e8da7dffcd11a0a3d1081af1e1">getRootMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9b5e79699935bf721647d44339701860">llvm::CallingConv::SPIR_KERNEL</a>.</p>


<p>Referenced by <a href="#a25ff815479f22e7490dfcdf74080d2c0">~MetadataStreamerMsgPackV4</a>.</p>

</div>
</div>

### emitTo() {#a60682ebeccc6d8a4c4fb8458c6ed186e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitTo (<a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer">AMDGPUTargetStreamer</a> &amp; TargetStreamer)</td>
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



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="#a148871537413916a535e572612a48529">DelayedExprs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#a02fc438fa1d605d806b8bef3c1d6e9a1">llvm::AMDGPUTargetStreamer::EmitHSAMetadata</a> and <a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a>.</p>


<p>Referenced by <a href="#a25ff815479f22e7490dfcdf74080d2c0">~MetadataStreamerMsgPackV4</a>.</p>

</div>
</div>

### end() {#aa6bd85a0e2d2b53c2f59708830ba3c6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::end ()</td>
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



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="#a148871537413916a535e572612a48529">DelayedExprs</a>, <a href="#a7bb3067fda5d6c61a6061d7b309a6637">dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cacb70bba6afdd01831243076fa5930">llvm::DumpHSAMetadata</a>, <a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a593cc2f204f7b2edc16ee222c37c3196">verify</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a17f63fdfe7ab20266c37dcb16400003e">llvm::VerifyHSAMetadata</a>.</p>


<p>Referenced by <a href="#a25ff815479f22e7490dfcdf74080d2c0">~MetadataStreamerMsgPackV4</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### dump() {#a7bb3067fda5d6c61a6061d7b309a6637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::dump (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> HSAMetadataString)</td>
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



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>.</p>


<p>Referenced by <a href="#aa6bd85a0e2d2b53c2f59708830ba3c6b">end</a>.</p>

</div>
</div>

### emitHiddenKernelArgs() {#ae25976638e06c5f87d1dd439602f1f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitHiddenKernelArgs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode">msgpack::ArrayDocNode</a> Args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a8e6dc274c7730d43ef8505856e984fa4">emitKernelArg</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a64b03142a1121fe88b2532c8240d0145">emitKernelArgs</a>.</p>

</div>
</div>

### emitKernelArg() {#a8e6dc274c7730d43ef8505856e984fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp; Arg, unsigned &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode">msgpack::ArrayDocNode</a> Args)</td>
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



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a8e6dc274c7730d43ef8505856e984fa4">emitKernelArg</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#ab205d366b1137026c32f5678f7cc2726">llvm::Argument::getArgNo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp/#af00d722295f4e7b769e28af02fbefc1f">getArgumentTypeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#acc5053f382c68b8dbdb3fae1b477441a">llvm::Argument::getParamAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#a1247bbc672e07bf7e30e147cd1990dc3">llvm::Argument::getParamByRefType</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#a862c73765000251be786c801260ba7c1">llvm::Argument::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#adb7bfed2c40e61784a27f7a7ccb150a8">getValueKind</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#a66059696916025f0f9d7ea35454a85fe">llvm::Argument::hasAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#a4c2b9814461b8632c4b956771722a05e">llvm::Argument::hasByRefAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#a3c0d4963c5d582a10687fbbad9040f20">llvm::Argument::hasNoAliasAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#a605c20365a110ba796d3379e83ae733d">llvm::Argument::onlyReadsMemory</a> and <a href="/web-llvm/docs/api/structs/llvm/maybealign/#a06846474be3ab85f8d30c388faf3b116">llvm::MaybeAlign::valueOrOne</a>.</p>


<p>Referenced by <a href="#ae25976638e06c5f87d1dd439602f1f8c">emitHiddenKernelArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#a00df0d04b86c6d3d0d027c912afb7282">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitHiddenKernelArgs</a>, <a href="#a8e6dc274c7730d43ef8505856e984fa4">emitKernelArg</a> and <a href="#a64b03142a1121fe88b2532c8240d0145">emitKernelArgs</a>.</p>

</div>
</div>

### emitKernelArg() {#a684f6b8b5cfa3d9d70c557c1d019ac62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ValueKind, unsigned &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode">msgpack::ArrayDocNode</a> Args, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> PointeeAlign=std::nullopt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name="", <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeName="", <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BaseTypeName="", <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ActAccQual="", <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> AccQual="", <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeQual="")</td>
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



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a14772fdd5684682678e840fcee863a55">getAccessQualifier</a>, <a href="#a0f43a155ccf31ff80ae9800335e1d00b">getAddressSpaceQualifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>

</div>
</div>

### emitKernelArgs() {#a64b03142a1121fe88b2532c8240d0145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArgs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a> Kern)</td>
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



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="#ae25976638e06c5f87d1dd439602f1f8c">emitHiddenKernelArgs</a>, <a href="#a8e6dc274c7730d43ef8505856e984fa4">emitKernelArg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#ae84e80460e1a14732ae49e64b8bbf9f6">emitKernel</a>.</p>

</div>
</div>

### emitKernelAttrs() {#a2877b4f51a65483c451edd59a4704df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a> Kern)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac1b702e99f1978f2dd36cac2f7400f">llvm::getTypeName</a> and <a href="#a0fa4b05292a7268cac4e8261332c3706">getWorkGroupDimensions</a>.</p>


<p>Referenced by <a href="#ae84e80460e1a14732ae49e64b8bbf9f6">emitKernel</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#ae8b78bc8c92db11a11ca0cf7f7fc6f90">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitKernelAttrs</a>.</p>

</div>
</div>

### emitKernelLanguage() {#a161232fcda35d33312029e1d80015b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelLanguage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a> Kern)</td>
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



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6e361fdc7f6a0c9dd44e46c0f020b46e">llvm::msgpack::Document::getArrayNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>.</p>


<p>Referenced by <a href="#ae84e80460e1a14732ae49e64b8bbf9f6">emitKernel</a>.</p>

</div>
</div>

### emitPrintf() {#afc867d6ad46b3c88e5d98f3554c23e17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitPrintf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod)</td>
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



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aeaf300e8da7dffcd11a0a3d1081af1e1">getRootMetadata</a>, <a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>.</p>


<p>Referenced by <a href="#a8e4f1ee036e76220fa5c2b0e021a829c">begin</a>.</p>

</div>
</div>

### emitTargetID() {#a935ca0164610567e453bd629e5f6da0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitTargetID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid">IsaInfo::AMDGPUTargetID</a> &amp; TargetID)</td>
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



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="#aeaf300e8da7dffcd11a0a3d1081af1e1">getRootMetadata</a>, <a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid/#ae9ec355054ee6400df6ba242dd3cb032">llvm::AMDGPU::IsaInfo::AMDGPUTargetID::toString</a>.</p>


<p>Referenced by <a href="#a8e4f1ee036e76220fa5c2b0e021a829c">begin</a>.</p>

</div>
</div>

### emitVersion() {#a229d7465aca8cd0ed22b48fee261acd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitVersion ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="#aeaf300e8da7dffcd11a0a3d1081af1e1">getRootMetadata</a>, <a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#afa1ccf366a7f5fac345e2a5a214ed73b">llvm::AMDGPU::HSAMD::VersionMajorV4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#a7e6fa158a96c4d1a9fd48eff2a740b93">llvm::AMDGPU::HSAMD::VersionMinorV4</a>.</p>


<p>Referenced by <a href="#a8e4f1ee036e76220fa5c2b0e021a829c">begin</a>.</p>

</div>
</div>

### getAccessQualifier() {#a14772fdd5684682678e840fcee863a55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getAccessQualifier (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> AccQual)</td>
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



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a> and <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>


<p>Referenced by <a href="#a684f6b8b5cfa3d9d70c557c1d019ac62">emitKernelArg</a>.</p>

</div>
</div>

### getAddressSpaceQualifier() {#a0f43a155ccf31ff80ae9800335e1d00b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getAddressSpaceQualifier (unsigned AddressSpace)</td>
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



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aa6d3112da64eecbdbb50aacb5f8251e8">llvm::AMDGPUAS::CONSTANT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aaa1e27e4fc68e5706a4b7bbaed447c14">llvm::AMDGPUAS::FLAT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a5b71ba6fa435ec288aba849e113721a7">llvm::AMDGPUAS::REGION_ADDRESS</a>.</p>


<p>Referenced by <a href="#a684f6b8b5cfa3d9d70c557c1d019ac62">emitKernelArg</a>.</p>

</div>
</div>

### getHSAKernelProps() {#a22f77187b94b2e4b729590a1f9a6ba51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::MapDocNode llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getHSAKernelProps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/siprograminfo">SIProgramInfo</a> &amp; ProgramInfo, unsigned CodeObjectVersion)</td>
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



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a30475b065bebd7bc81d1112d9067d772abd2438b14a6a1a27fae653284aaa3cb4">llvm::AMDGPU::AMDHSA_COV5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">llvm::msgpack::Boolean</a>, <a href="#a148871537413916a535e572612a48529">DelayedExprs</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a9e3a05260c49da2e5a9401472ca63d77">llvm::SIProgramInfo::DynamicCallStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a76976ccb29b7c0317d800e4dcd294ddb">llvm::AMDGPUSubtarget::getKernArgSegmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#ae66cd705df2870244a05921f551ff131">llvm::AMDGPUSubtarget::getWavefrontSize</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a278004c824cd46c7504e68ec7c5f2d57">llvm::GCNSubtarget::hasMAIInsts</a>, <a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#abf43be02eb6dd6450cf63b501f0f8f34">llvm::SIProgramInfo::LDSSize</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a98ea97b3ad31203bdf6769b105caa624">llvm::SIProgramInfo::NumAccVGPR</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a0a030caf65eb1d46c0fc1045e197e0ed">llvm::SIProgramInfo::NumSGPR</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#aad1837db2b83530ed07c95b6bac0744b">llvm::SIProgramInfo::NumVGPR</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ac3752448069c8c6edb67b57e0ac92f85">llvm::SIProgramInfo::ScratchSize</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#aa99f892ef918babd54c99742f34d6548">llvm::GCNSubtarget::supportsWGP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a> and <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ac559e84953a041d04f27c9a1063a1c59">llvm::SIProgramInfo::WgpMode</a>.</p>


<p>Referenced by <a href="#ae84e80460e1a14732ae49e64b8bbf9f6">emitKernel</a>.</p>

</div>
</div>

### getHSAMetadataRoot() {#ae2f4772f8f6ef6016d6ab24b6857d645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode &amp; llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getHSAMetadataRoot ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>.</p>


<p>Reference <a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a>.</p>

</div>
</div>

### getRootMetadata() {#aeaf300e8da7dffcd11a0a3d1081af1e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode &amp; llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getRootMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>.</p>


<p>Reference <a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a>.</p>


<p>Referenced by <a href="#a8e4f1ee036e76220fa5c2b0e021a829c">begin</a>, <a href="#ae84e80460e1a14732ae49e64b8bbf9f6">emitKernel</a>, <a href="#afc867d6ad46b3c88e5d98f3554c23e17">emitPrintf</a>, <a href="#a935ca0164610567e453bd629e5f6da0e">emitTargetID</a>, <a href="#a229d7465aca8cd0ed22b48fee261acd7">emitVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#a7b11851cdd1ebd21039cab1ec7841bf2">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv6/#a749e690658440b384eef01bcd282f796">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV6::emitVersion</a>.</p>

</div>
</div>

### getTypeName() {#a7054658e60a8af1dad40ecdd024effd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getTypeName (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool Signed)</td>
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



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac1b702e99f1978f2dd36cac2f7400f">llvm::getTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">llvm::Type::HalfTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>

</div>
</div>

### getValueKind() {#adb7bfed2c40e61784a27f7a7ccb150a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getValueKind (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeQual, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BaseTypeName)</td>
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



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a83a294111af6d4412163b209725ca556">llvm::StringRef::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>.</p>


<p>Referenced by <a href="#a8e6dc274c7730d43ef8505856e984fa4">emitKernelArg</a>.</p>

</div>
</div>

### getWorkGroupDimensions() {#a0fa4b05292a7268cac4e8261332c3706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::ArrayDocNode llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getWorkGroupDimensions (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Node)</td>
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



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a> and <a href="#a294fcc482ed4fc5eeaf6ad552a1d62dc">HSAMetadataDoc</a>.</p>


<p>Referenced by <a href="#a2877b4f51a65483c451edd59a4704df6">emitKernelAttrs</a>.</p>

</div>
</div>

### verify() {#ab08f2a767eab0b5eb8db953d35d80b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::verify (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> HSAMetadataString)</td>
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



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#abec5174f9edec79de20397f6b8e0ccdf">llvm::msgpack::Document::fromYAML</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a82205f2c71cb88331e554cb4fc8b8822">llvm::msgpack::Document::toYAML</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DelayedExprs {#a148871537413916a535e572612a48529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DelayedMCExprs&gt; llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::DelayedExprs</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      std::make_unique&lt;<a href="/web-llvm/docs/api/classes/llvm/delayedmcexprs">DelayedMCExprs</a>&gt;()
</div>
</dd>
</dl>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>.</p>


<p>Referenced by <a href="#a8e4f1ee036e76220fa5c2b0e021a829c">begin</a>, <a href="#a60682ebeccc6d8a4c4fb8458c6ed186e">emitTo</a>, <a href="#aa6bd85a0e2d2b53c2f59708830ba3c6b">end</a> and <a href="#a22f77187b94b2e4b729590a1f9a6ba51">getHSAKernelProps</a>.</p>

</div>
</div>

### HSAMetadataDoc {#a294fcc482ed4fc5eeaf6ad552a1d62dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;msgpack::Document&gt; llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::HSAMetadataDoc</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      std::make_unique&lt;<a href="/web-llvm/docs/api/classes/llvm/msgpack/document">msgpack::Document</a>&gt;()
</div>
</dd>
</dl>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a>.</p>


<p>Referenced by <a href="#a8e4f1ee036e76220fa5c2b0e021a829c">begin</a>, <a href="#a64b03142a1121fe88b2532c8240d0145">emitKernelArgs</a>, <a href="#afc867d6ad46b3c88e5d98f3554c23e17">emitPrintf</a>, <a href="#a935ca0164610567e453bd629e5f6da0e">emitTargetID</a>, <a href="#a60682ebeccc6d8a4c4fb8458c6ed186e">emitTo</a>, <a href="#a229d7465aca8cd0ed22b48fee261acd7">emitVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#a7b11851cdd1ebd21039cab1ec7841bf2">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv6/#a749e690658440b384eef01bcd282f796">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV6::emitVersion</a>, <a href="#aa6bd85a0e2d2b53c2f59708830ba3c6b">end</a>, <a href="#a22f77187b94b2e4b729590a1f9a6ba51">getHSAKernelProps</a>, <a href="#ae2f4772f8f6ef6016d6ab24b6857d645">getHSAMetadataRoot</a>, <a href="#aeaf300e8da7dffcd11a0a3d1081af1e1">getRootMetadata</a> and <a href="#a0fa4b05292a7268cac4e8261332c3706">getWorkGroupDimensions</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp">AMDGPUHSAMetadataStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-h">AMDGPUHSAMetadataStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
