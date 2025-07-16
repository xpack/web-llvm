---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instrprofcorrelator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InstrProfCorrelator` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> - A base class used to create raw instrumentation data to their functions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InstrProfCorrelator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">llvm/ProfileData/InstrProfCorrelator.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl&lt;IntPtrT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a> - A child of <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> with a template pointer type so that the ProfileData vector can be materialized. <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ProfCorrelatorKind { <a href="#aa6c294f873ca4a3787ea1141651a50bc">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate if we should use the debug info or profile metadata sections to correlate. <a href="#aa6c294f873ca4a3787ea1141651a50bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InstrProfCorrelatorKind { <a href="#aacbf16aca287c7491c678a6f132873c5">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45cfb7087b46423d6bd9974207b5df55">yaml::MappingTraits&lt; Probe &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a4579b4cffe007c4a08ce13ddc9b21">yaml::SequenceElementTraits&lt; Probe &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6b71b249ab8e330ed16fe0daf6799bb">yaml::MappingTraits&lt; CorrelationData &gt;</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340992f098d86dcc24bdaf9f198f0008">InstrProfCorrelator</a> (InstrProfCorrelatorKind K, std::unique_ptr&lt; Context &gt; Ctx)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2e756c49a136925fa3d7e475ed76f06">~InstrProfCorrelator</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b0ac7772288ac324edaedc970c83a6">correlateProfileData</a> (int MaxWarnings)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a ProfileData vector used to correlate raw instrumentation data to their functions. <a href="#a03b0ac7772288ac324edaedc970c83a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa086a12a82afb12af0c630f30f22b608">dumpYaml</a> (int MaxWarnings, raw_ostream &amp;OS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> debug info and dump the correlation data. <a href="#aa086a12a82afb12af0c630f30f22b608">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace6cb8ffeb5b05b42dd0b4d380d40bfd">getDataSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of ProfileData elements. <a href="#ace6cb8ffeb5b05b42dd0b4d380d40bfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3723529a1e015ee50a468f84518ab0f">getNamesPointer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to the names string that this class constructs. <a href="#aa3723529a1e015ee50a468f84518ab0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d1ed41cd48281ff76b7da09c288ff6">getNamesSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bytes in the names string. <a href="#af0d1ed41cd48281ff76b7da09c288ff6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cfac0ed71a286456535f680f9bb97e1">getCountersSectionSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of the counters section in bytes. <a href="#a5cfac0ed71a286456535f680f9bb97e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aacbf16aca287c7491c678a6f132873c5">InstrProfCorrelatorKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b6fae97ca9f604200d48d66b552cd9">getKind</a> () const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/context">Context</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e9fa2e8b9f1243b2f9b970dc245bef">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8708967ee1eb68916b2b81d12dd2b17d">Names</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8152ecdc21d95b563f3de52c8f5993cd">NamesVec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aacbf16aca287c7491c678a6f132873c5">InstrProfCorrelatorKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8080f9d0a3d6f69dadb1ccb388076d09">Kind</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a7b88fce11b12853e7b60a06a033ec">get</a> (StringRef Filename, ProfCorrelatorKind FileKind, const object::BuildIDFetcher *BIDFetcher=nullptr, const ArrayRef&lt; llvm::object::BuildID &gt; BIs={})</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2709177afecd55c5eebbb19de037200">get</a> (std::unique_ptr&lt; MemoryBuffer &gt; Buffer, ProfCorrelatorKind FileKind)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc6b1d0c2b920b16ed75230ba60adab">FunctionNameAttributeName</a> = "Function Name"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f30dd52854058f8f5c43c981acaf69e">CFGHashAttributeName</a> = "CFG Hash"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e192a01c077915a4f5777e8c6a5ec85">NumCountersAttributeName</a> = "Num Counters"</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> - A base class used to create raw instrumentation data to their functions.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### InstrProfCorrelatorKind {#aacbf16aca287c7491c678a6f132873c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::InstrProfCorrelator::InstrProfCorrelatorKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_32Bit<a id="aacbf16aca287c7491c678a6f132873c5a0da63906732947731d2b0fe9f8c6cd2f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_64Bit<a id="aacbf16aca287c7491c678a6f132873c5a78613e0199a199b50f3f437128c1c6e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

### ProfCorrelatorKind {#aa6c294f873ca4a3787ea1141651a50bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::InstrProfCorrelator::ProfCorrelatorKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate if we should use the debug info or profile metadata sections to correlate.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NONE<a id="aa6c294f873ca4a3787ea1141651a50bcae0a2be4a55ac1c966a85951b21b0efb7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DEBUG_INFO<a id="aa6c294f873ca4a3787ea1141651a50bca1286d41436cfb2b7552cfc78df6a6d58"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BINARY<a id="aa6c294f873ca4a3787ea1141651a50bcaeb8f1bb3bf7d5d8b8f527130a92be816"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### yaml::MappingTraits&lt; CorrelationData &gt; {#aa6b71b249ab8e330ed16fe0daf6799bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits">yaml::MappingTraits</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/correlationdata">CorrelationData</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

### yaml::MappingTraits&lt; Probe &gt; {#a45cfb7087b46423d6bd9974207b5df55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits">yaml::MappingTraits</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/probe">Probe</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

### yaml::SequenceElementTraits&lt; Probe &gt; {#ad1a4579b4cffe007c4a08ce13ddc9b21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/yaml/sequenceelementtraits">yaml::SequenceElementTraits</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/probe">Probe</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### InstrProfCorrelator() {#a340992f098d86dcc24bdaf9f198f0008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfCorrelator::InstrProfCorrelator (<a href="#aacbf16aca287c7491c678a6f132873c5">InstrProfCorrelatorKind</a> K, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/context">Context</a> &gt; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>References <a href="#ac9e9fa2e8b9f1243b2f9b970dc245bef">Ctx</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#a892a9f42e8f35325931654ddb70595c7">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::classof</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InstrProfCorrelator() {#ab2e756c49a136925fa3d7e475ed76f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::InstrProfCorrelator::~InstrProfCorrelator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### correlateProfileData() {#a03b0ac7772288ac324edaedc970c83a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::InstrProfCorrelator::correlateProfileData (int MaxWarnings)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a ProfileData vector used to correlate raw instrumentation data to their functions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxWarnings</td>
<td class="doxyParamItemDescription"><p>the maximum number of warnings to emit (0 = no limit)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

### dumpYaml() {#aa086a12a82afb12af0c630f30f22b608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::InstrProfCorrelator::dumpYaml (int MaxWarnings, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> debug info and dump the correlation data.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxWarnings</td>
<td class="doxyParamItemDescription"><p>the maximum number of warnings to emit (0 = no limit)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

### getCountersSectionSize() {#a5cfac0ed71a286456535f680f9bb97e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::InstrProfCorrelator::getCountersSectionSize ()</td>
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

<p>Return the size of the counters section in bytes.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Reference <a href="#ac9e9fa2e8b9f1243b2f9b970dc245bef">Ctx</a>.</p>

</div>
</div>

### getDataSize() {#ace6cb8ffeb5b05b42dd0b4d380d40bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; size_t &gt; InstrProfCorrelator::getDataSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of ProfileData elements.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### getKind() {#ac7b6fae97ca9f604200d48d66b552cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfCorrelatorKind llvm::InstrProfCorrelator::getKind ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

### getNamesPointer() {#aa3723529a1e015ee50a468f84518ab0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::InstrProfCorrelator::getNamesPointer ()</td>
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

<p>Return a pointer to the names string that this class constructs.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Reference <a href="#a8708967ee1eb68916b2b81d12dd2b17d">Names</a>.</p>

</div>
</div>

### getNamesSize() {#af0d1ed41cd48281ff76b7da09c288ff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::InstrProfCorrelator::getNamesSize ()</td>
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

<p>Return the number of bytes in the names string.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Reference <a href="#a8708967ee1eb68916b2b81d12dd2b17d">Names</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Ctx {#ac9e9fa2e8b9f1243b2f9b970dc245bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::unique_ptr&lt;Context&gt; llvm::InstrProfCorrelator::Ctx</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/binaryinstrprofcorrelator/#a9a4f4600ec30ccc7b2fe6d75dc774ab5">llvm::BinaryInstrProfCorrelator&lt; IntPtrT &gt;::BinaryInstrProfCorrelator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfinstrprofcorrelator/#a5c0d4ad038bb0679b8e58456ff7e21e2">llvm::DwarfInstrProfCorrelator&lt; IntPtrT &gt;::DwarfInstrProfCorrelator</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#a03623c93978bf24485c895a53d164368">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::get</a>, <a href="#a5cfac0ed71a286456535f680f9bb97e1">getCountersSectionSize</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryinstrprofcorrelator/#a458c057bfde6e2e0bb705849cf1ef25a">llvm::BinaryInstrProfCorrelator&lt; IntPtrT &gt;::getNamesPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryinstrprofcorrelator/#a231b075aa389203c8b6fe6d66321b947">llvm::BinaryInstrProfCorrelator&lt; IntPtrT &gt;::getNamesSize</a>, <a href="#a340992f098d86dcc24bdaf9f198f0008">InstrProfCorrelator</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#a9110dae8cefc94bca7e5f15b038b2d6a">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::InstrProfCorrelatorImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#abab40c355a15eb07bed9a3bca7edb2e8">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::maybeSwap</a>.</p>

</div>
</div>

### Names {#a8708967ee1eb68916b2b81d12dd2b17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::InstrProfCorrelator::Names</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#a69ac01fb5a8e58ba5dcd203e77b864c3">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::correlateProfileData</a>, <a href="#aa3723529a1e015ee50a468f84518ab0f">getNamesPointer</a> and <a href="#af0d1ed41cd48281ff76b7da09c288ff6">getNamesSize</a>.</p>

</div>
</div>

### NamesVec {#a8152ecdc21d95b563f3de52c8f5993cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::InstrProfCorrelator::NamesVec</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#a69ac01fb5a8e58ba5dcd203e77b864c3">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::correlateProfileData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#a8080f9d0a3d6f69dadb1ccb388076d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrProfCorrelatorKind llvm::InstrProfCorrelator::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#ad3a7b88fce11b12853e7b60a06a033ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; std::unique_ptr&lt; InstrProfCorrelator &gt; &gt; InstrProfCorrelator::get (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="#aa6c294f873ca4a3787ea1141651a50bc">ProfCorrelatorKind</a> FileKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/buildidfetcher">object::BuildIDFetcher</a> * BIDFetcher=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a4304894bcf353bce5ba4d3dd7ff534d7">llvm::object::BuildID</a> &gt; BIs={})</td>
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



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>


<p>References <a href="#aa6c294f873ca4a3787ea1141651a50bcaeb8f1bb3bf7d5d8b8f527130a92be816">BINARY</a>, <a href="#aa6c294f873ca4a3787ea1141651a50bca1286d41436cfb2b7552cfc78df6a6d58">DEBUG_INFO</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab97c9dc8dec5b044b551639baf324053">llvm::errorOrToExpected</a>, <a href="/web-llvm/docs/api/classes/llvm/object/buildidfetcher/#a0b88868ad72597e4cc566ca26068dfc9">llvm::object::BuildIDFetcher::fetch</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a301ba38f5a267f3cf123d6a9f551e3fd">llvm::object::MachOObjectFile::findDsymObjectMembers</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="#ad3a7b88fce11b12853e7b60a06a033ec">get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a2ab0ff9f82990293dc09df4d7283c5dd">llvm::unable_to_correlate_profile</a>.</p>


<p>Referenced by <a href="#ad3a7b88fce11b12853e7b60a06a033ec">get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### get() {#ae2709177afecd55c5eebbb19de037200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; std::unique_ptr&lt; InstrProfCorrelator &gt; &gt; InstrProfCorrelator::get (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Buffer, <a href="#aa6c294f873ca4a3787ea1141651a50bc">ProfCorrelatorKind</a> FileKind)</td>
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



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### CFGHashAttributeName {#a2f30dd52854058f8f5c43c981acaf69e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * InstrProfCorrelator::CFGHashAttributeName = "CFG Hash"</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

### FunctionNameAttributeName {#a2cc6b1d0c2b920b16ed75230ba60adab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * InstrProfCorrelator::FunctionNameAttributeName = "Function Name"</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

### NumCountersAttributeName {#a8e192a01c077915a4f5777e8c6a5ec85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * InstrProfCorrelator::NumCountersAttributeName = "Num Counters"</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
