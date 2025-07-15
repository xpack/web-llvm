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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad12ec4f74c5d78414738ed3b6bdb363">fastIssueInstruction</a> (const InstrDesc &amp;Desc, SmallVectorImpl&lt; ResourceWithCycles &gt; &amp;Pipes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A resource mask. <a href="#aad12ec4f74c5d78414738ed3b6bdb363">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a965a906ee0ae3fe72d57f6e3a47a7695">issueInstructionImpl</a> (const InstrDesc &amp;Desc, SmallVectorImpl&lt; ResourceWithCycles &gt; &amp;Pipes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32dd6a9044edddba5266d1c62dd34db2">cycleEvent</a> (SmallVectorImpl&lt; ResourceRef &gt; &amp;ResourcesFreed)</td>
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

</table>

## Description {#details}

<p>A processor resource descriptor.</p>


<p>There is an instance of this class for every processor resource defined by the machine scheduling model. Objects of class <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate">ResourceState</a> dynamically track the usage of processor resource units.</p>


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>


<div class="doxySectionDef">

## Private Member Functions

### cycleEvent() {#a32dd6a9044edddba5266d1c62dd34db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceState::cycleEvent (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a961b7aeaca000c803c0f4b1df4d26c27">ResourceRef</a> &gt; &amp; ResourcesFreed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

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

### fastIssueInstruction() {#aad12ec4f74c5d78414738ed3b6bdb363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceState::fastIssueInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/instrdesc">InstrDesc</a> &amp; Desc, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; ResourceWithCycles &gt; &amp; Pipes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A resource mask.</p>


<p>This is generated by the tool with the help of function ‘<a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae1d3c5a1f43dcec43774a3767b41e447">mca::computeProcResourceMasks</a>` (see Support.h). / / <a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> ResourceMask only has one bit set if this resource state describes a / processor resource unit (i.e. this is not a group). That means, we can / quickly check if a resource is a group by simply counting the number of / bits that are set in the mask. / / The most significant bit of a mask (MSB) uniquely identifies a resource. / Remaining bits are used to describe the composition of a group (Group). / / Example (little endian): / Resource | Mask | MSB | Group / ------—+---------—+---------—+---------— / A | 0b000001 | 0b000001 | 0b000000 / | | | / B | 0b000010 | 0b000010 | 0b000000 / | | | / C | 0b010000 | 0b010000 | 0b000000 / | | | / D | 0b110010 | 0b100000 | 0b010010 / / In this example, resources A, B and C are processor resource units. / Only resource D is a group resource, and it contains resources B and C. / That is because MSB(B) and MSB(C) are both contained within Group(D). const uint64_t ResourceMask;</p>


<p>/ A ProcResource can have multiple units. / / For processor resource groups this field is a mask of contained resource / units. It is obtained from ResourceMask by clearing the highest set bit. / The number of resource units in a group can be simply computed as the / population count of this field. / / For normal (i.e. non-group) resources, the number of bits set in this mask / is equivalent to the number of units declared by the processor model (see / field 'NumUnits' in 'ProcResourceUnits'). uint64_t ResourceSizeMask;</p>


<p>/ A mask of ready units. uint64_t ReadyMask;</p>


<p>/ Buffered resources will have this field set to a positive number different / than zero. A buffered resource behaves like a reservation station / implementing its own buffer for out-of-order execution. / / A BufferSize of 1 is used by scheduler resources that force in-order / execution. / / A BufferSize of 0 is used to model in-order issue/dispatch resources. / Since in-order issue/dispatch resources don't implement buffers, dispatch / events coincide with issue events. / Also, no other instruction ca be dispatched/issue while this resource is / in use. Only when all the "resource cycles" are consumed (after the issue / event), a new instruction ca be dispatched. const int BufferSize;</p>


<p>/ Available slots in the buffer (zero, if this is not a buffered resource). unsigned AvailableSlots;</p>


<p>/ This field is set if this resource is currently reserved. / / Resources can be reserved for a number of cycles. / Instructions can still be dispatched to reserved resources. However, / istructions dispatched to a reserved resource cannot be issued to the / underlying units (i.e. pipelines) until the resource is released. bool Unavailable;</p>


<p>const bool IsAGroup;</p>


<p>/ Checks for the availability of unit 'SubResMask' in the group. bool isSubResourceReady(uint64_t SubResMask) const { return ReadyMask &amp; SubResMask; }</p>


<p>public: ResourceState(const MCProcResourceDesc &amp;Desc, unsigned Index, uint64_t Mask);</p>


<p>unsigned getProcResourceID() const { return ProcResourceDescIndex; } uint64_t getResourceMask() const { return ResourceMask; } uint64_t getReadyMask() const { return ReadyMask; } int getBufferSize() const { return BufferSize; }</p>


<p>bool isBuffered() const { return BufferSize &gt; 0; } bool isInOrder() const { return BufferSize == 1; }</p>


<p>/ Returns true if this is an in-order dispatch/issue resource. bool isADispatchHazard() const { return BufferSize == 0; } bool isReserved() const { return Unavailable; }</p>


<p>void setReserved() { Unavailable = true; } void clearReserved() { Unavailable = false; }</p>


<p>/ Returs true if this resource is not reserved, and if there are at least / <span class="doxyComputerOutput">NumUnits</span> available units. bool isReady(unsigned NumUnits = 1) const;</p>


<p>uint64_t getNumReadyUnits() const { return llvm::popcount(ReadyMask); }</p>


<p>bool isAResourceGroup() const { return IsAGroup; }</p>


<p>bool containsResource(uint64_t ID) const { return ResourceMask &amp; ID; }</p>


<p>void markSubResourceAsUsed(uint64_t ID) { assert(isSubResourceReady(ID)); ReadyMask ^= ID; }</p>


<p>void releaseSubResource(uint64_t ID) { assert(!isSubResourceReady(ID)); ReadyMask ^= ID; }</p>


<p>unsigned getNumUnits() const { return isAResourceGroup() ? 1U : llvm::popcount(ResourceSizeMask); }</p>


<p>/ Checks if there is an available slot in the resource buffer. / / Returns RS_BUFFER_AVAILABLE if this is not a buffered resource, or if / there is a slot available. / / Returns RS_RESERVED if this buffered resource is a dispatch hazard, and it / is reserved. / / Returns RS_BUFFER_UNAVAILABLE if there are no available slots. <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072a">ResourceStateEvent</a> isBufferAvailable() const;</p>


<p>/ Reserve a buffer slot. / / Returns true if the buffer is not full. / It always returns true if BufferSize is set to zero. bool reserveBuffer() { if (BufferSize &lt;= 0) return true;</p>


<p>–AvailableSlots; assert(AvailableSlots &lt;= static_cast&lt;unsigned&gt;(BufferSize)); return AvailableSlots; }</p>


<p>/ Releases a slot in the buffer. void releaseBuffer() { Ignore dispatch hazards or invalid buffer sizes. if (BufferSize &lt;= 0) return;</p>


<p>++AvailableSlots; assert(AvailableSlots &lt;= static_cast&lt;unsigned&gt;(BufferSize)); }</p>


<p>void dump() const;</p>


<p>};</p>


<p>/ A resource unit identifier. / / This is used to identify a specific processor resource unit using a pair / of indices where the 'first' index is a processor resource mask, and the / 'second' index is an index for a "sub-resource" (i.e. unit). typedef std::pair&lt;uint64_t, uint64_t&gt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a961b7aeaca000c803c0f4b1df4d26c27">ResourceRef</a>;</p>


<p>First: a <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc">MCProcResourceDesc</a> index identifying a buffered resource. Second: max number of buffer entries used in this resource. typedef std::pair&lt;unsigned, unsigned&gt; BufferUsageEntry;</p>


<p>/ A resource manager for processor resource units and groups. / / This class owns all the <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate">ResourceState</a> objects, and it is responsible for / acting on requests from a <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler">Scheduler</a> by updating the internal state of / <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate">ResourceState</a> objects. / This class doesn't know about instruction itineraries and functional units. / In future, it can be extended to support itineraries too through the same / public interface. class <a href="/web-llvm/docs/api/classes/llvm/resourcemanager">ResourceManager</a> { Set of resources available on the subtarget.</p>


<p>There is an instance of <a href="/web-llvm/docs/api/classes/llvm/mca/resourcestate">ResourceState</a> for every resource declared by the target scheduling model.</p>


<p>Elements of this vector are ordered by resource kind. In particular, resource units take precedence over resource groups.</p>


<p>The index of a processor resource in this vector depends on the value of its mask (see the description of field ResourceState::ResourceMask). In particular, it is computed as the position of the most significant bit set (MSB) in the mask plus one (since we want to ignore the invalid resource descriptor at index zero).</p>


<p>Example (little endian):</p>


<p>Resource | Mask | MSB | Index ------—+------—+------—+----— A | 0b00001 | 0b00001 | 1 | | | B | 0b00100 | 0b00100 | 3 | | | C | 0b10010 | 0b10000 | 5</p>


<p>The same index is also used to address elements within vector <span class="doxyComputerOutput">Strategies</span> and vector <span class="doxyComputerOutput">Resource2Groups</span>. std::vector&lt;std::unique_ptr&lt;ResourceState&gt;&gt; Resources; std::vector&lt;std::unique_ptr&lt;ResourceStrategy&gt;&gt; Strategies;</p>


<p>Used to quickly identify groups that own a particular resource unit. std::vector&lt;uint64_t&gt; Resource2Groups;</p>


<p>A table that maps processor resource IDs to processor resource masks. <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;uint64_t, 8&gt;</a> ProcResID2Mask;</p>


<p>A table that maps resource indices to actual processor resource IDs in the scheduling model. <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;unsigned, 8&gt;</a> ResIndex2ProcResID;</p>


<p>Keeps track of which resources are busy, and how many cycles are left before those become usable again. <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap&lt;ResourceRef, unsigned&gt;</a> BusyResources;</p>


<p>Set of processor resource units available on the target. uint64_t ProcResUnitMask;</p>


<p>Set of processor resource units that are available during this cycle. uint64_t AvailableProcResUnits;</p>


<p>Set of processor resources that are currently reserved. uint64_t ReservedResourceGroups;</p>


<p>Set of unavailable scheduler buffer resources. This is used internally to speedup <span class="doxyComputerOutput">canBeDispatched()</span> queries. uint64_t AvailableBuffers;</p>


<p>Set of dispatch hazard buffer resources that are currently unavailable. uint64_t ReservedBuffers;</p>


<p>Returns the actual resource unit that will be used. <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a961b7aeaca000c803c0f4b1df4d26c27">ResourceRef</a> selectPipe(uint64_t ResourceID);</p>


<p>void <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use(const ResourceRef &amp;RR)</a>; void <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">release(const ResourceRef &amp;RR)</a>;</p>


<p>unsigned getNumUnits(uint64_t ResourceID) const;</p>


<p>Overrides the selection strategy for the processor resource with the given mask. void setCustomStrategyImpl(std::unique_ptr&lt;ResourceStrategy&gt; S,
                             uint64_t ResourceMask);</p>


<p>public: ResourceManager(const MCSchedModel &amp;SM); virtual ~ResourceManager() = default;</p>


<p>Overrides the selection strategy for the resource at index ResourceID in the <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc">MCProcResourceDesc</a> table. void setCustomStrategy(std::unique_ptr&lt;ResourceStrategy&gt; S,
                         unsigned ResourceID) { assert(ResourceID &lt; ProcResID2Mask.size() &amp;&amp; "Invalid resource index in input!"); return setCustomStrategyImpl(std::move(S), ProcResID2Mask[ResourceID]); }</p>


<p>Returns RS_BUFFER_AVAILABLE if buffered resources are not reserved, and if there are enough available slots in the buffers. <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072a">ResourceStateEvent</a> canBeDispatched(uint64_t ConsumedBuffers) const;</p>


<p>Return the processor resource identifier associated to this Mask. unsigned resolveResourceMask(uint64_t Mask) const;</p>


<p>Acquires a slot from every buffered resource in mask <span class="doxyComputerOutput">ConsumedBuffers</span>. Units that are dispatch hazards (i.e. BufferSize=0) are marked as reserved. void reserveBuffers(uint64_t ConsumedBuffers);</p>


<p>Releases a slot from every buffered resource in mask <span class="doxyComputerOutput">ConsumedBuffers</span>. ConsumedBuffers is a bitmask of previously acquired buffers (using method <span class="doxyComputerOutput">reserveBuffers</span>). Units that are dispatch hazards (i.e. BufferSize=0) are not automatically unreserved by this method. void releaseBuffers(uint64_t ConsumedBuffers);</p>


<p>Reserve a processor resource. A reserved resource is not available for instruction issue until it is released. void reserveResource(uint64_t ResourceID);</p>


<p>Release a previously reserved processor resource. void releaseResource(uint64_t ResourceID);</p>


<p>Returns a zero mask if resources requested by <a href="/web-llvm/docs/api/namespaces/llvm/#a4de98a9acffcef5bb4b31862cb8c72ac">Desc</a> are all available during this cycle. It returns a non-zero mask value only if there are unavailable processor resources; each bit set in the mask represents a busy processor resource unit or a reserved processor resource group. uint64_t checkAvailability(const InstrDesc &amp;Desc) const;</p>


<p>uint64_t getProcResUnitMask() const { return ProcResUnitMask; } uint64_t getAvailableProcResUnits() const { return AvailableProcResUnits; }</p>


<p>using ResourceWithCycles = std::pair&lt;ResourceRef, ReleaseAtCycles&gt;;</p>


<p>void issueInstruction(const InstrDesc &amp;Desc,
                        SmallVectorImpl&lt;ResourceWithCycles&gt; &amp;Pipes) { if (Desc.HasPartiallyOverlappingGroups) return issueInstructionImpl(Desc, Pipes);</p>


<p>return fastIssueInstruction(Desc, Pipes); }</p>


<p>Selects pipeline resources consumed by an instruction. This method works under the assumption that used group resources don't partially overlap. The logic is guaranteed to find a valid resource unit schedule, no matter in which order individual uses are processed. For that reason, the vector of resource uses is simply (and quickly) processed in sequence. The resulting schedule is eventually stored into vector <span class="doxyComputerOutput">Pipes</span>.</p>


<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

### issueInstructionImpl() {#a965a906ee0ae3fe72d57f6e3a47a7695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::ResourceState::issueInstructionImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/instrdesc">InstrDesc</a> &amp; Desc, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; ResourceWithCycles &gt; &amp; Pipes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

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

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/resourcemanager-h">ResourceManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
