---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/registerfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegisterFile` Class

<p>Manages hardware register files, and tracks register definitions for register renaming purposes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::mca::RegisterFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">llvm/MCA/HardwareUnits/RegisterFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/hardwareunit">HardwareUnit</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a41a518c7b3d483e68f9eba119db59a">IndexPlusCostPairTy</a> = std::pair&lt; unsigned, unsigned &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5891ceaa36a90311d626fbbd1150bdaf">RegisterMapping</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/writeref">WriteRef</a>, RegisterRenamingInfo &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d1dda94e57c587ddfcf918ee75630c6">RegisterFile</a> (const MCSchedModel &amp;SM, const MCRegisterInfo &amp;mri, unsigned NumRegs=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0130b17dd269a2bf18408bf108d2cf84">collectWrites</a> (const MCSubtargetInfo &amp;STI, const ReadState &amp;RS, SmallVectorImpl&lt; WriteRef &gt; &amp;Writes, SmallVectorImpl&lt; WriteRef &gt; &amp;CommittedWrites) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mca/registerfile/rawhazard">RAWHazard</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f9761f8807ef5c507cadfd2e1e99cd9">checkRAWHazards</a> (const MCSubtargetInfo &amp;STI, const ReadState &amp;RS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25dd8effff24d6d3273181f469154ee5">addRegisterWrite</a> (WriteRef Write, MutableArrayRef&lt; unsigned &gt; UsedPhysRegs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa27ad78489e8c685d427e45e6c4bc14d">addRegisterRead</a> (ReadState &amp;RS, const MCSubtargetInfo &amp;STI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a65825cbd0e2859b88d170184507982">removeRegisterWrite</a> (const WriteState &amp;WS, MutableArrayRef&lt; unsigned &gt; FreedPhysRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5dfe17c72c100ac5933b6776e8ceaeb">canEliminateMove</a> (const WriteState &amp;WS, const ReadState &amp;RS, unsigned PRFIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96196ee6ac47c0ff8c2398bbc4cb775d">tryEliminateMoveOrSwap</a> (MutableArrayRef&lt; WriteState &gt; Writes, MutableArrayRef&lt; ReadState &gt; Reads)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334c8ec1d332c32d8c8d8cff78cc6deb">isAvailable</a> (ArrayRef&lt; MCPhysReg &gt; Regs) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c3696cb86065fccf0e3fed349f1bdd">getNumRegisterFiles</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1466f7d3691522202889297ef461b3c5">getElapsedCyclesFromWriteBack</a> (const WriteRef &amp;WR) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff33426f5edf9f386718b122bae39f7b">onInstructionExecuted</a> (Instruction *IS)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55d698cb7776a4b4a824bd6450662e94">cycleStart</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafea068bc9d5827e22895fab2ba376d4">cycleEnd</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2055c0850627bf2b455c883667b78f3d">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a3d90f62c5c014793a0697ca85112b1">addRegisterFile</a> (const MCRegisterFileDesc &amp;RF, ArrayRef&lt; MCRegisterCostEntry &gt; Entries)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bca5c7f82a5c13fe91ea1147eead898">allocatePhysRegs</a> (const RegisterRenamingInfo &amp;Entry, MutableArrayRef&lt; unsigned &gt; UsedPhysRegs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a000852ea2da3f57fa597627f86b188ad">freePhysRegs</a> (const RegisterRenamingInfo &amp;Entry, MutableArrayRef&lt; unsigned &gt; FreedPhysRegs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00208431987180d6ce04906e38ad8408">initialize</a> (const MCSchedModel &amp;SM, unsigned NumRegs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e54096c990b88e7dd15686a997ca5cb">MRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; RegisterMappingTracker, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b80eeca9570df9c5b5d5b7b56cbe54e">RegisterFiles</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; RegisterMapping &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5501b45600c1989b25fb67d190c53caa">RegisterMappings</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab5a774d525eda836cbc615f826e181">ZeroRegisters</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9257a164bbd16ebbd9cb34b9b98bd97">CurrentCycle</a></td>
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

<p>Manages hardware register files, and tracks register definitions for register renaming purposes.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### IndexPlusCostPairTy {#a4a41a518c7b3d483e68f9eba119db59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::mca::RegisterFile::IndexPlusCostPairTy =  std::pair&lt;unsigned, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

### RegisterMapping {#a5891ceaa36a90311d626fbbd1150bdaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::mca::RegisterFile::RegisterMapping =  std::pair&lt;WriteRef, RegisterRenamingInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegisterFile() {#a9d1dda94e57c587ddfcf918ee75630c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::RegisterFile::RegisterFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp; SM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; mri, unsigned NumRegs=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRegisterRead() {#aa27ad78489e8c685d427e45e6c4bc14d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::addRegisterRead (<a href="/web-llvm/docs/api/classes/llvm/mca/readstate">ReadState</a> &amp; RS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#afb4ddf31a851451dfa623aec7ceef3c4">llvm::mca::WriteState::addUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0130b17dd269a2bf18408bf108d2cf84">collectWrites</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#a856dbf2a7665b6ed3c190caa792c9c3c">llvm::mca::ReadState::getDescriptor</a>, <a href="#a1466f7d3691522202889297ef461b3c5">getElapsedCyclesFromWriteBack</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a1060a7c37903fcc791a20d9d0c994c25">llvm::MCSubtargetInfo::getReadAdvanceCycles</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#ab48987b65ba62cc42cdfc9aa0b8218ea">llvm::mca::ReadState::getRegisterID</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a3837bacedb8dfa32c6a3b949bfdd6877">llvm::MCSchedModel::getSchedClassDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af907ecc18c1f4f0bce8a9e2eb449ffb8">llvm::MCSubtargetInfo::getSchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#a3f5396f654e242b3b2f79cbd264fb0ff">llvm::mca::ReadState::isIndependentFromDef</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/readdescriptor/#a0457e08d3ce6386375193b36276f148d">llvm::mca::ReadDescriptor::SchedClassID</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#a9c3f4f3a17f1c2e8a0c40124b504a3e4">llvm::mca::ReadState::setDependentWrites</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#a8d55abac05133a9d7fe14fec2827744a">llvm::mca::ReadState::setPRF</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#ad09c1ee8730169fba0d9350b22904370">llvm::mca::ReadState::setReadZero</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/readdescriptor/#a994a10ff4f6e37857af3bd7e1a02cb99">llvm::mca::ReadDescriptor::UseIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#a3a96634a46f3e609e75e4bf2e41bd879">llvm::mca::ReadState::writeStartEvent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a4df19f409f93dfad60c8af721603d452">llvm::mca::addRegisterReadWrite</a>.</p>

</div>
</div>

### addRegisterWrite() {#a25dd8effff24d6d3273181f469154ee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::addRegisterWrite (<a href="/web-llvm/docs/api/classes/llvm/mca/writeref">WriteRef</a> Write, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; unsigned &gt; UsedPhysRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#afb4ddf31a851451dfa623aec7ceef3c4">llvm::mca::WriteState::addUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#ab72ba7cf8bf88e7d8c3dcb3a20b1078c">llvm::mca::WriteState::clearsSuperRegisters</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#a405fdb90bbc7e779b4baf76aa77ce0bb">llvm::mca::WriteState::getLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#ad292021eb6613f2b9b807104f43b314b">llvm::mca::WriteState::getRegisterID</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#a20af3b12bfc186241f64184daf799a31">llvm::mca::WriteRef::getSourceIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#ab3fa6f3913b02ca785582b43e06c7401">llvm::mca::WriteRef::getWriteState</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#a2ef5fc00361f8a5d6ae99531232c1fe1">llvm::mca::WriteState::isEliminated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aba7ae9832c7e376c2629b52643cdd28a">llvm::mca::isNonArtificial</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#ade56a94cb586991cf9605301d237cdbe">llvm::mca::WriteState::isWriteZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#a482b726cdf5b63b3abf757eab5f84992">llvm::mca::WriteState::setPRF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa738b693496ce85aba70051f0aa8722bd">llvm::Write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a4df19f409f93dfad60c8af721603d452">llvm::mca::addRegisterReadWrite</a>.</p>

</div>
</div>

### canEliminateMove() {#ac5dfe17c72c100ac5933b6776e8ceaeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::RegisterFile::canEliminateMove (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/writestate">WriteState</a> &amp; WS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/readstate">ReadState</a> &amp; RS, unsigned PRFIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#ab72ba7cf8bf88e7d8c3dcb3a20b1078c">llvm::mca::WriteState::clearsSuperRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#ab48987b65ba62cc42cdfc9aa0b8218ea">llvm::mca::ReadState::getRegisterID</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#ad292021eb6613f2b9b807104f43b314b">llvm::mca::WriteState::getRegisterID</a>.</p>


<p>Referenced by <a href="#a96196ee6ac47c0ff8c2398bbc4cb775d">tryEliminateMoveOrSwap</a>.</p>

</div>
</div>

### checkRAWHazards() {#a6f9761f8807ef5c507cadfd2e1e99cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterFile::RAWHazard llvm::mca::RegisterFile::checkRAWHazards (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/readstate">ReadState</a> &amp; RS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#a0130b17dd269a2bf18408bf108d2cf84">collectWrites</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/registerfile/rawhazard/#a458da3a979bfbcb7c3841c6463448de9">llvm::mca::RegisterFile::RAWHazard::CyclesLeft</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#a4b0e3ad228a270b6eec03e3dd19ddee7">llvm::mca::WriteState::getCyclesLeft</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#a856dbf2a7665b6ed3c190caa792c9c3c">llvm::mca::ReadState::getDescriptor</a>, <a href="#a1466f7d3691522202889297ef461b3c5">getElapsedCyclesFromWriteBack</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a1060a7c37903fcc791a20d9d0c994c25">llvm::MCSubtargetInfo::getReadAdvanceCycles</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a3837bacedb8dfa32c6a3b949bfdd6877">llvm::MCSchedModel::getSchedClassDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af907ecc18c1f4f0bce8a9e2eb449ffb8">llvm::MCSubtargetInfo::getSchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#af7ade95e783ce5314942bf0d4f17d0d2">llvm::mca::WriteState::getWriteResourceID</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/registerfile/rawhazard/#a3a53e8e22604a9d19a6bb35d42996456">llvm::mca::RegisterFile::RAWHazard::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/registerfile/rawhazard/#a7d3591518afc5f5056765956bad9c0f0">llvm::mca::RegisterFile::RAWHazard::RegisterID</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/readdescriptor/#a0457e08d3ce6386375193b36276f148d">llvm::mca::ReadDescriptor::SchedClassID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#af459dc58960b1471b00b72f450869f01">llvm::mca::UNKNOWN_CYCLES</a> and <a href="/web-llvm/docs/api/structs/llvm/mca/readdescriptor/#a994a10ff4f6e37857af3bd7e1a02cb99">llvm::mca::ReadDescriptor::UseIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ac6ed6656160779919f747bc67182abd7">llvm::mca::checkRegisterHazard</a>.</p>

</div>
</div>

### collectWrites() {#a0130b17dd269a2bf18408bf108d2cf84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::collectWrites (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/readstate">ReadState</a> &amp; RS, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/writeref">WriteRef</a> &gt; &amp; Writes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/writeref">WriteRef</a> &gt; &amp; CommittedWrites)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#a856dbf2a7665b6ed3c190caa792c9c3c">llvm::mca::ReadState::getDescriptor</a>, <a href="#a1466f7d3691522202889297ef461b3c5">getElapsedCyclesFromWriteBack</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a1060a7c37903fcc791a20d9d0c994c25">llvm::MCSubtargetInfo::getReadAdvanceCycles</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#ab48987b65ba62cc42cdfc9aa0b8218ea">llvm::mca::ReadState::getRegisterID</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#ad292021eb6613f2b9b807104f43b314b">llvm::mca::WriteState::getRegisterID</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a3837bacedb8dfa32c6a3b949bfdd6877">llvm::MCSchedModel::getSchedClassDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af907ecc18c1f4f0bce8a9e2eb449ffb8">llvm::MCSubtargetInfo::getSchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#a20af3b12bfc186241f64184daf799a31">llvm::mca::WriteRef::getSourceIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#a2322850429b4482184841861b5fe8279">llvm::mca::WriteRef::getWriteResourceID</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#ab3fa6f3913b02ca785582b43e06c7401">llvm::mca::WriteRef::getWriteState</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#af4045c36ca1b3e8a6408d3eca7feab7a">llvm::mca::WriteRef::hasKnownWriteBackCycle</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/readdescriptor/#a0457e08d3ce6386375193b36276f148d">llvm::mca::ReadDescriptor::SchedClassID</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48f85da577c6ce7d9aed90437dc0d07c">llvm::unique</a> and <a href="/web-llvm/docs/api/structs/llvm/mca/readdescriptor/#a994a10ff4f6e37857af3bd7e1a02cb99">llvm::mca::ReadDescriptor::UseIndex</a>.</p>


<p>Referenced by <a href="#aa27ad78489e8c685d427e45e6c4bc14d">addRegisterRead</a> and <a href="#a6f9761f8807ef5c507cadfd2e1e99cd9">checkRAWHazards</a>.</p>

</div>
</div>

### cycleEnd() {#aafea068bc9d5827e22895fab2ba376d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::cycleEnd ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

### cycleStart() {#a55d698cb7776a4b4a824bd6450662e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::cycleStart ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>

</div>
</div>

### dump() {#a2055c0850627bf2b455c883667b78f3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a51c3696cb86065fccf0e3fed349f1bdd">getNumRegisterFiles</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getElapsedCyclesFromWriteBack() {#a1466f7d3691522202889297ef461b3c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::RegisterFile::getElapsedCyclesFromWriteBack (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/writeref">WriteRef</a> &amp; WR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#af21d536ceb2443d93a98c50e5d0d1153">llvm::mca::WriteRef::getWriteBackCycle</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#af4045c36ca1b3e8a6408d3eca7feab7a">llvm::mca::WriteRef::hasKnownWriteBackCycle</a>.</p>


<p>Referenced by <a href="#aa27ad78489e8c685d427e45e6c4bc14d">addRegisterRead</a>, <a href="#a6f9761f8807ef5c507cadfd2e1e99cd9">checkRAWHazards</a> and <a href="#a0130b17dd269a2bf18408bf108d2cf84">collectWrites</a>.</p>

</div>
</div>

### getNumRegisterFiles() {#a51c3696cb86065fccf0e3fed349f1bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::RegisterFile::getNumRegisterFiles ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>


<p>Referenced by <a href="#a2055c0850627bf2b455c883667b78f3d">dump</a> and <a href="#a334c8ec1d332c32d8c8d8cff78cc6deb">isAvailable</a>.</p>

</div>
</div>

### isAvailable() {#a334c8ec1d332c32d8c8d8cff78cc6deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::RegisterFile::isAvailable (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt; Regs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a51c3696cb86065fccf0e3fed349f1bdd">getNumRegisterFiles</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### onInstructionExecuted() {#aff33426f5edf9f386718b122bae39f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::onInstructionExecuted (<a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> * IS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a4bd1b7f022ec64b74af6360bca400f13">llvm::mca::InstructionBase::getDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#ab3fa6f3913b02ca785582b43e06c7401">llvm::mca::WriteRef::getWriteState</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instruction/#a12eb7cffeb144db46e8dfe35063a8d90">llvm::mca::Instruction::isExecuted</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#a293ffb54d80a7b162bcc0dda787106c8">llvm::mca::WriteRef::notifyExecuted</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#af459dc58960b1471b00b72f450869f01">llvm::mca::UNKNOWN_CYCLES</a>.</p>

</div>
</div>

### removeRegisterWrite() {#a7a65825cbd0e2859b88d170184507982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::removeRegisterWrite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/writestate">WriteState</a> &amp; WS, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; unsigned &gt; FreedPhysRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#ab72ba7cf8bf88e7d8c3dcb3a20b1078c">llvm::mca::WriteState::clearsSuperRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#a7b0829d9a1b982b240442bf94b38857b">llvm::mca::WriteRef::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#a4b0e3ad228a270b6eec03e3dd19ddee7">llvm::mca::WriteState::getCyclesLeft</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#ad292021eb6613f2b9b807104f43b314b">llvm::mca::WriteState::getRegisterID</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writeref/#ab3fa6f3913b02ca785582b43e06c7401">llvm::mca::WriteRef::getWriteState</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#a2ef5fc00361f8a5d6ae99531232c1fe1">llvm::mca::WriteState::isEliminated</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#ade56a94cb586991cf9605301d237cdbe">llvm::mca::WriteState::isWriteZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#af459dc58960b1471b00b72f450869f01">llvm::mca::UNKNOWN_CYCLES</a>.</p>

</div>
</div>

### tryEliminateMoveOrSwap() {#a96196ee6ac47c0ff8c2398bbc4cb775d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::RegisterFile::tryEliminateMoveOrSwap (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/writestate">WriteState</a> &gt; Writes, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/readstate">ReadState</a> &gt; Reads)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="#ac5dfe17c72c100ac5933b6776e8ceaeb">canEliminateMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#ab48987b65ba62cc42cdfc9aa0b8218ea">llvm::mca::ReadState::getRegisterID</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#ad292021eb6613f2b9b807104f43b314b">llvm::mca::WriteState::getRegisterID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aba7ae9832c7e376c2629b52643cdd28a">llvm::mca::isNonArtificial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#a7f5de599e82d9daefa5b6ada7ae0586a">llvm::mca::WriteState::setEliminated</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#ad09c1ee8730169fba0d9350b22904370">llvm::mca::ReadState::setReadZero</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#a3b6261f033feca69cf5371672a1de218">llvm::mca::WriteState::setWriteZero</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addRegisterFile() {#a6a3d90f62c5c014793a0697ca85112b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::addRegisterFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcregisterfiledesc">MCRegisterFileDesc</a> &amp; RF, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcregistercostentry">MCRegisterCostEntry</a> &gt; Entries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>

</div>
</div>

### allocatePhysRegs() {#a6bca5c7f82a5c13fe91ea1147eead898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::allocatePhysRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RegisterRenamingInfo &amp; Entry, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; unsigned &gt; UsedPhysRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>

</div>
</div>

### freePhysRegs() {#a000852ea2da3f57fa597627f86b188ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::freePhysRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RegisterRenamingInfo &amp; Entry, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; unsigned &gt; FreedPhysRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>

</div>
</div>

### initialize() {#a00208431987180d6ce04906e38ad8408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::RegisterFile::initialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp; SM, unsigned NumRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentCycle {#ad9257a164bbd16ebbd9cb34b9b98bd97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::RegisterFile::CurrentCycle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

### MRI {#a4e54096c990b88e7dd15686a997ca5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo&amp; llvm::mca::RegisterFile::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

### RegisterFiles {#a0b80eeca9570df9c5b5d5b7b56cbe54e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RegisterMappingTracker, 4&gt; llvm::mca::RegisterFile::RegisterFiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

### RegisterMappings {#a5501b45600c1989b25fb67d190c53caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;RegisterMapping&gt; llvm::mca::RegisterFile::RegisterMappings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

### ZeroRegisters {#a1ab5a774d525eda836cbc615f826e181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::mca::RegisterFile::ZeroRegisters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
