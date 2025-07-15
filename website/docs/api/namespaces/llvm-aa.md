---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/aa
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `AA` Namespace Reference

<p>Abstract <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> helper functions. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::AA { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/aa/pointerinfo">PointerInfo</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to represent an access offset and size, with logic to deal with uncertainty and check for overlapping accesses. <a href="/web-llvm/docs/api/structs/llvm/aa/rangety/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aa/valueandcontext">ValueAndContext</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7dc88f593d600ddcfe97fcbd6f15e43">InstExclusionSetTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">GPUAddressSpace : unsigned { <a href="#a0ab72bc360a96141393d6ff9f1af7511">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ValueScope : uint8_t { <a href="#ac85851126814105f4a92b699293e4141">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags to distinguish intra-procedural queries from <em>potentially</em> inter-procedural queries. <a href="#ac85851126814105f4a92b699293e4141">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d9e6f3d4b50c7d8624851ed2ad7ff33">operator&lt;&lt;</a> (raw_ostream &amp;OS, const RangeTy &amp;R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac63dc1dd71c9173b497a2193dcc3f70c">operator==</a> (const RangeTy &amp;A, const RangeTy &amp;B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f26e9da49fb529ebe03e31ba81d1ef8">operator!=</a> (const RangeTy &amp;A, const RangeTy &amp;B)</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7baf8e2e8dff3bb7152c6ffeb52fb8">isGPU</a> (const Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true iff <span class="doxyComputerOutput">M</span> target a GPU (and we can use GPU AS reasoning). <a href="#aba7baf8e2e8dff3bb7152c6ffeb52fb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add4df090e923f2fe0dceeb0c60e5f74b">isNoSyncInst</a> (Attributor &amp;A, const Instruction &amp;I, const AbstractAttribute &amp;QueryingAA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">I</span> is a <span class="doxyComputerOutput">nosync</span> instruction. <a href="#add4df090e923f2fe0dceeb0c60e5f74b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a559168f78e20f2d3d0e1763ee6e751ef">isDynamicallyUnique</a> (Attributor &amp;A, const AbstractAttribute &amp;QueryingAA, const Value &amp;V, bool ForAnalysisOnly=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">V</span> is dynamically unique, that is, there are no two "instances" of <span class="doxyComputerOutput">V</span> at runtime with different values. <a href="#a559168f78e20f2d3d0e1763ee6e751ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7be59b8a3d5e2faf55b21c42ed07a63">isValidInScope</a> (const Value &amp;V, const Function *Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">V</span> is a valid value in <span class="doxyComputerOutput">Scope</span>, that is a constant or an instruction/argument of <span class="doxyComputerOutput">Scope</span>. <a href="#ad7be59b8a3d5e2faf55b21c42ed07a63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec1a38ef077070bf9d3760ddbbcfe24">isValidAtPosition</a> (const ValueAndContext &amp;VAC, InformationCache &amp;InfoCache)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the value of <span class="doxyComputerOutput">VAC</span> is a valid at the position of <span class="doxyComputerOutput">VAC</span>, that is a constant, an argument of the same function, or an instruction in that function that dominates the position. <a href="#a1ec1a38ef077070bf9d3760ddbbcfe24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af967a81762eaaf67f292abee4a00180c">getWithType</a> (Value &amp;V, Type &amp;Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to convert <span class="doxyComputerOutput">V</span> to type <span class="doxyComputerOutput">Ty</span> without introducing new instructions. <a href="#af967a81762eaaf67f292abee4a00180c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e7aede47c97d1e610eeb8bdf152f4cc">combineOptionalValuesInAAValueLatice</a> (const std::optional&lt; Value * &gt; &amp;A, const std::optional&lt; Value * &gt; &amp;B, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the combination of <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> such that the result is a possible value of both. <a href="#a1e7aede47c97d1e610eeb8bdf152f4cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdc024165477822f664fda55551f8a66">getInitialValueForObj</a> (Attributor &amp;A, const AbstractAttribute &amp;QueryingAA, Value &amp;Obj, Type &amp;Ty, const TargetLibraryInfo *TLI, const DataLayout &amp;DL, RangeTy *RangePtr=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the initial value of <span class="doxyComputerOutput">Obj</span> with type <span class="doxyComputerOutput">Ty</span> if that is a constant. <a href="#abdc024165477822f664fda55551f8a66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af30179a08c576d56d2469f5373174c43">getPotentiallyLoadedValues</a> (Attributor &amp;A, LoadInst &amp;LI, SmallSetVector&lt; Value *, 4 &gt; &amp;PotentialValues, SmallSetVector&lt; Instruction *, 4 &gt; &amp;PotentialValueOrigins, const AbstractAttribute &amp;QueryingAA, bool &amp;UsedAssumedInformation, bool OnlyExact=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all potential values <span class="doxyComputerOutput">LI</span> could read into <span class="doxyComputerOutput">PotentialValues</span>. <a href="#af30179a08c576d56d2469f5373174c43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5901858977a1ad4f47eb76f8491fadd8">getPotentialCopiesOfStoredValue</a> (Attributor &amp;A, StoreInst &amp;SI, SmallSetVector&lt; Value *, 4 &gt; &amp;PotentialCopies, const AbstractAttribute &amp;QueryingAA, bool &amp;UsedAssumedInformation, bool OnlyExact=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all potential values of the one stored by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span> into <span class="doxyComputerOutput">PotentialCopies</span>. <a href="#a5901858977a1ad4f47eb76f8491fadd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d95a36815f9b2bb3441fd61ee328be">isAssumedReadOnly</a> (Attributor &amp;A, const IRPosition &amp;IRP, const AbstractAttribute &amp;QueryingAA, bool &amp;IsKnown)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">IRP</span> is readonly. <a href="#a17d95a36815f9b2bb3441fd61ee328be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1496d1d7b408ea24a3c4d3c6d9a2d08c">isAssumedReadNone</a> (Attributor &amp;A, const IRPosition &amp;IRP, const AbstractAttribute &amp;QueryingAA, bool &amp;IsKnown)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">IRP</span> is readnone. <a href="#a1496d1d7b408ea24a3c4d3c6d9a2d08c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc52b79e64dcac96ea901cbfab1ccc52">isPotentiallyReachable</a> (Attributor &amp;A, const Instruction &amp;FromI, const Instruction &amp;ToI, const AbstractAttribute &amp;QueryingAA, const AA::InstExclusionSetTy *ExclusionSet=nullptr, std::function&lt; bool(const Function &amp;F)&gt; GoBackwardsCB=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">ToI</span> is potentially reachable from <span class="doxyComputerOutput">FromI</span> without running into any instruction in <span class="doxyComputerOutput">ExclusionSet</span> The two instructions do not need to be in the same function. <a href="#adc52b79e64dcac96ea901cbfab1ccc52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18d541007c596beba0b31031ce056669">isPotentiallyReachable</a> (Attributor &amp;A, const Instruction &amp;FromI, const Function &amp;ToFn, const AbstractAttribute &amp;QueryingAA, const AA::InstExclusionSetTy *ExclusionSet=nullptr, std::function&lt; bool(const Function &amp;F)&gt; GoBackwardsCB=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as above but it is sufficient to reach any instruction in <span class="doxyComputerOutput">ToFn</span>. <a href="#a18d541007c596beba0b31031ce056669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f2a3f39b7febd40285065a7ed05b71d">isAssumedThreadLocalObject</a> (Attributor &amp;A, Value &amp;Obj, const AbstractAttribute &amp;QueryingAA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">Obj</span> is assumed to be a thread local object. <a href="#a1f2a3f39b7febd40285065a7ed05b71d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b9d4b530f90e36eede3c575ad1948ee">isPotentiallyAffectedByBarrier</a> (Attributor &amp;A, const Instruction &amp;I, const AbstractAttribute &amp;QueryingAA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">I</span> is potentially affected by a barrier. <a href="#a9b9d4b530f90e36eede3c575ad1948ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2517066083f5a59ca08c9724f8e727db">isPotentiallyAffectedByBarrier</a> (Attributor &amp;A, ArrayRef&lt; const Value * &gt; Ptrs, const AbstractAttribute &amp;QueryingAA, const Instruction *CtxI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;Attribute::AttrKind AK, typename AAType = AbstractAttribute&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae8abeaeed2f11072b2d064fe70510e9f">hasAssumedIRAttr</a> (Attributor &amp;A, const AbstractAttribute *QueryingAA, const IRPosition &amp;IRP, DepClassTy DepClass, bool &amp;IsKnown, bool IgnoreSubsumingPositions=false, const AAType **AAPtr=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to avoid creating an <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> for IR Attributes that might already be set. <a href="#ae8abeaeed2f11072b2d064fe70510e9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Abstract <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> helper functions.</p>

<div class="doxySectionDef">

## Typedefs

### InstExclusionSetTy {#ab7dc88f593d600ddcfe97fcbd6f15e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AA::InstExclusionSetTy =  SmallPtrSet&lt;Instruction *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### GPUAddressSpace {#a0ab72bc360a96141393d6ff9f1af7511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::AA::GPUAddressSpace : unsigned</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Generic<a id="a0ab72bc360a96141393d6ff9f1af7511a8045a0a6c688b0635e3caccc408a1446"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Global<a id="a0ab72bc360a96141393d6ff9f1af7511a4cc6684df7b4a92b1dec6fce3264fac8"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Shared<a id="a0ab72bc360a96141393d6ff9f1af7511aa6156ea9d66fef24e87e841fbabf7cca"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Constant<a id="a0ab72bc360a96141393d6ff9f1af7511acb17869fe51048b5a5c4c6106551a255"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Local<a id="a0ab72bc360a96141393d6ff9f1af7511a509820290d57f333403f490dde7316f4"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### ValueScope {#ac85851126814105f4a92b699293e4141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AA::ValueScope : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags to distinguish intra-procedural queries from <em>potentially</em> inter-procedural queries.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Intraprocedural<a id="ac85851126814105f4a92b699293e4141a5c330ebe62fe7984f41ec28c822a869a"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Interprocedural<a id="ac85851126814105f4a92b699293e4141ab563ef74be13fcdcf264798ed6af5666"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AnyScope<a id="ac85851126814105f4a92b699293e4141aab418ed12d74fcdd3d6976b470bd2e66"></a></td>
<td class="doxyEnumItemDescription"> (= Intraprocedural | Interprocedural)</td>
</tr>

</table>
</dd>
</dl>


<p>Not that information can be valid for both and therefore both bits might be set.</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Operators

### operator!=() {#a5f26e9da49fb529ebe03e31ba81d1ef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a> &amp; B)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a1d9e6f3d4b50c7d8624851ed2ad7ff33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::AA::operator&lt;&lt; (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a> &amp; R)</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### operator==() {#ac63dc1dd71c9173b497a2193dcc3f70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a> &amp; B)</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### combineOptionalValuesInAAValueLatice() {#a1e7aede47c97d1e610eeb8bdf152f4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; llvm::AA::combineOptionalValuesInAAValueLatice (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; B, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the combination of <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> such that the result is a possible value of both.</p>


<p><span class="doxyComputerOutput">B</span> is potentially casted to match the type <span class="doxyComputerOutput">Ty</span> or the type of <span class="doxyComputerOutput">A</span> if <span class="doxyComputerOutput">Ty</span> is null.</p>


<p>Examples: X + none =&gt; X not_none + undef =&gt; not_none V1 + V2 =&gt; nullptr</p>


<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#af967a81762eaaf67f292abee4a00180c">getWithType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#afbaf43cc6d56847d8f8202623b7f61e7">llvm::AAPotentialValues::getSingleValue</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#add3479adcfa3517e4017ace8e9ac9b2a">llvm::AAPointerInfo::Access::operator&amp;=</a> and <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#a3b30794202b9b3042b5567a270ea8735">llvm::ValueSimplifyStateType::unionAssumed</a>.</p>

</div>
</div>

### getInitialValueForObj() {#abdc024165477822f664fda55551f8a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::AA::getInitialValueForObj (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> &amp; Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a> * RangePtr=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the initial value of <span class="doxyComputerOutput">Obj</span> with type <span class="doxyComputerOutput">Ty</span> if that is a constant.</p>

<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a0ab72bc360a96141393d6ff9f1af7511acb17869fe51048b5a5c4c6106551a255">Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f2a6934eba2671f2fe2a121f2e9e4e9">llvm::ConstantFoldLoadFromConst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a65bb0005c2f40b94623bae2e9a51fe48">llvm::ConstantFoldLoadFromUniformValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a108b6e33f153eda5019d322f0ac909b0">llvm::getInitialValueOfAllocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/aa/rangety/#ad8b6601a2aaaa9968df053e679f85f58">llvm::AA::RangeTy::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/structs/llvm/aa/rangety/#a5182e1587d800f1eb2ca55e0a260ad2d">llvm::AA::RangeTy::offsetOrSizeAreUnknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a605fed3c698bbafcf2d81aa2a1b191af">getPotentialCopiesOfMemoryValue</a>.</p>

</div>
</div>

### getPotentialCopiesOfStoredValue() {#a5901858977a1ad4f47eb76f8491fadd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::getPotentialCopiesOfStoredValue (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> &amp; SI, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt; &amp; PotentialCopies, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, bool &amp; UsedAssumedInformation, bool OnlyExact=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect all potential values of the one stored by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span> into <span class="doxyComputerOutput">PotentialCopies</span>.</p>


<p>That is, the only copies that were made via the store are assumed to be known and all are in <span class="doxyComputerOutput">PotentialCopies</span>. Dependences onto <span class="doxyComputerOutput">QueryingAA</span> are properly tracked, <span class="doxyComputerOutput">UsedAssumedInformation</span> will inform the caller if assumed information was used.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the assumed potential copies are all in <span class="doxyComputerOutput">PotentialCopies</span>, false if something went wrong and the copies could not be determined.</p></dd>
</dl>


<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a605fed3c698bbafcf2d81aa2a1b191af">getPotentialCopiesOfMemoryValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#abbea65eed8b9b7cd07f0b8eef53df6f5">llvm::Attributor::checkForAllUses</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a2a4744a0553a69a758f119c04c303ae5">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::isDeadStore</a>.</p>

</div>
</div>

### getPotentiallyLoadedValues() {#af30179a08c576d56d2469f5373174c43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::getPotentiallyLoadedValues (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt; &amp; PotentialValues, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; &amp; PotentialValueOrigins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, bool &amp; UsedAssumedInformation, bool OnlyExact=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect all potential values <span class="doxyComputerOutput">LI</span> could read into <span class="doxyComputerOutput">PotentialValues</span>.</p>


<p>That is, the only values read by <span class="doxyComputerOutput">LI</span> are assumed to be known and all are in <span class="doxyComputerOutput">PotentialValues</span>. <span class="doxyComputerOutput">PotentialValueOrigins</span> will contain all the instructions that might have put a potential value into <span class="doxyComputerOutput">PotentialValues</span>. Dependences onto <span class="doxyComputerOutput">QueryingAA</span> are properly tracked, <span class="doxyComputerOutput">UsedAssumedInformation</span> will inform the caller if assumed information was used.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the assumed potential copies are all in <span class="doxyComputerOutput">PotentialValues</span>, false if something went wrong and the copies could not be determined.</p></dd>
</dl>


<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a605fed3c698bbafcf2d81aa2a1b191af">getPotentialCopiesOfMemoryValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a4366c809736e919b276b5cda925d17ac">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleLoadInst</a>.</p>

</div>
</div>

### getWithType() {#af967a81762eaaf67f292abee4a00180c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::AA::getWithType (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> &amp; Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to convert <span class="doxyComputerOutput">V</span> to type <span class="doxyComputerOutput">Ty</span> without introducing new instructions.</p>


<p>If this is not possible return <span class="doxyComputerOutput">nullptr</span>. Note: this function basically knows how to cast various constants.</p>


<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a1f469b1f703519ae25ce564c8704310f">llvm::ConstantExpr::getPointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af238147cf5453729781a0fcc7322e1c6">llvm::ConstantExpr::getTrunc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a98e912ad4f52dcd78856d78ad4c06338">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::askOtherAA</a>, <a href="#a1e7aede47c97d1e610eeb8bdf152f4cc">combineOptionalValuesInAAValueLatice</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a63540fe3243b44a62cb656c73274f8ac">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::ensureType</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ae86be98f39008a27ba987e282fc8dc2c">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::genericValueTraversal</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialconstantvalues/#ac6c45f02f71621808dd33da72d73cb00">llvm::AAPotentialConstantValues::getAssumedConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#a1e99011cd6c37ad4ab5be287c94735bf">llvm::AAValueConstantRange::getAssumedConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a605fed3c698bbafcf2d81aa2a1b191af">getPotentialCopiesOfMemoryValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a3b776824b1ee93e75dcf982fec706900">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>.</p>

</div>
</div>

### hasAssumedIRAttr() {#ae8abeaeed2f11072b2d064fe70510e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;Attribute::AttrKind AK, typename AAType = AbstractAttribute&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::hasAssumedIRAttr (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> * QueryingAA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1">DepClassTy</a> DepClass, bool &amp; IsKnown, bool IgnoreSubsumingPositions=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AAType ** AAPtr=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to avoid creating an <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> for IR Attributes that might already be set.</p>

<p>Definition at line 6493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h/#a5e95d69905ced069fbb692d4358001ee">CASE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a79d67102092193edc6d431f35cdb072da99fd7a59be55148bc3363d90453cc368">llvm::AAMemoryBehavior::NO_ACCESSES</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a79d67102092193edc6d431f35cdb072da968857ad600f95aa7d356e09c065c64f">llvm::AAMemoryBehavior::NO_READS</a> and <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a79d67102092193edc6d431f35cdb072da855b6c4a37d05f98826cad5d6c26cb14">llvm::AAMemoryBehavior::NO_WRITES</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a6982073fb3620dd727922e78e140af8f">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizePtrValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a9e78a16876b18d86097c67afa39bc090">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::checkUse</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a1bdef12f6088e0d320946736b48fb137">anonymous{AttributorAttributes.cpp}::clampCallSiteArgumentStates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a3c38e0e568db780d1a47a0b2ce3991f7">clampReturnedValueStates</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a7dcc7e60c55b76d16688ee3b04f804e4">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a193d427e5f23228ebb54da668ab02360">anonymous{AttributorAttributes.cpp}::getArgumentStateFromCallBaseContext</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#aec5728cc58649b5df11e645c97190fb8">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#a994c04cdb21b071d608c92eef461a88f">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::getDeducedAttributes</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a7159508155406ad5c350cc429980e09d">anonymous{AttributorAttributes.cpp}::getKnownNonNullAndDerefBytesForUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a0cb597b1f0cffe907fa834e9a95fe719">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a753ca373c3a99cb66666a497408ed72f">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#a35445c95fd89ba05e25a51bc417d24ff">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamustprogressimpl/#a9cf505706b8c2759833523482b0f9aa9">anonymous{AttributorAttributes.cpp}::AAMustProgressImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a86b9b15b791a3208226b41ae6fe2e869">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreeimpl/#a97c7dffaf9ec22a169ea965e2b255e95">anonymous{AttributorAttributes.cpp}::AANoFreeImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanorecurseimpl/#a5eb6779c5f8ea4cd5cdc24493a81a021">anonymous{AttributorAttributes.cpp}::AANoRecurseImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoreturnimpl/#a10cd7f9d7d5fc1ec427ad5dea2e98506">anonymous{AttributorAttributes.cpp}::AANoReturnImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanosyncimpl/#affb233d00cdbadc031afb08ae53ec518">anonymous{AttributorAttributes.cpp}::AANoSyncImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanounwindimpl/#a39e8c01cb5efac8b343ef895b3f2bbc3">anonymous{AttributorAttributes.cpp}::AANoUnwindImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aawillreturnimpl/#a04dae7c49e8ce3ffdb55eb4b10b84c26">anonymous{AttributorAttributes.cpp}::AAWillReturnImpl::initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#ac4e3c1743f6f71b7424a580571065530">isAssumedReadOnlyOrReadNone</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl/#a2758a929f5cb19b83ebb78e91b10ccb2">anonymous{AttributorAttributes.cpp}::AAIsDeadValueImpl::isAssumedSideEffectFree</a>, <a href="#a1f2a3f39b7febd40285065a7ed05b71d">isAssumedThreadLocalObject</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#a0a41d500fe5dcf2f575b99316d25ec30">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::isKnownNoAliasDueToNoAliasPreservation</a>, <a href="#add4df090e923f2fe0dceeb0c60e5f74b">isNoSyncInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#a976bb954c41e5ef3963f408aa726aba7">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#aa706a9b987f484bb0ac2c16422522dbc">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#ae66a50449dec20c1a137f704e5e2c949">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite/#a13627a051dc8e791e2f3f1699575605b">anonymous{AttributorAttributes.cpp}::AACalleeToCallSite&lt; AADereferenceable, AADereferenceableImpl &gt;::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#abe94b0d36f169e52ede6a35d6ac41859">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#a554ade21fa5bda8daa3af645c00364b1">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainstanceinfoimpl/#a42d1b636e669eab226d5c36c5569c4d6">anonymous{AttributorAttributes.cpp}::AAInstanceInfoImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a31f2a80a770f0aa93c1fab42e9d41407">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamustprogresscallsite/#a03cbaff1b92ba39f9f8b6e672c2c9d1e">anonymous{AttributorAttributes.cpp}::AAMustProgressCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamustprogressfunction/#a84b5ff4a5e48342e4d1dc19ffdb26105">anonymous{AttributorAttributes.cpp}::AAMustProgressFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliasargument/#abfc802ab387bc38bb8602eb1732737bd">anonymous{AttributorAttributes.cpp}::AANoAliasArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#ae7864a73feb64332db5d9304ee4a7ace">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliasreturned/#a58add1c5be55c8da55788e7cc412a877">anonymous{AttributorAttributes.cpp}::AANoAliasReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocapturecallsiteargument/#af8af50bbe36f25d0fd0d35c5d6e973fa">anonymous{AttributorAttributes.cpp}::AANoCaptureCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a2b832055235bac7e33fee8273b9c0211">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreecallsiteargument/#a057aad39e2f87b33e18b53e28adbf90b">anonymous{AttributorAttributes.cpp}::AANoFreeCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreefloating/#a81f7ea399468b1020d91546408433b54">anonymous{AttributorAttributes.cpp}::AANoFreeFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreeimpl/#a642335d91f91ad57c209550723da37c2">anonymous{AttributorAttributes.cpp}::AANoFreeImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonnullfloating/#a4b1fa4ad98c736b05369d73702328439">anonymous{AttributorAttributes.cpp}::AANonNullFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanorecursefunction/#a70d0199665a55282a85300405acf7419">anonymous{AttributorAttributes.cpp}::AANoRecurseFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanosyncimpl/#a671a7ae35e26ce8b5b12340ec2c712a6">anonymous{AttributorAttributes.cpp}::AANoSyncImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoundeffloating/#a6b86977408d6fd3bc77f900143401adb">anonymous{AttributorAttributes.cpp}::AANoUndefFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanounwindimpl/#ae8a0b1fdd249b94eeb8f937104a6c90d">anonymous{AttributorAttributes.cpp}::AANoUnwindImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrcallsiteargument/#ab15ea1d1102ef77ffab18c2e35cada55">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaundefinedbehaviorimpl/#ae455d1ecbeb7d95762d758c9aae70512">anonymous{AttributorAttributes.cpp}::AAUndefinedBehaviorImpl::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aawillreturnimpl/#a716d51da277d8ec4901a5f425dc274d1">anonymous{AttributorAttributes.cpp}::AAWillReturnImpl::updateImpl</a>.</p>

</div>
</div>

### isAssumedReadNone() {#a1496d1d7b408ea24a3c4d3c6d9a2d08c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isAssumedReadNone (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, bool &amp; IsKnown)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">IRP</span> is readnone.</p>


<p>This will query respective AAs that deduce the information and introduce dependences for <span class="doxyComputerOutput">QueryingAA</span>.</p>


<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#ac4e3c1743f6f71b7424a580571065530">isAssumedReadOnlyOrReadNone</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>.</p>

</div>
</div>

### isAssumedReadOnly() {#a17d95a36815f9b2bb3441fd61ee328be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isAssumedReadOnly (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, bool &amp; IsKnown)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">IRP</span> is readonly.</p>


<p>This will query respective AAs that deduce the information and introduce dependences for <span class="doxyComputerOutput">QueryingAA</span>.</p>


<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#ac4e3c1743f6f71b7424a580571065530">isAssumedReadOnlyOrReadNone</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl/#a2758a929f5cb19b83ebb78e91b10ccb2">anonymous{AttributorAttributes.cpp}::AAIsDeadValueImpl::isAssumedSideEffectFree</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aawillreturnimpl/#a7cd0840479bd42b4e10b4b5502f19edd">anonymous{AttributorAttributes.cpp}::AAWillReturnImpl::isImpliedByMustprogressAndReadonly</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliasargument/#abfc802ab387bc38bb8602eb1732737bd">anonymous{AttributorAttributes.cpp}::AANoAliasArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a2b832055235bac7e33fee8273b9c0211">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrcallsiteargument/#ab15ea1d1102ef77ffab18c2e35cada55">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrCallSiteArgument::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>.</p>

</div>
</div>

### isAssumedThreadLocalObject() {#a1f2a3f39b7febd40285065a7ed05b71d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isAssumedThreadLocalObject (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">Obj</span> is assumed to be a thread local object.</p>

<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a0ab72bc360a96141393d6ff9f1af7511acb17869fe51048b5a5c4c6106551a255">Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#ae8abeaeed2f11072b2d064fe70510e9f">hasAssumedIRAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a0ab72bc360a96141393d6ff9f1af7511a509820290d57f333403f490dde7316f4">Local</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#a11c293d30d1890d44e558905f3c0548c">llvm::InformationCache::stackIsAccessibleByOtherThreads</a> and <a href="/web-llvm/docs/api/structs/llvm/irposition/#a3bee165465962ee97307066da4f0fb13">llvm::IRPosition::value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a7dcc7e60c55b76d16688ee3b04f804e4">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses</a> and <a href="#a2517066083f5a59ca08c9724f8e727db">isPotentiallyAffectedByBarrier</a>.</p>

</div>
</div>

### isDynamicallyUnique() {#a559168f78e20f2d3d0e1763ee6e751ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isDynamicallyUnique (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V, bool ForAnalysisOnly=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">V</span> is dynamically unique, that is, there are no two "instances" of <span class="doxyComputerOutput">V</span> at runtime with different values.</p>


<p>Note: If <span class="doxyComputerOutput">ForAnalysisOnly</span> is set we only check that the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> will never use <span class="doxyComputerOutput">V</span> to represent two "instances" not that <span class="doxyComputerOutput">V</span> could not technically represent them.</p>


<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aainstanceinfo/#a61ebacb3626c93a0a9b38f4813ecf1e0">llvm::AAInstanceInfo::isAssumedUniqueForAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a> and <a href="/web-llvm/docs/api/structs/llvm/irposition/#a3bee165465962ee97307066da4f0fb13">llvm::IRPosition::value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a4366c809736e919b276b5cda925d17ac">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleLoadInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainstanceinfoimpl/#a42d1b636e669eab226d5c36c5569c4d6">anonymous{AttributorAttributes.cpp}::AAInstanceInfoImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesargument/#a2cc688aac3b055fb8d0cca7033823473">anonymous{AttributorAttributes.cpp}::AAPotentialValuesArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsitereturned/#a326827ab35aa09c37cb1a4ee329f67ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteReturned::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>.</p>

</div>
</div>

### isGPU() {#aba7baf8e2e8dff3bb7152c6ffeb52fb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isGPU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true iff <span class="doxyComputerOutput">M</span> target a GPU (and we can use GPU AS reasoning).</p>


<p>}</p>


<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a6982073fb3620dd727922e78e140af8f">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizePtrValue</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a7dcc7e60c55b76d16688ee3b04f804e4">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses</a>.</p>

</div>
</div>

### isNoSyncInst() {#add4df090e923f2fe0dceeb0c60e5f74b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isNoSyncInst (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">I</span> is a <span class="doxyComputerOutput">nosync</span> instruction.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> generic reasoning and potentially the corresponding <a href="/web-llvm/docs/api/structs/llvm/aanosync">AANoSync</a>.</p>


<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#aeef35bb007616add7418161b0313b56b">llvm::IRPosition::callsite_function</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ae8abeaeed2f11072b2d064fe70510e9f">hasAssumedIRAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/aanosync/#ac04222d8711a686794d15456445dd4fb">llvm::AANoSync::isNonRelaxedAtomic</a>, <a href="/web-llvm/docs/api/structs/llvm/aanosync/#af5126302d811937f43d1b3909e7a564d">llvm::AANoSync::isNoSyncIntrinsic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanosyncimpl/#a671a7ae35e26ce8b5b12340ec2c712a6">anonymous{AttributorAttributes.cpp}::AANoSyncImpl::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a>.</p>

</div>
</div>

### isPotentiallyAffectedByBarrier() {#a9b9d4b530f90e36eede3c575ad1948ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isPotentiallyAffectedByBarrier (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">I</span> is potentially affected by a barrier.</p>

<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a0c7d0dae14eb8a5916fff9f72d8b46d2">llvm::SetVector&lt; T, Vector, Set, N &gt;::getArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#ac8f8983c6b76d0e30f22fff86b281f16">llvm::MemoryLocation::getForDest</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a207e239d68b66b0d5ccad5997a5ef027">llvm::MemoryLocation::getForSource</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#af61b31a99c1e58b1760492d2a7a1ba9c">llvm::MemoryLocation::getOrNone</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="#a9b9d4b530f90e36eede3c575ad1948ee">isPotentiallyAffectedByBarrier</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a9b9d4b530f90e36eede3c575ad1948ee">isPotentiallyAffectedByBarrier</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a>.</p>

</div>
</div>

### isPotentiallyAffectedByBarrier() {#a2517066083f5a59ca08c9724f8e727db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isPotentiallyAffectedByBarrier (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Ptrs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a1f2a3f39b7febd40285065a7ed05b71d">isAssumedThreadLocalObject</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/structs/llvm/irposition/#a3bee165465962ee97307066da4f0fb13">llvm::IRPosition::value</a>.</p>

</div>
</div>

### isPotentiallyReachable() {#adc52b79e64dcac96ea901cbfab1ccc52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isPotentiallyReachable (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; FromI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; ToI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab7dc88f593d600ddcfe97fcbd6f15e43">AA::InstExclusionSetTy</a> * ExclusionSet=nullptr, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>)&gt; GoBackwardsCB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">ToI</span> is potentially reachable from <span class="doxyComputerOutput">FromI</span> without running into any instruction in <span class="doxyComputerOutput">ExclusionSet</span> The two instructions do not need to be in the same function.</p>


<p><span class="doxyComputerOutput">GoBackwardsCB</span> can be provided to convey domain knowledge about the "lifespan" the user is interested in. By default, the callers of <span class="doxyComputerOutput">FromI</span> are checked as well to determine if <span class="doxyComputerOutput">ToI</span> can be reached. If the query is not interested in callers beyond a certain point, e.g., a GPU kernel entry or the function containing an alloca, the <span class="doxyComputerOutput">GoBackwardsCB</span> should return false.</p>


<p>Declaration at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 816 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a7dcc7e60c55b76d16688ee3b04f804e4">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#a0a41d500fe5dcf2f575b99316d25ec30">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::isKnownNoAliasDueToNoAliasPreservation</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainstanceinfoimpl/#a42d1b636e669eab226d5c36c5569c4d6">anonymous{AttributorAttributes.cpp}::AAInstanceInfoImpl::updateImpl</a>.</p>

</div>
</div>

### isPotentiallyReachable() {#a18d541007c596beba0b31031ce056669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isPotentiallyReachable (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; FromI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; ToFn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab7dc88f593d600ddcfe97fcbd6f15e43">AA::InstExclusionSetTy</a> * ExclusionSet=nullptr, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>)&gt; GoBackwardsCB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as above but it is sufficient to reach any instruction in <span class="doxyComputerOutput">ToFn</span>.</p>

<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 826 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### isValidAtPosition() {#a1ec1a38ef077070bf9d3760ddbbcfe24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isValidAtPosition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aa/valueandcontext">ValueAndContext</a> &amp; VAC, <a href="/web-llvm/docs/api/structs/llvm/informationcache">InformationCache</a> &amp; InfoCache)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the value of <span class="doxyComputerOutput">VAC</span> is a valid at the position of <span class="doxyComputerOutput">VAC</span>, that is a constant, an argument of the same function, or an instruction in that function that dominates the position.</p>

<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#af887d734d176f82b42528b55c0bdc4f7">llvm::InformationCache::getAnalysisResultForFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackerfunction/#ab0a8c344bd57a953ec6b9327a443b2b0">anonymous{OpenMPOpt.cpp}::AAICVTrackerFunction::getValueForCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#aaf6f1a343b2a0c4e03abaff3569e5269">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a1cfca839ff13dd1c214a5dae9c737bda">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::manifest</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a450c2f1a2d1c2e08bf66297247baa964">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::reproduceValue</a>.</p>

</div>
</div>

### isValidInScope() {#ad7be59b8a3d5e2faf55b21c42ed07a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::isValidInScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">V</span> is a valid value in <span class="doxyComputerOutput">Scope</span>, that is a constant or an instruction/argument of <span class="doxyComputerOutput">Scope</span>.</p>

<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae92d755a80dec605503e2ba653765360">llvm::Attributor::getAssumedSimplifiedValues</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a4366c809736e919b276b5cda925d17ac">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleLoadInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#ade252ec650f1f043ccf664b66c038d38">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::isValidCtxInstructionForOutsideAnalysis</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsitereturned/#a326827ab35aa09c37cb1a4ee329f67ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteReturned::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a8f6027dabb6a1e32d6d01e904d6372a0">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::updateImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
