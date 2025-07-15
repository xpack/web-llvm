---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/textinstrprofreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TextInstrProfReader` Class Reference

<p>Reader for the simple text based instrprof format. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TextInstrProfReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">llvm/ProfileData/InstrProfReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofreader">InstrProfReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class and interface for reading profiling data of any known instrprof format. <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a695aae8d351cd41d0b6ae8400dc864b3">TextInstrProfReader</a> (std::unique_ptr&lt; MemoryBuffer &gt; DataBuffer_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a2cfc308d36df18ec1ed72bd99b140">TextInstrProfReader</a> (const TextInstrProfReader &amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/textinstrprofreader">TextInstrProfReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc646b5709aacb1e61f7efaa7cc14102">operator=</a> (const TextInstrProfReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a462b5a012961fd76b1e0dd1426e8c6ff">getVersion</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the profile version. <a href="#a462b5a012961fd76b1e0dd1426e8c6ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11786ab82600e8236280d142243b17a1">isIRLevelProfile</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab67ead159bf57a0700945d0198d3e4d">hasCSIRLevelProfile</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc133101f5e847ad386948fa5bb27a15">instrEntryBBEnabled</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afddb50e18046c0300a21bc3b6e766081">instrLoopEntriesEnabled</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the profile instruments all loop entries. <a href="#afddb50e18046c0300a21bc3b6e766081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba65d02a1ca0d62a0d3d4120ef91161">hasSingleByteCoverage</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the profile has single byte counters representing coverage. <a href="#a6ba65d02a1ca0d62a0d3d4120ef91161">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac03f9090429b07a6dcb0f91e7fe38487">functionEntryOnly</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the profile only instruments function entries. <a href="#ac03f9090429b07a6dcb0f91e7fe38487">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9bbd2893531315f5a033e8fed6d84a6">hasMemoryProfile</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if profile includes a memory profile. <a href="#aa9bbd2893531315f5a033e8fed6d84a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ee6fd0439fd878669a196179430ae5">hasTemporalProfile</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this has a temporal profile. <a href="#ad3ee6fd0439fd878669a196179430ae5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6">InstrProfKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac616e56dc9d68268db19ed1897793004">getProfileKind</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a BitsetEnum describing the attributes of the profile. <a href="#ac616e56dc9d68268db19ed1897793004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef869625c91dde9e5539eb2a417eaef4">readHeader</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the header. <a href="#aef869625c91dde9e5539eb2a417eaef4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d3a3124492d7f44aeebfea0d19e0e37">readNextRecord</a> (NamedInstrProfRecord &amp;Record) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a single record. <a href="#a7d3a3124492d7f44aeebfea0d19e0e37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfeeaac8e03fccb0f88213b3920a304">getSymtab</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the PGO symtab. <a href="#aabfeeaac8e03fccb0f88213b3920a304">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af96e8dee455517fb60665ac236ebb60d">readValueProfileData</a> (InstrProfRecord &amp;Record)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82ac41fe67683b86cf94a838fcafad76">readTemporalProfTraceData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Temporal profile trace data is stored in the header immediately after ":temporal_prof_traces". <a href="#a82ac41fe67683b86cf94a838fcafad76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac33b6c4f85438af3892a8a365fae945e">DataBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The profile data file contents. <a href="#ac33b6c4f85438af3892a8a365fae945e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/line-iterator">line_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad725363a709c06cb91225fe938e0c819">Line</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator over the profile data. <a href="#ad725363a709c06cb91225fe938e0c819">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6">InstrProfKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3e79d553338e4c6aee3690f6239f5c">ProfileKind</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a88183b946cc5f0e8c96b2e66e1c74a7e">InstrProfKind::Unknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The attributes of the current profile. <a href="#abc3e79d553338e4c6aee3690f6239f5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ea33c903b163ee020c34e36d6849c9">hasFormat</a> (const MemoryBuffer &amp;Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given buffer is in text instrprof format. <a href="#a54ea33c903b163ee020c34e36d6849c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Reader for the simple text based instrprof format.</p>


<p>This format is a simple text format that's suitable for test data. Records are separated by one or more blank lines, and record fields are separated by new lines.</p>


<p>Each record consists of a function name, a function hash, a number of counters, and then each counter value, in that order.</p>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TextInstrProfReader() {#a695aae8d351cd41d0b6ae8400dc864b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TextInstrProfReader::TextInstrProfReader (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; DataBuffer_)</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#afc646b5709aacb1e61f7efaa7cc14102">operator=</a> and <a href="#a95a2cfc308d36df18ec1ed72bd99b140">TextInstrProfReader</a>.</p>

</div>
</div>

### TextInstrProfReader() {#a95a2cfc308d36df18ec1ed72bd99b140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TextInstrProfReader::TextInstrProfReader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/textinstrprofreader">TextInstrProfReader</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>Reference <a href="#a695aae8d351cd41d0b6ae8400dc864b3">TextInstrProfReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#afc646b5709aacb1e61f7efaa7cc14102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextInstrProfReader &amp; llvm::TextInstrProfReader::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/textinstrprofreader">TextInstrProfReader</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>Reference <a href="#a695aae8d351cd41d0b6ae8400dc864b3">TextInstrProfReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### functionEntryOnly() {#ac03f9090429b07a6dcb0f91e7fe38487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TextInstrProfReader::functionEntryOnly ()</td>
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

<p>Return true if the profile only instruments function entries.</p>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a0e0f0e75dc57be5c12274ba6e78bc75a">llvm::FunctionEntryOnly</a>.</p>

</div>
</div>

### getProfileKind() {#ac616e56dc9d68268db19ed1897793004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfKind llvm::TextInstrProfReader::getProfileKind ()</td>
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

<p>Returns a BitsetEnum describing the attributes of the profile.</p>


<p>To check individual attributes prefer using the helpers above.</p>


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### getSymtab() {#aabfeeaac8e03fccb0f88213b3920a304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfSymtab &amp; llvm::TextInstrProfReader::getSymtab ()</td>
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

<p>Return the PGO symtab.</p>


<p>There are three different readers: Raw, Text, and Indexed profile readers. The first two types of readers are used only by llvm-profdata tool, while the indexed profile reader is also used by llvm-cov tool and the compiler ( backend or frontend). Since creating PGO symtab can create significant runtime and memory overhead (as it touches data for the whole program), <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> for the indexed profile reader should be created on demand and it is recommended to be only used for dumping purpose with llvm-proftool, not with the compiler.</p>


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#a51d19452b19c498a18cafa947fd744ad">llvm::InstrProfReader::Symtab</a>.</p>

</div>
</div>

### getVersion() {#a462b5a012961fd76b1e0dd1426e8c6ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::TextInstrProfReader::getVersion ()</td>
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

<p>Return the profile version.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### hasCSIRLevelProfile() {#aab67ead159bf57a0700945d0198d3e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TextInstrProfReader::hasCSIRLevelProfile ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a087151dc0bb6ff33db94d0479b6bc2cf">llvm::ContextSensitive</a>.</p>

</div>
</div>

### hasMemoryProfile() {#aa9bbd2893531315f5a033e8fed6d84a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TextInstrProfReader::hasMemoryProfile ()</td>
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

<p>Return true if profile includes a memory profile.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### hasSingleByteCoverage() {#a6ba65d02a1ca0d62a0d3d4120ef91161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TextInstrProfReader::hasSingleByteCoverage ()</td>
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

<p>Return true if the profile has single byte counters representing coverage.</p>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a5505edfdbf5f7c9b5bd53a769be32faf">llvm::SingleByteCoverage</a>.</p>

</div>
</div>

### hasTemporalProfile() {#ad3ee6fd0439fd878669a196179430ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TextInstrProfReader::hasTemporalProfile ()</td>
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

<p>Return true if this has a temporal profile.</p>

<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a3ef3ba43212f6a2779d594e507451d54">llvm::TemporalProfile</a>.</p>

</div>
</div>

### instrEntryBBEnabled() {#abc133101f5e847ad386948fa5bb27a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TextInstrProfReader::instrEntryBBEnabled ()</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a3d8a924372eb01d27427b757ba52d318">llvm::FunctionEntryInstrumentation</a>.</p>

</div>
</div>

### instrLoopEntriesEnabled() {#afddb50e18046c0300a21bc3b6e766081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TextInstrProfReader::instrLoopEntriesEnabled ()</td>
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

<p>Return true if the profile instruments all loop entries.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a2d0e271ef09b456a7c73384c7e787173">llvm::LoopEntriesInstrumentation</a>.</p>

</div>
</div>

### isIRLevelProfile() {#a11786ab82600e8236280d142243b17a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TextInstrProfReader::isIRLevelProfile ()</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a51056965b635025ecb4cdafb28bc1ae2">llvm::IRInstrumentation</a>.</p>

</div>
</div>

### readHeader() {#aef869625c91dde9e5539eb2a417eaef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TextInstrProfReader::readHeader ()</td>
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

<p>Read the header.</p>

<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>, definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086adde571add68cc36593098a17df48bd45">llvm::bad_header</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a087151dc0bb6ff33db94d0479b6bc2cf">llvm::ContextSensitive</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a5b8e304d44bb4e39203ed9bc70168db9">llvm::FrontendInstrumentation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a3d8a924372eb01d27427b757ba52d318">llvm::FunctionEntryInstrumentation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a51056965b635025ecb4cdafb28bc1ae2">llvm::IRInstrumentation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a2d0e271ef09b456a7c73384c7e787173">llvm::LoopEntriesInstrumentation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a5505edfdbf5f7c9b5bd53a769be32faf">llvm::SingleByteCoverage</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#a6fd927accec00ab7a4178b5290fcdb4b">llvm::InstrProfReader::success</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#a51d19452b19c498a18cafa947fd744ad">llvm::InstrProfReader::Symtab</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a3ef3ba43212f6a2779d594e507451d54">llvm::TemporalProfile</a>.</p>

</div>
</div>

### readNextRecord() {#a7d3a3124492d7f44aeebfea0d19e0e37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TextInstrProfReader::readNextRecord (<a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord">NamedInstrProfRecord</a> &amp; Record)</td>
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

<p>Read a single record.</p>

<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a2e51b1ab42e8a4a67f3445174be5191b">llvm::eof</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a7596fdd04dba990373ab2f3da0c7dd3f">llvm::malformed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0832225d8bce717f7aeb97c2f0eb2af3">llvm::NumBitmapBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a435d7554367e426f8c41efd8c1f70ab0">llvm::NumCounters</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#a6fd927accec00ab7a4178b5290fcdb4b">llvm::InstrProfReader::success</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#a51d19452b19c498a18cafa947fd744ad">llvm::InstrProfReader::Symtab</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086aac273a9aa2a7a6e63ef477fa7f6d1980">llvm::truncated</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### readTemporalProfTraceData() {#a82ac41fe67683b86cf94a838fcafad76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TextInstrProfReader::readTemporalProfTraceData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Temporal profile trace data is stored in the header immediately after ":temporal_prof_traces".</p>


<p>The first integer is the number of traces, the second integer is the stream size, then the following lines are the actual traces which consist of a weight and a comma separated list of function names.</p>


<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>

</div>
</div>

### readValueProfileData() {#af96e8dee455517fb60665ac236ebb60d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TextInstrProfReader::readValueProfileData (<a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DataBuffer {#ac33b6c4f85438af3892a8a365fae945e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::TextInstrProfReader::DataBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The profile data file contents.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### Line {#ad725363a709c06cb91225fe938e0c819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">line_iterator llvm::TextInstrProfReader::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterator over the profile data.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

### ProfileKind {#abc3e79d553338e4c6aee3690f6239f5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfKind llvm::TextInstrProfReader::ProfileKind = <a href="/web-llvm/docs/api/namespaces/llvm/#afe5a7327058c6702e128c22292fb66c6a88183b946cc5f0e8c96b2e66e1c74a7e">InstrProfKind::Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The attributes of the current profile.</p>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hasFormat() {#a54ea33c903b163ee020c34e36d6849c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TextInstrProfReader::hasFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; Buffer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the given buffer is in text instrprof format.</p>

<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a2ea075bd68f15b57e95f0771b8ba0bca">llvm::MemoryBuffer::getBufferSize</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#af1972b9a0324e0311ad641eac2de2b7f">llvm::MemoryBuffer::getBufferStart</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#a8cf37c58eefb5569a3926484ff808cbd">llvm::InstrProfReader::create</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp">InstrProfReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
