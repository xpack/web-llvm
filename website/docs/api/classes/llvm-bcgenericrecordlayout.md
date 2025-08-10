---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bcgenericrecordlayout
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BCGenericRecordLayout` Class Template

<p>Represents a single bitcode record type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IDField, typename... Fields&gt;
class llvm::BCGenericRecordLayout&lt;IDField, Fields&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">llvm/Bitcode/BitcodeConvenience.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IDField, typename... Fields&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac8ea0d34c1e141c2006c2ce26d416821">BCGenericRecordLayout</a> (llvm::BitstreamWriter &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a layout and register it with the given bitstream writer. <a href="#ac8ea0d34c1e141c2006c2ce26d416821">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BufferTy, typename... Data&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#affac6c467a59df0f58e3afdbeced562c">emit</a> (BufferTy &amp;buffer, unsigned id, Data &amp;&amp;...data) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a record to the bitstream writer, using the given buffer for scratch space. <a href="#affac6c467a59df0f58e3afdbeced562c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IDField, typename... Fields&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae1ae4bb0108500816aa2713426c69463">AbbrevCode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The abbreviation code used for this record in the current block. <a href="#ae1ae4bb0108500816aa2713426c69463">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IDField, typename... Fields&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">llvm::BitstreamWriter</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adc5b382cdda1d879aba329fcfacfccf3">Stream</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IDField, typename... Fields&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab3cc720dad36b79110fec48fa44d7b9">emitAbbrev</a> (llvm::BitstreamWriter &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers this record's layout with the bitstream reader. <a href="#aab3cc720dad36b79110fec48fa44d7b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BufferTy, typename... Data&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae7d7f30535b188ea68c4b3b617ad0483">emitRecord</a> (llvm::BitstreamWriter &amp;Stream, BufferTy &amp;buffer, unsigned abbrCode, unsigned recordID, Data &amp;&amp;...data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a record identified by <span class="doxyComputerOutput">abbrCode</span> to bitstream reader <span class="doxyComputerOutput">Stream</span>, using <span class="doxyComputerOutput">buffer</span> for scratch space. <a href="#ae7d7f30535b188ea68c4b3b617ad0483">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ElementTy, typename... Data&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add884a0033e0ba600114f12cc3ccd229">readRecord</a> (ArrayRef&lt; ElementTy &gt; buffer, Data &amp;&amp;...data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract record data from <span class="doxyComputerOutput">buffer</span> into the given data fields. <a href="#add884a0033e0ba600114f12cc3ccd229">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BufferTy, typename... Data&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa8a015d7d91c6367f5c59c47f7303eb0">readRecord</a> (BufferTy &amp;buffer, Data &amp;&amp;...data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract record data from <span class="doxyComputerOutput">buffer</span> into the given data fields. <a href="#aa8a015d7d91c6367f5c59c47f7303eb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents a single bitcode record type.</p>


<p>This class template is meant to be instantiated and then given a name, so that from then on that name can be used.</p>


<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BCGenericRecordLayout() {#ac8ea0d34c1e141c2006c2ce26d416821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IDField, typename... Fields&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BCGenericRecordLayout&lt; IDField, Fields &gt;::BCGenericRecordLayout (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">llvm::BitstreamWriter</a> &amp; Stream)</td>
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

<p>Create a layout and register it with the given bitstream writer.</p>

<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#affac6c467a59df0f58e3afdbeced562c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BufferTy, typename... Data&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BCGenericRecordLayout&lt; IDField, Fields &gt;::emit (BufferTy &amp; buffer, unsigned id, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">Data</a> &amp;&amp;... data)</td>
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

<p>Emit a record to the bitstream writer, using the given buffer for scratch space.</p>


<p>Note that even fixed arguments must be specified here.</p>


<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AbbrevCode {#ae1ae4bb0108500816aa2713426c69463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IDField, typename... Fields&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::BCGenericRecordLayout&lt; IDField, Fields &gt;::AbbrevCode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The abbreviation code used for this record in the current block.</p>


<p>Note that this is not the same as the semantic record code, which is the first field of the record.</p>


<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Stream {#adc5b382cdda1d879aba329fcfacfccf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IDField, typename... Fields&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitstreamWriter&amp; llvm::BCGenericRecordLayout&lt; IDField, Fields &gt;::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### emitAbbrev() {#aab3cc720dad36b79110fec48fa44d7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IDField, typename... Fields&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BCGenericRecordLayout&lt; IDField, Fields &gt;::emitAbbrev (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">llvm::BitstreamWriter</a> &amp; Stream)</td>
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

<p>Registers this record's layout with the bitstream reader.</p>


<p>eturns The abbreviation code for the newly-registered record type.</p>


<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>

</div>
</div>

### emitRecord() {#ae7d7f30535b188ea68c4b3b617ad0483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BufferTy, typename... Data&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BCGenericRecordLayout&lt; IDField, Fields &gt;::emitRecord (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">llvm::BitstreamWriter</a> &amp; Stream, BufferTy &amp; buffer, unsigned abbrCode, unsigned recordID, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">Data</a> &amp;&amp;... data)</td>
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

<p>Emit a record identified by <span class="doxyComputerOutput">abbrCode</span> to bitstream reader <span class="doxyComputerOutput">Stream</span>, using <span class="doxyComputerOutput">buffer</span> for scratch space.</p>


<p>Note that even fixed arguments must be specified here. Blobs are passed as StringRefs, while arrays can be passed inline, as aggregates, or as pre-encoded <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> data. Skipped values and empty arrays should use the special Nothing value.</p>


<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>


<p>Referenced by <a href="#affac6c467a59df0f58e3afdbeced562c">llvm::BCGenericRecordLayout&lt; BCLiteral&lt; RecordCode &gt;, Fields... &gt;::emit</a>.</p>

</div>
</div>

### readRecord() {#add884a0033e0ba600114f12cc3ccd229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ElementTy, typename... Data&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BCGenericRecordLayout&lt; IDField, Fields &gt;::readRecord (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; ElementTy &gt; buffer, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">Data</a> &amp;&amp;... data)</td>
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

<p>Extract record data from <span class="doxyComputerOutput">buffer</span> into the given data fields.</p>


<p>Note that even fixed arguments must be specified here. <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> <span class="doxyComputerOutput">Nothing</span> if you don't care about a particular parameter. Blob data is not included in the buffer and should be handled separately by the caller.</p>


<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>


<p>Referenced by <a href="#aa8a015d7d91c6367f5c59c47f7303eb0">llvm::BCGenericRecordLayout&lt; BCLiteral&lt; RecordCode &gt;, Fields... &gt;::readRecord</a>.</p>

</div>
</div>

### readRecord() {#aa8a015d7d91c6367f5c59c47f7303eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BufferTy, typename... Data&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BCGenericRecordLayout&lt; IDField, Fields &gt;::readRecord (BufferTy &amp; buffer, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">Data</a> &amp;&amp;... data)</td>
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

<p>Extract record data from <span class="doxyComputerOutput">buffer</span> into the given data fields.</p>


<p>Note that even fixed arguments must be specified here. <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> <span class="doxyComputerOutput">Nothing</span> if you don't care about a particular parameter. Blob data is not included in the buffer and should be handled separately by the caller.</p>


<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeconvenience-h">BitcodeConvenience.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
