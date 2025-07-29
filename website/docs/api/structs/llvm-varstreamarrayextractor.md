---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/varstreamarrayextractor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `VarStreamArrayExtractor` Struct Template

<p><a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor">VarStreamArrayExtractor</a> is intended to be specialized to provide customized extraction logic. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::VarStreamArrayExtractor&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamarray-h">llvm/Support/BinaryStreamArray.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e7a87abc173694df4fd4f9255636528">operator()</a> (BinaryStreamRef Stream, uint32_t &amp;Len, T &amp;Item) const =delete</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor">VarStreamArrayExtractor</a> is intended to be specialized to provide customized extraction logic.</p>


<p>On input it receives a <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> pointing to the beginning of the next record, but where the length of the record is not yet known. Upon completion, it should return an appropriate <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> instance if a record could not be extracted, or if one could be extracted it should return success and set Len to the number of bytes this record occupied in the underlying stream, and it should fill out the fields of the value type Item appropriately to represent the current record.</p>


<p>You can specialize this template for your own custom value types to avoid having to specify a second template argument to <a href="/web-llvm/docs/api/classes/llvm/varstreamarray">VarStreamArray</a> (documented below).</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamarray-h">BinaryStreamArray.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator()() {#a4e7a87abc173694df4fd4f9255636528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error VarStreamArrayExtractor::operator() (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> Stream, uint32_t &amp; Len, T &amp; Item)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamarray-h">BinaryStreamArray.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugchecksumssubsection-cpp">DebugChecksumsSubsection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/filechecksumentry/#af59eceeffd95dc0b17cfc7b3e0b4f5aa">llvm::codeview::FileChecksumEntry::Checksum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/filechecksumentry/#a07a498fcd876bdc77f36ee3c29f98ce4">llvm::codeview::FileChecksumEntry::FileNameOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/filechecksumentry/#a547715a93f80c48c1f0d683b81b334b1">llvm::codeview::FileChecksumEntry::Kind</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a2d56063bcd6039c9372e485e609cf692">llvm::BinaryStreamReader::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a07e25e055f92f545f94821c4a3cbded8">llvm::BinaryStreamReader::readObject</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamarray-h">BinaryStreamArray.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugchecksumssubsection-cpp">DebugChecksumsSubsection.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
