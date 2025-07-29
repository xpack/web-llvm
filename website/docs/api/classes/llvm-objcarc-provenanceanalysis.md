---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcarc/provenanceanalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ProvenanceAnalysis` Class

<p>This is similar to BasicAliasAnalysis, and it uses many of the same techniques, except it uses special ObjC-specific reasoning about pointer relationships. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::objcarc::ProvenanceAnalysis { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">Transforms/ObjCARC/ProvenanceAnalysis.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a616a55f88aacbb023f73238174fcd1c8">ValuePairTy</a> = std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1512369e587b4331d88fff3f4f7b8b9c">CachedResultsTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; ValuePairTy, bool &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcdae3be2fa8bb4f06d699064fbd8011">ProvenanceAnalysis</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adafa7ed2458c9594c1a36671b18b6dee">ProvenanceAnalysis</a> (const ProvenanceAnalysis &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcarc/provenanceanalysis">ProvenanceAnalysis</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8703fd414233c0f4cf1118e7da6644f7">operator=</a> (const ProvenanceAnalysis &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746f7f7833928dfd2e5dec71aad6d240">setAA</a> (AAResults *aa)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a186a005768089d004c0048c6efb6ed63">getAA</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd2cebbb0c91816f3af00f1014dd172">related</a> (const Value *A, const Value *B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1e7c0f132f5c996af8278d0779e3295">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae148766368045247e287034f187a4989">relatedCheck</a> (const Value *A, const Value *B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d05adc0b59cc54112756e4e7bd70454">relatedSelect</a> (const SelectInst *A, const Value *B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d664fe955dda8b96b77eb54fa003e6b">relatedPHI</a> (const PHINode *A, const Value *B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9adc3fe1633b78ac87e2df27798aa9a4">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">CachedResultsTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d75c2d6871188b6fe6a8e2fff16084e">CachedResults</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a>, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27dea9e4198a1ecc2933690a2a0cd609">UnderlyingObjCPtrCache</a></td>
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

<p>This is similar to BasicAliasAnalysis, and it uses many of the same techniques, except it uses special ObjC-specific reasoning about pointer relationships.</p>


<p>In this context “Provenance” is defined as the history of an object's ownership. Thus “Provenance Analysis” is defined by using the notion of an “independent provenance source” of a pointer to determine whether or not two pointers have the same provenance source and thus could potentially be related.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### CachedResultsTy {#a1512369e587b4331d88fff3f4f7b8b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::objcarc::ProvenanceAnalysis::CachedResultsTy =  DenseMap&lt;ValuePairTy, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>

</div>
</div>

### ValuePairTy {#a616a55f88aacbb023f73238174fcd1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::objcarc::ProvenanceAnalysis::ValuePairTy =  std::pair&lt;const Value *, const Value *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ProvenanceAnalysis() {#afcdae3be2fa8bb4f06d699064fbd8011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcarc::ProvenanceAnalysis::ProvenanceAnalysis ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>


<p>Referenced by <a href="#a8703fd414233c0f4cf1118e7da6644f7">operator=</a> and <a href="#adafa7ed2458c9594c1a36671b18b6dee">ProvenanceAnalysis</a>.</p>

</div>
</div>

### ProvenanceAnalysis() {#adafa7ed2458c9594c1a36671b18b6dee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcarc::ProvenanceAnalysis::ProvenanceAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcarc/provenanceanalysis">ProvenanceAnalysis</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>


<p>Reference <a href="#afcdae3be2fa8bb4f06d699064fbd8011">ProvenanceAnalysis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a8703fd414233c0f4cf1118e7da6644f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProvenanceAnalysis &amp; llvm::objcarc::ProvenanceAnalysis::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcarc/provenanceanalysis">ProvenanceAnalysis</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>


<p>Reference <a href="#afcdae3be2fa8bb4f06d699064fbd8011">ProvenanceAnalysis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#ac1e7c0f132f5c996af8278d0779e3295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::ProvenanceAnalysis::clear ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>

</div>
</div>

### getAA() {#a186a005768089d004c0048c6efb6ed63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults * llvm::objcarc::ProvenanceAnalysis::getAA ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a1b3a1bca1f908fbc09a8c4cb5df7e155">llvm::objcarc::CanAlterRefCount</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#af467748c4e634ace0c19cbbeb0af5fee">llvm::objcarc::CanUse</a>.</p>

</div>
</div>

### related() {#a0cd2cebbb0c91816f3af00f1014dd172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProvenanceAnalysis::related (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-cpp">ProvenanceAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a890cd42b6738df7f1159aa2d61f22876">llvm::objcarc::GetUnderlyingObjCPtrCached</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a1b3a1bca1f908fbc09a8c4cb5df7e155">llvm::objcarc::CanAlterRefCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#af467748c4e634ace0c19cbbeb0af5fee">llvm::objcarc::CanUse</a> and <a href="/web-llvm/docs/api/structs/llvm/paevalpass/#a7f0dda30879f62ea4eefdc53cfbb0e1d">llvm::PAEvalPass::run</a>.</p>

</div>
</div>

### setAA() {#a746f7f7833928dfd2e5dec71aad6d240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::ProvenanceAnalysis::setAA (<a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * aa)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a74b87337454200d4d33f80c4663dc5e5">aa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/paevalpass/#a7f0dda30879f62ea4eefdc53cfbb0e1d">llvm::PAEvalPass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### relatedCheck() {#ae148766368045247e287034f187a4989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProvenanceAnalysis::relatedCheck (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-cpp">ProvenanceAnalysis.cpp</a>.</p>

</div>
</div>

### relatedPHI() {#a3d664fe955dda8b96b77eb54fa003e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProvenanceAnalysis::relatedPHI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-cpp">ProvenanceAnalysis.cpp</a>.</p>

</div>
</div>

### relatedSelect() {#a7d05adc0b59cc54112756e4e7bd70454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProvenanceAnalysis::relatedSelect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-cpp">ProvenanceAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a9adc3fe1633b78ac87e2df27798aa9a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults* llvm::objcarc::ProvenanceAnalysis::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>

</div>
</div>

### CachedResults {#a7d75c2d6871188b6fe6a8e2fff16084e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CachedResultsTy llvm::objcarc::ProvenanceAnalysis::CachedResults</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>

</div>
</div>

### UnderlyingObjCPtrCache {#a27dea9e4198a1ecc2933690a2a0cd609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, std::pair&lt;WeakVH, WeakTrackingVH&gt; &gt; llvm::objcarc::ProvenanceAnalysis::UnderlyingObjCPtrCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-cpp">ProvenanceAnalysis.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
