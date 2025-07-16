---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/resourcestate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ResourceState` Class Reference

<p>A processor resource descriptor. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::mca::ResourceState { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">llvm/MCA/HardwareUnits/ResourceManager.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0571f42d6bb1d3b1dd87654d84850a36">ResourceState</a> (const MCProcResourceDesc &amp;Desc, unsigned Index, uint64_t Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3531c482699ec5c57cda4fe5da71e437">getProcResourceID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73af25b2ef1f64bacd9159b4a6245bd">getResourceMask</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f30db123002f2e8d39b42dcd1c18570">getReadyMask</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48457031a32ddb64e79938d8025feadb">getBufferSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada9e3a6c57a59a8b3840a728bc96babb">isBuffered</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846b5bca981ffa2e1df9a8ba83d9bfae">isInOrder</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60da4b5907972b572cd9bfea05e873d2">isADispatchHazard</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is an in-order dispatch/issue resource. <a href="#a60da4b5907972b572cd9bfea05e873d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86068473600ec09094efb9a31296440">isReserved</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a544c4ac3f4c76f40043ddc6d27062c0d">setReserved</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46fb23efb212b10dc397a1657a7b9de">clearReserved</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ae2ace0d555c5682324d2381d2e9d1">isReady</a> (unsigned NumUnits=1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returs true if this resource is not reserved, and if there are at least <span class="doxyComputerOutput">NumUnits</span> available units. <a href="#a73ae2ace0d555c5682324d2381d2e9d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc30739c7dc3548e9ffd1c44f145cf1">getNumReadyUnits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afed8fbb52bd979bc9a12381779985c6e">isAResourceGroup</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83cebd4f01a9f5d634d1ed8609b2bd39">containsResource</a> (uint64_t ID) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2748d56f2089c41461ee67396540a4df">markSubResourceAsUsed</a> (uint64_t ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b5633dbc64f7b112191eb422c3ae0b">releaseSubResource</a> (uint64_t ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95b0a9105b457a084a856daae87e8101">getNumUnits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0337f8d8b79a284ebeb54749866da71f">isBufferAvailable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if there is an available slot in the resource buffer. <a href="#a0337f8d8b79a284ebeb54749866da71f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab156c820364f0655426202aca3ef989">reserveBuffer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserve a buffer slot. <a href="#aab156c820364f0655426202aca3ef989">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a328531d91fb4e878f50c00ed55bf1d79">releaseBuffer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Releases a slot in the buffer. <a href="#a328531d91fb4e878f50c00ed55bf1d79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa99bfd758109a4e146d24a336a8b7e4">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf33619af255e0dcc5354e2ba359cd89">isSubResourceReady</a> (uint64_t SubResMask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks for the availability of unit 'SubResMask' in the group. <a href="#aaf33619af255e0dcc5354e2ba359cd89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d986b91e554d8aecae6e4334adbba3a">ProcResourceDescIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An index to the <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc">MCProcResourceDesc</a> entry in the processor model. <a href="#a4d986b91e554d8aecae6e4334adbba3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b0a77f2903a18085fe2636c85bef00c">ResourceMask</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A resource mask. <a href="#a4b0a77f2903a18085fe2636c85bef00c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87fbb539ff37b06fb66d1f6cfcc15795">ResourceSizeMask</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A ProcResource can have multiple units. <a href="#a87fbb539ff37b06fb66d1f6cfcc15795">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70002b5ef6b35c0e992c99b78c182a9">ReadyMask</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mask of ready units. <a href="#af70002b5ef6b35c0e992c99b78c182a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab7ef0fd3a8f6ff66cd5bf8e70b009bf">BufferSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Buffered resources will have this field set to a positive number different than zero. <a href="#aab7ef0fd3a8f6ff66cd5bf8e70b009bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b05cd0b348538ffe35da47e293cc412">AvailableSlots</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Available slots in the buffer (zero, if this is not a buffered resource). <a href="#a5b05cd0b348538ffe35da47e293cc412">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae705da50d420f6ca973e0041dd2f22d8">Unavailable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This field is set if this resource is currently reserved. <a href="#ae705da50d420f6ca973e0041dd2f22d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76de91c646227b63a009ae0ca26eb018">IsAGroup</a></td>
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

<p>A processor resource descriptor.</p>


<p>There is an instance of this class for every processor resource defined by the machine scheduling model. Objects of class <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate">ResourceState</a> dynamically track the usage of processor resource units.</p>


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ResourceState() {#a0571f42d6bb1d3b1dd87654d84850a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::ResourceState::ResourceState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc">MCProcResourceDesc</a> &amp; Desc, unsigned Index, uint64_t Mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae652ac0aafced9e7ef6249d3b4e50171">llvm::mca::getResourceStateIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearReserved() {#af46fb23efb212b10dc397a1657a7b9de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceState::clearReserved ()</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a7a285124e918bd59e42a03792e0fee81">llvm::mca::ResourceManager::releaseResource</a>.</p>

</div>
</div>

### containsResource() {#a83cebd4f01a9f5d634d1ed8609b2bd39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::ResourceState::containsResource (uint64_t ID)</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a44427ff63cc2c81606a3f0175ac2b756">llvm::mca::InstructionError&lt; T &gt;::ID</a>.</p>

</div>
</div>

### dump() {#afa99bfd758109a4e146d24a336a8b7e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceState::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>.</p>

</div>
</div>

### getBufferSize() {#a48457031a32ddb64e79938d8025feadb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::mca::ResourceState::getBufferSize ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### getNumReadyUnits() {#a8bc30739c7dc3548e9ffd1c44f145cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceState::getNumReadyUnits ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a94ebe004dfbba2e68530d0125ed16293">llvm::mca::ResourceManager::issueInstructionImpl</a>.</p>

</div>
</div>

### getNumUnits() {#a95b0a9105b457a084a856daae87e8101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::ResourceState::getNumUnits ()</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>References <a href="#afed8fbb52bd979bc9a12381779985c6e">isAResourceGroup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a64c9d50d5dc3399ab4bca5159e3ea35b">llvm::mca::getStrategyFor</a>.</p>

</div>
</div>

### getProcResourceID() {#a3531c482699ec5c57cda4fe5da71e437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::ResourceState::getProcResourceID ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### getReadyMask() {#a1f30db123002f2e8d39b42dcd1c18570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceState::getReadyMask ()</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#aec872e4acf72f2b7fe8347d1c027b2b9">llvm::mca::ResourceManager::checkAvailability</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a64c9d50d5dc3399ab4bca5159e3ea35b">llvm::mca::getStrategyFor</a>.</p>

</div>
</div>

### getResourceMask() {#ae73af25b2ef1f64bacd9159b4a6245bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceState::getResourceMask ()</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### isADispatchHazard() {#a60da4b5907972b572cd9bfea05e873d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::ResourceState::isADispatchHazard ()</td>
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

<p>Returns true if this is an in-order dispatch/issue resource.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Referenced by <a href="#a0337f8d8b79a284ebeb54749866da71f">isBufferAvailable</a>, <a href="#a73ae2ace0d555c5682324d2381d2e9d1">isReady</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a7a285124e918bd59e42a03792e0fee81">llvm::mca::ResourceManager::releaseResource</a>.</p>

</div>
</div>

### isAResourceGroup() {#afed8fbb52bd979bc9a12381779985c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::ResourceState::isAResourceGroup ()</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#aec872e4acf72f2b7fe8347d1c027b2b9">llvm::mca::ResourceManager::checkAvailability</a>, <a href="#a95b0a9105b457a084a856daae87e8101">getNumUnits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a64c9d50d5dc3399ab4bca5159e3ea35b">llvm::mca::getStrategyFor</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a94ebe004dfbba2e68530d0125ed16293">llvm::mca::ResourceManager::issueInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a7a285124e918bd59e42a03792e0fee81">llvm::mca::ResourceManager::releaseResource</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a946efb5d7f623e1285039dadcab561a9">llvm::mca::ResourceManager::reserveResource</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a7d000778dc6adcdb34b656a83939800a">llvm::mca::ResourceManager::ResourceManager</a>.</p>

</div>
</div>

### isBufferAvailable() {#a0337f8d8b79a284ebeb54749866da71f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceStateEvent llvm::mca::ResourceState::isBufferAvailable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if there is an available slot in the resource buffer.</p>


<p>Returns RS_BUFFER_AVAILABLE if this is not a buffered resource, or if there is a slot available.</p>


<p>Returns RS_RESERVED if this buffered resource is a dispatch hazard, and it is reserved.</p>


<p>Returns RS_BUFFER_UNAVAILABLE if there are no available slots.</p>


<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="#a60da4b5907972b572cd9bfea05e873d2">isADispatchHazard</a>, <a href="#ada9e3a6c57a59a8b3840a728bc96babb">isBuffered</a>, <a href="#ad86068473600ec09094efb9a31296440">isReserved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072aa3f746cb41f05bc7d2405d8f261ad3b53">llvm::mca::RS_BUFFER_AVAILABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072aa31d38f37314ff7269028574355831c80">llvm::mca::RS_BUFFER_UNAVAILABLE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072aadc0c2c76e3c6a9189f1c720ed16abd2f">llvm::mca::RS_RESERVED</a>.</p>

</div>
</div>

### isBuffered() {#ada9e3a6c57a59a8b3840a728bc96babb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::ResourceState::isBuffered ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Referenced by <a href="#a0337f8d8b79a284ebeb54749866da71f">isBufferAvailable</a>.</p>

</div>
</div>

### isInOrder() {#a846b5bca981ffa2e1df9a8ba83d9bfae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::ResourceState::isInOrder ()</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### isReady() {#a73ae2ace0d555c5682324d2381d2e9d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::ResourceState::isReady (unsigned NumUnits=1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returs true if this resource is not reserved, and if there are at least <span class="doxyComputerOutput">NumUnits</span> available units.</p>

<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/resourcemanager-cpp">ResourceManager.cpp</a>.</p>


<p>References <a href="#a60da4b5907972b572cd9bfea05e873d2">isADispatchHazard</a>, <a href="#ad86068473600ec09094efb9a31296440">isReserved</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#aec872e4acf72f2b7fe8347d1c027b2b9">llvm::mca::ResourceManager::checkAvailability</a>.</p>

</div>
</div>

### isReserved() {#ad86068473600ec09094efb9a31296440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::ResourceState::isReserved ()</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Referenced by <a href="#a0337f8d8b79a284ebeb54749866da71f">isBufferAvailable</a>, <a href="#a73ae2ace0d555c5682324d2381d2e9d1">isReady</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a946efb5d7f623e1285039dadcab561a9">llvm::mca::ResourceManager::reserveResource</a>.</p>

</div>
</div>

### markSubResourceAsUsed() {#a2748d56f2089c41461ee67396540a4df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceState::markSubResourceAsUsed (uint64_t ID)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a44427ff63cc2c81606a3f0175ac2b756">llvm::mca::InstructionError&lt; T &gt;::ID</a>.</p>

</div>
</div>

### releaseBuffer() {#a328531d91fb4e878f50c00ed55bf1d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceState::releaseBuffer ()</td>
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

<p>Releases a slot in the buffer.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### releaseSubResource() {#a45b5633dbc64f7b112191eb422c3ae0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceState::releaseSubResource (uint64_t ID)</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a44427ff63cc2c81606a3f0175ac2b756">llvm::mca::InstructionError&lt; T &gt;::ID</a>.</p>

</div>
</div>

### reserveBuffer() {#aab156c820364f0655426202aca3ef989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::ResourceState::reserveBuffer ()</td>
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

<p>Reserve a buffer slot.</p>


<p>Returns true if the buffer is not full. It always returns true if BufferSize is set to zero.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### setReserved() {#a544c4ac3f4c76f40043ddc6d27062c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceState::setReserved ()</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a946efb5d7f623e1285039dadcab561a9">llvm::mca::ResourceManager::reserveResource</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isSubResourceReady() {#aaf33619af255e0dcc5354e2ba359cd89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::ResourceState::isSubResourceReady (uint64_t SubResMask)</td>
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

<p>Checks for the availability of unit 'SubResMask' in the group.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AvailableSlots {#a5b05cd0b348538ffe35da47e293cc412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::ResourceState::AvailableSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Available slots in the buffer (zero, if this is not a buffered resource).</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### BufferSize {#aab7ef0fd3a8f6ff66cd5bf8e70b009bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::mca::ResourceState::BufferSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Buffered resources will have this field set to a positive number different than zero.</p>


<p>A buffered resource behaves like a reservation station implementing its own buffer for out-of-order execution.</p>


<p>A BufferSize of 1 is used by scheduler resources that force in-order execution.</p>


<p>A BufferSize of 0 is used to model in-order issue/dispatch resources. Since in-order issue/dispatch resources don't implement buffers, dispatch events coincide with issue events. Also, no other instruction ca be dispatched/issue while this resource is in use. Only when all the "resource cycles" are consumed (after the issue event), a new instruction ca be dispatched.</p>


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### IsAGroup {#a76de91c646227b63a009ae0ca26eb018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::mca::ResourceState::IsAGroup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### ProcResourceDescIndex {#a4d986b91e554d8aecae6e4334adbba3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::mca::ResourceState::ProcResourceDescIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An index to the <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc">MCProcResourceDesc</a> entry in the processor model.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### ReadyMask {#af70002b5ef6b35c0e992c99b78c182a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceState::ReadyMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A mask of ready units.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### ResourceMask {#a4b0a77f2903a18085fe2636c85bef00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::mca::ResourceState::ResourceMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A resource mask.</p>


<p>This is generated by the tool with the help of function ‘<a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae1d3c5a1f43dcec43774a3767b41e447">mca::computeProcResourceMasks</a>` (see Support.h).</p>


<p><a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> ResourceMask only has one bit set if this resource state describes a processor resource unit (i.e. this is not a group). That means, we can quickly check if a resource is a group by simply counting the number of bits that are set in the mask.</p>


<p>The most significant bit of a mask (MSB) uniquely identifies a resource. Remaining bits are used to describe the composition of a group (Group).</p>


<p>Example (little endian): Resource | Mask | MSB | Group ------—+---------—+---------—+---------— A | 0b000001 | 0b000001 | 0b000000 | | | B | 0b000010 | 0b000010 | 0b000000 | | | C | 0b010000 | 0b010000 | 0b000000 | | | D | 0b110010 | 0b100000 | 0b010010</p>


<p>In this example, resources A, B and C are processor resource units. Only resource D is a group resource, and it contains resources B and C. That is because MSB(B) and MSB(C) are both contained within Group(D).</p>


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### ResourceSizeMask {#a87fbb539ff37b06fb66d1f6cfcc15795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::ResourceState::ResourceSizeMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A ProcResource can have multiple units.</p>


<p>For processor resource groups this field is a mask of contained resource units. It is obtained from ResourceMask by clearing the highest set bit. The number of resource units in a group can be simply computed as the population count of this field.</p>


<p>For normal (i.e. non-group) resources, the number of bits set in this mask is equivalent to the number of units declared by the processor model (see field 'NumUnits' in 'ProcResourceUnits').</p>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### Unavailable {#ae705da50d420f6ca973e0041dd2f22d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::ResourceState::Unavailable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This field is set if this resource is currently reserved.</p>


<p>Resources can be reserved for a number of cycles. Instructions can still be dispatched to reserved resources. However, istructions dispatched to a reserved resource cannot be issued to the underlying units (i.e. pipelines) until the resource is released.</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

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
