---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/raw-pwrite-stream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `raw_pwrite_stream` Class

<p>An abstract base class for streams implementations that also support a pwrite operation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::raw_pwrite_stream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class implements an extremely fast bulk output stream that can <em>only</em> output to a stream. <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that writes to a file descriptor. <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-null-ostream">raw_null_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that discards all output. <a href="/web-llvm/docs/api/classes/llvm/raw-null-ostream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that writes to an <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> or <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>. <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6114ce21446653490e1d609d876b42eb">raw_pwrite_stream</a> (bool Unbuffered=false, OStreamKind K=OStreamKind::OK_OStream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a004bff5f9c00b2ede3a52c93c665c2">pwrite</a> (const char *Ptr, size_t Size, uint64_t Offset)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91f5b2713f703e82a436d5a79173aa53">pwrite_impl</a> (const char *Ptr, size_t Size, uint64_t Offset)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac164642744bda105c0052fc7143c8360">anchor</a> () override</td>
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

<p>An abstract base class for streams implementations that also support a pwrite operation.</p>


<p>This is useful for code that can mostly stream out data, but needs to patch in a header that needs to know the output size.</p>


<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### raw\_pwrite\_stream() {#a6114ce21446653490e1d609d876b42eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::raw_pwrite_stream::raw_pwrite_stream (bool Unbuffered=false, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad85a9ad7858d658c954afde33bcf3d43">OStreamKind</a> K=<a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad85a9ad7858d658c954afde33bcf3d43a2bdd687fb19e606203cb02f5c50bf07b">OStreamKind::OK_OStream</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad85a9ad7858d658c954afde33bcf3d43a2bdd687fb19e606203cb02f5c50bf07b">llvm::raw_ostream::OK_OStream</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f4b64a0f7aec0a02e7f2ff5a6552723">llvm::raw_ostream::raw_ostream</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a8006c8875484467031d61b1e671cfede">llvm::raw_fd_ostream::raw_fd_ostream</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#ac5de2c3f4305e6a5f5a6076e5f60c7d7">llvm::raw_svector_ostream::raw_svector_ostream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### pwrite() {#a9a004bff5f9c00b2ede3a52c93c665c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_pwrite_stream::pwrite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size, uint64_t Offset)</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-wasmobjectwriter-cpp-/#adad5590d922967efb0f15ac9abfaef4b">anonymous{WasmObjectWriter.cpp}::patchI32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-wasmobjectwriter-cpp-/#a2f9c5a29000c354facddf3731e390d56">anonymous{WasmObjectWriter.cpp}::patchI64</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a27e478bd5208561e8eb16ec550509761">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeObject</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-wasmobjectwriter-cpp-/#afe54cb1b28952ae642f7ee7e61d3f2d1">anonymous{WasmObjectWriter.cpp}::writePatchableSLEB</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-wasmobjectwriter-cpp-/#a7a9e8962620a1121fe60fa4717527d89">anonymous{WasmObjectWriter.cpp}::writePatchableULEB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#ac164642744bda105c0052fc7143c8360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_pwrite_stream::anchor ()</td>
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



<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

### pwrite\_impl() {#a91f5b2713f703e82a436d5a79173aa53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::raw_pwrite_stream::pwrite_impl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size, uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
