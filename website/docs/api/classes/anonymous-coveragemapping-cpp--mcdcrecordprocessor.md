---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-coveragemapping-cpp-/mcdcrecordprocessor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCDCRecordProcessor` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{CoverageMapping.cpp}::MCDCRecordProcessor { ... }
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-coveragemapping-cpp-/nextidsbuilder">NextIDsBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct this-&gt;NextIDs with Branches for TVIdxBuilder to use it before MCDCRecordProcessor(). <a href="/web-llvm/docs/api/classes/anonymous-coveragemapping-cpp-/nextidsbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coverage/mcdc/tvidxbuilder">TVIdxBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute TestVector Indices "TVIdx" from the Conds graph. <a href="/web-llvm/docs/api/classes/llvm/coverage/mcdc/tvidxbuilder/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6bbdfab424b93f5f9564d6317cf4af5">MCDCRecordProcessor</a> (const BitVector &amp;Bitmap, const CounterMappingRegion &amp;Region, ArrayRef&lt; const CounterMappingRegion * &gt; Branches, bool IsVersion11)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord">MCDCRecord</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbbbd2393a335a673e48fc85db8471f3">processMCDCRecord</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the MC/DC <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> in order to produce a result for a boolean expression. <a href="#adbbbd2393a335a673e48fc85db8471f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fe8ae3c49f16e7cdd2b8402a9de59de">buildTestVector</a> (MCDCRecord::TestVector &amp;TV, mcdc::ConditionID ID, int TVIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfeabe801fd5c127bd5ed35e41d100cf">findExecutedTestVectors</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walk the bits in the bitmap. <a href="#adfeabe801fd5c127bd5ed35e41d100cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05858e4a24067cfb179aa72b10860304">Bitmap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A bitmap representing the executed test vectors for a boolean expression. <a href="#a05858e4a24067cfb179aa72b10860304">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b2cef896c5f7ea9b37d234dc1a7e8df">Region</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decision Region to which the ExecutedTestVectorBitmap applies. <a href="#a7b2cef896c5f7ea9b37d234dc1a7e8df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdc/decisionparameters">mcdc::DecisionParameters</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18d166926f344686fd5fef1b51b04717">DecisionParams</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66979056ab28f258da9a8ba092e3c358">Branches</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Array of branch regions corresponding each conditions in the boolean expression. <a href="#a66979056ab28f258da9a8ba092e3c358">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6708a1f3a0fb4a245ca8580275cb05">NumConditions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total number of conditions in the boolean expression. <a href="#a5d6708a1f3a0fb4a245ca8580275cb05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#ae5afbd567b8595b229fcb547dfbfd760">MCDCRecord::BoolVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a7b96551e08565d8bfe908cbaf35f7f">Folded</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector used to track whether a condition is constant folded. <a href="#a0a7b96551e08565d8bfe908cbaf35f7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#af42c29c8bb4f6cfab16f5a483728c913">MCDCRecord::TVPairMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55c4cf438265aa52a4ee449ac78fd83">IndependencePairs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping of calculated MC/DC Independence Pairs for each condition. <a href="#ab55c4cf438265aa52a4ee449ac78fd83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#a59573d02b596b1d3f901d928fbab9a5f">MCDCRecord::TestVectors</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe37f97a4366d02cbe6c18a9995798b4">ExecVectorsByCond</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Storage for ExecVectors ExecVectors is the alias of its 0th element. <a href="#abe37f97a4366d02cbe6c18a9995798b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#a59573d02b596b1d3f901d928fbab9a5f">MCDCRecord::TestVectors</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b0714754f9afbb8ac1e476e2dc004f6">ExecVectors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Actual executed Test Vectors for the boolean expression, based on ExecutedTestVectorBitmap. <a href="#a5b0714754f9afbb8ac1e476e2dc004f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad65e7991322d3196a8c3f9d443034109">TVIdxs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982cade59f7bbae2a34b65f1a5292093">IsVersion11</a></td>
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


<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCDCRecordProcessor() {#ad6bbdfab424b93f5f9564d6317cf4af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::MCDCRecordProcessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; Bitmap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a> &amp; Region, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a> * &gt; Branches, bool IsVersion11)</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-coveragemapping-cpp-/nextidsbuilder/#ab1703675851cc6adf45c6a547ec73b00">anonymous{CoverageMapping.cpp}::NextIDsBuilder::NextIDs</a>, <a href="/web-llvm/docs/api/classes/anonymous-coveragemapping-cpp-/nextidsbuilder/#a8aa8068dd2c7f1dae5774ac028abe168">anonymous{CoverageMapping.cpp}::NextIDsBuilder::NextIDsBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/coverage/mcdc/tvidxbuilder/#a85f4860524d04ca3d92dae7f5b1a9fba">llvm::coverage::mcdc::TVIdxBuilder::TVIdxBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### processMCDCRecord() {#adbbbd2393a335a673e48fc85db8471f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDCRecord anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::processMCDCRecord ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the MC/DC <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> in order to produce a result for a boolean expression.</p>


<p>This process includes tracking the conditions that comprise the decision region, calculating the list of all possible test vectors, marking the executed test vectors, and then finding an Independence Pair out of the executed test vectors for each condition in the boolean expression. A condition is tracked to ensure that its <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> can be mapped to its ordinal position in the boolean expression. The condition's source location is also tracked, as well as whether it is constant folded (in which case it is excuded from the metric).</p>


<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildTestVector() {#a5fe8ae3c49f16e7cdd2b8402a9de59de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::buildTestVector (<a href="/web-llvm/docs/api/classes/llvm/coverage/mcdcrecord/testvector">MCDCRecord::TestVector</a> &amp; TV, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/mcdc/#a63a49e70ac940938cebbbe7c41a08cce">mcdc::ConditionID</a> ID, int TVIdx)</td>
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



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### findExecutedTestVectors() {#adfeabe801fd5c127bd5ed35e41d100cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::findExecutedTestVectors ()</td>
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

<p>Walk the bits in the bitmap.</p>


<p>A bit set to '1' indicates that the test vector at the corresponding index was executed during a test run.</p>


<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bitmap {#a05858e4a24067cfb179aa72b10860304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector&amp; anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::Bitmap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A bitmap representing the executed test vectors for a boolean expression.</p>


<p>Each index of the bitmap corresponds to a possible test vector. An index with a bit value of '1' indicates that the corresponding Test Vector identified by that index was executed.</p>


<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### Branches {#a66979056ab28f258da9a8ba092e3c358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;const CounterMappingRegion *&gt; anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::Branches</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Array of branch regions corresponding each conditions in the boolean expression.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### DecisionParams {#a18d166926f344686fd5fef1b51b04717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const mcdc::DecisionParameters&amp; anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::DecisionParams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### ExecVectors {#a5b0714754f9afbb8ac1e476e2dc004f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDCRecord::TestVectors&amp; anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::ExecVectors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Actual executed Test Vectors for the boolean expression, based on ExecutedTestVectorBitmap.</p>

<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### ExecVectorsByCond {#abe37f97a4366d02cbe6c18a9995798b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;MCDCRecord::TestVectors, 2&gt; anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::ExecVectorsByCond</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Storage for ExecVectors ExecVectors is the alias of its 0th element.</p>

<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### Folded {#a0a7b96551e08565d8bfe908cbaf35f7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDCRecord::BoolVector anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::Folded</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector used to track whether a condition is constant folded.</p>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### IndependencePairs {#ab55c4cf438265aa52a4ee449ac78fd83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDCRecord::TVPairMap anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::IndependencePairs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping of calculated MC/DC Independence Pairs for each condition.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### IsVersion11 {#a982cade59f7bbae2a34b65f1a5292093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::IsVersion11</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### NumConditions {#a5d6708a1f3a0fb4a245ca8580275cb05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::NumConditions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Total number of conditions in the boolean expression.</p>

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### Region {#a7b2cef896c5f7ea9b37d234dc1a7e8df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CounterMappingRegion&amp; anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::Region</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decision Region to which the ExecutedTestVectorBitmap applies.</p>

<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### TVIdxs {#ad65e7991322d3196a8c3f9d443034109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;unsigned&gt; anonymous{CoverageMapping.cpp}::MCDCRecordProcessor::TVIdxs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
