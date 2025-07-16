---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DevirtIndex` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{WholeProgramDevirt.cpp}::DevirtIndex { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5db647c9814cb99c752697414e3399">DevirtIndex</a> (ModuleSummaryIndex &amp;ExportSummary, std::set&lt; GlobalValue::GUID &gt; &amp;ExportedGUIDs, std::map&lt; ValueInfo, std::vector&lt; VTableSlotSummary &gt; &gt; &amp;LocalWPDTargetsMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd9be7acff38f150936f7bbfe72ac14">tryFindVirtualCallTargets</a> (std::vector&lt; ValueInfo &gt; &amp;TargetsForSlot, const TypeIdCompatibleVtableInfo TIdInfo, uint64_t ByteOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e99a7c09395086976fe39e08dbe36a6">trySingleImplDevirt</a> (MutableArrayRef&lt; ValueInfo &gt; TargetsForSlot, VTableSlotSummary &amp;SlotSummary, VTableSlotInfo &amp;SlotInfo, WholeProgramDevirtResolution *Res, std::set&lt; ValueInfo &gt; &amp;DevirtTargets)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6378f806ed88c9d72ddcb04dacd75ce">run</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a580a3d29805799d41ed60b32fdb93e85">ExportSummary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a211f4c50a39b65312e78e28b8495fe9f">ExportedGUIDs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a>, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/vtableslotsummary">VTableSlotSummary</a> &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea2860c9fa6197642568af4277e8f66c">LocalWPDTargetsMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vtableslotsummary">VTableSlotSummary</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo">VTableSlotInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5007d06acac8e5cbeae9d69e07c0aaa3">CallSlots</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/patternlist">PatternList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ba27cf0873670701cc296c02750359">FunctionsToSkip</a></td>
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


<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DevirtIndex() {#aee5db647c9814cb99c752697414e3399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::DevirtIndex (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; ExportSummary, std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; ExportedGUIDs, std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a>, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/vtableslotsummary">VTableSlotSummary</a> &gt; &gt; &amp; LocalWPDTargetsMap)</td>
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



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a211f4c50a39b65312e78e28b8495fe9f">ExportedGUIDs</a>, <a href="#a580a3d29805799d41ed60b32fdb93e85">ExportSummary</a>, <a href="#aa5ba27cf0873670701cc296c02750359">FunctionsToSkip</a>, <a href="#aea2860c9fa6197642568af4277e8f66c">LocalWPDTargetsMap</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#a4acfa59172dc9825ef4c1362be8d31e7">SkipFunctionNames</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#ad6378f806ed88c9d72ddcb04dacd75ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtIndex::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5007d06acac8e5cbeae9d69e07c0aaa3">CallSlots</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a580a3d29805799d41ed60b32fdb93e85">ExportSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a71ee7e63264e4997a3340a781d44832e">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#acf0749a3f0019d8d6f49681ae6a6bd51">PrintSummaryDevirt</a>, <a href="#abcd9be7acff38f150936f7bbfe72ac14">tryFindVirtualCallTargets</a> and <a href="#a0e99a7c09395086976fe39e08dbe36a6">trySingleImplDevirt</a>.</p>

</div>
</div>

### tryFindVirtualCallTargets() {#abcd9be7acff38f150936f7bbfe72ac14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtIndex::tryFindVirtualCallTargets (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &gt; &amp; TargetsForSlot, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ada2485ca228b028f8639ad86ce41d6ec">TypeIdCompatibleVtableInfo</a> TIdInfo, uint64_t ByteOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a578061260691a59a9e7b0455fd68359c">llvm::GlobalValue::isAvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a308b65a044b4f53e31a2026a81c991d2">llvm::GlobalValue::isLocalLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#aaeceda7c9243e01a0888f44e2f3e7ba3">mustBeUnreachableFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ab0fc6ae566ff5de33790f565a2abe49aa938bd45f40d238428b91833b85ecd22a">llvm::GlobalObject::VCallVisibilityPublic</a>.</p>


<p>Referenced by <a href="#ad6378f806ed88c9d72ddcb04dacd75ce">run</a>.</p>

</div>
</div>

### trySingleImplDevirt() {#a0e99a7c09395086976fe39e08dbe36a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtIndex::trySingleImplDevirt (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &gt; TargetsForSlot, <a href="/web-llvm/docs/api/structs/llvm/vtableslotsummary">VTableSlotSummary</a> &amp; SlotSummary, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo">VTableSlotInfo</a> &amp; SlotInfo, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> * Res, std::set&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &gt; &amp; DevirtTargets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#aa8309e74a87a287dfe316da0535c4722">AddCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a846137dc22b3b399b62f606698f3ed59">llvm::AreStatisticsEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a211f4c50a39b65312e78e28b8495fe9f">ExportedGUIDs</a>, <a href="#a580a3d29805799d41ed60b32fdb93e85">ExportSummary</a>, <a href="#aa5ba27cf0873670701cc296c02750359">FunctionsToSkip</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#ab2a95e6bf06c717c20fc64f6c1e5a2fa">llvm::ModuleSummaryIndex::getGlobalNameForLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a308b65a044b4f53e31a2026a81c991d2">llvm::GlobalValue::isLocalLinkage</a>, <a href="#aea2860c9fa6197642568af4277e8f66c">LocalWPDTargetsMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#acf0749a3f0019d8d6f49681ae6a6bd51">PrintSummaryDevirt</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ae992643f8965e97ffbc353b083615208a05ee7e7ff849410d68ccfd73e177387f">llvm::WholeProgramDevirtResolution::SingleImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ab97c12959c5cc7b46b115da7e1ac5047">llvm::WholeProgramDevirtResolution::SingleImplName</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a11bddbadb47e3bd7803ded5d4f4248fc">llvm::WholeProgramDevirtResolution::TheKind</a>.</p>


<p>Referenced by <a href="#ad6378f806ed88c9d72ddcb04dacd75ce">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CallSlots {#a5007d06acac8e5cbeae9d69e07c0aaa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;VTableSlotSummary, VTableSlotInfo&gt; anonymous{WholeProgramDevirt.cpp}::DevirtIndex::CallSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#ad6378f806ed88c9d72ddcb04dacd75ce">run</a>.</p>

</div>
</div>

### ExportedGUIDs {#a211f4c50a39b65312e78e28b8495fe9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;GlobalValue::GUID&gt;&amp; anonymous{WholeProgramDevirt.cpp}::DevirtIndex::ExportedGUIDs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#aee5db647c9814cb99c752697414e3399">DevirtIndex</a> and <a href="#a0e99a7c09395086976fe39e08dbe36a6">trySingleImplDevirt</a>.</p>

</div>
</div>

### ExportSummary {#a580a3d29805799d41ed60b32fdb93e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSummaryIndex&amp; anonymous{WholeProgramDevirt.cpp}::DevirtIndex::ExportSummary</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#aee5db647c9814cb99c752697414e3399">DevirtIndex</a>, <a href="#ad6378f806ed88c9d72ddcb04dacd75ce">run</a> and <a href="#a0e99a7c09395086976fe39e08dbe36a6">trySingleImplDevirt</a>.</p>

</div>
</div>

### FunctionsToSkip {#aa5ba27cf0873670701cc296c02750359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PatternList anonymous{WholeProgramDevirt.cpp}::DevirtIndex::FunctionsToSkip</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#aee5db647c9814cb99c752697414e3399">DevirtIndex</a> and <a href="#a0e99a7c09395086976fe39e08dbe36a6">trySingleImplDevirt</a>.</p>

</div>
</div>

### LocalWPDTargetsMap {#aea2860c9fa6197642568af4277e8f66c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;ValueInfo, std::vector&lt;VTableSlotSummary&gt; &gt;&amp; anonymous{WholeProgramDevirt.cpp}::DevirtIndex::LocalWPDTargetsMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#aee5db647c9814cb99c752697414e3399">DevirtIndex</a> and <a href="#a0e99a7c09395086976fe39e08dbe36a6">trySingleImplDevirt</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
