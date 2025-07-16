---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-runtimedyldelf-cpp-/loadedelfobjectinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoadedELFObjectInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{RuntimeDyldELF.cpp}::LoadedELFObjectInfo { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loadedobjectinfohelper">LoadedObjectInfoHelper&lt;Derived, Base&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19687529e5a8c9a25a6ac6e1fb9da5c4">LoadedELFObjectInfo</a> (RuntimeDyldImpl &amp;RTDyld, ObjSectionToIDMap ObjSecToIDMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44fe83651262377fdc122efe7d79d394">getObjectForDebug</a> (const ObjectFile &amp;Obj) const override</td>
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


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoadedELFObjectInfo() {#a19687529e5a8c9a25a6ac6e1fb9da5c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RuntimeDyldELF.cpp}::LoadedELFObjectInfo::LoadedELFObjectInfo (<a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl">RuntimeDyldImpl</a> &amp; RTDyld, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo/#a5120bbacb83db50d0e84c0070497027b">ObjSectionToIDMap</a> ObjSecToIDMap)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/loadedobjectinfohelper/#a815b8a6b13d17a42f4fd9d082ff69fc3">llvm::LoadedObjectInfoHelper&lt; LoadedELFObjectInfo, RuntimeDyld::LoadedObjectInfo &gt;::LoadedObjectInfoHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo/#a7714e17f315ea92fddde2c67e9b4cdb9">llvm::RuntimeDyld::LoadedObjectInfo::ObjSecToIDMap</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo/#a95b62f22193e46f10790cf2e0b778ac6">llvm::RuntimeDyld::LoadedObjectInfo::RTDyld</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo/#a29ff645c4ca493936f36642dc8ef01e9">llvm::RuntimeDyld::LoadedObjectInfo::RuntimeDyldImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getObjectForDebug() {#a44fe83651262377fdc122efe7d79d394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OwningBinary&lt; ObjectFile &gt; anonymous{RuntimeDyldELF.cpp}::LoadedELFObjectInfo::getObjectForDebug (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/anonymous-runtimedyldelf-cpp-/#a4c89c8ae8b758aaf88cb3ddcb0a25c20">anonymous{RuntimeDyldELF.cpp}::createELFDebugObject</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
