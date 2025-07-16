---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instrprofreaderitaniumremapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InstrProfReaderItaniumRemapper` Class Template Reference

<p>A remapper that applies remappings based on a symbol remapping file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename HashTableImpl&gt;
class llvm::InstrProfReaderItaniumRemapper&lt;HashTableImpl&gt; { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofreaderremapper">InstrProfReaderRemapper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Name matcher supporting fuzzy matching of symbol names to names in profiles. <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderremapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HashTableImpl&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a3aed1473d681f1ded0d6e13ef15347fa">InstrProfReaderItaniumRemapper</a> (std::unique_ptr&lt; MemoryBuffer &gt; RemapBuffer, InstrProfReaderIndex&lt; HashTableImpl &gt; &amp;Underlying)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HashTableImpl&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b37c058778bd80dba88bef8fdad0802">populateRemappings</a> () override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HashTableImpl&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada5c91ffe6ce1366ef81b5cfea3c59fc">getRecords</a> (StringRef FuncName, ArrayRef&lt; NamedInstrProfRecord &gt; &amp;Data) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HashTableImpl&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5d41439e50ccae2f88703b61820bc7fe">RemapBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The memory buffer containing the remapping configuration. <a href="#a5d41439e50ccae2f88703b61820bc7fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HashTableImpl&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/symbolremappingreader">SymbolRemappingReader</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a133e722713d1ceaa781d8aaf612ba1a2">Remappings</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The mangling remapper. <a href="#a133e722713d1ceaa781d8aaf612ba1a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HashTableImpl&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/symbolremappingreader/#a927d799644c7df94d198980a02abcc14">SymbolRemappingReader::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5474846a37bd7ea44c6987e4a934428d">MappedNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping from mangled name keys to the name used for the key in the profile data. <a href="#a5474846a37bd7ea44c6987e4a934428d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HashTableImpl&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex">InstrProfReaderIndex</a>&lt; HashTableImpl &gt; &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac166c464a4e0f36d16a3641feea26ae1">Underlying</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The real profile data reader. <a href="#ac166c464a4e0f36d16a3641feea26ae1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HashTableImpl&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2284c35b89fc03798620ccd10c1a81f9">extractName</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the original function name from a PGO function name. <a href="#a2284c35b89fc03798620ccd10c1a81f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HashTableImpl&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9cbc0396671b685858c523ed763e724">reconstituteName</a> (StringRef OrigName, StringRef ExtractedName, StringRef Replacement, SmallVectorImpl&lt; char &gt; &amp;Out)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a mangled name extracted from a PGO function name, and a new form for that mangled name, reconstitute the name. <a href="#ab9cbc0396671b685858c523ed763e724">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A remapper that applies remappings based on a symbol remapping file.</p>

<p>Definition at line 1067 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrProfReaderItaniumRemapper() {#a3aed1473d681f1ded0d6e13ef15347fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HashTableImpl&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::InstrProfReaderItaniumRemapper (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; RemapBuffer, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex">InstrProfReaderIndex</a>&lt; HashTableImpl &gt; &amp; Underlying)</td>
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



<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRecords() {#ada5c91ffe6ce1366ef81b5cfea3c59fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HashTableImpl&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::getRecords (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord">NamedInstrProfRecord</a> &gt; &amp; Data)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1118 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#a2284c35b89fc03798620ccd10c1a81f9">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::extractName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3285d0c2736154c3ea72dbecaa446eec">llvm::handleErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="#ab9cbc0396671b685858c523ed763e724">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::reconstituteName</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086ab87eee819cec0e1d8b2dfa938d14a77a">llvm::unknown_function</a>.</p>

</div>
</div>

### populateRemappings() {#a9b37c058778bd80dba88bef8fdad0802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HashTableImpl&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::populateRemappings ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1103 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>References <a href="#a2284c35b89fc03798620ccd10c1a81f9">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::extractName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MappedNames {#a5474846a37bd7ea44c6987e4a934428d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HashTableImpl&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;SymbolRemappingReader::Key, StringRef&gt; llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::MappedNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping from mangled name keys to the name used for the key in the profile data.</p>


<p>FIXME: Can we store a location within the on-disk hash table instead of redoing lookup?</p>


<p>Definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>

</div>
</div>

### RemapBuffer {#a5d41439e50ccae2f88703b61820bc7fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HashTableImpl&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::RemapBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The memory buffer containing the remapping configuration.</p>


<p>Remappings holds pointers into this buffer.</p>


<p>Definition at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>

</div>
</div>

### Remappings {#a133e722713d1ceaa781d8aaf612ba1a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HashTableImpl&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolRemappingReader llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::Remappings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The mangling remapper.</p>

<p>Definition at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>

</div>
</div>

### Underlying {#ac166c464a4e0f36d16a3641feea26ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HashTableImpl&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfReaderIndex&lt;HashTableImpl&gt;&amp; llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::Underlying</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The real profile data reader.</p>

<p>Definition at line 1165 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### extractName() {#a2284c35b89fc03798620ccd10c1a81f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HashTableImpl&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::extractName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Extract the original function name from a PGO function name.</p>

<p>Definition at line 1077 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abd3f34fde967eea4eab5a02d7920ef9a">llvm::GlobalIdentifierDelimiter</a>.</p>


<p>Referenced by <a href="#ada5c91ffe6ce1366ef81b5cfea3c59fc">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::getRecords</a> and <a href="#a9b37c058778bd80dba88bef8fdad0802">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::populateRemappings</a>.</p>

</div>
</div>

### reconstituteName() {#ab9cbc0396671b685858c523ed763e724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HashTableImpl&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::reconstituteName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OrigName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExtractedName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Replacement, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Out)</td>
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

<p>Given a mangled name extracted from a PGO function name, and a new form for that mangled name, reconstitute the name.</p>

<p>Definition at line 1094 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#ada5c91ffe6ce1366ef81b5cfea3c59fc">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::getRecords</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
