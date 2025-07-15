---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAMemoryBehaviorImpl` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior">AAMemoryBehavior</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract interface for memory access kind related attributes (readnone/readonly/writeonly). <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite">AACalleeToCallSite&lt;AAType, BaseType, StateType, IntroduceCallBaseContext, IRAttributeKind&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class for generic replication: function returned -&gt; cs returned. <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating">AAMemoryBehaviorFloating</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> behavior attribute for a floating value. <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction">AAMemoryBehaviorFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> to represent the memory behavior function attributes. <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1528f84762237cd607845b9f7d6295a">AAMemoryBehaviorImpl</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a976c2bfe7b4d81596b6b66a7c78bca1d">initialize</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::initialize(...). <a href="#a976c2bfe7b4d81596b6b66a7c78bca1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34e094853fc48c4acf66ca5e1c5a73dd">getDeducedAttributes</a> (Attributor &amp;A, LLVMContext &amp;Ctx, SmallVectorImpl&lt; Attribute &gt; &amp;Attrs) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::getDeducedAttributes(...). <a href="#a34e094853fc48c4acf66ca5e1c5a73dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1b2954b9c4eb6f178a0c7e66581822">manifest</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::manifest(...). <a href="#a9a1b2954b9c4eb6f178a0c7e66581822">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf12a1e247ff067ec47e8c70ac160089">getAsStr</a> (Attributor *A) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::getAsStr(). <a href="#aaf12a1e247ff067ec47e8c70ac160089">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad10f589dc1ab8e883ac7ee7d8957e965">getKnownStateFromValue</a> (Attributor &amp;A, const IRPosition &amp;IRP, BitIntegerState &amp;State, bool IgnoreSubsumingPositions=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the memory behavior information encoded in the IR for <span class="doxyComputerOutput">IRP</span>. <a href="#ad10f589dc1ab8e883ac7ee7d8957e965">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f93e36de0b3b9a3777b20c3d7772cd5">AttrKinds</a>[3] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of IR attributes AAMemoryBehavior deals with. <a href="#a5f93e36de0b3b9a3777b20c3d7772cd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 7794 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AAMemoryBehaviorImpl() {#ac1528f84762237cd607845b9f7d6295a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::AAMemoryBehaviorImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 7795 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#ad661bac9a38752d2abbbbf67130d5cdb">llvm::AAMemoryBehavior::AAMemoryBehavior</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a7c783d790de471054b07232950c41904">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::AAMemoryBehaviorFloating</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#a386733155cbacaf3ee3f30b29a50919e">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::AAMemoryBehaviorFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAsStr() {#aaf12a1e247ff067ec47e8c70ac160089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::getAsStr (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> * A)</td>
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

<p>See AbstractState::getAsStr().</p>

<p>Definition at line 7876 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a9e33a52cf9594a3a2f962a24328b59bc">llvm::AAMemoryBehavior::isAssumedReadNone</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a0d5c2d97702f51db9f73d3147f2b25e9">llvm::AAMemoryBehavior::isAssumedReadOnly</a> and <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#aa70372b8e98c0f7aa3422a936e0dab0e">llvm::AAMemoryBehavior::isAssumedWriteOnly</a>.</p>

</div>
</div>

### getDeducedAttributes() {#a34e094853fc48c4acf66ca5e1c5a73dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::getDeducedAttributes (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &gt; &amp; Attrs)</td>
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

<p>Definition at line 7836 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a9e33a52cf9594a3a2f962a24328b59bc">llvm::AAMemoryBehavior::isAssumedReadNone</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a0d5c2d97702f51db9f73d3147f2b25e9">llvm::AAMemoryBehavior::isAssumedReadOnly</a> and <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#aa70372b8e98c0f7aa3422a936e0dab0e">llvm::AAMemoryBehavior::isAssumedWriteOnly</a>.</p>


<p>Referenced by <a href="#a9a1b2954b9c4eb6f178a0c7e66581822">manifest</a>.</p>

</div>
</div>

### initialize() {#a976c2bfe7b4d81596b6b66a7c78bca1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::initialize (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>Definition at line 7799 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a79d67102092193edc6d431f35cdb072da6b8577d14abbaf2ef84df4df30780f1b">llvm::AAMemoryBehavior::BEST_STATE</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="#ad10f589dc1ab8e883ac7ee7d8957e965">getKnownStateFromValue</a>, <a href="/web-llvm/docs/api/structs/llvm/statewrapper/#aa83a3107fcf157e652c6be8fa548b893">llvm::StateWrapper&lt; BitIntegerState&lt; uint8_t, 3 &gt;, AbstractAttribute &gt;::getState</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a63f1f9078e9f43f6ac08ac9e1e9b4a41">llvm::AbstractAttribute::initialize</a> and <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a6e0463fb784adc7b2cef8dabb69dad32">llvm::BitIntegerState&lt; uint8_t, 3 &gt;::intersectAssumedBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsitereturned/#ac9dcdbb21b48648bdbd10658f88945a5">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSiteReturned::initialize</a>.</p>

</div>
</div>

### manifest() {#a9a1b2954b9c4eb6f178a0c7e66581822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::manifest (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>Definition at line 7849 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="#a5f93e36de0b3b9a3777b20c3d7772cd5">AttrKinds</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a9f40f87a556db81bd2403007b83acce7">llvm::IRPosition::getAnchorValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a34e094853fc48c4acf66ca5e1c5a73dd">getDeducedAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a6fea074fd9120ff82abd8f9e0036a12a">llvm::Attribute::getKindAsEnum</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a0d5c2d97702f51db9f73d3147f2b25e9">llvm::AAMemoryBehavior::isAssumedReadOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/irattribute/#aa8300749b291967b0d8fc610924741dc">llvm::IRAttribute&lt; AK, BaseType, AAType &gt;::manifest</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getKnownStateFromValue() {#ad10f589dc1ab8e883ac7ee7d8957e965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::getKnownStateFromValue (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate">BitIntegerState</a> &amp; State, bool IgnoreSubsumingPositions=false)</td>
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

<p>Definition at line 7806 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a5f93e36de0b3b9a3777b20c3d7772cd5">AttrKinds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a9f40f87a556db81bd2403007b83acce7">llvm::IRPosition::getAnchorValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a79d67102092193edc6d431f35cdb072da99fd7a59be55148bc3363d90453cc368">llvm::AAMemoryBehavior::NO_ACCESSES</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a79d67102092193edc6d431f35cdb072da968857ad600f95aa7d356e09c065c64f">llvm::AAMemoryBehavior::NO_READS</a> and <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a79d67102092193edc6d431f35cdb072da855b6c4a37d05f98826cad5d6c26cb14">llvm::AAMemoryBehavior::NO_WRITES</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorargument/#ae2b86059bf01f6d99d5871e52aa75212">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorArgument::initialize</a> and <a href="#a976c2bfe7b4d81596b6b66a7c78bca1d">initialize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### AttrKinds {#a5f93e36de0b3b9a3777b20c3d7772cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Attribute::AttrKind anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::AttrKinds</td>
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

<p>The set of IR attributes AAMemoryBehavior deals with.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    Attribute::ReadNone, Attribute::ReadOnly, Attribute::WriteOnly}
</div>
</dd>
</dl>

<p>Definition at line 7887 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="#ad10f589dc1ab8e883ac7ee7d8957e965">getKnownStateFromValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorargument/#a40a41eccaeafb327b27a589542a5f106">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a0451826f9ecd21f9d963cc51401b1b4d">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#ae444282c6d6bc8d5e9905620c936d39e">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::manifest</a> and <a href="#a9a1b2954b9c4eb6f178a0c7e66581822">manifest</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
