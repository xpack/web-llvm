---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/resourcemanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ResourceManager` Class Reference

<p>A resource manager for processor resource units and groups. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::mca::ResourceManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">llvm/MCA/HardwareUnits/ResourceManager.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d0922d705874b9cea40f18f294fa123">ResourceWithCycles</a> = std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aa013ffaca9bcaadec118afaede71ab29">ResourceRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/releaseatcycles">ReleaseAtCycles</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d000778dc6adcdb34b656a83939800a">ResourceManager</a> (const MCSchedModel &amp;SM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a57518c78fb4d6fe1d515b27c7b9117">~ResourceManager</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac566e78d7358c6a1d6b94e5c448b3bcd">setCustomStrategy</a> (std::unique_ptr&lt; ResourceStrategy &gt; S, unsigned ResourceID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072a">ResourceStateEvent</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4667d37055ff477b91719d2c84e2171">canBeDispatched</a> (uint64_t ConsumedBuffers) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a795cf659d06359358c86c4ea0f64ad">resolveResourceMask</a> (uint64_t Mask) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02869b34a5fed7e3d15b09d677ee8cf2">reserveBuffers</a> (uint64_t ConsumedBuffers)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d93a035221e49bed83c4e10a906ebad">releaseBuffers</a> (uint64_t ConsumedBuffers)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a946efb5d7f623e1285039dadcab561a9">reserveResource</a> (uint64_t ResourceID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a285124e918bd59e42a03792e0fee81">releaseResource</a> (uint64_t ResourceID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec872e4acf72f2b7fe8347d1c027b2b9">checkAvailability</a> (const InstrDesc &amp;Desc) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa90fc6aed26d5f91436e6693d08274b">getProcResUnitMask</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2495a18d0d821d616adc01d4fa6c717">getAvailableProcResUnits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a036f48e5c25b534f16e84aae90c56df7">issueInstruction</a> (const InstrDesc &amp;Desc, SmallVectorImpl&lt; ResourceWithCycles &gt; &amp;Pipes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422417017bcd1f449e0fc7f64622ad42">fastIssueInstruction</a> (const InstrDesc &amp;Desc, SmallVectorImpl&lt; ResourceWithCycles &gt; &amp;Pipes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94ebe004dfbba2e68530d0125ed16293">issueInstructionImpl</a> (const InstrDesc &amp;Desc, SmallVectorImpl&lt; ResourceWithCycles &gt; &amp;Pipes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1f2beab8ceaaf066d1523dd523fe25a">cycleEvent</a> (SmallVectorImpl&lt; ResourceRef &gt; &amp;ResourcesFreed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affc2d4b4c36db8ff43920257cd64d615">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/mca/#aa013ffaca9bcaadec118afaede71ab29">ResourceRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a464c1ec4304ed04bf623070c352b12">selectPipe</a> (uint64_t ResourceID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dc69bc3beffd768c0c6c7a65a19da66">use</a> (const ResourceRef &amp;RR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a834ce03ab17698b3131e79dc14471bc7">release</a> (const ResourceRef &amp;RR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93d63cb46cdcebeed8a4c3b4af72dc93">getNumUnits</a> (uint64_t ResourceID) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc76507f1ad2988efd88c428e78e2cce">setCustomStrategyImpl</a> (std::unique_ptr&lt; ResourceStrategy &gt; S, uint64_t ResourceMask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate">ResourceState</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bd0b5cdb01bdda564051785bf084ca7">Resources</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestrategy">ResourceStrategy</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add2f262593360499dfeff8472de4ac3f">Strategies</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5bcd3de89fc81d686c6d5436437ad0e">Resource2Groups</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a3fbf9aee5e9773016223f495f8e0c3">ProcResID2Mask</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac23bfc0c963f295a65497666bfafd6f0">ResIndex2ProcResID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aa013ffaca9bcaadec118afaede71ab29">ResourceRef</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3dfa8e08ce4bcf0e534dac33e1ccfed">BusyResources</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a553465efb94f9f5dc6f9fe1d8a24b346">ProcResUnitMask</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ee2217d4458262fc94a72926f2105a">AvailableProcResUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6bdaf2eb2b93791dd68c5ba9c5d48df">ReservedResourceGroups</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1714d0370fa0f51782d51fb6c0110aa1">AvailableBuffers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8918212c2767ae8d32b0f67a84d918">ReservedBuffers</a></td>
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

<p>A resource manager for processor resource units and groups.</p>


<p>This class owns all the <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate">ResourceState</a> objects, and it is responsible for acting on requests from a <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler">Scheduler</a> by updating the internal state of <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate">ResourceState</a> objects. This class doesn't know about instruction itineraries and functional units. In future, it can be extended to support itineraries too through the same public interface.</p>


<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ResourceWithCycles {#a5d0922d705874b9cea40f18f294fa123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::mca::ResourceManager::ResourceWithCycles =  std::pair&lt;ResourceRef, ReleaseAtCycles&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ResourceManager() {#a7d000778dc6adcdb34b656a83939800a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::ResourceManager::ResourceManager (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp; SM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae1d3c5a1f43dcec43774a3767b41e447">llvm::mca::computeProcResourceMasks</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a5268bc4b5673e84a8f75df74b024d374">llvm::MCSchedModel::getNumProcResourceKinds</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ac7376c4db05cd0fbb107dd0b1fecc9ba">llvm::MCSchedModel::getProcResource</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae652ac0aafced9e7ef6249d3b4e50171">llvm::mca::getResourceStateIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a64c9d50d5dc3399ab4bca5159e3ea35b">llvm::mca::getStrategyFor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#afed8fbb52bd979bc9a12381779985c6e">llvm::mca::ResourceState::isAResourceGroup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ResourceManager() {#a7a57518c78fb4d6fe1d515b27c7b9117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::mca::ResourceManager::~ResourceManager ()</td>
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



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canBeDispatched() {#ad4667d37055ff477b91719d2c84e2171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceStateEvent llvm::mca::ResourceManager::canBeDispatched (uint64_t ConsumedBuffers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072aa3f746cb41f05bc7d2405d8f261ad3b53">llvm::mca::RS_BUFFER_AVAILABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072aa31d38f37314ff7269028574355831c80">llvm::mca::RS_BUFFER_UNAVAILABLE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072aadc0c2c76e3c6a9189f1c720ed16abd2f">llvm::mca::RS_RESERVED</a>.</p>

</div>
</div>

### checkAvailability() {#aec872e4acf72f2b7fe8347d1c027b2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceManager::checkAvailability (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/instrdesc">InstrDesc</a> &amp; Desc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae22967d11b695d268992470debfae4b2">llvm::bit_floor</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#a1f30db123002f2e8d39b42dcd1c18570">llvm::mca::ResourceState::getReadyMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae652ac0aafced9e7ef6249d3b4e50171">llvm::mca::getResourceStateIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#afed8fbb52bd979bc9a12381779985c6e">llvm::mca::ResourceState::isAResourceGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#a73ae2ace0d555c5682324d2381d2e9d1">llvm::mca::ResourceState::isReady</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1a245b31aced1374f28f45d2b297f402">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::try_emplace</a>.</p>

</div>
</div>

### cycleEvent() {#aa1f2beab8ceaaf066d1523dd523fe25a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::cycleEvent (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aa013ffaca9bcaadec118afaede71ab29">ResourceRef</a> &gt; &amp; ResourcesFreed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a> and <a href="#a7a285124e918bd59e42a03792e0fee81">releaseResource</a>.</p>

</div>
</div>

### dump() {#affc2d4b4c36db8ff43920257cd64d615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::dump ()</td>
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



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### fastIssueInstruction() {#a422417017bcd1f449e0fc7f64622ad42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::fastIssueInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/instrdesc">InstrDesc</a> &amp; Desc, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#a5d0922d705874b9cea40f18f294fa123">ResourceWithCycles</a> &gt; &amp; Pipes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/cyclesegment/#ae685c65931e63b37c73195cda93e6e8c">llvm::mca::CycleSegment::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>, <a href="#a7a285124e918bd59e42a03792e0fee81">releaseResource</a>, <a href="#a946efb5d7f623e1285039dadcab561a9">reserveResource</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/cyclesegment/#ac4e0c44b851905b797eb1428321d06b0">llvm::mca::CycleSegment::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use</a>.</p>


<p>Referenced by <a href="#a036f48e5c25b534f16e84aae90c56df7">issueInstruction</a>.</p>

</div>
</div>

### getAvailableProcResUnits() {#af2495a18d0d821d616adc01d4fa6c717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceManager::getAvailableProcResUnits ()</td>
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



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### getProcResUnitMask() {#aaa90fc6aed26d5f91436e6693d08274b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceManager::getProcResUnitMask ()</td>
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



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### issueInstruction() {#a036f48e5c25b534f16e84aae90c56df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::issueInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/instrdesc">InstrDesc</a> &amp; Desc, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#a5d0922d705874b9cea40f18f294fa123">ResourceWithCycles</a> &gt; &amp; Pipes)</td>
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



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>References <a href="#a422417017bcd1f449e0fc7f64622ad42">fastIssueInstruction</a> and <a href="#a94ebe004dfbba2e68530d0125ed16293">issueInstructionImpl</a>.</p>

</div>
</div>

### issueInstructionImpl() {#a94ebe004dfbba2e68530d0125ed16293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::issueInstructionImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/instrdesc">InstrDesc</a> &amp; Desc, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#a5d0922d705874b9cea40f18f294fa123">ResourceWithCycles</a> &gt; &amp; Pipes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/cyclesegment/#ae685c65931e63b37c73195cda93e6e8c">llvm::mca::CycleSegment::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#a8bc30739c7dc3548e9ffd1c44f145cf1">llvm::mca::ResourceState::getNumReadyUnits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae652ac0aafced9e7ef6249d3b4e50171">llvm::mca::getResourceStateIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#afed8fbb52bd979bc9a12381779985c6e">llvm::mca::ResourceState::isAResourceGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a7a285124e918bd59e42a03792e0fee81">releaseResource</a>, <a href="#a946efb5d7f623e1285039dadcab561a9">reserveResource</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/cyclesegment/#ac4e0c44b851905b797eb1428321d06b0">llvm::mca::CycleSegment::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use</a>.</p>


<p>Referenced by <a href="#a036f48e5c25b534f16e84aae90c56df7">issueInstruction</a>.</p>

</div>
</div>

### releaseBuffers() {#a3d93a035221e49bed83c4e10a906ebad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::releaseBuffers (uint64_t ConsumedBuffers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae652ac0aafced9e7ef6249d3b4e50171">llvm::mca::getResourceStateIndex</a>.</p>

</div>
</div>

### releaseResource() {#a7a285124e918bd59e42a03792e0fee81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::releaseResource (uint64_t ResourceID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#af46fb23efb212b10dc397a1657a7b9de">llvm::mca::ResourceState::clearReserved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae652ac0aafced9e7ef6249d3b4e50171">llvm::mca::getResourceStateIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#a60da4b5907972b572cd9bfea05e873d2">llvm::mca::ResourceState::isADispatchHazard</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#afed8fbb52bd979bc9a12381779985c6e">llvm::mca::ResourceState::isAResourceGroup</a>.</p>


<p>Referenced by <a href="#aa1f2beab8ceaaf066d1523dd523fe25a">cycleEvent</a>, <a href="#a422417017bcd1f449e0fc7f64622ad42">fastIssueInstruction</a> and <a href="#a94ebe004dfbba2e68530d0125ed16293">issueInstructionImpl</a>.</p>

</div>
</div>

### reserveBuffers() {#a02869b34a5fed7e3d15b09d677ee8cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::reserveBuffers (uint64_t ConsumedBuffers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae652ac0aafced9e7ef6249d3b4e50171">llvm::mca::getResourceStateIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072aa3f746cb41f05bc7d2405d8f261ad3b53">llvm::mca::RS_BUFFER_AVAILABLE</a>.</p>

</div>
</div>

### reserveResource() {#a946efb5d7f623e1285039dadcab561a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::reserveResource (uint64_t ResourceID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae652ac0aafced9e7ef6249d3b4e50171">llvm::mca::getResourceStateIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#afed8fbb52bd979bc9a12381779985c6e">llvm::mca::ResourceState::isAResourceGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#ad86068473600ec09094efb9a31296440">llvm::mca::ResourceState::isReserved</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate/#a544c4ac3f4c76f40043ddc6d27062c0d">llvm::mca::ResourceState::setReserved</a>.</p>


<p>Referenced by <a href="#a422417017bcd1f449e0fc7f64622ad42">fastIssueInstruction</a> and <a href="#a94ebe004dfbba2e68530d0125ed16293">issueInstructionImpl</a>.</p>

</div>
</div>

### resolveResourceMask() {#a9a795cf659d06359358c86c4ea0f64ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::ResourceManager::resolveResourceMask (uint64_t Mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae652ac0aafced9e7ef6249d3b4e50171">llvm::mca::getResourceStateIndex</a>.</p>

</div>
</div>

### setCustomStrategy() {#ac566e78d7358c6a1d6b94e5c448b3bcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::setCustomStrategy (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestrategy">ResourceStrategy</a> &gt; S, unsigned ResourceID)</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getNumUnits() {#a93d63cb46cdcebeed8a4c3b4af72dc93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::ResourceManager::getNumUnits (uint64_t ResourceID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>

</div>
</div>

### release() {#a834ce03ab17698b3131e79dc14471bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::release (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aa013ffaca9bcaadec118afaede71ab29">ResourceRef</a> &amp; RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>

</div>
</div>

### selectPipe() {#a5a464c1ec4304ed04bf623070c352b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceRef llvm::mca::ResourceManager::selectPipe (uint64_t ResourceID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>

</div>
</div>

### setCustomStrategyImpl() {#adc76507f1ad2988efd88c428e78e2cce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::setCustomStrategyImpl (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestrategy">ResourceStrategy</a> &gt; S, uint64_t ResourceMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>

</div>
</div>

### use() {#a6dc69bc3beffd768c0c6c7a65a19da66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceManager::use (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aa013ffaca9bcaadec118afaede71ab29">ResourceRef</a> &amp; RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AvailableBuffers {#a1714d0370fa0f51782d51fb6c0110aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceManager::AvailableBuffers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### AvailableProcResUnits {#aa0ee2217d4458262fc94a72926f2105a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceManager::AvailableProcResUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### BusyResources {#ad3dfa8e08ce4bcf0e534dac33e1ccfed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;ResourceRef, unsigned&gt; llvm::mca::ResourceManager::BusyResources</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### ProcResID2Mask {#a6a3fbf9aee5e9773016223f495f8e0c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;uint64_t, 8&gt; llvm::mca::ResourceManager::ProcResID2Mask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### ProcResUnitMask {#a553465efb94f9f5dc6f9fe1d8a24b346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceManager::ProcResUnitMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### ReservedBuffers {#a9c8918212c2767ae8d32b0f67a84d918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceManager::ReservedBuffers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### ReservedResourceGroups {#ac6bdaf2eb2b93791dd68c5ba9c5d48df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceManager::ReservedResourceGroups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### ResIndex2ProcResID {#ac23bfc0c963f295a65497666bfafd6f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 8&gt; llvm::mca::ResourceManager::ResIndex2ProcResID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### Resource2Groups {#af5bcd3de89fc81d686c6d5436437ad0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; llvm::mca::ResourceManager::Resource2Groups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### Resources {#a7bd0b5cdb01bdda564051785bf084ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;ResourceState&gt; &gt; llvm::mca::ResourceManager::Resources</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### Strategies {#add2f262593360499dfeff8472de4ac3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;ResourceStrategy&gt; &gt; llvm::mca::ResourceManager::Strategies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
