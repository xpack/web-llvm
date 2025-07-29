---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimedyld/loadedobjectinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoadedObjectInfo` Class

<p>Information about the loaded object. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RuntimeDyld::LoadedObjectInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">llvm/ExecutionEngine/RuntimeDyld.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loadedobjectinfo">LoadedObjectInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An inferface for inquiring the load address of a loaded object file to be used by the <a href="/web-llvm/docs/api/classes/llvm/dicontext">DIContext</a> implementations when applying relocations on the fly. <a href="/web-llvm/docs/api/classes/llvm/loadedobjectinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5120bbacb83db50d0e84c0070497027b">ObjSectionToIDMap</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">object::SectionRef</a>, unsigned &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29ff645c4ca493936f36642dc8ef01e9">RuntimeDyldImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefca359b2171a9d452f6fd3da2cdf173">LoadedObjectInfo</a> (RuntimeDyldImpl &amp;RTDyld, ObjSectionToIDMap ObjSecToIDMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad26e0abd20b5134ecc3e1258896c3f92">getObjectForDebug</a> (const object::ObjectFile &amp;Obj) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a212951ee11baafaa00abd5ee1a9d3a13">getSectionLoadAddress</a> (const object::SectionRef &amp;Sec) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the Load Address of a section by <a href="/web-llvm/docs/api/classes/llvm/sectionref">SectionRef</a>. <a href="#a212951ee11baafaa00abd5ee1a9d3a13">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f049a21afb42901016049d28fe6f79">anchor</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl">RuntimeDyldImpl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95b62f22193e46f10790cf2e0b778ac6">RTDyld</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5120bbacb83db50d0e84c0070497027b">ObjSectionToIDMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7714e17f315ea92fddde2c67e9b4cdb9">ObjSecToIDMap</a></td>
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

<p>Information about the loaded object.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ObjSectionToIDMap {#a5120bbacb83db50d0e84c0070497027b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RuntimeDyld::LoadedObjectInfo::ObjSectionToIDMap =  std::map&lt;object::SectionRef, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### RuntimeDyldImpl {#a29ff645c4ca493936f36642dc8ef01e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl">RuntimeDyldImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Reference <a href="#a29ff645c4ca493936f36642dc8ef01e9">RuntimeDyldImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldcoff-cpp-/loadedcoffobjectinfo/#af8f8cc2553ffa25cc794d3305c161b06">anonymous{RuntimeDyldCOFF.cpp}::LoadedCOFFObjectInfo::LoadedCOFFObjectInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldelf-cpp-/loadedelfobjectinfo/#a19687529e5a8c9a25a6ac6e1fb9da5c4">anonymous{RuntimeDyldELF.cpp}::LoadedELFObjectInfo::LoadedELFObjectInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldmacho-cpp-/loadedmachoobjectinfo/#a80899a540873896a6bdd0531d704b381">anonymous{RuntimeDyldMachO.cpp}::LoadedMachOObjectInfo::LoadedMachOObjectInfo</a>, <a href="#aefca359b2171a9d452f6fd3da2cdf173">LoadedObjectInfo</a> and <a href="#a29ff645c4ca493936f36642dc8ef01e9">RuntimeDyldImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LoadedObjectInfo() {#aefca359b2171a9d452f6fd3da2cdf173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyld::LoadedObjectInfo::LoadedObjectInfo (<a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl">RuntimeDyldImpl</a> &amp; RTDyld, <a href="#a5120bbacb83db50d0e84c0070497027b">ObjSectionToIDMap</a> ObjSecToIDMap)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a7714e17f315ea92fddde2c67e9b4cdb9">ObjSecToIDMap</a>, <a href="#a95b62f22193e46f10790cf2e0b778ac6">RTDyld</a> and <a href="#a29ff645c4ca493936f36642dc8ef01e9">RuntimeDyldImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getObjectForDebug() {#ad26e0abd20b5134ecc3e1258896c3f92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual object::OwningBinary&lt; object::ObjectFile &gt; llvm::RuntimeDyld::LoadedObjectInfo::getObjectForDebug (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

### getSectionLoadAddress() {#a212951ee11baafaa00abd5ee1a9d3a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RuntimeDyld::LoadedObjectInfo::getSectionLoadAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">object::SectionRef</a> &amp; Sec)</td>
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

<p>Obtain the Load Address of a section by <a href="/web-llvm/docs/api/classes/llvm/sectionref">SectionRef</a>.</p>


<p>Calculate the address of the given section. The section need not be present in the local address space. The addresses need to be consistent with the addresses used to query the <a href="/web-llvm/docs/api/classes/llvm/dicontext">DIContext</a> and the output of this function should be deterministic, i.e. repeated calls with the same Sec should give the same address.</p>


<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1287 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a7714e17f315ea92fddde2c67e9b4cdb9">ObjSecToIDMap</a> and <a href="#a95b62f22193e46f10790cf2e0b778ac6">RTDyld</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### anchor() {#a81f049a21afb42901016049d28fe6f79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RuntimeDyld::LoadedObjectInfo::anchor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ObjSecToIDMap {#a7714e17f315ea92fddde2c67e9b4cdb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjSectionToIDMap llvm::RuntimeDyld::LoadedObjectInfo::ObjSecToIDMap</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Referenced by <a href="#a212951ee11baafaa00abd5ee1a9d3a13">getSectionLoadAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldcoff-cpp-/loadedcoffobjectinfo/#af8f8cc2553ffa25cc794d3305c161b06">anonymous{RuntimeDyldCOFF.cpp}::LoadedCOFFObjectInfo::LoadedCOFFObjectInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldelf-cpp-/loadedelfobjectinfo/#a19687529e5a8c9a25a6ac6e1fb9da5c4">anonymous{RuntimeDyldELF.cpp}::LoadedELFObjectInfo::LoadedELFObjectInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldmacho-cpp-/loadedmachoobjectinfo/#a80899a540873896a6bdd0531d704b381">anonymous{RuntimeDyldMachO.cpp}::LoadedMachOObjectInfo::LoadedMachOObjectInfo</a> and <a href="#aefca359b2171a9d452f6fd3da2cdf173">LoadedObjectInfo</a>.</p>

</div>
</div>

### RTDyld {#a95b62f22193e46f10790cf2e0b778ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeDyldImpl&amp; llvm::RuntimeDyld::LoadedObjectInfo::RTDyld</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Referenced by <a href="#a212951ee11baafaa00abd5ee1a9d3a13">getSectionLoadAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldcoff-cpp-/loadedcoffobjectinfo/#af8f8cc2553ffa25cc794d3305c161b06">anonymous{RuntimeDyldCOFF.cpp}::LoadedCOFFObjectInfo::LoadedCOFFObjectInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldelf-cpp-/loadedelfobjectinfo/#a19687529e5a8c9a25a6ac6e1fb9da5c4">anonymous{RuntimeDyldELF.cpp}::LoadedELFObjectInfo::LoadedELFObjectInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldmacho-cpp-/loadedmachoobjectinfo/#a80899a540873896a6bdd0531d704b381">anonymous{RuntimeDyldMachO.cpp}::LoadedMachOObjectInfo::LoadedMachOObjectInfo</a> and <a href="#aefca359b2171a9d452f6fd3da2cdf173">LoadedObjectInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
