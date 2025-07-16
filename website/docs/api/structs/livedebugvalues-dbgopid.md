---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/livedebugvalues/dbgopid
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DbgOpID` Struct Reference

<p>An ID used in the <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap">DbgOpIDMap</a> (below) to lookup a stored <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop">DbgOp</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct LiveDebugValues::DbgOpID { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">CodeGen/LiveDebugValues/InstrRefBasedImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26fa3298b1a679da596a0ee2d0e41fa5">DbgOpID</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af535b4df0c494b4f33356334c4c10faa">DbgOpID</a> (uint32_t RawID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765daad2948619360609fd66c7f72832">DbgOpID</a> (bool IsConst, uint32_t Index)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e2402481c5028542702b6bf0390e9f">operator==</a> (const DbgOpID &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c2c43d8357f00d8b9ed9b37742047db">operator!=</a> (const DbgOpID &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e6661b8b23bbe5d428f8177ae17656b">asU32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acae2cb38ea8ad4e487e5101c8bb085f7">isUndef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa91469b374d4e14c8e445dc79420c850">isConst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74cad069a68241540dfec8b7ab7ad921">getIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a743561a2288ede30c2992d98e1866505">dump</a> (const MLocTracker *MTrack, const DbgOpIDMap *OpStore) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2c275ac433f922d745b9ec6fe198600">ID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4daebd0f9238b300b28306a656cb475">RawID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">LiveDebugValues::DbgOpID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f1daf4e1d0787d450ca7aa9a8e8686c"></a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91064aebe93d3d6b7776a90451f2a854">UndefID</a> = <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a>(0xffffffff)</td>
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

<p>An ID used in the <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap">DbgOpIDMap</a> (below) to lookup a stored <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop">DbgOp</a>.</p>


<p>This is used in place of actual DbgOps inside of a <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> to reduce its size, as <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> is very frequently used and passed around, and the actual <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop">DbgOp</a> is over 8x larger than this class, due to storing a <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>. This ID should be equal for all equal DbgOps, and also encodes whether the mapped <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop">DbgOp</a> is a constant, meaning that for simple equality or const-ness checks it is not necessary to lookup this ID.</p>


<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DbgOpID() {#a26fa3298b1a679da596a0ee2d0e41fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveDebugValues::DbgOpID::DbgOpID ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a26fa3298b1a679da596a0ee2d0e41fa5">DbgOpID</a>, <a href="#ae4daebd0f9238b300b28306a656cb475">RawID</a> and <a href="#a91064aebe93d3d6b7776a90451f2a854">UndefID</a>.</p>


<p>Referenced by <a href="#a26fa3298b1a679da596a0ee2d0e41fa5">DbgOpID</a>, <a href="#a6c2c43d8357f00d8b9ed9b37742047db">operator!=</a> and <a href="#a06e2402481c5028542702b6bf0390e9f">operator==</a>.</p>

</div>
</div>

### DbgOpID() {#af535b4df0c494b4f33356334c4c10faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveDebugValues::DbgOpID::DbgOpID (uint32_t RawID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="#ae4daebd0f9238b300b28306a656cb475">RawID</a>.</p>

</div>
</div>

### DbgOpID() {#a765daad2948619360609fd66c7f72832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveDebugValues::DbgOpID::DbgOpID (bool IsConst, uint32_t Index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="#ac2c275ac433f922d745b9ec6fe198600">ID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a6c2c43d8357f00d8b9ed9b37742047db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::DbgOpID::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a26fa3298b1a679da596a0ee2d0e41fa5">DbgOpID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#a06e2402481c5028542702b6bf0390e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::DbgOpID::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a26fa3298b1a679da596a0ee2d0e41fa5">DbgOpID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae4daebd0f9238b300b28306a656cb475">RawID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### asU32() {#a0e6661b8b23bbe5d428f8177ae17656b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LiveDebugValues::DbgOpID::asU32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="#ae4daebd0f9238b300b28306a656cb475">RawID</a>.</p>


<p>Referenced by <a href="#a743561a2288ede30c2992d98e1866505">dump</a>.</p>

</div>
</div>

### dump() {#a743561a2288ede30c2992d98e1866505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgOpID::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a> * MTrack, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap">DbgOpIDMap</a> * OpStore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 990 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a0e6661b8b23bbe5d428f8177ae17656b">asU32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop/#a645a31ec228d2d3f5ec064b726514cd2">LiveDebugValues::DbgOp::dump</a> and <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap/#a0ff8cac5d6ff149c80d136de06314455">LiveDebugValues::DbgOpIDMap::find</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue/#a9959e337a4d3e325e795686118700112">LiveDebugValues::DbgValue::dump</a>.</p>

</div>
</div>

### getIndex() {#a74cad069a68241540dfec8b7ab7ad921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LiveDebugValues::DbgOpID::getIndex ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="#ac2c275ac433f922d745b9ec6fe198600">ID</a>.</p>

</div>
</div>

### isConst() {#aa91469b374d4e14c8e445dc79420c850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::DbgOpID::isConst ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#ac2c275ac433f922d745b9ec6fe198600">ID</a> and <a href="#acae2cb38ea8ad4e487e5101c8bb085f7">isUndef</a>.</p>

</div>
</div>

### isUndef() {#acae2cb38ea8ad4e487e5101c8bb085f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::DbgOpID::isUndef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="#a91064aebe93d3d6b7776a90451f2a854">UndefID</a>.</p>


<p>Referenced by <a href="#aa91469b374d4e14c8e445dc79420c850">isConst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#a8f1daf4e1d0787d450ca7aa9a8e8686c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union LiveDebugValues::DbgOpID LiveDebugValues::DbgOpID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### ID {#ac2c275ac433f922d745b9ec6fe198600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct IsConstIndexPair LiveDebugValues::DbgOpID::ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a765daad2948619360609fd66c7f72832">DbgOpID</a>, <a href="#a74cad069a68241540dfec8b7ab7ad921">getIndex</a> and <a href="#aa91469b374d4e14c8e445dc79420c850">isConst</a>.</p>

</div>
</div>

### RawID {#ae4daebd0f9238b300b28306a656cb475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LiveDebugValues::DbgOpID::RawID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a0e6661b8b23bbe5d428f8177ae17656b">asU32</a>, <a href="#a26fa3298b1a679da596a0ee2d0e41fa5">DbgOpID</a>, <a href="#af535b4df0c494b4f33356334c4c10faa">DbgOpID</a> and <a href="#a06e2402481c5028542702b6bf0390e9f">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### UndefID {#a91064aebe93d3d6b7776a90451f2a854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgOpID DbgOpID::UndefID = <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a>(0xffffffff)</td>
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



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a26fa3298b1a679da596a0ee2d0e41fa5">DbgOpID</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap/#a0ff8cac5d6ff149c80d136de06314455">LiveDebugValues::DbgOpIDMap::find</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue/#aa70e8b6292c37300a3ea50fce69b2cdd">LiveDebugValues::DbgValue::getDbgOpID</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap/#a31b80daf003f8250c14e14fbb5d9a283">LiveDebugValues::DbgOpIDMap::insert</a> and <a href="#acae2cb38ea8ad4e487e5101c8bb085f7">isUndef</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
