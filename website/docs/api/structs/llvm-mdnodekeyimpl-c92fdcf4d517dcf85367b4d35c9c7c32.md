---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mdnodekeyimpl-c92fdcf4d517dcf85367b4d35c9c7c32
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MDNodeKeyImpl` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MDNodeKeyImpl&lt;DIObjCProperty&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">IR/LLVMContextImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac039634219405277621f1b31e2d5b5">MDNodeKeyImpl</a> (MDString *Name, Metadata *File, unsigned Line, MDString *GetterName, MDString *SetterName, unsigned Attributes, Metadata *Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2791f954759af8da1eab54aa83063f1c">MDNodeKeyImpl</a> (const DIObjCProperty *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f454f2919884d9c9c44f19a56a8b965">isKeyOf</a> (const DIObjCProperty *RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a050dca6e0473eb607aaf35355b37bf0f">getHashValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2658a89a6c9257bb5b061f557e20c6f6">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89aebb2748c5be5baf108fe0630f6212">File</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190349f60b96996005b62d867af8249b">Line</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a1fcd6007a89b6a042f7628846a1cda">GetterName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c1fa8b7144f305fa3e2851d3e5d07c">SetterName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b38840849fbbeb17ffc628056b40cfb">Attributes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada24ebbd80bf38c4300305d96bf52374">Type</a></td>
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


<p>Definition at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MDNodeKeyImpl() {#a5ac039634219405277621f1b31e2d5b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::MDNodeKeyImpl (<a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * File, unsigned Line, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * GetterName, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * SetterName, unsigned Attributes, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Type)</td>
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



<p>Definition at line 1239 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a8b38840849fbbeb17ffc628056b40cfb">Attributes</a>, <a href="#a89aebb2748c5be5baf108fe0630f6212">File</a>, <a href="#a7a1fcd6007a89b6a042f7628846a1cda">GetterName</a>, <a href="#a190349f60b96996005b62d867af8249b">Line</a>, <a href="#a2658a89a6c9257bb5b061f557e20c6f6">Name</a>, <a href="#ab5c1fa8b7144f305fa3e2851d3e5d07c">SetterName</a> and <a href="#ada24ebbd80bf38c4300305d96bf52374">Type</a>.</p>

</div>
</div>

### MDNodeKeyImpl() {#a2791f954759af8da1eab54aa83063f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::MDNodeKeyImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diobjcproperty">DIObjCProperty</a> * N)</td>
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



<p>Definition at line 1244 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a8b38840849fbbeb17ffc628056b40cfb">Attributes</a>, <a href="#a89aebb2748c5be5baf108fe0630f6212">File</a>, <a href="#a7a1fcd6007a89b6a042f7628846a1cda">GetterName</a>, <a href="#a190349f60b96996005b62d867af8249b">Line</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a2658a89a6c9257bb5b061f557e20c6f6">Name</a>, <a href="#ab5c1fa8b7144f305fa3e2851d3e5d07c">SetterName</a> and <a href="#ada24ebbd80bf38c4300305d96bf52374">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getHashValue() {#a050dca6e0473eb607aaf35355b37bf0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::getHashValue ()</td>
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



<p>Definition at line 1256 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a8b38840849fbbeb17ffc628056b40cfb">Attributes</a>, <a href="#a89aebb2748c5be5baf108fe0630f6212">File</a>, <a href="#a7a1fcd6007a89b6a042f7628846a1cda">GetterName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="#a190349f60b96996005b62d867af8249b">Line</a>, <a href="#a2658a89a6c9257bb5b061f557e20c6f6">Name</a>, <a href="#ab5c1fa8b7144f305fa3e2851d3e5d07c">SetterName</a> and <a href="#ada24ebbd80bf38c4300305d96bf52374">Type</a>.</p>

</div>
</div>

### isKeyOf() {#a3f454f2919884d9c9c44f19a56a8b965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::isKeyOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diobjcproperty">DIObjCProperty</a> * RHS)</td>
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



<p>Definition at line 1249 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a8b38840849fbbeb17ffc628056b40cfb">Attributes</a>, <a href="#a89aebb2748c5be5baf108fe0630f6212">File</a>, <a href="#a7a1fcd6007a89b6a042f7628846a1cda">GetterName</a>, <a href="#a190349f60b96996005b62d867af8249b">Line</a>, <a href="#a2658a89a6c9257bb5b061f557e20c6f6">Name</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#ab5c1fa8b7144f305fa3e2851d3e5d07c">SetterName</a> and <a href="#ada24ebbd80bf38c4300305d96bf52374">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Attributes {#a8b38840849fbbeb17ffc628056b40cfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::Attributes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1236 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a050dca6e0473eb607aaf35355b37bf0f">getHashValue</a>, <a href="#a3f454f2919884d9c9c44f19a56a8b965">isKeyOf</a>, <a href="#a2791f954759af8da1eab54aa83063f1c">MDNodeKeyImpl</a> and <a href="#a5ac039634219405277621f1b31e2d5b5">MDNodeKeyImpl</a>.</p>

</div>
</div>

### File {#a89aebb2748c5be5baf108fe0630f6212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::File</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a050dca6e0473eb607aaf35355b37bf0f">getHashValue</a>, <a href="#a3f454f2919884d9c9c44f19a56a8b965">isKeyOf</a>, <a href="#a2791f954759af8da1eab54aa83063f1c">MDNodeKeyImpl</a> and <a href="#a5ac039634219405277621f1b31e2d5b5">MDNodeKeyImpl</a>.</p>

</div>
</div>

### GetterName {#a7a1fcd6007a89b6a042f7628846a1cda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString* llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::GetterName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a050dca6e0473eb607aaf35355b37bf0f">getHashValue</a>, <a href="#a3f454f2919884d9c9c44f19a56a8b965">isKeyOf</a>, <a href="#a2791f954759af8da1eab54aa83063f1c">MDNodeKeyImpl</a> and <a href="#a5ac039634219405277621f1b31e2d5b5">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Line {#a190349f60b96996005b62d867af8249b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1233 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a050dca6e0473eb607aaf35355b37bf0f">getHashValue</a>, <a href="#a3f454f2919884d9c9c44f19a56a8b965">isKeyOf</a>, <a href="#a2791f954759af8da1eab54aa83063f1c">MDNodeKeyImpl</a> and <a href="#a5ac039634219405277621f1b31e2d5b5">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Name {#a2658a89a6c9257bb5b061f557e20c6f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString* llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a050dca6e0473eb607aaf35355b37bf0f">getHashValue</a>, <a href="#a3f454f2919884d9c9c44f19a56a8b965">isKeyOf</a>, <a href="#a2791f954759af8da1eab54aa83063f1c">MDNodeKeyImpl</a> and <a href="#a5ac039634219405277621f1b31e2d5b5">MDNodeKeyImpl</a>.</p>

</div>
</div>

### SetterName {#ab5c1fa8b7144f305fa3e2851d3e5d07c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString* llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::SetterName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1235 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a050dca6e0473eb607aaf35355b37bf0f">getHashValue</a>, <a href="#a3f454f2919884d9c9c44f19a56a8b965">isKeyOf</a>, <a href="#a2791f954759af8da1eab54aa83063f1c">MDNodeKeyImpl</a> and <a href="#a5ac039634219405277621f1b31e2d5b5">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Type {#ada24ebbd80bf38c4300305d96bf52374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1237 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a050dca6e0473eb607aaf35355b37bf0f">getHashValue</a>, <a href="#a3f454f2919884d9c9c44f19a56a8b965">isKeyOf</a>, <a href="#a2791f954759af8da1eab54aa83063f1c">MDNodeKeyImpl</a> and <a href="#a5ac039634219405277621f1b31e2d5b5">MDNodeKeyImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
