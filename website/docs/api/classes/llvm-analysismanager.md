---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/analysismanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AnalysisManager` Class Template

<p>A container for analyses that lazily runs them and caches their results. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IRUnitT, typename... ExtraArgTs&gt;
class llvm::AnalysisManager&lt;IRUnitT, ExtraArgTs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa227a706b01df3e897821abd38cdf405">ResultConceptT</a> = <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultconcept">detail::AnalysisResultConcept</a>&lt; IRUnitT, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/invalidator">Invalidator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3edb3b59ea216c36548151c2b1a14766">PassConceptT</a> = <a href="/web-llvm/docs/api/structs/llvm/detail/analysispassconcept">detail::AnalysisPassConcept</a>&lt; IRUnitT, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/invalidator">Invalidator</a>, ExtraArgTs... &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6f9398a4226b26a5a676287641878a9">AnalysisResultListT</a> = std::list&lt; std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultconcept">ResultConceptT</a> &gt; &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of analysis pass IDs and associated concept pointers. <a href="#ab6f9398a4226b26a5a676287641878a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a442b62f548be7c59c652cf403fbef3b4">AnalysisResultListMapT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; IRUnitT *, AnalysisResultListT &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map type from IRUnitT pointer to our custom list type. <a href="#a442b62f548be7c59c652cf403fbef3b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeebed2f97445627bc499c393c8e80882">AnalysisResultMapT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> *, IRUnitT * &gt;, typename AnalysisResultListT::iterator &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map type from a pair of analysis <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and IRUnitT pointer to an iterator into a particular result list (which is where the actual analysis result is stored). <a href="#aeebed2f97445627bc499c393c8e80882">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a134f995a67e3c8da28760abb1bc55ea5">AnalysisPassMapT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/detail/analysispassconcept">PassConceptT</a> &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map type from analysis pass <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to pass concept pointer. <a href="#a134f995a67e3c8da28760abb1bc55ea5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a04d20e532396b71cf376c777d6b838c9">AnalysisManager</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an empty analysis manager. <a href="#a04d20e532396b71cf376c777d6b838c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a22f4fe9d72c2287370e28fbbeabbd89f">AnalysisManager</a> (AnalysisManager &amp;&amp;)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2bc6bb441a5b546bf76b838ff9b5e473">operator=</a> (AnalysisManager &amp;&amp;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a92d8409cca05ebc97ee7d3180b2c00e3">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the analysis manager has an empty results cache. <a href="#a92d8409cca05ebc97ee7d3180b2c00e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4926331431f03253ee3ec8e6e3bb9d1c">clear</a> (IRUnitT &amp;IR, llvm::StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear any cached analysis results for a single unit of IR. <a href="#a4926331431f03253ee3ec8e6e3bb9d1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1def78d3ab800e1f9b15ac7f772862ff">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear all analysis results cached by this <a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a>. <a href="#a1def78d3ab800e1f9b15ac7f772862ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a03f50a72945de4b779ffd17b508974c8">isPassRegistered</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified analysis pass is registered. <a href="#a03f50a72945de4b779ffd17b508974c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">PassT::Result &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaab1fad63e4f3b8679469720a873fedd">getResult</a> (IRUnitT &amp;IR, ExtraArgTs... ExtraArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the result of an analysis pass for a given IR unit. <a href="#aaab1fad63e4f3b8679469720a873fedd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">PassT::Result *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a828ff8185f881fca9e3d534781244041">getCachedResult</a> (IRUnitT &amp;IR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the cached result of an analysis pass for a given IR unit. <a href="#a828ff8185f881fca9e3d534781244041">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a29648f060d2dd1e126ed17733813cf0a">verifyNotInvalidated</a> (IRUnitT &amp;IR, typename PassT::Result *Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that the given Result cannot be invalidated, assert otherwise. <a href="#a29648f060d2dd1e126ed17733813cf0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassBuilderT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a91ff894f756175a693c85bf73f79de9e">registerPass</a> (PassBuilderT &amp;&amp;PassBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an analysis pass with the manager. <a href="#a91ff894f756175a693c85bf73f79de9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a64b2a209a16bcd41375b5cae12690eaa">invalidate</a> (IRUnitT &amp;IR, const PreservedAnalyses &amp;PA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidate cached analyses for an IR unit. <a href="#a64b2a209a16bcd41375b5cae12690eaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/analysispassconcept">PassConceptT</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a896a2d0697604f08f99fe7b019ad3bfd">lookUpPass</a> (AnalysisKey *ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up a registered analysis pass. <a href="#a896a2d0697604f08f99fe7b019ad3bfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/detail/analysispassconcept">PassConceptT</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b69a92067fc1113f29d9d4ca1d6c3ff">lookUpPass</a> (AnalysisKey *ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up a registered analysis pass. <a href="#a7b69a92067fc1113f29d9d4ca1d6c3ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultconcept">ResultConceptT</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c21e9b71e06095567ef2d8749ec18b6">getResultImpl</a> (AnalysisKey *ID, IRUnitT &amp;IR, ExtraArgTs... ExtraArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an analysis result, running the pass if necessary. <a href="#a7c21e9b71e06095567ef2d8749ec18b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultconcept">ResultConceptT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad87204b3132c8461e2b6f0e3629da6a5">getCachedResultImpl</a> (AnalysisKey *ID, IRUnitT &amp;IR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a cached analysis result or return null. <a href="#ad87204b3132c8461e2b6f0e3629da6a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">AnalysisPassMapT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6165fb98ddb81478865918c3e1b2b7d7">AnalysisPasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of analysis passes, indexed by <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a6165fb98ddb81478865918c3e1b2b7d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">AnalysisResultListMapT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af18e57efae06e5053d32594df0afbbcc">AnalysisResultLists</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from IR unit to a list of analysis results. <a href="#af18e57efae06e5053d32594df0afbbcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">AnalysisResultMapT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6aa580ea41f8ad85f2dee2a40fb578d">AnalysisResults</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from an analysis <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and IR unit to a particular cached analysis result. <a href="#af6aa580ea41f8ad85f2dee2a40fb578d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A container for analyses that lazily runs them and caches their results.</p>


<p>This class can manage analyses for any IR unit where the address of the IR unit sufficies as its identity.</p>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AnalysisPassMapT {#a134f995a67e3c8da28760abb1bc55ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::AnalysisPassMapT = 
      DenseMap&lt;AnalysisKey *, std::unique_ptr&lt;PassConceptT&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map type from analysis pass <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to pass concept pointer.</p>

<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### AnalysisResultListMapT {#a442b62f548be7c59c652cf403fbef3b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::AnalysisResultListMapT =  DenseMap&lt;IRUnitT *, AnalysisResultListT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map type from IRUnitT pointer to our custom list type.</p>

<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### AnalysisResultListT {#ab6f9398a4226b26a5a676287641878a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::AnalysisResultListT = 
      std::list&lt;std::pair&lt;AnalysisKey *, std::unique_ptr&lt;ResultConceptT&gt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of analysis pass IDs and associated concept pointers.</p>


<p>Requires iterators to be valid across appending new entries and arbitrary erases. Provides the analysis <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to enable finding iterators to a given entry in maps below, and provides the storage for the actual result concept.</p>


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### AnalysisResultMapT {#aeebed2f97445627bc499c393c8e80882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::AnalysisResultMapT = 
      DenseMap&lt;std::pair&lt;AnalysisKey *, IRUnitT *&gt;,
               typename AnalysisResultListT::iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map type from a pair of analysis <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and IRUnitT pointer to an iterator into a particular result list (which is where the actual analysis result is stored).</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### PassConceptT {#a3edb3b59ea216c36548151c2b1a14766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::PassConceptT = 
      detail::AnalysisPassConcept&lt;IRUnitT, Invalidator, ExtraArgTs...&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### ResultConceptT {#aa227a706b01df3e897821abd38cdf405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::ResultConceptT =  detail::AnalysisResultConcept&lt;IRUnitT, Invalidator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AnalysisManager() {#a04d20e532396b71cf376c777d6b838c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::AnalysisManager ()</td>
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

<p>Construct an empty analysis manager.</p>

<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### AnalysisManager() {#a22f4fe9d72c2287370e28fbbeabbd89f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::AnalysisManager (<a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a> &amp;&amp;)</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a2bc6bb441a5b546bf76b838ff9b5e473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisManager&lt; IRUnitT, ExtraArgTs... &gt; &amp; llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a> &amp;&amp;)</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a4926331431f03253ee3ec8e6e3bb9d1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::clear (IRUnitT &amp; IR, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name)</td>
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

<p>Clear any cached analysis results for a single unit of IR.</p>


<p>This doesn't invalidate, but instead simply deletes, the relevant results. It is useful when the IR is being removed and we want to clear out all the memory pinned for it.</p>


<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerimpl-h">PassManagerImpl.h</a>.</p>


<p>References <a href="#a828ff8185f881fca9e3d534781244041">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getCachedResult</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### clear() {#a1def78d3ab800e1f9b15ac7f772862ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::clear ()</td>
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

<p>Clear all analysis results cached by this <a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a>.</p>


<p>Like <span class="doxyComputerOutput">clear(IRUnitT&amp;)</span>, this doesn't invalidate the results; it simply deletes them. This lets you clean up the <a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a> when the set of IR units itself has potentially changed, and thus we can't even look up a a result and invalidate/clear it directly.</p>


<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### empty() {#a92d8409cca05ebc97ee7d3180b2c00e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::empty ()</td>
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

<p>Returns true if the analysis manager has an empty results cache.</p>

<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### getCachedResult() {#a828ff8185f881fca9e3d534781244041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassT::Result * llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getCachedResult (IRUnitT &amp; IR)</td>
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

<p>Get the cached result of an analysis pass for a given IR unit.</p>


<p>This method never runs the analysis.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>null if there is no cached result.</p></dd>
</dl>


<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<p>Referenced by <a href="#a4926331431f03253ee3ec8e6e3bb9d1c">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#aa64f6bcd5ace031369edc14aa406d745">incorporateNewSCCRange</a>, <a href="#a64b2a209a16bcd41375b5cae12690eaa">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::invalidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenprepare/#aa963097f89a02195cba904f74c5e0f71">anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::run</a>, <a href="/web-llvm/docs/api/structs/llvm/assumebuilderpass/#aca0fa8f3093912d8045361e2f6b79cac">llvm::AssumeBuilderPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/assumesimplifypass/#a378f8b2a8e11ac78939bd1c732f05d2e">llvm::AssumeSimplifyPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/breakcriticaledgespass/#a5f8ef6ce9ef2eb4568d48e3530b5652d">llvm::BreakCriticalEdgesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/extrafunctionpassmanager/#ae66709ae0e3be48ab315ad2ac6ae6fa7">llvm::ExtraFunctionPassManager&lt; MarkerTy &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/extralooppassmanager/#abc9e4c26ae75979993c43cbd6392104c">llvm::ExtraLoopPassManager&lt; MarkerTy &gt;::run</a>, <a href="/web-llvm/docs/api/structs/llvm/fixirreduciblepass/#a61707c67652fa7e327bb8ac607164e09">llvm::FixIrreduciblePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a13571b5fc50d701864f8b3de9b930b7f">llvm::GuardWideningPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnpass/#a25dcf17194b012b2b35388798cac2da7">llvm::GVNPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inferaddressspacespass/#a8750fe658baa71eeba987c3bea8bf83e">llvm::InferAddressSpacesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinepass/#aa1ffc7ad08181545bbc25eabac7f5aae">llvm::InstCombinePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/jumptabletoswitchpass/#a84778fc53894f05e88ce0cc794561742">llvm::JumpTableToSwitchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lcssapass/#a7ae4df8ff3ca478772f6f055bf88bd1f">llvm::LCSSAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsimplifypass/#a294bd885b054adcb86315a9112ea0b33">llvm::LoopSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass/#a62ed17cf8aa893362e6c3c1f6d8a0898">llvm::LoopUnrollPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerswitchpass/#a7ed296f67da3966a7e2c0dd6f4fbcf9e">llvm::LowerSwitchPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/mergeicmpspass/#a96cfc6defc256b49f69f6fb8bfbf8c87">llvm::MergeICmpsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/partiallyinlinelibcallspass/#a0e2ff100989ce66c294cfe38904c6cf1">llvm::PartiallyInlineLibCallsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>, <a href="/web-llvm/docs/api/structs/llvm/recomputeglobalsaapass/#abd209c0e2c06b211cbd147ad96b70890">llvm::RecomputeGlobalsAAPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/scalarizemaskedmemintrinpass/#ab805176ab5d08e2a34fadbc760bca5a6">llvm::ScalarizeMaskedMemIntrinPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sccppass/#ad9201f5b1be7f1b9cbff7b2b631b2256">llvm::SCCPPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/silowercontrolflowpass/#a8b4643be70785c8f090659b3ab19d73e">llvm::SILowerControlFlowPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/silowersgprspillspass/#acc251fdad2ff98bf8f116ecbd8e93b14">llvm::SILowerSGPRSpillsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/silowerwwmcopiespass/#a8190b1c16b87f7d2ff20607bc4efb554">llvm::SILowerWWMCopiesPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/slpvectorizerpass/#aaec443311cb572adf0e2db9db82279ef">llvm::SLPVectorizerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/tailcallelimpass/#ab754a2815f5333ff5f443593896814dc">llvm::TailCallElimPass::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a>.</p>

</div>
</div>

### getResult() {#aaab1fad63e4f3b8679469720a873fedd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassT::Result &amp; llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult (IRUnitT &amp; IR, ExtraArgTs... ExtraArgs)</td>
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

<p>Get the result of an analysis pass for a given IR unit.</p>


<p>Runs the analysis if a cached result is not available.</p>


<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a12c711c62171c14dcedca2db5874d33e">llvm::SelectionDAGISel::initializeAnalysisResults</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a41245c88cdf19ddbfe8a2dffba0a500d">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::LowerTypeTestsModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenprepare/#aa963097f89a02195cba904f74c5e0f71">anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::run</a>, <a href="/web-llvm/docs/api/classes/llvm/aaevaluator/#a9ed5f1670101ec861ebdd6c74540f4da">llvm::AAEvaluator::run</a>, <a href="/web-llvm/docs/api/classes/llvm/aamanager/#aeaceed25b77fd7235079349031e41839">llvm::AAManager::run</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveinstcombinepass/#a1d380b75a626cf6035ca021b9033e8f4">llvm::AggressiveInstCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/aliassetsprinterpass/#a3a8a27458f2832e65ace0c61bb035be7">llvm::AliasSetsPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a850fc86971c292f64bfad4d9076bfea8">llvm::AlignmentFromAssumptionsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuatomicoptimizerpass/#a61ccbe84ff2f490892da47cd8af3d621">llvm::AMDGPUAtomicOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuattributorpass/#a6b853868668b480de1fb9a5638185bbf">llvm::AMDGPUAttributorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuiseldagtodagpass/#a50f97f48ab6353d9bb2bc36ce592c7e4">llvm::AMDGPUISelDAGToDAGPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuperfhintanalysispass/#abd3d261eb47ebf4c6d8fe9b40a90e726">llvm::AMDGPUPerfHintAnalysisPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpupromoteallocatovectorpass/#a4d58a8f51935070c2ec517b3becde405">llvm::AMDGPUPromoteAllocaToVectorPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpupromotekernelargumentspass/#a09b7bed11d55d255fef525817e8d1a6b">llvm::AMDGPUPromoteKernelArgumentsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpurewriteundefforphipass/#a389937d71bd8740fe3be1c396949e0bb">llvm::AMDGPURewriteUndefForPHIPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuswlowerldspass/#a60fde742e4c1eaef19a09e78c111cd6a">llvm::AMDGPUSwLowerLDSPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuunifydivergentexitnodespass/#a3e73b9a5c7212271285ef6c38d1cd26d">llvm::AMDGPUUnifyDivergentExitNodesPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/annotationremarkspass/#a1dd7b1feb9652fcb6ea5e6741029b063">llvm::AnnotationRemarksPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentpromotionpass/#afe0f49f9daec2532b14ded30ed46ff28">llvm::ArgumentPromotionPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/assumebuilderpass/#aca0fa8f3093912d8045361e2f6b79cac">llvm::AssumeBuilderPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/assumesimplifypass/#a378f8b2a8e11ac78939bd1c732f05d2e">llvm::AssumeSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptionprinterpass/#a140e7194c82dc0eda75b3602736a0b83">llvm::AssumptionPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorcgsccpass/#a305cbdd90350f05f5ee772811d596ded">llvm::AttributorCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightcgsccpass/#a1725467ef5883a44e7777d681c6a4d32">llvm::AttributorLightCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightpass/#af4dc3e41c843da6385d1252386d4c03e">llvm::AttributorLightPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorpass/#aba65d47dce0a15a90eb4e519ffc4929c">llvm::AttributorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaa/#ab69d4d2a49531dbe7734c261a0578604">llvm::BasicAA::run</a>, <a href="/web-llvm/docs/api/structs/llvm/bdcepass/#afbbfc5e8696e402cd67ebdc99da7c47a">llvm::BDCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodewriterpass/#a2cf5fec0ba55756093b6c7e6c8f31c00">llvm::BitcodeWriterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyanalysis/#ae5af9e07de7320c60fc8c89057e69354">llvm::BlockFrequencyAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyprinterpass/#a5a6cbafd8221cce28bfb4fe7aca32f94">llvm::BlockFrequencyPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/boundscheckingpass/#aaeef3ef960131b08e172917320b9507d">llvm::BoundsCheckingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityanalysis/#a16f8c5851cffc6f908a232089fc71de6">llvm::BranchProbabilityAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityprinterpass/#af8bbfa323a4917223612dff12067110b">llvm::BranchProbabilityPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphdotprinterpass/#a7d72837594bc13f77f2d84bcfd0752de">llvm::CallGraphDOTPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphprinterpass/#a3bb83e1831d2ffb599b81c6bd047a7b9">llvm::CallGraphPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphsccsprinterpass/#adab3cbb8d806b7d4d2138bd93e92c99a">llvm::CallGraphSCCsPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphviewerpass/#aaea10b30adce800d7d54b5394a49567b">llvm::CallGraphViewerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/callsitesplittingpass/#a758aec9b799aa0d0559635cfc6144f36">llvm::CallSiteSplittingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgonlyprinterpass/#af4633166ee31522ede36144c2cadde39">llvm::CFGOnlyPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgonlyviewerpass/#a2c9830e7108892805b14bca50f644d0c">llvm::CFGOnlyViewerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgprinterpass/#a4d6be8adf1d7c561f9a47831f910fd91">llvm::CFGPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgviewerpass/#a4ec76f0493f0ee9679e2a15343680ccf">llvm::CFGViewerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/constanthoistingpass/#abe3f0e309e575379e5bae02d1907f394">llvm::ConstantHoistingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainteliminationpass/#a42aea849d980d7bce1c0ef31ac326e87">llvm::ConstraintEliminationPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroannotationelidepass/#a411202dc502ac666302ba81c40e94b10">llvm::CoroAnnotationElidePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroelidepass/#a6dfdc223099c4ca952c8b0369027e34d">llvm::CoroElidePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/correlatedvaluepropagationpass/#a1672fc6d49348158aa95dbb4ae80224c">llvm::CorrelatedValuePropagationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/costmodelprinterpass/#a6685ffe146df7448fc95cd7fcec89e55">llvm::CostModelPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cycleinfoprinterpass/#a5fe94fefc760afe4f7b178e72299aa39">llvm::CycleInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/cycleinfoverifierpass/#af9fcac728641055cca5bdb95469dc5e4">llvm::CycleInfoVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dataflowsanitizerpass/#a763709e61e42f6df707528b509adf8de">llvm::DataFlowSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dcepass/#ae0adbbdfa4d74b93465ac5dd85124af4">llvm::DCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ddganalysisprinterpass/#aa18a597cd04af57bb4061499d5d5640c">llvm::DDGAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgdotprinterpass/#ad73a209beeea1475814429bdd8bdeda5">llvm::DDGDotPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/delinearizationprinterpass/#af564d4ce1f4c1029592d1a923b0d2c43">llvm::DelinearizationPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/demandedbitsanalysis/#a6004ad957fdd5fcccada1f2e8508265b">llvm::DemandedBitsAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/demandedbitsprinterpass/#a3f85a7e646826596cd811e66f0df417f">llvm::DemandedBitsPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/dfajumpthreadingpass/#a1e2cfc4a731613030f8f416677999fa0">llvm::DFAJumpThreadingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dominancefrontieranalysis/#a4216ac958d2e020933cafd0f0b43b712">llvm::DominanceFrontierAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierprinterpass/#aae343d5e2c1b700a31142af232a990cf">llvm::DominanceFrontierPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreeprinterpass/#a4e7ca1ff82e0d63a88d574a545380fea">llvm::DominatorTreePrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/dominatortreeverifierpass/#a680c63d627c9e32ca9f2ba34e52c6543">llvm::DominatorTreeVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dsepass/#a29b9f8c28e2ba0531f66bd82e8c5a32e">llvm::DSEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/shaderflagsanalysis/#aac5850fcb98ccf20d9a084c65b224df9">llvm::dxil::ShaderFlagsAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/shaderflagsanalysisprinter/#a0784c57dc0671927404b56c94ec983c8">llvm::dxil::ShaderFlagsAnalysisPrinter::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilmetadataanalysisprinterpass/#a853a7e2cfb272918dbcf0f260f091598">llvm::DXILMetadataAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcebindinganalysis/#a25a190212c3eb0ea291ac64cfff1f665">llvm::DXILResourceBindingAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcebindingprinterpass/#a9c5f08a05826fa28ba48d255e06f1b97">llvm::DXILResourceBindingPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/earlycsepass/#a1977dd7d302009cd95b32ad3a5dd8db6">llvm::EarlyCSEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/earlyifconverterpass/#a9f45d5f14e7be68f178eadf56bd84d25">llvm::EarlyIfConverterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandreductionspass/#a9fea76fcf757718eb4aafcd72cb89038">llvm::ExpandReductionsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/fixirreduciblepass/#a61707c67652fa7e327bb8ac607164e09">llvm::FixIrreduciblePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/flattencfgpass/#ac48dd5c80bc3b98f2e2f5aa65117456f">llvm::FlattenCFGPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/float2intpass/#ad9900fbd867b1e73f7da240f0e7a28c1">llvm::Float2IntPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionanalysismanagercgsccproxy/#a0b67cd81e4ea0371cae072a28008e469">llvm::FunctionAnalysisManagerCGSCCProxy::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesprinterpass/#aac1f30e6e61c72eaa61dc3daf83dc588">llvm::FunctionPropertiesPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovprofilerpass/#abe3a54029a1d4094373deb485452f033">llvm::GCOVProfilerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globaloptpass/#a0be1afba37502be6858f2a1c38955be8">llvm::GlobalOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globalsaa/#a13e2d1113ed664d73521d89676ba6e9d">llvm::GlobalsAA::run</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a13571b5fc50d701864f8b3de9b930b7f">llvm::GuardWideningPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/gvnhoistpass/#a73462db6e4114fd6c543b9b3de65a504">llvm::GVNHoistPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnpass/#a25dcf17194b012b2b35388798cac2da7">llvm::GVNPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hardwareloopspass/#a7b139351e6b64d570e4ee5b7ece478ea">llvm::HardwareLoopsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hotcoldsplittingpass/#a1428bc0c1945db2bcb0bc0b17447c18c">llvm::HotColdSplittingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/indvarsimplifypass/#a00bd6521a4f23d764d5d1403e7728e8f">llvm::IndVarSimplifyPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inferaddressspacespass/#a8750fe658baa71eeba987c3bea8bf83e">llvm::InferAddressSpacesPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inferalignmentpass/#ad5a046232f4066339175c677ff26b9f5">llvm::InferAlignmentPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inferfunctionattrspass/#a43509c520610b43c4b366bee12dc1f4b">llvm::InferFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/injecttlimappings/#a132043059b6f75e1cdca29b58c58d872">llvm::InjectTLIMappings::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisoranalysisprinterpass/#af0f697cf524e464ace6a8652e4dbb128">llvm::InlineAdvisorAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinesizeestimatoranalysisprinterpass/#a5e90152cff8dae138bbd12056eeb56ca">llvm::InlineSizeEstimatorAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinepass/#aa1ffc7ad08181545bbc25eabac7f5aae">llvm::InstCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofilingloweringpass/#a610148cfab0328ada1642b17b9a9e71c">llvm::InstrProfilingLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instsimplifypass/#ad073cb9259c01c880086405f8776a106">llvm::InstSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ipsccppass/#a7c77a408787021dc65c12646cee2ac43">llvm::IPSCCPPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ircepass/#ac7e45d3f509c7e40c4d6666a24e88f73">llvm::IRCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/iroutlinerpass/#a5b9a8fe2c3b6834817b2c12b08441cff">llvm::IROutlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarityanalysisprinterpass/#a8dde7acadd30b1860704841855a1a07d">llvm::IRSimilarityAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ivusersprinterpass/#acaca26216fbb3760b644841037f422d7">llvm::IVUsersPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/jumptabletoswitchpass/#a84778fc53894f05e88ce0cc794561742">llvm::JumpTableToSwitchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a48dd43ef05b66261790497edbdac92d9">llvm::JumpThreadingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraphanalysis/#a2b4c0dcc83d56146b52f6825c093b9db">llvm::LazyCallGraphAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraphdotprinterpass/#a172985546be95f992c665ac5d82e4a08">llvm::LazyCallGraphDOTPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraphprinterpass/#a2860c75599e4f96204b58e3c3be96dfe">llvm::LazyCallGraphPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoprinterpass/#ab0c9c93431b62e36767c973517bf1733">llvm::LazyValueInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lcssapass/#a7ae4df8ff3ca478772f6f055bf88bd1f">llvm::LCSSAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lintpass/#a414d1a9e191f52da209fd34c264a0cd4">llvm::LintPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariablesanalysis/#a9fefe50c560d6fab257603f7e8b20ecc">llvm::LiveDebugVariablesAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariablesprinterpass/#ab768a4034fa150ccf9784887c90ea58c">llvm::LiveDebugVariablesPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalsanalysis/#ada57f166f3386be2ce76727b30484e79">llvm::LiveIntervalsAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalsprinterpass/#a27fc3994cdeaf984273c9ec315423631">llvm::LiveIntervalsPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrixanalysis/#a2b601beea6193fd88698584c85cdadcd">llvm::LiveRegMatrixAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/livestacksprinterpass/#aa3bb974f54082b4cda61faff8b9756c0">llvm::LiveStacksPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariablesprinterpass/#a9b4943b4e128bc059ad8261448328184">llvm::LiveVariablesPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loadstorevectorizerpass/#a78465c41b72ca43acdbbfc47cbce3d76">llvm::LoadStoreVectorizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfoprinterpass/#ac64f34186e4e16d5b0baca6d232c810d">llvm::LoopAccessInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopanalysis/#aea38b668f2d98b7e9f64b8b3c2e524dc">llvm::LoopAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdataprefetchpass/#af1020d68a0e1a023973890cf0e079c28">llvm::LoopDataPrefetchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdistributepass/#ab4ccb40cf0dd5fd358dd5e0f0d4d7c6f">llvm::LoopDistributePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopextractorpass/#ac1cd83190da80057c6903402d80cc1f7">llvm::LoopExtractorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopfusepass/#a971f40ada3f1410759faede02bfbace7">llvm::LoopFusePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/looploadeliminationpass/#af81bad0018d7e67a1c92d785305426b0">llvm::LoopLoadEliminationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopprinterpass/#accccc20ac629c11b33de7dcb9fbc8449">llvm::LoopPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsimplifypass/#a294bd885b054adcb86315a9112ea0b33">llvm::LoopSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopstrengthreducepass/#a4e475c0fcd6ade09109db20acb073a77">llvm::LoopStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass/#a62ed17cf8aa893362e6c3c1f6d8a0898">llvm::LoopUnrollPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#af3b0e58cfdb2c6c663cd47a8808ba70a">llvm::LoopVectorizePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopverifierpass/#ac0ce536f08ade507773b16d2ceb9e8d1">llvm::LoopVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioningpass/#ab85aee23551eb41e8d1d7e01e1fd3f98">llvm::LoopVersioningPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowerallowcheckpass/#a0333cadd9ec11ea319d1fd3d3e0e6f05">llvm::LowerAllowCheckPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowermatrixintrinsicspass/#a7b05a9de14294b7a5a7904cc8d5c8e1e">llvm::LowerMatrixIntrinsicsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerswitchpass/#a7ed296f67da3966a7e2c0dd6f4fbcf9e">llvm::LowerSwitchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyanalysis/#ae20ca4ab784e07cd8a7c6ecfdf29db08">llvm::MachineBlockFrequencyAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyprinterpass/#aa35b27316428c32c7d320f53174fdbd5">llvm::MachineBlockFrequencyPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityprinterpass/#a7aef24d9b265073b477cd3781bb733ef">llvm::MachineBranchProbabilityPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinecsepass/#a495f06046288f4b8207cd36d72d19939">llvm::MachineCSEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortreeprinterpass/#adba4d4be92ffca419c2d16979f1c6d11">llvm::MachineDominatorTreePrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopanalysis/#a81d45818327732898308fbe130126f3e">llvm::MachineLoopAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopprinterpass/#ab87752c40887e452b51a8300347641de">llvm::MachineLoopPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitteranalysis/#a362fbd1b0bdfc30a7b45a625fcf582c5">llvm::MachineOptimizationRemarkEmitterAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortreeprinterpass/#a3979191544a4fa418cb6332df5edd481">llvm::MachinePostDominatorTreePrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetricsanalysis/#a845e43b0a7e3fa930353004b91b6842c">llvm::MachineTraceMetricsAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetricsverifierpass/#a6ba933eae8cb10287475af486e7b1602">llvm::MachineTraceMetricsVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memcpyoptpass/#a07c3f5129a977e2f949212878c3042ae">llvm::MemCpyOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceanalysis/#a19bc33a610ce16b681fe59559cd987d9">llvm::MemoryDependenceAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/llvm/memorysanitizerpass/#adfd94cfcef9d896734905bd5a18a05df">llvm::MemorySanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaanalysis/#a0edf62c9bbb9566682c697dfb8fb2ed5">llvm::MemorySSAAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaprinterpass/#ab228481c477a8f642742650e2f03c231">llvm::MemorySSAPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/memoryssaverifierpass/#a5fa2dbea1ad6cf5950da7d2a642a73bd">llvm::MemorySSAVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssawalkerprinterpass/#a9982e0fb4d45bbefee3aa1a790306610">llvm::MemorySSAWalkerPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofcontextdisambiguation/#ac43814024a542d89728f88411b553e6d">llvm::MemProfContextDisambiguation::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofusepass/#a301e9c18f7576c32229ca4c2a06fb8e4">llvm::MemProfUsePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mergedloadstoremotionpass/#af9d31b63718e1ad6d4e0881e49a415bd">llvm::MergedLoadStoreMotionPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/mergeicmpspass/#a96cfc6defc256b49f69f6fb8bfbf8c87">llvm::MergeICmpsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/metarenamerpass/#a1f547e81e18e412faa9f0a8a71cbd90c">llvm::MetaRenamerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindexanalysis/#a2aa0bcdd9165815fc18c689df7f2c7f5">llvm::ModuleSummaryIndexAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moveautoinitpass/#a55a3f992f62d23ae617927c2de5a81c9">llvm::MoveAutoInitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mustbeexecutedcontextprinterpass/#a1b1a19034ac7bbb0481e54e850fc431a">llvm::MustBeExecutedContextPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mustexecuteprinterpass/#ac776766336198f23f11dc141cd0278d7">llvm::MustExecutePrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/naryreassociatepass/#a44a686152f979478fbbac82b70bf85fb">llvm::NaryReassociatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/newgvnpass/#a6b1b7ab1a677eb8039694b4dfe6cb997">llvm::NewGVNPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarccontractpass/#a37aa96fbe116641ca7204a785341c962">llvm::ObjCARCContractPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarcoptpass/#a02b31ca54388bfecbdd6593b7563d146">llvm::ObjCARCOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitteranalysis/#a82def85e95d702c5c226841c3d8205b8">llvm::OptimizationRemarkEmitterAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/llvm/paevalpass/#a7f0dda30879f62ea4eefdc53cfbb0e1d">llvm::PAEvalPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/partialinlinerpass/#a022b0aa595cef197b5b0c655cd18ad9c">llvm::PartialInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/partiallyinlinelibcallspass/#a0e2ff100989ce66c294cfe38904c6cf1">llvm::PartiallyInlineLibCallsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/peepholeoptimizerpass/#a80af47b78e07ddb33af6e7d86af034df">llvm::PeepholeOptimizerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/pgoforcefunctionattrspass/#a5a7425ff46058c5adf7da1d9a58c4000">llvm::PGOForceFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/phivaluesprinterpass/#a21d9889708699714c41846b90164e285">llvm::PhiValuesPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/physicalregisterusageinfoprinterpass/#ac906046b0d9451273e8073b46cdfa74c">llvm::PhysicalRegisterUsageInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/placesafepointspass/#a4c1a6d3206d9f1278836bdc314e56141">llvm::PlaceSafepointsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/postdominatortreeprinterpass/#a5a8a80e5f89a52ac0fb8e2ee24c3960b">llvm::PostDominatorTreePrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/postorderfunctionattrspass/#a8312d250d0f7b4407b4bad97293e5865">llvm::PostOrderFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/predicateinfoprinterpass/#a3d2162a259a40a3c7fecd27694e24a8d">llvm::PredicateInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/predicateinfoverifierpass/#aa6365590a30ab595458b49c30b231661">llvm::PredicateInfoVerifierPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/preiselintrinsicloweringpass/#a6c4bdf5cd38f45ec8052f395f32f63ee">llvm::PreISelIntrinsicLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/printmirpass/#a354177020e92f5ab2dd0433a47123270">llvm::PrintMIRPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/printmodulepass/#abb1b61a3833aedd2fa62272bfd6740f3">llvm::PrintModulePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryprinterpass/#aff1db3108eff5862498fecfa0d419d72">llvm::ProfileSummaryPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/promotepass/#aca8a105910e7bb81285435f553e71872">llvm::PromotePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeupdatepass/#a1eef7e13ba8f6964ddd2f64c8a85d8b8">llvm::PseudoProbeUpdatePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/recomputeglobalsaapass/#abd209c0e2c06b211cbd147ad96b70890">llvm::RecomputeGlobalsAAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfoanalysis/#aeb18bff655e7a0fdfbf8143b8beec782">llvm::RegionInfoAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfoprinterpass/#a226463c4c73a0f1fc36d8d3256911f72">llvm::RegionInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/regioninfoverifierpass/#a9e4421b3ea5f943378bff6877592acf2">llvm::RegionInfoVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regtomempass/#a0a8fbb23329369eafe88acc194f6336d">llvm::RegToMemPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regusageinfocollectorpass/#a387db9c3806e18b7691b075381d0ac09">llvm::RegUsageInfoCollectorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regusageinfopropagationpass/#ab365c22ad0becb1f9a4f0fc2d85f088f">llvm::RegUsageInfoPropagationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/rellookuptableconverterpass/#a3b1519f165c877970b589c9f53db69eb">llvm::RelLookupTableConverterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/replacewithveclib/#ac03e0f62c8cbbdd055546686f847183c">llvm::ReplaceWithVeclib::run</a>, <a href="/web-llvm/docs/api/classes/llvm/reversepostorderfunctionattrspass/#a711463cdc12e518aaca8c394a0f82139">llvm::ReversePostOrderFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc/#af56b6dd2da7f65fa682eaf6a16cdb36a">llvm::RewriteStatepointsForGC::run</a>, <a href="/web-llvm/docs/api/classes/llvm/safepointirverifierpass/#af94bb71714afbf2f143e6535c8264e56">llvm::SafepointIRVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderpass/#a324d3696b255beea7cfd1e8b901b2363">llvm::SampleProfileLoaderPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxvectorizerpass/#a551ef06f642e5ab4d0e22806eb5bb4ac">llvm::SandboxVectorizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolutionanalysis/#acbc87d909d53e5f43fde82950e15b59d">llvm::ScalarEvolutionAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolutionprinterpass/#a5701836bcbb5fc1663cbaf72ea475bc0">llvm::ScalarEvolutionPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolutionverifierpass/#a922e2e00f7528f19fdece7de80099fc2">llvm::ScalarEvolutionVerifierPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/scalarizemaskedmemintrinpass/#ab805176ab5d08e2a34fadbc760bca5a6">llvm::ScalarizeMaskedMemIntrinPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarizerpass/#a250da10ea723b93bcd9f52cd0bca4d7e">llvm::ScalarizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sccppass/#ad9201f5b1be7f1b9cbff7b2b631b2256">llvm::SCCPPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaa/#ab52c682b31b74ce3fe18ff10e5e2bbac">llvm::SCEVAA::run</a>, <a href="/web-llvm/docs/api/classes/llvm/separateconstoffsetfromgeppass/#a949e76f284f0977c83f729850a8b8a8b">llvm::SeparateConstOffsetFromGEPPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sifixsgprcopiespass/#aa09db25356e6c1389f8c477c5555e298">llvm::SIFixSGPRCopiesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siloadstoreoptimizerpass/#a73bd665c6e03c1dc196c107a450e228a">llvm::SILoadStoreOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siloweri1copiespass/#a0af1fadc28e71aac6e7e74c59686a02b">llvm::SILowerI1CopiesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/silowersgprspillspass/#acc251fdad2ff98bf8f116ecbd8e93b14">llvm::SILowerSGPRSpillsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/simplifycfgpass/#a1196be608a7f568e9cb19fe11f80ebe2">llvm::SimplifyCFGPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sinkingpass/#a07a25f4cfc32581da84eea1e0ced7f2e">llvm::SinkingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sioptimizevgprliverangepass/#a7bf8baafeef111584b003c06f997080a">llvm::SIOptimizeVGPRLiveRangePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sipreallocatewwmregspass/#ae0b2123e3a8afffcdfc0e364d088f39a">llvm::SIPreAllocateWWMRegsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexesprinterpass/#afedda4628bf652e8255f1e6a6378d744">llvm::SlotIndexesPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/slpvectorizerpass/#aaec443311cb572adf0e2db9db82279ef">llvm::SLPVectorizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/speculativeexecutionpass/#a75693e29732ce9935478d5fdc533c67d">llvm::SpeculativeExecutionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/spillplacementanalysis/#a2856ed5854959844cc1615dcc351614f">llvm::SpillPlacementAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvconvergenceregionanalysis/#ac6c45e1270072876327eef85a8f73ea9">llvm::SPIRVConvergenceRegionAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sroapass/#a6cca3e145c2eb9050c6b4b94e2f760a0">llvm::SROAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stackcoloringpass/#a693535db98527be92419386a4baba10a">llvm::StackColoringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyanalysis/#a3843b659bf378a511aadde4a6d10aa72">llvm::StackSafetyAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalanalysis/#aa68230712fbc6c2839196d128777e5c5">llvm::StackSafetyGlobalAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalprinterpass/#ac43f3f00ee89cc0fd16d5ba5323eef37">llvm::StackSafetyGlobalPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyprinterpass/#a418ed81d84497654db26995150b7c57a">llvm::StackSafetyPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/straightlinestrengthreducepass/#a40a452b8f3a3f5538eed5201e5bfdcc4">llvm::StraightLineStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/structurizecfgpass/#aeb3e7a1f92ba7129a43fdfe85ea9c000">llvm::StructurizeCFGPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/tailcallelimpass/#ab754a2815f5333ff5f443593896814dc">llvm::TailCallElimPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicatepassbase/#a0780ac5d6a2962adf46e1c611e6ca6fa">llvm::TailDuplicatePassBase&lt; DerivedT, PreRegAlloc &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/thinltobitcodewriterpass/#a407be825a5084267d383681109e30df9">llvm::ThinLTOBitcodeWriterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/typepromotionpass/#addcc6ab5729a0a8e495cdc585f02234c">llvm::TypePromotionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/uniformityinfoprinterpass/#a60f393028e23ebd547f6b141ccb51c43">llvm::UniformityInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/unifyloopexitspass/#afa18953dc3062e2c68866c9065b12bcb">llvm::UnifyLoopExitsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/verifierpass/#a27b98c15f4931023c6e5f739d9df2a02">llvm::VerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/verifierpass/#a6112c8ef2aa7acf00aa9b0ce02eb3711">llvm::VerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmapprinterpass/#a101be45b1a9d89ebbd7df78a0f9ffa85">llvm::VirtRegMapPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/warnmissedtransformationspass/#aa622d589f82389844d93eca02d865d4c">llvm::WarnMissedTransformationsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtpass/#af94d9399906155205bf6afa17427d5c7">llvm::WholeProgramDevirtPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a358b28b8ab641a2a22ed8849a2dff2cf">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#ab31c9b14b5bd6245b789fb6ed28a7aeb">updateNewSCCFunctionAnalyses</a>.</p>

</div>
</div>

### invalidate() {#a64b2a209a16bcd41375b5cae12690eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::invalidate (IRUnitT &amp; IR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA)</td>
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

<p>Invalidate cached analyses for an IR unit.</p>


<p>Walk through all of the analyses pertaining to this unit of IR and invalidate them, unless they are preserved by the PreservedAnalyses set.</p>


<p>Declaration at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerimpl-h">PassManagerImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="#a828ff8185f881fca9e3d534781244041">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getCachedResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a> and <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#a698253acb40299131fecdb9489f88fcd">llvm::PassInstrumentation::runAnalysisInvalidated</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#aa64f6bcd5ace031369edc14aa406d745">incorporateNewSCCRange</a>, <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontomachinefunctionpassadaptor/#a1c8aea757190a42fd931c0d95a4f2721">llvm::FunctionToMachineFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ircepass/#ac7e45d3f509c7e40c4d6666a24e88f73">llvm::IRCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a>.</p>

</div>
</div>

### isPassRegistered() {#a03f50a72945de4b779ffd17b508974c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::isPassRegistered ()</td>
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

<p>Returns true if the specified analysis pass is registered.</p>

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### registerPass() {#a91ff894f756175a693c85bf73f79de9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassBuilderT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::registerPass (PassBuilderT &amp;&amp; PassBuilder)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an analysis pass with the manager.</p>


<p>The parameter is a callable whose result is an analysis pass. This allows passing in a lambda to construct the analysis.</p>


<p>The analysis type to register is the type returned by calling the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a></span> argument. If that type has already been registered, then the argument will not be called and this function will return false. Otherwise, we register the analysis returned by calling <span class="doxyComputerOutput">PassBuilder()</span>, and this function returns true.</p>


<p>(Note: Although the return value of this function indicates whether or not an analysis was previously registered, you should just register all the analyses you might want and let this class run them lazily. This idiom lets us minimize the number of times we have to look up analyses in our hashtable.)</p>


<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a3c2e12459e81e47a53dc49484af24bc2">llvm::PassBuilder::crossRegisterProxies</a>.</p>

</div>
</div>

### verifyNotInvalidated() {#a29648f060d2dd1e126ed17733813cf0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::verifyNotInvalidated (IRUnitT &amp; IR, typename PassT::Result * Result)</td>
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

<p>Verify that the given Result cannot be invalidated, assert otherwise.</p>

<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getCachedResultImpl() {#ad87204b3132c8461e2b6f0e3629da6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResultConceptT * llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getCachedResultImpl (<a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> * ID, IRUnitT &amp; IR)</td>
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

<p>Get a cached analysis result or return null.</p>

<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### getResultImpl() {#a7c21e9b71e06095567ef2d8749ec18b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisManager&lt; IRUnitT, ExtraArgTs... &gt;::ResultConceptT &amp; llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResultImpl (<a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> * ID, IRUnitT &amp; IR, ExtraArgTs... ExtraArgs)</td>
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

<p>Get an analysis result, running the pass if necessary.</p>

<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerimpl-h">PassManagerImpl.h</a>.</p>

</div>
</div>

### lookUpPass() {#a896a2d0697604f08f99fe7b019ad3bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassConceptT &amp; llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::lookUpPass (<a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> * ID)</td>
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

<p>Look up a registered analysis pass.</p>

<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### lookUpPass() {#a7b69a92067fc1113f29d9d4ca1d6c3ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PassConceptT &amp; llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::lookUpPass (<a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> * ID)</td>
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

<p>Look up a registered analysis pass.</p>

<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AnalysisPasses {#a6165fb98ddb81478865918c3e1b2b7d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisPassMapT llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::AnalysisPasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of analysis passes, indexed by <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### AnalysisResultLists {#af18e57efae06e5053d32594df0afbbcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisResultListMapT llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::AnalysisResultLists</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from IR unit to a list of analysis results.</p>


<p>Provides linear time removal of all analysis results for a IR unit and the ultimate storage for a particular cached analysis result.</p>


<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### AnalysisResults {#af6aa580ea41f8ad85f2dee2a40fb578d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisResultMapT llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::AnalysisResults</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from an analysis <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and IR unit to a particular cached analysis result.</p>

<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerimpl-h">PassManagerImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
