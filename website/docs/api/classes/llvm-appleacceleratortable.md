---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/appleacceleratortable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AppleAcceleratorTable` Class

<p>This implements the Apple accelerator table format, a precursor of the DWARF 5 accelerator table format. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AppleAcceleratorTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">llvm/DebugInfo/DWARF/DWARFAcceleratorTable.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable">DWARFAcceleratorTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The accelerator tables are designed to allow efficient random access (using a symbol name as a key) into debug info by providing an index of the debug info DIEs. <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e128b0501d9d0ea1660bcf91020d6d8">AppleAcceleratorTable</a> (const DWARFDataExtractor &amp;AccelSection, DataExtractor StringSection)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03c6ddff22ebc41466903c966d7e7655">extract</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26d6f3f7320f8d31f0250d7bf6fa7e6b">getNumBuckets</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3aed8c66799dcb2f8e54d51fbcc85fc">getNumHashes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a871aab12ee974991f9304e96d0610979">getSizeHdr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9cce643f443850fca6cc8d0c0fd6aa4">getHeaderDataLength</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab753a496e54ed26c7747b79fd48ec76c">getHashDataEntryLength</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of one HashData entry. <a href="#ab753a496e54ed26c7747b79fd48ec76c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; HeaderData::AtomType, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">HeaderData::Form</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac764ab3480bb5c7832100c436203adc4">getAtomsDesc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the Atom description, which can be used to interpret the raw values of the Accelerator Entries in this table. <a href="#ac764ab3480bb5c7832100c436203adc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b655e3d8fe640c8fc4bf873b0f9738c">containsAtomType</a> (HeaderData::AtomType AtomTy) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff <span class="doxyComputerOutput">AtomTy</span> is one of the atoms available in Entries of this table. <a href="#a7b655e3d8fe640c8fc4bf873b0f9738c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5281584900ceee9be87126630f1fae12">validateForms</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a916b783c03f11e76d5144b3468d0c775">readAtoms</a> (uint64_t *HashDataOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return information related to the DWARF <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> we're looking for when performing a lookup by name. <a href="#a916b783c03f11e76d5144b3468d0c775">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdb9058a51e2fb5fd61d203dcdfd551a">dump</a> (raw_ostream &amp;OS) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/samenameiterator">SameNameIterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11c62084389a9ff84f504ab422ea3923">equal_range</a> (StringRef Key) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up all entries in the accelerator table matching <span class="doxyComputerOutput">Key</span>. <a href="#a11c62084389a9ff84f504ab422ea3923">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6f81e43d4530aa78102f8a5103bc9b9">entries</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup all entries in the accelerator table. <a href="#ae6f81e43d4530aa78102f8a5103bc9b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac218b64f001f382aeb3ee139c852cc0c">dumpName</a> (ScopedPrinter &amp;W, SmallVectorImpl&lt; DWARFFormValue &gt; &amp;AtomForms, uint64_t *DataOffset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we should continue scanning for entries or false if we've reached the last (sentinel) entry of encountered a parsing error. <a href="#ac218b64f001f382aeb3ee139c852cc0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf89fd8e7fd699bc183085eb9cd07c6c">readU32FromAccel</a> (uint64_t &amp;Offset, bool UseRelocation=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads an uint32_t from the accelerator table at Offset, which is incremented by the number of bytes read. <a href="#adf89fd8e7fd699bc183085eb9cd07c6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e64f348d86e13a99ee86a8d35b75f7">readStringFromStrSection</a> (uint64_t StringSectionOffset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> from the string table at Offset. <a href="#af6e64f348d86e13a99ee86a8d35b75f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6fcaf80296e789c1e79af7dfc4cb66">getBucketBase</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the offset into the section where the Buckets begin. <a href="#abe6fcaf80296e789c1e79af7dfc4cb66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d81e16df4f65279be8e765440346e66">getIthBucketBase</a> (uint32_t I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the offset into the section where the I-th bucket is. <a href="#a5d81e16df4f65279be8e765440346e66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52acfda5ba13d56d672c604ba649b598">getHashBase</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the offset into the section where the hash list begins. <a href="#a52acfda5ba13d56d672c604ba649b598">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac18b67ab736bbeafda91abd9604d3523">getIthHashBase</a> (uint32_t I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the offset into the section where the I-th hash is. <a href="#ac18b67ab736bbeafda91abd9604d3523">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ddea269300516ef2a36dec6ad099e93">getOffsetBase</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the offset into the section where the offset list begins. <a href="#a0ddea269300516ef2a36dec6ad099e93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac36b9bfb072b0d29885284261a32ec51">getEntriesBase</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the offset into the section where the table entries begin. <a href="#ac36b9bfb072b0d29885284261a32ec51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e66d39926b0d2f25a305eeb3b5b8a8c">getIthOffsetBase</a> (uint32_t I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the offset into the section where the I-th offset is. <a href="#a0e66d39926b0d2f25a305eeb3b5b8a8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2faebaf550ef610ed9eb2db78227f4d0">hashToBucketIdx</a> (uint32_t Hash) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the index of the bucket where a hypothetical Hash would be. <a href="#a2faebaf550ef610ed9eb2db78227f4d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59cbe0bf03dd86422e1f718f325d3190">wouldHashBeInBucket</a> (uint32_t Hash, uint32_t BucketIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff a hypothetical Hash would be assigned to the BucketIdx-th bucket. <a href="#a59cbe0bf03dd86422e1f718f325d3190">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d608eb10afe5464ca9dff73bff0a00e">readIthBucket</a> (uint32_t I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads the contents of the I-th bucket, that is, the index in the hash list where the hashes corresponding to this bucket begin. <a href="#a8d608eb10afe5464ca9dff73bff0a00e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa196d8c520fb9ad19d2e6ecc1ce3fc17">readIthHash</a> (uint32_t I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads the I-th hash in the hash list. <a href="#aa196d8c520fb9ad19d2e6ecc1ce3fc17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29713e657bc23f0588950636b0fefaa6">readIthOffset</a> (uint32_t I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads the I-th offset in the offset list. <a href="#a29713e657bc23f0588950636b0fefaa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5f9c4b1597ce32bcb4b14234446bcb">readStringOffsetAt</a> (uint64_t &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads a string offset from the accelerator table at Offset, which is incremented by the number of bytes read. <a href="#a0f5f9c4b1597ce32bcb4b14234446bcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad593a1faccce6c8360427ce70d42e097">idxOfHashInBucket</a> (uint32_t HashToFind, uint32_t BucketIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scans through all Hashes in the BucketIdx-th bucket, attempting to find HashToFind. <a href="#ad593a1faccce6c8360427ce70d42e097">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Header</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b38d7da26427e74d676e9528cafba38">Hdr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">HeaderData</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87bb2675add0a64ba61b8e37f70797f6">HdrData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8657abbfbe16fffa995c55ef07088f38">FormParams</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2734eac358750afda705f7f6077f3a1e">HashDataEntryLength</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa20f5cc5929b4f9c7fa9f9faaec3db48">IsValid</a> = false</td>
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

<p>This implements the Apple accelerator table format, a precursor of the DWARF 5 accelerator table format.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AppleAcceleratorTable() {#a1e128b0501d9d0ea1660bcf91020d6d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AppleAcceleratorTable::AppleAcceleratorTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> &amp; AccelSection, <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> StringSection)</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/#ae9e1078ab559cff15bdc6684349b26c9">llvm::DWARFAcceleratorTable::AccelSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/#a84b11a2c5bc8a48c0a56a5d3c3157fcf">llvm::DWARFAcceleratorTable::DWARFAcceleratorTable</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/#ab98aea29cf744ad97a6bc77ba51b9aa7">llvm::DWARFAcceleratorTable::StringSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/appleacceleratortable/entrywithname/#a117eec926dfb8989b6deb569474f34d6">llvm::AppleAcceleratorTable::EntryWithName::EntryWithName</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/iterator/#ae09b5763e8186c246faa42a434bcec8d">llvm::AppleAcceleratorTable::Iterator::Iterator</a> and <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/samenameiterator/#a72051e1542a8dc294384369605f3aad3">llvm::AppleAcceleratorTable::SameNameIterator::SameNameIterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### containsAtomType() {#a7b655e3d8fe640c8fc4bf873b0f9738c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AppleAcceleratorTable::containsAtomType (HeaderData::AtomType AtomTy)</td>
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

<p>Returns true iff <span class="doxyComputerOutput">AtomTy</span> is one of the atoms available in Entries of this table.</p>

<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f02feabe2798347395e53d18da48f96">llvm::make_first_range</a>.</p>

</div>
</div>

### dump() {#abdb9058a51e2fb5fd61d203dcdfd551a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void AppleAcceleratorTable::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/#ae9e1078ab559cff15bdc6684349b26c9">llvm::DWARFAcceleratorTable::AccelSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp/#aa975c3a1b5eb8ee021c8746cdd7de4fb">formatAtom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#ab753a496e54ed26c7747b79fd48ec76c">getHashDataEntryLength</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>.</p>

</div>
</div>

### entries() {#ae6f81e43d4530aa78102f8a5103bc9b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::AppleAcceleratorTable::entries ()</td>
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

<p>Lookup all entries in the accelerator table.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### equal\_range() {#a11c62084389a9ff84f504ab422ea3923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; AppleAcceleratorTable::SameNameIterator &gt; AppleAcceleratorTable::equal_range (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look up all entries in the accelerator table matching <span class="doxyComputerOutput">Key</span>.</p>

<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/#ae9e1078ab559cff15bdc6684349b26c9">llvm::DWARFAcceleratorTable::AccelSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba816fb56fad484d9cd712825dcacaa6">llvm::djbHash</a>, <a href="#ab753a496e54ed26c7747b79fd48ec76c">getHashDataEntryLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### extract() {#a03c6ddff22ebc41466903c966d7e7655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error AppleAcceleratorTable::extract ()</td>
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



<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/#ae9e1078ab559cff15bdc6684349b26c9">llvm::DWARFAcceleratorTable::AccelSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga4863132f9f3dd24b6df4cfc6c9cfb676">llvm::dwarf::FormEncodingString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa03b0ad8792b784269332332eb61d8ad">llvm::dwarf::getFixedFormByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba53a9e57a679708b2d8ff0ccd8ec96b18">llvm::illegal_byte_sequence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baa55e82356e9721946aa9ba954733c6f0">llvm::not_supported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a276e8a32e0bbf024aadd9420b8f2d3b3">offsetof</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getAtomsDesc() {#ac764ab3480bb5c7832100c436203adc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; AppleAcceleratorTable::HeaderData::AtomType, AppleAcceleratorTable::HeaderData::Form &gt; &gt; AppleAcceleratorTable::getAtomsDesc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the Atom description, which can be used to interpret the raw values of the Accelerator Entries in this table.</p>

<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Referenced by <a href="#a916b783c03f11e76d5144b3468d0c775">readAtoms</a> and <a href="#a5281584900ceee9be87126630f1fae12">validateForms</a>.</p>

</div>
</div>

### getHashDataEntryLength() {#ab753a496e54ed26c7747b79fd48ec76c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AppleAcceleratorTable::getHashDataEntryLength ()</td>
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

<p>Returns the size of one HashData entry.</p>

<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#abdb9058a51e2fb5fd61d203dcdfd551a">dump</a> and <a href="#a11c62084389a9ff84f504ab422ea3923">equal_range</a>.</p>

</div>
</div>

### getHeaderDataLength() {#ad9cce643f443850fca6cc8d0c0fd6aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t AppleAcceleratorTable::getHeaderDataLength ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

### getNumBuckets() {#a26d6f3f7320f8d31f0250d7bf6fa7e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t AppleAcceleratorTable::getNumBuckets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

### getNumHashes() {#aa3aed8c66799dcb2f8e54d51fbcc85fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t AppleAcceleratorTable::getNumHashes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

### getSizeHdr() {#a871aab12ee974991f9304e96d0610979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t AppleAcceleratorTable::getSizeHdr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

### readAtoms() {#a916b783c03f11e76d5144b3468d0c775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, dwarf::Tag &gt; AppleAcceleratorTable::readAtoms (uint64_t * HashDataOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return information related to the DWARF <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> we're looking for when performing a lookup by name.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">HashDataOffset</td>
<td class="doxyParamItemDescription"><p>an offset into the hash data table</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>&lt;DieOffset, DieTag&gt; DieOffset is the offset into the .debug_info section for the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> related to the input hash data offset. DieTag is the tag of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></p></dd>
</dl>


<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/#ae9e1078ab559cff15bdc6684349b26c9">llvm::DWARFAcceleratorTable::AccelSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da729ef8a54240d5ae532c7261914cae96">llvm::dwarf::DW_ATOM_die_offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da297d590afe629760c5523b1a3e907941">llvm::dwarf::DW_ATOM_die_tag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a8cf7e4c313bcdcec4f781bbcd2c815bf">llvm::dwarf::DW_INVALID_OFFSET</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#aa146755e2500aea560c4417a30c0b96b">llvm::DWARFFormValue::extractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#acf6d7ec7b1699c2bf60e54e032aae623">llvm::DWARFFormValue::getAsUnsignedConstant</a> and <a href="#ac764ab3480bb5c7832100c436203adc4">getAtomsDesc</a>.</p>

</div>
</div>

### validateForms() {#a5281584900ceee9be87126630f1fae12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AppleAcceleratorTable::validateForms ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da729ef8a54240d5ae532c7261914cae96">llvm::dwarf::DW_ATOM_die_offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da297d590afe629760c5523b1a3e907941">llvm::dwarf::DW_ATOM_die_tag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da004bb656ad7f6bb23d888a35111de0a8">llvm::dwarf::DW_ATOM_type_flags</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228a9190be54233acc999af9cb02ed854c0f">llvm::DWARFFormValue::FC_Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228aa32d75d2d5fc3faca059726ac4615fd2">llvm::DWARFFormValue::FC_Flag</a>, <a href="#ac764ab3480bb5c7832100c436203adc4">getAtomsDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#afae7527783aa2e969040c3cfcb4070c6">llvm::DWARFFormValue::getForm</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a7f4acdd5d8a9b78623878262b10f8e4f">llvm::DWARFFormValue::isFormClass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### dumpName() {#ac218b64f001f382aeb3ee139c852cc0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AppleAcceleratorTable::dumpName (<a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &gt; &amp; AtomForms, uint64_t * DataOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if we should continue scanning for entries or false if we've reached the last (sentinel) entry of encountered a parsing error.</p>

<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

### getBucketBase() {#abe6fcaf80296e789c1e79af7dfc4cb66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AppleAcceleratorTable::getBucketBase ()</td>
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

<p>Return the offset into the section where the Buckets begin.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### getEntriesBase() {#ac36b9bfb072b0d29885284261a32ec51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AppleAcceleratorTable::getEntriesBase ()</td>
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

<p>Return the offset into the section where the table entries begin.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### getHashBase() {#a52acfda5ba13d56d672c604ba649b598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AppleAcceleratorTable::getHashBase ()</td>
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

<p>Return the offset into the section where the hash list begins.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### getIthBucketBase() {#a5d81e16df4f65279be8e765440346e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AppleAcceleratorTable::getIthBucketBase (uint32_t I)</td>
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

<p>Return the offset into the section where the I-th bucket is.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### getIthHashBase() {#ac18b67ab736bbeafda91abd9604d3523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AppleAcceleratorTable::getIthHashBase (uint32_t I)</td>
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

<p>Return the offset into the section where the I-th hash is.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### getIthOffsetBase() {#a0e66d39926b0d2f25a305eeb3b5b8a8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AppleAcceleratorTable::getIthOffsetBase (uint32_t I)</td>
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

<p>Return the offset into the section where the I-th offset is.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### getOffsetBase() {#a0ddea269300516ef2a36dec6ad099e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AppleAcceleratorTable::getOffsetBase ()</td>
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

<p>Return the offset into the section where the offset list begins.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### hashToBucketIdx() {#a2faebaf550ef610ed9eb2db78227f4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AppleAcceleratorTable::hashToBucketIdx (uint32_t Hash)</td>
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

<p>Returns the index of the bucket where a hypothetical Hash would be.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### idxOfHashInBucket() {#ad593a1faccce6c8360427ce70d42e097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; AppleAcceleratorTable::idxOfHashInBucket (uint32_t HashToFind, uint32_t BucketIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scans through all Hashes in the BucketIdx-th bucket, attempting to find HashToFind.</p>


<p>If it is found, its index in the list of hashes is returned.</p>


<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

### readIthBucket() {#a8d608eb10afe5464ca9dff73bff0a00e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::AppleAcceleratorTable::readIthBucket (uint32_t I)</td>
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

<p>Reads the contents of the I-th bucket, that is, the index in the hash list where the hashes corresponding to this bucket begin.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### readIthHash() {#aa196d8c520fb9ad19d2e6ecc1ce3fc17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::AppleAcceleratorTable::readIthHash (uint32_t I)</td>
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

<p>Reads the I-th hash in the hash list.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### readIthOffset() {#a29713e657bc23f0588950636b0fefaa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::AppleAcceleratorTable::readIthOffset (uint32_t I)</td>
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

<p>Reads the I-th offset in the offset list.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### readStringFromStrSection() {#af6e64f348d86e13a99ee86a8d35b75f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; AppleAcceleratorTable::readStringFromStrSection (uint64_t StringSectionOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reads a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> from the string table at Offset.</p>

<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

### readStringOffsetAt() {#a0f5f9c4b1597ce32bcb4b14234446bcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::AppleAcceleratorTable::readStringOffsetAt (uint64_t &amp; Offset)</td>
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

<p>Reads a string offset from the accelerator table at Offset, which is incremented by the number of bytes read.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### readU32FromAccel() {#adf89fd8e7fd699bc183085eb9cd07c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; AppleAcceleratorTable::readU32FromAccel (uint64_t &amp; Offset, bool UseRelocation=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reads an uint32_t from the accelerator table at Offset, which is incremented by the number of bytes read.</p>

<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

### wouldHashBeInBucket() {#a59cbe0bf03dd86422e1f718f325d3190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AppleAcceleratorTable::wouldHashBeInBucket (uint32_t Hash, uint32_t BucketIdx)</td>
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

<p>Returns true iff a hypothetical Hash would be assigned to the BucketIdx-th bucket.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FormParams {#a8657abbfbe16fffa995c55ef07088f38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::FormParams llvm::AppleAcceleratorTable::FormParams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### HashDataEntryLength {#a2734eac358750afda705f7f6077f3a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AppleAcceleratorTable::HashDataEntryLength</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### Hdr {#a4b38d7da26427e74d676e9528cafba38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Header llvm::AppleAcceleratorTable::Hdr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### HdrData {#a87bb2675add0a64ba61b8e37f70797f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HeaderData llvm::AppleAcceleratorTable::HdrData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### IsValid {#aa20f5cc5929b4f9c7fa9f9faaec3db48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AppleAcceleratorTable::IsValid = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
