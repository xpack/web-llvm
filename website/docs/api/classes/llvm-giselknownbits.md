---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/giselknownbits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GISelKnownBits` Class



## Declaration

<div class="doxyDeclaration">
class llvm::GISelKnownBits { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">llvm/CodeGen/GlobalISel/GISelKnownBits.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract class that contains various methods for clients to notify about changes. <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd3054202251b55372fac4798d23a9d0">GISelKnownBits</a> (MachineFunction &amp;MF, unsigned MaxDepth=6)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b3793e276e4ac4d10ea4a998ac32c4">~GISelKnownBits</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabaf78f3c38d60989bd100b623fc8b56">getMachineFunction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0769c966e72057b6447878307d931195">getDataLayout</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e367b6a777f570054f6c62eb885a609">computeKnownBitsImpl</a> (Register R, KnownBits &amp;Known, const APInt &amp;DemandedElts, unsigned Depth=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a651adf8bbb2fece837c1ef70250e19ce">computeNumSignBits</a> (Register R, const APInt &amp;DemandedElts, unsigned Depth=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad77d3e231789845c6639b23249bed7">computeNumSignBits</a> (Register R, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3bd16b0bda0d7c3290bf9ba7d095400">getKnownBits</a> (Register R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcde3878046bd6b199a6f2090f9536a3">getKnownBits</a> (Register R, const APInt &amp;DemandedElts, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1bb87bfd2d58b2ee620648c6abbed30">getKnownBits</a> (MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa921e79a9e2303f303c40afb3ab222f">getKnownZeroes</a> (Register R)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c6988abbc44623a2f302ede7a8e63b2">getKnownOnes</a> (Register R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac649db401bd177e1c826fdcb0776a833">maskedValueIsZero</a> (Register Val, const APInt &amp;Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8379867536cb5449ebfc7b134a8e14b">signBitIsZero</a> (Register Op)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19348924fef8d7717551786dc89923a9">computeKnownAlignment</a> (Register R, unsigned Depth=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db7bc9c9e2d2fddc0797aa82d91c6f2">erasingInstr</a> (MachineInstr &amp;MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instruction is about to be erased. <a href="#a2db7bc9c9e2d2fddc0797aa82d91c6f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fd6fc7eb31e25a63214b638745424d8">createdInstr</a> (MachineInstr &amp;MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instruction has been created and inserted into the function. <a href="#a5fd6fc7eb31e25a63214b638745424d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6197b28c76dc27c56cf5e941fe3d55ed">changingInstr</a> (MachineInstr &amp;MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction is about to be mutated in some way. <a href="#a6197b28c76dc27c56cf5e941fe3d55ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae592aaf4ed9986b40a16dd1475aab7f1">changedInstr</a> (MachineInstr &amp;MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction was mutated in some way. <a href="#ae592aaf4ed9986b40a16dd1475aab7f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9490ecd52cd5bf1975e06c657f546e7">getMaxDepth</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14227dcf230ab3e07e0a3328ad22882c">computeKnownBitsMin</a> (Register Src0, Register Src1, KnownBits &amp;Known, const APInt &amp;DemandedElts, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for the intersection of <span class="doxyComputerOutput">Src0</span> and <span class="doxyComputerOutput">Src1</span>. <a href="#a14227dcf230ab3e07e0a3328ad22882c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa615d8d5b0615c99c755684e3124ea03">computeNumSignBitsMin</a> (Register Src0, Register Src1, const APInt &amp;DemandedElts, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute number of sign bits for the intersection of <span class="doxyComputerOutput">Src0</span> and <span class="doxyComputerOutput">Src1</span>. <a href="#aa615d8d5b0615c99c755684e3124ea03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a737be484bc58d6a03b84e3fa528362b7">MF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af695b9193869d109e8e2fde5b20b2f9a">MRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a3319b0092b52011fc729e51b72a32">TL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb584f571b0416ae622f4c1a15933416">DL</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7421fa2b0844cb70f5440662bd8569ad">MaxDepth</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e9baa43455fa7c1a081a152dc84c081">ComputeKnownBitsCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache maintained during a computeKnownBits request. <a href="#a7e9baa43455fa7c1a081a152dc84c081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a249a932d6f75f857e8caf11bcab9f920">computeKnownBitsForAlignment</a> (KnownBits &amp;Known, Align Alignment)</td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GISelKnownBits() {#afd3054202251b55372fac4798d23a9d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GISelKnownBits::GISelKnownBits (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned MaxDepth=6)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GISelKnownBits() {#a40b3793e276e4ac4d10ea4a998ac32c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::GISelKnownBits::~GISelKnownBits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### changedInstr() {#ae592aaf4ed9986b40a16dd1475aab7f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GISelKnownBits::changedInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>This instruction was mutated in some way.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### changingInstr() {#a6197b28c76dc27c56cf5e941fe3d55ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GISelKnownBits::changingInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>This instruction is about to be mutated in some way.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### computeKnownAlignment() {#a19348924fef8d7717551786dc89923a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align GISelKnownBits::computeKnownAlignment (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The known alignment for the pointer-like value <span class="doxyComputerOutput">R</span>.</p></dd>
</dl>


<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>


<p>References <a href="#a19348924fef8d7717551786dc89923a9">computeKnownAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a19348924fef8d7717551786dc89923a9">computeKnownAlignment</a>.</p>

</div>
</div>

### computeKnownBitsImpl() {#a0e367b6a777f570054f6c62eb885a609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GISelKnownBits::computeKnownBitsImpl (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, unsigned Depth=0)</td>
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



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7a4bd85cb03fa4d3b2c5c67cd4af39a5">llvm::KnownBits::add</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac6661654e5ce1b32651508eec50b6d58">llvm::KnownBits::anyext</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a0c649ec21217b3feb2f2a28b4736b689">llvm::KnownBits::anyextOrTrunc</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1f1be83c0efdaff4af051b7a45faaba7">llvm::KnownBits::ashr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37c1fdede126353d80c3753dfe06f3c7">llvm::bit_width</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4421e5acdca3cb36134d66d5a06e23b2">llvm::KnownBits::byteSwap</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aac76bff09195240a482b319136ab6144">llvm::APInt::clearLowBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae277e0144afb92a90c24163fb4898f02">llvm::computeKnownBitsFromRangeMetadata</a>, <a href="#a0e367b6a777f570054f6c62eb885a609">computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aaf8d1fc0f6386ef04a4b991fd73d823b">llvm::KnownBits::countMaxLeadingZeros</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4676f4bc7da9235ff3b6683dd670d7be">llvm::KnownBits::countMaxPopulation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#ae744642bc86b281d7458f66f962cc154">dumpResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9dfebbd5f16d2a5c7effdabb97579b4">llvm::extractBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a6f1c4a256c58844fb8dc8aa154f335a4">llvm::KnownBits::extractBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4fdc09049a61f952b5d52788dbd2f69b">llvm::KnownBits::getBitWidth</a>, <a href="#ad9490ecd52cd5bf1975e06c657f546e7">getMaxDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a3e9d2a9063bce7f5b3d7dd21fd05c79d">llvm::MachineMemOperand::getMemoryType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a5ea985de61dfccc6e599ccf7a460c3a3">llvm::MachineMemOperand::getRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ab41beafb710aa35f1b793e5876bf2c70">llvm::KnownBits::insertBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a76e45a40f2f0b5b09132d1de119765e8">llvm::KnownBits::intersectWith</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ad1db89614d919436714d099c99ff12a0">llvm::LLT::isFixedVector</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a28cf355963391ab8781b2347d495553d">llvm::KnownBits::isUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5c34f40ce539320222a15a88ebcef716">llvm::KnownBits::lshr</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a066220c7a472d8793de64a0ad23487d2">llvm::KnownBits::makeConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#abd85d08f35600dd19615a1efe9cacb1d">llvm::KnownBits::mul</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a48c734dfebb2a1b9faa891d2d2c3a807">llvm::KnownBits::reverseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6fff8a97bcb55e50e9be0ecf0c99b63">llvm::APInt::setAllBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a286d4fa2a50c9ac6ac3a8069cccfcd0c">llvm::APInt::setBitsFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ade8e20ecea1091e835395746448e262e">llvm::APInt::setLowBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a781ca23d84995ffb2efaa51267053c19">llvm::KnownBits::sext</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a0c936127975e910ae794122a057b067d">llvm::KnownBits::sextInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb9c55b6986369948507ca5241b4e411">llvm::APInt::shl</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ae9ffa8b50ca6095202b2e8e7686c10b8">llvm::KnownBits::shl</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a137874360a1967ac811fe9e5d7605eee">llvm::KnownBits::smax</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a87b6ba94fe7d3ee69dbeed7350fad096">llvm::KnownBits::smin</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aaedcbc66cfec0117e98d503c89234716">llvm::KnownBits::sub</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5120eaa394627e6c1ec3d66ef77947cd">llvm::KnownBits::umax</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aea97402782d7e8098b6ae00c7a6365dd">llvm::KnownBits::umin</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a51c3c203b80468b8761416d14e6f5b7f">llvm::KnownBits::zext</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7ddb13bdf305b1d4eee7bf1a9ac9d35e">llvm::KnownBits::zextOrTrunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ac680fd9aee1de89385f2ac2d1878ed9b">llvm::SITargetLowering::computeKnownBitsForTargetInstr</a>, <a href="#a0e367b6a777f570054f6c62eb885a609">computeKnownBitsImpl</a> and <a href="#adcde3878046bd6b199a6f2090f9536a3">getKnownBits</a>.</p>

</div>
</div>

### computeNumSignBits() {#a651adf8bbb2fece837c1ef70250e19ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GISelKnownBits::computeNumSignBits (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a651adf8bbb2fece837c1ef70250e19ce">computeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#ada5a1c97857d6b28c7292bcb5496ac68">computeNumSignBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#a0769c966e72057b6447878307d931195">getDataLayout</a>, <a href="#ab3bd16b0bda0d7c3290bf9ba7d095400">getKnownBits</a>, <a href="#ad9490ecd52cd5bf1975e06c657f546e7">getMaxDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abcceb535a4bb1e23c320e7628476bd5d">llvm::MachineMemOperand::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aabc0af41b4437080b27002ed7a1ed656">llvm::KnownBits::isNegative</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a157efd68e8b4b838829cad165b1583f8">llvm::KnownBits::isNonNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a695a19c9c3ae14638be151add82755cb">llvm::TargetLoweringBase::ZeroOrNegativeOneBooleanContent</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a>.</p>


<p>Referenced by <a href="#a651adf8bbb2fece837c1ef70250e19ce">computeNumSignBits</a>, <a href="#acad77d3e231789845c6639b23249bed7">computeNumSignBits</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#afa0ed64c2bf09a336fb47c9488d2880b">anonymous{AArch64PreLegalizerCombiner.cpp}::matchICmpRedundantTrunc</a>.</p>

</div>
</div>

### computeNumSignBits() {#acad77d3e231789845c6639b23249bed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GISelKnownBits::computeNumSignBits (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>


<p>References <a href="#a651adf8bbb2fece837c1ef70250e19ce">computeNumSignBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>.</p>

</div>
</div>

### createdInstr() {#a5fd6fc7eb31e25a63214b638745424d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GISelKnownBits::createdInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>An instruction has been created and inserted into the function.</p>


<p>Note that the instruction might not be a fully fledged instruction at this point and won't be if the <a href="/web-llvm/docs/api/classes/llvm/machinefunction/delegate">MachineFunction::Delegate</a> is calling it. This is because the delegate only sees the construction of the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> before operands have been added.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### erasingInstr() {#a2db7bc9c9e2d2fddc0797aa82d91c6f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GISelKnownBits::erasingInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>An instruction is about to be erased.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getDataLayout() {#a0769c966e72057b6447878307d931195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; llvm::GISelKnownBits::getDataLayout ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>


<p>Referenced by <a href="#a651adf8bbb2fece837c1ef70250e19ce">computeNumSignBits</a>.</p>

</div>
</div>

### getKnownBits() {#ab3bd16b0bda0d7c3290bf9ba7d095400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits GISelKnownBits::getKnownBits (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a> and <a href="#ab3bd16b0bda0d7c3290bf9ba7d095400">getKnownBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>, <a href="#a651adf8bbb2fece837c1ef70250e19ce">computeNumSignBits</a>, <a href="#ad1bb87bfd2d58b2ee620648c6abbed30">getKnownBits</a>, <a href="#ab3bd16b0bda0d7c3290bf9ba7d095400">getKnownBits</a>, <a href="#a2c6988abbc44623a2f302ede7a8e63b2">getKnownOnes</a>, <a href="#afa921e79a9e2303f303c40afb3ab222f">getKnownZeroes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9941226cefb2787fa29507c4f5630d6">llvm::isKnownToBeAPowerOfTwo</a> and <a href="#ac649db401bd177e1c826fdcb0776a833">maskedValueIsZero</a>.</p>

</div>
</div>

### getKnownBits() {#adcde3878046bd6b199a6f2090f9536a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits GISelKnownBits::getKnownBits (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0e367b6a777f570054f6c62eb885a609">computeKnownBitsImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>

</div>
</div>

### getKnownBits() {#ad1bb87bfd2d58b2ee620648c6abbed30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits GISelKnownBits::getKnownBits (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab3bd16b0bda0d7c3290bf9ba7d095400">getKnownBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getKnownOnes() {#a2c6988abbc44623a2f302ede7a8e63b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt GISelKnownBits::getKnownOnes (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>


<p>References <a href="#ab3bd16b0bda0d7c3290bf9ba7d095400">getKnownBits</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>.</p>

</div>
</div>

### getKnownZeroes() {#afa921e79a9e2303f303c40afb3ab222f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt GISelKnownBits::getKnownZeroes (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>


<p>References <a href="#ab3bd16b0bda0d7c3290bf9ba7d095400">getKnownBits</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

### getMachineFunction() {#aabaf78f3c38d60989bd100b623fc8b56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction &amp; llvm::GISelKnownBits::getMachineFunction ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#af77a6b87eef9b3173d765b97ceb6c5fb">llvm::SITargetLowering::computeKnownAlignForTargetInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ac72c6a7fdaf91e99b6a6232207e57edc">knownBitsForWorkitemID</a>.</p>

</div>
</div>

### maskedValueIsZero() {#ac649db401bd177e1c826fdcb0776a833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GISelKnownBits::maskedValueIsZero (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Mask)</td>
</tr>
</table>
</td>
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
<dd><p>true if 'V &amp; Mask' is known to be zero in DemandedElts. We use this predicate to simplify operations downstream. Mask is known to be zero for bits that V cannot have.</p></dd>
</dl>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>


<p>Reference <a href="#ab3bd16b0bda0d7c3290bf9ba7d095400">getKnownBits</a>.</p>


<p>Referenced by <a href="#ae8379867536cb5449ebfc7b134a8e14b">signBitIsZero</a>.</p>

</div>
</div>

### signBitIsZero() {#ae8379867536cb5449ebfc7b134a8e14b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GISelKnownBits::signBitIsZero (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the sign bit of <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is known to be zero. We use this predicate to simplify operations downstream.</p></dd>
</dl>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1e6f0d8dfed0ab631b488a3e6317718e">llvm::APInt::getSignMask</a> and <a href="#ac649db401bd177e1c826fdcb0776a833">maskedValueIsZero</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getMaxDepth() {#ad9490ecd52cd5bf1975e06c657f546e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GISelKnownBits::getMaxDepth ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>


<p>Referenced by <a href="#a0e367b6a777f570054f6c62eb885a609">computeKnownBitsImpl</a> and <a href="#a651adf8bbb2fece837c1ef70250e19ce">computeNumSignBits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeKnownBitsMin() {#a14227dcf230ab3e07e0a3328ad22882c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GISelKnownBits::computeKnownBitsMin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src0, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src1, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute known bits for the intersection of <span class="doxyComputerOutput">Src0</span> and <span class="doxyComputerOutput">Src1</span>.</p>

<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>

</div>
</div>

### computeNumSignBitsMin() {#aa615d8d5b0615c99c755684e3124ea03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GISelKnownBits::computeNumSignBitsMin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src0, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute number of sign bits for the intersection of <span class="doxyComputerOutput">Src0</span> and <span class="doxyComputerOutput">Src1</span>.</p>

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>, definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ComputeKnownBitsCache {#a7e9baa43455fa7c1a081a152dc84c081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;Register, KnownBits, 16&gt; llvm::GISelKnownBits::ComputeKnownBitsCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache maintained during a computeKnownBits request.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>

</div>
</div>

### DL {#abb584f571b0416ae622f4c1a15933416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::GISelKnownBits::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>

</div>
</div>

### MaxDepth {#a7421fa2b0844cb70f5440662bd8569ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GISelKnownBits::MaxDepth</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>

</div>
</div>

### MF {#a737be484bc58d6a03b84e3fa528362b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::GISelKnownBits::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>

</div>
</div>

### MRI {#af695b9193869d109e8e2fde5b20b2f9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::GISelKnownBits::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>

</div>
</div>

### TL {#a75a3319b0092b52011fc729e51b72a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering&amp; llvm::GISelKnownBits::TL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### computeKnownBitsForAlignment() {#a249a932d6f75f857e8caf11bcab9f920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GISelKnownBits::computeKnownBitsForAlignment (<a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ade8e20ecea1091e835395746448e262e">llvm::APInt::setLowBits</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">GISelKnownBits.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp">GISelKnownBits.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
