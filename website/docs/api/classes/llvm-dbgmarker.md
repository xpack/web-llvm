---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dbgmarker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DbgMarker` Class

<p>Per-instruction record of debug-info. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DbgMarker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">llvm/IR/DebugProgramInstruction.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61126cfd97c32672a743dd41ecffc21d">DbgMarker</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad39ef3fe92125bd74a67fdfdfdf0e19c">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf6be32c12a1a6509d7ac0a4d0819f3f">getParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c76096cf924426a3ec7a830e055148">getParent</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98eceec46c49f571b3413d3f91e31e10">removeMarker</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle the removal of a marker: the position of debug-info has gone away, but the stored debug records should not. <a href="#a98eceec46c49f571b3413d3f91e31e10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2660a4c17b0c7f6c294a670ecc6812d7">dump</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2143a44a5fc334642c4507af1d73e458">removeFromParent</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfe9e3b0fff7798516c65590d8ab39fe">eraseFromParent</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a91755a39059240dcc0a2cdaa8b03ec">print</a> (raw_ostream &amp;O, bool IsForDebug=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement operator&lt;&lt; on <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>. <a href="#a5a91755a39059240dcc0a2cdaa8b03ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24a1b510b43c0dc48de0d37e6fff061">print</a> (raw_ostream &amp;ROS, ModuleSlotTracker &amp;MST, bool IsForDebug) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;::iterator &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac97b2d030b47783e5a1f334f0ad6f219">getDbgRecordRange</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce a range over all the DbgRecords in this Marker. <a href="#ac97b2d030b47783e5a1f334f0ad6f219">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;::const_iterator &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab49651eba09f1cf64f2ab0d0774f2cec">getDbgRecordRange</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab72d53ec1bee5605dfe12b8b594f40f5">absorbDebugValues</a> (DbgMarker &amp;Src, bool InsertAtHead)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer any DbgRecords from <span class="doxyComputerOutput">Src</span> into this <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>. <a href="#ab72d53ec1bee5605dfe12b8b594f40f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26190820a0a31cb926738f188db08f8b">absorbDebugValues</a> (iterator_range&lt; DbgRecord::self_iterator &gt; Range, DbgMarker &amp;Src, bool InsertAtHead)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer the DbgRecords in <span class="doxyComputerOutput">Range</span> from <span class="doxyComputerOutput">Src</span> into this <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>. <a href="#a26190820a0a31cb926738f188db08f8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad286983c7ed10a987ff5c2a3391aa9de">insertDbgRecord</a> (DbgRecord *New, bool InsertAtHead)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> into this <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>, at the end of the list. <a href="#ad286983c7ed10a987ff5c2a3391aa9de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad39cef6524b0757f3d47c5e988c20214">insertDbgRecord</a> (DbgRecord *New, DbgRecord *InsertBefore)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> prior to a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> contained within this marker. <a href="#ad39cef6524b0757f3d47c5e988c20214">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e3e46a5043b9376725624d0655d187a">insertDbgRecordAfter</a> (DbgRecord *New, DbgRecord *InsertAfter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> after a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> contained within this marker. <a href="#a4e3e46a5043b9376725624d0655d187a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;::iterator &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d1ce6143d40c11fda669dd0a3a7fd4f">cloneDebugInfoFrom</a> (DbgMarker *From, std::optional&lt; simple_ilist&lt; DbgRecord &gt;::iterator &gt; FromHere, bool InsertAtHead=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone all DbgMarkers from <span class="doxyComputerOutput">From</span> into this marker. <a href="#a4d1ce6143d40c11fda669dd0a3a7fd4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbecb38d0e9efb34d40d57e80ea9e8bd">dropDbgRecords</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase all DbgRecords in this <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>. <a href="#abbecb38d0e9efb34d40d57e80ea9e8bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acde68625afdf845a15c3358956e34057">dropOneDbgRecord</a> (DbgRecord *DR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase a single <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> from this marker. <a href="#acde68625afdf845a15c3358956e34057">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e5e8e39d6d654db719920186533fac">MarkedInstr</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Link back to the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that owns this marker. <a href="#a36e5e8e39d6d654db719920186533fac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of DbgRecords, the non-instruction equivalent of llvm.dbg. <a href="#acf93a5910e8b1adcdca71705495e5d92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;::iterator &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a035be77460cd22dc24e1f25b30ad6377">getEmptyDbgRecordRange</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaea792ba3c9036a33d483f4a7516f9b">EmptyDbgMarker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We generally act like all llvm Instructions have a range of DbgRecords attached to them, but in reality sometimes we don't allocate the <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> to save time and memory, but still have to return ranges of DbgRecords. <a href="#afaea792ba3c9036a33d483f4a7516f9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Per-instruction record of debug-info.</p>


<p>If an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> is the position of some debugging information, it points at a <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> storing that info. Each marker points back at the instruction that owns it. Various utilities are provided for manipulating the DbgRecords contained within this marker.</p>


<p>This class has a rough surface area, because it's needed to preserve the one arefact that we can't yet eliminate from the intrinsic / dbg.value debug-info design: the order of records is significant, and duplicates can exist. Thus, if one has a run of debug-info records such as: dbg.value(... foo = barinst dbg.value(... and remove barinst, then the dbg.values must be preserved in the correct order. Hence, the use of iterators to select positions to insert things into, or the occasional InsertAtHead parameter indicating that new records should go at the start of the list.</p>


<p>There are only five or six places in LLVM that truly rely on this ordering, which we can improve in the future. Additionally, many improvements in the way that debug-info is stored can be achieved in this class, at a future date.</p>


<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DbgMarker() {#a61126cfd97c32672a743dd41ecffc21d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgMarker::DbgMarker ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Referenced by <a href="#ab72d53ec1bee5605dfe12b8b594f40f5">absorbDebugValues</a>, <a href="#a26190820a0a31cb926738f188db08f8b">absorbDebugValues</a>, <a href="#a4d1ce6143d40c11fda669dd0a3a7fd4f">cloneDebugInfoFrom</a> and <a href="#a98eceec46c49f571b3413d3f91e31e10">removeMarker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### absorbDebugValues() {#ab72d53ec1bee5605dfe12b8b594f40f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgMarker::absorbDebugValues (<a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> &amp; Src, bool InsertAtHead)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transfer any DbgRecords from <span class="doxyComputerOutput">Src</span> into this <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>.</p>


<p>If <span class="doxyComputerOutput">InsertAtHead</span> is true, place them before existing DbgRecords, otherwise afterwards.</p>


<p>Declaration at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a61126cfd97c32672a743dd41ecffc21d">DbgMarker</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#ad412124c6d332b19147cb1cce6cbd3e9">llvm::DbgRecord::setMarker</a> and <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>


<p>Referenced by <a href="#a98eceec46c49f571b3413d3f91e31e10">removeMarker</a>.</p>

</div>
</div>

### absorbDebugValues() {#a26190820a0a31cb926738f188db08f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgMarker::absorbDebugValues (<a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a35975cf965c120e55130f30dd377418d">DbgRecord::self_iterator</a> &gt; Range, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> &amp; Src, bool InsertAtHead)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transfer the DbgRecords in <span class="doxyComputerOutput">Range</span> from <span class="doxyComputerOutput">Src</span> into this <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>.</p>


<p>If <span class="doxyComputerOutput">InsertAtHead</span> is true, place them before existing DbgRecords, otherwise</p>


<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a61126cfd97c32672a743dd41ecffc21d">DbgMarker</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>

</div>
</div>

### cloneDebugInfoFrom() {#a4d1ce6143d40c11fda669dd0a3a7fd4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; simple_ilist&lt; DbgRecord &gt;::iterator &gt; llvm::DbgMarker::cloneDebugInfoFrom (<a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> * From, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;::iterator &gt; FromHere, bool InsertAtHead=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone all DbgMarkers from <span class="doxyComputerOutput">From</span> into this marker.</p>


<p>There are numerous options to customise the source/destination, due to gnarliness, see class comment. <span class="doxyComputerOutput">FromHere</span> If non-null, copy from FromHere to the end of From's DbgRecords <span class="doxyComputerOutput">InsertAtHead</span> Place the cloned DbgRecords at the start of StoredDbgRecords</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Range over all the newly cloned DbgRecords</p></dd>
</dl>


<p>Declaration at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#a61126cfd97c32672a743dd41ecffc21d">DbgMarker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>.</p>

</div>
</div>

### dropDbgRecords() {#abbecb38d0e9efb34d40d57e80ea9e8bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgMarker::dropDbgRecords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase all DbgRecords in this <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>.</p>

<p>Declaration at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a4d8ddb598af3628af2a22306f38eb12e">llvm::DbgRecord::deleteRecord</a> and <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>


<p>Referenced by <a href="#acfe9e3b0fff7798516c65590d8ab39fe">eraseFromParent</a>.</p>

</div>
</div>

### dropOneDbgRecord() {#acde68625afdf845a15c3358956e34057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgMarker::dropOneDbgRecord (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * DR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase a single <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> from this marker.</p>


<p>In an ideal future, we would never erase an assignment in this way, but it's the equivalent to erasing a debug intrinsic from a block.</p>


<p>Declaration at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a4d8ddb598af3628af2a22306f38eb12e">llvm::DbgRecord::deleteRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aa1b7611e70113463caabc2bc84bd08bf">llvm::DbgRecord::getMarker</a> and <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>

</div>
</div>

### dump() {#a2660a4c17b0c7f6c294a670ecc6812d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void DbgMarker::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 5308 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### empty() {#ad39ef3fe92125bd74a67fdfdfdf0e19c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgMarker::empty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>

</div>
</div>

### eraseFromParent() {#acfe9e3b0fff7798516c65590d8ab39fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgMarker::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#abbecb38d0e9efb34d40d57e80ea9e8bd">dropDbgRecords</a>, <a href="#a36e5e8e39d6d654db719920186533fac">MarkedInstr</a> and <a href="#a2143a44a5fc334642c4507af1d73e458">removeFromParent</a>.</p>


<p>Referenced by <a href="#a98eceec46c49f571b3413d3f91e31e10">removeMarker</a>.</p>

</div>
</div>

### getDbgRecordRange() {#ac97b2d030b47783e5a1f334f0ad6f219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; DbgRecord::self_iterator &gt; llvm::DbgMarker::getDbgRecordRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Produce a range over all the DbgRecords in this Marker.</p>

<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8bca4688ad9d211ceeaba65271a9fbfa">llvm::getDbgRecordRange</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a05eb84c8f630be406f61761013146574">getNextNode</a>.</p>

</div>
</div>

### getDbgRecordRange() {#ab49651eba09f1cf64f2ab0d0774f2cec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; DbgRecord::const_self_iterator &gt; llvm::DbgMarker::getDbgRecordRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>

</div>
</div>

### getParent() {#acf6be32c12a1a6509d7ac0a4d0819f3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * llvm::DbgMarker::getParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="#a36e5e8e39d6d654db719920186533fac">MarkedInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7b98dd2ff18a320795917ace7f8010db">getModuleFromDPI</a>, <a href="#a98eceec46c49f571b3413d3f91e31e10">removeMarker</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#aea660fd3de70e7854de06b7e212f0ecd">RewriteUsesOfClonedInstructions</a>.</p>

</div>
</div>

### getParent() {#a08c76096cf924426a3ec7a830e055148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::DbgMarker::getParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="#a36e5e8e39d6d654db719920186533fac">MarkedInstr</a>.</p>

</div>
</div>

### insertDbgRecord() {#ad286983c7ed10a987ff5c2a3391aa9de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgMarker::insertDbgRecord (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * New, bool InsertAtHead)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> into this <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>, at the end of the list.</p>


<p>If <span class="doxyComputerOutput">InsertAtHead</span> is true, at the start.</p>


<p>Declaration at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a569963898bf9957c3f3c944b34cbb7d7">llvm::DbgRecord::insertBefore</a>.</p>

</div>
</div>

### insertDbgRecord() {#ad39cef6524b0757f3d47c5e988c20214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgMarker::insertDbgRecord (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * New, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> prior to a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> contained within this marker.</p>

<p>Declaration at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aa1b7611e70113463caabc2bc84bd08bf">llvm::DbgRecord::getMarker</a> and <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>

</div>
</div>

### insertDbgRecordAfter() {#a4e3e46a5043b9376725624d0655d187a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgMarker::insertDbgRecordAfter (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * New, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * InsertAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> after a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> contained within this marker.</p>

<p>Declaration at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aa1b7611e70113463caabc2bc84bd08bf">llvm::DbgRecord::getMarker</a> and <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a029e51f0556ca3cf6bb0116298444a0d">llvm::DbgRecord::insertAfter</a>.</p>

</div>
</div>

### print() {#a5a91755a39059240dcc0a2cdaa8b03ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgMarker::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement operator&lt;&lt; on <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>.</p>

<p>Declaration at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 4995 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7b98dd2ff18a320795917ace7f8010db">getModuleFromDPI</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a79a16d2529ae3fc775887b93f65cb949">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### print() {#ad24a1b510b43c0dc48de0d37e6fff061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgMarker::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; ROS, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, bool IsForDebug)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 5007 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a802b848d702c132a97b3da454c1e68c1">llvm::ModuleSlotTracker::getMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7b98dd2ff18a320795917ace7f8010db">getModuleFromDPI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#ace93d877ff9298d25a15e2a32f765653">llvm::ModuleSlotTracker::incorporateFunction</a>.</p>

</div>
</div>

### removeFromParent() {#a2143a44a5fc334642c4507af1d73e458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgMarker::removeFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="#a36e5e8e39d6d654db719920186533fac">MarkedInstr</a>.</p>


<p>Referenced by <a href="#acfe9e3b0fff7798516c65590d8ab39fe">eraseFromParent</a>.</p>

</div>
</div>

### removeMarker() {#a98eceec46c49f571b3413d3f91e31e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgMarker::removeMarker ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle the removal of a marker: the position of debug-info has gone away, but the stored debug records should not.</p>


<p>Drop them onto the next instruction, or otherwise work out what to do with them.</p>


<p>Declaration at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="#ab72d53ec1bee5605dfe12b8b594f40f5">absorbDebugValues</a>, <a href="#a61126cfd97c32672a743dd41ecffc21d">DbgMarker</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0172245e9f9a9097b5d403ab70348bdd">llvm::Instruction::DebugMarker</a>, <a href="#acfe9e3b0fff7798516c65590d8ab39fe">eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="#acf6be32c12a1a6509d7ac0a4d0819f3f">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#a36e5e8e39d6d654db719920186533fac">MarkedInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a15ee901003da006e9da907c2bf70b9ec">llvm::BasicBlock::setTrailingDbgRecords</a> and <a href="#acf93a5910e8b1adcdca71705495e5d92">StoredDbgRecords</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MarkedInstr {#a36e5e8e39d6d654db719920186533fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::DbgMarker::MarkedInstr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Link back to the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that owns this marker.</p>


<p>Can be null during operations that move a marker from one instruction to another.</p>


<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Referenced by <a href="#acfe9e3b0fff7798516c65590d8ab39fe">eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a05eb84c8f630be406f61761013146574">getNextNode</a>, <a href="#a08c76096cf924426a3ec7a830e055148">getParent</a>, <a href="#acf6be32c12a1a6509d7ac0a4d0819f3f">getParent</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a16ec90e40a57f00c972a2e26352bf658">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgMarker</a>, <a href="#a2143a44a5fc334642c4507af1d73e458">removeFromParent</a>, <a href="#a98eceec46c49f571b3413d3f91e31e10">removeMarker</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a>.</p>

</div>
</div>

### StoredDbgRecords {#acf93a5910e8b1adcdca71705495e5d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">simple_ilist&lt;DbgRecord&gt; llvm::DbgMarker::StoredDbgRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of DbgRecords, the non-instruction equivalent of llvm.dbg.</p>


<ul class="doxyList ">
<li>intrinsics. There is a one-to-one relationship between each debug intrinsic in a block and each <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> once the representation has been converted, and the ordering is meaningful in the same way.</li>
</ul>

<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Referenced by <a href="#ab72d53ec1bee5605dfe12b8b594f40f5">absorbDebugValues</a>, <a href="#a26190820a0a31cb926738f188db08f8b">absorbDebugValues</a>, <a href="#a4d1ce6143d40c11fda669dd0a3a7fd4f">cloneDebugInfoFrom</a>, <a href="#abbecb38d0e9efb34d40d57e80ea9e8bd">dropDbgRecords</a>, <a href="#acde68625afdf845a15c3358956e34057">dropOneDbgRecord</a>, <a href="#ad39ef3fe92125bd74a67fdfdfdf0e19c">empty</a>, <a href="#ac97b2d030b47783e5a1f334f0ad6f219">getDbgRecordRange</a>, <a href="#ab49651eba09f1cf64f2ab0d0774f2cec">getDbgRecordRange</a>, <a href="#ad286983c7ed10a987ff5c2a3391aa9de">insertDbgRecord</a>, <a href="#ad39cef6524b0757f3d47c5e988c20214">insertDbgRecord</a>, <a href="#a4e3e46a5043b9376725624d0655d187a">insertDbgRecordAfter</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a16ec90e40a57f00c972a2e26352bf658">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgMarker</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a04a8b2dc4d72db72e1f87bdec4074973">llvm::DbgRecord::removeFromParent</a> and <a href="#a98eceec46c49f571b3413d3f91e31e10">removeMarker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEmptyDbgRecordRange() {#a035be77460cd22dc24e1f25b30ad6377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; simple_ilist&lt; DbgRecord &gt;::iterator &gt; llvm::DbgMarker::getEmptyDbgRecordRange ()</td>
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



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="#afaea792ba3c9036a33d483f4a7516f9b">EmptyDbgMarker</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8bca4688ad9d211ceeaba65271a9fbfa">llvm::getDbgRecordRange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### EmptyDbgMarker {#afaea792ba3c9036a33d483f4a7516f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgMarker llvm::DbgMarker::EmptyDbgMarker</td>
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

<p>We generally act like all llvm Instructions have a range of DbgRecords attached to them, but in reality sometimes we don't allocate the <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> to save time and memory, but still have to return ranges of DbgRecords.</p>


<p>When we need to describe such an unallocated <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> range, use this static markers range instead. This will bite us if someone tries to insert a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> in that range, but they should be using the Official (TM) API for that.</p>


<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Referenced by <a href="#a035be77460cd22dc24e1f25b30ad6377">getEmptyDbgRecordRange</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
