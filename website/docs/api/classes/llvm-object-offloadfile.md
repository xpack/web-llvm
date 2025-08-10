---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/offloadfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OffloadFile` Class

<p>A class to contain the binary information for a single <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary">OffloadBinary</a> that owns its memory. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::object::OffloadFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">llvm/Object/OffloadBinary.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">OwningBinary&lt;T&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c0c9b12f8ee79572afeb77fdac1bdfa">TargetID</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac54eb4a0720e51053aaa66b42f2f7d3b">OffloadFile</a> (std::unique_ptr&lt; OffloadBinary &gt; Binary, std::unique_ptr&lt; MemoryBuffer &gt; Buffer)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69757b9578d9da60b7e69f302bfb880f">operator TargetID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We use the <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> and Architecture pair to group linker inputs together. <a href="#a69757b9578d9da60b7e69f302bfb880f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/offloadfile">OffloadFile</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b4886b96406a196d56ea326687ba908">copy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make a deep copy of this offloading file. <a href="#a9b4886b96406a196d56ea326687ba908">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A class to contain the binary information for a single <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary">OffloadBinary</a> that owns its memory.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### TargetID {#a6c0c9b12f8ee79572afeb77fdac1bdfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::OffloadFile::TargetID =  std::pair&lt;StringRef, StringRef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OffloadFile() {#ac54eb4a0720e51053aaa66b42f2f7d3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::OffloadFile::OffloadFile (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary">OffloadBinary</a> &gt; Binary, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Buffer)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/owningbinary/#ae119b2e4ff6317be8116ba6c0a7af8a6">llvm::object::OwningBinary&lt; OffloadBinary &gt;::OwningBinary</a>.</p>


<p>Referenced by <a href="#a9b4886b96406a196d56ea326687ba908">copy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator TargetID() {#a69757b9578d9da60b7e69f302bfb880f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::OffloadFile::operator TargetID ()</td>
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

<p>We use the <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> and Architecture pair to group linker inputs together.</p>


<p>This conversion function lets us use these inputs in a hash-map.</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/owningbinary/#a3f6d33585a43bad491af78cc5c07f605">llvm::object::OwningBinary&lt; OffloadBinary &gt;::getBinary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copy() {#a9b4886b96406a196d56ea326687ba908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffloadFile llvm::object::OffloadFile::copy ()</td>
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

<p>Make a deep copy of this offloading file.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#ab1f06bb87aef1053996ec05424135d82">llvm::object::OffloadBinary::create</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/owningbinary/#a3f6d33585a43bad491af78cc5c07f605">llvm::object::OwningBinary&lt; OffloadBinary &gt;::getBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a32d2c9ba9019e6e41605c60acd06bd09">llvm::MemoryBuffer::getMemBufferCopy</a> and <a href="#ac54eb4a0720e51053aaa66b42f2f7d3b">OffloadFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
