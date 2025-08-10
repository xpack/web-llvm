---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `TypeHashing.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">llvm/DebugInfo/CodeView/TypeHashing.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typeindexdiscovery-h">llvm/DebugInfo/CodeView/TypeIndexDiscovery.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">llvm/Support/BLAKE3.h</a>"
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeview/locallyhashedtype">LocallyHashedType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066f917f4a73ce07260b0e4262be92ba">DenseMapInfo&lt; LocallyHashedType &gt;::Empty</a> {0, {}}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeview/locallyhashedtype">LocallyHashedType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58762abf82ba4b9f2f46d3b89070d6c1">DenseMapInfo&lt; LocallyHashedType &gt;::Tombstone</a> {<a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a>(-1), {}}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::array&lt; uint8_t, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9a83559273f0aefcc65aca2abe5223">EmptyHash</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::array&lt; uint8_t, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1271abb0a3e60a5f41463ac3cfe4d67">TombstoneHash</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47d461cd30a3c8d529207a56ef4154a9">DenseMapInfo&lt; GloballyHashedType &gt;::Empty</a> {<a href="#adc9a83559273f0aefcc65aca2abe5223">EmptyHash</a>}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a847a86bd907aad2e9136cef29586bc8f">DenseMapInfo&lt; GloballyHashedType &gt;::Tombstone</a> {<a href="#ad1271abb0a3e60a5f41463ac3cfe4d67">TombstoneHash</a>}</td>
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


<div class="doxySectionDef">

## Variables

### DenseMapInfo&lt; GloballyHashedType &gt;::Empty {#a47d461cd30a3c8d529207a56ef4154a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GloballyHashedType DenseMapInfo&lt; GloballyHashedType &gt;::Empty {<a href="#adc9a83559273f0aefcc65aca2abe5223">EmptyHash</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp">TypeHashing.cpp</a>.</p>

</div>
</div>

### DenseMapInfo&lt; GloballyHashedType &gt;::Tombstone {#a847a86bd907aad2e9136cef29586bc8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GloballyHashedType DenseMapInfo&lt; GloballyHashedType &gt;::Tombstone {<a href="#ad1271abb0a3e60a5f41463ac3cfe4d67">TombstoneHash</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp">TypeHashing.cpp</a>.</p>

</div>
</div>

### DenseMapInfo&lt; LocallyHashedType &gt;::Empty {#a066f917f4a73ce07260b0e4262be92ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocallyHashedType DenseMapInfo&lt; LocallyHashedType &gt;::Empty {0, {}}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp">TypeHashing.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ad89ca302de455d3971f751c8d1a5bd58">llvm::MemorySSAUpdater::applyUpdates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb6fca77863850136760be488d6ea345">llvm::dumpRegSetPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#afb719bff41b5688bcd0e39208d11677f">llvm::HexagonRegisterInfo::getCallerSavedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a29c708de8e758ac420523c94c797b501">getDebugLocFromInstOrOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymboltable/#adbd42021a3ce3803cf25cf07b54a0d67">llvm::logicalview::LVSymbolTable::getEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp/#a50a4b76a4e856e2e4b0e5fe36e7d5e09">getFirstCompositeRange</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#afc03c7ece1270aa0066e484af24eb28f">llvm::SIRegisterInfo::getRegUnitPressureSets</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, DenseMap&lt; ValueT, detail::DenseSetEmpty, ValueInfoT, detail::DenseSetPair&lt; ValueT &gt; &gt;, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a14bde875c76c33528837b5248483b90b">llvm::detail::DenseSetImpl&lt; ValueT, DenseMap&lt; ValueT, detail::DenseSetEmpty, ValueInfoT, detail::DenseSetPair&lt; ValueT &gt; &gt;, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#aa2b11e914798a4e54c7e640722f1b08d">llvm::PredicatedScalarEvolution::PredicatedScalarEvolution</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pgoctxprofreader-cpp-/#adbbd2ec36cbfb0867c1747b2c445fe41">anonymous{PGOCtxProfReader.cpp}::toYaml</a> and <a href="/web-llvm/docs/api/structs/anonymous-autoupgrade-cpp-/amdgpuunsafefpatomicsupgradevisitor/#aa5a373065be6eabfcc9eeb46018af87c">anonymous{AutoUpgrade.cpp}::AMDGPUUnsafeFPAtomicsUpgradeVisitor::visitAtomicRMWInst</a>.</p>

</div>
</div>

### DenseMapInfo&lt; LocallyHashedType &gt;::Tombstone {#a58762abf82ba4b9f2f46d3b89070d6c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocallyHashedType DenseMapInfo&lt; LocallyHashedType &gt;::Tombstone {<a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a>(-1), {}}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp">TypeHashing.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rangelistentry/#a9490d0b5d168b24193e600de304103e1">llvm::RangeListEntry::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrangelist/#a988c616ede2f0e4cf1c8c4f5faa554c8">llvm::DWARFDebugRangeList::getAbsoluteRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrnglist/#a08ab890d3a702ced75f774fa2bad2bbc">llvm::DWARFDebugRnglist::getAbsoluteRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a75a8f3e9af7915e4b0b10f9e17de63ca">llvm::DWARFDie::getHighPC</a>, <a href="/web-llvm/docs/api/structs/llvm/pdb/symboldensemapinfo/#aaad7a8a467f862dd084bf18951b64280">llvm::pdb::SymbolDenseMapInfo::getTombstoneKey</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>.</p>

</div>
</div>

### EmptyHash {#adc9a83559273f0aefcc65aca2abe5223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;uint8_t, 8&gt; EmptyHash</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00}}
</div>
</dd>
</dl>

<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp">TypeHashing.cpp</a>.</p>

</div>
</div>

### TombstoneHash {#ad1271abb0a3e60a5f41463ac3cfe4d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;uint8_t, 8&gt; TombstoneHash</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {0xFF, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00}}
</div>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp">TypeHashing.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
