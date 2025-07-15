---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcopy/macho/machowriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachOWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::objcopy::macho::MachOWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">ObjCopy/MachO/MachOWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab868ef72555762f5c79f0829c920fda5">MachOWriter</a> (Object &amp;O, bool Is64Bit, bool IsLittleEndian, StringRef OutputFileName, uint64_t PageSize, raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace4d95a09224c0956cada6a3a7319e3a">totalSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6075f02bb8591bb5bf64134c7597631d">finalize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a664a6fc223b56ef4fec7642360062ae0">write</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b519594dc6b50c758aadfc8bd87cb8d">headerSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aef73b1ecf0f899555ff2bd58d1fa23">loadCommandsSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a224417e2b9ba17fa0cb2624c63464a0b">symTableSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bfa02c8e9ee9f15a8d1bd7cacb744ed">strTableSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb18275bd010f753c93b09c4af597f1d">writeHeader</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f87c8b55eea19f3ba26f6fa577ffe5d">writeLoadCommands</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename StructType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afbb9b65865bfabae5c5f8351e284a21a">writeSectionInLoadCommand</a> (const Section &amp;Sec, uint8_t *&amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f330d937e9b0b52b9040efabc0fefa7">writeSections</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ada01af302c51e656cefd85962ba52">writeSymbolTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8c97aa0c268927a1340fe96809e693">writeStringTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a373c0e095b274ffe4fdb64ec26054d54">writeRebaseInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fdd6ea556b1bdcadf8589adf79d51d6">writeBindInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a394f95446941e8066ee1aad30ae3f2cc">writeWeakBindInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb924df81099633161834ee974a09e89">writeLazyBindInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd73024a0bd5970c9f43f3f6ec54cb8">writeExportInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a648ef439b5b3f09f7569cebcbb525884">writeIndirectSymbolTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2bdbb9557af658282ff73e9b70ff9a">writeLinkData</a> (std::optional&lt; size_t &gt; LCIndex, const LinkData &amp;LD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c13034cbb6923e65930bdee93218cd1">writeCodeSignatureData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fbdc14f8f3f93b65806f2f0e6096f96">writeDataInCodeData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab19ead95cb1f304acf69558297e3226d">writeLinkerOptimizationHint</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8104e13b290e3ef78280cfcf80189fa">writeFunctionStartsData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0049f3a9c8f2f3914e77dc375b3b38e">writeDylibCodeSignDRsData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6549183a25f9b0c8a782579105255787">writeChainedFixupsData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9acbfb6fd0109e9800d57e2ab6e3f7bd">writeExportsTrieData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87436c89822e2239de2c08662450b0f5">writeTail</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e01e593214215ebd7dba839dc3fa54">O</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac18aa27f6c8c45136d7271ac0ed523">Is64Bit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a504c84d1731a7624e51dd106721b3">IsLittleEndian</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f6d28a61f57db4023668f5be69396b">PageSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6dc8b6861c954088429ec1e08a94bb">Buf</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3598d228644fa6191d4d0c1c24f1439">Out</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/macho/macholayoutbuilder">MachOLayoutBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35c7d8bfe55961a80106b5790a30c1ea">LayoutBuilder</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachOWriter() {#ab868ef72555762f5c79f0829c920fda5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::macho::MachOWriter::MachOWriter (<a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; O, bool Is64Bit, bool IsLittleEndian, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OutputFileName, uint64_t PageSize, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalize() {#a6075f02bb8591bb5bf64134c7597631d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MachOWriter::finalize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/macho/#ad23f6403620ffb61f8c0e1f006f6ea66">llvm::objcopy::macho::executeObjcopyOnBinary</a>.</p>

</div>
</div>

### totalSize() {#ace4d95a09224c0956cada6a3a7319e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t MachOWriter::totalSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ab88cd765d6656769b73824ee3633f9c6">llvm::MachO::dyld_info_command::bind_off</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6ffe60a024bfb2a697cf4717e3a1ca5d">llvm::MachO::dyld_info_command::bind_size</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a7d4425eb797faa587c5634883588c45d">llvm::MachO::linkedit_data_command::datasize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6abfd90c1ff5f9fab154b1b7c2ca9fdf">llvm::MachO::dyld_info_command::export_off</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6cc1cf394f79b0012db18526d363f887">llvm::MachO::dyld_info_command::export_size</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a1e9b3d4be015aa2be10de0a437ad5686">llvm::MachO::dysymtab_command::indirectsymoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a66f14c5767f6c0860bcca3f23d15002c">llvm::MachO::dyld_info_command::lazy_bind_off</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a8bbee159752147265303f294926c72d6">llvm::MachO::dyld_info_command::lazy_bind_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab4e6de707bff0fe8081c4da0711bba07">llvm::max_element</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ac0a251eaae629a1e7f918ff416ff17fd">llvm::MachO::dyld_info_command::rebase_off</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6b8dd4f28d4ff3bd7ea7ba0c3cd8a377">llvm::MachO::dyld_info_command::rebase_size</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#aa9d03f7cb5acb5efb6c8aaa9fa5df989">llvm::objcopy::macho::LoadCommand::Sections</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ad664b3b2032af10912280b74303ee21d">llvm::MachO::symtab_command::stroff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a1459968fe2ad55b364958070dde70c6e">llvm::MachO::symtab_command::strsize</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ae6c74170eea156826ddfb4b61bd5d043">llvm::MachO::symtab_command::symoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ad19b3e306dcbd600f6e735c02c118eb6">llvm::MachO::dyld_info_command::weak_bind_off</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ab64b83ee5772b8d112c8961f209d1ab4">llvm::MachO::dyld_info_command::weak_bind_size</a>.</p>


<p>Referenced by <a href="#a664a6fc223b56ef4fec7642360062ae0">write</a>.</p>

</div>
</div>

### write() {#a664a6fc223b56ef4fec7642360062ae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MachOWriter::write ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a3ba0db4e545291ac0dbf07804f13d351">llvm::WritableMemoryBuffer::getNewMemBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baafdb5594dc3e484fc1bfd7c564d550c1">llvm::not_enough_memory</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#ace4d95a09224c0956cada6a3a7319e3a">totalSize</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/macho/#ad23f6403620ffb61f8c0e1f006f6ea66">llvm::objcopy::macho::executeObjcopyOnBinary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### headerSize() {#a4b519594dc6b50c758aadfc8bd87cb8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t MachOWriter::headerSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### loadCommandsSize() {#a6aef73b1ecf0f899555ff2bd58d1fa23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t MachOWriter::loadCommandsSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### strTableSize() {#a5bfa02c8e9ee9f15a8d1bd7cacb744ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::objcopy::macho::MachOWriter::strTableSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>.</p>

</div>
</div>

### symTableSize() {#a224417e2b9ba17fa0cb2624c63464a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t MachOWriter::symTableSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeBindInfo() {#a7fdd6ea556b1bdcadf8589adf79d51d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeBindInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeChainedFixupsData() {#a6549183a25f9b0c8a782579105255787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeChainedFixupsData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeCodeSignatureData() {#a4c13034cbb6923e65930bdee93218cd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeCodeSignatureData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeDataInCodeData() {#a0fbdc14f8f3f93b65806f2f0e6096f96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeDataInCodeData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeDylibCodeSignDRsData() {#ad0049f3a9c8f2f3914e77dc375b3b38e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeDylibCodeSignDRsData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeExportInfo() {#afcd73024a0bd5970c9f43f3f6ec54cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeExportInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeExportsTrieData() {#a9acbfb6fd0109e9800d57e2ab6e3f7bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeExportsTrieData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeFunctionStartsData() {#ad8104e13b290e3ef78280cfcf80189fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeFunctionStartsData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeHeader() {#adb18275bd010f753c93b09c4af597f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeIndirectSymbolTable() {#a648ef439b5b3f09f7569cebcbb525884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeIndirectSymbolTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeLazyBindInfo() {#adb924df81099633161834ee974a09e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeLazyBindInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeLinkData() {#a5d2bdbb9557af658282ff73e9b70ff9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeLinkData (std::optional&lt; size_t &gt; LCIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/linkdata">LinkData</a> &amp; LD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeLinkerOptimizationHint() {#ab19ead95cb1f304acf69558297e3226d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeLinkerOptimizationHint ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeLoadCommands() {#a1f87c8b55eea19f3ba26f6fa577ffe5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeLoadCommands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeRebaseInfo() {#a373c0e095b274ffe4fdb64ec26054d54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeRebaseInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeSectionInLoadCommand() {#afbb9b65865bfabae5c5f8351e284a21a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename StructType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeSectionInLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section">Section</a> &amp; Sec, uint8_t *&amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeSections() {#a3f330d937e9b0b52b9040efabc0fefa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeStringTable() {#a1b8c97aa0c268927a1340fe96809e693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeStringTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeSymbolTable() {#aa0ada01af302c51e656cefd85962ba52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeSymbolTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeTail() {#a87436c89822e2239de2c08662450b0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeTail ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

### writeWeakBindInfo() {#a394f95446941e8066ee1aad30ae3f2cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOWriter::writeWeakBindInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buf {#abc6dc8b6861c954088429ec1e08a94bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;WritableMemoryBuffer&gt; llvm::objcopy::macho::MachOWriter::Buf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>.</p>

</div>
</div>

### Is64Bit {#a8ac18aa27f6c8c45136d7271ac0ed523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::macho::MachOWriter::Is64Bit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>.</p>

</div>
</div>

### IsLittleEndian {#ab9a504c84d1731a7624e51dd106721b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::macho::MachOWriter::IsLittleEndian</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>.</p>

</div>
</div>

### LayoutBuilder {#a35c7d8bfe55961a80106b5790a30c1ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOLayoutBuilder llvm::objcopy::macho::MachOWriter::LayoutBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>.</p>

</div>
</div>

### O {#ab8e01e593214215ebd7dba839dc3fa54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Object&amp; llvm::objcopy::macho::MachOWriter::O</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>.</p>

</div>
</div>

### Out {#ae3598d228644fa6191d4d0c1c24f1439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::objcopy::macho::MachOWriter::Out</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>.</p>

</div>
</div>

### PageSize {#a88f6d28a61f57db4023668f5be69396b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::objcopy::macho::MachOWriter::PageSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
