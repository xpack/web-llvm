---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-gdbregistrationlistener-cpp-/registeredobjectinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RegisteredObjectInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{GDBRegistrationListener.cpp}::RegisteredObjectInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a395959a81a363d412506d58dc7901eb5">RegisteredObjectInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e40558060b2b1456512d926515b1601">RegisteredObjectInfo</a> (std::size_t Size, jit_code_entry *Entry, OwningBinary&lt; ObjectFile &gt; Obj)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37da4b6926920500fe9d8fa30f1fa0a7">Size</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/jit-code-entry">jit_code_entry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39bd968476cac1cabf260e40a1eaa11c">Entry</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31ffa18f8fdd4d5db8b46b296c484344">Obj</a></td>
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


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegisteredObjectInfo() {#a395959a81a363d412506d58dc7901eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GDBRegistrationListener.cpp}::RegisteredObjectInfo::RegisteredObjectInfo ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-gdbregistrationlistener-cpp-/gdbjitregistrationlistener/#ae41608a898388d10b4a7d39b4f94e32e">anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener::notifyObjectLoaded</a>.</p>

</div>
</div>

### RegisteredObjectInfo() {#a1e40558060b2b1456512d926515b1601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GDBRegistrationListener.cpp}::RegisteredObjectInfo::RegisteredObjectInfo (std::size_t Size, <a href="/web-llvm/docs/api/structs/jit-code-entry">jit_code_entry</a> * Entry, <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt; Obj)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>References <a href="#a39bd968476cac1cabf260e40a1eaa11c">Entry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a31ffa18f8fdd4d5db8b46b296c484344">Obj</a> and <a href="#a37da4b6926920500fe9d8fa30f1fa0a7">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Entry {#a39bd968476cac1cabf260e40a1eaa11c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">jit_code_entry* anonymous{GDBRegistrationListener.cpp}::RegisteredObjectInfo::Entry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>Referenced by <a href="#a1e40558060b2b1456512d926515b1601">RegisteredObjectInfo</a>.</p>

</div>
</div>

### Obj {#a31ffa18f8fdd4d5db8b46b296c484344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OwningBinary&lt;ObjectFile&gt; anonymous{GDBRegistrationListener.cpp}::RegisteredObjectInfo::Obj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>Referenced by <a href="#a1e40558060b2b1456512d926515b1601">RegisteredObjectInfo</a>.</p>

</div>
</div>

### Size {#a37da4b6926920500fe9d8fa30f1fa0a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::size_t anonymous{GDBRegistrationListener.cpp}::RegisteredObjectInfo::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>Referenced by <a href="#a1e40558060b2b1456512d926515b1601">RegisteredObjectInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
