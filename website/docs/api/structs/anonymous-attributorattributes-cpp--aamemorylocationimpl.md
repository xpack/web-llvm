---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AAMemoryLocationImpl` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamemorylocation">AAMemoryLocation</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract interface for all memory location attributes (readnone/argmemonly/inaccessiblememonly/inaccessibleorargmemonly). <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationcallsite">AAMemoryLocationCallSite</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AAMemoryLocation attribute for call sites. <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationcallsite/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction">AAMemoryLocationFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> to represent the memory behavior function attributes. <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d832b084d7370e7b94d21bb046287cb">AccessSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/accessinfo">AccessInfo</a>, 2, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/accessinfo">AccessInfo</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping from <em>single</em> memory location kinds, e.g., LOCAL_MEM with the value of NO_LOCAL_MEM, to the accesses encountered for this memory kind. <a href="#a4d832b084d7370e7b94d21bb046287cb">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14fd1a0c7ba79d015f0d48a648e1c74e">AAMemoryLocationImpl</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd528d765c89243ad506dbed2416b21f">~AAMemoryLocationImpl</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a591478b4b082b96804160de6e9d26356">initialize</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::initialize(...). <a href="#a591478b4b082b96804160de6e9d26356">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8df2e20241276fa840a50aaf747a059e">getDeducedAttributes</a> (Attributor &amp;A, LLVMContext &amp;Ctx, SmallVectorImpl&lt; Attribute &gt; &amp;Attrs) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::getDeducedAttributes(...). <a href="#a8df2e20241276fa840a50aaf747a059e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9971c8a3647ef1b5439ed7cd18aee749">manifest</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::manifest(...). <a href="#a9971c8a3647ef1b5439ed7cd18aee749">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc7a4a81ba257d29a226a6f27a29a654">checkForAllAccessesToMemoryKind</a> (function_ref&lt; bool(const Instruction *, const Value *, AccessKind, MemoryLocationsKind)&gt; Pred, MemoryLocationsKind RequestedMLK) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AAMemoryLocation::checkForAllAccessesToMemoryKind(...). <a href="#adc7a4a81ba257d29a226a6f27a29a654">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93339349de364716175a03098d94d44f">indicatePessimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that the abstract state should converge to the pessimistic state. <a href="#a93339349de364716175a03098d94d44f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58d962e3d29a81e1cdd18243bf6c71d3">categorizeArgumentPointerLocations</a> (Attributor &amp;A, CallBase &amp;CB, AAMemoryLocation::StateType &amp;AccessedLocs, bool &amp;Changed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Categorize the pointer arguments of CB that might access memory in AccessedLoc and update the state and access map accordingly. <a href="#a58d962e3d29a81e1cdd18243bf6c71d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#acffe374fb52ac7da0511285fdf18db3f">AAMemoryLocation::MemoryLocationsKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2c6df05bd2236b9d36680de5e09b78a">categorizeAccessedLocations</a> (Attributor &amp;A, Instruction &amp;I, bool &amp;Changed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the kind(s) of location that may be accessed by <span class="doxyComputerOutput">V</span>. <a href="#ae2c6df05bd2236b9d36680de5e09b78a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ace2d4d5ab8dffea597c39bc129d90f7f">AccessKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d3d6ffe937a44d192abca0e8b8611c">getAccessKindFromInst</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the access kind as determined by <span class="doxyComputerOutput">I</span>. <a href="#a57d3d6ffe937a44d192abca0e8b8611c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a781a14b565c3dbb6f7b9890c5eface01">updateStateAndAccessesMap</a> (AAMemoryLocation::StateType &amp;State, MemoryLocationsKind MLK, const Instruction *I, const Value *Ptr, bool &amp;Changed, AccessKind AK=READ_WRITE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the state <span class="doxyComputerOutput">State</span> and the AccessKind2Accesses given that <span class="doxyComputerOutput">I</span> is an access of kind <span class="doxyComputerOutput">AK</span> to a <span class="doxyComputerOutput">MLK</span> memory location with the access pointer <span class="doxyComputerOutput">Ptr</span>. <a href="#a781a14b565c3dbb6f7b9890c5eface01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6982073fb3620dd727922e78e140af8f">categorizePtrValue</a> (Attributor &amp;A, const Instruction &amp;I, const Value &amp;Ptr, AAMemoryLocation::StateType &amp;State, bool &amp;Changed, unsigned AccessAS=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the underlying locations kinds for <span class="doxyComputerOutput">Ptr</span>, e.g., globals or arguments, and update the state and access map accordingly. <a href="#a6982073fb3620dd727922e78e140af8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="#a4d832b084d7370e7b94d21bb046287cb">AccessSet</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a157580cd43622bf53270856bf51da098">llvm::CTLog2</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737a9cac5c2e512a4b66789775333f4b5d53">VALID_STATE</a> &gt;()&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad35cdc311249134997ad115817c6bc56">AccessKind2Accesses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39cbd37618b0078f9279ccbf0851e845">Allocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to allocate access sets. <a href="#a39cbd37618b0078f9279ccbf0851e845">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad06b99b6c5abffb1da312f75775f2f08">getKnownStateFromValue</a> (Attributor &amp;A, const IRPosition &amp;IRP, BitIntegerState &amp;State, bool IgnoreSubsumingPositions=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the memory behavior information encoded in the IR for <span class="doxyComputerOutput">IRP</span>. <a href="#ad06b99b6c5abffb1da312f75775f2f08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 8353 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### AccessSet {#a4d832b084d7370e7b94d21bb046287cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::AccessSet =  SmallSet&lt;AccessInfo, 2, AccessInfo&gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping from <em>single</em> memory location kinds, e.g., LOCAL_MEM with the value of NO_LOCAL_MEM, to the accesses encountered for this memory kind.</p>

<p>Definition at line 8546 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AAMemoryLocationImpl() {#a14fd1a0c7ba79d015f0d48a648e1c74e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::AAMemoryLocationImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 8355 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a660dfbde897cf25a66779982ac229d5f">llvm::AAMemoryLocation::AAMemoryLocation</a>, <a href="#ad35cdc311249134997ad115817c6bc56">AccessKind2Accesses</a> and <a href="#a39cbd37618b0078f9279ccbf0851e845">Allocator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationcallsite/#aaf55feb30f3adcb01e00e08b81208d35">anonymous{AttributorAttributes.cpp}::AAMemoryLocationCallSite::AAMemoryLocationCallSite</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#a4b54badde15a6d2fb25316b128b53914">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::AAMemoryLocationFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AAMemoryLocationImpl() {#acd528d765c89243ad506dbed2416b21f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::~AAMemoryLocationImpl ()</td>
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



<p>Definition at line 8360 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="#ad35cdc311249134997ad115817c6bc56">AccessKind2Accesses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### checkForAllAccessesToMemoryKind() {#adc7a4a81ba257d29a226a6f27a29a654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::checkForAllAccessesToMemoryKind (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ace2d4d5ab8dffea597c39bc129d90f7f">AccessKind</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#acffe374fb52ac7da0511285fdf18db3f">MemoryLocationsKind</a>)&gt; Pred, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#acffe374fb52ac7da0511285fdf18db3f">MemoryLocationsKind</a> RequestedMLK)</td>
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

<p>See AAMemoryLocation::checkForAllAccessesToMemoryKind(...).</p>

<p>Definition at line 8474 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="#ad35cdc311249134997ad115817c6bc56">AccessKind2Accesses</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ad7370cc538424a0e12fd632cb076c14c">llvm::AAMemoryLocation::getAssumedNotAccessedLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#a160d75d0c1abdc58fe6a377f6f8ddd4f">llvm::IntegerStateBase&lt; uint32_t, BestState, 0 &gt;::isValidState</a> and <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737ad3983885c932078fb829f29d2b7fed01">llvm::AAMemoryLocation::NO_LOCATIONS</a>.</p>

</div>
</div>

### getDeducedAttributes() {#a8df2e20241276fa840a50aaf747a059e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getDeducedAttributes (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &gt; &amp; Attrs)</td>
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

<p>See AbstractAttribute::getDeducedAttributes(...).</p>

<p>Definition at line 8436 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a5288b2ba178703d9e1f24a5d3708f594">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::argMemOnly</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#aea16db681aa18f4eded0015e284fdfe5">llvm::IRPosition::getPositionKind</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adaf42001b3cc4c8c631902cbb48106d5">llvm::Attribute::getWithMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a5cba4a49c183c6c2f6168be64f04a7b9">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::inaccessibleMemOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#ad341f584befc40ff0aefca99682baf7c">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::inaccessibleOrArgMemOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a53f576f97e0dfa8314afb16bd74a76d0aa823f70d88660d88196943a3f09301da">llvm::IRPosition::IRP_FUNCTION</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#af6e57f7a255f09243d9c303563c08ceb">llvm::AAMemoryLocation::isAssumedArgMemOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a876121bc7d9e565f5627b2350d643c64">llvm::AAMemoryLocation::isAssumedInaccessibleMemOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#aa6830f20bec5f8746595c497d5c3c4ed">llvm::AAMemoryLocation::isAssumedInaccessibleOrArgMemOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ae336b602cf0a89b2fa9551663c6f3295">llvm::AAMemoryLocation::isAssumedReadNone</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#af04065f3c729719471689b08089942f3">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::none</a>.</p>


<p>Referenced by <a href="#a9971c8a3647ef1b5439ed7cd18aee749">manifest</a>.</p>

</div>
</div>

### indicatePessimisticFixpoint() {#a93339349de364716175a03098d94d44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::indicatePessimisticFixpoint ()</td>
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

<p>Indicate that the abstract state should converge to the pessimistic state.</p>


<p>This will usually revert the optimistically assumed state to the known to be true state.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>ChangeStatus::CHANGED as the assumed value may change.</p></dd>
</dl>


<p>Definition at line 8501 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a57d3d6ffe937a44d192abca0e8b8611c">getAccessKindFromInst</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#a3eddb71da33fdca7d23f5e623a914290">llvm::IntegerStateBase&lt; uint32_t, BestState, 0 &gt;::getKnown</a>, <a href="/web-llvm/docs/api/structs/llvm/statewrapper/#aa83a3107fcf157e652c6be8fa548b893">llvm::StateWrapper&lt; BitIntegerState&lt; uint32_t, 511 &gt;, AbstractAttribute &gt;::getState</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#ac61c038186769d32f4f8c10168367965">llvm::AbstractState::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737ad3983885c932078fb829f29d2b7fed01">llvm::AAMemoryLocation::NO_LOCATIONS</a> and <a href="#a781a14b565c3dbb6f7b9890c5eface01">updateStateAndAccessesMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationcallsite/#a36ef96efb68b331087c86a5c9920173c">anonymous{AttributorAttributes.cpp}::AAMemoryLocationCallSite::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#a4de16ddc7d968804ec058444ee4145fd">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::updateImpl</a>.</p>

</div>
</div>

### initialize() {#a591478b4b082b96804160de6e9d26356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::initialize (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AbstractAttribute::initialize(...).</p>

<p>Definition at line 8369 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737a4dd21df945eb0ef4d3eaa8137eb7a98a">llvm::AAMemoryLocation::BEST_STATE</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="#ad06b99b6c5abffb1da312f75775f2f08">getKnownStateFromValue</a>, <a href="/web-llvm/docs/api/structs/llvm/statewrapper/#aa83a3107fcf157e652c6be8fa548b893">llvm::StateWrapper&lt; BitIntegerState&lt; uint32_t, 511 &gt;, AbstractAttribute &gt;::getState</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a63f1f9078e9f43f6ac08ac9e1e9b4a41">llvm::AbstractAttribute::initialize</a> and <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a6e0463fb784adc7b2cef8dabb69dad32">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::intersectAssumedBits</a>.</p>

</div>
</div>

### manifest() {#a9971c8a3647ef1b5439ed7cd18aee749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::manifest (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AbstractAttribute::manifest(...).</p>

<p>Definition at line 8458 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a9f40f87a556db81bd2403007b83acce7">llvm::IRPosition::getAnchorValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a8df2e20241276fa840a50aaf747a059e">getDeducedAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adaf42001b3cc4c8c631902cbb48106d5">llvm::Attribute::getWithMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### categorizeAccessedLocations() {#ae2c6df05bd2236b9d36680de5e09b78a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMemoryLocation::MemoryLocationsKind anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeAccessedLocations (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, bool &amp; Changed)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the kind(s) of location that may be accessed by <span class="doxyComputerOutput">V</span>.</p>

<p>Definition at line 8558 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a660dfbde897cf25a66779982ac229d5f">llvm::AAMemoryLocation::AAMemoryLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#aeef35bb007616add7418161b0313b56b">llvm::IRPosition::callsite_function</a>, <a href="#a58d962e3d29a81e1cdd18243bf6c71d3">categorizeArgumentPointerLocations</a>, <a href="#a6982073fb3620dd727922e78e140af8f">categorizePtrValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a57d3d6ffe937a44d192abca0e8b8611c">getAccessKindFromInst</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a37f5c90d6e9853a204b4ca1da2317c66">llvm::AAMemoryLocation::getMemoryLocationsAsStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54b19432f9c7d4df0f2f2307175f73e4">llvm::getPointerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#afc0831ad69241e3cde373281a1024848">llvm::AAMemoryLocation::inverseLocation</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737ae2f2e5630a82d0153e2369b9e8290b6b">llvm::AAMemoryLocation::NO_ARGUMENT_MEM</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737a8bd4fe34d8c924ec42c22a5156f9221d">llvm::AAMemoryLocation::NO_GLOBAL_MEM</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737a8540c0ac516fe3b3e9ac52d378537f41">llvm::AAMemoryLocation::NO_INACCESSIBLE_MEM</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737ad3983885c932078fb829f29d2b7fed01">llvm::AAMemoryLocation::NO_LOCATIONS</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737afd32faf24ee03f6bc85e632020569048">llvm::AAMemoryLocation::NO_UNKOWN_MEM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="#a781a14b565c3dbb6f7b9890c5eface01">updateStateAndAccessesMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#a4de16ddc7d968804ec058444ee4145fd">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::updateImpl</a>.</p>

</div>
</div>

### categorizeArgumentPointerLocations() {#a58d962e3d29a81e1cdd18243bf6c71d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeArgumentPointerLocations (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, AAMemoryLocation::StateType &amp; AccessedLocs, bool &amp; Changed)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Categorize the pointer arguments of CB that might access memory in AccessedLoc and update the state and access map accordingly.</p>

<p>Definition at line 8552 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a4c17a71e75898bbc42578a1c0b94c6b6">llvm::IRPosition::callsite_argument</a>, <a href="#a6982073fb3620dd727922e78e140af8f">categorizePtrValue</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab03652069eab17006c51f00c261a6a44">llvm::Type::isPtrOrPtrVectorTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>.</p>


<p>Referenced by <a href="#ae2c6df05bd2236b9d36680de5e09b78a">categorizeAccessedLocations</a>.</p>

</div>
</div>

### categorizePtrValue() {#a6982073fb3620dd727922e78e140af8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizePtrValue (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; Ptr, AAMemoryLocation::StateType &amp; State, bool &amp; Changed, unsigned AccessAS=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the underlying locations kinds for <span class="doxyComputerOutput">Ptr</span>, e.g., globals or arguments, and update the state and access map accordingly.</p>

<p>Definition at line 8590 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a22b55f73ab4057a8c3da9f32bd582f4b">llvm::IRPosition::callsite_returned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a0ab72bc360a96141393d6ff9f1af7511acb17869fe51048b5a5c4c6106551a255">llvm::AA::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a57d3d6ffe937a44d192abca0e8b8611c">getAccessKindFromInst</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a054de50dbf11b87063f6a32f3bccee80">llvm::IRPosition::getAssociatedFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a37f5c90d6e9853a204b4ca1da2317c66">llvm::AAMemoryLocation::getMemoryLocationsAsStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ae8abeaeed2f11072b2d064fe70510e9f">llvm::AA::hasAssumedIRAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ac85851126814105f4a92b699293e4141a5c330ebe62fe7984f41ec28c822a869a">llvm::AA::Intraprocedural</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#aba7baf8e2e8dff3bb7152c6ffeb52fb8">llvm::AA::isGPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed2c5dd2a303159f87771db83f54352b">llvm::isIdentifiedObject</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737ae2f2e5630a82d0153e2369b9e8290b6b">llvm::AAMemoryLocation::NO_ARGUMENT_MEM</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737af3f5a89da741bc5d46d9c5c13ae4bd52">llvm::AAMemoryLocation::NO_GLOBAL_EXTERNAL_MEM</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737a5bc229053d97809b7320418384ae49b2">llvm::AAMemoryLocation::NO_GLOBAL_INTERNAL_MEM</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737a3cd674c8b8c557b19cea3e0a6c4eb9a4">llvm::AAMemoryLocation::NO_LOCAL_MEM</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737ad3983885c932078fb829f29d2b7fed01">llvm::AAMemoryLocation::NO_LOCATIONS</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737a5702b1d175e7a1236d500fc64a1207bf">llvm::AAMemoryLocation::NO_MALLOCED_MEM</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737afd32faf24ee03f6bc85e632020569048">llvm::AAMemoryLocation::NO_UNKOWN_MEM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b03ed78a8e299bde6d26a8793cd4e06">llvm::NullPointerIsDefined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#a781a14b565c3dbb6f7b9890c5eface01">updateStateAndAccessesMap</a> and <a href="/web-llvm/docs/api/structs/llvm/irposition/#a3bee165465962ee97307066da4f0fb13">llvm::IRPosition::value</a>.</p>


<p>Referenced by <a href="#ae2c6df05bd2236b9d36680de5e09b78a">categorizeAccessedLocations</a> and <a href="#a58d962e3d29a81e1cdd18243bf6c71d3">categorizeArgumentPointerLocations</a>.</p>

</div>
</div>

### getAccessKindFromInst() {#a57d3d6ffe937a44d192abca0e8b8611c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccessKind anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getAccessKindFromInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the access kind as determined by <span class="doxyComputerOutput">I</span>.</p>

<p>Definition at line 8561 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ace2d4d5ab8dffea597c39bc129d90f7faed185f46b5cbd4dad3125978f8e69e6b">llvm::AAMemoryLocation::NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ace2d4d5ab8dffea597c39bc129d90f7faf8d236460bf15db958f25e6c7a258897">llvm::AAMemoryLocation::READ</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ace2d4d5ab8dffea597c39bc129d90f7fa02060fba95d9f2779f0d05683b601c24">llvm::AAMemoryLocation::READ_WRITE</a> and <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ace2d4d5ab8dffea597c39bc129d90f7fa5f6f5c92d79526533958cfb066ec63bc">llvm::AAMemoryLocation::WRITE</a>.</p>


<p>Referenced by <a href="#ae2c6df05bd2236b9d36680de5e09b78a">categorizeAccessedLocations</a>, <a href="#a6982073fb3620dd727922e78e140af8f">categorizePtrValue</a>, <a href="#a93339349de364716175a03098d94d44f">indicatePessimisticFixpoint</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationcallsite/#a36ef96efb68b331087c86a5c9920173c">anonymous{AttributorAttributes.cpp}::AAMemoryLocationCallSite::updateImpl</a>.</p>

</div>
</div>

### updateStateAndAccessesMap() {#a781a14b565c3dbb6f7b9890c5eface01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::updateStateAndAccessesMap (AAMemoryLocation::StateType &amp; State, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#acffe374fb52ac7da0511285fdf18db3f">MemoryLocationsKind</a> MLK, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, bool &amp; Changed, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ace2d4d5ab8dffea597c39bc129d90f7f">AccessKind</a> AK=<a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ace2d4d5ab8dffea597c39bc129d90f7fa02060fba95d9f2779f0d05683b601c24">READ_WRITE</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the state <span class="doxyComputerOutput">State</span> and the AccessKind2Accesses given that <span class="doxyComputerOutput">I</span> is an access of kind <span class="doxyComputerOutput">AK</span> to a <span class="doxyComputerOutput">MLK</span> memory location with the access pointer <span class="doxyComputerOutput">Ptr</span>.</p>

<p>Definition at line 8573 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="#ad35cdc311249134997ad115817c6bc56">AccessKind2Accesses</a>, <a href="#a39cbd37618b0078f9279ccbf0851e845">Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737ad3983885c932078fb829f29d2b7fed01">llvm::AAMemoryLocation::NO_LOCATIONS</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737afd32faf24ee03f6bc85e632020569048">llvm::AAMemoryLocation::NO_UNKOWN_MEM</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ace2d4d5ab8dffea597c39bc129d90f7fa02060fba95d9f2779f0d05683b601c24">llvm::AAMemoryLocation::READ_WRITE</a>.</p>


<p>Referenced by <a href="#ae2c6df05bd2236b9d36680de5e09b78a">categorizeAccessedLocations</a>, <a href="#a6982073fb3620dd727922e78e140af8f">categorizePtrValue</a>, <a href="#a93339349de364716175a03098d94d44f">indicatePessimisticFixpoint</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationcallsite/#a36ef96efb68b331087c86a5c9920173c">anonymous{AttributorAttributes.cpp}::AAMemoryLocationCallSite::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AccessKind2Accesses {#ad35cdc311249134997ad115817c6bc56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;AccessSet *, llvm::CTLog2&lt;VALID_STATE&gt;()&gt; anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::AccessKind2Accesses</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 8547 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="#a14fd1a0c7ba79d015f0d48a648e1c74e">AAMemoryLocationImpl</a>, <a href="#adc7a4a81ba257d29a226a6f27a29a654">checkForAllAccessesToMemoryKind</a>, <a href="#a781a14b565c3dbb6f7b9890c5eface01">updateStateAndAccessesMap</a> and <a href="#acd528d765c89243ad506dbed2416b21f">~AAMemoryLocationImpl</a>.</p>

</div>
</div>

### Allocator {#a39cbd37618b0078f9279ccbf0851e845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator&amp; anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::Allocator</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to allocate access sets.</p>

<p>Definition at line 8595 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="#a14fd1a0c7ba79d015f0d48a648e1c74e">AAMemoryLocationImpl</a> and <a href="#a781a14b565c3dbb6f7b9890c5eface01">updateStateAndAccessesMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getKnownStateFromValue() {#ad06b99b6c5abffb1da312f75775f2f08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate">BitIntegerState</a> &amp; State, bool IgnoreSubsumingPositions=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the memory behavior information encoded in the IR for <span class="doxyComputerOutput">IRP</span>.</p>

<p>Definition at line 8376 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a513f55e474dba6d6c2507997e9920b6d">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::doesNotAccessMemory</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a9f40f87a556db81bd2403007b83acce7">llvm::IRPosition::getAnchorValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a76a16756c4c05000711a5ab6c68756dc">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::getModRef</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adaf42001b3cc4c8c631902cbb48106d5">llvm::Attribute::getWithMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#afc0831ad69241e3cde373281a1024848">llvm::AAMemoryLocation::inverseLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737ae2f2e5630a82d0153e2369b9e8290b6b">llvm::AAMemoryLocation::NO_ARGUMENT_MEM</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737ab78c83bfe8ae55b0ce8b10773f244443">llvm::AAMemoryLocation::NO_CONST_MEM</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737a8540c0ac516fe3b3e9ac52d378537f41">llvm::AAMemoryLocation::NO_INACCESSIBLE_MEM</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737a3cd674c8b8c557b19cea3e0a6c4eb9a4">llvm::AAMemoryLocation::NO_LOCAL_MEM</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a8bc927c80d7734e7e0baef13efd08bc5">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyAccessesArgPointees</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a636d669d76e435e9d71cdc417c89a30c">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyAccessesInaccessibleMem</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#afe3bf77a36d10551139f91d68bb00c4d">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyAccessesInaccessibleOrArgMem</a>.</p>


<p>Referenced by <a href="#a591478b4b082b96804160de6e9d26356">initialize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
