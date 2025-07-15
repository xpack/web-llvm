---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/inprocessmemorymapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InProcessMemoryMapper` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::InProcessMemoryMapper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">llvm/ExecutionEngine/Orc/MemoryMapper.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper">MemoryMapper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Manages mapping, content transfer and protections for JIT memory. <a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52011a66beed8160690bd4a1b830f1ae">AllocationMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, Allocation &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d0ae2a89b7c9917523860c3eafa8ee">ReservationMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; void *, Reservation &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83a0052e8954805eb391e3fbead2a069">InProcessMemoryMapper</a> (size_t PageSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a8a5be08a1b215a7da11ae9d55ad31b">~InProcessMemoryMapper</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9c425a42bde93665721fc7ecfcac4d4">getPageSize</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7567e026468fa261fb6186a2d30115ff">reserve</a> (size_t NumBytes, OnReservedFunction OnReserved) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserves address space in executor process. <a href="#a7567e026468fa261fb6186a2d30115ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a492e4d6b2bf660e7c499e22f85b72440">initialize</a> (AllocInfo &amp;AI, OnInitializedFunction OnInitialized) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensures executor memory is synchronized with working copy memory, sends functions to be called after initilization and before deinitialization and applies memory protections Returns a unique address identifying the allocation. <a href="#a492e4d6b2bf660e7c499e22f85b72440">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56d2316a6611ee7bf8958565aee64a2">prepare</a> (ExecutorAddr Addr, size_t ContentSize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides working memory. <a href="#ad56d2316a6611ee7bf8958565aee64a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac501a4fc8b8826d6451a9ae117ca3e0b">deinitialize</a> (ArrayRef&lt; ExecutorAddr &gt; Allocations, OnDeinitializedFunction OnDeInitialized) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs previously specified deinitialization actions Executor addresses returned by initialize should be passed. <a href="#ac501a4fc8b8826d6451a9ae117ca3e0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b7c908c1016860ed8c53965f8f167a">release</a> (ArrayRef&lt; ExecutorAddr &gt; Reservations, OnReleasedFunction OnRelease) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release address space acquired through <a href="#a7567e026468fa261fb6186a2d30115ff">reserve()</a> <a href="#ae7b7c908c1016860ed8c53965f8f167a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72fae1373890fc9f1995a1eb01ee7fb4">Mutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ReservationMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e35e9f5700bf0ee8113f3d78124f3e">Reservations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">AllocationMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f964305f91d5371b7a1e911bdb7279d">Allocations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897b969c171fa3c5a46c9029e0ecbac7">PageSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper">InProcessMemoryMapper</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace0850e56331e89848ec64c74dada4bd">Create</a> ()</td>
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


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AllocationMap {#a52011a66beed8160690bd4a1b830f1ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::InProcessMemoryMapper::AllocationMap =  DenseMap&lt;ExecutorAddr, Allocation&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

### ReservationMap {#ae0d0ae2a89b7c9917523860c3eafa8ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::InProcessMemoryMapper::ReservationMap =  DenseMap&lt;void *, Reservation&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InProcessMemoryMapper() {#a83a0052e8954805eb391e3fbead2a069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::InProcessMemoryMapper::InProcessMemoryMapper (size_t PageSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InProcessMemoryMapper() {#a9a8a5be08a1b215a7da11ae9d55ad31b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::InProcessMemoryMapper::~InProcessMemoryMapper ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a8adb0ae35f7e95c960c86cfe19bc7215">llvm::orc::ExecutorAddr::fromPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deinitialize() {#ac501a4fc8b8826d6451a9ae117ca3e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProcessMemoryMapper::deinitialize (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt; Allocations, <a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper/#aedfe192af316b519758f8f400ff24ff5">OnDeinitializedFunction</a> OnDeInitialized)</td>
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

<p>Runs previously specified deinitialization actions Executor addresses returned by initialize should be passed.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a548f317b89dc0bba738b89e5ce791395a02cae455b05abf1bfb1de69095e66417">llvm::sys::Memory::MF_READ</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a548f317b89dc0bba738b89e5ce791395a83e34a8267f7acd88563e9d5a3ee7c25">llvm::sys::Memory::MF_WRITE</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#ae27409ddee7e191f33392283ca826703">llvm::sys::Memory::protectMappedMemory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a8263d385de2b406acf8dbef9b0993cc9">llvm::orc::shared::runDeallocActions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ae7b7c908c1016860ed8c53965f8f167a">release</a>.</p>

</div>
</div>

### getPageSize() {#ad9c425a42bde93665721fc7ecfcac4d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::orc::InProcessMemoryMapper::getPageSize ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

### initialize() {#a492e4d6b2bf660e7c499e22f85b72440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProcessMemoryMapper::initialize (<a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo">AllocInfo</a> &amp; AI, <a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper/#ae546b70ffe0d3b8451b9b2a3163c4372">OnInitializedFunction</a> OnInitialized)</td>
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

<p>Ensures executor memory is synchronized with working copy memory, sends functions to be called after initilization and before deinitialization and applies memory protections Returns a unique address identifying the allocation.</p>


<p>This address should be passed to deinitialize to run deallocation actions (and reset permissions where possible).</p>


<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/#aa83c8c10a9eb18cd233eed2ecf12ca71">llvm::orc::MemoryMapper::AllocInfo::Actions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a953feeff1e20f40677fb7f77c073b3be">llvm::orc::Exec</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a5cfd4d2a8227a3f9ca0667f42f05f20b">llvm::sys::Memory::InvalidateInstructionCache</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/#a8ae25e2221d662f2fbffc49d0b172b3a">llvm::orc::MemoryMapper::AllocInfo::MappingBase</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#ae27409ddee7e191f33392283ca826703">llvm::sys::Memory::protectMappedMemory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#aa02467cf9213727cd36bce6f59653e5b">llvm::orc::shared::runFinalizeActions</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/#a6b6dcea60d496fc8de6d65188804b995">llvm::orc::MemoryMapper::AllocInfo::Segments</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac28fc72cfcd4ee10f9f913aa2969bc45">llvm::orc::toSysMemoryProtectionFlags</a>.</p>

</div>
</div>

### prepare() {#ad56d2316a6611ee7bf8958565aee64a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * llvm::orc::InProcessMemoryMapper::prepare (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> Addr, size_t ContentSize)</td>
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

<p>Provides working memory.</p>

<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a>.</p>

</div>
</div>

### release() {#ae7b7c908c1016860ed8c53965f8f167a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProcessMemoryMapper::release (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt; Reservations, <a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper/#a002df15a1ca5b57f024af911d7854e90">OnReleasedFunction</a> OnRelease)</td>
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

<p>Release address space acquired through <a href="#a7567e026468fa261fb6186a2d30115ff">reserve()</a></p>

<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="#ac501a4fc8b8826d6451a9ae117ca3e0b">deinitialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a042d24349a4b6a5ce475309cce529ae0">llvm::sys::Memory::releaseMappedMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### reserve() {#a7567e026468fa261fb6186a2d30115ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProcessMemoryMapper::reserve (size_t NumBytes, <a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper/#ae6b31499ac8e7d26c03092c14275d796">OnReservedFunction</a> OnReserved)</td>
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

<p>Reserves address space in executor process.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a1326dd13b23711e68ade413fbc57b9f6">llvm::sys::Memory::allocateMappedMemory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a8adb0ae35f7e95c960c86cfe19bc7215">llvm::orc::ExecutorAddr::fromPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a548f317b89dc0bba738b89e5ce791395a02cae455b05abf1bfb1de69095e66417">llvm::sys::Memory::MF_READ</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a548f317b89dc0bba738b89e5ce791395a83e34a8267f7acd88563e9d5a3ee7c25">llvm::sys::Memory::MF_WRITE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocations {#a0f964305f91d5371b7a1e911bdb7279d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocationMap llvm::orc::InProcessMemoryMapper::Allocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

### Mutex {#a72fae1373890fc9f1995a1eb01ee7fb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::InProcessMemoryMapper::Mutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

### PageSize {#a897b969c171fa3c5a46c9029e0ecbac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::InProcessMemoryMapper::PageSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

### Reservations {#a84e35e9f5700bf0ee8113f3d78124f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReservationMap llvm::orc::InProcessMemoryMapper::Reservations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#ace0850e56331e89848ec64c74dada4bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; InProcessMemoryMapper &gt; &gt; llvm::orc::InProcessMemoryMapper::Create ()</td>
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



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a2b6f374dc4eb2a7f84cc346e5630e132">llvm::sys::Process::getPageSize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
