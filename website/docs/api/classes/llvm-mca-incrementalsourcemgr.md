---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/incrementalsourcemgr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IncrementalSourceMgr` Class Reference

<p>An implementation of <em><a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">SourceMgr</a></em> that allows users to add new instructions incrementally / dynamically. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::mca::IncrementalSourceMgr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">llvm/MCA/IncrementalSourceMgr.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">SourceMgr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstracting the input code sequence (a sequence of <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>) and assigning unique identifiers to every instruction in the sequence. <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f6f6cee3110562acdf6b7c4302809a">InstFreedCallback</a> = std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> *)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when an instruction is no longer needed. <a href="#a56f6f6cee3110562acdf6b7c4302809a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa90e9baa09e3b21a90ea3df2b802749e">IncrementalSourceMgr</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac1bf46c1b8d46f2675e857ff328b2e1">clear</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f4a2d708bc5d5a3f9c139948ae3c2e2">setOnInstFreedCallback</a> (InstFreedCallback CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a callback that is invoked when a <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">mca::Instruction</a> is no longer needed. <a href="#a0f4a2d708bc5d5a3f9c139948ae3c2e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr/#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bc6c0a4359b9969b36c14eb243cbfe0">getInstructions</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides a fixed range of <em><a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr/#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a></em> to iterate. <a href="#a5bc6c0a4359b9969b36c14eb243cbfe0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ab6fe3fb026ff48265f9836f282d5b3">hasNext</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether there is any <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em> to inspect / peek next. <a href="#a7ab6fe3fb026ff48265f9836f282d5b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba19dadd2449aab5779bf9677d35604">isEnd</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the instruction stream has eneded. <a href="#a4ba19dadd2449aab5779bf9677d35604">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1ccc01d5bce4605ec868529a91bc5f">peekNext</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The next <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em>. <a href="#a6c1ccc01d5bce4605ec868529a91bc5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a79fdf47b12f2543c93039662106caf">addInst</a> (UniqueInst &amp;&amp;Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new instruction. <a href="#a5a79fdf47b12f2543c93039662106caf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3145b940234a234e7ce649909952500a">addRecycledInst</a> (Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a recycled instruction. <a href="#a3145b940234a234e7ce649909952500a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e7a65dca58ec0969862ae9fe6ba64e">updateNext</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance to the next <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em>. <a href="#ae7e7a65dca58ec0969862ae9fe6ba64e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95676d1de997484e03ec6f0ce79d1331">endOfStream</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark the end of instruction stream. <a href="#a95676d1de997484e03ec6f0ce79d1331">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55086232b62ba76e882e380ca1e4576a">printStatistic</a> (raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print statistic about instruction recycling stats. <a href="#a55086232b62ba76e882e380ca1e4576a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr/#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a874a1818f5ba4817157d0b9984c48709">InstStorage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Owner of all <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">mca::Instruction</a> instances. <a href="#a874a1818f5ba4817157d0b9984c48709">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cfc9c04f70a48fff31cc9e7c83051c5">Staging</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instructions that are ready to be used. <a href="#a8cfc9c04f70a48fff31cc9e7c83051c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d888c0488860f2071c07dcf4aad16ae">TotalCounter</a> = 0U</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current instruction index. <a href="#a2d888c0488860f2071c07dcf4aad16ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2444704e623564b0785065d57ef0e4db">EOS</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>End-of-stream flag. <a href="#a2444704e623564b0785065d57ef0e4db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">InstFreedCallback</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbcd36a4378ebe614b46a1a4ec91943a">InstFreedCB</a></td>
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

<p>An implementation of <em><a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">SourceMgr</a></em> that allows users to add new instructions incrementally / dynamically.</p>


<p>Note that this <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">SourceMgr</a> takes ownership of all <em><a href="/web-llvm/docs/api/classes/llvm/mca/instruction">mca::Instruction</a></em>.</p>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### InstFreedCallback {#a56f6f6cee3110562acdf6b7c4302809a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::mca::IncrementalSourceMgr::InstFreedCallback =  std::function&lt;void(Instruction *)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called when an instruction is no longer needed.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IncrementalSourceMgr() {#aa90e9baa09e3b21a90ea3df2b802749e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::IncrementalSourceMgr::IncrementalSourceMgr ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addInst() {#a5a79fdf47b12f2543c93039662106caf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::IncrementalSourceMgr::addInst (<a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr/#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a> &amp;&amp; Inst)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new instruction.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

### addRecycledInst() {#a3145b940234a234e7ce649909952500a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::IncrementalSourceMgr::addRecycledInst (<a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> * Inst)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a recycled instruction.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

### clear() {#aac1bf46c1b8d46f2675e857ff328b2e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IncrementalSourceMgr::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/incrementalsourcemgr-cpp">IncrementalSourceMgr.cpp</a>.</p>

</div>
</div>

### endOfStream() {#a95676d1de997484e03ec6f0ce79d1331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::IncrementalSourceMgr::endOfStream ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark the end of instruction stream.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

### getInstructions() {#a5bc6c0a4359b9969b36c14eb243cbfe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; UniqueInst &gt; llvm::mca::IncrementalSourceMgr::getInstructions ()</td>
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

<p>Provides a fixed range of <em><a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr/#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a></em> to iterate.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### hasNext() {#a7ab6fe3fb026ff48265f9836f282d5b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::IncrementalSourceMgr::hasNext ()</td>
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

<p>Whether there is any <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em> to inspect / peek next.</p>


<p>Note that returning false from this doesn't mean the instruction stream has ended.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>


<p>Referenced by <a href="#a6c1ccc01d5bce4605ec868529a91bc5f">peekNext</a>.</p>

</div>
</div>

### isEnd() {#a4ba19dadd2449aab5779bf9677d35604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::IncrementalSourceMgr::isEnd ()</td>
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

<p>Whether the instruction stream has eneded.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

### peekNext() {#a6c1ccc01d5bce4605ec868529a91bc5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceRef llvm::mca::IncrementalSourceMgr::peekNext ()</td>
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

<p>The next <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em>.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7ab6fe3fb026ff48265f9836f282d5b3">hasNext</a>.</p>

</div>
</div>

### printStatistic() {#a55086232b62ba76e882e380ca1e4576a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IncrementalSourceMgr::printStatistic (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print statistic about instruction recycling stats.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/incrementalsourcemgr-cpp">IncrementalSourceMgr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>.</p>

</div>
</div>

### setOnInstFreedCallback() {#a0f4a2d708bc5d5a3f9c139948ae3c2e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::IncrementalSourceMgr::setOnInstFreedCallback (InstFreedCallback CB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set a callback that is invoked when a <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">mca::Instruction</a> is no longer needed.</p>


<p>This is usually used for recycling the instruction.</p>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

### updateNext() {#ae7e7a65dca58ec0969862ae9fe6ba64e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IncrementalSourceMgr::updateNext ()</td>
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

<p>Advance to the next <em><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a6194ec8d4ff9d0552963291008b31ee7">SourceRef</a></em>.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/incrementalsourcemgr-cpp">IncrementalSourceMgr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EOS {#a2444704e623564b0785065d57ef0e4db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::IncrementalSourceMgr::EOS = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>End-of-stream flag.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

### InstFreedCB {#abbcd36a4378ebe614b46a1a4ec91943a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstFreedCallback llvm::mca::IncrementalSourceMgr::InstFreedCB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

### InstStorage {#a874a1818f5ba4817157d0b9984c48709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt;UniqueInst&gt; llvm::mca::IncrementalSourceMgr::InstStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Owner of all <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">mca::Instruction</a> instances.</p>


<p>Note that we use std::deque here to have a better throughput, in comparison to std::vector or <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>, as they usually pay a higher re-allocation cost when there is a large number of instructions.</p>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

### Staging {#a8cfc9c04f70a48fff31cc9e7c83051c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt;Instruction *&gt; llvm::mca::IncrementalSourceMgr::Staging</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instructions that are ready to be used.</p>


<p>Each of them is a pointer of an <em><a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr/#ac81a93288d7e85027cbd1ec07d5d8432">UniqueInst</a></em> inside InstStorage.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

### TotalCounter {#a2d888c0488860f2071c07dcf4aad16ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::IncrementalSourceMgr::TotalCounter = 0U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current instruction index.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/incrementalsourcemgr-h">IncrementalSourceMgr.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mca/incrementalsourcemgr-cpp">IncrementalSourceMgr.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
