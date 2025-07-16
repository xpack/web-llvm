---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/lazyrandomtypecollection
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LazyRandomTypeCollection` Class Reference

<p>Provides amortized O(1) random access to a CodeView type stream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::codeview::LazyRandomTypeCollection { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">llvm/DebugInfo/CodeView/LazyRandomTypeCollection.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typecollection">TypeCollection</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8f2ae10cbaa8f46059fadbc5bc0c94c">PartialOffsetArray</a> = <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/typeindexoffset">TypeIndexOffset</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afad57506ce439940f94785edf80084da">LazyRandomTypeCollection</a> (uint32_t RecordCountHint)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfec94087683be804d07270a89c7819">LazyRandomTypeCollection</a> (StringRef Data, uint32_t RecordCountHint)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f281d0be821ff871f838262cc1fb263">LazyRandomTypeCollection</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t RecordCountHint)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2247baf15a7691d396b52b2900e75a81">LazyRandomTypeCollection</a> (const CVTypeArray &amp;Types, uint32_t RecordCountHint, PartialOffsetArray PartialOffsets)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a890b46f548669fb59ee820d18f10c3ff">LazyRandomTypeCollection</a> (const CVTypeArray &amp;Types, uint32_t RecordCountHint)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad762dd32330ae91ab7adc5267918cf43">reset</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t RecordCountHint)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a360afdcd9d4f62ee3d7717620c44486f">reset</a> (StringRef Data, uint32_t RecordCountHint)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88666e96d35b7e7e26892eb8424728b3">reset</a> (BinaryStreamReader &amp;Reader, uint32_t RecordCountHint)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eb7b146a5032a7f0f411dcdcbb8b4b3">getOffsetOfType</a> (TypeIndex Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f93ee6dba63b9b441fa268ec636391f">tryGetType</a> (TypeIndex Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9f32907d1d49ee8974b2f68ce2cdf6">getType</a> (TypeIndex Index) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41c72c1487d92d9beb6b4bfd325b1b1">getTypeName</a> (TypeIndex Index) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc6536c9d578ff7417ce2bae51151465">contains</a> (TypeIndex Index) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83fe8752f1d487f057a12945e9da6e1f">size</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3e173c49db244a90840a7b4b69418fe">capacity</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4a9f6debf4b0a808ea6ce5b9a579591">getFirst</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a253fd026aa57c367c965c81ed6125bd0">getNext</a> (TypeIndex Prev) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9bfc8547ccc3fbe75129dc3e9dea2a6">replaceType</a> (TypeIndex &amp;Index, CVType Data, bool Stabilize) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a252c43a31e94f8de725ab616906875d3">ensureTypeExists</a> (TypeIndex Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d750975b1abb91df3a853e844e41b77">ensureCapacityFor</a> (TypeIndex Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299a70a6d7474be270cfae46bb324541">visitRangeForType</a> (TypeIndex TI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adea2e2fcf30f73942f03f82d51140b29">fullScanForType</a> (TypeIndex TI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3261906609618fc3af73e0e41f36995c">visitRange</a> (TypeIndex Begin, uint32_t BeginOffset, TypeIndex End)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe805f87953ed4f90533d6624bd25e3">Count</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of actual records. <a href="#a0fe805f87953ed4f90533d6624bd25e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1a0c5a6ac6259a0251644d27e00014b">LargestTypeIndex</a> = <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a2d9a88c5d445b0e9d7299c3e4a7ca9a5">TypeIndex::None</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The largest type index which we've visited. <a href="#ab1a0c5a6ac6259a0251644d27e00014b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53cb7a5129417a623ebcac7613c5a4f5">Allocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringsaver">StringSaver</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4acf5edc4fa819ef02df8dcbc547661">NameStorage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26d2c90b0984d5fe775d0e93aa1b38a5">Types</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type array to allow random access visitation of. <a href="#a26d2c90b0984d5fe775d0e93aa1b38a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; CacheEntry &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637d82291a4b263365de4c59f8bd76c3">Records</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">PartialOffsetArray</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf88617283e91b58dfa9060b2a8b26d">PartialOffsets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An array of index offsets for the given type stream, allowing log(N) lookups of a type record by index. <a href="#a8cf88617283e91b58dfa9060b2a8b26d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Provides amortized O(1) random access to a CodeView type stream.</p>


<p>Normally to access a type from a type stream, you must know its byte offset into the type stream, because type records are variable-lengthed. However, this is not the way we prefer to access them. For example, given a symbol record one of the fields may be the <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> of the symbol's type record. Or given a type record such as an array type, there might be a <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> for the element type. Sequential access is perfect when we're just dumping every entry, but it's very poor for real world usage.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> streams in PDBs contain an additional field which is a list of pairs containing indices and their corresponding offsets, roughly every ~8KB of record data. This general idea need not be confined to PDBs though. By supplying such an array, the producer of a type stream can allow the consumer much better access time, because the consumer can find the nearest index in this array, and do a linear scan forward only from there.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/codeview/lazyrandomtypecollection">LazyRandomTypeCollection</a> implements this algorithm, but additionally goes one step further by caching offsets of every record that has been visited at least once. This way, even repeated visits of the same record will never require more than one linear scan. For a type stream of N elements divided into M chunks of roughly equal size, this yields a worst case lookup time of O(N/M) and an amortized time of O(1).</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### PartialOffsetArray {#af8f2ae10cbaa8f46059fadbc5bc0c94c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::codeview::LazyRandomTypeCollection::PartialOffsetArray =  FixedStreamArray&lt;TypeIndexOffset&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LazyRandomTypeCollection() {#afad57506ce439940f94785edf80084da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyRandomTypeCollection::LazyRandomTypeCollection (uint32_t RecordCountHint)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>Reference <a href="#afad57506ce439940f94785edf80084da">LazyRandomTypeCollection</a>.</p>


<p>Referenced by <a href="#a2f281d0be821ff871f838262cc1fb263">LazyRandomTypeCollection</a>, <a href="#a890b46f548669fb59ee820d18f10c3ff">LazyRandomTypeCollection</a>, <a href="#aabfec94087683be804d07270a89c7819">LazyRandomTypeCollection</a> and <a href="#afad57506ce439940f94785edf80084da">LazyRandomTypeCollection</a>.</p>

</div>
</div>

### LazyRandomTypeCollection() {#aabfec94087683be804d07270a89c7819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyRandomTypeCollection::LazyRandomTypeCollection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, uint32_t RecordCountHint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="#afad57506ce439940f94785edf80084da">LazyRandomTypeCollection</a>.</p>

</div>
</div>

### LazyRandomTypeCollection() {#a2f281d0be821ff871f838262cc1fb263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyRandomTypeCollection::LazyRandomTypeCollection (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t RecordCountHint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="#afad57506ce439940f94785edf80084da">LazyRandomTypeCollection</a>.</p>

</div>
</div>

### LazyRandomTypeCollection() {#a2247baf15a7691d396b52b2900e75a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyRandomTypeCollection::LazyRandomTypeCollection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a> &amp; Types, uint32_t RecordCountHint, <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">PartialOffsetArray</a> PartialOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>

</div>
</div>

### LazyRandomTypeCollection() {#a890b46f548669fb59ee820d18f10c3ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyRandomTypeCollection::LazyRandomTypeCollection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a> &amp; Types, uint32_t RecordCountHint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>Reference <a href="#afad57506ce439940f94785edf80084da">LazyRandomTypeCollection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### capacity() {#aa3e173c49db244a90840a7b4b69418fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LazyRandomTypeCollection::capacity ()</td>
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



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>

</div>
</div>

### contains() {#acc6536c9d578ff7417ce2bae51151465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LazyRandomTypeCollection::contains (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Index)</td>
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



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>Referenced by <a href="#a8eb7b146a5032a7f0f411dcdcbb8b4b3">getOffsetOfType</a>, <a href="#a4c9f32907d1d49ee8974b2f68ce2cdf6">getType</a> and <a href="#a2f93ee6dba63b9b441fa268ec636391f">tryGetType</a>.</p>

</div>
</div>

### getFirst() {#ad4a9f6debf4b0a808ea6ce5b9a579591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; TypeIndex &gt; LazyRandomTypeCollection::getFirst ()</td>
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



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a07d13e00998a0b341376f2fbd3a0ed54">llvm::codeview::TypeIndex::fromArrayIndex</a>.</p>

</div>
</div>

### getNext() {#a253fd026aa57c367c965c81ed6125bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; TypeIndex &gt; LazyRandomTypeCollection::getNext (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Prev)</td>
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



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>.</p>

</div>
</div>

### getOffsetOfType() {#a8eb7b146a5032a7f0f411dcdcbb8b4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LazyRandomTypeCollection::getOffsetOfType (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acc6536c9d578ff7417ce2bae51151465">contains</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>.</p>

</div>
</div>

### getType() {#a4c9f32907d1d49ee8974b2f68ce2cdf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVType LazyRandomTypeCollection::getType (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Index)</td>
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



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acc6536c9d578ff7417ce2bae51151465">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeinlinesitesymbol/#aa1db1fcd4aca7e9b22abd894f4716696">llvm::pdb::NativeInlineSiteSymbol::getName</a>.</p>

</div>
</div>

### getTypeName() {#ab41c72c1487d92d9beb6b4bfd325b1b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef LazyRandomTypeCollection::getTypeName (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Index)</td>
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



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4c1be5e840f541db6de41d95d4022561">llvm::codeview::computeTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a8b1dd732eb26d531ff0a7efc29fda083">llvm::codeview::TypeIndex::simpleTypeName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeinlinesitesymbol/#aa1db1fcd4aca7e9b22abd894f4716696">llvm::pdb::NativeInlineSiteSymbol::getName</a>.</p>

</div>
</div>

### replaceType() {#aa9bfc8547ccc3fbe75129dc3e9dea2a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LazyRandomTypeCollection::replaceType (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &amp; Index, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> Data, bool Stabilize)</td>
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



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### reset() {#ad762dd32330ae91ab7adc5267918cf43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyRandomTypeCollection::reset (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t RecordCountHint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="#ad762dd32330ae91ab7adc5267918cf43">reset</a>.</p>


<p>Referenced by <a href="#ad762dd32330ae91ab7adc5267918cf43">reset</a> and <a href="#a360afdcd9d4f62ee3d7717620c44486f">reset</a>.</p>

</div>
</div>

### reset() {#a360afdcd9d4f62ee3d7717620c44486f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyRandomTypeCollection::reset (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, uint32_t RecordCountHint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="#ad762dd32330ae91ab7adc5267918cf43">reset</a>.</p>

</div>
</div>

### reset() {#a88666e96d35b7e7e26892eb8424728b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyRandomTypeCollection::reset (<a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; Reader, uint32_t RecordCountHint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a81b49f753bf7db44da6cf4b0fc59b76e">llvm::BinaryStreamReader::bytesRemaining</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab88a8b3835c1028f8fd6c2b23f396d30">llvm::BinaryStreamReader::readArray</a>.</p>

</div>
</div>

### size() {#a83fe8752f1d487f057a12945e9da6e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LazyRandomTypeCollection::size ()</td>
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



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>

</div>
</div>

### tryGetType() {#a2f93ee6dba63b9b441fa268ec636391f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CVType &gt; LazyRandomTypeCollection::tryGetType (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#acc6536c9d578ff7417ce2bae51151465">contains</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### ensureCapacityFor() {#a8d750975b1abb91df3a853e844e41b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyRandomTypeCollection::ensureCapacityFor (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>

</div>
</div>

### ensureTypeExists() {#a252c43a31e94f8de725ab616906875d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LazyRandomTypeCollection::ensureTypeExists (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>

</div>
</div>

### fullScanForType() {#adea2e2fcf30f73942f03f82d51140b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LazyRandomTypeCollection::fullScanForType (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>

</div>
</div>

### visitRange() {#a3261906609618fc3af73e0e41f36995c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyRandomTypeCollection::visitRange (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Begin, uint32_t BeginOffset, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>

</div>
</div>

### visitRangeForType() {#a299a70a6d7474be270cfae46bb324541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LazyRandomTypeCollection::visitRangeForType (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#a53cb7a5129417a623ebcac7613c5a4f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::codeview::LazyRandomTypeCollection::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>.</p>

</div>
</div>

### Count {#a0fe805f87953ed4f90533d6624bd25e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::LazyRandomTypeCollection::Count = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of actual records.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>.</p>

</div>
</div>

### LargestTypeIndex {#ab1a0c5a6ac6259a0251644d27e00014b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex llvm::codeview::LazyRandomTypeCollection::LargestTypeIndex = <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a2d9a88c5d445b0e9d7299c3e4a7ca9a5">TypeIndex::None</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The largest type index which we've visited.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>.</p>

</div>
</div>

### NameStorage {#af4acf5edc4fa819ef02df8dcbc547661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSaver llvm::codeview::LazyRandomTypeCollection::NameStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>.</p>

</div>
</div>

### PartialOffsets {#a8cf88617283e91b58dfa9060b2a8b26d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PartialOffsetArray llvm::codeview::LazyRandomTypeCollection::PartialOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An array of index offsets for the given type stream, allowing log(N) lookups of a type record by index.</p>


<p>Similar to KnownOffsets but only contains offsets for some type indices, some of which may not have ever been visited.</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>.</p>

</div>
</div>

### Records {#a637d82291a4b263365de4c59f8bd76c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CacheEntry&gt; llvm::codeview::LazyRandomTypeCollection::Records</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>.</p>

</div>
</div>

### Types {#a26d2c90b0984d5fe775d0e93aa1b38a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVTypeArray llvm::codeview::LazyRandomTypeCollection::Types</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type array to allow random access visitation of.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">LazyRandomTypeCollection.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/lazyrandomtypecollection-cpp">LazyRandomTypeCollection.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
