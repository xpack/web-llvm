---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/metadatatracking
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MetadataTracking` Class Reference

<p>API for tracking metadata references through RAUW and deletion. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MetadataTracking { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787e65b587425fda0bdb4b76e5b30c80">OwnerTy</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue">MetadataAsValue</a> *, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> * &gt;</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d18d3d41665a4f2747c2da7195055a">track</a> (Metadata *&amp;MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track the reference to metadata. <a href="#ac8d18d3d41665a4f2747c2da7195055a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad35867ebcbacce31990adc61d7679f9a">track</a> (void *Ref, Metadata &amp;MD, Metadata &amp;Owner)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track the reference to metadata for <em><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a></em>. <a href="#ad35867ebcbacce31990adc61d7679f9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b3749460eb0b75055842f745a7c8b87">track</a> (void *Ref, Metadata &amp;MD, MetadataAsValue &amp;Owner)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track the reference to metadata for <em><a href="/web-llvm/docs/api/classes/llvm/metadataasvalue">MetadataAsValue</a></em>. <a href="#a4b3749460eb0b75055842f745a7c8b87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcdc1faf8d730966a4ec843139193442">track</a> (void *Ref, Metadata &amp;MD, DebugValueUser &amp;Owner)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track the reference to metadata for <em><a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a></em>. <a href="#adcdc1faf8d730966a4ec843139193442">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7349c5af03206b0b24d096f5c50378af">untrack</a> (Metadata *&amp;MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stop tracking a reference to metadata. <a href="#a7349c5af03206b0b24d096f5c50378af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7da9d2f2d53d9197acf5abc73d7aeb0">untrack</a> (void *Ref, Metadata &amp;MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80df62c7fe69bd81d3f2ecd843d0db92">retrack</a> (Metadata *&amp;MD, Metadata *&amp;New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move tracking from one reference to another. <a href="#a80df62c7fe69bd81d3f2ecd843d0db92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168c95e63d349b2b34821da321f20bb8">retrack</a> (void *Ref, Metadata &amp;MD, void *New)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45da08f68cfc27dc2e0dfc6b0057e1c3">isReplaceable</a> (const Metadata &amp;MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether metadata is replaceable. <a href="#a45da08f68cfc27dc2e0dfc6b0057e1c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a365a07044167fa48859867477a4ad87b">track</a> (void *Ref, Metadata &amp;MD, OwnerTy Owner)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track a reference to metadata for an owner. <a href="#a365a07044167fa48859867477a4ad87b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>API for tracking metadata references through RAUW and deletion.</p>


<p>Shared API for updating <em><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a></em> pointers in subclasses that support RAUW.</p>


<p>This API is not meant to be used directly. See <em><a href="/web-llvm/docs/api/classes/llvm/trackingmdref">TrackingMDRef</a></em> for a user-friendly tracking reference.</p>


<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### OwnerTy {#a787e65b587425fda0bdb4b76e5b30c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MetadataTracking::OwnerTy =  PointerUnion&lt;MetadataAsValue *, Metadata *, DebugValueUser *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isReplaceable() {#a45da08f68cfc27dc2e0dfc6b0057e1c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MetadataTracking::isReplaceable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> &amp; MD)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether metadata is replaceable.</p>

<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/trackingmdref/#a59859360e877cbf0ccccbe17ecd22550">llvm::TrackingMDRef::hasTrivialDestructor</a> and <a href="#a168c95e63d349b2b34821da321f20bb8">retrack</a>.</p>

</div>
</div>

### retrack() {#a80df62c7fe69bd81d3f2ecd843d0db92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataTracking::retrack (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *&amp; MD, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *&amp; New)</td>
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

<p>Move tracking from one reference to another.</p>


<p>Semantically equivalent to <span class="doxyComputerOutput">untrack(MD)</span> followed by <span class="doxyComputerOutput">track(New)</span>, except that ownership callbacks are maintained.</p>


<p>Note: it is an error if <span class="doxyComputerOutput">*MD</span> does not equal <span class="doxyComputerOutput">New</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true iff tracking is supported by <span class="doxyComputerOutput">MD</span>.</p></dd>
</dl>


<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#a80df62c7fe69bd81d3f2ecd843d0db92">retrack</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mdoperand/#afde78da28dc070b13a2455058584670e">llvm::MDOperand::MDOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mdoperand/#aea2949b73771a88ea757dbc287c56eb0">llvm::MDOperand::operator=</a> and <a href="#a80df62c7fe69bd81d3f2ecd843d0db92">retrack</a>.</p>

</div>
</div>

### retrack() {#a168c95e63d349b2b34821da321f20bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MetadataTracking::retrack (void * Ref, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> &amp; MD, void * New)</td>
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



<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a45da08f68cfc27dc2e0dfc6b0057e1c3">isReplaceable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### track() {#ac8d18d3d41665a4f2747c2da7195055a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataTracking::track (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *&amp; MD)</td>
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

<p>Track the reference to metadata.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> <span class="doxyComputerOutput">MD</span> with <span class="doxyComputerOutput">*MD</span>, if the subclass supports tracking. If <span class="doxyComputerOutput">*MD</span> gets RAUW'ed, <span class="doxyComputerOutput">MD</span> will be updated to the new address. If <span class="doxyComputerOutput">*MD</span> gets deleted, <span class="doxyComputerOutput">MD</span> will be set to <span class="doxyComputerOutput">nullptr</span>.</p>


<p>If tracking isn't supported, <span class="doxyComputerOutput">*MD</span> will not change.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true iff tracking is supported by <span class="doxyComputerOutput">MD</span>.</p></dd>
</dl>


<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#ac8d18d3d41665a4f2747c2da7195055a">track</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl/#a2b9c0ec6595f7f4b7d737415a8cb0aaf">llvm::ReplaceableMetadataImpl::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/distinctmdoperandplaceholder/#a00aa234931f09b9795007fe1cf69d7fc">llvm::DistinctMDOperandPlaceholder::replaceUseWith</a>, <a href="#ac8d18d3d41665a4f2747c2da7195055a">track</a>, <a href="#adcdc1faf8d730966a4ec843139193442">track</a>, <a href="#ad35867ebcbacce31990adc61d7679f9a">track</a> and <a href="#a4b3749460eb0b75055842f745a7c8b87">track</a>.</p>

</div>
</div>

### track() {#ad35867ebcbacce31990adc61d7679f9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataTracking::track (void * Ref, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> &amp; MD, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> &amp; Owner)</td>
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

<p>Track the reference to metadata for <em><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a></em>.</p>


<p>As <em><a href="#ac8d18d3d41665a4f2747c2da7195055a">track(Metadata*&amp;)</a></em>, but with support for calling back to <span class="doxyComputerOutput">Owner</span> to tell it that its operand changed. This could trigger <span class="doxyComputerOutput">Owner</span> being re-uniqued.</p>


<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="#ac8d18d3d41665a4f2747c2da7195055a">track</a>.</p>

</div>
</div>

### track() {#a4b3749460eb0b75055842f745a7c8b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataTracking::track (void * Ref, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> &amp; MD, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue">MetadataAsValue</a> &amp; Owner)</td>
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

<p>Track the reference to metadata for <em><a href="/web-llvm/docs/api/classes/llvm/metadataasvalue">MetadataAsValue</a></em>.</p>


<p>As <em><a href="#ac8d18d3d41665a4f2747c2da7195055a">track(Metadata*&amp;)</a></em>, but with support for calling back to <span class="doxyComputerOutput">Owner</span> to tell it that its operand changed. This could trigger <span class="doxyComputerOutput">Owner</span> being re-uniqued.</p>


<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="#ac8d18d3d41665a4f2747c2da7195055a">track</a>.</p>

</div>
</div>

### track() {#adcdc1faf8d730966a4ec843139193442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataTracking::track (void * Ref, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> &amp; MD, <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> &amp; Owner)</td>
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

<p>Track the reference to metadata for <em><a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a></em>.</p>


<p>As <em><a href="#ac8d18d3d41665a4f2747c2da7195055a">track(Metadata*&amp;)</a></em>, but with support for calling back to <span class="doxyComputerOutput">Owner</span> to tell it that its operand changed. This could trigger <span class="doxyComputerOutput">Owner</span> being re-uniqued.</p>


<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="#ac8d18d3d41665a4f2747c2da7195055a">track</a>.</p>

</div>
</div>

### untrack() {#a7349c5af03206b0b24d096f5c50378af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataTracking::untrack (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *&amp; MD)</td>
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

<p>Stop tracking a reference to metadata.</p>


<p>Stops <span class="doxyComputerOutput">*MD</span> from tracking <span class="doxyComputerOutput">MD</span>.</p>


<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#a7349c5af03206b0b24d096f5c50378af">untrack</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/distinctmdoperandplaceholder/#a00aa234931f09b9795007fe1cf69d7fc">llvm::DistinctMDOperandPlaceholder::replaceUseWith</a> and <a href="#a7349c5af03206b0b24d096f5c50378af">untrack</a>.</p>

</div>
</div>

### untrack() {#ac7da9d2f2d53d9197acf5abc73d7aeb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MetadataTracking::untrack (void * Ref, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> &amp; MD)</td>
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



<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### track() {#a365a07044167fa48859867477a4ad87b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MetadataTracking::track (void * Ref, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> &amp; MD, <a href="#a787e65b587425fda0bdb4b76e5b30c80">OwnerTy</a> Owner)</td>
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

<p>Track a reference to metadata for an owner.</p>


<p>Generalized version of tracking.</p>


<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
