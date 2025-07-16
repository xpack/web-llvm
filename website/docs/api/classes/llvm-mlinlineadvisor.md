---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mlinlineadvisor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MLInlineAdvisor` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MLInlineAdvisor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">llvm/Analysis/MLInlineAdvisor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface for deciding whether to inline a call site or not. <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a721f6a9227830f0254a70a740f43f24f">MLInlineAdvisor</a> (Module &amp;M, ModuleAnalysisManager &amp;MAM, std::unique_ptr&lt; MLModelRunner &gt; ModelRunner, std::function&lt; bool(CallBase &amp;)&gt; GetDefaultAdvice)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae13a64e601a0aa04050c096a1ac684ba">~MLInlineAdvisor</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaec1d89794dccf1f6d02c0e46258796">onPassEntry</a> (LazyCallGraph::SCC *SCC) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This must be called when the Inliner pass is entered, to allow the <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> update internal state, as result of function passes run between Inliner pass runs (for the same module). <a href="#aaaec1d89794dccf1f6d02c0e46258796">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42079a872d9a000c124cef0d38723741">onPassExit</a> (LazyCallGraph::SCC *SCC) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This must be called when the Inliner pass is exited, as function passes may be run subsequently. <a href="#a42079a872d9a000c124cef0d38723741">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad64807412969a3708f691675898a58c0">getIRSize</a> (Function &amp;F) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8116ffdfb54f7d195eb185c8bf7c060c">onSuccessfulInlining</a> (const MLInlineAdvice &amp;Advice, bool CalleeWasDeleted)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af51ba1b089b59418d39aa40424b996dd">isForcedToStop</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdcccbb9d3934f1685accebaf51f5aef">getLocalCalls</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65f0a9492034c08d15be5b62481d0970">getModelRunner</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b7f1071fac3720a2f1d4bd7da91625d">getCachedFPI</a> (Function &amp;) const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb44b65867ce48eee9d2d49cbdc60333">getAdviceImpl</a> (CallBase &amp;CB) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adca0f8d16629001e04b5f4d1cbae214b">getMandatoryAdvice</a> (CallBase &amp;CB, bool Advice) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice">MLInlineAdvice</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa64517193ce5ce41b3a4902fcece379e">getMandatoryAdviceImpl</a> (CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice">MLInlineAdvice</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29d86e8f62a35997fcc2f48d72653b2">getAdviceFromModel</a> (CallBase &amp;CB, OptimizationRemarkEmitter &amp;ORE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af89cb65bd8bca0c28b1a0b7cd0bcff89">getInitialFunctionLevel</a> (const Function &amp;F) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae462501929f31059d41a3845e466688f">getModuleIRSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a31cf5f26ffd8c0b90ff28431269c8">getSkipAdviceIfUnreachableCallsite</a> (CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9384dc67a2a8f93ff53f54f3cb29fa7f">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support for printer pass. <a href="#a9384dc67a2a8f93ff53f54f3cb29fa7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33dfb3ef81bda64ebcbc766046c701c6">ModelRunner</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8c9b5a4b4d8a2504741ea95eb2f6ccc">GetDefaultAdvice</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa67734b9be37e64a3dea330328a32c56">FPICache</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8e72c5c26f66144d5e9f0db8d960b2">CG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa33e16cc8cf26e084da62214ce92de88">NodeCount</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad039e456e8d4ad7dc1f5231f8562cb95">EdgeCount</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018b53da1c6bdead2eb3426219ef8f84">EdgesOfLastSeenNodes</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">LazyCallGraph::Node</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f535ff280d0a6f2d554fb9ad6c4fde">FunctionLevels</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e40613f463e728c7527eeda6c7d1f0e">InitialIRSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa61c30f7a33bfd714817795781645d8d">CurrentIRSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">llvm::SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">LazyCallGraph::Node</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf2d228d9f0f668954ed19a23fc31c34">NodesInLastSCC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">LazyCallGraph::Node</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec4a89589717ba8cb68df61684922486">AllNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ce3b8f569bf6a03978a78ac2d3a0c48">DeadFunctions</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a686f6cb4a614c4168d37d19218204b12">ForceStop</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af33cab307e561db0b73ebbadad858082">PSI</a></td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MLInlineAdvisor() {#a721f6a9227830f0254a70a740f43f24f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MLInlineAdvisor::MLInlineAdvisor (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a> &gt; ModelRunner, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp;)&gt; GetDefaultAdvice)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ad8c9b5a4b4d8a2504741ea95eb2f6ccc">GetDefaultAdvice</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp/#a5f3d88e0af08023b408b444789632423">getInlinableCS</a>, <a href="#abdcccbb9d3934f1685accebaf51f5aef">getLocalCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#aec021d6b460b139f3c1d570a0f2dd4b6">llvm::InlineAdvisor::InlineAdvisor</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#ab63e90899ab78f60bf47256071c0a48b">llvm::InlineAdvisor::M</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>, <a href="#a33dfb3ef81bda64ebcbc766046c701c6">ModelRunner</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3c1a67796e24a843db8a6766baa54c21">llvm::scc_begin</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MLInlineAdvisor() {#ae13a64e601a0aa04050c096a1ac684ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::MLInlineAdvisor::~MLInlineAdvisor ()</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCachedFPI() {#a3b7f1071fac3720a2f1d4bd7da91625d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPropertiesInfo &amp; MLInlineAdvisor::getCachedFPI (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a1b1b99bc0fe39cbe400f49bbd65f01c3">llvm::InlineAdvisor::FAM</a>.</p>


<p>Referenced by <a href="#adb44b65867ce48eee9d2d49cbdc60333">getAdviceImpl</a>, <a href="#ad64807412969a3708f691675898a58c0">getIRSize</a>, <a href="#abdcccbb9d3934f1685accebaf51f5aef">getLocalCalls</a> and <a href="#a8116ffdfb54f7d195eb185c8bf7c060c">onSuccessfulInlining</a>.</p>

</div>
</div>

### getIRSize() {#ad64807412969a3708f691675898a58c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MLInlineAdvisor::getIRSize (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a3b7f1071fac3720a2f1d4bd7da91625d">getCachedFPI</a> and <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo/#ae0ec2659390ab61b126f336e2727d0c7">llvm::FunctionPropertiesInfo::TotalInstructionCount</a>.</p>


<p>Referenced by <a href="#a8116ffdfb54f7d195eb185c8bf7c060c">onSuccessfulInlining</a>.</p>

</div>
</div>

### getLocalCalls() {#abdcccbb9d3934f1685accebaf51f5aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t MLInlineAdvisor::getLocalCalls (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo/#afa568a5b2ab440f02bbc9eef3863a619">llvm::FunctionPropertiesInfo::DirectCallsToDefinedFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a3b7f1071fac3720a2f1d4bd7da91625d">getCachedFPI</a>.</p>


<p>Referenced by <a href="#a721f6a9227830f0254a70a740f43f24f">MLInlineAdvisor</a>, <a href="#aaaec1d89794dccf1f6d02c0e46258796">onPassEntry</a> and <a href="#a42079a872d9a000c124cef0d38723741">onPassExit</a>.</p>

</div>
</div>

### getModelRunner() {#a65f0a9492034c08d15be5b62481d0970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MLModelRunner &amp; llvm::MLInlineAdvisor::getModelRunner ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>


<p>Reference <a href="#a33dfb3ef81bda64ebcbc766046c701c6">ModelRunner</a>.</p>

</div>
</div>

### isForcedToStop() {#af51ba1b089b59418d39aa40424b996dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MLInlineAdvisor::isForcedToStop ()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### onPassEntry() {#aaaec1d89794dccf1f6d02c0e46258796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MLInlineAdvisor::onPassEntry (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> * SCC)</td>
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

<p>This must be called when the Inliner pass is entered, to allow the <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> update internal state, as result of function passes run between Inliner pass runs (for the same module).</p>

<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abdcccbb9d3934f1685accebaf51f5aef">getLocalCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### onPassExit() {#a42079a872d9a000c124cef0d38723741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MLInlineAdvisor::onPassExit (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> * SCC)</td>
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

<p>This must be called when the Inliner pass is exited, as function passes may be run subsequently.</p>


<p>This allows an implementation of <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> to prepare for a partial update, based on the optional SCC.</p>


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abdcccbb9d3934f1685accebaf51f5aef">getLocalCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp/#a2a33484582662d461a05c44318837ae9">KeepFPICache</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### onSuccessfulInlining() {#a8116ffdfb54f7d195eb185c8bf7c060c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MLInlineAdvisor::onSuccessfulInlining (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice">MLInlineAdvice</a> &amp; Advice, bool CalleeWasDeleted)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a6330d9efb13139a5058e3ee2d240c81d">llvm::MLInlineAdvice::CalleeIRSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#ac2fa94d7c9401db9a42cee3a9e7a4416">llvm::MLInlineAdvice::CallerAndCalleeEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a367c676bd322e75aad02114a0763d955">llvm::MLInlineAdvice::CallerIRSize</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo/#afa568a5b2ab440f02bbc9eef3863a619">llvm::FunctionPropertiesInfo::DirectCallsToDefinedFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a1b1b99bc0fe39cbe400f49bbd65f01c3">llvm::InlineAdvisor::FAM</a>, <a href="#a3b7f1071fac3720a2f1d4bd7da91625d">getCachedFPI</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#ada4b28b495ff3ca02d3373edf2b5bac6">llvm::MLInlineAdvice::getCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#ab7a31fef6e390f4ddf21f9f63a94f70f">llvm::MLInlineAdvice::getCaller</a>, <a href="#ad64807412969a3708f691675898a58c0">getIRSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp/#abd4d4cdc8da5c0940a6a02c33f44d44a">SizeIncreaseThreshold</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a19a31f34d91bfcdfa8c16f9a16079461">llvm::MLInlineAdvice::updateCachedCallerFPI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getAdviceFromModel() {#ad29d86e8f62a35997fcc2f48d72653b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MLInlineAdvice &gt; MLInlineAdvisor::getAdviceFromModel (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>Reference <a href="#a33dfb3ef81bda64ebcbc766046c701c6">ModelRunner</a>.</p>


<p>Referenced by <a href="#adb44b65867ce48eee9d2d49cbdc60333">getAdviceImpl</a>.</p>

</div>
</div>

### getAdviceImpl() {#adb44b65867ce48eee9d2d49cbdc60333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; InlineAdvice &gt; MLInlineAdvisor::getAdviceImpl (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a6659e9fe3450059147033d140cd8496ea68eec46437c384d8dad18d5464ebc35c">llvm::InlineAdvisor::Always</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4fb513d744ca72275932b2c7003f16f6">llvm::CallBase::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a1b1b99bc0fe39cbe400f49bbd65f01c3">llvm::InlineAdvisor::FAM</a>, <a href="#ad29d86e8f62a35997fcc2f48d72653b2">getAdviceFromModel</a>, <a href="#a3b7f1071fac3720a2f1d4bd7da91625d">getCachedFPI</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#afac5b39bcbb90d660f83d9b4bd8c6d95">llvm::CallBase::getCaller</a>, <a href="#ad8c9b5a4b4d8a2504741ea95eb2f6ccc">GetDefaultAdvice</a>, <a href="#af89cb65bd8bca0c28b1a0b7cd0bcff89">getInitialFunctionLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9362dadd20c02f3227f93421cb8829d">llvm::getInliningCostEstimate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bc682ff4e05f8bbb181be693c717dd8">llvm::getInliningCostFeatures</a>, <a href="#adca0f8d16629001e04b5f4d1cbae214b">getMandatoryAdvice</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a2610d24c389789284bb8c8b616ab5e43">llvm::InlineAdvisor::getMandatoryKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp/#a85aafdc928303332b0b6c7b3beb05a69aa2365bf0e0ab37bb03e34f2dafa7015a">IfCallerIsNotCold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a087651f2fd9aa01317b1380f4fb896a2">llvm::inlineCostFeatureToMlFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp/#a9e1d79b99b2115a50ef0d8ce2f31c990">InteractiveChannelBaseName</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp/#ae87d902750143c5a86d089a3b3ab451e">InteractiveIncludeDefault</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a33dfb3ef81bda64ebcbc766046c701c6">ModelRunner</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a6659e9fe3450059147033d140cd8496ea6e7b34fa59e1bd229b207892956dc41c">llvm::InlineAdvisor::Never</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ef78f96e07a124af3b346d8df9010cca67f61322a0f693e8ff8200717ec6adde">llvm::NumberOfFeatures</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp/#ae7774b8d57d957bad377faa2f46cdc49">SkipPolicy</a>.</p>

</div>
</div>

### getInitialFunctionLevel() {#af89cb65bd8bca0c28b1a0b7cd0bcff89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MLInlineAdvisor::getInitialFunctionLevel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#adb44b65867ce48eee9d2d49cbdc60333">getAdviceImpl</a>.</p>

</div>
</div>

### getMandatoryAdvice() {#adca0f8d16629001e04b5f4d1cbae214b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; InlineAdvice &gt; MLInlineAdvisor::getMandatoryAdvice (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, bool Advice)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a14528ae0117f755bc5a74a7683c0722d">llvm::InlineAdvisor::getCallerORE</a> and <a href="#aa64517193ce5ce41b3a4902fcece379e">getMandatoryAdviceImpl</a>.</p>


<p>Referenced by <a href="#adb44b65867ce48eee9d2d49cbdc60333">getAdviceImpl</a>.</p>

</div>
</div>

### getMandatoryAdviceImpl() {#aa64517193ce5ce41b3a4902fcece379e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MLInlineAdvice &gt; MLInlineAdvisor::getMandatoryAdviceImpl (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a14528ae0117f755bc5a74a7683c0722d">llvm::InlineAdvisor::getCallerORE</a>.</p>


<p>Referenced by <a href="#adca0f8d16629001e04b5f4d1cbae214b">getMandatoryAdvice</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getModuleIRSize() {#ae462501929f31059d41a3845e466688f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t MLInlineAdvisor::getModuleIRSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>

</div>
</div>

### getSkipAdviceIfUnreachableCallsite() {#a63a31cf5f26ffd8c0b90ff28431269c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; InlineAdvice &gt; MLInlineAdvisor::getSkipAdviceIfUnreachableCallsite (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>

</div>
</div>

### print() {#a9384dc67a2a8f93ff53f54f3cb29fa7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MLInlineAdvisor::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Support for printer pass.</p>

<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### GetDefaultAdvice {#ad8c9b5a4b4d8a2504741ea95eb2f6ccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;bool(CallBase &amp;)&gt; llvm::MLInlineAdvisor::GetDefaultAdvice</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#adb44b65867ce48eee9d2d49cbdc60333">getAdviceImpl</a> and <a href="#a721f6a9227830f0254a70a740f43f24f">MLInlineAdvisor</a>.</p>

</div>
</div>

### ModelRunner {#a33dfb3ef81bda64ebcbc766046c701c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MLModelRunner&gt; llvm::MLInlineAdvisor::ModelRunner</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#ad29d86e8f62a35997fcc2f48d72653b2">getAdviceFromModel</a>, <a href="#adb44b65867ce48eee9d2d49cbdc60333">getAdviceImpl</a>, <a href="#a65f0a9492034c08d15be5b62481d0970">getModelRunner</a> and <a href="#a721f6a9227830f0254a70a740f43f24f">MLInlineAdvisor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllNodes {#aec4a89589717ba8cb68df61684922486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;const LazyCallGraph::Node *&gt; llvm::MLInlineAdvisor::AllNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### CG {#abf8e72c5c26f66144d5e9f0db8d960b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph&amp; llvm::MLInlineAdvisor::CG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### CurrentIRSize {#aa61c30f7a33bfd714817795781645d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::MLInlineAdvisor::CurrentIRSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### DeadFunctions {#a6ce3b8f569bf6a03978a78ac2d3a0c48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;Function *&gt; llvm::MLInlineAdvisor::DeadFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### EdgeCount {#ad039e456e8d4ad7dc1f5231f8562cb95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MLInlineAdvisor::EdgeCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### EdgesOfLastSeenNodes {#a018b53da1c6bdead2eb3426219ef8f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MLInlineAdvisor::EdgesOfLastSeenNodes = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### ForceStop {#a686f6cb4a614c4168d37d19218204b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MLInlineAdvisor::ForceStop = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### FPICache {#aa67734b9be37e64a3dea330328a32c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;const Function *, FunctionPropertiesInfo&gt; llvm::MLInlineAdvisor::FPICache</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### FunctionLevels {#a94f535ff280d0a6f2d554fb9ad6c4fde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;const LazyCallGraph::Node *, unsigned&gt; llvm::MLInlineAdvisor::FunctionLevels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### InitialIRSize {#a4e40613f463e728c7527eeda6c7d1f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int32_t llvm::MLInlineAdvisor::InitialIRSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### NodeCount {#aa33e16cc8cf26e084da62214ce92de88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MLInlineAdvisor::NodeCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### NodesInLastSCC {#adf2d228d9f0f668954ed19a23fc31c34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallPtrSet&lt;const LazyCallGraph::Node *, 1&gt; llvm::MLInlineAdvisor::NodesInLastSCC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### PSI {#af33cab307e561db0b73ebbadad858082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo&amp; llvm::MLInlineAdvisor::PSI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
