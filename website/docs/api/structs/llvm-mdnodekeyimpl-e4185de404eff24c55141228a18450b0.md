---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mdnodekeyimpl-e4185de404eff24c55141228a18450b0
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
struct llvm::MDNodeKeyImpl&lt;DIStringType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">IR/LLVMContextImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d1a457d25f9a4f2217260cb6698ccdb">MDNodeKeyImpl</a> (unsigned Tag, MDString *Name, Metadata *StringLength, Metadata *StringLengthExp, Metadata *StringLocationExp, uint64_t SizeInBits, uint32_t AlignInBits, unsigned Encoding)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7773090aff21c5087a36f883d73f5285">MDNodeKeyImpl</a> (const DIStringType *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1d82eccc72b6d5ff09a4b58e8216c6e">isKeyOf</a> (const DIStringType *RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef4a1754c64f761318d93c1ab3a9ba71">getHashValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f388f541298474488e0f092c0d5ebf">Tag</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a1c519f0daf2ae94459b78ecc798b50">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1227e97cc2f4762c0f3da5aa4fb10d4">StringLength</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3f03837c35708859b1a593a99643da4">StringLengthExp</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9772d0789c88fa09bdc432163ac6556">StringLocationExp</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a696121487162230841741a9845a2aa57">SizeInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab202f1390648f846ae79a51cab98a2e4">AlignInBits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab842b4d6f3da043a758b5f87d12a50bc">Encoding</a></td>
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


<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MDNodeKeyImpl() {#a8d1a457d25f9a4f2217260cb6698ccdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeKeyImpl&lt; DIStringType &gt;::MDNodeKeyImpl (unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * StringLength, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * StringLengthExp, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * StringLocationExp, uint64_t SizeInBits, uint32_t AlignInBits, unsigned Encoding)</td>
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



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#ab202f1390648f846ae79a51cab98a2e4">AlignInBits</a>, <a href="#ab842b4d6f3da043a758b5f87d12a50bc">Encoding</a>, <a href="#a6a1c519f0daf2ae94459b78ecc798b50">Name</a>, <a href="#a696121487162230841741a9845a2aa57">SizeInBits</a>, <a href="#af1227e97cc2f4762c0f3da5aa4fb10d4">StringLength</a>, <a href="#ae3f03837c35708859b1a593a99643da4">StringLengthExp</a>, <a href="#ac9772d0789c88fa09bdc432163ac6556">StringLocationExp</a> and <a href="#a14f388f541298474488e0f092c0d5ebf">Tag</a>.</p>

</div>
</div>

### MDNodeKeyImpl() {#a7773090aff21c5087a36f883d73f5285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeKeyImpl&lt; DIStringType &gt;::MDNodeKeyImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> * N)</td>
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



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#ab202f1390648f846ae79a51cab98a2e4">AlignInBits</a>, <a href="#ab842b4d6f3da043a758b5f87d12a50bc">Encoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a8094520fe3fe9f3967fe72b7266a2f68">getTag</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a6a1c519f0daf2ae94459b78ecc798b50">Name</a>, <a href="#a696121487162230841741a9845a2aa57">SizeInBits</a>, <a href="#af1227e97cc2f4762c0f3da5aa4fb10d4">StringLength</a>, <a href="#ae3f03837c35708859b1a593a99643da4">StringLengthExp</a>, <a href="#ac9772d0789c88fa09bdc432163ac6556">StringLocationExp</a> and <a href="#a14f388f541298474488e0f092c0d5ebf">Tag</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getHashValue() {#aef4a1754c64f761318d93c1ab3a9ba71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DIStringType &gt;::getHashValue ()</td>
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



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#ab842b4d6f3da043a758b5f87d12a50bc">Encoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="#a6a1c519f0daf2ae94459b78ecc798b50">Name</a>, <a href="#af1227e97cc2f4762c0f3da5aa4fb10d4">StringLength</a> and <a href="#a14f388f541298474488e0f092c0d5ebf">Tag</a>.</p>

</div>
</div>

### isKeyOf() {#ac1d82eccc72b6d5ff09a4b58e8216c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MDNodeKeyImpl&lt; DIStringType &gt;::isKeyOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> * RHS)</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#ab202f1390648f846ae79a51cab98a2e4">AlignInBits</a>, <a href="#ab842b4d6f3da043a758b5f87d12a50bc">Encoding</a>, <a href="#a6a1c519f0daf2ae94459b78ecc798b50">Name</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a696121487162230841741a9845a2aa57">SizeInBits</a>, <a href="#af1227e97cc2f4762c0f3da5aa4fb10d4">StringLength</a>, <a href="#ae3f03837c35708859b1a593a99643da4">StringLengthExp</a>, <a href="#ac9772d0789c88fa09bdc432163ac6556">StringLocationExp</a> and <a href="#a14f388f541298474488e0f092c0d5ebf">Tag</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AlignInBits {#ab202f1390648f846ae79a51cab98a2e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MDNodeKeyImpl&lt; DIStringType &gt;::AlignInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac1d82eccc72b6d5ff09a4b58e8216c6e">isKeyOf</a>, <a href="#a7773090aff21c5087a36f883d73f5285">MDNodeKeyImpl</a> and <a href="#a8d1a457d25f9a4f2217260cb6698ccdb">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Encoding {#ab842b4d6f3da043a758b5f87d12a50bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DIStringType &gt;::Encoding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#aef4a1754c64f761318d93c1ab3a9ba71">getHashValue</a>, <a href="#ac1d82eccc72b6d5ff09a4b58e8216c6e">isKeyOf</a>, <a href="#a7773090aff21c5087a36f883d73f5285">MDNodeKeyImpl</a> and <a href="#a8d1a457d25f9a4f2217260cb6698ccdb">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Name {#a6a1c519f0daf2ae94459b78ecc798b50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString* llvm::MDNodeKeyImpl&lt; DIStringType &gt;::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#aef4a1754c64f761318d93c1ab3a9ba71">getHashValue</a>, <a href="#ac1d82eccc72b6d5ff09a4b58e8216c6e">isKeyOf</a>, <a href="#a7773090aff21c5087a36f883d73f5285">MDNodeKeyImpl</a> and <a href="#a8d1a457d25f9a4f2217260cb6698ccdb">MDNodeKeyImpl</a>.</p>

</div>
</div>

### SizeInBits {#a696121487162230841741a9845a2aa57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MDNodeKeyImpl&lt; DIStringType &gt;::SizeInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac1d82eccc72b6d5ff09a4b58e8216c6e">isKeyOf</a>, <a href="#a7773090aff21c5087a36f883d73f5285">MDNodeKeyImpl</a> and <a href="#a8d1a457d25f9a4f2217260cb6698ccdb">MDNodeKeyImpl</a>.</p>

</div>
</div>

### StringLength {#af1227e97cc2f4762c0f3da5aa4fb10d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DIStringType &gt;::StringLength</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#aef4a1754c64f761318d93c1ab3a9ba71">getHashValue</a>, <a href="#ac1d82eccc72b6d5ff09a4b58e8216c6e">isKeyOf</a>, <a href="#a7773090aff21c5087a36f883d73f5285">MDNodeKeyImpl</a> and <a href="#a8d1a457d25f9a4f2217260cb6698ccdb">MDNodeKeyImpl</a>.</p>

</div>
</div>

### StringLengthExp {#ae3f03837c35708859b1a593a99643da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DIStringType &gt;::StringLengthExp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac1d82eccc72b6d5ff09a4b58e8216c6e">isKeyOf</a>, <a href="#a7773090aff21c5087a36f883d73f5285">MDNodeKeyImpl</a> and <a href="#a8d1a457d25f9a4f2217260cb6698ccdb">MDNodeKeyImpl</a>.</p>

</div>
</div>

### StringLocationExp {#ac9772d0789c88fa09bdc432163ac6556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DIStringType &gt;::StringLocationExp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac1d82eccc72b6d5ff09a4b58e8216c6e">isKeyOf</a>, <a href="#a7773090aff21c5087a36f883d73f5285">MDNodeKeyImpl</a> and <a href="#a8d1a457d25f9a4f2217260cb6698ccdb">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Tag {#a14f388f541298474488e0f092c0d5ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DIStringType &gt;::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#aef4a1754c64f761318d93c1ab3a9ba71">getHashValue</a>, <a href="#ac1d82eccc72b6d5ff09a4b58e8216c6e">isKeyOf</a>, <a href="#a7773090aff21c5087a36f883d73f5285">MDNodeKeyImpl</a> and <a href="#a8d1a457d25f9a4f2217260cb6698ccdb">MDNodeKeyImpl</a>.</p>

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
