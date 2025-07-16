---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/detail/bcrecordcoding
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BCRecordCoding` Class Template Reference

<p>Helper class for dealing with a scalar element in the middle of a record. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ElementTy, typename... Fields&gt;
class llvm::detail::BCRecordCoding&lt;ElementTy, Fields&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">llvm/Bitcode/BitcodeConvenience.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BufferTy, typename ElementDataTy, typename... DataTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6e68e79dc245aeff38c710e106e0b29">emit</a> (llvm::BitstreamWriter &amp;Stream, BufferTy &amp;buffer, unsigned code, ElementDataTy element, DataTy &amp;&amp;...data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename ElementDataTy, typename... DataTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a899ed81dbda72496c2d105042da6acef">read</a> (ArrayRef&lt; T &gt; buffer, ElementDataTy &amp;element, DataTy &amp;&amp;...data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename... DataTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af455dc61361369b5ef61f16db37c3c66">read</a> (ArrayRef&lt; T &gt; buffer, std::nullopt_t, DataTy &amp;&amp;...data)</td>
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

<p>Helper class for dealing with a scalar element in the middle of a record.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/bcrecordlayout">BCRecordLayout</a></p></dd>
</dl>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### emit() {#ab6e68e79dc245aeff38c710e106e0b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BufferTy, typename ElementDataTy, typename... DataTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::emit (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">llvm::BitstreamWriter</a> &amp; Stream, BufferTy &amp; buffer, unsigned code, ElementDataTy element, DataTy &amp;&amp;... data)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a> and <a href="#ab6e68e79dc245aeff38c710e106e0b29">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::emit</a>.</p>


<p>Referenced by <a href="#ab6e68e79dc245aeff38c710e106e0b29">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-e92e567fbcfc8afd44242d623ff29b96/#a707d66256835aaba5f53cf6157df99ad">llvm::detail::BCRecordCoding&lt; BCArray&lt; ElementTy &gt; &gt;::emit</a> and <a href="/web-llvm/docs/api/classes/llvm/bcgenericrecordlayout/#ae7d7f30535b188ea68c4b3b617ad0483">llvm::BCGenericRecordLayout&lt; BCLiteral&lt; RecordCode &gt;, Fields... &gt;::emitRecord</a>.</p>

</div>
</div>

### read() {#a899ed81dbda72496c2d105042da6acef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename ElementDataTy, typename... DataTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; buffer, ElementDataTy &amp; element, DataTy &amp;&amp;... data)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="#a899ed81dbda72496c2d105042da6acef">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>.</p>


<p>Referenced by <a href="#a899ed81dbda72496c2d105042da6acef">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read</a>, <a href="#af455dc61361369b5ef61f16db37c3c66">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read</a> and <a href="/web-llvm/docs/api/classes/llvm/bcgenericrecordlayout/#add884a0033e0ba600114f12cc3ccd229">llvm::BCGenericRecordLayout&lt; BCLiteral&lt; RecordCode &gt;, Fields... &gt;::readRecord</a>.</p>

</div>
</div>

### read() {#af455dc61361369b5ef61f16db37c3c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename... DataTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; buffer, std::nullopt_t, DataTy &amp;&amp;... data)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#a899ed81dbda72496c2d105042da6acef">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
