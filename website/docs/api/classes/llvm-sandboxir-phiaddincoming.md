---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/phiaddincoming
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PHIAddIncoming` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::PHIAddIncoming { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">llvm/SandboxIR/Tracker.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/irchangebase">IRChangeBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base class for IR Change classes. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/irchangebase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63428d678e776cf898d5c59c2e943331">PHIAddIncoming</a> (PHINode *PHI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a844f1664a7830b5c507a88f0a1505ef9">revert</a> (Tracker &amp;Tracker) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This runs when changes get reverted. <a href="#a844f1664a7830b5c507a88f0a1505ef9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa5a83854e01e1d63febc1df6b2e1f46">accept</a> () final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This runs when changes get accepted. <a href="#aaa5a83854e01e1d63febc1df6b2e1f46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71e36f06d168af310af38cbab4285003">dump</a> (raw_ostream &amp;OS) const final</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1d42c933976072a83a9a95416ce17ae">dump</a> () const final</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addb79af930331fe0c3297afdb86f5619">PHI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af174c2dbcfa84dc6e56c1866e19cf08c">Idx</a></td>
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


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PHIAddIncoming() {#a63428d678e776cf898d5c59c2e943331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHIAddIncoming::PHIAddIncoming (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode">PHINode</a> * PHI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### accept() {#aaa5a83854e01e1d63febc1df6b2e1f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::PHIAddIncoming::accept ()</td>
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

<p>This runs when changes get accepted.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

### dump() {#a71e36f06d168af310af38cbab4285003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::PHIAddIncoming::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

### dump() {#ac1d42c933976072a83a9a95416ce17ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PHIAddIncoming::dump ()</td>
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



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#ac1d42c933976072a83a9a95416ce17ae">dump</a>.</p>


<p>Referenced by <a href="#ac1d42c933976072a83a9a95416ce17ae">dump</a>.</p>

</div>
</div>

### revert() {#a844f1664a7830b5c507a88f0a1505ef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PHIAddIncoming::revert (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/tracker">Tracker</a> &amp; Tracker)</td>
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

<p>This runs when changes get reverted.</p>

<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/irchangebase/#a178a085e66872f6cbe6c33f101debdf5">llvm::sandboxir::IRChangeBase::Tracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Idx {#af174c2dbcfa84dc6e56c1866e19cf08c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::PHIAddIncoming::Idx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

### PHI {#addb79af930331fe0c3297afdb86f5619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode* llvm::sandboxir::PHIAddIncoming::PHI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
