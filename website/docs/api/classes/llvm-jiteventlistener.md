---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jiteventlistener
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `JITEventListener` Class

<p><a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> - Abstract interface for use by the JIT to notify clients about significant events during compilation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::JITEventListener { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">llvm/ExecutionEngine/JITEventListener.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gdbregistrationlistener-cpp-/gdbjitregistrationlistener">GDBJITRegistrationListener</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global access point for the JIT debugging interface designed for use with a singleton toolbox. <a href="/web-llvm/docs/api/classes/anonymous-gdbregistrationlistener-cpp-/gdbjitregistrationlistener/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener">IntelJITEventListener</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-oprofilejiteventlistener-cpp-/oprofilejiteventlistener">OProfileJITEventListener</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-perfjiteventlistener-cpp-/perfjiteventlistener">PerfJITEventListener</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc8c6bb6d8f5a09e48f4b9db9c10024">ObjectKey</a> = uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ee72597bbb2b490cf27892d4509add">JITEventListener</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af307eac43ee37915727a0d239d9f8f66">~JITEventListener</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a6eea839cd80cdbc1c9ce2baeecef74">notifyObjectLoaded</a> (ObjectKey K, const object::ObjectFile &amp;Obj, const RuntimeDyld::LoadedObjectInfo &amp;L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>notifyObjectLoaded - Called after an object has had its sections allocated and addresses assigned to all symbols. <a href="#a3a6eea839cd80cdbc1c9ce2baeecef74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d9dbef6d1a1a97e5fadd0bdcd5ba954">notifyFreeingObject</a> (ObjectKey K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>notifyFreeingObject - Called just before the memory associated with a previously emitted object is released. <a href="#a1d9dbef6d1a1a97e5fadd0bdcd5ba954">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4aa238b8909923fc35c988ac1072a04">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a004abbb5a0d48ac376dfbe3e3c97c306">createGDBRegistrationListener</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fc9cd1088989682b3d72a2560d0c577">createIntelJITEventListener</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab75def1bbc1bc1c95434203e0f9d8aa5">createIntelJITEventListener</a> (IntelJITEventsWrapper *AlternativeImpl)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada1f87075221bc4d64d42c15b6e47e54">createOProfileJITEventListener</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6edb3f85d8874b0a22884c28b59c366">createOProfileJITEventListener</a> (OProfileWrapper *AlternativeImpl)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa6e4061784b1c2064eafe1adaef7e5">createPerfJITEventListener</a> ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> - Abstract interface for use by the JIT to notify clients about significant events during compilation.</p>


<p>For example, to notify profilers and debuggers that need to know where functions have been emitted.</p>


<p>The default implementation of each method does nothing.</p>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ObjectKey {#aefc8c6bb6d8f5a09e48f4b9db9c10024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::JITEventListener::ObjectKey =  uint64_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### JITEventListener() {#a01ee72597bbb2b490cf27892d4509add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITEventListener::JITEventListener ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>.</p>


<p>Referenced by <a href="#a004abbb5a0d48ac376dfbe3e3c97c306">createGDBRegistrationListener</a>, <a href="#a8fc9cd1088989682b3d72a2560d0c577">createIntelJITEventListener</a>, <a href="#ab75def1bbc1bc1c95434203e0f9d8aa5">createIntelJITEventListener</a>, <a href="#ada1f87075221bc4d64d42c15b6e47e54">createOProfileJITEventListener</a>, <a href="#ae6edb3f85d8874b0a22884c28b59c366">createOProfileJITEventListener</a> and <a href="#acaa6e4061784b1c2064eafe1adaef7e5">createPerfJITEventListener</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~JITEventListener() {#af307eac43ee37915727a0d239d9f8f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::JITEventListener::~JITEventListener ()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### notifyFreeingObject() {#a1d9dbef6d1a1a97e5fadd0bdcd5ba954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::JITEventListener::notifyFreeingObject (<a href="#aefc8c6bb6d8f5a09e48f4b9db9c10024">ObjectKey</a> K)</td>
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

<p>notifyFreeingObject - Called just before the memory associated with a previously emitted object is released.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>.</p>

</div>
</div>

### notifyObjectLoaded() {#a3a6eea839cd80cdbc1c9ce2baeecef74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::JITEventListener::notifyObjectLoaded (<a href="#aefc8c6bb6d8f5a09e48f4b9db9c10024">ObjectKey</a> K, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a> &amp; L)</td>
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

<p>notifyObjectLoaded - Called after an object has had its sections allocated and addresses assigned to all symbols.</p>


<p>Note: Section memory will not have been relocated yet. notifyFunctionLoaded will not be called for individual functions in the object.</p>


<p>ELF-specific information The ObjectImage contains the generated object image with section headers updated to reflect the address at which sections were loaded and with relocations performed in-place on debug sections.</p>


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#ad4aa238b8909923fc35c988ac1072a04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void JITEventListener::anchor ()</td>
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



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createGDBRegistrationListener() {#a004abbb5a0d48ac376dfbe3e3c97c306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITEventListener * llvm::JITEventListener::createGDBRegistrationListener ()</td>
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



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-gdbregistrationlistener-cpp-/gdbjitregistrationlistener/#a02ab9f0e6bafa6a158c61ca0a442f1cd">anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener::instance</a> and <a href="#a01ee72597bbb2b490cf27892d4509add">JITEventListener</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga9ff6e0b848af7f64c654c8240e1fb4ab">LLVMCreateGDBRegistrationListener</a>.</p>

</div>
</div>

### createIntelJITEventListener() {#a8fc9cd1088989682b3d72a2560d0c577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITEventListener * llvm::JITEventListener::createIntelJITEventListener ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>.</p>


<p>Reference <a href="#a01ee72597bbb2b490cf27892d4509add">JITEventListener</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga8feedaf2301fb3a7dc2e7e5f66328bba">LLVMCreateIntelJITEventListener</a>.</p>

</div>
</div>

### createIntelJITEventListener() {#ab75def1bbc1bc1c95434203e0f9d8aa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITEventListener * llvm::JITEventListener::createIntelJITEventListener (<a href="/web-llvm/docs/api/classes/llvm/inteljiteventswrapper">IntelJITEventsWrapper</a> * AlternativeImpl)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>.</p>


<p>Reference <a href="#a01ee72597bbb2b490cf27892d4509add">JITEventListener</a>.</p>

</div>
</div>

### createOProfileJITEventListener() {#ada1f87075221bc4d64d42c15b6e47e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITEventListener * llvm::JITEventListener::createOProfileJITEventListener ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>.</p>


<p>Reference <a href="#a01ee72597bbb2b490cf27892d4509add">JITEventListener</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga07411f28dc370e0ece91597b7449f764">LLVMCreateOProfileJITEventListener</a>.</p>

</div>
</div>

### createOProfileJITEventListener() {#ae6edb3f85d8874b0a22884c28b59c366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITEventListener * llvm::JITEventListener::createOProfileJITEventListener (<a href="/web-llvm/docs/api/classes/llvm/oprofilewrapper">OProfileWrapper</a> * AlternativeImpl)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>.</p>


<p>Reference <a href="#a01ee72597bbb2b490cf27892d4509add">JITEventListener</a>.</p>

</div>
</div>

### createPerfJITEventListener() {#acaa6e4061784b1c2064eafe1adaef7e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITEventListener * llvm::JITEventListener::createPerfJITEventListener ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a>.</p>


<p>Reference <a href="#a01ee72597bbb2b490cf27892d4509add">JITEventListener</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga5b912f524525c4df3780b8cb3629b9d7">LLVMCreatePerfJITEventListener</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">JITEventListener.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
