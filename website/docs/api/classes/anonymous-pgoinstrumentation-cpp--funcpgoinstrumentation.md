---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-pgoinstrumentation-cpp-/funcpgoinstrumentation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FuncPGOInstrumentation` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;class Edge, class BBInfo&gt;
class anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt;Edge, BBInfo&gt; { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4745567b4c976c8dd075125fff13eb54">FuncPGOInstrumentation</a> (Function &amp;Func, TargetLibraryInfo &amp;TLI, std::unordered_multimap&lt; Comdat *, GlobalValue * &gt; &amp;ComdatMembers, bool CreateGlobalVar=false, BranchProbabilityInfo *BPI=nullptr, BlockFrequencyInfo *BFI=nullptr, LoopInfo *LI=nullptr, bool IsCS=false, bool InstrumentFuncEntry=true, bool InstrumentLoopEntries=false, bool HasSingleByteCoverage=false)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2876942731e1d9fd082f8bb9d2bda898">getInstrumentBBs</a> (std::vector&lt; BasicBlock * &gt; &amp;InstrumentBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all the BBs that will be instruments and add them to <span class="doxyComputerOutput">InstrumentBBs</span>. <a href="#a2876942731e1d9fd082f8bb9d2bda898">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5e10295899c921b1730c88017d1bc4d6">getInstrBB</a> (Edge *E)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BBInfo &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a339b5ad82df6c72ba2313fa01a33b9cc">getBBInfo</a> (const BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BBInfo *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a17d186d046fe9ffbb2233682815a0651">findBBInfo</a> (const BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6743fe2a6d559d064fb99fcf01f41229">dumpInfo</a> (StringRef Str="") const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a542d06864b8dade5c60add3460f682">computeCFGHash</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a29f6e226469c2cc506436769d43a9513">renameComdatFunction</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa87666b068fc63aa8b7ebefd6119d6d2">TLI</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a93b02dcc9ad7c8870705384937946426">VPCandidateInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a34c5bba8cfca0fc1a8b19b4f96d19921">ValueSites</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-pgoinstrumentation-cpp-/selectinstvisitor">SelectInstVisitor</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac4964cc328cca6659e0d329252ffc76f">SIVisitor</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af7fb543244ce388b13bdf0f689027950">FuncName</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5378f3010d03bf85da8662e1e427029b">DeprecatedFuncName</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27a87e7b0729f805ca26aec7ce1bf3c1">FuncNameVar</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a403d8592dd61fe6a61bb76cd011b19f2">FunctionHash</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cfgmst">CFGMST</a>&lt; Edge, BBInfo &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba90c94167488013a625a948be022e53">MST</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/blockcoverageinference">BlockCoverageInference</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ff45bfd45b2199b85326b2b66ea20b2">BCI</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16c8e0b4f60a7679aab3592ba0d6f5b5">F</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab16aaf75e5d36e289eb88ea1a87c1b6f">IsCS</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::unordered_multimap&lt; <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa443dfb0f7545cd5e0158041bd731bd4">ComdatMembers</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valueprofilecollector">ValueProfileCollector</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3de4d666e80974987ab697172590ed86">VPC</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae5ad4817ba766285a1b984c6bfd1d0e2">constructBCI</a> (Function &amp;Func, bool HasSingleByteCoverage, bool InstrumentFuncEntry) -&gt; std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/blockcoverageinference">BlockCoverageInference</a> &gt;</td>
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


<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FuncPGOInstrumentation() {#a4745567b4c976c8dd075125fff13eb54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, std::unordered_multimap&lt; <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt; &amp; ComdatMembers, bool CreateGlobalVar=false, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> * BPI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI=nullptr, bool IsCS=false, bool InstrumentFuncEntry=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool InstrumentLoopEntries=false, bool HasSingleByteCoverage=false)</td>
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



<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>References <a href="#a3ff45bfd45b2199b85326b2b66ea20b2">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::BCI</a>, <a href="#ae5ad4817ba766285a1b984c6bfd1d0e2">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::constructBCI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6791ec50da8cffef53eae412b5b90936">llvm::createPGOFuncNameVar</a>, <a href="#a5378f3010d03bf85da8662e1e427029b">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::DeprecatedFuncName</a>, <a href="#a6743fe2a6d559d064fb99fcf01f41229">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::dumpInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af32878ec52dce0e4c46389f07efbc101">llvm::EnableVTableValueProfiling</a>, <a href="#af7fb543244ce388b13bdf0f689027950">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncName</a>, <a href="#a27a87e7b0729f805ca26aec7ce1bf3c1">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncNameVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1b3e6af13e7130b5bd9994948ec48ccd">llvm::getIRPGOFuncName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a133c5cb70e0ea68fc5e503b7a7732390">llvm::getPGOFuncName</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aba90c94167488013a625a948be022e53">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::MST</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#ad7524c9441f8bbae8681ba775d2d2868">PGOViewBlockCoverageGraph</a>, <a href="#ac4964cc328cca6659e0d329252ffc76f">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::SIVisitor</a>, <a href="#aa87666b068fc63aa8b7ebefd6119d6d2">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::TLI</a> and <a href="#a34c5bba8cfca0fc1a8b19b4f96d19921">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::ValueSites</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dumpInfo() {#a6743fe2a6d559d064fb99fcf01f41229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::dumpInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str="")</td>
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



<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#af7fb543244ce388b13bdf0f689027950">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncName</a>, <a href="#a403d8592dd61fe6a61bb76cd011b19f2">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FunctionHash</a> and <a href="#aba90c94167488013a625a948be022e53">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::MST</a>.</p>


<p>Referenced by <a href="#a4745567b4c976c8dd075125fff13eb54">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation</a>.</p>

</div>
</div>

### findBBInfo() {#a17d186d046fe9ffbb2233682815a0651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBInfo * anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::findBBInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Reference <a href="#aba90c94167488013a625a948be022e53">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::MST</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#acac2cdce1b0c83bc61f41259233faef5">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::populateCounters</a>.</p>

</div>
</div>

### getBBInfo() {#a339b5ad82df6c72ba2313fa01a33b9cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBInfo &amp; anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::getBBInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Reference <a href="#aba90c94167488013a625a948be022e53">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::MST</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#a1a310418cc4a6390149e5428eed88406">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::annotateIrrLoopHeaderWeights</a>, <a href="#a5e10295899c921b1730c88017d1bc4d6">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::getInstrBB</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#acac2cdce1b0c83bc61f41259233faef5">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::populateCounters</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#a2552b5ad0f8384773bd8c70dc002b0c6">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::readCounters</a> and <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#a693592fa7e2d0950e30d14f38c333f9b">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::setBranchWeights</a>.</p>

</div>
</div>

### getInstrBB() {#a5e10295899c921b1730c88017d1bc4d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * FuncPGOInstrumentation::getInstrBB (Edge * E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a339b5ad82df6c72ba2313fa01a33b9cc">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::getBBInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3287172f2d13af086e6d66364e8c6de3">llvm::Instruction::getNumSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1b38a63d3be7413f335be5f2d81bb234">llvm::GetSuccessorNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aba90c94167488013a625a948be022e53">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::MST</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab61955a622d233750894890e0704da5c">llvm::SplitCriticalEdge</a>.</p>


<p>Referenced by <a href="#a2876942731e1d9fd082f8bb9d2bda898">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::getInstrumentBBs</a>.</p>

</div>
</div>

### getInstrumentBBs() {#a2876942731e1d9fd082f8bb9d2bda898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FuncPGOInstrumentation::getInstrumentBBs (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; InstrumentBBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect all the BBs that will be instruments and add them to <span class="doxyComputerOutput">InstrumentBBs</span>.</p>

<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>References <a href="#a3ff45bfd45b2199b85326b2b66ea20b2">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::BCI</a>, <a href="#a5e10295899c921b1730c88017d1bc4d6">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::getInstrBB</a> and <a href="#aba90c94167488013a625a948be022e53">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::MST</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeCFGHash() {#a3a542d06864b8dade5c60add3460f682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FuncPGOInstrumentation::computeCFGHash ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>

</div>
</div>

### renameComdatFunction() {#a29f6e226469c2cc506436769d43a9513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FuncPGOInstrumentation::renameComdatFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BCI {#a3ff45bfd45b2199b85326b2b66ea20b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt;BlockCoverageInference&gt; anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::BCI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a4745567b4c976c8dd075125fff13eb54">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation</a> and <a href="#a2876942731e1d9fd082f8bb9d2bda898">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::getInstrumentBBs</a>.</p>

</div>
</div>

### DeprecatedFuncName {#a5378f3010d03bf85da8662e1e427029b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::DeprecatedFuncName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a4745567b4c976c8dd075125fff13eb54">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation</a>.</p>

</div>
</div>

### FuncName {#af7fb543244ce388b13bdf0f689027950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a6743fe2a6d559d064fb99fcf01f41229">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::dumpInfo</a> and <a href="#a4745567b4c976c8dd075125fff13eb54">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation</a>.</p>

</div>
</div>

### FuncNameVar {#a27a87e7b0729f805ca26aec7ce1bf3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncNameVar</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a4745567b4c976c8dd075125fff13eb54">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation</a>.</p>

</div>
</div>

### FunctionHash {#a403d8592dd61fe6a61bb76cd011b19f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FunctionHash = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a6743fe2a6d559d064fb99fcf01f41229">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::dumpInfo</a>.</p>

</div>
</div>

### MST {#aba90c94167488013a625a948be022e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CFGMST&lt;Edge, BBInfo&gt; anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::MST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a6743fe2a6d559d064fb99fcf01f41229">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::dumpInfo</a>, <a href="#a17d186d046fe9ffbb2233682815a0651">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::findBBInfo</a>, <a href="#a4745567b4c976c8dd075125fff13eb54">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation</a>, <a href="#a339b5ad82df6c72ba2313fa01a33b9cc">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::getBBInfo</a>, <a href="#a5e10295899c921b1730c88017d1bc4d6">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::getInstrBB</a> and <a href="#a2876942731e1d9fd082f8bb9d2bda898">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::getInstrumentBBs</a>.</p>

</div>
</div>

### SIVisitor {#ac4964cc328cca6659e0d329252ffc76f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectInstVisitor anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::SIVisitor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a4745567b4c976c8dd075125fff13eb54">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation</a>.</p>

</div>
</div>

### TLI {#aa87666b068fc63aa8b7ebefd6119d6d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo&amp; anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a4745567b4c976c8dd075125fff13eb54">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation</a>.</p>

</div>
</div>

### ValueSites {#a34c5bba8cfca0fc1a8b19b4f96d19921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;VPCandidateInfo&gt; &gt; anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::ValueSites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a4745567b4c976c8dd075125fff13eb54">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ComdatMembers {#aa443dfb0f7545cd5e0158041bd731bd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_multimap&lt;Comdat *, GlobalValue *&gt;&amp; anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::ComdatMembers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>

</div>
</div>

### F {#a16c8e0b4f60a7679aab3592ba0d6f5b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>

</div>
</div>

### IsCS {#ab16aaf75e5d36e289eb88ea1a87c1b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::IsCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>

</div>
</div>

### VPC {#a3de4d666e80974987ab697172590ed86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueProfileCollector anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::VPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### constructBCI() {#ae5ad4817ba766285a1b984c6bfd1d0e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; BlockCoverageInference &gt; anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::constructBCI (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, bool HasSingleByteCoverage, bool InstrumentFuncEntry)</td>
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



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a>.</p>


<p>Referenced by <a href="#a4745567b4c976c8dd075125fff13eb54">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp">PGOInstrumentation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
