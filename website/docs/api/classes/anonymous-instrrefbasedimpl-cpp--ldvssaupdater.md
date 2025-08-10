---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaupdater
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LDVSSAUpdater` Class

<p>Utility class for the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> interface: tracks blocks, PHIs and values while <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> is exploring the CFG. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeef57536617f4a175b045bf015a8bdb">LDVSSAUpdater</a> (LocIdx L, const FuncValueTable &amp;MLiveIns)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e0fdd8232c2647bb86992a593c42cc6">~LDVSSAUpdater</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d6542e763c848192704ad2a7adb9910">reset</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock">LDVSSABlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8594a94db7702a43b08bf55a9bce60fe">getSSALDVBlock</a> (MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a given MBB, create a wrapper block for it. <a href="#a8594a94db7702a43b08bf55a9bce60fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-instrrefbasedimpl-cpp-/#a8c63effba4b56132c365c02a07251561">BlockValueNum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd31ac5da9b05da0496de42fdb1f191">getValue</a> (LDVSSABlock *LDVBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the live-in value number for the given block. <a href="#aebd31ac5da9b05da0496de42fdb1f191">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-instrrefbasedimpl-cpp-/#a8c63effba4b56132c365c02a07251561">BlockValueNum</a>, <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaphi">LDVSSAPhi</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4593aef60bd2c6a29b6e3d80d386158a">PHIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of value numbers to PHI records. <a href="#a4593aef60bd2c6a29b6e3d80d386158a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/namespaces/anonymous-instrrefbasedimpl-cpp-/#a8c63effba4b56132c365c02a07251561">BlockValueNum</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ff4d8f56e2494a870c2fb739e5dea1">PoisonMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of which blocks generate Undef values – blocks that are not dominated by any Def. <a href="#a90ff4d8f56e2494a870c2fb739e5dea1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock">LDVSSABlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a1f9d35131c0434a59bdbce8cfa74b">BlockMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of machine blocks to our own records of them. <a href="#a64a1f9d35131c0434a59bdbce8cfa74b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5617610cefec0e080cafb643b3f2a19e">Loc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Machine location where any PHI must occur. <a href="#a5617610cefec0e080cafb643b3f2a19e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a690763e8c1022c6482c95d63a457404b">MLiveIns</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Table of live-in machine value numbers for blocks / locations. <a href="#a690763e8c1022c6482c95d63a457404b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Utility class for the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> interface: tracks blocks, PHIs and values while <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> is exploring the CFG.</p>


<p>It's passed as a handle / baton to</p>


<p>Definition at line 3951 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LDVSSAUpdater() {#aeeef57536617f4a175b045bf015a8bdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater::LDVSSAUpdater (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MLiveIns)</td>
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



<p>Definition at line 3965 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a5617610cefec0e080cafb643b3f2a19e">Loc</a> and <a href="#a690763e8c1022c6482c95d63a457404b">MLiveIns</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LDVSSAUpdater() {#a8e0fdd8232c2647bb86992a593c42cc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater::~LDVSSAUpdater ()</td>
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



<p>Definition at line 3977 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="#a9d6542e763c848192704ad2a7adb9910">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSSALDVBlock() {#a8594a94db7702a43b08bf55a9bce60fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSABlock * anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater::getSSALDVBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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

<p>For a given MBB, create a wrapper block for it.</p>


<p>Stores it in the <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaupdater">LDVSSAUpdater</a> block map.</p>


<p>Definition at line 3981 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="#a64a1f9d35131c0434a59bdbce8cfa74b">BlockMap</a>.</p>

</div>
</div>

### getValue() {#aebd31ac5da9b05da0496de42fdb1f191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockValueNum anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater::getValue (<a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock">LDVSSABlock</a> * LDVBB)</td>
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

<p>Find the live-in value number for the given block.</p>


<p>Looks up the value at the PHI location on entry.</p>


<p>Definition at line 3990 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock/#a52b402bdc44acc7380d60d09a59b71b0">anonymous{InstrRefBasedImpl.cpp}::LDVSSABlock::BB</a>, <a href="#a5617610cefec0e080cafb643b3f2a19e">Loc</a> and <a href="#a690763e8c1022c6482c95d63a457404b">MLiveIns</a>.</p>

</div>
</div>

### reset() {#a9d6542e763c848192704ad2a7adb9910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater::reset ()</td>
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



<p>Definition at line 3968 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="#a64a1f9d35131c0434a59bdbce8cfa74b">BlockMap</a>, <a href="#a4593aef60bd2c6a29b6e3d80d386158a">PHIs</a> and <a href="#a90ff4d8f56e2494a870c2fb739e5dea1">PoisonMap</a>.</p>


<p>Referenced by <a href="#a8e0fdd8232c2647bb86992a593c42cc6">~LDVSSAUpdater</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BlockMap {#a64a1f9d35131c0434a59bdbce8cfa74b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineBasicBlock *, LDVSSABlock *&gt; anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater::BlockMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of machine blocks to our own records of them.</p>

<p>Definition at line 3959 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a8594a94db7702a43b08bf55a9bce60fe">getSSALDVBlock</a> and <a href="#a9d6542e763c848192704ad2a7adb9910">reset</a>.</p>

</div>
</div>

### Loc {#a5617610cefec0e080cafb643b3f2a19e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocIdx anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Machine location where any PHI must occur.</p>

<p>Definition at line 3961 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#aebd31ac5da9b05da0496de42fdb1f191">getValue</a> and <a href="#aeeef57536617f4a175b045bf015a8bdb">LDVSSAUpdater</a>.</p>

</div>
</div>

### MLiveIns {#a690763e8c1022c6482c95d63a457404b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FuncValueTable&amp; anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater::MLiveIns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Table of live-in machine value numbers for blocks / locations.</p>

<p>Definition at line 3963 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#aebd31ac5da9b05da0496de42fdb1f191">getValue</a> and <a href="#aeeef57536617f4a175b045bf015a8bdb">LDVSSAUpdater</a>.</p>

</div>
</div>

### PHIs {#a4593aef60bd2c6a29b6e3d80d386158a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BlockValueNum, LDVSSAPhi *&gt; anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater::PHIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of value numbers to PHI records.</p>

<p>Definition at line 3954 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a9d6542e763c848192704ad2a7adb9910">reset</a>.</p>

</div>
</div>

### PoisonMap {#a90ff4d8f56e2494a870c2fb739e5dea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineBasicBlock *, BlockValueNum&gt; anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater::PoisonMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of which blocks generate Undef values – blocks that are not dominated by any Def.</p>

<p>Definition at line 3957 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a9d6542e763c848192704ad2a7adb9910">reset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
