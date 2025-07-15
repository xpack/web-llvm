---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/basicblockinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BasicBlockInfo` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/basicblockinfo">BasicBlockInfo</a> - Information about the offset and size of a single basic block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::BasicBlockInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">Target/ARM/ARMBasicBlockInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fec3f0b886c81f10897cccfba57e904">BasicBlockInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f264104cc3a87ed07dd196d281ccd2c">internalKnownBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the number of known offset bits internally to this block. <a href="#a5f264104cc3a87ed07dd196d281ccd2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96d35759d0115509c273fbdfd8fe011a">postOffset</a> (Align Alignment=Align(1)) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the offset immediately following this block. <a href="#a96d35759d0115509c273fbdfd8fe011a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fcaddb16aceac174b38bb7bc118bdfe">postKnownBits</a> (Align Align=llvm::Align(1)) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the number of known low bits of postOffset. <a href="#a9fcaddb16aceac174b38bb7bc118bdfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acadf079e9232969cd61ca5744b10dd16">Offset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset - Distance from the beginning of the function to the beginning of this basic block. <a href="#acadf079e9232969cd61ca5744b10dd16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b26f2a8fbde15592af8af3fb950d8fc">Size</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size - Size of the basic block in bytes. <a href="#a1b26f2a8fbde15592af8af3fb950d8fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a9e20cafe54e922aeead667cdd73ff">KnownBits</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> - The number of low bits in Offset that are known to be exact. <a href="#a57a9e20cafe54e922aeead667cdd73ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadef2620c9e7d116fda27a2d9edbd125">Unalign</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unalign - When non-zero, the block contains instructions (inline asm) of unknown size. <a href="#aadef2620c9e7d116fda27a2d9edbd125">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3322f1dcf981856028e4ec195de0024d">PostAlign</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PostAlign - When &gt; 1, the block terminator contains a .align directive, so the end of the block is aligned to PostAlign bytes. <a href="#a3322f1dcf981856028e4ec195de0024d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/basicblockinfo">BasicBlockInfo</a> - Information about the offset and size of a single basic block.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BasicBlockInfo() {#a6fec3f0b886c81f10897cccfba57e904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BasicBlockInfo::BasicBlockInfo ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### internalKnownBits() {#a5f264104cc3a87ed07dd196d281ccd2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BasicBlockInfo::internalKnownBits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the number of known offset bits internally to this block.</p>


<p>This number should be used to predict worst case padding when splitting the block.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="#a57a9e20cafe54e922aeead667cdd73ff">KnownBits</a>, <a href="#a1b26f2a8fbde15592af8af3fb950d8fc">Size</a> and <a href="#aadef2620c9e7d116fda27a2d9edbd125">Unalign</a>.</p>


<p>Referenced by <a href="#a9fcaddb16aceac174b38bb7bc118bdfe">postKnownBits</a> and <a href="#a96d35759d0115509c273fbdfd8fe011a">postOffset</a>.</p>

</div>
</div>

### postKnownBits() {#a9fcaddb16aceac174b38bb7bc118bdfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BasicBlockInfo::postKnownBits (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Align=<a href="/web-llvm/docs/api/structs/llvm/align">llvm::Align</a>(1))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the number of known low bits of postOffset.</p>


<p>If this block contains inline asm, the number of known bits drops to the instruction alignment. An aligned terminator may increase the number of know bits. If LogAlign is given, also consider the alignment of the next block.</p>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a>.</p>


<p>References <a href="#a5f264104cc3a87ed07dd196d281ccd2c">internalKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a> and <a href="#a3322f1dcf981856028e4ec195de0024d">PostAlign</a>.</p>

</div>
</div>

### postOffset() {#a96d35759d0115509c273fbdfd8fe011a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BasicBlockInfo::postOffset (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the offset immediately following this block.</p>


<p>If <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> is specified, return the offset the successor block will get if it has this alignment.</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a>.</p>


<p>References <a href="#a5f264104cc3a87ed07dd196d281ccd2c">internalKnownBits</a>, <a href="#acadf079e9232969cd61ca5744b10dd16">Offset</a>, <a href="#a3322f1dcf981856028e4ec195de0024d">PostAlign</a>, <a href="#a1b26f2a8fbde15592af8af3fb950d8fc">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aca36878e37b708e22ace80dececead61">llvm::UnknownPadding</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### KnownBits {#a57a9e20cafe54e922aeead667cdd73ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::BasicBlockInfo::KnownBits = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> - The number of low bits in Offset that are known to be exact.</p>


<p>The remaining bits of Offset are an upper bound.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a>.</p>


<p>Referenced by <a href="#a5f264104cc3a87ed07dd196d281ccd2c">internalKnownBits</a>.</p>

</div>
</div>

### Offset {#acadf079e9232969cd61ca5744b10dd16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BasicBlockInfo::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset - Distance from the beginning of the function to the beginning of this basic block.</p>


<p>Offsets are computed assuming worst case padding before an aligned block. This means that subtracting basic block offsets always gives a conservative estimate of the real distance which may be smaller.</p>


<p>Because worst case padding is used, the computed offset of an aligned block may not actually be aligned.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a>.</p>


<p>Referenced by <a href="#a96d35759d0115509c273fbdfd8fe011a">postOffset</a>.</p>

</div>
</div>

### PostAlign {#a3322f1dcf981856028e4ec195de0024d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::BasicBlockInfo::PostAlign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PostAlign - When &gt; 1, the block terminator contains a .align directive, so the end of the block is aligned to PostAlign bytes.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbasicblockutils/#a96fd72530daba07f5a05b8f467d2cf14">llvm::ARMBasicBlockUtils::computeBlockSize</a>, <a href="#a9fcaddb16aceac174b38bb7bc118bdfe">postKnownBits</a> and <a href="#a96d35759d0115509c273fbdfd8fe011a">postOffset</a>.</p>

</div>
</div>

### Size {#a1b26f2a8fbde15592af8af3fb950d8fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BasicBlockInfo::Size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size - Size of the basic block in bytes.</p>


<p>If the block contains inline assembly, this is a worst case estimate.</p>


<p>The size does not include any alignment padding whether from the beginning of the block, or from an aligned jump table at the end.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbasicblockutils/#a96fd72530daba07f5a05b8f467d2cf14">llvm::ARMBasicBlockUtils::computeBlockSize</a>, <a href="#a5f264104cc3a87ed07dd196d281ccd2c">internalKnownBits</a> and <a href="#a96d35759d0115509c273fbdfd8fe011a">postOffset</a>.</p>

</div>
</div>

### Unalign {#aadef2620c9e7d116fda27a2d9edbd125}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::BasicBlockInfo::Unalign = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unalign - When non-zero, the block contains instructions (inline asm) of unknown size.</p>


<p>The real size may be smaller than Size bytes by a multiple of 1 &lt;&lt; Unalign.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbasicblockutils/#a96fd72530daba07f5a05b8f467d2cf14">llvm::ARMBasicBlockUtils::computeBlockSize</a> and <a href="#a5f264104cc3a87ed07dd196d281ccd2c">internalKnownBits</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
