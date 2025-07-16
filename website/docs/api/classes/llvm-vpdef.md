---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpdef
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VPDef` Class Reference

<p>This class augments a recipe with a set of VPValues defined by the recipe. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">Transforms/Vectorize/VPlanValue.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> is a base class modeling a sequence of one or more output IR instructions. <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada72f56c476318d4756920ecb66e056e">VPRecipeTy</a> = enum { VPBranchOnMaskSC, VPDerivedIVSC, VPExpandSCEVSC, VPIRInstructionSC, VPInstructionSC, VPInterleaveSC, VPReductionEVLSC, VPReductionSC, VPPartialReductionSC, VPReplicateSC, VPScalarCastSC, VPScalarIVStepsSC, VPVectorPointerSC, VPReverseVectorPointerSC, VPWidenCallSC, VPWidenCanonicalIVSC, VPWidenCastSC, VPWidenGEPSC, VPWidenIntrinsicSC, VPWidenLoadEVLSC, VPWidenLoadSC, VPWidenStoreEVLSC, VPWidenStoreSC, VPWidenSC, VPWidenEVLSC, VPWidenSelectSC, VPBlendSC, VPHistogramSC, VPWidenPHISC, VPPredInstPHISC, VPCanonicalIVPHISC, VPActiveLaneMaskPHISC, VPEVLBasedIVPHISC, VPFirstOrderRecurrencePHISC, VPWidenIntOrFpInductionSC, VPWidenPointerInductionSC, VPScalarPHISC, VPReductionPHISC, VPFirstPHISC=VPWidenPHISC, VPFirstHeaderPHISC=VPCanonicalIVPHISC, VPLastHeaderPHISC=VPReductionPHISC, VPLastPHISC=VPReductionPHISC, }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An enumeration for keeping track of the concrete subclass of <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> that is actually instantiated. <a href="#ada72f56c476318d4756920ecb66e056e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac865b61fa8f58dd0f6873b6fae365caa">VPValue</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5915b6b9efc4889c4ff4bfa01bf5903">VPDef</a> (const unsigned char SC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4718932c5ca6023cf203d75e6b7ce0">~VPDef</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76a983b694720483a3dd9fe57314e39b">getVPSingleValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the only <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> defined by the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>. <a href="#a76a983b694720483a3dd9fe57314e39b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8146636f2686f023d198d657e41c9848">getVPSingleValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9264a7c042631ed72c3bca345fc24003">getVPValue</a> (unsigned I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> with index <span class="doxyComputerOutput">I</span> defined by the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>. <a href="#a9264a7c042631ed72c3bca345fc24003">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af551518dc2fa0ba48b8247d9fbcdaaa6">getVPValue</a> (unsigned I) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b7aa8b207f721cee2e80ebd99682563">definedValues</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> of the values defined by the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>. <a href="#a5b7aa8b207f721cee2e80ebd99682563">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81fdb6975e0ded1645c1f87e0d2ebd99">definedValues</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> of the values defined by the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>. <a href="#a81fdb6975e0ded1645c1f87e0d2ebd99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31492b9d8412415c2dae85e33e2748fd">getNumDefinedValues</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of values defined by the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>. <a href="#a31492b9d8412415c2dae85e33e2748fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad537baa7adabb231da7e1b79a1e1696b">getVPDefID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223467b284dc610de3b6c21d0e03f111">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> to stderr (for debugging). <a href="#a223467b284dc610de3b6c21d0e03f111">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b32822f5bc7dc4a4ad6a4c4a3f3f12f">print</a> (raw_ostream &amp;O, const Twine &amp;Indent, VPSlotTracker &amp;SlotTracker) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Each concrete <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> prints itself. <a href="#a8b32822f5bc7dc4a4ad6a4c4a3f3f12f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cefbe6145d67430085605b90f8e0c92">addDefinedValue</a> (VPValue *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add <span class="doxyComputerOutput">V</span> as a defined value by this <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>. <a href="#a7cefbe6145d67430085605b90f8e0c92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2800ae3448b254bdfd5f24297142b002">removeDefinedValue</a> (VPValue *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove <span class="doxyComputerOutput">V</span> from the values defined by this <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>. <a href="#a2800ae3448b254bdfd5f24297142b002">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68aaffc1d77df5d4c9df09af1fef8af3">SubclassID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subclass identifier (for isa/dyn_cast). <a href="#a68aaffc1d77df5d4c9df09af1fef8af3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/tinyptrvector">TinyPtrVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b8ddaaa9f4239c363d8e03bd1b3e61b">DefinedValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The VPValues defined by this <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>. <a href="#a3b8ddaaa9f4239c363d8e03bd1b3e61b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class augments a recipe with a set of VPValues defined by the recipe.</p>


<p>It allows recipes to define zero, one or multiple VPValues. A <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> owns the VPValues it defines and is responsible for deleting its defined values. Single-value VPDefs that also inherit from <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> must make sure to inherit from <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> before <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>.</p>


<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### VPRecipeTy {#ada72f56c476318d4756920ecb66e056e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::VPDef::VPRecipeTy =  enum {
    VPBranchOnMaskSC,
    VPDerivedIVSC,
    VPExpandSCEVSC,
    VPIRInstructionSC,
    VPInstructionSC,
    VPInterleaveSC,
    VPReductionEVLSC,
    VPReductionSC,
    VPPartialReductionSC,
    VPReplicateSC,
    VPScalarCastSC,
    VPScalarIVStepsSC,
    VPVectorPointerSC,
    VPReverseVectorPointerSC,
    VPWidenCallSC,
    VPWidenCanonicalIVSC,
    VPWidenCastSC,
    VPWidenGEPSC,
    VPWidenIntrinsicSC,
    VPWidenLoadEVLSC,
    VPWidenLoadSC,
    VPWidenStoreEVLSC,
    VPWidenStoreSC,
    VPWidenSC,
    VPWidenEVLSC,
    VPWidenSelectSC,
    VPBlendSC,
    VPHistogramSC,
    
    VPWidenPHISC,
    VPPredInstPHISC,
    
    
    VPCanonicalIVPHISC,
    VPActiveLaneMaskPHISC,
    VPEVLBasedIVPHISC,
    VPFirstOrderRecurrencePHISC,
    VPWidenIntOrFpInductionSC,
    VPWidenPointerInductionSC,
    VPScalarPHISC,
    VPReductionPHISC,
    
    
    VPFirstPHISC = VPWidenPHISC,
    VPFirstHeaderPHISC = VPCanonicalIVPHISC,
    VPLastHeaderPHISC = VPReductionPHISC,
    VPLastPHISC = VPReductionPHISC,
  }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An enumeration for keeping track of the concrete subclass of <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> that is actually instantiated.</p>


<p>Values of this enumeration are kept in the SubclassID field of the <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> objects. They are used for concrete type identification.</p>


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### VPValue {#ac865b61fa8f58dd0f6873b6fae365caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#ac865b61fa8f58dd0f6873b6fae365caa">VPValue</a>.</p>


<p>Referenced by <a href="#a76a983b694720483a3dd9fe57314e39b">getVPSingleValue</a>, <a href="#a8146636f2686f023d198d657e41c9848">getVPSingleValue</a>, <a href="#a9264a7c042631ed72c3bca345fc24003">getVPValue</a>, <a href="#af551518dc2fa0ba48b8247d9fbcdaaa6">getVPValue</a>, <a href="#ac865b61fa8f58dd0f6873b6fae365caa">VPValue</a> and <a href="#a3f4718932c5ca6023cf203d75e6b7ce0">~VPDef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VPDef() {#ae5915b6b9efc4889c4ff4bfa01bf5903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPDef::VPDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC)</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a94599a3a939b7cf678cc58c8827c4d21">llvm::VPRecipeBase::classof</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VPDef() {#a3f4718932c5ca6023cf203d75e6b7ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::VPDef::~VPDef ()</td>
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



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a> and <a href="#ac865b61fa8f58dd0f6873b6fae365caa">VPValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### definedValues() {#a5b7aa8b207f721cee2e80ebd99682563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; VPValue * &gt; llvm::VPDef::definedValues ()</td>
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

<p>Returns an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> of the values defined by the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>.</p>

<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-vplanunroll-cpp-/unrollstate/#ab9d451e46e072fa57afbc34788c93f44">anonymous{VPlanUnroll.cpp}::UnrollState::addRecipeForPart</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aa70c8f392e8295a96bfd493337e122fa">collectUsersRecursively</a> and <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ab0d48fabf61af227821d568b1c3aa4ca">llvm::VPInterleaveRecipe::execute</a>.</p>

</div>
</div>

### definedValues() {#a81fdb6975e0ded1645c1f87e0d2ebd99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; VPValue * &gt; llvm::VPDef::definedValues ()</td>
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

<p>Returns an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> of the values defined by the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### dump() {#a223467b284dc610de3b6c21d0e03f111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPDef::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> to stderr (for debugging).</p>

<p>Declaration at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a8b32822f5bc7dc4a4ad6a4c4a3f3f12f">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#ac84a2bc6b484c5d3a03e80ce40f0a14c">llvm::VPRecipeBase::cost</a> and <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#aa998ed92e73ad469ff6c41d9d5093d0a">llvm::VPSingleDefRecipe::dump</a>.</p>

</div>
</div>

### getNumDefinedValues() {#a31492b9d8412415c2dae85e33e2748fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VPDef::getNumDefinedValues ()</td>
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

<p>Returns the number of values defined by the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>.</p>

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ad59bafaeacd51c2b1e6251488039d29a">llvm::VPInterleaveRecipe::computeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4a5b1db18197a65d0f6a487f2e236921">sinkRecurrenceUsersAfterPrevious</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad210afaefb4884ac5008dd5fbaf1cbf8">llvm::VPlanTransforms::VPInstructionsToVPRecipes</a>.</p>

</div>
</div>

### getVPDefID() {#ad537baa7adabb231da7e1b79a1e1696b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VPDef::getVPDefID ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the concrete type of this object. This is used to implement the classof checks. This should not be used for any other purpose, as the values may change as LLVM evolves.</p></dd>
</dl>


<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#af1fd3c4a51ec7fed4584ced33acc368d">llvm::VPRecipeBase::isPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a2408a88276528d80adefefa00995705a">llvm::VPRecipeBase::mayHaveSideEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a00bc7da040562d501bcc0e0635a2b53c">llvm::VPRecipeBase::mayReadFromMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a5fcebe7c77877e7f65c88e61c0fe1149">llvm::VPRecipeBase::mayWriteToMemory</a>.</p>

</div>
</div>

### getVPSingleValue() {#a76a983b694720483a3dd9fe57314e39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPDef::getVPSingleValue ()</td>
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

<p>Returns the only <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> defined by the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>.</p>


<p>Can only be called for VPDefs with a single defined value.</p>


<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac865b61fa8f58dd0f6873b6fae365caa">VPValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa88371693bc18186386b04e8c45a30e4">llvm::VPlanTransforms::createInterleaveGroups</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa0f143b8d4693978b984f0639c90e508">llvm::VPlanTransforms::dropPoisonGeneratingRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a6d8fbabf45554d7d598dc8eb4eca41cf">llvm::VPRecipeBuilder::fixHeaderPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a2408a88276528d80adefefa00995705a">llvm::VPRecipeBase::mayHaveSideEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a00bc7da040562d501bcc0e0635a2b53c">llvm::VPRecipeBase::mayReadFromMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a5fcebe7c77877e7f65c88e61c0fe1149">llvm::VPRecipeBase::mayWriteToMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4a5b1db18197a65d0f6a487f2e236921">sinkRecurrenceUsersAfterPrevious</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad210afaefb4884ac5008dd5fbaf1cbf8">llvm::VPlanTransforms::VPInstructionsToVPRecipes</a>.</p>

</div>
</div>

### getVPSingleValue() {#a8146636f2686f023d198d657e41c9848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPValue * llvm::VPDef::getVPSingleValue ()</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac865b61fa8f58dd0f6873b6fae365caa">VPValue</a>.</p>

</div>
</div>

### getVPValue() {#a9264a7c042631ed72c3bca345fc24003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPDef::getVPValue (unsigned I)</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> with index <span class="doxyComputerOutput">I</span> defined by the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>.</p>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ac865b61fa8f58dd0f6873b6fae365caa">VPValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-vplanunroll-cpp-/unrollstate/#ab9d451e46e072fa57afbc34788c93f44">anonymous{VPlanUnroll.cpp}::UnrollState::addRecipeForPart</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ad59bafaeacd51c2b1e6251488039d29a">llvm::VPInterleaveRecipe::computeCost</a> and <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#a942db1b770fa4cb70c66a2546d88cfb0">llvm::VPInterleaveRecipe::print</a>.</p>

</div>
</div>

### getVPValue() {#af551518dc2fa0ba48b8247d9fbcdaaa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPValue * llvm::VPDef::getVPValue (unsigned I)</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ac865b61fa8f58dd0f6873b6fae365caa">VPValue</a>.</p>

</div>
</div>

### print() {#a8b32822f5bc7dc4a4ad6a4c4a3f3f12f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::VPDef::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Each concrete <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> prints itself.</p>

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="#a223467b284dc610de3b6c21d0e03f111">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#abaf6ac959836f909c24a39b8913ec22f">llvm::VPBasicBlock::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addDefinedValue() {#a7cefbe6145d67430085605b90f8e0c92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPDef::addDefinedValue (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V)</td>
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

<p>Add <span class="doxyComputerOutput">V</span> as a defined value by this <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### removeDefinedValue() {#a2800ae3448b254bdfd5f24297142b002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPDef::removeDefinedValue (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V)</td>
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

<p>Remove <span class="doxyComputerOutput">V</span> from the values defined by this <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>.</p>


<p><span class="doxyComputerOutput">V</span> must be a defined value of this <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>.</p>


<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DefinedValues {#a3b8ddaaa9f4239c363d8e03bd1b3e61b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TinyPtrVector&lt;VPValue *&gt; llvm::VPDef::DefinedValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The VPValues defined by this <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a>.</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### SubclassID {#a68aaffc1d77df5d4c9df09af1fef8af3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char llvm::VPDef::SubclassID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subclass identifier (for isa/dyn_cast).</p>

<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
