---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LDVSSABlock` Class Reference

<p>Thin wrapper around a block for SSA Updater interface. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{InstrRefBasedImpl.cpp}::LDVSSABlock { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf4c8e73a87f414924b17cd8e1cd9af">PHIListT</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaphi">LDVSSAPhi</a>, 1 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a170ab3942820bda10dcbbb825da88fce">LDVSSABlock</a> (MachineBasicBlock &amp;BB, LDVSSAUpdater &amp;Updater)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablockiterator">LDVSSABlockIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a285fb198bbe35cc1fa6c27ef4dbc5e42">succ_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablockiterator">LDVSSABlockIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e0d53b8490bf09534b1efd1659461e2">succ_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaphi">LDVSSAPhi</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa96d9dec40a4511895bdf897fbbb3801">newPHI</a> (BlockValueNum Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> has requested a PHI: create that within this block record. <a href="#aa96d9dec40a4511895bdf897fbbb3801">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abcf4c8e73a87f414924b17cd8e1cd9af">PHIListT</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a280774b93e812679c3a35c1aa6c86b23">phis</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> wishes to know what PHIs already exist in this block. <a href="#a280774b93e812679c3a35c1aa6c86b23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52b402bdc44acc7380d60d09a59b71b0">BB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaupdater">LDVSSAUpdater</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac29b7dc686f19c84e5efe7b9012c81">Updater</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abcf4c8e73a87f414924b17cd8e1cd9af">PHIListT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9aa68ac8f9e8aecab33ec2bd5551be">PHIList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of PHIs in this block. There should only ever be one. <a href="#a3f9aa68ac8f9e8aecab33ec2bd5551be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Thin wrapper around a block for SSA Updater interface.</p>


<p>Necessary because we need to track the PHI value(s) that we may have observed as necessary in this block.</p>


<p>Definition at line 3919 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### PHIListT {#abcf4c8e73a87f414924b17cd8e1cd9af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{InstrRefBasedImpl.cpp}::LDVSSABlock::PHIListT =  SmallVector&lt;LDVSSAPhi, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3923 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LDVSSABlock() {#a170ab3942820bda10dcbbb825da88fce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InstrRefBasedImpl.cpp}::LDVSSABlock::LDVSSABlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaupdater">LDVSSAUpdater</a> &amp; Updater)</td>
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



<p>Definition at line 3927 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a52b402bdc44acc7380d60d09a59b71b0">BB</a> and <a href="#a7ac29b7dc686f19c84e5efe7b9012c81">Updater</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### newPHI() {#aa96d9dec40a4511895bdf897fbbb3801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSAPhi * anonymous{InstrRefBasedImpl.cpp}::LDVSSABlock::newPHI (<a href="/web-llvm/docs/api/namespaces/anonymous-instrrefbasedimpl-cpp-/#a8c63effba4b56132c365c02a07251561">BlockValueNum</a> Value)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> has requested a PHI: create that within this block record.</p>

<p>Definition at line 3939 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="#a3f9aa68ac8f9e8aecab33ec2bd5551be">PHIList</a>.</p>

</div>
</div>

### phis() {#a280774b93e812679c3a35c1aa6c86b23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHIListT &amp; anonymous{InstrRefBasedImpl.cpp}::LDVSSABlock::phis ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> wishes to know what PHIs already exist in this block.</p>

<p>Definition at line 3945 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="#a3f9aa68ac8f9e8aecab33ec2bd5551be">PHIList</a>.</p>

</div>
</div>

### succ\_begin() {#a285fb198bbe35cc1fa6c27ef4dbc5e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSABlockIterator anonymous{InstrRefBasedImpl.cpp}::LDVSSABlock::succ_begin ()</td>
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



<p>Definition at line 3930 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a52b402bdc44acc7380d60d09a59b71b0">BB</a> and <a href="#a7ac29b7dc686f19c84e5efe7b9012c81">Updater</a>.</p>

</div>
</div>

### succ\_end() {#a5e0d53b8490bf09534b1efd1659461e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSABlockIterator anonymous{InstrRefBasedImpl.cpp}::LDVSSABlock::succ_end ()</td>
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



<p>Definition at line 3934 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a52b402bdc44acc7380d60d09a59b71b0">BB</a> and <a href="#a7ac29b7dc686f19c84e5efe7b9012c81">Updater</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BB {#a52b402bdc44acc7380d60d09a59b71b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock&amp; anonymous{InstrRefBasedImpl.cpp}::LDVSSABlock::BB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3921 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaupdater/#aebd31ac5da9b05da0496de42fdb1f191">anonymous{InstrRefBasedImpl.cpp}::LDVSSAUpdater::getValue</a>, <a href="#a170ab3942820bda10dcbbb825da88fce">LDVSSABlock</a>, <a href="#a285fb198bbe35cc1fa6c27ef4dbc5e42">succ_begin</a> and <a href="#a5e0d53b8490bf09534b1efd1659461e2">succ_end</a>.</p>

</div>
</div>

### PHIList {#a3f9aa68ac8f9e8aecab33ec2bd5551be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHIListT anonymous{InstrRefBasedImpl.cpp}::LDVSSABlock::PHIList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of PHIs in this block. There should only ever be one.</p>

<p>Definition at line 3925 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#aa96d9dec40a4511895bdf897fbbb3801">newPHI</a> and <a href="#a280774b93e812679c3a35c1aa6c86b23">phis</a>.</p>

</div>
</div>

### Updater {#a7ac29b7dc686f19c84e5efe7b9012c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSAUpdater&amp; anonymous{InstrRefBasedImpl.cpp}::LDVSSABlock::Updater</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3922 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a170ab3942820bda10dcbbb825da88fce">LDVSSABlock</a>, <a href="#a285fb198bbe35cc1fa6c27ef4dbc5e42">succ_begin</a> and <a href="#a5e0d53b8490bf09534b1efd1659461e2">succ_end</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
