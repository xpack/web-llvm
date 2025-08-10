---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/stackmaps
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `StackMaps` Class



## Declaration

<div class="doxyDeclaration">
class llvm::StackMaps { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">llvm/CodeGen/StackMaps.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239279fa569564dff1d5ed13903c8f00">OpType</a> = enum { DirectMemRefOp, IndirectMemRefOp, ConstantOp }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd10846f022ea0ca579e64604ab40604">LocationVec</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/stackmaps/location">Location</a>, 8 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85a4bfddff0c7f8d3f474788a2e8a5d0">LiveOutVec</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/stackmaps/liveoutreg">LiveOutReg</a>, 8 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9567d7a87531ba41848dbded854caa76">ConstantPool</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; uint64_t, uint64_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa82c7ebb50f79e9f4e8be394ff1f4280">FnInfoMap</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/structs/llvm/stackmaps/functioninfo">FunctionInfo</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfa1a29a881b7acc55117704cf0f6c4c">CallsiteInfoList</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/stackmaps/callsiteinfo">CallsiteInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a776c51f82ece4ef812e2bd3015977d">StackMaps</a> (AsmPrinter &amp;AP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a8f4a1317037479dc1bd2306412ea5">reset</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e0d21e7b7d893213aff8459e87c6c2">recordStackMap</a> (const MCSymbol &amp;L, const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a stackmap record for a stackmap instruction. <a href="#ae7e0d21e7b7d893213aff8459e87c6c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29d96c130705fae151f95b1215e7ea2">recordPatchPoint</a> (const MCSymbol &amp;L, const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a stackmap record for a patchpoint instruction. <a href="#ac29d96c130705fae151f95b1215e7ea2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf7e8cc29c69ba598ca74cdaf4684f1b">recordStatepoint</a> (const MCSymbol &amp;L, const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a stackmap record for a statepoint instruction. <a href="#abf7e8cc29c69ba598ca74cdaf4684f1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f17d34c6ec33d574438b69fa43c2e2">serializeToStackMapSection</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there is any stack map data, create a stack map section and serialize the map info into it. <a href="#a64f17d34c6ec33d574438b69fa43c2e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abfa1a29a881b7acc55117704cf0f6c4c">CallsiteInfoList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8cdb111ecc3aa30169e1cd09c429dc7">getCSInfos</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get call site info. <a href="#ad8cdb111ecc3aa30169e1cd09c429dc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa82c7ebb50f79e9f4e8be394ff1f4280">FnInfoMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1d146def33c43931a7aad77bdf5dfc7">getFnInfos</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get function info. <a href="#ad1d146def33c43931a7aad77bdf5dfc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a476971826fa13b07e28ad971ec5a3234">MachineInstr::const_mop_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf2e24eb3d06ba9b5d137f17e07d87a">parseOperand</a> (MachineInstr::const_mop_iterator MOI, MachineInstr::const_mop_iterator MOE, LocationVec &amp;Locs, LiveOutVec &amp;LiveOuts)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac31350f79e49c00cdead92c9138083f">parseStatepointOpers</a> (const MachineInstr &amp;MI, MachineInstr::const_mop_iterator MOI, MachineInstr::const_mop_iterator MOE, LocationVec &amp;Locations, LiveOutVec &amp;LiveOuts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialized parser of statepoint operands. <a href="#aac31350f79e49c00cdead92c9138083f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/stackmaps/liveoutreg">LiveOutReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6818a685c56f97e679e383ed566d5608">createLiveOutReg</a> (unsigned Reg, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a live-out register record for the given register <span class="doxyComputerOutput">Reg</span>. <a href="#a6818a685c56f97e679e383ed566d5608">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a85a4bfddff0c7f8d3f474788a2e8a5d0">LiveOutVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe63ab7253698f19218bd95182f736b9">parseRegisterLiveOutMask</a> (const uint32_t *Mask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the register live-out mask and return a vector of live-out registers that need to be recorded in the stackmap. <a href="#afe63ab7253698f19218bd95182f736b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2dc521e0ab30d61650dbc875cecb0b">recordStackMapOpers</a> (const MCSymbol &amp;L, const MachineInstr &amp;MI, uint64_t ID, MachineInstr::const_mop_iterator MOI, MachineInstr::const_mop_iterator MOE, bool recordResult=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the locations of the operands of the provided instruction in a record keyed by the provided label. <a href="#a4c2dc521e0ab30d61650dbc875cecb0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ce0ba2ca1ab3cd09e74c2335effd0ab">emitStackmapHeader</a> (MCStreamer &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the stackmap header. <a href="#a4ce0ba2ca1ab3cd09e74c2335effd0ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a0d880814cbfa68ee095fb35bc1ba3b">emitFunctionFrameRecords</a> (MCStreamer &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the function frame record for each function. <a href="#a9a0d880814cbfa68ee095fb35bc1ba3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a621d8c17c3a444567991bd1c8077676e">emitConstantPoolEntries</a> (MCStreamer &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the constant pool. <a href="#a621d8c17c3a444567991bd1c8077676e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b5ea170fffe072b252dec9bd7dd5edf">emitCallsiteEntries</a> (MCStreamer &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the callsite info for each stackmap/patchpoint intrinsic call. <a href="#a1b5ea170fffe072b252dec9bd7dd5edf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af6a5531e112d693fbdec53101ba1a3">print</a> (raw_ostream &amp;OS)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135b3048b4bd834fa030e41fa9376b6d">debug</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e94f85c07dfe78b4bea1a4736237cdd">AP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abfa1a29a881b7acc55117704cf0f6c4c">CallsiteInfoList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab10225515f2bc6a1d7da6d7a7a99a083">CSInfos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9567d7a87531ba41848dbded854caa76">ConstantPool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ff9d048c0e3387901cf2d59b8c25d54">ConstPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa82c7ebb50f79e9f4e8be394ff1f4280">FnInfoMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18a77bb3539214254882e23b8ad94dd8">FnInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0678a1f52ff04158310e4157e81282f6">getNextMetaArgIdx</a> (const MachineInstr *MI, unsigned CurIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of next meta operand. <a href="#a0678a1f52ff04158310e4157e81282f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4e28b6a926e8f7a66cae35d70736a3">WSMP</a> = "Stack Maps: "</td>
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


<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CallsiteInfoList {#abfa1a29a881b7acc55117704cf0f6c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StackMaps::CallsiteInfoList =  std::vector&lt;CallsiteInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### ConstantPool {#a9567d7a87531ba41848dbded854caa76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StackMaps::ConstantPool =  MapVector&lt;uint64_t, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### FnInfoMap {#aa82c7ebb50f79e9f4e8be394ff1f4280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StackMaps::FnInfoMap =  MapVector&lt;const MCSymbol *, FunctionInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### LiveOutVec {#a85a4bfddff0c7f8d3f474788a2e8a5d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StackMaps::LiveOutVec =  SmallVector&lt;LiveOutReg, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### LocationVec {#abd10846f022ea0ca579e64604ab40604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StackMaps::LocationVec =  SmallVector&lt;Location, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### OpType {#a239279fa569564dff1d5ed13903c8f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StackMaps::OpType =  enum { DirectMemRefOp, IndirectMemRefOp, ConstantOp }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### StackMaps() {#a1a776c51f82ece4ef812e2bd3015977d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackMaps::StackMaps (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp; AP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp/#aae273634bb88a1299e1793fed99d8022">StackMapVersion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCSInfos() {#ad8cdb111ecc3aa30169e1cd09c429dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteInfoList &amp; llvm::StackMaps::getCSInfos ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get call site info.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### getFnInfos() {#ad1d146def33c43931a7aad77bdf5dfc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FnInfoMap &amp; llvm::StackMaps::getFnInfos ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get function info.</p>

<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### recordPatchPoint() {#ac29d96c130705fae151f95b1215e7ea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackMaps::recordPatchPoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate a stackmap record for a patchpoint instruction.</p>

<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a5a3543b67035589350015920ce01b489">llvm::PatchPointOpers::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a261d8b16e91a9c713a7679ba25f99dff">llvm::PatchPointOpers::getNumCallArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#adf81f2558ea3364922ba63cb46e09ca4">llvm::PatchPointOpers::getStackMapStartIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#af55421adc5b3812f574f7dd5177899e5">llvm::PatchPointOpers::hasDef</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#aa2483e2d41750caf41e314334d91538b">llvm::PatchPointOpers::isAnyReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/structs/llvm/stackmaps/location/#af9d5c323fe88901a1b584492c00e892aa26d1f3569991555e23e97ec24e7d1a5b">llvm::StackMaps::Location::Register</a>.</p>

</div>
</div>

### recordStackMap() {#ae7e0d21e7b7d893213aff8459e87c6c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackMaps::recordStackMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate a stackmap record for a stackmap instruction.</p>


<p>MI must be a raw STACKMAP, not a PATCHPOINT.</p>


<p>Declaration at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stackmapopers/#ab3789a35b591042c5b16a7db57572298">llvm::StackMapOpers::getVarIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a6892641fbb4193030fe2ad0108407e06a08353423e1d98722d846a7c35ac15dc5">llvm::PatchPointOpers::IDPos</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### recordStatepoint() {#abf7e8cc29c69ba598ca74cdaf4684f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackMaps::recordStatepoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate a stackmap record for a statepoint instruction.</p>

<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#af92f104836fb6bba872e578682a0e65f">llvm::StatepointOpers::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#afdfbc7a83c5d0400c01becf8ff27eba3">llvm::StatepointOpers::getVarIdx</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### reset() {#ad8a8f4a1317037479dc1bd2306412ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StackMaps::reset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### serializeToStackMapSection() {#a64f17d34c6ec33d574438b69fa43c2e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackMaps::serializeToStackMapSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there is any stack map data, create a stack map section and serialize the map info into it.</p>


<p>Serialize the stackmap data.</p>


<p>This clears the stack map data structures afterwards.</p>


<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a06efd6f3d736ec481ab81ab2c574bbe6">llvm::MCStreamer::addBlankLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#aaded1e857e3e6aa44d76a3a967624818">llvm::MCObjectFileInfo::getStackMapSection</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createLiveOutReg() {#a6818a685c56f97e679e383ed566d5608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackMaps::LiveOutReg StackMaps::createLiveOutReg (unsigned Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a live-out register record for the given register <span class="doxyComputerOutput">Reg</span>.</p>


<p>Create a live-out register record for the given register Reg.</p>


<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>

</div>
</div>

### debug() {#a135b3048b4bd834fa030e41fa9376b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StackMaps::debug ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### emitCallsiteEntries() {#a1b5ea170fffe072b252dec9bd7dd5edf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackMaps::emitCallsiteEntries (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the callsite info for each stackmap/patchpoint intrinsic call.</p>


<p>Emit the callsite info for each callsite.</p>


<p>StkMapRecord[NumRecords] { uint64 : PatchPoint <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> uint32 : <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Offset uint16 : Reserved (record flags) uint16 : NumLocations <a href="/web-llvm/docs/api/structs/llvm/stackmaps/location">Location</a>[NumLocations] { uint8 : <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> | Direct | Indirect | <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> | ConstantIndex uint8 : Size in Bytes uint16 : Dwarf RegNum int32 : Offset } uint16 : Padding uint16 : NumLiveOuts LiveOuts[NumLiveOuts] { uint16 : Dwarf RegNum uint8 : Reserved uint8 : Size in Bytes } uint32 : Padding (only if required to align to 8 byte) }</p>


<p><a href="/web-llvm/docs/api/structs/llvm/stackmaps/location">Location</a> Encoding, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>: 0x1, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, Reg (value in register) 0x2, Direct, Reg + Offset (frame index) 0x3, Indirect, [Reg + Offset] (spilled value) 0x4, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a>, Offset (small constant) 0x5, ConstIndex, Constants[Offset] (large constant)</p>


<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>

</div>
</div>

### emitConstantPoolEntries() {#a621d8c17c3a444567991bd1c8077676e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackMaps::emitConstantPoolEntries (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the constant pool.</p>


<p>int64 : Constants[NumConstants]</p>


<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>

</div>
</div>

### emitFunctionFrameRecords() {#a9a0d880814cbfa68ee095fb35bc1ba3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackMaps::emitFunctionFrameRecords (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the function frame record for each function.</p>


<p>StkSizeRecord[NumFunctions] { uint64 : <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Address uint64 : Stack Size uint64 : <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> Count }</p>


<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>

</div>
</div>

### emitStackmapHeader() {#a4ce0ba2ca1ab3cd09e74c2335effd0ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackMaps::emitStackmapHeader (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the stackmap header.</p>


<p>Header { uint8 : Stack Map Version (currently 3) uint8 : Reserved (expected to be 0) uint16 : Reserved (expected to be 0) } uint32 : NumFunctions uint32 : NumConstants uint32 : NumRecords</p>


<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>

</div>
</div>

### parseOperand() {#a0cf2e24eb3d06ba9b5d137f17e07d87a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr::const_mop_iterator StackMaps::parseOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a476971826fa13b07e28ad971ec5a3234">MachineInstr::const_mop_iterator</a> MOI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a476971826fa13b07e28ad971ec5a3234">MachineInstr::const_mop_iterator</a> MOE, <a href="#abd10846f022ea0ca579e64604ab40604">LocationVec</a> &amp; Locs, <a href="#a85a4bfddff0c7f8d3f474788a2e8a5d0">LiveOutVec</a> &amp; LiveOuts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>

</div>
</div>

### parseRegisterLiveOutMask() {#afe63ab7253698f19218bd95182f736b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackMaps::LiveOutVec StackMaps::parseRegisterLiveOutMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the register live-out mask and return a vector of live-out registers that need to be recorded in the stackmap.</p>

<p>Declaration at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>

</div>
</div>

### parseStatepointOpers() {#aac31350f79e49c00cdead92c9138083f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackMaps::parseStatepointOpers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a476971826fa13b07e28ad971ec5a3234">MachineInstr::const_mop_iterator</a> MOI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a476971826fa13b07e28ad971ec5a3234">MachineInstr::const_mop_iterator</a> MOE, <a href="#abd10846f022ea0ca579e64604ab40604">LocationVec</a> &amp; Locations, <a href="#a85a4bfddff0c7f8d3f474788a2e8a5d0">LiveOutVec</a> &amp; LiveOuts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specialized parser of statepoint operands.</p>


<p>They do not directly correspond to StackMap record entries.</p>


<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>

</div>
</div>

### print() {#a0af6a5531e112d693fbdec53101ba1a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackMaps::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>

</div>
</div>

### recordStackMapOpers() {#a4c2dc521e0ab30d61650dbc875cecb0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackMaps::recordStackMapOpers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, uint64_t ID, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a476971826fa13b07e28ad971ec5a3234">MachineInstr::const_mop_iterator</a> MOI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a476971826fa13b07e28ad971ec5a3234">MachineInstr::const_mop_iterator</a> MOE, bool recordResult=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the locations of the operands of the provided instruction in a record keyed by the provided label.</p>


<p>For instructions w/AnyReg calling convention the return register is also recorded if requested. For STACKMAP, and PATCHPOINT the label is expected to immediately <em>preceed</em> lowering of the MI to MCInsts. For STATEPOINT, it expected to immediately <em>follow</em>. It's not clear this difference was intentional, but it exists today.</p>


<p>Declaration at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AP {#a0e94f85c07dfe78b4bea1a4736237cdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter&amp; llvm::StackMaps::AP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### ConstPool {#a1ff9d048c0e3387901cf2d59b8c25d54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantPool llvm::StackMaps::ConstPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### CSInfos {#ab10225515f2bc6a1d7da6d7a7a99a083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteInfoList llvm::StackMaps::CSInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### FnInfos {#a18a77bb3539214254882e23b8ad94dd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FnInfoMap llvm::StackMaps::FnInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getNextMetaArgIdx() {#a0678a1f52ff04158310e4157e81282f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StackMaps::getNextMetaArgIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned CurIdx)</td>
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

<p>Get index of next meta operand.</p>


<p>Similar to parseOperand, but does not actually parses operand meaning.</p>


<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa2dfd6ae7ded046f5e5e03e0f745d5c3">llvm::MachineInstr::findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a72f688fbc467b422cbaa2863879853b0">llvm::StatepointOpers::getNumAllocaIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a74489068197c4dc2f59abb1ee9da80e2">llvm::StatepointOpers::getNumGcMapEntriesIdx</a> and <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#afec1cbe3c73e6d6b86e5d6b00815dc2e">llvm::StatepointOpers::getNumGCPtrIdx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### WSMP {#a9f4e28b6a926e8f7a66cae35d70736a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * StackMaps::WSMP = "Stack Maps: "</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
