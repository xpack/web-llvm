---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/infostream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InfoStream` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::InfoStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">llvm/DebugInfo/PDB/Native/InfoStream.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dc0a5d02398060098dc9caa59f04672">InfoStreamBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a8d2b43c9981cf2dfc6b0cb58de119">InfoStream</a> (std::unique_ptr&lt; BinaryStream &gt; Stream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8061dd23eb1daa95b6fca9bf53dad3a5">reload</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a979d9b45c95be9e83a85b9b45348f64a">getStreamSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/pdb/infostreamheader">InfoStreamHeader</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f3640f3b4248c6751f14bdd08c2f00">getHeader</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5c4e2e4cc5de604553e9fa9afe8d5ab">containsIdStream</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ad17ec0f543b59c53c2661bea8c3b927e">PdbRaw_ImplVer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6cd1bf38c9858b9d194bd1d437ef1c">getVersion</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ab39347be7115e7a6b32bd8cb3b131">getSignature</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1666f7d3579e63b7f61a24ed890dff9">getAge</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeview/guid">codeview::GUID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215c9258f8499d85fb4655287822194f">getGuid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc5f56fdf2dcd80a15e2eb1a5efc3422">getNamedStreamMapByteSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a731e4835a2b752a938539925fcb0e1b9">PdbRaw_Features</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf59022d793e257b64d744cf63645762">getFeatures</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a86e0553e34d25c1eba47da3234b144f7">PdbRaw_FeatureSig</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c5cab674be61641fabfbdebcd046050">getFeatureSignatures</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/namedstreammap">NamedStreamMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aebec569be9f2de75a8880902bb8179">getNamedStreams</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe665fc28c70d1e4dbc57a2dca665fc5">getNamedStreamsBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b3736e1c60ef1ec526cc0c3ebe907f3">getNamedStreamIndex</a> (llvm::StringRef Name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7b9b28c16feb0ff844e9bd119c8ff6">named_streams</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a163cd6bcbd6888264dfa814d1d2e4ab1">Stream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/pdb/infostreamheader">InfoStreamHeader</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb57a759d88d48690243c729e157b2d">Header</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ea9aea3f2936fb18cdf4d2001b975d">SubNamedStreams</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a86e0553e34d25c1eba47da3234b144f7">PdbRaw_FeatureSig</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf030cdcde29cb1240a839b11b5ad12">FeatureSignatures</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a731e4835a2b752a938539925fcb0e1b9">PdbRaw_Features</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0bb1026db2c039280a600376dfd6b91">Features</a> = <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a731e4835a2b752a938539925fcb0e1b9a568a23d06a25518a6f26b7ba45016cc5">PdbFeatureNone</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab44871a4235bf715dd440b374b74887d">NamedStreamMapByteSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/namedstreammap">NamedStreamMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5182eef5ae9828654bd738f9f45ebe3a">NamedStreams</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>.</p>


<div class="doxySectionDef">

## Friends

### InfoStreamBuilder {#a3dc0a5d02398060098dc9caa59f04672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/pdb/infostreambuilder">InfoStreamBuilder</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>.</p>


<p>Reference <a href="#a3dc0a5d02398060098dc9caa59f04672">InfoStreamBuilder</a>.</p>


<p>Referenced by <a href="#a3dc0a5d02398060098dc9caa59f04672">InfoStreamBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InfoStream() {#aa7a8d2b43c9981cf2dfc6b0cb58de119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InfoStream::InfoStream (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> &gt; Stream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### containsIdStream() {#ac5c4e2e4cc5de604553e9fa9afe8d5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InfoStream::containsIdStream ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a731e4835a2b752a938539925fcb0e1b9afbfc37c08fe887d54debc46ca8da1f48">llvm::pdb::PdbFeatureContainsIdStream</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#a8c60bf2690e6b9c33e5b3c458dec03f5">llvm::pdb::PDBFile::hasPDBIpiStream</a>.</p>

</div>
</div>

### getAge() {#ad1666f7d3579e63b7f61a24ed890dff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t InfoStream::getAge ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>

</div>
</div>

### getFeatures() {#aaf59022d793e257b64d744cf63645762}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PdbRaw_Features InfoStream::getFeatures ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>

</div>
</div>

### getFeatureSignatures() {#a7c5cab674be61641fabfbdebcd046050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; PdbRaw_FeatureSig &gt; InfoStream::getFeatureSignatures ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>

</div>
</div>

### getGuid() {#a215c9258f8499d85fb4655287822194f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GUID InfoStream::getGuid ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/codeview/guid/#a3f8c8ef2f399797cb0193401350c1409">llvm::codeview::GUID::Guid</a>.</p>

</div>
</div>

### getHeader() {#aa5f3640f3b4248c6751f14bdd08c2f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InfoStreamHeader * llvm::pdb::InfoStream::getHeader ()</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>.</p>

</div>
</div>

### getNamedStreamIndex() {#a3b3736e1c60ef1ec526cc0c3ebe907f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; InfoStream::getNamedStreamIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a573bcbbea76b4d72b33de1e392cc14aea881999a844c0bb1ee62b8bd1b29e60bb">llvm::pdb::no_stream</a>.</p>

</div>
</div>

### getNamedStreamMapByteSize() {#adc5f56fdf2dcd80a15e2eb1a5efc3422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t InfoStream::getNamedStreamMapByteSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>

</div>
</div>

### getNamedStreams() {#a9aebec569be9f2de75a8880902bb8179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NamedStreamMap &amp; InfoStream::getNamedStreams ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>

</div>
</div>

### getNamedStreamsBuffer() {#afe665fc28c70d1e4dbc57a2dca665fc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef InfoStream::getNamedStreamsBuffer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>

</div>
</div>

### getSignature() {#af6ab39347be7115e7a6b32bd8cb3b131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t InfoStream::getSignature ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>

</div>
</div>

### getStreamSize() {#a979d9b45c95be9e83a85b9b45348f64a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t InfoStream::getStreamSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>

</div>
</div>

### getVersion() {#add6cd1bf38c9858b9d194bd1d437ef1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PdbRaw_ImplVer InfoStream::getVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>

</div>
</div>

### named\_streams() {#ada7b9b28c16feb0ff844e9bd119c8ff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt; uint32_t &gt; InfoStream::named_streams ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>

</div>
</div>

### reload() {#a8061dd23eb1daa95b6fca9bf53dad3a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InfoStream::reload ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a573bcbbea76b4d72b33de1e392cc14aea8c4fdeb9f0256322a364cd1347a6ffd6">llvm::pdb::corrupt_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a85689faff97c850c60750cc7c365dba2">llvm::BinaryStreamReader::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aa132a8414842bf6ee8325fb27fc531f1">llvm::BinaryStreamReader::getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a86e0553e34d25c1eba47da3234b144f7ac04233006ecdd96147cf1c91ef59a36a">llvm::pdb::MinimalDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a86e0553e34d25c1eba47da3234b144f7ae4236c942ccac2d6cbb6fdb330d5a67d">llvm::pdb::NoTypeMerge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a731e4835a2b752a938539925fcb0e1b9afbfc37c08fe887d54debc46ca8da1f48">llvm::pdb::PdbFeatureContainsIdStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a731e4835a2b752a938539925fcb0e1b9a5bbdcc60da267e84d84622f76b4f201d">llvm::pdb::PdbFeatureMinimalDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a731e4835a2b752a938539925fcb0e1b9a90c22b2f525ea871e1e7e2c081ff6609">llvm::pdb::PdbFeatureNoTypeMerging</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ad17ec0f543b59c53c2661bea8c3b927eafcbe56d20b3e5fd6ca2844aba0ef00bb">llvm::pdb::PdbImplVC110</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ad17ec0f543b59c53c2661bea8c3b927eaa177009c6d59129a5c452042096ccf25">llvm::pdb::PdbImplVC140</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ad17ec0f543b59c53c2661bea8c3b927ea0100542a7c938adb43d4b979331bbcb5">llvm::pdb::PdbImplVC70</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ad17ec0f543b59c53c2661bea8c3b927eae331f6be7b6e4078f194ae15dac03f51">llvm::pdb::PdbImplVC80</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a6a4349bd091677944d67764f80b6fbe0">llvm::BinaryStreamReader::readEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a07e25e055f92f545f94821c4a3cbded8">llvm::BinaryStreamReader::readObject</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a520983e8f7f744a446b4b6501d6ccb03">llvm::BinaryStreamReader::readSubstream</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab56b001a0bd245c9e73972be0ac5d593">llvm::BinaryStreamReader::setOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a86e0553e34d25c1eba47da3234b144f7a8a67e6b6705f4a011838a8242242e35f">llvm::pdb::VC110</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a86e0553e34d25c1eba47da3234b144f7a090d36009ce4ca0698bae2c1abba7be9">llvm::pdb::VC140</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Features {#ad0bb1026db2c039280a600376dfd6b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PdbRaw_Features llvm::pdb::InfoStream::Features = <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a731e4835a2b752a938539925fcb0e1b9a568a23d06a25518a6f26b7ba45016cc5">PdbFeatureNone</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>.</p>

</div>
</div>

### FeatureSignatures {#abcf030cdcde29cb1240a839b11b5ad12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;PdbRaw_FeatureSig&gt; llvm::pdb::InfoStream::FeatureSignatures</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>.</p>

</div>
</div>

### Header {#a9cb57a759d88d48690243c729e157b2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InfoStreamHeader* llvm::pdb::InfoStream::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>.</p>

</div>
</div>

### NamedStreamMapByteSize {#ab44871a4235bf715dd440b374b74887d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::pdb::InfoStream::NamedStreamMapByteSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>.</p>

</div>
</div>

### NamedStreams {#a5182eef5ae9828654bd738f9f45ebe3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedStreamMap llvm::pdb::InfoStream::NamedStreams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>.</p>

</div>
</div>

### Stream {#a163cd6bcbd6888264dfa814d1d2e4ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BinaryStream&gt; llvm::pdb::InfoStream::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>.</p>

</div>
</div>

### SubNamedStreams {#a43ea9aea3f2936fb18cdf4d2001b975d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef llvm::pdb::InfoStream::SubNamedStreams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/infostream-h">InfoStream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/infostream-cpp">InfoStream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
