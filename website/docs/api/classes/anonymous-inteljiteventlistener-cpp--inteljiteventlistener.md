---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IntelJITEventListener` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{IntelJITEventListener.cpp}::IntelJITEventListener { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> - Abstract interface for use by the JIT to notify clients about significant events during compilation. <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; void *, unsigned int &gt; <a href="#ae81111785b6a66f12562eb3e2b8c0b7d">MethodIDMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *, 64 &gt; <a href="#a9f119a1b606ade59eabfea95ca350c1c">MethodAddressVector</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">MethodAddressVector</a> &gt; <a href="#aaa82ee88e870d3a14bcc3b559e33d6e6">ObjectMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e2db1fb4ed0993db7d100cb5b50b1f">IntelJITEventListener</a> (IntelJITEventsWrapper *libraryWrapper)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a253502d0973aa5cc212b8373f5401586">~IntelJITEventListener</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89cbcd5cb777a56db440c87f1ebffdb4">notifyObjectLoaded</a> (ObjectKey Key, const ObjectFile &amp;Obj, const RuntimeDyld::LoadedObjectInfo &amp;L) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>notifyObjectLoaded - Called after an object has had its sections allocated and addresses assigned to all symbols. <a href="#a89cbcd5cb777a56db440c87f1ebffdb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b51573bc0b0e62d37537759a24a44c3">notifyFreeingObject</a> (ObjectKey Key) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>notifyFreeingObject - Called just before the memory associated with a previously emitted object is released. <a href="#a1b51573bc0b0e62d37537759a24a44c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inteljiteventswrapper">IntelJITEventsWrapper</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e20713b768359b51bf7790e7dbdd2a">Wrapper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">MethodIDMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3eb6494aa729d9261d724f5aeb2ca9b">MethodIDs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ObjectMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b53ecef7d4c991d49f9d0e69f5a043a">LoadedObjectMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#aefc8c6bb6d8f5a09e48f4b9db9c10024">ObjectKey</a>, <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5018d14cb709c8ceaeb5b21e7f5c68c4">DebugObjects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#aefc8c6bb6d8f5a09e48f4b9db9c10024">ObjectKey</a>, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo">IntelIttnotifyInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c2cab544e9057a8c8d4163dc6dca7b">KeyToIttnotify</a></td>
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


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### MethodAddressVector {#a9f119a1b606ade59eabfea95ca350c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVector&lt;const void *, 64&gt; anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::MethodAddressVector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>

</div>
</div>

### MethodIDMap {#ae81111785b6a66f12562eb3e2b8c0b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef DenseMap&lt;void*, unsigned int&gt; anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::MethodIDMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>

</div>
</div>

### ObjectMap {#aaa82ee88e870d3a14bcc3b559e33d6e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef DenseMap&lt;const void *, MethodAddressVector&gt; anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::ObjectMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IntelJITEventListener() {#ac9e2db1fb4ed0993db7d100cb5b50b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::IntelJITEventListener (<a href="/web-llvm/docs/api/classes/llvm/inteljiteventswrapper">IntelJITEventsWrapper</a> * libraryWrapper)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~IntelJITEventListener() {#a253502d0973aa5cc212b8373f5401586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::~IntelJITEventListener ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### notifyFreeingObject() {#a1b51573bc0b0e62d37537759a24a44c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyFreeingObject (<a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#aefc8c6bb6d8f5a09e48f4b9db9c10024">ObjectKey</a> K)</td>
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

<p>notifyFreeingObject - Called just before the memory associated with a previously emitted object is released.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-inteljiteventlistener-cpp-/#ac5094885b654e66770472d1e6802b21f">anonymous{IntelJITEventListener.cpp}::getBackwardCompatibilityMode</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo/#a3cde2b65e32b7a88db7b47405dd815af">anonymous{IntelJITEventListener.cpp}::IntelIttnotifyInfo::getModuleObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a199e5cfae34a345dd07c5da4db615318abaeae040e439fd0de07f2b09b4ae99d5">iJVM_EVENT_TYPE_METHOD_UNLOAD_START</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1e9832c872d8a59daf3b982a6d4f7782a4dfbcb2196a94e60cc0ffee0e9eab9ed">llvm::UnloadBinaryModule</a>.</p>

</div>
</div>

### notifyObjectLoaded() {#a89cbcd5cb777a56db440c87f1ebffdb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded (<a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#aefc8c6bb6d8f5a09e48f4b9db9c10024">ObjectKey</a> K, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a> &amp; L)</td>
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

<p>notifyObjectLoaded - Called after an object has had its sections allocated and addresses assigned to all symbols.</p>


<p>Note: Section memory will not have been relocated yet. notifyFunctionLoaded will not be called for individual functions in the object.</p>


<p>ELF-specific information The ObjectImage contains the generated object image with section headers updated to reflect the address at which sections were loaded and with relocations performed in-place on debug sections.</p>


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#acf228956812ef6e7722e8c114fe3b923">llvm::object::computeSymbolSizes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ad6f9fa82bb8b6a5dae98b9d9d346d913">llvm::DWARFContext::create</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-inteljiteventlistener-cpp-/#a34295cd852aa896f64c8665f1c2ac292">anonymous{IntelJITEventListener.cpp}::DILineInfoToIntelJITFormat</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-inteljiteventlistener-cpp-/#a6914f5f9e02468ebb7278d069dc68129">anonymous{IntelJITEventListener.cpp}::FunctionDescToIntelJITFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#ac22d03239bd28b53a229486b43a9d3b8">llvm::object::SymbolRef::getAddress</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-inteljiteventlistener-cpp-/#ac5094885b654e66770472d1e6802b21f">anonymous{IntelJITEventListener.cpp}::getBackwardCompatibilityMode</a>, <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary/#a3f6d33585a43bad491af78cc5c07f605">llvm::object::OwningBinary&lt; T &gt;::getBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a7301c8fd89ad0f595f4ce4609c872704">llvm::MemoryBufferRef::getBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a2036a4973d159e49dcc471488205656f">llvm::MemoryBufferRef::getBufferSize</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a62b2843b74e5f05930ebf5c63766a668">llvm::MemoryBufferRef::getBufferStart</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a1683493667fa7e44083fe1258a1dcb10">llvm::object::SectionRef::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ac0322f1809be8f6f88af125c1956c9a1">llvm::object::Binary::getMemoryBufferRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a6935271c0f6df1209adbb91f2f68d2c1">llvm::object::SymbolRef::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#af8b31890b3cf3677a9c279325661e3af">llvm::object::SymbolRef::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a234b2c90b26a44886a6f04c4281b1b65">llvm::object::SymbolRef::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a199e5cfae34a345dd07c5da4db615318aace21abae9888611f9fb6e6cf1922b20">iJVM_EVENT_TYPE_METHOD_LOAD_FINISHED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ae470b1ff27e3d72e61fcb4a97fd0a461">llvm::object::Binary::isELF</a>, <a href="/web-llvm/docs/api/structs/-ijit-method-load/#a18fba4fe0f235d81be7e6661c8de2890">_iJIT_Method_Load::line_number_size</a>, <a href="/web-llvm/docs/api/structs/-ijit-method-load/#a8cc078c6201ccc6fd2e292e82cb061ae">_iJIT_Method_Load::line_number_table</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1e9832c872d8a59daf3b982a6d4f7782a6810092147ad88d96e09c8634a39ef1c">llvm::LoadBinaryModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a8e89e6935aaf48cde9d60fd12a3dae0f">llvm::sampleprof::MD5Hash</a>, <a href="/web-llvm/docs/api/structs/-ijit-method-load/#a4749361629cb18a2134ffcfb7c5009c3">_iJIT_Method_Load::method_id</a>, <a href="/web-llvm/docs/api/structs/-ijit-method-load/#ab68d7a5a9552ec49bd7baa01c03d1f72">_iJIT_Method_Load::method_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3e48ce01c39d5e5e36eced4e3d3f6f23">llvm::object::ObjectFile::section_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/structs/-ijit-method-load/#a8dc975a3b54110af8007f2418477ac50">_iJIT_Method_Load::source_file_name</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DebugObjects {#a5018d14cb709c8ceaeb5b21e7f5c68c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;ObjectKey, OwningBinary&lt;ObjectFile&gt; &gt; anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::DebugObjects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>

</div>
</div>

### KeyToIttnotify {#a84c2cab544e9057a8c8d4163dc6dca7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;ObjectKey, std::unique_ptr&lt;IntelIttnotifyInfo&gt; &gt; anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::KeyToIttnotify</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>

</div>
</div>

### LoadedObjectMap {#a4b53ecef7d4c991d49f9d0e69f5a043a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectMap anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::LoadedObjectMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>

</div>
</div>

### MethodIDs {#ac3eb6494aa729d9261d724f5aeb2ca9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MethodIDMap anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::MethodIDs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>

</div>
</div>

### Wrapper {#a02e20713b768359b51bf7790e7dbdd2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;IntelJITEventsWrapper&gt; anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::Wrapper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
