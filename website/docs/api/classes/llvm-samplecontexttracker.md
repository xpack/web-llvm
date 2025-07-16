---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/samplecontexttracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SampleContextTracker` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SampleContextTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">llvm/Transforms/IPO/SampleContextTracker.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a9b7d80dcef95b2edf085460d5980ae">ContextSamplesTy</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af52a487243093c41b1250ff0f5d25f10">SampleContextTracker</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8960053536efb781f864875695ddd403">SampleContextTracker</a> (SampleProfileMap &amp;Profiles, const DenseMap&lt; uint64_t, StringRef &gt; *GUIDToFuncNameMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f0ac0cd0b840c490d896fd333c79c51">populateFuncToCtxtMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a5eace41510a920670a82474022c7a">getCalleeContextSamplesFor</a> (const CallBase &amp;Inst, StringRef CalleeName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c5a7cbd593261dc632d06d8225c04d">getIndirectCalleeContextSamplesFor</a> (const DILocation *DIL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75bd919afb45ef334b6e8fa723d4beb5">getContextSamplesFor</a> (const DILocation *DIL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af28f7125a853d062a2d7257b4fb636bb">getContextSamplesFor</a> (const SampleContext &amp;Context)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7a9b7d80dcef95b2edf085460d5980ae">ContextSamplesTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83f63b9731fdab5bde79ae70ece636b9">getAllContextSamplesFor</a> (const Function &amp;Func)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7a9b7d80dcef95b2edf085460d5980ae">ContextSamplesTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53b3f2ae446672f3efef879c5a121641">getAllContextSamplesFor</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29ace6547e20981299820eb3779ceb51">getOrCreateContextPath</a> (const SampleContext &amp;Context, bool AllowCreate)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b4a3e47e33b66648a8b870f6182c1f2">getBaseSamplesFor</a> (const Function &amp;Func, bool MergeContext=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac617e33450ffda81e4b830543674abbf">getBaseSamplesFor</a> (FunctionId Name, bool MergeContext=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afabf889a9ec8cf67e7fbd0cbb4896114">getContextFor</a> (const SampleContext &amp;Context)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38619f3c2ad3874334865ce9543c03c6">getFuncNameFor</a> (ContextTrieNode *Node) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa144b495aee60da309a023d554952ac9">markContextSamplesInlined</a> (const FunctionSamples *InlinedSamples)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42ff5d19f024e956412b151ae3a095ec">getRootContext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03cbc7841d2552fcd7639666975fa13c">promoteMergeContextSamplesTree</a> (const Instruction &amp;Inst, FunctionId CalleeName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5b41c4e8db4215ef2a11b40cca0525d">createContextLessProfileMap</a> (SampleProfileMap &amp;ContextLessProfiles)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7484455941088a1d51ad0cb28671fc9c">getContextNodeForProfile</a> (const FunctionSamples *FSamples) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="#a7a9b7d80dcef95b2edf085460d5980ae">ContextSamplesTy</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3148fcffe222bd1965a28fecde75ee4d">getFuncToCtxtProfiles</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/iterator">Iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83752b2f27a46b7f0bea80368cbe84f0">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/iterator">Iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc29a07e94a407a336aeab6086cd3d0e">end</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea9ecee021e761f0e7dda19d1641840">getContextString</a> (const FunctionSamples &amp;FSamples) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa12ce67d21274bae7db762b1e5728bf6">getContextString</a> (ContextTrieNode *Node) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e92cc2ea24816c72aa10eda98125171">dump</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e050bc79e31e02b63c17f05be6edc4">getContextFor</a> (const DILocation *DIL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8300601a2a8910bd1adc297a1d825e6a">getCalleeContextFor</a> (const DILocation *DIL, FunctionId CalleeName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bb441d488b6cb0c30a7da9560573e5f">getTopLevelContextNode</a> (FunctionId FName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f952c45f9ae02842ebe15eaa1f29fda">addTopLevelContextNode</a> (FunctionId FName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c509e66dac32992b5001d7f5fbfbb92">promoteMergeContextSamplesTree</a> (ContextTrieNode &amp;NodeToPromo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f1c12c014d9d3cde322c571a81fd327">mergeContextNode</a> (ContextTrieNode &amp;FromNode, ContextTrieNode &amp;ToNode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a034b465c095375d082fa6414804f7e1c">promoteMergeContextSamplesTree</a> (ContextTrieNode &amp;FromNode, ContextTrieNode &amp;ToNodeParent)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1168b96d3cd9b774b914c8238789b389">moveContextSamples</a> (ContextTrieNode &amp;ToNodeParent, const LineLocation &amp;CallSite, ContextTrieNode &amp;&amp;NodeToMove)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a3b27d29b4455648f77dc84ea83db4">setContextNode</a> (const FunctionSamples *FSample, ContextTrieNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="#a7a9b7d80dcef95b2edf085460d5980ae">ContextSamplesTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c2f93b9aa5c72a50eb46430fdf5e386">FuncToCtxtProfiles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d43e36c65118f01d2a3a7bcbd9a27b8">ProfileToNodeMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511bf1ba495730eb25cb7bd6ea37737f">GUIDToFuncNameMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9ddc2fda31b20746125d6d8f3182ee3">RootContext</a></td>
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


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ContextSamplesTy {#a7a9b7d80dcef95b2edf085460d5980ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SampleContextTracker::ContextSamplesTy =  std::vector&lt;FunctionSamples *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SampleContextTracker() {#af52a487243093c41b1250ff0f5d25f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SampleContextTracker::SampleContextTracker ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### SampleContextTracker() {#a8960053536efb781f864875695ddd403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SampleContextTracker::SampleContextTracker (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; Profiles, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; * GUIDToFuncNameMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a247f427d8cb89802a69482144f937aaf">llvm::ContextTrieNode::getFunctionSamples</a>, <a href="#a29ace6547e20981299820eb3779ceb51">getOrCreateContextPath</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a3f0ac0cd0b840c490d896fd333c79c51">populateFuncToCtxtMap</a> and <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#ac12abae83b7ced7abcade7bc0c1b791a">llvm::ContextTrieNode::setFunctionSamples</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a83752b2f27a46b7f0bea80368cbe84f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Iterator llvm::SampleContextTracker::begin ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### createContextLessProfileMap() {#ac5b41c4e8db4215ef2a11b40cca0525d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleContextTracker::createContextLessProfileMap (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ContextLessProfiles)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap/#a21711def0b8514183a4394a50e525e81">llvm::sampleprof::SampleProfileMap::create</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adfcf1b41d1251eac2f16312eec52b45a">llvm::sampleprof::FunctionSamples::merge</a>.</p>

</div>
</div>

### dump() {#a7e92cc2ea24816c72aa10eda98125171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleContextTracker::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### end() {#acc29a07e94a407a336aeab6086cd3d0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Iterator llvm::SampleContextTracker::end ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### getAllContextSamplesFor() {#a83f63b9731fdab5bde79ae70ece636b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleContextTracker::ContextSamplesTy &amp; llvm::SampleContextTracker::getAllContextSamplesFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa7122a07ea48e47fc71083e68b829003">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a012731cbc58856aff956543ab824eb8d">llvm::sampleprof::getRepInFormat</a>.</p>

</div>
</div>

### getAllContextSamplesFor() {#a53b3f2ae446672f3efef879c5a121641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleContextTracker::ContextSamplesTy &amp; llvm::SampleContextTracker::getAllContextSamplesFor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a012731cbc58856aff956543ab824eb8d">llvm::sampleprof::getRepInFormat</a>.</p>

</div>
</div>

### getBaseSamplesFor() {#a0b4a3e47e33b66648a8b870f6182c1f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples * llvm::SampleContextTracker::getBaseSamplesFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, bool MergeContext=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="#a0b4a3e47e33b66648a8b870f6182c1f2">getBaseSamplesFor</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa7122a07ea48e47fc71083e68b829003">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a012731cbc58856aff956543ab824eb8d">llvm::sampleprof::getRepInFormat</a>.</p>


<p>Referenced by <a href="#a0b4a3e47e33b66648a8b870f6182c1f2">getBaseSamplesFor</a>.</p>

</div>
</div>

### getBaseSamplesFor() {#ac617e33450ffda81e4b830543674abbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples * llvm::SampleContextTracker::getBaseSamplesFor (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> Name, bool MergeContext=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a7484455941088a1d51ad0cb28671fc9c">getContextNodeForProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca0639979a0b27bb1cd0e0d94784fd3285">llvm::sampleprof::InlinedContext</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca341f13af8fa5d6c42e361bcf419abcff">llvm::sampleprof::MergedContext</a> and <a href="#a03cbc7841d2552fcd7639666975fa13c">promoteMergeContextSamplesTree</a>.</p>

</div>
</div>

### getCalleeContextSamplesFor() {#af9a5eace41510a920670a82474022c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples * llvm::SampleContextTracker::getCalleeContextSamplesFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CalleeName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa7122a07ea48e47fc71083e68b829003">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a>, <a href="#a4ea9ecee021e761f0e7dda19d1641840">getContextString</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a247f427d8cb89802a69482144f937aaf">llvm::ContextTrieNode::getFunctionSamples</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a012731cbc58856aff956543ab824eb8d">llvm::sampleprof::getRepInFormat</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### getContextFor() {#afabf889a9ec8cf67e7fbd0cbb4896114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode * llvm::SampleContextTracker::getContextFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Reference <a href="#a29ace6547e20981299820eb3779ceb51">getOrCreateContextPath</a>.</p>


<p>Referenced by <a href="#a75bd919afb45ef334b6e8fa723d4beb5">getContextSamplesFor</a>, <a href="#af28f7125a853d062a2d7257b4fb636bb">getContextSamplesFor</a>, <a href="#af2c5a7cbd593261dc632d06d8225c04d">getIndirectCalleeContextSamplesFor</a> and <a href="#a03cbc7841d2552fcd7639666975fa13c">promoteMergeContextSamplesTree</a>.</p>

</div>
</div>

### getContextNodeForProfile() {#a7484455941088a1d51ad0cb28671fc9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode * llvm::SampleContextTracker::getContextNodeForProfile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * FSamples)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ac617e33450ffda81e4b830543674abbf">getBaseSamplesFor</a> and <a href="#a4ea9ecee021e761f0e7dda19d1641840">getContextString</a>.</p>

</div>
</div>

### getContextSamplesFor() {#a75bd919afb45ef334b6e8fa723d4beb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples * llvm::SampleContextTracker::getContextSamplesFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DIL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="#afabf889a9ec8cf67e7fbd0cbb4896114">getContextFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca0639979a0b27bb1cd0e0d94784fd3285">llvm::sampleprof::InlinedContext</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#aa41059d227a82a3a80090c944aa80c5b">llvm::sampleprof::SampleContext::setState</a>.</p>

</div>
</div>

### getContextSamplesFor() {#af28f7125a853d062a2d7257b4fb636bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples * llvm::SampleContextTracker::getContextSamplesFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Reference <a href="#afabf889a9ec8cf67e7fbd0cbb4896114">getContextFor</a>.</p>

</div>
</div>

### getContextString() {#a4ea9ecee021e761f0e7dda19d1641840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::SampleContextTracker::getContextString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; FSamples)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="#a7484455941088a1d51ad0cb28671fc9c">getContextNodeForProfile</a> and <a href="#a4ea9ecee021e761f0e7dda19d1641840">getContextString</a>.</p>


<p>Referenced by <a href="#af9a5eace41510a920670a82474022c7a">getCalleeContextSamplesFor</a>, <a href="#a4ea9ecee021e761f0e7dda19d1641840">getContextString</a> and <a href="#aa144b495aee60da309a023d554952ac9">markContextSamplesInlined</a>.</p>

</div>
</div>

### getContextString() {#aa12ce67d21274bae7db762b1e5728bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::SampleContextTracker::getContextString (<a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a225eff054e4076aff7702dd9369d0541">llvm::ContextTrieNode::getCallSiteLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a9103cd6ba6a3cc429e059e53ac9212b8">llvm::sampleprof::SampleContext::getContextString</a>.</p>

</div>
</div>

### getFuncNameFor() {#a38619f3c2ad3874334865ce9543c03c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::SampleContextTracker::getFuncNameFor (<a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afddaa81316d56f125de69793e0ddb33c">llvm::sampleprof::FunctionSamples::UseMD5</a>.</p>

</div>
</div>

### getFuncToCtxtProfiles() {#a3148fcffe222bd1965a28fecde75ee4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashKeyMap&lt; std::unordered_map, FunctionId, ContextSamplesTy &gt; &amp; llvm::SampleContextTracker::getFuncToCtxtProfiles ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### getIndirectCalleeContextSamplesFor() {#af2c5a7cbd593261dc632d06d8225c04d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; const FunctionSamples * &gt; llvm::SampleContextTracker::getIndirectCalleeContextSamplesFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DIL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a0f957c3b9a4c1c915ff992784abea057">llvm::ContextTrieNode::getAllChildContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aeea4c49a1040f9305f6a09d7d7815544">llvm::sampleprof::FunctionSamples::getCallSiteIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a225eff054e4076aff7702dd9369d0541">llvm::ContextTrieNode::getCallSiteLoc</a>, <a href="#afabf889a9ec8cf67e7fbd0cbb4896114">getContextFor</a> and <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a247f427d8cb89802a69482144f937aaf">llvm::ContextTrieNode::getFunctionSamples</a>.</p>

</div>
</div>

### getOrCreateContextPath() {#a29ace6547e20981299820eb3779ceb51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode * llvm::SampleContextTracker::getOrCreateContextPath (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; Context, bool AllowCreate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#afabf889a9ec8cf67e7fbd0cbb4896114">getContextFor</a> and <a href="#a8960053536efb781f864875695ddd403">SampleContextTracker</a>.</p>

</div>
</div>

### getRootContext() {#a42ff5d19f024e956412b151ae3a095ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode &amp; llvm::SampleContextTracker::getRootContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph/#acae2ab44bcb9d9add7c351061ac8e6f6">llvm::sampleprof::ProfiledCallGraph::ProfiledCallGraph</a>.</p>

</div>
</div>

### markContextSamplesInlined() {#aa144b495aee60da309a023d554952ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleContextTracker::markContextSamplesInlined (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * InlinedSamples)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="#a4ea9ecee021e761f0e7dda19d1641840">getContextString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca0639979a0b27bb1cd0e0d94784fd3285">llvm::sampleprof::InlinedContext</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#aa41059d227a82a3a80090c944aa80c5b">llvm::sampleprof::SampleContext::setState</a>.</p>

</div>
</div>

### populateFuncToCtxtMap() {#a3f0ac0cd0b840c490d896fd333c79c51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleContextTracker::populateFuncToCtxtMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca33510720a1514b03ccfd70b909722ec6">llvm::sampleprof::RawContext</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#aa41059d227a82a3a80090c944aa80c5b">llvm::sampleprof::SampleContext::setState</a>.</p>


<p>Referenced by <a href="#a8960053536efb781f864875695ddd403">SampleContextTracker</a>.</p>

</div>
</div>

### promoteMergeContextSamplesTree() {#a03cbc7841d2552fcd7639666975fa13c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleContextTracker::promoteMergeContextSamplesTree (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> CalleeName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid/#a8f6fbd8851c1e7809544abaf1fae75a0">llvm::sampleprof::FunctionId::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a0f957c3b9a4c1c915ff992784abea057">llvm::ContextTrieNode::getAllChildContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aeea4c49a1040f9305f6a09d7d7815544">llvm::sampleprof::FunctionSamples::getCallSiteIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a225eff054e4076aff7702dd9369d0541">llvm::ContextTrieNode::getCallSiteLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#ab05fd0aa0f2a966006e4b4bd448617e7">llvm::ContextTrieNode::getChildContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="#afabf889a9ec8cf67e7fbd0cbb4896114">getContextFor</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a247f427d8cb89802a69482144f937aaf">llvm::ContextTrieNode::getFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a3f30fb3b02e2a17d75e3caf5af38eaed">llvm::sampleprof::SampleContext::hasState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca0639979a0b27bb1cd0e0d94784fd3285">llvm::sampleprof::InlinedContext</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a03cbc7841d2552fcd7639666975fa13c">promoteMergeContextSamplesTree</a>.</p>


<p>Referenced by <a href="#ac617e33450ffda81e4b830543674abbf">getBaseSamplesFor</a> and <a href="#a03cbc7841d2552fcd7639666975fa13c">promoteMergeContextSamplesTree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addTopLevelContextNode() {#a1f952c45f9ae02842ebe15eaa1f29fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode &amp; llvm::SampleContextTracker::addTopLevelContextNode (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> FName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### getCalleeContextFor() {#a8300601a2a8910bd1adc297a1d825e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode * llvm::SampleContextTracker::getCalleeContextFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DIL, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> CalleeName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### getContextFor() {#a43e050bc79e31e02b63c17f05be6edc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode * llvm::SampleContextTracker::getContextFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DIL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### getTopLevelContextNode() {#a1bb441d488b6cb0c30a7da9560573e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode * llvm::SampleContextTracker::getTopLevelContextNode (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> FName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### mergeContextNode() {#a3f1c12c014d9d3cde322c571a81fd327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleContextTracker::mergeContextNode (<a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp; FromNode, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp; ToNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### moveContextSamples() {#a1168b96d3cd9b774b914c8238789b389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode &amp; llvm::SampleContextTracker::moveContextSamples (<a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp; ToNodeParent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; CallSite, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp;&amp; NodeToMove)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### promoteMergeContextSamplesTree() {#a9c509e66dac32992b5001d7f5fbfbb92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode &amp; llvm::SampleContextTracker::promoteMergeContextSamplesTree (<a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp; NodeToPromo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### promoteMergeContextSamplesTree() {#a034b465c095375d082fa6414804f7e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode &amp; llvm::SampleContextTracker::promoteMergeContextSamplesTree (<a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp; FromNode, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &amp; ToNodeParent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### setContextNode() {#a47a3b27d29b4455648f77dc84ea83db4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleContextTracker::setContextNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * FSample, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> * Node)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FuncToCtxtProfiles {#a8c2f93b9aa5c72a50eb46430fdf5e386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashKeyMap&lt;std::unordered_map, FunctionId, ContextSamplesTy&gt; llvm::SampleContextTracker::FuncToCtxtProfiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### GUIDToFuncNameMap {#a511bf1ba495730eb25cb7bd6ea37737f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt;uint64_t, StringRef&gt;* llvm::SampleContextTracker::GUIDToFuncNameMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### ProfileToNodeMap {#a8d43e36c65118f01d2a3a7bcbd9a27b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;const FunctionSamples *, ContextTrieNode *&gt; llvm::SampleContextTracker::ProfileToNodeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### RootContext {#ae9ddc2fda31b20746125d6d8f3182ee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode llvm::SampleContextTracker::RootContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
