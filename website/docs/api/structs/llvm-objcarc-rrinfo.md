---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/objcarc/rrinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RRInfo` Struct

<p>Unidirectional information about either a retain-decrement-use-release sequence or release-use-decrement-retain reverse sequence. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::objcarc::RRInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">Transforms/ObjCARC/PtrState.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aa0fa2f22bce7a65f1e861281edadfa">RRInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae219d35c9d1bb909cd32110815007c7f">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a090a8b4357ddca03d984584db3b6bc69">Merge</a> (const RRInfo &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Conservatively merge the two <a href="/web-llvm/docs/api/structs/llvm/objcarc/rrinfo">RRInfo</a>. <a href="#a090a8b4357ddca03d984584db3b6bc69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5770bc64392d64b9900226f925521b94">KnownSafe</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After an objc_retain, the reference count of the referenced object is known to be positive. <a href="#a5770bc64392d64b9900226f925521b94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9afa1dadab0e6367ce487573142be4e">IsTailCallRelease</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True of the objc_release calls are all marked with the "tail" keyword. <a href="#ac9afa1dadab0e6367ce487573142be4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab976ce410e551d37ce2f43177bb96995">ReleaseMetadata</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the Calls are objc_release calls and they all have a clang.imprecise_release tag, this is the metadata tag. <a href="#ab976ce410e551d37ce2f43177bb96995">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937b2f49aeebc9752e9ff219acbd93f0">Calls</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a top-down sequence, the set of objc_retains or objc_retainBlocks. <a href="#a937b2f49aeebc9752e9ff219acbd93f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed932d067cad4f2d928df9bee21af52a">ReverseInsertPts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of optimal insert positions for moving calls in the opposite sequence. <a href="#aed932d067cad4f2d928df9bee21af52a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac287dbb01fd38c21bbf0dafdbcfcb8cf">CFGHazardAfflicted</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is true, we cannot perform code motion but can still remove retain/release pairs. <a href="#ac287dbb01fd38c21bbf0dafdbcfcb8cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Unidirectional information about either a retain-decrement-use-release sequence or release-use-decrement-retain reverse sequence.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RRInfo() {#a4aa0fa2f22bce7a65f1e861281edadfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcarc::RRInfo::RRInfo ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a4aa0fa2f22bce7a65f1e861281edadfa">RRInfo</a>.</p>


<p>Referenced by <a href="#a090a8b4357ddca03d984584db3b6bc69">Merge</a> and <a href="#a4aa0fa2f22bce7a65f1e861281edadfa">RRInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#ae219d35c9d1bb909cd32110815007c7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RRInfo::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="#a937b2f49aeebc9752e9ff219acbd93f0">Calls</a>, <a href="#ac287dbb01fd38c21bbf0dafdbcfcb8cf">CFGHazardAfflicted</a>, <a href="#ac9afa1dadab0e6367ce487573142be4e">IsTailCallRelease</a>, <a href="#a5770bc64392d64b9900226f925521b94">KnownSafe</a>, <a href="#ab976ce410e551d37ce2f43177bb96995">ReleaseMetadata</a> and <a href="#aed932d067cad4f2d928df9bee21af52a">ReverseInsertPts</a>.</p>

</div>
</div>

### Merge() {#a090a8b4357ddca03d984584db3b6bc69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RRInfo::Merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcarc/rrinfo">RRInfo</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Conservatively merge the two <a href="/web-llvm/docs/api/structs/llvm/objcarc/rrinfo">RRInfo</a>.</p>


<p>Returns true if a partial merge has occurred, false otherwise.</p>


<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="#a937b2f49aeebc9752e9ff219acbd93f0">Calls</a>, <a href="#ac287dbb01fd38c21bbf0dafdbcfcb8cf">CFGHazardAfflicted</a>, <a href="#ac9afa1dadab0e6367ce487573142be4e">IsTailCallRelease</a>, <a href="#a5770bc64392d64b9900226f925521b94">KnownSafe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#ab976ce410e551d37ce2f43177bb96995">ReleaseMetadata</a>, <a href="#aed932d067cad4f2d928df9bee21af52a">ReverseInsertPts</a> and <a href="#a4aa0fa2f22bce7a65f1e861281edadfa">RRInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Calls {#a937b2f49aeebc9752e9ff219acbd93f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction *, 2&gt; llvm::objcarc::RRInfo::Calls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For a top-down sequence, the set of objc_retains or objc_retainBlocks.</p>


<p>For bottom-up, the set of objc_releases.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Referenced by <a href="#ae219d35c9d1bb909cd32110815007c7f">clear</a> and <a href="#a090a8b4357ddca03d984584db3b6bc69">Merge</a>.</p>

</div>
</div>

### CFGHazardAfflicted {#ac287dbb01fd38c21bbf0dafdbcfcb8cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::RRInfo::CFGHazardAfflicted = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is true, we cannot perform code motion but can still remove retain/release pairs.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Referenced by <a href="#ae219d35c9d1bb909cd32110815007c7f">clear</a> and <a href="#a090a8b4357ddca03d984584db3b6bc69">Merge</a>.</p>

</div>
</div>

### IsTailCallRelease {#ac9afa1dadab0e6367ce487573142be4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::RRInfo::IsTailCallRelease = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True of the objc_release calls are all marked with the "tail" keyword.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Referenced by <a href="#ae219d35c9d1bb909cd32110815007c7f">clear</a> and <a href="#a090a8b4357ddca03d984584db3b6bc69">Merge</a>.</p>

</div>
</div>

### KnownSafe {#a5770bc64392d64b9900226f925521b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::RRInfo::KnownSafe = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>After an objc_retain, the reference count of the referenced object is known to be positive.</p>


<p>Similarly, before an objc_release, the reference count of the referenced object is known to be positive. If there are retain-release pairs in code regions where the retain count is known to be positive, they can be eliminated, regardless of any side effects between them.</p>


<p>Also, a retain+release pair nested within another retain+release pair all on the known same pointer value can be eliminated, regardless of any intervening side effects.</p>


<p>KnownSafe is true when either of these conditions is satisfied.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Referenced by <a href="#ae219d35c9d1bb909cd32110815007c7f">clear</a> and <a href="#a090a8b4357ddca03d984584db3b6bc69">Merge</a>.</p>

</div>
</div>

### ReleaseMetadata {#ab976ce410e551d37ce2f43177bb96995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode* llvm::objcarc::RRInfo::ReleaseMetadata = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the Calls are objc_release calls and they all have a clang.imprecise_release tag, this is the metadata tag.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Referenced by <a href="#ae219d35c9d1bb909cd32110815007c7f">clear</a> and <a href="#a090a8b4357ddca03d984584db3b6bc69">Merge</a>.</p>

</div>
</div>

### ReverseInsertPts {#aed932d067cad4f2d928df9bee21af52a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction *, 2&gt; llvm::objcarc::RRInfo::ReverseInsertPts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of optimal insert positions for moving calls in the opposite sequence.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Referenced by <a href="#ae219d35c9d1bb909cd32110815007c7f">clear</a> and <a href="#a090a8b4357ddca03d984584db3b6bc69">Merge</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
