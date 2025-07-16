---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/cvrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CVRecord` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord">CVRecord</a> is a fat pointer (base + size pair) to a symbol or type record. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename Kind&gt;
class llvm::codeview::CVRecord&lt;Kind&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">llvm/DebugInfo/CodeView/CVRecord.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1430c1823eb6da8308853b454dd80b61">CVRecord</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a17508e35594878b720955d99d82f723b">CVRecord</a> (ArrayRef&lt; uint8_t &gt; Data)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a83850e3b015408edc6c9b1278aaf642e">CVRecord</a> (const RecordPrefix *P, size_t Size)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5269afff02d4459d074da701a21e8711">valid</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad2287d2f898bae38b5295534990e6856">length</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Kind</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaeef9f2a2d0dc09ec00ec9b38242c706">kind</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa5ac0ccd261c6bd6e07e1b288952fe33">data</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6596ef84bef896715bfde36138770623">str_data</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acb4bfb2259905c9116067e4a2837fd4b">content</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abf24508852ac431412daa99def7d29ae">RecordData</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord">CVRecord</a> is a fat pointer (base + size pair) to a symbol or type record.</p>


<p>Carrying the size separately instead of trusting the size stored in the record prefix provides some extra safety and flexibility.</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CVRecord() {#a1430c1823eb6da8308853b454dd80b61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::CVRecord&lt; Kind &gt;::CVRecord ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a>.</p>

</div>
</div>

### CVRecord() {#a17508e35594878b720955d99d82f723b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::CVRecord&lt; Kind &gt;::CVRecord (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a>.</p>

</div>
</div>

### CVRecord() {#a83850e3b015408edc6c9b1278aaf642e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::CVRecord&lt; Kind &gt;::CVRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codeview/recordprefix">RecordPrefix</a> * P, size_t Size)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### content() {#acb4bfb2259905c9116067e4a2837fd4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; llvm::codeview::CVRecord&lt; Kind &gt;::content ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/typedeserializer/#ad2afe9d87179bb184fd5f477db6e8509">llvm::codeview::TypeDeserializer::deserializeAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a13ac613b895f170feaee6616a75e05fc">llvm::codeview::discoverTypeIndicesInSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad540067d5e143dbc9d0a957b4b28968f">llvm::codeview::getSymbolName</a> and <a href="/web-llvm/docs/api/classes/anonymous-symboldumper-cpp-/cvsymboldumperimpl/#a4236f2c1eae2b4f515a4f75986e61b68">anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::visitSymbolEnd</a>.</p>

</div>
</div>

### data() {#aa5ac0ccd261c6bd6e07e1b288952fe33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; llvm::codeview::CVRecord&lt; Kind &gt;::data ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/binaryitemtraits-f4d38101d84063f5b9778260a2f72c51/#aeb1f51e600c24ddc5dcab63bae1e2ae6">llvm::BinaryItemTraits&lt; codeview::CVType &gt;::bytes</a>, <a href="/web-llvm/docs/api/structs/llvm/binaryitemtraits-4708805e12d072d0e5c200f2bcb1f60b/#a0126f2daefbfe9da40b35ccd17bd72b3">llvm::BinaryItemTraits&lt; llvm::codeview::CVType &gt;::bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp/#a70d89e90b3449d03c7ca937d76fbdda0">getHashForUdt</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp/#af798249882e2b294e8eb95506cfce700">getTagRecordHashForUdt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a69bf231aca848ed614fb954ea4d65ff2">llvm::pdb::hashTypeRecord</a>.</p>

</div>
</div>

### kind() {#aaeef9f2a2d0dc09ec00ec9b38242c706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind llvm::codeview::CVRecord&lt; Kind &gt;::kind ()</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordhelpers-cpp/#aec9b5f4a60552ed88346b2a37636ae4f">createRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedeserializer/#ad2afe9d87179bb184fd5f477db6e8509">llvm::codeview::TypeDeserializer::deserializeAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a13ac613b895f170feaee6616a75e05fc">llvm::codeview::discoverTypeIndicesInSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#aab363a93f3751289108fdc859406dec4">llvm::pdb::TpiStream::findFullDeclForForwardRef</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolcache/#a5ec9985ad0d83fa432f370483228cf7d">llvm::pdb::SymbolCache::findSymbolByTypeIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/unknownsymbolrecord/#a20ab345d5cce9e08d1319607834b711f">llvm::CodeViewYAML::detail::UnknownSymbolRecord::fromCodeViewSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aeeee24e4951098e13042b484886d47bb">llvm::codeview::getModifiedType</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeinlinesitesymbol/#aa1db1fcd4aca7e9b22abd894f4716696">llvm::pdb::NativeInlineSiteSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolcache/#affa16ab83d35cb583b2ae91644aa8c68">llvm::pdb::SymbolCache::getOrCreateGlobalSymbolByOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a63a780627da7c5b7088ebaf5bd7408aa">llvm::logicalview::getRecordName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a7eef7c2356ec9c0368019221027fb432">llvm::codeview::getScopeEndOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a8fde83b67f14703faf4b0f410ecabc80">llvm::codeview::getScopeParentOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac4a2f1866a17117b240fe173fae7699b">llvm::codeview::getSizeInBytesForTypeRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad540067d5e143dbc9d0a957b4b28968f">llvm::codeview::getSymbolName</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/recordname-cpp/#ab1946f7c4c985f713fd6b606fd84bd68">getSymbolNameOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a69bf231aca848ed614fb954ea4d65ff2">llvm::pdb::hashTypeRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aa59cca6142d1e491d779bd3f0b7436dc">llvm::codeview::isAggregate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a1caacde32c41f8b301176da4190c3639">llvm::codeview::isUdtForwardRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ae77cc39ccd9efa05d6afa6936cfc8cd8">llvm::codeview::limitSymbolArrayToScope</a>, <a href="/web-llvm/docs/api/classes/anonymous-nativetypeenum-cpp-/nativeenumenumenumerators/#a8c1a55d489bc1b25ca1a430cb818b2c4">anonymous{NativeTypeEnum.cpp}::NativeEnumEnumEnumerators::NativeEnumEnumEnumerators</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeenumglobals/#a6b7d28f87110427a24e6fdba62bd5496">llvm::pdb::NativeEnumGlobals::NativeEnumGlobals</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeenumtypes/#a403daea184f56bac9e0196314ba22866">llvm::pdb::NativeEnumTypes::NativeEnumTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/simpletypeserializer/#ae10015a36f68325417d06aa9ab5bce62">llvm::codeview::SimpleTypeSerializer::serialize</a>, <a href="#a5269afff02d4459d074da701a21e8711">llvm::codeview::CVRecord&lt; TypeLeafKind &gt;::valid</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ac72c1663cfda32b4cb722e815b1ea005">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ade7088de2025cc1850af4e51e17c9255">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-symboldumper-cpp-/cvsymboldumperimpl/#afdd17a4669d7d1cf98833763cfbb09c4">anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::visitSymbolBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvsymbolvisitor/#a386edc0742a93b59caac3efd31876012">llvm::codeview::CVSymbolVisitor::visitSymbolStreamFiltered</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#a0b455766e2cade6732d4d6680e4512e4">llvm::codeview::TypeRecordMapping::visitTypeBegin</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#acf1507b6abe0cb0d10cf17e976fd908d">llvm::codeview::TypeRecordMapping::visitTypeBegin</a>.</p>

</div>
</div>

### length() {#ad2287d2f898bae38b5295534990e6856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::CVRecord&lt; Kind &gt;::length ()</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac4a2f1866a17117b240fe173fae7699b">llvm::codeview::getSizeInBytesForTypeRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/binaryitemtraits-f4d38101d84063f5b9778260a2f72c51/#a0e6dd3641fdd0270f27a23afaa978e2e">llvm::BinaryItemTraits&lt; codeview::CVType &gt;::length</a>, <a href="/web-llvm/docs/api/structs/llvm/binaryitemtraits-4708805e12d072d0e5c200f2bcb1f60b/#ae0520994447c6ae40ada538b77eedb58">llvm::BinaryItemTraits&lt; llvm::codeview::CVType &gt;::length</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#a0b455766e2cade6732d4d6680e4512e4">llvm::codeview::TypeRecordMapping::visitTypeBegin</a> and <a href="/web-llvm/docs/api/classes/anonymous-symboldumper-cpp-/cvsymboldumperimpl/#abd0a783cd91db1983a177bdfee26a6a9">anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::visitUnknownSymbol</a>.</p>

</div>
</div>

### str\_data() {#a6596ef84bef896715bfde36138770623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::codeview::CVRecord&lt; Kind &gt;::str_data ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a>.</p>

</div>
</div>

### valid() {#a5269afff02d4459d074da701a21e8711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::CVRecord&lt; Kind &gt;::valid ()</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### RecordData {#abf24508852ac431412daa99def7d29ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::codeview::CVRecord&lt; Kind &gt;::RecordData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/binaryitemtraits-7e3dbb0894d46ad0ca22830f22e986bb/#aee6577a048114c7f64cf99d04f8837d2">llvm::BinaryItemTraits&lt; codeview::CVSymbol &gt;::bytes</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/unknownsymbolrecord/#a20ab345d5cce9e08d1319607834b711f">llvm::CodeViewYAML::detail::UnknownSymbolRecord::fromCodeViewSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/pdb/symboldensemapinfo/#a1124289bde357728198a464b10744755">llvm::pdb::SymbolDenseMapInfo::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/binaryitemtraits-7e3dbb0894d46ad0ca22830f22e986bb/#a6c96273f1093282fe3c39cc238411483">llvm::BinaryItemTraits&lt; codeview::CVSymbol &gt;::length</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ae77cc39ccd9efa05d6afa6936cfc8cd8">llvm::codeview::limitSymbolArrayToScope</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvrecord-h">CVRecord.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
