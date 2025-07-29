---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprofilematcher
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SampleProfileMatcher` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SampleProfileMatcher { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">llvm/Transforms/IPO/SampleProfileMatcher.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MatchState { <a href="#a0c1553a56d0c17e710fa92bbff188ca7">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d575a750ffea9476649ae2b753350af">SampleProfileMatcher</a> (Module &amp;M, SampleProfileReader &amp;Reader, LazyCallGraph &amp;CG, const PseudoProbeManager *ProbeManager, ThinOrFullLTOPhase LTOPhase, HashKeyMap&lt; std::unordered_map, FunctionId, Function * &gt; &amp;SymMap, std::shared_ptr&lt; ProfileSymbolList &gt; PSL, HashKeyMap&lt; std::unordered_map, FunctionId, FunctionId &gt; &amp;FuncNameToProfNameMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5031837ecbfce3c5c2811da239ba777e">runOnModule</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac46a82d65c568d23542b5e44e0b89206">clearMatchingData</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d6e8887ebcd67a0f2f3bdde0e3c2064">getFlattenedSamplesFor</a> (const FunctionId &amp;Fname)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b54585ab5664b31476f0713873da7de">getFlattenedSamplesFor</a> (const Function &amp;F)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a80b4ab0c2542c80f3dca15c07ca1be90">freeContainer</a> (T &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59d2ac5e6a9af433fbdb5258d4698cd4">getFilteredAnchorList</a> (const AnchorMap &amp;IRAnchors, const AnchorMap &amp;ProfileAnchors, AnchorList &amp;FilteredIRAnchorsList, AnchorList &amp;FilteredProfileAnchorList)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50d3c7885d5b38db01821adc652310ee">runOnFunction</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f39bcb35c628aae29f9f120321d7f5">findIRAnchors</a> (const Function &amp;F, AnchorMap &amp;IRAnchors) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af802a727eef11bea1e045a67c836ef03">findProfileAnchors</a> (const FunctionSamples &amp;FS, AnchorMap &amp;ProfileAnchors) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e464831372c1eb585b7ab2ff2bc6171">recordCallsiteMatchStates</a> (const Function &amp;F, const AnchorMap &amp;IRAnchors, const AnchorMap &amp;ProfileAnchors, const LocToLocMap *IRToProfileLocationMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c1f023ea55f7784af980db3f06a189">isMismatchState</a> (const enum MatchState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e72a3549f6a2895c551c9bf1dbb87bb">isInitialState</a> (const enum MatchState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a3aba5072a6a2cf78d30eb97ee1110">isFinalState</a> (const enum MatchState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa238f333c4e95904c3815cee9c0be970">countCallGraphRecoveredSamples</a> (const FunctionSamples &amp;FS, std::unordered_set&lt; FunctionId &gt; &amp;MatchedUnusedProfile)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9efd5a074492f074e0ea5246dc192e8d">countMismatchedFuncSamples</a> (const FunctionSamples &amp;FS, bool IsTopLevel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd355e12e61d6d0fe4918a68fe588f33">countMismatchCallsites</a> (const FunctionSamples &amp;FS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f9536e80e377bc64b0cb022b8484b6">countMismatchedCallsiteSamples</a> (const FunctionSamples &amp;FS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3f4f71a63b3b1c58d8af60074d8bd8d">computeAndReportProfileStaleness</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa362710559abc702a87cb8c3bd5db508">UpdateWithSalvagedProfiles</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ac5c498b2a2603e7b437b91b6dcd3a9f9">LocToLocMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56bef332122d709a5cf35f472f2d02c2">getIRToProfileLocationMap</a> (const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88a2ae3e92eac3f5186231b5b9493c0">distributeIRToProfileLocationMap</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad919ad91e26392f7a6bcc853b609cf63">distributeIRToProfileLocationMap</a> (FunctionSamples &amp;FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ac5c498b2a2603e7b437b91b6dcd3a9f9">LocToLocMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4286f8339951cff560473291d862e410">longestCommonSequence</a> (const AnchorList &amp;IRCallsiteAnchors, const AnchorList &amp;ProfileCallsiteAnchors, bool MatchUnusedFunction)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cfba859d2c8d7388b3f2abf50479731">matchNonCallsiteLocs</a> (const LocToLocMap &amp;AnchorMatchings, const AnchorMap &amp;IRAnchors, LocToLocMap &amp;IRToProfileLocationMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a141d2ab393c34e7e185978eba35ae49b">runStaleProfileMatching</a> (const Function &amp;F, const AnchorMap &amp;IRAnchors, const AnchorMap &amp;ProfileAnchors, LocToLocMap &amp;IRToProfileLocationMap, bool RunCFGMatching, bool RunCGMatching)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b6027b67654dfef138e312d8aa998e">functionHasProfile</a> (const FunctionId &amp;IRFuncName, Function *&amp;FuncWithoutProfile)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5776870f7442a813d68bf932f0eaf63">isProfileUnused</a> (const FunctionId &amp;ProfileFuncName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e212b6fd0083cf1cac62eb7d68abf7e">functionMatchesProfileHelper</a> (const Function &amp;IRFunc, const FunctionId &amp;ProfFunc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a18b43de9c6a569b324a195e1bd829e">functionMatchesProfile</a> (const FunctionId &amp;IRFuncName, const FunctionId &amp;ProfileFuncName, bool FindMatchedProfileOnly)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbc23f81869b609976bea275c06ab415">functionMatchesProfile</a> (Function &amp;IRFunc, const FunctionId &amp;ProfFunc, bool FindMatchedProfileOnly)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24215b2489415364a8535f9f6798e8f">findFunctionsWithoutProfile</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a835a828a741301fcab91b83ba1d3d4e3">reportOrPersistProfileStats</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af60d3bd08b7e5fa36e234414ff0a92fc">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader">SampleProfileReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98342ee251de68d2a48a594556056b78">Reader</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addb3a8a938a298ae6ed59483447722b4">CG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudoprobemanager">PseudoProbeManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6120a09993d8239645bf43ba04751c1f">ProbeManager</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca0f206d44cbab14ac34f08b4c63a375">LTOPhase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadb014482ddc4c11d377b85d6081b035">FlattenedProfiles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ac5c498b2a2603e7b437b91b6dcd3a9f9">LocToLocMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a8e18ba47fd4bcfe1c4f218e3dfdce7">FuncMappings</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::unordered_map&lt; <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a>, MatchState, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocationhash">LineLocationHash</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292b4c6e1f314908caa381a4dc4cc47f">FuncCallsiteMatchStates</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt;, bool, FuncToProfileNameMapHash &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30cd50ca212d1b283b245dadaca2d515">FuncProfileMatchCache</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01b85a84cd017fea46b0b888c7020311">FuncToProfileNameMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb7869daf4e9748e904e1863918c23b7">FuncNameToProfNameMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee3e2accfee4a2fbafd772d456969d7">SymbolMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2130d8869050ac6ef24c2d8e570387b8">FunctionsWithoutProfile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profilesymbollist">ProfileSymbolList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d9f41fc7d3bbf2dbba47518cbc152af">PSL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e345fbb851d8ae022969b00d4c9b1d">TotalProfiledFunc</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a94e58f2e278e24a1859d3be7a7e8e2">NumStaleProfileFunc</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b1935f0ad4eafd18a387fcb65f8047">TotalProfiledCallsites</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd9f2b2f6d20f614fc0dc04eb25a3976">NumMismatchedCallsites</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9dbd8eb9fa446bdecbd9ddfaf222679">NumRecoveredCallsites</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea7e2d07d581a90e35445dd4f760adf9">TotalFunctionSamples</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e64bca02b113db2d66ff6e155e6edb2">MismatchedFunctionSamples</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeef26744069db34b281064f4e082e7ee">MismatchedCallsiteSamples</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f74f945ba7ecdd768e08bc7384b9a56">RecoveredCallsiteSamples</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67951edecbc97ec3377d24128b1acddc">NumCallGraphRecoveredProfiledFunc</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40abb5892d54fc5dd8988fc4eeeac283">NumCallGraphRecoveredFuncSamples</a> = 0</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af841620e01d5401b2800046e9d07e768">UnknownIndirectCallee</a> = ...</td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### MatchState {#a0c1553a56d0c17e710fa92bbff188ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::SampleProfileMatcher::MatchState </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Unknown<a id="a0c1553a56d0c17e710fa92bbff188ca7a88183b946cc5f0e8c96b2e66e1c74a7e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InitialMatch<a id="a0c1553a56d0c17e710fa92bbff188ca7add8e5ae8812a9410fa48ba41e0b61070"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InitialMismatch<a id="a0c1553a56d0c17e710fa92bbff188ca7ab29aeb1e55e22e4113f24d6bb64e1eb5"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnchangedMatch<a id="a0c1553a56d0c17e710fa92bbff188ca7a226892a318d85b4b4c4b467a4429d8e2"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnchangedMismatch<a id="a0c1553a56d0c17e710fa92bbff188ca7a2d75dc2539a9bf1cadb3eb577d629427"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RecoveredMismatch<a id="a0c1553a56d0c17e710fa92bbff188ca7acaa5f3df0a56da3dc61b04043187bb2a"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RemovedMatch<a id="a0c1553a56d0c17e710fa92bbff188ca7a08bf9e42e37245b1d9f8db8cc203e0c0"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SampleProfileMatcher() {#a9d575a750ffea9476649ae2b753350af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SampleProfileMatcher::SampleProfileMatcher (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader">SampleProfileReader</a> &amp; Reader, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp; CG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudoprobemanager">PseudoProbeManager</a> * ProbeManager, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> LTOPhase, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; SymMap, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profilesymbollist">ProfileSymbolList</a> &gt; PSL, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt; &amp; FuncNameToProfNameMap)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearMatchingData() {#ac46a82d65c568d23542b5e44e0b89206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileMatcher::clearMatchingData ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### runOnModule() {#a5031837ecbfce3c5c2811da239ba777e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::runOnModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d05aa2854cf8b7927d9f162180d1a37">llvm::buildTopDownFuncOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profileconverter/#aa3ffda78d2adde5ff1916294f9fe3488">llvm::sampleprof::ProfileConverter::flattenProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a8fcac4cee0537749800b9b24859dc7dd">SalvageStaleProfile</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a176dcdd54b914f2847535fc7c8f1f77b">SalvageUnusedProfile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac5e4f143be554153513191443c4709f6">llvm::skipProfileForFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeAndReportProfileStaleness() {#af3f4f71a63b3b1c58d8af60074d8bd8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::computeAndReportProfileStaleness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### countCallGraphRecoveredSamples() {#aa238f333c4e95904c3815cee9c0be970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::countCallGraphRecoveredSamples (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; FS, std::unordered_set&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt; &amp; MatchedUnusedProfile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### countMismatchCallsites() {#acd355e12e61d6d0fe4918a68fe588f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::countMismatchCallsites (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### countMismatchedCallsiteSamples() {#ae4f9536e80e377bc64b0cb022b8484b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::countMismatchedCallsiteSamples (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### countMismatchedFuncSamples() {#a9efd5a074492f074e0ea5246dc192e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::countMismatchedFuncSamples (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; FS, bool IsTopLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### distributeIRToProfileLocationMap() {#ae88a2ae3e92eac3f5186231b5b9493c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::distributeIRToProfileLocationMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 894 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### distributeIRToProfileLocationMap() {#ad919ad91e26392f7a6bcc853b609cf63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::distributeIRToProfileLocationMap (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 877 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### findFunctionsWithoutProfile() {#ad24215b2489415364a8535f9f6798e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::findFunctionsWithoutProfile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### findIRAnchors() {#a33f39bcb35c628aae29f9f120321d7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::findIRAnchors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#a119c56314c891b1049f631457144812f">AnchorMap</a> &amp; IRAnchors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### findProfileAnchors() {#af802a727eef11bea1e045a67c836ef03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::findProfileAnchors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; FS, <a href="/web-llvm/docs/api/namespaces/llvm/#a119c56314c891b1049f631457144812f">AnchorMap</a> &amp; ProfileAnchors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### freeContainer() {#a80b4ab0c2542c80f3dca15c07ca1be90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileMatcher::freeContainer (T &amp; C)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### functionHasProfile() {#a61b6027b67654dfef138e312d8aa998e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileMatcher::functionHasProfile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &amp; IRFuncName, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *&amp; FuncWithoutProfile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### functionMatchesProfile() {#a6a18b43de9c6a569b324a195e1bd829e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileMatcher::functionMatchesProfile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &amp; IRFuncName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &amp; ProfileFuncName, bool FindMatchedProfileOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### functionMatchesProfile() {#acbc23f81869b609976bea275c06ab415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileMatcher::functionMatchesProfile (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; IRFunc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &amp; ProfFunc, bool FindMatchedProfileOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### functionMatchesProfileHelper() {#a4e212b6fd0083cf1cac62eb7d68abf7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileMatcher::functionMatchesProfileHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; IRFunc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &amp; ProfFunc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### getFilteredAnchorList() {#a59d2ac5e6a9af433fbdb5258d4698cd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::getFilteredAnchorList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a119c56314c891b1049f631457144812f">AnchorMap</a> &amp; IRAnchors, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a119c56314c891b1049f631457144812f">AnchorMap</a> &amp; ProfileAnchors, <a href="/web-llvm/docs/api/namespaces/llvm/#ab922ecb2ac147fd3b2816cd1182932d3">AnchorList</a> &amp; FilteredIRAnchorsList, <a href="/web-llvm/docs/api/namespaces/llvm/#ab922ecb2ac147fd3b2816cd1182932d3">AnchorList</a> &amp; FilteredProfileAnchorList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### getFlattenedSamplesFor() {#a0d6e8887ebcd67a0f2f3bdde0e3c2064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples * llvm::SampleProfileMatcher::getFlattenedSamplesFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &amp; Fname)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### getFlattenedSamplesFor() {#a9b54585ab5664b31476f0713873da7de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples * llvm::SampleProfileMatcher::getFlattenedSamplesFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### getIRToProfileLocationMap() {#a56bef332122d709a5cf35f472f2d02c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocToLocMap &amp; llvm::SampleProfileMatcher::getIRToProfileLocationMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### isFinalState() {#a25a3aba5072a6a2cf78d30eb97ee1110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SampleProfileMatcher::isFinalState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> enum MatchState &amp; State)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### isInitialState() {#a6e72a3549f6a2895c551c9bf1dbb87bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SampleProfileMatcher::isInitialState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> enum MatchState &amp; State)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### isMismatchState() {#a87c1f023ea55f7784af980db3f06a189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SampleProfileMatcher::isMismatchState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> enum MatchState &amp; State)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### isProfileUnused() {#ab5776870f7442a813d68bf932f0eaf63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileMatcher::isProfileUnused (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &amp; ProfileFuncName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### longestCommonSequence() {#a4286f8339951cff560473291d862e410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocToLocMap SampleProfileMatcher::longestCommonSequence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ab922ecb2ac147fd3b2816cd1182932d3">AnchorList</a> &amp; IRCallsiteAnchors, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ab922ecb2ac147fd3b2816cd1182932d3">AnchorList</a> &amp; ProfileCallsiteAnchors, bool MatchUnusedFunction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### matchNonCallsiteLocs() {#a7cfba859d2c8d7388b3f2abf50479731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::matchNonCallsiteLocs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ac5c498b2a2603e7b437b91b6dcd3a9f9">LocToLocMap</a> &amp; AnchorMatchings, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a119c56314c891b1049f631457144812f">AnchorMap</a> &amp; IRAnchors, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ac5c498b2a2603e7b437b91b6dcd3a9f9">LocToLocMap</a> &amp; IRToProfileLocationMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### recordCallsiteMatchStates() {#a6e464831372c1eb585b7ab2ff2bc6171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::recordCallsiteMatchStates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a119c56314c891b1049f631457144812f">AnchorMap</a> &amp; IRAnchors, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a119c56314c891b1049f631457144812f">AnchorMap</a> &amp; ProfileAnchors, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ac5c498b2a2603e7b437b91b6dcd3a9f9">LocToLocMap</a> * IRToProfileLocationMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### reportOrPersistProfileStats() {#a835a828a741301fcab91b83ba1d3d4e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SampleProfileMatcher::reportOrPersistProfileStats ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### runOnFunction() {#a50d3c7885d5b38db01821adc652310ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### runStaleProfileMatching() {#a141d2ab393c34e7e185978eba35ae49b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::runStaleProfileMatching (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a119c56314c891b1049f631457144812f">AnchorMap</a> &amp; IRAnchors, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a119c56314c891b1049f631457144812f">AnchorMap</a> &amp; ProfileAnchors, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ac5c498b2a2603e7b437b91b6dcd3a9f9">LocToLocMap</a> &amp; IRToProfileLocationMap, bool RunCFGMatching, bool RunCGMatching)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

### UpdateWithSalvagedProfiles() {#aa362710559abc702a87cb8c3bd5db508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileMatcher::UpdateWithSalvagedProfiles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>, definition at line 828 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CG {#addb3a8a938a298ae6ed59483447722b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph&amp; llvm::SampleProfileMatcher::CG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### FlattenedProfiles {#aadb014482ddc4c11d377b85d6081b035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleProfileMap llvm::SampleProfileMatcher::FlattenedProfiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### FuncCallsiteMatchStates {#a292b4c6e1f314908caa381a4dc4cc47f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::unordered_map&lt;LineLocation, MatchState, LineLocationHash&gt; &gt; llvm::SampleProfileMatcher::FuncCallsiteMatchStates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### FuncMappings {#a5a8e18ba47fd4bcfe1c4f218e3dfdce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;LocToLocMap&gt; llvm::SampleProfileMatcher::FuncMappings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### FuncNameToProfNameMap {#aeb7869daf4e9748e904e1863918c23b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashKeyMap&lt;std::unordered_map, FunctionId, FunctionId&gt;* llvm::SampleProfileMatcher::FuncNameToProfNameMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### FuncProfileMatchCache {#a30cd50ca212d1b283b245dadaca2d515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::pair&lt;const Function *, FunctionId&gt;, bool, FuncToProfileNameMapHash&gt; llvm::SampleProfileMatcher::FuncProfileMatchCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### FunctionsWithoutProfile {#a2130d8869050ac6ef24c2d8e570387b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashKeyMap&lt;std::unordered_map, FunctionId, Function *&gt; llvm::SampleProfileMatcher::FunctionsWithoutProfile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### FuncToProfileNameMap {#a01b85a84cd017fea46b0b888c7020311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;Function *, FunctionId&gt; llvm::SampleProfileMatcher::FuncToProfileNameMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### LTOPhase {#aca0f206d44cbab14ac34f08b4c63a375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ThinOrFullLTOPhase llvm::SampleProfileMatcher::LTOPhase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### M {#af60d3bd08b7e5fa36e234414ff0a92fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; llvm::SampleProfileMatcher::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### MismatchedCallsiteSamples {#aeef26744069db34b281064f4e082e7ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileMatcher::MismatchedCallsiteSamples = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### MismatchedFunctionSamples {#a7e64bca02b113db2d66ff6e155e6edb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileMatcher::MismatchedFunctionSamples = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### NumCallGraphRecoveredFuncSamples {#a40abb5892d54fc5dd8988fc4eeeac283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileMatcher::NumCallGraphRecoveredFuncSamples = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### NumCallGraphRecoveredProfiledFunc {#a67951edecbc97ec3377d24128b1acddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileMatcher::NumCallGraphRecoveredProfiledFunc = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### NumMismatchedCallsites {#acd9f2b2f6d20f614fc0dc04eb25a3976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileMatcher::NumMismatchedCallsites = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### NumRecoveredCallsites {#aa9dbd8eb9fa446bdecbd9ddfaf222679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileMatcher::NumRecoveredCallsites = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### NumStaleProfileFunc {#a3a94e58f2e278e24a1859d3be7a7e8e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileMatcher::NumStaleProfileFunc = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### ProbeManager {#a6120a09993d8239645bf43ba04751c1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoProbeManager* llvm::SampleProfileMatcher::ProbeManager</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### PSL {#a7d9f41fc7d3bbf2dbba47518cbc152af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;ProfileSymbolList&gt; llvm::SampleProfileMatcher::PSL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### Reader {#a98342ee251de68d2a48a594556056b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleProfileReader&amp; llvm::SampleProfileMatcher::Reader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### RecoveredCallsiteSamples {#a4f74f945ba7ecdd768e08bc7384b9a56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileMatcher::RecoveredCallsiteSamples = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### SymbolMap {#a8ee3e2accfee4a2fbafd772d456969d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashKeyMap&lt;std::unordered_map, FunctionId, Function *&gt;* llvm::SampleProfileMatcher::SymbolMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### TotalFunctionSamples {#aea7e2d07d581a90e35445dd4f760adf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileMatcher::TotalFunctionSamples = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### TotalProfiledCallsites {#a82b1935f0ad4eafd18a387fcb65f8047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileMatcher::TotalProfiledCallsites = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

### TotalProfiledFunc {#a35e345fbb851d8ae022969b00d4c9b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SampleProfileMatcher::TotalProfiledFunc = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### UnknownIndirectCallee {#af841620e01d5401b2800046e9d07e768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::SampleProfileMatcher::UnknownIndirectCallee</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
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
<div class="doxyVerbatim">=
      "unknown.indirect.callee"
</div>
</dd>
</dl>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">SampleProfileMatcher.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofilematcher-cpp">SampleProfileMatcher.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
