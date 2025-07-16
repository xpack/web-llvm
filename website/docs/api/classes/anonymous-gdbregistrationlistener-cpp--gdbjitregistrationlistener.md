---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-gdbregistrationlistener-cpp-/gdbjitregistrationlistener
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GDBJITRegistrationListener` Class Reference

<p>Global access point for the JIT debugging interface designed for use with a singleton toolbox. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener { ... }
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc8b002958ca498ceaeb864ee156dd3">GDBJITRegistrationListener</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instantiates the JIT service. <a href="#abfc8b002958ca498ceaeb864ee156dd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fe8ec178b276bf2cc56801053e83143">~GDBJITRegistrationListener</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unregisters each object that was previously registered and releases all internal resources. <a href="#a4fe8ec178b276bf2cc56801053e83143">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae41608a898388d10b4a7d39b4f94e32e">notifyObjectLoaded</a> (ObjectKey K, const ObjectFile &amp;Obj, const RuntimeDyld::LoadedObjectInfo &amp;L) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an entry in the JIT registry for the buffer <span class="doxyComputerOutput">Object</span>, which must contain an object file in executable memory with any debug information for the debugger. <a href="#ae41608a898388d10b4a7d39b4f94e32e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a08fb4e12d95ae18f3a656f1210d0b">notifyFreeingObject</a> (ObjectKey K) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the internal registration of <span class="doxyComputerOutput">Object</span>, and frees associated resources. <a href="#a46a08fb4e12d95ae18f3a656f1210d0b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07a7f51743d4d481fc59a2cce24c9d6f">deregisterObjectInternal</a> (RegisteredObjectBufferMap::iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deregister the debug info for the given object file from the debugger and delete any temporary copies. <a href="#a07a7f51743d4d481fc59a2cce24c9d6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52d48084c5b60251870b6118e4670fee">sys::Mutex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880da7403e190a8d68234ffd1ba19825">JITDebugLock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lock used to serialize all jit registration events, since they modify global variables. <a href="#a880da7403e190a8d68234ffd1ba19825">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-/#ad24beec920a5d33ddb8f0d2af143b376">RegisteredObjectBufferMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd444151e9d80786fd5ad31619bade7b">ObjectBufferMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map of in-memory object files that have been registered with the JIT interface. <a href="#abd444151e9d80786fd5ad31619bade7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-gdbregistrationlistener-cpp-/gdbjitregistrationlistener">GDBJITRegistrationListener</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02ab9f0e6bafa6a158c61ca0a442f1cd">instance</a> ()</td>
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

<p>Global access point for the JIT debugging interface designed for use with a singleton toolbox.</p>


<p>Handles thread-safe registration and deregistration of object files that are in executable memory managed by the client of this class.</p>


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### GDBJITRegistrationListener() {#abfc8b002958ca498ceaeb864ee156dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener::GDBJITRegistrationListener ()</td>
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

<p>Instantiates the JIT service.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~GDBJITRegistrationListener() {#a4fe8ec178b276bf2cc56801053e83143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener::~GDBJITRegistrationListener ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unregisters each object that was previously registered and releases all internal resources.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### notifyFreeingObject() {#a46a08fb4e12d95ae18f3a656f1210d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener::notifyFreeingObject (<a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#aefc8c6bb6d8f5a09e48f4b9db9c10024">ObjectKey</a> K)</td>
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

<p>Removes the internal registration of <span class="doxyComputerOutput">Object</span>, and frees associated resources.</p>


<p>Returns true if <span class="doxyComputerOutput">Object</span> was found in ObjectBufferMap.</p>


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### notifyObjectLoaded() {#ae41608a898388d10b4a7d39b4f94e32e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener::notifyObjectLoaded (<a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#aefc8c6bb6d8f5a09e48f4b9db9c10024">ObjectKey</a> K, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a> &amp; L)</td>
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

<p>Creates an entry in the JIT registry for the buffer <span class="doxyComputerOutput">Object</span>, which must contain an object file in executable memory with any debug information for the debugger.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary/#a3f6d33585a43bad491af78cc5c07f605">llvm::object::OwningBinary&lt; T &gt;::getBinary</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-/#ac04610af527ea2371b9c4aad7a11b539">anonymous{GDBRegistrationListener.cpp}::NotifyDebugger</a>, <a href="/web-llvm/docs/api/structs/anonymous-gdbregistrationlistener-cpp-/registeredobjectinfo/#a395959a81a363d412506d58dc7901eb5">anonymous{GDBRegistrationListener.cpp}::RegisteredObjectInfo::RegisteredObjectInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/structs/jit-code-entry/#a60186e403eff321111fb57d7b461b618">jit_code_entry::symfile_addr</a> and <a href="/web-llvm/docs/api/structs/jit-code-entry/#aad8fa2b15fe70092d6fdd41ff48e1f76">jit_code_entry::symfile_size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### deregisterObjectInternal() {#a07a7f51743d4d481fc59a2cce24c9d6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener::deregisterObjectInternal (<a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a214e872d61db2ea8cb023f127cafd0b9">RegisteredObjectBufferMap::iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deregister the debug info for the given object file from the debugger and delete any temporary copies.</p>


<p>This private method does not remove the function from Map so that it can be called while iterating over Map.</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### JITDebugLock {#a880da7403e190a8d68234ffd1ba19825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::Mutex anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener::JITDebugLock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lock used to serialize all jit registration events, since they modify global variables.</p>


<p>Only a single instance of <a href="/web-llvm/docs/api/classes/anonymous-gdbregistrationlistener-cpp-/gdbjitregistrationlistener">GDBJITRegistrationListener</a> is ever created, and so the lock can be a member variable of that instance. This ensures destructors are run in the correct order.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>

</div>
</div>

### ObjectBufferMap {#abd444151e9d80786fd5ad31619bade7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisteredObjectBufferMap anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener::ObjectBufferMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map of in-memory object files that have been registered with the JIT interface.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#a02ab9f0e6bafa6a158c61ca0a442f1cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GDBJITRegistrationListener &amp; anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener::instance ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#a004abbb5a0d48ac376dfbe3e3c97c306">llvm::JITEventListener::createGDBRegistrationListener</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
