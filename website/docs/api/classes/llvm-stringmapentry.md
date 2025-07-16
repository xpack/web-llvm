---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/stringmapentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StringMapEntry` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a> - This is used to represent one value that is inserted into a <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ValueTy&gt;
class llvm::StringMapEntry&lt;ValueTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmapentry-h">llvm/ADT/StringMapEntry.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmapentrystorage">StringMapEntryStorage&lt;ValueTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/stringmapentrystorage">StringMapEntryStorage</a> - Holds the value in a <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>. <a href="/web-llvm/docs/api/classes/llvm/stringmapentrystorage/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21f5a5ab1fe706f89623fe0ce55679af">ValueType</a> = ValueTy</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6201b76e51e8eecfbb57c77fba8367b8">getKey</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af00ecfc79d7fe461d92e306db445a13f">getKeyData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getKeyData - Return the start of the string data that is the key for this value. <a href="#af00ecfc79d7fe461d92e306db445a13f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa90d7ff5110be6315425ec6c29da762b">first</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AllocatorTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acb4c668e424bcb706f1b0e51605b2b43">Destroy</a> (AllocatorTy &amp;allocator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy - Destroy this <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>, releasing memory back to the specified allocator. <a href="#acb4c668e424bcb706f1b0e51605b2b43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AllocatorTy, typename... InitTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09f6c55119f75e7997dab2bbd8d2f065">create</a> (StringRef key, AllocatorTy &amp;allocator, InitTy &amp;&amp;...initVals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a> for the specified key construct the value using <span class="doxyComputerOutput">InitiVals</span>. <a href="#a09f6c55119f75e7997dab2bbd8d2f065">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae642d4e909f7f77f2496fa6331f27837">GetStringMapEntryFromKeyData</a> (const char *keyData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetStringMapEntryFromKeyData - Given key data that is known to be embedded into a <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>, return the <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a> itself. <a href="#ae642d4e909f7f77f2496fa6331f27837">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a> - This is used to represent one value that is inserted into a <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>.</p>


<p>It contains the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> itself and the key: the string length and data.</p>


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmapentry-h">StringMapEntry.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ValueType {#a21f5a5ab1fe706f89623fe0ce55679af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StringMapEntry&lt; ValueTy &gt;::ValueType =  ValueTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmapentry-h">StringMapEntry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Destroy() {#acb4c668e424bcb706f1b0e51605b2b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StringMapEntry&lt; ValueTy &gt;::Destroy (AllocatorTy &amp; allocator)</td>
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

<p>Destroy - Destroy this <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>, releasing memory back to the specified allocator.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmapentry-h">StringMapEntry.h</a>.</p>

</div>
</div>

### first() {#aa90d7ff5110be6315425ec6c29da762b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringMapEntry&lt; ValueTy &gt;::first ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmapentry-h">StringMapEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool/#a9d5dd239d695012f27da4cac70118c8a">llvm::dwarf_linker::parallel::TypePool::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptrbase/#a110e9c1b1b05e2c756e957217488c505">llvm::orc::SymbolStringPtrBase::operator&lt;&lt;</a>.</p>

</div>
</div>

### getKey() {#a6201b76e51e8eecfbb57c77fba8367b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringMapEntry&lt; ValueTy &gt;::getKey ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmapentry-h">StringMapEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ac0f5b717fb77c6c02c668e29b9764c9e">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addDIETypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a027b6b972f10fc3ec4f94616d1b1481c">llvm::StringMap&lt; std::nullopt_t, AllocatorTy &gt;::count</a>, <a href="#aa90d7ff5110be6315425ec6c29da762b">llvm::StringMapEntry&lt; std::nullopt_t &gt;::first</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentryinfo/#a3dde30a8ffa855b4ad9e2f9c8b2031d0">llvm::dwarf_linker::parallel::TypeEntryInfo::getKey</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/stringpoolentryinfo/#aec68c8b63c615e717f7fa0a71dda0dd4">llvm::dwarf_linker::StringPoolEntryInfo::getKey</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5b33634e0aa97435f13845ce7e10411e">llvm::getKnowledgeFromBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#afea367cbdd62e85c20d3ebe044253ce7">llvm::StringMap&lt; std::nullopt_t, AllocatorTy &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringset/#a5ca1272e3b56a501307fcd090709a358">llvm::StringSet&lt; AllocatorTy &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#aca2d3ebfb1896c7f85f76bcb6dea8b81">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::save</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#a37addefa67ac345264fef8f6f477eef8">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::saveObjC</a>.</p>

</div>
</div>

### getKeyData() {#af00ecfc79d7fe461d92e306db445a13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::StringMapEntry&lt; ValueTy &gt;::getKeyData ()</td>
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

<p>getKeyData - Return the start of the string data that is the key for this value.</p>


<p>The string data is always stored immediately after the <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a> object.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmapentry-h">StringMapEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetintrinsicinfo/#ab83719d8328f99cee031acfe4881a456">llvm::TargetIntrinsicInfo::getIntrinsicID</a> and <a href="#a6201b76e51e8eecfbb57c77fba8367b8">llvm::StringMapEntry&lt; std::nullopt_t &gt;::getKey</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a09f6c55119f75e7997dab2bbd8d2f065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AllocatorTy, typename... InitTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMapEntry * llvm::StringMapEntry&lt; ValueTy &gt;::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> key, AllocatorTy &amp; allocator, InitTy &amp;&amp;... initVals)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a> for the specified key construct the value using <span class="doxyComputerOutput">InitiVals</span>.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmapentry-h">StringMapEntry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvstringpool/#ae39a6c4bf47bfd20b1d17e8b352e3a14">llvm::logicalview::LVStringPool::getIndex</a>.</p>

</div>
</div>

### GetStringMapEntryFromKeyData() {#ae642d4e909f7f77f2496fa6331f27837}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMapEntry &amp; llvm::StringMapEntry&lt; ValueTy &gt;::GetStringMapEntryFromKeyData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * keyData)</td>
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

<p>GetStringMapEntryFromKeyData - Given key data that is known to be embedded into a <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>, return the <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a> itself.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmapentry-h">StringMapEntry.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmapentry-h">StringMapEntry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
