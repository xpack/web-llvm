---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `OMPContext.cpp` File

<p>This file implements helper functions and classes to deal with OpenMP contexts as used by <span class="doxyComputerOutput">[begin/end] declare variant</span> and <span class="doxyComputerOutput">metadirective</span>. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">llvm/Frontend/OpenMP/OMPContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include "llvm/Frontend/OpenMP/OMPKinds.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac4d13f5ea905de676278414d7f7c2601">isSubset</a> (ArrayRef&lt; T &gt; C0, ArrayRef&lt; T &gt; C1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">C0</span> is a subset of <span class="doxyComputerOutput">C1</span>. <a href="#ac4d13f5ea905de676278414d7f7c2601">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a05d88c62bda0d2e90b00e2407db9b556">isStrictSubset</a> (ArrayRef&lt; T &gt; C0, ArrayRef&lt; T &gt; C1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">C0</span> is a strict subset of <span class="doxyComputerOutput">C1</span>. <a href="#a05d88c62bda0d2e90b00e2407db9b556">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e6a1be6ce8d2df306c9b6c34706610d">isStrictSubset</a> (const VariantMatchInfo &amp;VMI0, const VariantMatchInfo &amp;VMI1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a> (const VariantMatchInfo &amp;VMI, const OMPContext &amp;Ctx, SmallVectorImpl&lt; unsigned &gt; *ConstructMatches, bool DeviceSetOnly)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0776bd50b7c822627400a43977db933b">getVariantMatchScore</a> (const VariantMatchInfo &amp;VMI, const OMPContext &amp;Ctx, SmallVectorImpl&lt; unsigned &gt; &amp;ConstructMatches)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"openmp-<a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#a3d3459f5796b9b9f0253f71d5620e958">ir</a>-builder"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4472c452d7a9a0a2bb0af8ed35e290a6">OMP_TRAIT_PROPERTY</a>(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbbc2ef80506fd714ce71b12e18fc5e2">OMP_TRAIT_SET</a>(Enum, Str)&nbsp;&nbsp;&nbsp;.Case(Str, TraitSet::Enum)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be2d078c441cd94469605cf837acb5a">OMP_TRAIT_SELECTOR</a>(Enum, TraitSetEnum, Str, ReqProp)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e55c90adf189b48711ce0c6970f951e">OMP_TRAIT_PROPERTY</a>(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7508ce26947c5b2489cb5d9136b95f4f">OMP_TRAIT_SET</a>(Enum, Str)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab92d0511e84a38a4ccfc3dacef270896">OMP_TRAIT_SELECTOR</a>(Enum, TraitSetEnum, Str, ReqProp)&nbsp;&nbsp;&nbsp;  .Case(Str, TraitSelector::Enum)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae020e12f341a072b87e8a5c33c59b4e8">OMP_TRAIT_PROPERTY</a>(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6246fb949161c39acf3e31d0776739c9">OMP_TRAIT_SELECTOR</a>(Enum, TraitSetEnum, Str, ReqProp)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13c4bb4a785d6b309bff8a14bb5d7c95">OMP_TRAIT_PROPERTY</a>(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e9f39148c9c48b52657f8ce241d8255">OMP_TRAIT_PROPERTY</a>(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f90397388c1522f57e245004e8394da">OMP_TRAIT_PROPERTY</a>(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e450060b23ff26fbe153782db985176">OMP_TRAIT_PROPERTY</a>(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8b0fe975bb1da76e4bb18a7a4b5c5f4">OMP_TRAIT_SELECTOR</a>(Enum, TraitSetEnum, Str, ReqProp)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a744e8a33807a07202a437bda1b5c3f">OMP_TRAIT_PROPERTY</a>(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac407db0f26286ea47f769fa4e6994da2">OMP_TRAIT_SET</a>(Enum, Str)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a505405adbb01d28b09505d77b07e6347">OMP_TRAIT_SELECTOR</a>(Enum, TraitSetEnum, Str, ReqProp)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dfa3a8e022d5b8720b0b44fab8fa685">OMP_TRAIT_PROPERTY</a>(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
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

<p>This file implements helper functions and classes to deal with OpenMP contexts as used by <span class="doxyComputerOutput">[begin/end] declare variant</span> and <span class="doxyComputerOutput">metadirective</span>.</p>

<div class="doxySectionDef">

## Functions

### getVariantMatchScore() {#a0776bd50b7c822627400a43977db933b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt getVariantMatchScore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo">VariantMatchInfo</a> &amp; VMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/omp/ompcontext">OMPContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; ConstructMatches)</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo/#a391eed61e8202859bdda749028fab76e">llvm::omp::VariantMatchInfo::ConstructTraits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#ac1fa08b331c261d3acc12d3821b77b2f">llvm::omp::getOpenMPContextTraitSelectorForProperty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a6ab910ced9f2e14f0c3b7a176ab5fe45">llvm::omp::getOpenMPContextTraitSetForProperty</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo/#a350aec756a45652070266d41672199b8">llvm::omp::VariantMatchInfo::RequiredTraits</a>, <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo/#ac9c13ad13f5c1ebefe7039b90868cec0">llvm::omp::VariantMatchInfo::ScoreMap</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#aa56c07cdb4f03ddef7dfdf460811d36e">llvm::BitVector::set_bits</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a7fe8accb4198eb111067fe7c4bb544dd">llvm::omp::getBestVariantMatchForContext</a>.</p>

</div>
</div>

### isStrictSubset() {#a05d88c62bda0d2e90b00e2407db9b556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isStrictSubset (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; C0, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; C1)</td>
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

<p>Return true if <span class="doxyComputerOutput">C0</span> is a strict subset of <span class="doxyComputerOutput">C1</span>.</p>


<p>Note that both arrays are expected to be sorted.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>References <a href="#ac4d13f5ea905de676278414d7f7c2601">isSubset</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a7fe8accb4198eb111067fe7c4bb544dd">llvm::omp::getBestVariantMatchForContext</a>.</p>

</div>
</div>

### isStrictSubset() {#a7e6a1be6ce8d2df306c9b6c34706610d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isStrictSubset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo">VariantMatchInfo</a> &amp; VMI0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo">VariantMatchInfo</a> &amp; VMI1)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo/#a391eed61e8202859bdda749028fab76e">llvm::omp::VariantMatchInfo::ConstructTraits</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a568ff706b8c5991bd299c8c00b803897">llvm::BitVector::count</a>, <a href="#ac4d13f5ea905de676278414d7f7c2601">isSubset</a>, <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo/#a350aec756a45652070266d41672199b8">llvm::omp::VariantMatchInfo::RequiredTraits</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#aa56c07cdb4f03ddef7dfdf460811d36e">llvm::BitVector::set_bits</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>.</p>

</div>
</div>

### isSubset() {#ac4d13f5ea905de676278414d7f7c2601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSubset (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; C0, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; C1)</td>
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

<p>Return true if <span class="doxyComputerOutput">C0</span> is a subset of <span class="doxyComputerOutput">C1</span>.</p>


<p>Note that both arrays are expected to be sorted.</p>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a05d88c62bda0d2e90b00e2407db9b556">isStrictSubset</a>, <a href="#a7e6a1be6ce8d2df306c9b6c34706610d">isStrictSubset</a> and <a href="#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>.</p>

</div>
</div>

### isVariantApplicableInContextHelper() {#ad468a923807a048c8f7379f087507651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int isVariantApplicableInContextHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo">VariantMatchInfo</a> &amp; VMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/omp/ompcontext">OMPContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; * ConstructMatches, bool DeviceSetOnly)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo/#a391eed61e8202859bdda749028fab76e">llvm::omp::VariantMatchInfo::ConstructTraits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a9716757628bb15b0930b25325b5edb10">llvm::omp::getOpenMPContextTraitPropertyName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#ac1fa08b331c261d3acc12d3821b77b2f">llvm::omp::getOpenMPContextTraitSelectorForProperty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a6ab910ced9f2e14f0c3b7a176ab5fe45">llvm::omp::getOpenMPContextTraitSetForProperty</a>, <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo/#a28550439283e1ce0094fa4ae13db5ccb">llvm::omp::VariantMatchInfo::ISATraits</a>, <a href="#ac4d13f5ea905de676278414d7f7c2601">isSubset</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo/#a350aec756a45652070266d41672199b8">llvm::omp::VariantMatchInfo::RequiredTraits</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#aa56c07cdb4f03ddef7dfdf460811d36e">llvm::BitVector::set_bits</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a7fe8accb4198eb111067fe7c4bb544dd">llvm::omp::getBestVariantMatchForContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/omp/#af416d75b9a8863d8e262d00743dc66f7">llvm::omp::isVariantApplicableInContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"openmp-<a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#a3d3459f5796b9b9f0253f71d5620e958">ir</a>-builder"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_PROPERTY {#a4472c452d7a9a0a2bb0af8ed35e290a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_PROPERTY(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (TraitSelector::TraitSelectorEnum == TraitSelector::device_arch) {        \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (TargetTriple.getArch() == TargetTriple.getArchTypeForLLVMName(Str))    \
      ActiveTraits.set(unsigned(TraitProperty::Enum));                         \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (StringRef(Str) == "x86_64" &amp;&amp;                                          \
        TargetTriple.getArch() == Triple::x86_64)                              \
      ActiveTraits.set(unsigned(TraitProperty::Enum));                         \
  }
</div>
</dd>
</dl>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_PROPERTY {#a7e55c90adf189b48711ce0c6970f951e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_PROPERTY(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case TraitProperty::Enum:                                                    \
    return TraitSet::TraitSetEnum;
</div>
</dd>
</dl>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_PROPERTY {#ae020e12f341a072b87e8a5c33c59b4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_PROPERTY(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case TraitProperty::Enum:                                                    \
    return TraitSelector::TraitSelectorEnum;
</div>
</dd>
</dl>

<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_PROPERTY {#a13c4bb4a785d6b309bff8a14bb5d7c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_PROPERTY(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Set == TraitSet::TraitSetEnum &amp;&amp; Str == S)                               \
    return TraitProperty::Enum;
</div>
</dd>
</dl>

<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_PROPERTY {#a8e9f39148c9c48b52657f8ce241d8255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_PROPERTY(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  .Case(Str, Selector == TraitSelector::TraitSelectorEnum                      \
                 ? TraitProperty::Enum                                         \
                 : TraitProperty::invalid)
</div>
</dd>
</dl>

<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_PROPERTY {#a2f90397388c1522f57e245004e8394da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_PROPERTY(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case TraitProperty::Enum:                                                    \
    return Str;
</div>
</dd>
</dl>

<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_PROPERTY {#a5e450060b23ff26fbe153782db985176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_PROPERTY(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case TraitProperty::Enum:                                                    \
    return "(" #TraitSetEnum "," #TraitSelectorEnum "," Str ")";
</div>
</dd>
</dl>

<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_PROPERTY {#a0a744e8a33807a07202a437bda1b5c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_PROPERTY(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case TraitProperty::Enum:                                                    \
    return Set == TraitSet::TraitSetEnum &amp;&amp;                                    \
           Selector == TraitSelector::TraitSelectorEnum;
</div>
</dd>
</dl>

<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_PROPERTY {#a3dfa3a8e022d5b8720b0b44fab8fa685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_PROPERTY(Enum, TraitSetEnum, TraitSelectorEnum, Str)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (TraitSet::TraitSetEnum == Set &amp;&amp;                                         \
      TraitSelector::TraitSelectorEnum == Selector &amp;&amp;                          \
      StringRef(Str) != "invalid")                                             \
    S.append("'").append(Str).append("'").append(" ");
</div>
</dd>
</dl>

<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_SELECTOR {#a5be2d078c441cd94469605cf837acb5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_SELECTOR(Enum, TraitSetEnum, Str, ReqProp)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case TraitSelector::Enum:                                                    \
    return TraitSet::TraitSetEnum;
</div>
</dd>
</dl>

<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_SELECTOR {#ab92d0511e84a38a4ccfc3dacef270896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_SELECTOR(Enum, TraitSetEnum, Str, ReqProp)&nbsp;&nbsp;&nbsp;  .Case(Str, TraitSelector::Enum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_SELECTOR {#a6246fb949161c39acf3e31d0776739c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_SELECTOR(Enum, TraitSetEnum, Str, ReqProp)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case TraitSelector::Enum:                                                    \
    return Str;
</div>
</dd>
</dl>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_SELECTOR {#af8b0fe975bb1da76e4bb18a7a4b5c5f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_SELECTOR(Enum, TraitSetEnum, Str, ReqProp)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case TraitSelector::Enum:                                                    \
    RequiresProperty = ReqProp;                                                \
    return Set == TraitSet::TraitSetEnum;
</div>
</dd>
</dl>

<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_SELECTOR {#a505405adbb01d28b09505d77b07e6347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_SELECTOR(Enum, TraitSetEnum, Str, ReqProp)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (TraitSet::TraitSetEnum == Set &amp;&amp; StringRef(Str) != "Invalid")            \
    S.append("'").append(Str).append("'").append(" ");
</div>
</dd>
</dl>

<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_SET {#adbbc2ef80506fd714ce71b12e18fc5e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_SET(Enum, Str)&nbsp;&nbsp;&nbsp;.Case(Str, TraitSet::Enum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_SET {#a7508ce26947c5b2489cb5d9136b95f4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_SET(Enum, Str)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case TraitSet::Enum:                                                         \
    return Str;
</div>
</dd>
</dl>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### OMP\_TRAIT\_SET {#ac407db0f26286ea47f769fa4e6994da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OMP_TRAIT_SET(Enum, Str)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (StringRef(Str) != "invalid")                                             \
    S.append("'").append(Str).append("'").append(" ");
</div>
</dd>
</dl>

<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
