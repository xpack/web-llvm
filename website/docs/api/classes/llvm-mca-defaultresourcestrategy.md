---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/defaultresourcestrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DefaultResourceStrategy` Class Reference

<p>Default resource allocation strategy used by processor resource groups and processor resources with multiple units. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::mca::DefaultResourceStrategy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">llvm/MCA/HardwareUnits/ResourceManager.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/resourcestrategy">ResourceStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resource allocation strategy used by hardware scheduler resources. <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestrategy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10cdf68ba23d403b70dd95f8d0f2023b">DefaultResourceStrategy</a> (uint64_t UnitMask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae738360dc7fe17f32f3602264628f2dd">~DefaultResourceStrategy</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae98cd9a61040a0208a29df6238b7aa08">select</a> (uint64_t ReadyMask) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Selects a processor resource unit from a ReadyMask. <a href="#ae98cd9a61040a0208a29df6238b7aa08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c31dd9225bfb63fd296560b380c2bd">used</a> (uint64_t Mask) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by the <a href="/web-llvm/docs/api/classes/llvm/resourcemanager">ResourceManager</a> when a processor resource group, or a processor resource with multiple units has become unavailable. <a href="#a37c31dd9225bfb63fd296560b380c2bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1367398974ada69c45d2f8ab0120c981">ResourceUnitMask</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A Mask of resource unit identifiers. <a href="#a1367398974ada69c45d2f8ab0120c981">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ff2007f601aa66c1c73c400d5c73902">NextInSequenceMask</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A simple round-robin selector for processor resource units. <a href="#a2ff2007f601aa66c1c73c400d5c73902">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a875fe6d657ee4e85a66e79d33f65c696">RemovedFromNextInSequence</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This field is used to track resource units that are used (i.e. <a href="#a875fe6d657ee4e85a66e79d33f65c696">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Default resource allocation strategy used by processor resource groups and processor resources with multiple units.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DefaultResourceStrategy() {#a10cdf68ba23d403b70dd95f8d0f2023b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::DefaultResourceStrategy::DefaultResourceStrategy (uint64_t UnitMask)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DefaultResourceStrategy() {#ae738360dc7fe17f32f3602264628f2dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::mca::DefaultResourceStrategy::~DefaultResourceStrategy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### select() {#ae98cd9a61040a0208a29df6238b7aa08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::DefaultResourceStrategy::select (uint64_t ReadyMask)</td>
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

<p>Selects a processor resource unit from a ReadyMask.</p>

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a9daeae4f77bbf637d7f5ed46c92ed5c5">llvm::mca::selectImpl</a>.</p>

</div>
</div>

### used() {#a37c31dd9225bfb63fd296560b380c2bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::DefaultResourceStrategy::used (uint64_t ResourceMask)</td>
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

<p>Called by the <a href="/web-llvm/docs/api/classes/llvm/resourcemanager">ResourceManager</a> when a processor resource group, or a processor resource with multiple units has become unavailable.</p>


<p>The default strategy uses this information to bias its selection logic.</p>


<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NextInSequenceMask {#a2ff2007f601aa66c1c73c400d5c73902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::DefaultResourceStrategy::NextInSequenceMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A simple round-robin selector for processor resource units.</p>


<p>Each bit of this mask identifies a sub resource within a group.</p>


<p>As an example, lets assume that this is a default policy for a processor resource group composed by the following three units: ResourceA – 0b001 ResourceB – 0b010 ResourceC – 0b100</p>


<p><a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> NextInSequenceMask is used to select the next unit from the set of resource units. It defaults to the value of field <span class="doxyComputerOutput">ResourceUnitMasks</span> (in this example, it defaults to mask '0b111').</p>


<p>The round-robin selector would firstly select 'ResourceC', then 'ResourceB', and eventually 'ResourceA'. When a resource R is used, the corresponding bit in NextInSequenceMask is cleared. For example, if 'ResourceC' is selected, then the new value of NextInSequenceMask becomes 0xb011.</p>


<p>When NextInSequenceMask becomes zero, it is automatically reset to the default value (i.e. ResourceUnitMask).</p>


<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### RemovedFromNextInSequence {#a875fe6d657ee4e85a66e79d33f65c696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::DefaultResourceStrategy::RemovedFromNextInSequence</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This field is used to track resource units that are used (i.e.</p>


<p>selected) by other groups other than the one associated with this strategy object.</p>


<p>In LLVM processor resource groups are allowed to partially (or fully) overlap. That means, a same unit may be visible to multiple groups. This field keeps track of uses that have originated from outside of this group. The idea is to bias the selection strategy, so that resources that haven't been used by other groups get prioritized.</p>


<p>The end goal is to (try to) keep the resource distribution as much uniform as possible. By construction, this mask only tracks one-level of resource usage. Therefore, this strategy is expected to be less accurate when same units are used multiple times by other groups within a single round of select.</p>


<p>Note: an LRU selector would have a better accuracy at the cost of being slightly more expensive (mostly in terms of runtime cost). Methods 'select' and 'used', are always in the hot execution path of llvm-mca. Therefore, a slow implementation of 'select' would have a negative impact on the overall performance of the tool.</p>


<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### ResourceUnitMask {#a1367398974ada69c45d2f8ab0120c981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::mca::DefaultResourceStrategy::ResourceUnitMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A Mask of resource unit identifiers.</p>


<p>There is one bit set for every available resource unit. It defaults to the value of field ResourceSizeMask in <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate">ResourceState</a>.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
