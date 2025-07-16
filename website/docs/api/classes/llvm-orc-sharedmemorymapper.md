---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/sharedmemorymapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SharedMemoryMapper` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::SharedMemoryMapper { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc87c1eedea4bfa8adc928caf64d0933">SharedMemoryMapper</a> (ExecutorProcessControl &amp;EPC, SymbolAddrs SAs, size_t PageSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eac18316db606c0b211c40950acc2fa">~SharedMemoryMapper</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae400b1b0e333e4fc52f2e621fdb24f45">getPageSize</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422f2a2c01a04dbb4fe4100fc74b90ca">reserve</a> (size_t NumBytes, OnReservedFunction OnReserved) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserves address space in executor process. <a href="#a422f2a2c01a04dbb4fe4100fc74b90ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8295d4ee787fed22f7a1b37c7b0a559c">prepare</a> (ExecutorAddr Addr, size_t ContentSize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides working memory. <a href="#a8295d4ee787fed22f7a1b37c7b0a559c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6776668e9d06d4ffccc140a13cd25095">initialize</a> (AllocInfo &amp;AI, OnInitializedFunction OnInitialized) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensures executor memory is synchronized with working copy memory, sends functions to be called after initilization and before deinitialization and applies memory protections Returns a unique address identifying the allocation. <a href="#a6776668e9d06d4ffccc140a13cd25095">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a0e809cf10b6a741b5b9d62698073b">deinitialize</a> (ArrayRef&lt; ExecutorAddr &gt; Allocations, OnDeinitializedFunction OnDeInitialized) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs previously specified deinitialization actions Executor addresses returned by initialize should be passed. <a href="#a49a0e809cf10b6a741b5b9d62698073b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c1571f24dc447307937d7a1c82ee8b">release</a> (ArrayRef&lt; ExecutorAddr &gt; Reservations, OnReleasedFunction OnRelease) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release address space acquired through <a href="#a422f2a2c01a04dbb4fe4100fc74b90ca">reserve()</a> <a href="#ac8c1571f24dc447307937d7a1c82ee8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e74776e73ef9eeeb3dc51000e186a2e">EPC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/sharedmemorymapper/symboladdrs">SymbolAddrs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9cf120b54e7471871aff2e0c363452">SAs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab945688ddaead02d10bec70a8100a56c">Mutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, Reservation &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2099221c2c43c05ccdc2ac7dadc1ce5">Reservations</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06089eee5987525eb2e7882496e328d">PageSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper">SharedMemoryMapper</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05efc99c84f85d88901dd71a716814dd">Create</a> (ExecutorProcessControl &amp;EPC, SymbolAddrs SAs)</td>
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


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SharedMemoryMapper() {#acc87c1eedea4bfa8adc928caf64d0933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SharedMemoryMapper::SharedMemoryMapper (<a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp; EPC, <a href="/web-llvm/docs/api/structs/llvm/orc/sharedmemorymapper/symboladdrs">SymbolAddrs</a> SAs, size_t PageSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SharedMemoryMapper() {#a4eac18316db606c0b211c40950acc2fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SharedMemoryMapper::~SharedMemoryMapper ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deinitialize() {#a49a0e809cf10b6a741b5b9d62698073b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SharedMemoryMapper::deinitialize (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt; Allocations, <a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper/#aedfe192af316b519758f8f400ff24ff5">OnDeinitializedFunction</a> OnDeInitialized)</td>
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

<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>.</p>

</div>
</div>

### getPageSize() {#ae400b1b0e333e4fc52f2e621fdb24f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::orc::SharedMemoryMapper::getPageSize ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

### initialize() {#a6776668e9d06d4ffccc140a13cd25095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SharedMemoryMapper::initialize (<a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo">AllocInfo</a> &amp; AI, <a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper/#ae546b70ffe0d3b8451b9b2a3163c4372">OnInitializedFunction</a> OnInitialized)</td>
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


<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/#aa83c8c10a9eb18cd233eed2ecf12ca71">llvm::orc::MemoryMapper::AllocInfo::Actions</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemoryfinalizerequest/#ac480f8342ad8500b7f9477ba74fd5ed2">llvm::orc::tpctypes::SharedMemoryFinalizeRequest::Actions</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#a291bd7c0717557dd244547b23c8c7c41">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#abdd6ae2070338087f3d5d54200d708d6afd565de81da1c94807c0b80840ba18b0">llvm::orc::Finalize</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/#a8ae25e2221d662f2fbffc49d0b172b3a">llvm::orc::MemoryMapper::AllocInfo::MappingBase</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#af8722c220368ae6ec29f1659a9db656d">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::RAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/#a6b6dcea60d496fc8de6d65188804b995">llvm::orc::MemoryMapper::AllocInfo::Segments</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemoryfinalizerequest/#a1cd77f9692f05fed6a1a9fa7b59da1e6">llvm::orc::tpctypes::SharedMemoryFinalizeRequest::Segments</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#a285451feed03fc082fba2259ac6f1f2d">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::Size</a>.</p>

</div>
</div>

### prepare() {#a8295d4ee787fed22f7a1b37c7b0a559c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * llvm::orc::SharedMemoryMapper::prepare (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> Addr, size_t ContentSize)</td>
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

<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### release() {#ac8c1571f24dc447307937d7a1c82ee8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SharedMemoryMapper::release (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt; Reservations, <a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper/#a002df15a1ca5b57f024af911d7854e90">OnReleasedFunction</a> OnRelease)</td>
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

<p>Release address space acquired through <a href="#a422f2a2c01a04dbb4fe4100fc74b90ca">reserve()</a></p>

<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae075c94db10b09d6d5876d32219eaf0d">llvm::errnoAsErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0799d74677708a87dee45acdd40bab2">llvm::mapWindowsError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### reserve() {#a422f2a2c01a04dbb4fe4100fc74b90ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SharedMemoryMapper::reserve (size_t NumBytes, <a href="/web-llvm/docs/api/classes/llvm/orc/memorymapper/#ae6b31499ac8e7d26c03092c14275d796">OnReservedFunction</a> OnReserved)</td>
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

<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae075c94db10b09d6d5876d32219eaf0d">llvm::errnoAsErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/blake3/#a9dbdb16a7c1e784048a1a7f65821f5be">llvm::BLAKE3::hash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0799d74677708a87dee45acdd40bab2">llvm::mapWindowsError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EPC {#a2e74776e73ef9eeeb3dc51000e186a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorProcessControl&amp; llvm::orc::SharedMemoryMapper::EPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

### Mutex {#ab945688ddaead02d10bec70a8100a56c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::SharedMemoryMapper::Mutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

### PageSize {#ae06089eee5987525eb2e7882496e328d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::SharedMemoryMapper::PageSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

### Reservations {#ab2099221c2c43c05ccdc2ac7dadc1ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;ExecutorAddr, Reservation&gt; llvm::orc::SharedMemoryMapper::Reservations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

### SAs {#abb9cf120b54e7471871aff2e0c363452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolAddrs llvm::orc::SharedMemoryMapper::SAs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#a05efc99c84f85d88901dd71a716814dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; SharedMemoryMapper &gt; &gt; llvm::orc::SharedMemoryMapper::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp; EPC, <a href="/web-llvm/docs/api/structs/llvm/orc/sharedmemorymapper/symboladdrs">SymbolAddrs</a> SAs)</td>
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



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/memorymapper-cpp">MemoryMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a2b6f374dc4eb2a7f84cc346e5630e132">llvm::sys::Process::getPageSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
