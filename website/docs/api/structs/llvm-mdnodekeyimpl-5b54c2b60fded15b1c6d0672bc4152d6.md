---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mdnodekeyimpl-5b54c2b60fded15b1c6d0672bc4152d6
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
struct llvm::MDNodeKeyImpl&lt;DILexicalBlock&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">IR/LLVMContextImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d00611ccbdb4453a3739aeb6cea25f7">MDNodeKeyImpl</a> (Metadata *Scope, Metadata *File, unsigned Line, unsigned Column)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ddc8bbe2e8d61c71b82e011f7a4862f">MDNodeKeyImpl</a> (const DILexicalBlock *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d93a75f9188a74bc77d8910f1e4132b">isKeyOf</a> (const DILexicalBlock *RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a824d05a2c608f7e21cfd61bef79869e4">getHashValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71da17880c2a210b965e997436081d59">Scope</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb9aa82741f1ed488d96c4183002a45">File</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f3210698409ea44bf525351cda6c39">Line</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f7a19e72cf4d42979456c78cb743b9e">Column</a></td>
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


<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MDNodeKeyImpl() {#a8d00611ccbdb4453a3739aeb6cea25f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeKeyImpl&lt; DILexicalBlock &gt;::MDNodeKeyImpl (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * File, unsigned Line, unsigned Column)</td>
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



<p>Definition at line 912 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a9f7a19e72cf4d42979456c78cb743b9e">Column</a>, <a href="#a5cb9aa82741f1ed488d96c4183002a45">File</a>, <a href="#ae2f3210698409ea44bf525351cda6c39">Line</a> and <a href="#a71da17880c2a210b965e997436081d59">Scope</a>.</p>

</div>
</div>

### MDNodeKeyImpl() {#a7ddc8bbe2e8d61c71b82e011f7a4862f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeKeyImpl&lt; DILexicalBlock &gt;::MDNodeKeyImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock">DILexicalBlock</a> * N)</td>
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



<p>Definition at line 914 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a9f7a19e72cf4d42979456c78cb743b9e">Column</a>, <a href="#a5cb9aa82741f1ed488d96c4183002a45">File</a>, <a href="#ae2f3210698409ea44bf525351cda6c39">Line</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a71da17880c2a210b965e997436081d59">Scope</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getHashValue() {#a824d05a2c608f7e21cfd61bef79869e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DILexicalBlock &gt;::getHashValue ()</td>
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



<p>Definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a9f7a19e72cf4d42979456c78cb743b9e">Column</a>, <a href="#a5cb9aa82741f1ed488d96c4183002a45">File</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="#ae2f3210698409ea44bf525351cda6c39">Line</a> and <a href="#a71da17880c2a210b965e997436081d59">Scope</a>.</p>

</div>
</div>

### isKeyOf() {#a3d93a75f9188a74bc77d8910f1e4132b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MDNodeKeyImpl&lt; DILexicalBlock &gt;::isKeyOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock">DILexicalBlock</a> * RHS)</td>
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



<p>Definition at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a9f7a19e72cf4d42979456c78cb743b9e">Column</a>, <a href="#a5cb9aa82741f1ed488d96c4183002a45">File</a>, <a href="#ae2f3210698409ea44bf525351cda6c39">Line</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a71da17880c2a210b965e997436081d59">Scope</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Column {#a9f7a19e72cf4d42979456c78cb743b9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DILexicalBlock &gt;::Column</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a824d05a2c608f7e21cfd61bef79869e4">getHashValue</a>, <a href="#a3d93a75f9188a74bc77d8910f1e4132b">isKeyOf</a>, <a href="#a7ddc8bbe2e8d61c71b82e011f7a4862f">MDNodeKeyImpl</a> and <a href="#a8d00611ccbdb4453a3739aeb6cea25f7">MDNodeKeyImpl</a>.</p>

</div>
</div>

### File {#a5cb9aa82741f1ed488d96c4183002a45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DILexicalBlock &gt;::File</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a824d05a2c608f7e21cfd61bef79869e4">getHashValue</a>, <a href="#a3d93a75f9188a74bc77d8910f1e4132b">isKeyOf</a>, <a href="#a7ddc8bbe2e8d61c71b82e011f7a4862f">MDNodeKeyImpl</a> and <a href="#a8d00611ccbdb4453a3739aeb6cea25f7">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Line {#ae2f3210698409ea44bf525351cda6c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DILexicalBlock &gt;::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a824d05a2c608f7e21cfd61bef79869e4">getHashValue</a>, <a href="#a3d93a75f9188a74bc77d8910f1e4132b">isKeyOf</a>, <a href="#a7ddc8bbe2e8d61c71b82e011f7a4862f">MDNodeKeyImpl</a> and <a href="#a8d00611ccbdb4453a3739aeb6cea25f7">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Scope {#a71da17880c2a210b965e997436081d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DILexicalBlock &gt;::Scope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 907 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a824d05a2c608f7e21cfd61bef79869e4">getHashValue</a>, <a href="#a3d93a75f9188a74bc77d8910f1e4132b">isKeyOf</a>, <a href="#a7ddc8bbe2e8d61c71b82e011f7a4862f">MDNodeKeyImpl</a> and <a href="#a8d00611ccbdb4453a3739aeb6cea25f7">MDNodeKeyImpl</a>.</p>

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
