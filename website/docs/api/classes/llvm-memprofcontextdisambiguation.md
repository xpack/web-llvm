---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memprofcontextdisambiguation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemProfContextDisambiguation` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MemProfContextDisambiguation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">llvm/Transforms/IPO/MemProfContextDisambiguation.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc69efe5e1b61e475c294e22e3601d5">MemProfContextDisambiguation</a> (const ModuleSummaryIndex *Summary=nullptr, bool isSamplePGO=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac43814024a542d89728f88411b553e6d">run</a> (Module &amp;M, ModuleAnalysisManager &amp;AM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abab06043547d675404b0a17d136fafc8">run</a> (ModuleSummaryIndex &amp;Index, function_ref&lt; bool(GlobalValue::GUID, const GlobalValueSummary *)&gt; isPrevailing)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59d390ac91da7acb5e4150371b011c6">processModule</a> (Module &amp;M, function_ref&lt; OptimizationRemarkEmitter &amp;(Function *)&gt; OREGetter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the context disambiguator on <span class="doxyComputerOutput">M</span>, returns true if any changes made. <a href="#af59d390ac91da7acb5e4150371b011c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64929f37ea0ebb3523b92b3648d0263">applyImport</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In the ThinLTO backend, apply the cloning decisions in ImportSummary to the IR. <a href="#af64929f37ea0ebb3523b92b3648d0263">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90089eb7f698421087a45af9c474c3ef">initializeIndirectCallPromotionInfo</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee775a02bbe23cb36ae9d3459758908e">recordICPInfo</a> (CallBase *CB, ArrayRef&lt; CallsiteInfo &gt; AllCallsites, ArrayRef&lt; CallsiteInfo &gt;::iterator &amp;SI, SmallVector&lt; ICallAnalysisData &gt; &amp;ICallAnalysisInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6f0134c450bff7b90c3d29d4067316d">performICP</a> (Module &amp;M, ArrayRef&lt; CallsiteInfo &gt; AllCallsites, ArrayRef&lt; std::unique_ptr&lt; ValueToValueMapTy &gt; &gt; VMaps, ArrayRef&lt; ICallAnalysisData &gt; ICallAnalysisInfo, OptimizationRemarkEmitter &amp;ORE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affd950cd8c448c24a37aeb3aa2d883da">ImportSummary</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Import summary containing cloning decisions for the ThinLTO backend. <a href="#affd950cd8c448c24a37aeb3aa2d883da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab78633277e7e2d98b6299cd1e5ad2563">ImportSummaryForTesting</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d74a1e7558062fe59d663d67f29d4cb">isSamplePGO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77d7d3acc0810a3e1c23ef0e0244994c">Symtab</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/icallpromotionanalysis">ICallPromotionAnalysis</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a144199ed2da60a749c535c70bae45296">ICallAnalysis</a></td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MemProfContextDisambiguation() {#abfc69efe5e1b61e475c294e22e3601d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemProfContextDisambiguation::MemProfContextDisambiguation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * Summary=nullptr, bool isSamplePGO=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>, definition at line 4859 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab97c9dc8dec5b044b551639baf324053">llvm::errorOrToExpected</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59316b66df2176ff19458e2d624b98ad">llvm::getModuleSummaryIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#ac577f50d4870e58f3716e9f06eca5491">MemProfImportSummary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#ac43814024a542d89728f88411b553e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses MemProfContextDisambiguation::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>, definition at line 4891 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a> and <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>.</p>

</div>
</div>

### run() {#abab06043547d675404b0a17d136fafc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemProfContextDisambiguation::run (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *)&gt; isPrevailing)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>, definition at line 4902 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8e71e9f801d8c3d999ee7a7f3cd8b1c3">llvm::SupportsHotColdNew</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyImport() {#af64929f37ea0ebb3523b92b3648d0263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemProfContextDisambiguation::applyImport (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In the ThinLTO backend, apply the cloning decisions in ImportSummary to the IR.</p>

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>, definition at line 4260 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### initializeIndirectCallPromotionInfo() {#a90089eb7f698421087a45af9c474c3ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemProfContextDisambiguation::initializeIndirectCallPromotionInfo (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>, definition at line 4238 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### performICP() {#af6f0134c450bff7b90c3d29d4067316d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemProfContextDisambiguation::performICP (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/callsiteinfo">CallsiteInfo</a> &gt; AllCallsites, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &gt; &gt; VMaps, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; ICallAnalysisData &gt; ICallAnalysisInfo, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>, definition at line 4675 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### processModule() {#af59d390ac91da7acb5e4150371b011c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemProfContextDisambiguation::processModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *)&gt; OREGetter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run the context disambiguator on <span class="doxyComputerOutput">M</span>, returns true if any changes made.</p>

<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>, definition at line 4835 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### recordICPInfo() {#aee775a02bbe23cb36ae9d3459758908e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MemProfContextDisambiguation::recordICPInfo (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/callsiteinfo">CallsiteInfo</a> &gt; AllCallsites, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/callsiteinfo">CallsiteInfo</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> &amp; SI, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; ICallAnalysisData &gt; &amp; ICallAnalysisInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>, definition at line 4627 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ICallAnalysis {#a144199ed2da60a749c535c70bae45296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ICallPromotionAnalysis&gt; llvm::MemProfContextDisambiguation::ICallAnalysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>.</p>

</div>
</div>

### ImportSummary {#affd950cd8c448c24a37aeb3aa2d883da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleSummaryIndex* llvm::MemProfContextDisambiguation::ImportSummary</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Import summary containing cloning decisions for the ThinLTO backend.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>.</p>

</div>
</div>

### ImportSummaryForTesting {#ab78633277e7e2d98b6299cd1e5ad2563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ModuleSummaryIndex&gt; llvm::MemProfContextDisambiguation::ImportSummaryForTesting</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>.</p>

</div>
</div>

### isSamplePGO {#a5d74a1e7558062fe59d663d67f29d4cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemProfContextDisambiguation::isSamplePGO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>.</p>

</div>
</div>

### Symtab {#a77d7d3acc0810a3e1c23ef0e0244994c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InstrProfSymtab&gt; llvm::MemProfContextDisambiguation::Symtab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">MemProfContextDisambiguation.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
