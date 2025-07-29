---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ondiskiterablechainedhashtable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OnDiskIterableChainedHashTable` Class Template

<p>Provides lookup and iteration over an on disk hash table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename Info&gt;
class llvm::OnDiskIterableChainedHashTable&lt;Info&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">llvm/Support/OnDiskHashTable.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable">OnDiskChainedHashTable&lt;Info&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides lookup on an on disk hash table. <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable">OnDiskChainedHashTable</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> &gt; <a href="#ae159f6e71f97b64f924e906a7990ddc8">base_type</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#a7dc1418cabc4fb5b21e8b5ac2cea6082">base_type::internal_key_type</a> <a href="#a54929240b76c7b607c4104ac5b476461">internal_key_type</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#a4b1d29d4445b452af5a72affd2f0911b">base_type::external_key_type</a> <a href="#a7ae73e1c258dab7ffb74903aa69d8899">external_key_type</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#a5e739e477a5e2d63741971c5b538cbfd">base_type::data_type</a> <a href="#a6be647356c28c77e6301d64afc41ab02">data_type</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#a33d86d8f0e6643ddab5c3505bcf85dd6">base_type::hash_value_type</a> <a href="#a870639c44275f12ae0557ac7bc1d2eed">hash_value_type</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#a261c0872f78c9b40613b0f44083dc809">base_type::offset_type</a> <a href="#ab22fef914a7936745fd1b71506067c47">offset_type</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa451d1ab92d61da67ac7e7d3c198eeca">OnDiskIterableChainedHashTable</a> (offset_type NumBuckets, offset_type NumEntries, const unsigned char *Buckets, const unsigned char *Payload, const unsigned char *Base, const Info &amp;InfoObj=Info())</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ondiskiterablechainedhashtable/key-iterator">key_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a881bbe4a8f08a0098ae6544aa68dac19">key_begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ondiskiterablechainedhashtable/key-iterator">key_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a401f135c22a9c3f0916440d1a69a2827">key_end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a03f0b20e8cec041b5b401fda08b70f31">keys</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ondiskiterablechainedhashtable/key-iterator">key_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ondiskiterablechainedhashtable/data-iterator">data_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89df6fd8eb3d4a955a240b2b3bb97adb">data_begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ondiskiterablechainedhashtable/data-iterator">data_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0539da205dded4e5ea936d2911b62801">data_end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c030d4ebdc671520e7cb8ae3f0da2b0">data</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ondiskiterablechainedhashtable/data-iterator">data_iterator</a> &gt;</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5415b8c7b1637e3f8d1c39925d47a3ba">Payload</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Info&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ondiskiterablechainedhashtable">OnDiskIterableChainedHashTable</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a08f0b83b48f8790ea85409e56975bb17">Create</a> (const unsigned char *Buckets, const unsigned char *const Payload, const unsigned char *const Base, const Info &amp;InfoObj=Info())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the hash table. <a href="#a08f0b83b48f8790ea85409e56975bb17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Provides lookup and iteration over an on disk hash table.</p>


<p>This needs an <span class="doxyComputerOutput">Info</span> that handles reading values from the hash table's payload and computes the hash for a given key. This should provide the following interface:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">ExampleLookupInfo {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> ExampleData <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ad674bc524f54fe7fb728ded6ae31d66d">data_type</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> ExampleInternalKey internal_key_type; </span><span class="doxyHighlightComment">// The stored key type.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> ExampleKey external_key_type; </span><span class="doxyHighlightComment">// The type to pass to find().</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> uint32_t hash_value_type; </span><span class="doxyHighlightComment">// The type the hash function returns.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> uint32_t <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#a098d428243cfee4c355f295ef47cf549">offset_type</a>; </span><span class="doxyHighlightComment">// The type for offsets into the table.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// Compare two keys for equality.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> EqualKey(internal_key_type &amp;Key1, internal_key_type &amp;Key2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// Calculate the hash for the given key.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> hash_value_type <a href="/web-llvm/docs/api/namespaces/llvm/indexedinstrprof/#a26647986f25d6168afc4204fd79873df">ComputeHash</a>(internal_key_type &amp;IKey);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// Translate from the semantic type of a key in the hash table to the</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// type that is actually stored and used for hashing and comparisons.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// The internal and external types are often the same, in which case this</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// can simply return the passed in value.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> internal_key_type &amp;GetInternalKey(external_key_type &amp;EKey);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// Read the key and data length from Buffer, leaving it pointing at the</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// following byte.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::pair&lt;offset_type, offset_type&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ReadKeyDataLength(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *&amp;Buffer);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// Read the key from Buffer, given the KeyLen as reported from</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// ReadKeyDataLength.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> internal_key_type &amp;ReadKey(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *Buffer,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                                   <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#a098d428243cfee4c355f295ef47cf549">offset_type</a> KeyLen);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// Read the data for Key from Buffer, given the DataLen as reported from</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// ReadKeyDataLength.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#ad674bc524f54fe7fb728ded6ae31d66d">data_type</a> ReadData(StringRef Key, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *Buffer,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#a098d428243cfee4c355f295ef47cf549">offset_type</a> DataLen);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### base\_type {#ae159f6e71f97b64f924e906a7990ddc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef OnDiskChainedHashTable&lt;Info&gt; llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::base_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>

</div>
</div>

### data\_type {#a6be647356c28c77e6301d64afc41ab02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef base_type::data_type llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::data_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>

</div>
</div>

### external\_key\_type {#a7ae73e1c258dab7ffb74903aa69d8899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef base_type::external_key_type llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::external_key_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>

</div>
</div>

### hash\_value\_type {#a870639c44275f12ae0557ac7bc1d2eed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef base_type::hash_value_type llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::hash_value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>

</div>
</div>

### internal\_key\_type {#a54929240b76c7b607c4104ac5b476461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef base_type::internal_key_type llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::internal_key_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>

</div>
</div>

### offset\_type {#ab22fef914a7936745fd1b71506067c47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef base_type::offset_type llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::offset_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OnDiskIterableChainedHashTable() {#aa451d1ab92d61da67ac7e7d3c198eeca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::OnDiskIterableChainedHashTable (<a href="#ab22fef914a7936745fd1b71506067c47">offset_type</a> NumBuckets, <a href="#ab22fef914a7936745fd1b71506067c47">offset_type</a> NumEntries, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Buckets, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Payload, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Base, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> &amp; InfoObj=<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>())</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>


<p>Referenced by <a href="#a08f0b83b48f8790ea85409e56975bb17">llvm::OnDiskIterableChainedHashTable&lt; InstrProfLookupTrait &gt;::Create</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### data() {#a7c030d4ebdc671520e7cb8ae3f0da2b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; data_iterator &gt; llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::data ()</td>
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



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>

</div>
</div>

### data\_begin() {#a89df6fd8eb3d4a955a240b2b3bb97adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">data_iterator llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::data_begin ()</td>
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



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>


<p>Referenced by <a href="#a7c030d4ebdc671520e7cb8ae3f0da2b0">llvm::OnDiskIterableChainedHashTable&lt; InstrProfLookupTrait &gt;::data</a>.</p>

</div>
</div>

### data\_end() {#a0539da205dded4e5ea936d2911b62801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">data_iterator llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::data_end ()</td>
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



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>


<p>Referenced by <a href="#a7c030d4ebdc671520e7cb8ae3f0da2b0">llvm::OnDiskIterableChainedHashTable&lt; InstrProfLookupTrait &gt;::data</a>.</p>

</div>
</div>

### key\_begin() {#a881bbe4a8f08a0098ae6544aa68dac19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">key_iterator llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::key_begin ()</td>
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



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>


<p>Referenced by <a href="#a03f0b20e8cec041b5b401fda08b70f31">llvm::OnDiskIterableChainedHashTable&lt; InstrProfLookupTrait &gt;::keys</a>.</p>

</div>
</div>

### key\_end() {#a401f135c22a9c3f0916440d1a69a2827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">key_iterator llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::key_end ()</td>
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



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>


<p>Referenced by <a href="#a03f0b20e8cec041b5b401fda08b70f31">llvm::OnDiskIterableChainedHashTable&lt; InstrProfLookupTrait &gt;::keys</a>.</p>

</div>
</div>

### keys() {#a03f0b20e8cec041b5b401fda08b70f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; key_iterator &gt; llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::keys ()</td>
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



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Payload {#a5415b8c7b1637e3f8d1c39925d47a3ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char* llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::Payload</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#a08f0b83b48f8790ea85409e56975bb17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Info&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OnDiskIterableChainedHashTable * llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::Create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Buckets, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Payload, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Base, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> &amp; InfoObj=<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>())</td>
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

<p>Create the hash table.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Buckets</td>
<td class="doxyParamItemDescription"><p>is the beginning of the hash table itself, which follows the payload of entire structure. This is the value returned by OnDiskHashTableGenerator::Emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Payload</td>
<td class="doxyParamItemDescription"><p>is the beginning of the data contained in the table. This is Base plus any padding or header data that was stored, ie, the offset that the stream was at when calling Emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Base</td>
<td class="doxyParamItemDescription"><p>is the point from which all offsets into the structure are based. This is offset 0 in the stream that was used when Emitting the table.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/ondiskhashtable-h">OnDiskHashTable.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
