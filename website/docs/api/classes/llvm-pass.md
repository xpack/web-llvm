---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Pass` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> interface - Implemented by all 'passes'. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Pass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager">MPPassManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager">MPPassManager</a> manages ModulePasses and function pass managers. <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass">CallGraphSCCPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> class - This class is used to implement most global optimizations. <a href="/web-llvm/docs/api/classes/llvm/functionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/looppass">LoopPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a> class - This class is used to implement unstructured interprocedural optimizations and analyses. <a href="/web-llvm/docs/api/classes/llvm/modulepass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regionpass">RegionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pass that runs on each <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> in a function. <a href="/web-llvm/docs/api/classes/llvm/regionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl">FunctionPassManagerImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl">FunctionPassManagerImpl</a> manages FPPassManagers. <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl">PassManagerImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl">PassManagerImpl</a> manages MPPassManagers. <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16baa169d062524be5a6b67609266174">Pass</a> (PassKind K, char &amp;pid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40d19ce644ec38c52ea00be59016cd5">Pass</a> (const Pass &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe2fe9b29d21424fe4b410fc8e98606c">~Pass</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af468a2aeb0d98e3dbeda38176ce516d3">operator=</a> (const Pass &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0da955cbb4215ccd3e153c81e415b9d5">PassKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de4db62e6884f2e5efea6793af30d99">getPassKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad729b39eacf070a9bca84533b3c743bf">getPassName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#ad729b39eacf070a9bca84533b3c743bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63192e749ba4a0ee29336a59d6a19647">getPassID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassID - Return the PassID number that corresponds to this pass. <a href="#a63192e749ba4a0ee29336a59d6a19647">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab007d6c51634eb65e4f4f9dab4eb6a8c">doInitialization</a> (Module &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doInitialization - Virtual method overridden by subclasses to do any necessary initialization before any pass is run. <a href="#ab007d6c51634eb65e4f4f9dab4eb6a8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7811985250c75d7e2a244292d615fff">doFinalization</a> (Module &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doFinalization - Virtual method overriden by subclasses to do any necessary clean up after all passes have run. <a href="#ac7811985250c75d7e2a244292d615fff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a061b4c01e9c189208dbfd3c77fdb9a5c">print</a> (raw_ostream &amp;OS, const Module *M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print out the internal state of the pass. <a href="#a061b4c01e9c189208dbfd3c77fdb9a5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a60731eeff800b39fca7280a5a167ae">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac55441198454912f464204d02129b425">createPrinterPass</a> (raw_ostream &amp;OS, const std::string &amp;Banner) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createPrinterPass - Get a <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> appropriate to print the IR this pass operates on (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> or <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>). <a href="#ac55441198454912f464204d02129b425">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a798ee7d328442bd53b66267635788770">assignPassManager</a> (PMStack &amp;, PassManagerType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Each pass is responsible for assigning a pass manager to itself. <a href="#a798ee7d328442bd53b66267635788770">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f61a8789f87816c5f494d42a70f01f">preparePassManager</a> (PMStack &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if available pass managers are suitable for this pass or not. <a href="#aa5f61a8789f87816c5f494d42a70f01f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebb">PassManagerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05cd3cab5ce2e13c7636ef21adef6e8d">getPotentialPassManagerType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return what kind of <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager can manage this pass. <a href="#a05cd3cab5ce2e13c7636ef21adef6e8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2423fcc912a698d4f36c9c9380b53a50">setResolver</a> (AnalysisResolver *AR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisresolver">AnalysisResolver</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a969c082f66671df288441bbad9ca87db">getResolver</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6590d0486104165ca40c7df0707f7b9e">getAnalysisUsage</a> (AnalysisUsage &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a6590d0486104165ca40c7df0707f7b9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb6e74b0f36a0acd1d20149ef088715a">releaseMemory</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#aeb6e74b0f36a0acd1d20149ef088715a">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed. <a href="#aeb6e74b0f36a0acd1d20149ef088715a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03d3a81b1c46aff7c38ef3a6750ba225">getAdjustedAnalysisPointer</a> (AnalysisID ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAdjustedAnalysisPointer - This method is used when a pass implements an analysis interface through multiple inheritance. <a href="#a03d3a81b1c46aff7c38ef3a6750ba225">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablepass">ImmutablePass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae31759fd992cddb1f2d62ab0df85834a">getAsImmutablePass</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a626b77ef8abdfa9f53c697ad129a6e5a">getAsPMDataManager</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ef6f57d4ec869a7f1007aeddf2b169">verifyAnalysis</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#ac8ef6f57d4ec869a7f1007aeddf2b169">verifyAnalysis()</a> - This member can be implemented by a analysis pass to check state of analysis information. <a href="#ac8ef6f57d4ec869a7f1007aeddf2b169">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2f0576ef7c9c4af40e35001c81f4922">dumpPassStructure</a> (unsigned Offset=0)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">AnalysisType *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af94c014e968489e96c7d4353a84ad7f5">getAnalysisIfAvailable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#af94c014e968489e96c7d4353a84ad7f5">getAnalysisIfAvailable&lt;AnalysisType&gt;()</a> - Subclasses use this function to get analysis information that might be around, for example to update it. <a href="#af94c014e968489e96c7d4353a84ad7f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b4a511579939b07831db90c3fc98996">mustPreserveAnalysisID</a> (char &amp;AID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>mustPreserveAnalysisID - This method serves the same function as getAnalysisIfAvailable, but works if you just have an <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>. <a href="#a0b4a511579939b07831db90c3fc98996">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">AnalysisType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> - This function is used by subclasses to get to the analysis information that they claim to use by overriding the getAnalysisUsage function. <a href="#a4863e5e463fb79955269fbf7fbf52b80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">AnalysisType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a560d384c0cef7f62836884fdbbd1fe66">getAnalysis</a> (Function &amp;F, bool *Changed=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> - This function is used by subclasses to get to the analysis information that they claim to use by overriding the getAnalysisUsage function. <a href="#a560d384c0cef7f62836884fdbbd1fe66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">AnalysisType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6613f29d3e54ce175ac33fb9ba264fae">getAnalysisID</a> (AnalysisID PI) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">AnalysisType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2190247edbacb33b4e8a3d409fa2d99e">getAnalysisID</a> (AnalysisID PI, Function &amp;F, bool *Changed=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/analysisresolver">AnalysisResolver</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a904990eb2e4e1c22e464cd1502254bcd">Resolver</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b74f8adddf230d701f86af34a3ce67">PassID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0da955cbb4215ccd3e153c81e415b9d5">PassKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d122b07004ba08f932973d84f90db54">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab174263c400ece13a7278990e102fa6">lookupPassInfo</a> (const void *TI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a992ff669acca94459037cfb1f41cb9dc">lookupPassInfo</a> (StringRef Arg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed7d79d79dffe7368c3d3cdf40dd80e">createPass</a> (AnalysisID ID)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> interface - Implemented by all 'passes'.</p>


<p>Subclass this if you are an interprocedural optimization or you do not fit into any of the more constrained passes described below.</p>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Pass() {#a16baa169d062524be5a6b67609266174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Pass::Pass (<a href="/web-llvm/docs/api/namespaces/llvm/#a0da955cbb4215ccd3e153c81e415b9d5">PassKind</a> K, char &amp; pid)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a11484d56af409b65a713965e27296130">llvm::legacy::FunctionPassManagerImpl::add</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#a34d27e9f9118eddcf4ee25bd89991eb4">llvm::legacy::PassManagerImpl::add</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a452b3946fae687fe6ab129970b5f9c75">anonymous{LegacyPassManager.cpp}::MPPassManager::addLowerLevelRequiredPass</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#af6897bd5a86b78fc12f93cdfb04c9e6a">llvm::CallGraphSCCPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#a480100967dadb2b532fc863b7a4a80a1">llvm::CallGraphSCCPass::CallGraphSCCPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a2b89931791713740e3d5af2fba2a4212">anonymous{LegacyPassManager.cpp}::MPPassManager::createPrinterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#a5377370c7153008ccd1f5c04536051e2">llvm::CallGraphSCCPass::createPrinterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a13fc442533e199f9c395354d7c631049">llvm::legacy::FunctionPassManagerImpl::createPrinterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#ae59d53abe9eb1035e1c37319f925eb29">llvm::legacy::PassManagerImpl::createPrinterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a4e873281b14eed910a1f1d0d2b67b7c9">llvm::LoopPass::createPrinterPass</a>, <a href="#ac55441198454912f464204d02129b425">createPrinterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#af9791a6c4ebc5fc6ab6cd26d739ce965">llvm::RegionPass::createPrinterPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a4efbb82e436e90c66cc02d1630c0c528">anonymous{CallGraphSCCPass.cpp}::CGPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a316f684869eb05f6ea093331e0fa05ae">llvm::legacy::FunctionPassManagerImpl::FunctionPassManagerImpl</a>, <a href="#a6613f29d3e54ce175ac33fb9ba264fae">getAnalysisID</a>, <a href="#a2190247edbacb33b4e8a3d409fa2d99e">getAnalysisID</a>, <a href="#af94c014e968489e96c7d4353a84ad7f5">getAnalysisIfAvailable</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#ab3cbde4fa9325acf3d46bcd036e7fc87">anonymous{CallGraphSCCPass.cpp}::CGPassManager::getAsPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a957b3c9bb2a8b7107fa8d6b1a82598d8">anonymous{LegacyPassManager.cpp}::MPPassManager::getAsPass</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a6bcc5baefb0a24c2a6699b7b71f2b07f">llvm::legacy::FunctionPassManagerImpl::getAsPass</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#a36d2e27c8764b7c8b90d8fab007d6244">llvm::legacy::PassManagerImpl::getAsPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a4b1bfae8468f5272b17dbfa99b21d8cf">anonymous{CallGraphSCCPass.cpp}::CGPassManager::getContainedPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a887a8078ca0523b9494da138a800bb65">anonymous{LegacyPassManager.cpp}::MPPassManager::getOnTheFlyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a4d5799624e630ba03cb9133168951e8a">llvm::LoopPass::LoopPass</a>, <a href="/web-llvm/docs/api/classes/llvm/modulepass/#a723659a08d210f4f566887bda3f9f976">llvm::ModulePass::ModulePass</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a80a9a3415fcb39b9461c78a41b23ab7f">anonymous{LegacyPassManager.cpp}::MPPassManager::MPPassManager</a>, <a href="#af468a2aeb0d98e3dbeda38176ce516d3">operator=</a>, <a href="#ad40d19ce644ec38c52ea00be59016cd5">Pass</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#a99fe001798819fa40f548ade3fde03df">llvm::legacy::PassManagerImpl::PassManagerImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a64960c9ccfcfac1e3562564564c30c51">llvm::RegionPass::RegionPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuremoveincompatiblefunctions-cpp-/amdgpuremoveincompatiblefunctionslegacy/#a5b241b27f5e110855e867787c5b47731">anonymous{AMDGPURemoveIncompatibleFunctions.cpp}::AMDGPURemoveIncompatibleFunctionsLegacy::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#aebf6dc4e02bc6a1f544af50b8921ec2c">llvm::RegionPass::runOnRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/modulepass/#a9f0e05dc5678bc7914700d3d4ff75668">llvm::ModulePass::~ModulePass</a>.</p>

</div>
</div>

### Pass() {#ad40d19ce644ec38c52ea00be59016cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Pass::Pass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> &amp;)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>


<p>Reference <a href="#a16baa169d062524be5a6b67609266174">Pass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Pass() {#abe2fe9b29d21424fe4b410fc8e98606c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass::~Pass ()</td>
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



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#af468a2aeb0d98e3dbeda38176ce516d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass &amp; llvm::Pass::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> &amp;)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>


<p>Reference <a href="#a16baa169d062524be5a6b67609266174">Pass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignPassManager() {#a798ee7d328442bd53b66267635788770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::Pass::assignPassManager (<a href="/web-llvm/docs/api/classes/llvm/pmstack">PMStack</a> &amp;, <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebb">PassManagerType</a>)</td>
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

<p>Each pass is responsible for assigning a pass manager to itself.</p>


<p>PMS is the stack of available pass manager.</p>


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5fb719fc8062d116b93091d9c9addd43">llvm::PMTopLevelManager::schedulePass</a>.</p>

</div>
</div>

### createPrinterPass() {#ac55441198454912f464204d02129b425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Pass * llvm::Pass::createPrinterPass (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Banner)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createPrinterPass - Get a <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> appropriate to print the IR this pass operates on (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> or <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>).</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>


<p>Reference <a href="#a16baa169d062524be5a6b67609266174">Pass</a>.</p>

</div>
</div>

### doFinalization() {#ac7811985250c75d7e2a244292d615fff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Pass::doFinalization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>doFinalization - Virtual method overriden by subclasses to do any necessary clean up after all passes have run.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a5d3dbe08c733714a84c9f79714007327">llvm::FPPassManager::doFinalization</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a58669aeace6a6347402abf3b54d4d239">llvm::LoopPass::runOnLoop</a> and <a href="/web-llvm/docs/api/classes/llvm/regionpass/#aebf6dc4e02bc6a1f544af50b8921ec2c">llvm::RegionPass::runOnRegion</a>.</p>

</div>
</div>

### doInitialization() {#ab007d6c51634eb65e4f4f9dab4eb6a8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Pass::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>doInitialization - Virtual method overridden by subclasses to do any necessary initialization before any pass is run.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a1ea063b9aef63a724f2f14b2e8d2be0e">llvm::FPPassManager::doInitialization</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#a9b33d70eb77e44e553ac5aa79a3da589">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp/#acb4ccb1e3e3e40a5db92d467a97369c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a58669aeace6a6347402abf3b54d4d239">llvm::LoopPass::runOnLoop</a> and <a href="/web-llvm/docs/api/classes/llvm/regionpass/#aebf6dc4e02bc6a1f544af50b8921ec2c">llvm::RegionPass::runOnRegion</a>.</p>

</div>
</div>

### dump() {#a1a60731eeff800b39fca7280a5a167ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pass::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

### dumpPassStructure() {#ad2f0576ef7c9c4af40e35001c81f4922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pass::dumpPassStructure (unsigned Offset=0)</td>
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



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#aa58716ef5ab4c044f1f90f257bf91e6a">llvm::PMTopLevelManager::dumpPasses</a> and <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a7c9d902501ce3b0da29040e896cc4a9e">anonymous{LegacyPassManager.cpp}::MPPassManager::dumpPassStructure</a>.</p>

</div>
</div>

### getAdjustedAnalysisPointer() {#a03d3a81b1c46aff7c38ef3a6750ba225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * Pass::getAdjustedAnalysisPointer (<a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> ID)</td>
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

<p>getAdjustedAnalysisPointer - This method is used when a pass implements an analysis interface through multiple inheritance.</p>


<p>If needed, it should override this to adjust the this pointer as needed for the specified pass info.</p>


<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="#a6613f29d3e54ce175ac33fb9ba264fae">getAnalysisID</a>, <a href="#a2190247edbacb33b4e8a3d409fa2d99e">getAnalysisID</a> and <a href="#af94c014e968489e96c7d4353a84ad7f5">getAnalysisIfAvailable</a>.</p>

</div>
</div>

### getAnalysis() {#a4863e5e463fb79955269fbf7fbf52b80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisType &amp; llvm::Pass::getAnalysis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> - This function is used by subclasses to get to the analysis information that they claim to use by overriding the getAnalysisUsage function.</p>

<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a6613f29d3e54ce175ac33fb9ba264fae">getAnalysisID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopalign-cpp-/hexagonloopalign/#a49530a2f7101146544b49c809bc2e035">anonymous{HexagonLoopAlign.cpp}::HexagonLoopAlign::attemptToBalignSmallLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5f32c10b46f4e956f21552b0984ae68f">llvm::AsmPrinter::emitBBAddrMapSection</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a6f7e57c8c003253b7da93520af8ef8c2">llvm::RegBankSelect::init</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aafadfc35831cdb7ef3dd321cc28f1208">llvm::SelectionDAGISel::initializeAnalysisResults</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceanalysiswrapperpass/#a593db0c680559cb282b2caf56eae0f7b">llvm::DependenceAnalysisWrapperPass::print</a>, <a href="/web-llvm/docs/api/classes/amdgpuannotateuniformvalueslegacy/#a1d333068678281eda86396cae068d247">AMDGPUAnnotateUniformValuesLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/amdgpulatecodegenpreparelegacy/#a37af73d7a2d2cfc4e3fd009ecc167207">AMDGPULateCodeGenPrepareLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64falkorhwpffix-cpp-/falkormarkstridedaccesseslegacy/#af3cbd5567c4155fd6d9c25e64fe95975">anonymous{AArch64FalkorHWPFFix.cpp}::FalkorMarkStridedAccessesLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuatomicoptimizer-cpp-/amdgpuatomicoptimizer/#a239d03ce853ea6b2a72debc452590218">anonymous{AMDGPUAtomicOptimizer.cpp}::AMDGPUAtomicOptimizer::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepare/#af6170254ef76a5d14783363b7862d85b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepare::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/amdgpulowerkernelarguments/#a0b9c316444e149083f3f670f452771c7">anonymous{AMDGPULowerKernelArguments.cpp}::AMDGPULowerKernelArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotealloca-cpp-/amdgpupromotealloca/#a415c2fe7bb80ea1eec2885cd51136119">anonymous{AMDGPUPromoteAlloca.cpp}::AMDGPUPromoteAlloca::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotealloca-cpp-/amdgpupromoteallocatovector/#a4db28e896fe88fa692c280aff5fdaa13">anonymous{AMDGPUPromoteAlloca.cpp}::AMDGPUPromoteAllocaToVector::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotekernelarguments-cpp-/amdgpupromotekernelarguments/#aed2f3cb3110bf67f7b36f6db0863b856">anonymous{AMDGPUPromoteKernelArguments.cpp}::AMDGPUPromoteKernelArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteundefforphi-cpp-/amdgpurewriteundefforphilegacy/#ad0b2e5aeb5c1fc55f6614e0c8c9cbfba">anonymous{AMDGPURewriteUndefForPHI.cpp}::AMDGPURewriteUndefForPHILegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodes/#a4b2cf942a6fb0d8955330826f161d4c7">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodes::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/armparalleldsp/#ae40feb69d50495a1f334abd82dd64e87">anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenpreparelegacypass/#a247a6373f131cbd580f94dd0483551b2">anonymous{CodeGenPrepare.cpp}::CodeGenPrepareLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinglegacypass/#a2cc06a96e878ac5df1fe5ddb5deb5114">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-constanthoisting-cpp-/constanthoistinglegacypass/#a6d8190a379520af73a22bb1f14b73f1f">anonymous{ConstantHoisting.cpp}::ConstantHoistingLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-dce-cpp-/dcelegacypass/#ab8dd233306300017af87428129a0878a">anonymous{DCE.cpp}::DCELegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfehprepare-cpp-/dwarfehpreparelegacypass/#a4f41301e138ffeaa12761bf5e94692e8">anonymous{DwarfEHPrepare.cpp}::DwarfEHPrepareLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilresourceaccess-cpp-/dxilresourceaccesslegacy/#aa702425859c9ca8980ea163501ec5523">anonymous{DXILResourceAccess.cpp}::DXILResourceAccessLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlycse-cpp-/earlycselegacycommonpass/#a4e17dc21414f3e03a75d63ad94436ce6">anonymous{EarlyCSE.cpp}::EarlyCSELegacyCommonPass&lt; UseMemorySSA &gt;::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandlargedivrem-cpp-/expandlargedivremlegacypass/#aa7d7ea9e2d32b1837b3826c0b8ccd9ee">anonymous{ExpandLargeDivRem.cpp}::ExpandLargeDivRemLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandlargefpconvert-cpp-/expandlargefpconvertlegacypass/#acb19b315a948eddca959776d612d55bc">anonymous{ExpandLargeFpConvert.cpp}::ExpandLargeFpConvertLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/expandmemcmplegacypass/#a744c97bd2b03802d78ec941f5c7b9d16">anonymous{ExpandMemCmp.cpp}::ExpandMemCmpLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandreductions-cpp-/expandreductions/#a5fb6c8ae986cf80379e477fdcd059d79">anonymous{ExpandReductions.cpp}::ExpandReductions::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-fixirreducible-cpp-/fixirreducible/#a8d14bed3c1d3c5f9cd62aa160cc02d70">anonymous{FixIrreducible.cpp}::FixIrreducible::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-flattencfgpass-cpp-/flattencfglegacypass/#ab54e7e34d1b73ad5e2d40fdb310858f5">anonymous{FlattenCFGPass.cpp}::FlattenCFGLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/lowerintrinsics/#af8839af043a33c29a875d4dddb11a095">anonymous{GCRootLowering.cpp}::LowerIntrinsics::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hardwareloops-cpp-/hardwareloopslegacy/#a090edab056118e7dae834ce8e11e8157">anonymous{HardwareLoops.cpp}::HardwareLoopsLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncommongep-cpp-/hexagoncommongep/#acbc127dd5146e3f07d1b0da5eaca7356">anonymous{HexagonCommonGEP.cpp}::HexagonCommonGEP::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenextract-cpp-/hexagongenextract/#aa0a19a5e8390a91b75bdc895f04e2b42">anonymous{HexagonGenExtract.cpp}::HexagonGenExtract::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombinelegacy/#a4fc007a48e77822e30e0c6080aa5cae1">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombineLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-inferaddressspaces-cpp-/inferaddressspaces/#ab8fd0d1d5b31cb7a1a069e588343c67a">anonymous{InferAddressSpaces.cpp}::InferAddressSpaces::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-instsimplifypass-cpp-/instsimplifylegacypass/#a3b5ea09d64637ac1796d3e3147efc69f">anonymous{InstSimplifyPass.cpp}::InstSimplifyLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-interleavedaccesspass-cpp-/interleavedaccess/#a1a0ee1417af452f2512df6359fbe248a">anonymous{InterleavedAccessPass.cpp}::InterleavedAccess::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/interleavedloadcombine/#adef67ae3266f48eacb955c2d515737ef">anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombine::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-lcssa-cpp-/lcssawrapperpass/#ad6bef3a04cd1005ebd2040194d8548a2">anonymous{LCSSA.cpp}::LCSSAWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loadstorevectorizer-cpp-/loadstorevectorizerlegacypass/#aded951af0d41cd9dd8c76609c67ca771">anonymous{LoadStoreVectorizer.cpp}::LoadStoreVectorizerLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdataprefetch-cpp-/loopdataprefetchlegacypass/#a2039a56cbb67bf26db99176d064c9be8">anonymous{LoopDataPrefetch.cpp}::LoopDataPrefetchLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopsimplify-cpp-/loopsimplify/#ae6b772642c62e8f8d03d9a75148b12a2">anonymous{LoopSimplify.cpp}::LoopSimplify::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowerswitch-cpp-/lowerswitchlegacypass/#a8345e59cbfe10219f49fb04405952871">anonymous{LowerSwitch.cpp}::LowerSwitchLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinemoduleinfo-cpp-/freemachinefunction/#a8214aae5e0ab52ed3978bbba9265778b">anonymous{MachineModuleInfo.cpp}::FreeMachineFunction::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-mem2reg-cpp-/promotelegacypass/#a44e2a30df5d10705e2a1a64790ac40a6">anonymous{Mem2Reg.cpp}::PromoteLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/mergeicmpslegacypass/#a49d9ddefdd0a53fe9bf060228c87bbb9">anonymous{MergeICmps.cpp}::MergeICmpsLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvegatherscatterlowering-cpp-/mvegatherscatterlowering/#ab630c640ea64fe3d2d7a1733d6bf7dc2">anonymous{MVEGatherScatterLowering.cpp}::MVEGatherScatterLowering::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvelaneinterleavingpass-cpp-/mvelaneinterleaving/#a6d679dfc2baa424f4dfe87212d2c8ca9">anonymous{MVELaneInterleavingPass.cpp}::MVELaneInterleaving::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-naryreassociate-cpp-/naryreassociatelegacypass/#acf8485db359e7da3ae1188cfb3dfe092">anonymous{NaryReassociate.cpp}::NaryReassociateLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxloweraggrcopies-cpp-/nvptxloweraggrcopies/#a1e7cbd0783ad9cbbfdf85b5dbaba57f8">anonymous{NVPTXLowerAggrCopies.cpp}::NVPTXLowerAggrCopies::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontractlegacypass/#ab643320efd2f4aacb0288787aa68ad5a">anonymous{ObjCARCContract.cpp}::ObjCARCContractLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-partiallyinlinelibcalls-cpp-/partiallyinlinelibcallslegacypass/#a8fad2b25e12f4c61e0494fffc8dab1e0">anonymous{PartiallyInlineLibCalls.cpp}::PartiallyInlineLibCallsLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-placesafepoints-cpp-/placebackedgesafepointslegacypass/#affd1850125d61f01b3542b64a7d9e6fc">anonymous{PlaceSafepoints.cpp}::PlaceBackedgeSafepointsLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcloopinstrformprep-cpp-/ppcloopinstrformprep/#a8d1182a1362bef2929d09ce054e8fa5d">anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvcodegenprepare-cpp-/riscvcodegenprepare/#acec185283c75c347d2768c112fd40653">anonymous{RISCVCodeGenPrepare.cpp}::RISCVCodeGenPrepare::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvgatherscatterlowering-cpp-/riscvgatherscatterlowering/#a463122d7144f83fbbc69c99609fd2599">anonymous{RISCVGatherScatterLowering.cpp}::RISCVGatherScatterLowering::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvzacasabifix-cpp-/riscvzacasabifix/#aa90e78ff1ab16a5e5e2ad8a470defdbe">anonymous{RISCVZacasABIFix.cpp}::RISCVZacasABIFix::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/safepointirverifier/#abd707c03eccdccbcdbb0c4844bd66852">anonymous{SafepointIRVerifier.cpp}::SafepointIRVerifier::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestacklegacypass/#a7cac2bf189a71c58d1514aaaac25414a">anonymous{SafeStack.cpp}::SafeStackLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizemaskedmemintrin-cpp-/scalarizemaskedmemintrinlegacypass/#a7d2ab592f7a307c23332fd688694d557">anonymous{ScalarizeMaskedMemIntrin.cpp}::ScalarizeMaskedMemIntrinLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizerlegacypass/#a7180234aab23ce013ef3fda8bc49774c">anonymous{Scalarizer.cpp}::ScalarizerLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-separateconstoffsetfromgep-cpp-/separateconstoffsetfromgeplegacypass/#a48218a9855ccf2accfd3d6bdee172e00">anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEPLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifycfgpass-cpp-/cfgsimplifypass/#a3d3865809388cc37e85b5fba71e35023">anonymous{SimplifyCFGPass.cpp}::CFGSimplifyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sink-cpp-/sinkinglegacypass/#a0a0c8152f4385081cfc1aad11c77a87d">anonymous{Sink.cpp}::SinkingLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-speculativeexecution-cpp-/speculativeexecutionlegacypass/#ab9f11c56fde815d4c5b98350f06fa140">anonymous{SpeculativeExecution.cpp}::SpeculativeExecutionLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroalegacypass/#a8e87a8ac1e3d62aaa253240fc597f797">anonymous{SROA.cpp}::SROALegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-straightlinestrengthreduce-cpp-/straightlinestrengthreducelegacypass/#a5a9e13a6bfcbe1c44acb0418c111e1cd">anonymous{StraightLineStrengthReduce.cpp}::StraightLineStrengthReduceLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemztdc-cpp-/systemztdcpass/#a297c01ed88bcbeaac178adb0ff9e497f">anonymous{SystemZTDC.cpp}::SystemZTDCPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-tailrecursionelimination-cpp-/tailcallelim/#abcc0dcce78ac4618e3b3e70df45e3539">anonymous{TailRecursionElimination.cpp}::TailCallElim::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-typepromotion-cpp-/typepromotionlegacy/#a60e7de3a73e4cfa9c1b3961a3d435f84">anonymous{TypePromotion.cpp}::TypePromotionLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-unifyloopexits-cpp-/unifyloopexitslegacypass/#a414a4f7334ec69f73a1b1cbe9de8f52a">anonymous{UnifyLoopExits.cpp}::UnifyLoopExitsLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsicslegacypass/#a3676b694f0f141994877ccf4564027ef">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsicsLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxtypelegacypass/#a63b5e6f11338cd1363537097457e4265">anonymous{X86LowerAMXType.cpp}::X86LowerAMXTypeLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresultswrapperpass/#a47ee17feac90f644d8afe91156ae9ddf">llvm::AAResultsWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaawrapperpass/#a45b820022c591db55806ce53d8b9de65">llvm::BasicAAWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfowrapperpass/#a83a7b5557444da82ac7406712c89188a">llvm::BlockFrequencyInfoWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfowrapperpass/#ad32017b091b9ec5d6d88187d44ede817">llvm::BranchProbabilityInfoWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceanalysiswrapperpass/#a1d7296e688ca102773f2c074d64f56bf">llvm::DependenceAnalysisWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierwrapperpass/#a5570bd9f15232ec8b2685b2f2b1c431d">llvm::DominanceFrontierWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsprinterwrapperpass/#a13f01c501d30959accca2ddeec59fe10">llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsviewerwrapperpass/#a2d6db797796df0405b03c47a31340cc9">llvm::DOTGraphTraitsViewerWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/gvn/gvnlegacypass/#ab5d98be3e1b14ce50e328b3712b72b7f">llvm::gvn::GVNLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncombiningpass/#ab64b7e967adeebc9bacc8abd8ddce0c8">llvm::InstructionCombiningPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyblockfrequencyinfopass/#a770f30d62e60c34453e8f2818a244686">llvm::LazyBlockFrequencyInfoPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lazybranchprobabilityinfopass/#a42914c7e7a1f7363e421f7ce30673f5d">llvm::LazyBranchProbabilityInfoPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfowrapperpass/#a154ac41453d6258a3b9f9895ba7ae35d">llvm::LazyValueInfoWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfowrapperpass/#aea27493f9f8413433bab89a007ced708">llvm::LoopInfoWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependencewrapperpass/#a28b03127a71ed0d48ff09af46631fa71">llvm::MemoryDependenceWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssawrapperpass/#a4c858dddb5beb0ab1b09ea1f03befcee">llvm::MemorySSAWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitterwrapperpass/#a645560c675406ac4567a4cb46bbe1824">llvm::OptimizationRemarkEmitterWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfopass/#a0f190fc7ae16274a25436aef02eba40c">llvm::RegionInfoPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/regtomemwrapperpass/#aed9a7685d9b8b8775099d95d27898b74">llvm::RegToMemWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/replacewithvecliblegacy/#a86519aa4756de655d9faee188cf248b9">llvm::ReplaceWithVeclibLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a8fcc78c1f34a2d1f636b5880db631439">llvm::RGPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolutionwrapperpass/#a2b0012b09a95be3e1eb70ce22f14e029">llvm::ScalarEvolutionWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaawrapperpass/#a4184e96b12cd15b17b812455bd593be2">llvm::SCEVAAWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvconvergenceregionanalysiswrapperpass/#a61f563a2fee2bb13de295defc8e5393b">llvm::SPIRVConvergenceRegionAnalysisWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#af427a7ace1ffeca02c00f80b3c25d047">llvm::SPIRVMergeRegionExitTargets::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotector/#ad6088af9690051701647680fd467ed97">llvm::StackProtector::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyinfowrapperpass/#a379237123db0caefb5a42572d85cf0a5">llvm::StackSafetyInfoWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/uniformityinfowrapperpass/#a1351c9b8849ef3ef40c8ac58d0dfee79">llvm::UniformityInfoWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/siannotatecontrolflowlegacy/#a144e57d493e0a42780bde31ea9427ad0">SIAnnotateControlFlowLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopidiomrecognition-cpp-/hexagonloopidiomrecognizelegacypass/#ac9efac4b95f0cab03f789653b1a5e1aa">anonymous{HexagonLoopIdiomRecognition.cpp}::HexagonLoopIdiomRecognizeLegacyPass::runOnLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-licm-cpp-/legacylicmpass/#adfe3debfb083aea25b34a2f09c1b3132">anonymous{LICM.cpp}::LegacyLICMPass::runOnLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopunrollpass-cpp-/loopunroll/#a176b0f7a9dc90d996cae2767b3aea0ca">anonymous{LoopUnrollPass.cpp}::LoopUnroll::runOnLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/moduloscheduletest/#aff71500f971dc1f796d293a1450dc6b0">anonymous{ModuloSchedule.cpp}::ModuloScheduleTest::runOnLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvetailpredication-cpp-/mvetailpredication/#a7b878614c194557b9109ce592f817861">anonymous{MVETailPredication.cpp}::MVETailPredication::runOnLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/ivuserswrapperpass/#a4b80c09a916a8a8db95fa16817df4460">llvm::IVUsersWrapperPass::runOnLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#ab7fe307733ec8e501f180b78fe879980">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/aarch64conditionalcompares/#af7b7982c58340c2b9b066e30a4fd558f">anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#a1ee52a66badadfe0d31d88d614305f41">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64falkorhwpffix-cpp-/falkorhwpffix/#a8db91d643058fb5ebe6a3c5fed12f67a">anonymous{AArch64FalkorHWPFFix.cpp}::FalkorHWPFFix::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a34e994dfc31c367cdb33d1f78ba747d7">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a861f713b12304772bfbadc6051ca3cc7">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64postcoalescerpass-cpp-/aarch64postcoalescer/#af7c68f72faddb47f4a574fbd77f55806">anonymous{AArch64PostCoalescerPass.cpp}::AArch64PostCoalescer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64storepairsuppress-cpp-/aarch64storepairsuppress/#ab876191f2b64955413fe0423a672c3b2">anonymous{AArch64StorePairSuppress.cpp}::AArch64StorePairSuppress::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/amdgpuglobaliseldivergencelowering/#a13bb7baebeca659ef9eacc195d86c082">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::AMDGPUGlobalISelDivergenceLowering::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbanklegalize-cpp-/amdgpuregbanklegalize/#ad1210df2e489436f417f18f10180ea44">anonymous{AMDGPURegBankLegalize.cpp}::AMDGPURegBankLegalize::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbankselect-cpp-/amdgpuregbankselect/#abceb824dea15a0f50ab19fc7126f618f">anonymous{AMDGPURegBankSelect.cpp}::AMDGPURegBankSelect::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcoptaddrmode-cpp-/arcoptaddrmode/#ad3c2bac5f197edc2768414bd15250487">anonymous{ARCOptAddrMode.cpp}::ARCOptAddrMode::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armconstantislandpass-cpp-/armconstantislands/#aaf4297850ccff6052205f45bc2ba2f87">anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armfixcortexa57aes1742098pass-cpp-/armfixcortexa57aes1742098/#a43d2faff17080847be1128de33a8fe54">anonymous{ARMFixCortexA57AES1742098Pass.cpp}::ARMFixCortexA57AES1742098::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-armloadstoreoptimizer-cpp-/armpreallocloadstoreopt/#a96eb57802bc641c0bb2dc3459fd4b962">anonymous{ARMLoadStoreOptimizer.cpp}::ARMPreAllocLoadStoreOpt::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/armlowoverheadloops/#a4b7c398733988f966d29c1873804320c">anonymous{ARMLowOverheadLoops.cpp}::ARMLowOverheadLoops::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifconverterlegacy/#ab25fcd369020ce14b4cec3eefa04936c">anonymous{EarlyIfConversion.cpp}::EarlyIfConverterLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifpredicator/#aa90706243c94cf284f209044cce20578">anonymous{EarlyIfConversion.cpp}::EarlyIfPredicator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#a98d8aaed2e429cfec371c300cb8244c2">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnpreraoptimizations-cpp-/gcnpreraoptimizations/#a579b1d5abab1d9f7ada407f49d3a56a1">anonymous{GCNPreRAOptimizations.cpp}::GCNPreRAOptimizations::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis/#a82b0862f6017d073489a4971d43ecf3a">anonymous{GCRootLowering.cpp}::GCMachineCodeAnalysis::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a4a8e77e619417aa3e56a24caf68d6820">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a50a95c05ee7d95c49a8c65c49046e3ec">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonearlyifconv-cpp-/hexagonearlyifconversion/#ad77c439037ce7afbf19bafdc4927d4cb">anonymous{HexagonEarlyIfConv.cpp}::HexagonEarlyIfConversion::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonexpandcondsets-cpp-/hexagonexpandcondsets/#a4552c648a6db6ec6bff6ed09de4136d7">anonymous{HexagonExpandCondsets.cpp}::HexagonExpandCondsets::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongeninsert-cpp-/hexagongeninsert/#a37b356976dd89ab9dc3212616667218e">anonymous{HexagonGenInsert.cpp}::HexagonGenInsert::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonhardwareloops-cpp-/hexagonhardwareloops/#a227e7ddfafd6bce13cfb1473136e8230">anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloadstorewidening-cpp-/hexagonloadwidening/#a9e42da81e4f2dc0432ee7d615420d07f">anonymous{HexagonLoadStoreWidening.cpp}::HexagonLoadWidening::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloadstorewidening-cpp-/hexagonstorewidening/#a70e2faddefd0484ebf9d2dfa47007678">anonymous{HexagonLoadStoreWidening.cpp}::HexagonStoreWidening::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonoptaddrmode-cpp-/hexagonoptaddrmode/#ad07a6a329e102fb53ef087cbba07c002">anonymous{HexagonOptAddrMode.cpp}::HexagonOptAddrMode::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonrdfopt-cpp-/hexagonrdfopt/#acb675de67baa3aed372fdf62b440c866">anonymous{HexagonRDFOpt.cpp}::HexagonRDFOpt::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonsplitdouble-cpp-/hexagonsplitdoubleregs/#af1d2ad2c8e51ccc9c2539735ad482dfa">anonymous{HexagonSplitDouble.cpp}::HexagonSplitDoubleRegs::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvliwpacketizer-cpp-/hexagonpacketizer/#a84914fb49b671ec22a8cb348237182c7">anonymous{HexagonVLIWPacketizer.cpp}::HexagonPacketizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ifconversion-cpp-/ifconverter/#abff4179252123a7710b2fa134be3f9d6">anonymous{IfConversion.cpp}::IfConverter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-implicitnullchecks-cpp-/implicitnullchecks/#adfa9682269920db0fdac767478243124">anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a1f0291b83febf5c94491d76bf5236799">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacementstats/#a8305613a915321631b70e8f26e2d55d6">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacementStats::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecombiner-cpp-/machinecombiner/#aaee7889b0d1357a4eb765cecb57fdf92">anonymous{MachineCombiner.cpp}::MachineCombiner::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecse-cpp-/machinecselegacy/#a25a61f0786a4d1ad0472aaedf92f1ac1">anonymous{MachineCSE.cpp}::MachineCSELegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecycleanalysis-cpp-/machinecycleinfoprinterpass/#a244db25a09b3907d84c4839019c1648a">anonymous{MachineCycleAnalysis.cpp}::MachineCycleInfoPrinterPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">anonymous{MachineScheduler.cpp}::MachineScheduler::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#ab1dc85fd08ff7aa2a4057683e7a4dc8f">anonymous{MachineScheduler.cpp}::PostMachineScheduler::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/machinesinking/#af56efb8509ab5b039fe9dcf0c4f5eccd">anonymous{MachineSink.cpp}::MachineSinking::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineuniformityanalysis-cpp-/machineuniformityinfoprinterpass/#ad10cf36964de198af4483e2e9d103089">anonymous{MachineUniformityAnalysis.cpp}::MachineUniformityInfoPrinterPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsmoduleiseldagtodag-cpp-/mipsmoduledagtodagisel/#ad2dfa038f4571552b456516bbe19131c">anonymous{MipsModuleISelDAGToDAG.cpp}::MipsModuleDAGToDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsoptimizepiccall-cpp-/optimizepiccall/#af8fb60c334fa1c7571459b115762b09e">anonymous{MipsOptimizePICCall.cpp}::OptimizePICCall::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsprelegalizercombiner-cpp-/mipsprelegalizercombiner/#a19ada2e0d9fd32ef5cafea3f4581bab0">anonymous{MipsPreLegalizerCombiner.cpp}::MipsPreLegalizerCombiner::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-mirprintingpass-cpp-/mirprintingpass/#a2a94e998309a4c9a1621cf510866812e">anonymous{MIRPrintingPass.cpp}::MIRPrintingPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/moduloscheduletest/#ae99b20adac63b661778529c880baec14">anonymous{ModuloSchedule.cpp}::ModuloScheduleTest::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvetpandvptoptimisationspass-cpp-/mvetpandvptoptimisations/#a583bacd9cc15714c083c599b7e45cbb6">anonymous{MVETPAndVPTOptimisationsPass.cpp}::MVETPAndVPTOptimisations::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizerlegacy/#abd22f1c3f5b46ab25e3ee84ecfa57093">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizerLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/postrascheduler/#a73244099672dcbc8e1f1a034f957a438">anonymous{PostRASchedulerList.cpp}::PostRAScheduler::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcctrloops-cpp-/ppcctrloops/#a72b4857732797214a988ddaf2a7c6421">anonymous{PPCCTRLoops.cpp}::PPCCTRLoops::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcctrloopsverify-cpp-/ppcctrloopsverify/#a77d7469acf0eff421a41b7f991ea5724">anonymous{PPCCTRLoopsVerify.cpp}::PPCCTRLoopsVerify::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#a4d6db0f25025bd365ee0251e88bda4fd">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a18192ed7893e8738ddd38e7f75bb3bf7">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizer/#abd55d929e000dd3a109e8e8325e811bc">anonymous{R600Packetizer.cpp}::R600Packetizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a94391e15de6cfad5cf6522641d8b7f95">anonymous{RegAllocBasic.cpp}::RABasic::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/regallocpbqp/#a82bfae004546453f47c217784928e0a5">anonymous{RegAllocPBQP.cpp}::RegAllocPBQP::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#aa408ab9747b8ce0bd0a81465c10e8f29">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollectorlegacy/#a3fdc2f8a0f56306cb97f5d964813340f">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollectorLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfopropagate-cpp-/regusageinfopropagationlegacy/#a2de0bf3d20143c648a57005ee26555d1">anonymous{RegUsageInfoPropagate.cpp}::RegUsageInfoPropagationLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-renameindependentsubregs-cpp-/renameindependentsubregs/#a5a7168c10662c11aea9894ec2b7481bb">anonymous{RenameIndependentSubregs.cpp}::RenameIndependentSubregs::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvvloptimizer-cpp-/riscvvloptimizer/#aef0982e6aa98fe02059f7f1a24d0de65">anonymous{RISCVVLOptimizer.cpp}::RISCVVLOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopieslegacy/#afa68e5327e51ad81a9188788ada95c62">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopiesLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silatebranchlowering-cpp-/silatebranchlowering/#a2f96cc01100e6467c2b124371cf417c0">anonymous{SILateBranchLowering.cpp}::SILateBranchLowering::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloadstoreoptimizer-cpp-/siloadstoreoptimizerlegacy/#a9645c3e7e0efef967704ae1dbd7ecb29">anonymous{SILoadStoreOptimizer.cpp}::SILoadStoreOptimizerLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspillslegacy/#a39b4f2fe5e2c2535293788e161357031">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpillsLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemorylegalizer/#a599c4517601e4b05d04b3093a7968a91">anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmaskingprera-cpp-/sioptimizeexecmaskingprera/#a7e75a4f6568424bf0940a7c509a6d18c">anonymous{SIOptimizeExecMaskingPreRA.cpp}::SIOptimizeExecMaskingPreRA::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverangelegacy/#afc439d8fd92fc2513ddcf060ad04c896">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRangeLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipreallocatewwmregs-cpp-/sipreallocatewwmregslegacy/#aab18d5ce221151f612364e18c2fdb47b">anonymous{SIPreAllocateWWMRegs.cpp}::SIPreAllocateWWMRegsLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siwholequadmode-cpp-/siwholequadmode/#ae53d8e40bdcb428165b0243af4be1dcc">anonymous{SIWholeQuadMode.cpp}::SIWholeQuadMode::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackcoloring-cpp-/stackcoloringlegacy/#aebba3fc564ac51598f1af02c540bc1ed">anonymous{StackColoring.cpp}::StackColoringLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a208684dda693662f834195df68d843f8">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackslotcoloring-cpp-/stackslotcoloring/#ad072a4f9fd33459ffa629f881b707cd2">anonymous{StackSlotColoring.cpp}::StackSlotColoring::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzldcleanup-cpp-/systemzldcleanup/#a5ca5f9f4a18fb64aa67be317c3a963d0">anonymous{SystemZLDCleanup.cpp}::SystemZLDCleanup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-tailduplication-cpp-/tailduplicatebaselegacy/#a78a8906bfe5ee3db7d500fa09d238b8b">anonymous{TailDuplication.cpp}::TailDuplicateBaseLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-virtregmap-cpp-/virtregrewriter/#a4268652d87bd14a2b124f863ead3025f">anonymous{VirtRegMap.cpp}::VirtRegRewriter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblymemintrinsicresults-cpp-/webassemblymemintrinsicresults/#ad27c15e1132658396d31be906fa54cd7">anonymous{WebAssemblyMemIntrinsicResults.cpp}::WebAssemblyMemIntrinsicResults::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86avoidstoreforwardingblocks-cpp-/x86avoidsfbpass/#a42cae0fd23182f6d2b4d4368a4ec21c3">anonymous{X86AvoidStoreForwardingBlocks.cpp}::X86AvoidSFBPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86cmovconversion-cpp-/x86cmovconverterpass/#a2b90fb87402f7118da2019ae5b84f0b1">anonymous{X86CmovConversion.cpp}::X86CmovConverterPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupbwinsts-cpp-/fixupbwinstpass/#a6d249baaf63b718978cd27d27731a57b">anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupleas-cpp-/fixupleapass/#a12fbadb122d7381f6222cab24d3150e5">anonymous{X86FixupLEAs.cpp}::FixupLEAPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86floatingpoint-cpp-/fps/#aaf871b359dfbd7ec0d35819bf8d089a1">anonymous{X86FloatingPoint.cpp}::FPS::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/ldtlscleanup/#a0f3b4e5e968c5ab89944989495e68799">anonymous{X86InstrInfo.cpp}::LDTLSCleanup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loadvalueinjectionloadhardening-cpp-/x86loadvalueinjectionloadhardeningpass/#a54e4ad32ffe88b1a55da7ca8c9d90521">anonymous{X86LoadValueInjectionLoadHardening.cpp}::X86LoadValueInjectionLoadHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86optimizeleas-cpp-/x86optimizeleapass/#aa1c0ec05b137d32e33005eaf6649afd3">anonymous{X86OptimizeLEAs.cpp}::X86OptimizeLEAPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86padshortfunction-cpp-/padshortfunc/#a396d8bcf59a3557450bf806512b47e3d">anonymous{X86PadShortFunction.cpp}::PadShortFunc::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisellegacy/#af1dd57979f0af9109ee912b38c3a20e5">llvm::AMDGPUDAGToDAGISelLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a874997c646d9fb27b6ccbaf2f594511d">llvm::ARMBlockPlacement::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/breakfalsedeps/#ad21a053369c2ee6c4adef784d6af900e">llvm::BreakFalseDeps::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executiondomainfix/#aa90dd7f08ca467a5d6dc3215fb98ee51">llvm::ExecutionDomainFix::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a98e4a98a0db786235d78fce93ad4a72f">llvm::InstructionSelect::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a356f9de405c2904f7ad73659a2f378a0">llvm::Legalizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariableswrapperlegacy/#ad1bc4751b78528b7168b32a4428b98af">llvm::LiveDebugVariablesWrapperLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalswrapperpass/#a3d479ab94b2854cdaa3edb7ecbba6860">llvm::LiveIntervalsWrapperPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrixwrapperlegacy/#af5f63d36511130a0808cfac5c3c0be2c">llvm::LiveRegMatrixWrapperLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfowrapperpass/#a3c01eed31ef82cfdef7a195dc82512b7">llvm::MachineBlockFrequencyInfoWrapperPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinedominancefrontier/#a7adff5b591287262995012ab54c12c08">llvm::MachineDominanceFrontier::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfowrapperpass/#a5f667eeaa88a04357ccac3476ab576a4">llvm::MachineLoopInfoWrapperPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitterpass/#abaf47a746ff0c09836ffb448d4287287">llvm::MachineOptimizationRemarkEmitterPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepipeliner/#a292abfa5a62a1fd7b53592085a48e651">llvm::MachinePipeliner::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass/#a4eb11177ec8af97bacb6cea7fd9fe9df">llvm::MachineRegionInfoPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetricswrapperpass/#a5679f7ecb69427bd4889526a56168aab">llvm::MachineTraceMetricsWrapperPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineuniformityanalysispass/#a991dc8c24011fbe82989fbc943caa7dd">llvm::MachineUniformityAnalysisPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a9f1a58845384add66455538dc8725392">llvm::RAGreedy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/thunkinserterpass/#a6fd7809c000f7c16bc390bce02924a7e">llvm::ThunkInserterPass&lt; Inserters &gt;::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyexceptioninfo/#a2997d996c3268cfbd8751029c819e58b">llvm::WebAssemblyExceptionInfo::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/siloweri1copieslegacy/#aef90df953e70edbf33f185e2a525ac0c">SILowerI1CopiesLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/staticdatasplitter/#a7fedae3a951c1e76f4d85d6bc6fd5d88">StaticDataSplitter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-alwaysinliner-cpp-/alwaysinlinerlegacypass/#aa485a64e0f544b4f5119d86583097b68">anonymous{AlwaysInliner.cpp}::AlwaysInlinerLegacyPass::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/amdgpulowerbufferfatpointers/#a47139b5ce0b433221df6d3598993d4ab">anonymous{AMDGPULowerBufferFatPointers.cpp}::AMDGPULowerBufferFatPointers::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermoduleldslegacy/#a4155d1d229b762266499e2e0f34ca42b">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDSLegacy::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerldslegacy/#acfe402ed12ef3aa3f9b6b75a60baeb33">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDSLegacy::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a1f2ac01d6e79a5eff1623936ef49847c">anonymous{CallGraphSCCPass.cpp}::CGPassManager::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphdotprinter/#a2ab234950b299930fe1a4d5b9f68e55a">anonymous{CallPrinter.cpp}::CallGraphDOTPrinter::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphviewer/#a0ab22936fc8a48301af3e72a814bdd7c">anonymous{CallPrinter.cpp}::CallGraphViewer::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/dxiloploweringlegacy/#a18ed0eced9115f0c75c4e093f4d06d02">anonymous{DXILOpLowering.cpp}::DXILOpLoweringLegacy::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilprepare-cpp-/dxilpreparemodule/#a6bcc20d3d2e7ec05e259efe87ba8fd0c">anonymous{DXILPrepare.cpp}::DXILPrepareModule::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilprettyprinter-cpp-/dxilprettyprinterlegacy/#aeaafee5be83e13663d74d9b75bdcd4f3">anonymous{DXILPrettyPrinter.cpp}::DXILPrettyPrinterLegacy::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiltranslatemetadata-cpp-/dxiltranslatemetadatalegacy/#a697fcfe76ef1dfd679fa0c9400f89a03">anonymous{DXILTranslateMetadata.cpp}::DXILTranslateMetadataLegacy::runOnModule</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopextractor-cpp-/loopextractorlegacypass/#aff0c08d4d1a9e1e89c177378d7b2d21d">anonymous{LoopExtractor.cpp}::LoopExtractorLegacyPass::runOnModule</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinecheckdebugify-cpp-/checkdebugmachinemodule/#a326b0f33afafa16b37d37f736e52bf5e">anonymous{MachineCheckDebugify.cpp}::CheckDebugMachineModule::runOnModule</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinedebugify-cpp-/debugifymachinemodule/#af63365e98863c61503b632f982aecca4">anonymous{MachineDebugify.cpp}::DebugifyMachineModule::runOnModule</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a847c562b6cc1fea696bcf695257cd6fb">anonymous{MachineOutliner.cpp}::MachineOutliner::runOnModule</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinestripdebug-cpp-/stripdebugmachinemodule/#af68a3711fb7b940ff150244b5892be4e">anonymous{MachineStripDebug.cpp}::StripDebugMachineModule::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-mips16hardfloat-cpp-/mips16hardfloat/#afe38556e5426f0e8a8c0c06bfa91769b">anonymous{Mips16HardFloat.cpp}::Mips16HardFloat::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsicloweringlegacypass/#a5092e99089883790c3496c84f7628904">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLoweringLegacyPass::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsmoduleprinterwrapperpass/#a164bd1e6aebc7d99557c5ddda3aa218b">llvm::DOTGraphTraitsModulePrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsmoduleviewerwrapperpass/#ad583334a516ee60aff18a2f6c70d0441">llvm::DOTGraphTraitsModuleViewerWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/shaderflagsanalysiswrapper/#ab61c60e0e612e0ba5c02b7773c0ebdcb">llvm::dxil::ShaderFlagsAnalysisWrapper::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcebindingwrapperpass/#a1ce5fa616d22e72d8634978441672a8e">llvm::DXILResourceBindingWrapperPass::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/globalsaawrapperpass/#aa22b2d673cfaa9cea78e29950ed1ef2c">llvm::GlobalsAAWrapperPass::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindexwrapperpass/#a65245026d158487606a0c04c035eff13">llvm::ModuleSummaryIndexWrapperPass::runOnModule</a>, <a href="/web-llvm/docs/api/structs/llvm/spirvmoduleanalysis/#a8eae6ad023f13a78b20df1ac5fd511fd">llvm::SPIRVModuleAnalysis::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfowrapperpass/#a2bb72590504bf690b08d2ad05ab19fce">llvm::StackSafetyGlobalInfoWrapperPass::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfglegacypass/#aecbd421c713f3803e5d34d14db2b4409">anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::runOnRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5b05d795913638143ef01b80fb151e89">llvm::AsmPrinter::SetupMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/loopinfowrapperpass/#aea281601b9f1c88d8cc2a4d6245d3b7d">llvm::LoopInfoWrapperPass::verifyAnalysis</a>.</p>

</div>
</div>

### getAnalysis() {#a560d384c0cef7f62836884fdbbd1fe66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisType &amp; llvm::Pass::getAnalysis (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, bool * Changed=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> - This function is used by subclasses to get to the analysis information that they claim to use by overriding the getAnalysisUsage function.</p>


<p>If as part of the dependencies, an IR transformation is triggered (e.g. because the analysis requires BreakCriticalEdges), and Changed is non null, *Changed is updated.</p>


<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a6613f29d3e54ce175ac33fb9ba264fae">getAnalysisID</a>.</p>

</div>
</div>

### getAnalysisID() {#a6613f29d3e54ce175ac33fb9ba264fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisType &amp; llvm::Pass::getAnalysisID (<a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> PI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a03d3a81b1c46aff7c38ef3a6750ba225">getAdjustedAnalysisPointer</a> and <a href="#a16baa169d062524be5a6b67609266174">Pass</a>.</p>


<p>Referenced by <a href="#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis</a> and <a href="#a560d384c0cef7f62836884fdbbd1fe66">getAnalysis</a>.</p>

</div>
</div>

### getAnalysisID() {#a2190247edbacb33b4e8a3d409fa2d99e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisType &amp; llvm::Pass::getAnalysisID (<a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> PI, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, bool * Changed=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a03d3a81b1c46aff7c38ef3a6750ba225">getAdjustedAnalysisPointer</a> and <a href="#a16baa169d062524be5a6b67609266174">Pass</a>.</p>

</div>
</div>

### getAnalysisIfAvailable() {#af94c014e968489e96c7d4353a84ad7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisType * llvm::Pass::getAnalysisIfAvailable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#af94c014e968489e96c7d4353a84ad7f5">getAnalysisIfAvailable&lt;AnalysisType&gt;()</a> - Subclasses use this function to get analysis information that might be around, for example to update it.</p>


<p>This is different than getAnalysis in that it can fail (if the analysis results haven't been computed), so should only be used if you can handle the case when the analysis is not available. This method is often used by transformation APIs to update analysis results for a pass automatically as the transform is performed.</p>


<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a03d3a81b1c46aff7c38ef3a6750ba225">getAdjustedAnalysisPointer</a> and <a href="#a16baa169d062524be5a6b67609266174">Pass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa9a2aed0d26a4fca41f8fc0986a3f12b">llvm::AsmPrinter::doFinalization</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuannotatekernelfeatures-cpp-/amdgpuannotatekernelfeatures/#aadbe2ecc21e2ba0125e89d1cb3e58678">anonymous{AMDGPUAnnotateKernelFeatures.cpp}::AMDGPUAnnotateKernelFeatures::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuattributor-cpp-/amdgpuattributorlegacy/#a254c2a9fbe65019571f695c1881ef26f">anonymous{AMDGPUAttributor.cpp}::AMDGPUAttributorLegacy::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/lowerintrinsics/#af5be2ef617c2421e873733744b14cffc">anonymous{GCRootLowering.cpp}::LowerIntrinsics::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7cd6d58462a0ebf3fa2c3d1423b0e2c6">llvm::AsmPrinter::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5b7c6daec7e647061052e0947de4703b">llvm::AsmPrinter::emitFunctionBody</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a67b9b30049b5642ea95990164c5e36cd">llvm::AsmPrinter::emitStackMaps</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptioncachetracker/#af0c9a679eca493aa32aa7002bf4a50a3">llvm::AssumptionCacheTracker::getAssumptionCache</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aafadfc35831cdb7ef3dd321cc28f1208">llvm::SelectionDAGISel::initializeAnalysisResults</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a4636655f10db66966895ea366108f1e5">anonymous{MachineOutliner.cpp}::MachineOutliner::initializeOutlinerMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-phielimination-cpp-/phieliminationimpl/#aba6e49d59266f311a4ec8bb6574d13ad">anonymous{PHIElimination.cpp}::PHIEliminationImpl::PHIEliminationImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuatomicoptimizer-cpp-/amdgpuatomicoptimizer/#a239d03ce853ea6b2a72debc452590218">anonymous{AMDGPUAtomicOptimizer.cpp}::AMDGPUAtomicOptimizer::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepare/#af6170254ef76a5d14783363b7862d85b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepare::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotealloca-cpp-/amdgpupromotealloca/#a415c2fe7bb80ea1eec2885cd51136119">anonymous{AMDGPUPromoteAlloca.cpp}::AMDGPUPromoteAlloca::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotealloca-cpp-/amdgpupromoteallocatovector/#a4db28e896fe88fa692c280aff5fdaa13">anonymous{AMDGPUPromoteAlloca.cpp}::AMDGPUPromoteAllocaToVector::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-atomicexpandpass-cpp-/atomicexpandlegacy/#a43c38bf17748be9713e9fadf457de0be">anonymous{AtomicExpandPass.cpp}::AtomicExpandLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-breakcriticaledges-cpp-/breakcriticaledges/#a1c9d2281808f2cebaf85dc0206fd4409">anonymous{BreakCriticalEdges.cpp}::BreakCriticalEdges::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-callbrprepare-cpp-/callbrprepare/#a059a9f67e58a405134e69baa176e4ee1">anonymous{CallBrPrepare.cpp}::CallBrPrepare::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenpreparelegacypass/#a247a6373f131cbd580f94dd0483551b2">anonymous{CodeGenPrepare.cpp}::CodeGenPrepareLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfehprepare-cpp-/dwarfehpreparelegacypass/#a4f41301e138ffeaa12761bf5e94692e8">anonymous{DwarfEHPrepare.cpp}::DwarfEHPrepareLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/expandmemcmplegacypass/#a744c97bd2b03802d78ec941f5c7b9d16">anonymous{ExpandMemCmp.cpp}::ExpandMemCmpLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-fixirreducible-cpp-/fixirreducible/#a8d14bed3c1d3c5f9cd62aa160cc02d70">anonymous{FixIrreducible.cpp}::FixIrreducible::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hardwareloops-cpp-/hardwareloopslegacy/#a090edab056118e7dae834ce8e11e8157">anonymous{HardwareLoops.cpp}::HardwareLoopsLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-indirectbrexpandpass-cpp-/indirectbrexpandlegacypass/#a64dedd5849a9616aaa9ba3ed8010c384">anonymous{IndirectBrExpandPass.cpp}::IndirectBrExpandLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-inferaddressspaces-cpp-/inferaddressspaces/#ab8fd0d1d5b31cb7a1a069e588343c67a">anonymous{InferAddressSpaces.cpp}::InferAddressSpaces::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-interleavedaccesspass-cpp-/interleavedaccess/#a1a0ee1417af452f2512df6359fbe248a">anonymous{InterleavedAccessPass.cpp}::InterleavedAccess::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/interleavedloadcombine/#adef67ae3266f48eacb955c2d515737ef">anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombine::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-lcssa-cpp-/lcssawrapperpass/#ad6bef3a04cd1005ebd2040194d8548a2">anonymous{LCSSA.cpp}::LCSSAWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopsimplify-cpp-/loopsimplify/#ae6b772642c62e8f8d03d9a75148b12a2">anonymous{LoopSimplify.cpp}::LoopSimplify::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowerswitch-cpp-/lowerswitchlegacypass/#a8345e59cbfe10219f49fb04405952871">anonymous{LowerSwitch.cpp}::LowerSwitchLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/mergeicmpslegacypass/#a49d9ddefdd0a53fe9bf060228c87bbb9">anonymous{MergeICmps.cpp}::MergeICmpsLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-partiallyinlinelibcalls-cpp-/partiallyinlinelibcallslegacypass/#a8fad2b25e12f4c61e0494fffc8dab1e0">anonymous{PartiallyInlineLibCalls.cpp}::PartiallyInlineLibCallsLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcboolrettoint-cpp-/ppcboolrettoint/#afe9b5d441ad1fd6deb411648d498badc">anonymous{PPCBoolRetToInt.cpp}::PPCBoolRetToInt::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcloopinstrformprep-cpp-/ppcloopinstrformprep/#a8d1182a1362bef2929d09ce054e8fa5d">anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestacklegacypass/#a7cac2bf189a71c58d1514aaaac25414a">anonymous{SafeStack.cpp}::SafeStackLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizemaskedmemintrin-cpp-/scalarizemaskedmemintrinlegacypass/#a7d2ab592f7a307c23332fd688694d557">anonymous{ScalarizeMaskedMemIntrin.cpp}::ScalarizeMaskedMemIntrinLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-shadowstackgclowering-cpp-/shadowstackgclowering/#a2694e07d77f9cc729952b03b1e66463e">anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLowering::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-tailrecursionelimination-cpp-/tailcallelim/#abcc0dcce78ac4618e3b3e70df45e3539">anonymous{TailRecursionElimination.cpp}::TailCallElim::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsicslegacypass/#a3676b694f0f141994877ccf4564027ef">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsicsLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86partialreduction-cpp-/x86partialreduction/#a1fe47be14e85bf40acfb1b10aca7fe08">anonymous{X86PartialReduction.cpp}::X86PartialReduction::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresultswrapperpass/#a47ee17feac90f644d8afe91156ae9ddf">llvm::AAResultsWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/gvn/gvnlegacypass/#ab5d98be3e1b14ce50e328b3712b72b7f">llvm::gvn::GVNLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncombiningpass/#ab64b7e967adeebc9bacc8abd8ddce0c8">llvm::InstructionCombiningPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotector/#ad6088af9690051701647680fd467ed97">llvm::StackProtector::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-licm-cpp-/legacylicmpass/#adfe3debfb083aea25b34a2f09c1b3132">anonymous{LICM.cpp}::LegacyLICMPass::runOnLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-basicblocksections-cpp-/basicblocksections/#a977d864b83223a6ae106ddc332dba144">anonymous{BasicBlockSections.cpp}::BasicBlockSections::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnrewritepartialreguses-cpp-/gcnrewritepartialreguses/#adf18d032626767c9b0590624712d3ac1">anonymous{GCNRewritePartialRegUses.cpp}::GCNRewritePartialRegUses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagontfrcleanup-cpp-/hexagontfrcleanup/#aa7619322b2d38567f6b30b0bc454a28e">anonymous{HexagonTfrCleanup.cpp}::HexagonTfrCleanup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinefunctionprinterpass-cpp-/machinefunctionprinterpass/#ab2aab8a3c4b3b78eaa8f51355ac9fd28">anonymous{MachineFunctionPrinterPass.cpp}::MachineFunctionPrinterPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/riscvinsertvsetvli/#ac9a5b9cc9cc2d9a2444ce7ca62803639">anonymous{RISCVInsertVSETVLI.cpp}::RISCVInsertVSETVLI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowercontrolflow-cpp-/silowercontrolflowlegacy/#aed4f0bb85cffb011a78edc2ce6c0b6cb">anonymous{SILowerControlFlow.cpp}::SILowerControlFlowLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspillslegacy/#a39b4f2fe5e2c2535293788e161357031">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpillsLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowerwwmcopies-cpp-/silowerwwmcopieslegacy/#a5aaaf11f9364085f56bd6f05520fd226">anonymous{SILowerWWMCopies.cpp}::SILowerWWMCopiesLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siwholequadmode-cpp-/siwholequadmode/#ae53d8e40bdcb428165b0243af4be1dcc">anonymous{SIWholeQuadMode.cpp}::SIWholeQuadMode::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/#abc3887b23032d20ff538f82f3e5f4867">llvm::AMDGPUResourceUsageAnalysis::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerldslegacy/#acfe402ed12ef3aa3f9b6b75a60baeb33">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDSLegacy::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmergefunctions-cpp-/globalmergefuncpasswrapper/#a9a965d9aa584ff64a96cc24f62a23b59">anonymous{GlobalMergeFunctions.cpp}::GlobalMergeFuncPassWrapper::runOnModule</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopextractor-cpp-/loopextractorlegacypass/#aff0c08d4d1a9e1e89c177378d7b2d21d">anonymous{LoopExtractor.cpp}::LoopExtractorLegacyPass::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-loweremutls-cpp-/loweremutls/#a4486e8843a723b736dedb0f8f61c1322">anonymous{LowerEmuTLS.cpp}::LowerEmuTLS::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcgenscalarmassentries-cpp-/ppcgenscalarmassentries/#a8d53ccc35d29279812f307f7e908ed06">anonymous{PPCGenScalarMASSEntries.cpp}::PPCGenScalarMASSEntries::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppclowermassventries-cpp-/ppclowermassventries/#afc7b9162f72717ab77864ee9b4b48030">anonymous{PPCLowerMASSVEntries.cpp}::PPCLowerMASSVEntries::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a4e54683754f6664c17d470ae3a097486">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::runOnModule</a> and <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfowrapperpass/#a2bb72590504bf690b08d2ad05ab19fce">llvm::StackSafetyGlobalInfoWrapperPass::runOnModule</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a6590d0486104165ca40c7df0707f7b9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pass::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64lowerhomogeneousprologepilog-cpp-/aarch64lowerhomogeneousprologepilog/#ac90310a56e9cae1304a02023e8a760ee">anonymous{AArch64LowerHomogeneousPrologEpilog.cpp}::AArch64LowerHomogeneousPrologEpilog::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotealloca-cpp-/amdgpupromotealloca/#a862c305aa8da9877b0b1adc40047f85d">anonymous{AMDGPUPromoteAlloca.cpp}::AMDGPUPromoteAlloca::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotealloca-cpp-/amdgpupromoteallocatovector/#aad5855d9b0d61f931ddb2051de0762c6">anonymous{AMDGPUPromoteAlloca.cpp}::AMDGPUPromoteAllocaToVector::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af4b26d5c6b40a6d1f66d4e96b5352d9b">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodes/#ae0488ec3d2973d61223a316e88988b65">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodes::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/armparalleldsp/#a150618f73ac168f3449ea9325dc36b81">anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphdotprinter/#ab8495a00f0c8d8dc82aa00ea515dc692">anonymous{CallPrinter.cpp}::CallGraphDOTPrinter::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphviewer/#acdb259f5a825cd4226f7ddb29f94c869">anonymous{CallPrinter.cpp}::CallGraphViewer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/lowerintrinsics/#a6dd7dba6eaa5dbc596a942319506a45c">anonymous{GCRootLowering.cpp}::LowerIntrinsics::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmerge/#a306b0d81a7cf944346a854335c0c3436">anonymous{GlobalMerge.cpp}::GlobalMerge::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmergefunctions-cpp-/globalmergefuncpasswrapper/#a8ef3651109e98ef564491e2c89febed6">anonymous{GlobalMergeFunctions.cpp}::GlobalMergeFuncPassWrapper::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncommongep-cpp-/hexagoncommongep/#a2b2ceca55e74b675689b101431a52f2a">anonymous{HexagonCommonGEP.cpp}::HexagonCommonGEP::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongenextract-cpp-/hexagongenextract/#a5707542f1ed48d8046d39b60514b308d">anonymous{HexagonGenExtract.cpp}::HexagonGenExtract::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#a1d4b281de1bd93793ccd793ca400e664">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombinelegacy/#abd5bd35073dfc041b595cdaee05bb3b3">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombineLegacy::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/interleavedloadcombine/#ae150a828e8305ad8c3ead8ceee930089">anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombine::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a91bb84179044c30641f066d505ac80cc">anonymous{MachineOutliner.cpp}::MachineOutliner::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mips16hardfloat-cpp-/mips16hardfloat/#af19d4487f8cb225bcce0c323d24e9d05">anonymous{Mips16HardFloat.cpp}::Mips16HardFloat::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvegatherscatterlowering-cpp-/mvegatherscatterlowering/#afa4a0702e24a4ace54875ffda7200ae2">anonymous{MVEGatherScatterLowering.cpp}::MVEGatherScatterLowering::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvelaneinterleavingpass-cpp-/mvelaneinterleaving/#a5d398dffcffa3207fea0090bfcb6b18a">anonymous{MVELaneInterleavingPass.cpp}::MVELaneInterleaving::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-partiallyinlinelibcalls-cpp-/partiallyinlinelibcallslegacypass/#ade5e04b82d1e1419ce848bd0edd5cbe5">anonymous{PartiallyInlineLibCalls.cpp}::PartiallyInlineLibCallsLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcboolrettoint-cpp-/ppcboolrettoint/#a11e3444b331ddd64964613fe19bfde30">anonymous{PPCBoolRetToInt.cpp}::PPCBoolRetToInt::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-sink-cpp-/sinkinglegacypass/#a63a0ebb8bc075dbdbed33044d75affba">anonymous{Sink.cpp}::SinkingLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#a570915e7b11b2252b502a34b69ad63a0">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvpreparefunctions-cpp-/spirvpreparefunctions/#ab03a8fe9243ec198202eedd098b839bd">anonymous{SPIRVPrepareFunctions.cpp}::SPIRVPrepareFunctions::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/anonymous-spirvregularizer-cpp-/spirvregularizer/#ac3fdb03fb019719c4a8fdb2a93a888a5">anonymous{SPIRVRegularizer.cpp}::SPIRVRegularizer::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfglegacypass/#abe30a2c7f18e2cb17df9295407d6c22c">anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#a2162395b97baa410f6b5a0dd6b160c12">llvm::SPIRVMergeRegionExitTargets::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvstructurizer/#a0861553af62de2a79f4a9abecc92b3bb">llvm::SPIRVStructurizer::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/siannotatecontrolflowlegacy/#aee9d51ef08a7d3163b2f1601fdaa94a5">SIAnnotateControlFlowLegacy::getAnalysisUsage</a>.</p>

</div>
</div>

### getAsImmutablePass() {#ae31759fd992cddb1f2d62ab0df85834a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutablePass * Pass::getAsImmutablePass ()</td>
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



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

### getAsPMDataManager() {#a626b77ef8abdfa9f53c697ad129a6e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMDataManager * Pass::getAsPMDataManager ()</td>
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



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

### getPassID() {#a63192e749ba4a0ee29336a59d6a19647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisID llvm::Pass::getPassID ()</td>
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

<p>getPassID - Return the PassID number that corresponds to this pass.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a452b3946fae687fe6ab129970b5f9c75">anonymous{LegacyPassManager.cpp}::MPPassManager::addLowerLevelRequiredPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a36adfc24480b78dfe7a51559b8264de7">llvm::TargetPassConfig::insertPass</a>.</p>

</div>
</div>

### getPassKind() {#a9de4db62e6884f2e5efea6793af30d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassKind llvm::Pass::getPassKind ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

</div>
</div>

### getPassName() {#ad729b39eacf070a9bca84533b3c743bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Pass::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a490078b030c2d08d36afe903601d86da">llvm::PMDataManager::addLowerLevelRequiredPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#af740891e192aa63a0fbbfe317301cbdb">llvm::PMDataManager::removeNotPreservedAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5fb719fc8062d116b93091d9c9addd43">llvm::PMTopLevelManager::schedulePass</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#ac97db8f0e4f4a0946dddf617f45f6c8b">llvm::LoopPass::skipLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2a3749e0f47aa3b73df3ac0e66a78771">llvm::RegionPass::skipRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#a978ee5e9b5b33e10cea60aea38f80788">llvm::CallGraphSCCPass::skipSCC</a>.</p>

</div>
</div>

### getPotentialPassManagerType() {#a05cd3cab5ce2e13c7636ef21adef6e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassManagerType Pass::getPotentialPassManagerType ()</td>
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

<p>Return what kind of <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager can manage this pass.</p>

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a452b3946fae687fe6ab129970b5f9c75">anonymous{LegacyPassManager.cpp}::MPPassManager::addLowerLevelRequiredPass</a> and <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5fb719fc8062d116b93091d9c9addd43">llvm::PMTopLevelManager::schedulePass</a>.</p>

</div>
</div>

### getResolver() {#a969c082f66671df288441bbad9ca87db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisResolver * llvm::Pass::getResolver ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5eab64f06a4196bd59b9b19251eefddb">llvm::PMTopLevelManager::setLastUser</a>.</p>

</div>
</div>

### mustPreserveAnalysisID() {#a0b4a511579939b07831db90c3fc98996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Pass::mustPreserveAnalysisID (char &amp; AID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>mustPreserveAnalysisID - This method serves the same function as getAnalysisIfAvailable, but works if you just have an <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>.</p>


<p>This obviously cannot give you a properly typed instance of the class if you don't have the class name available (use getAnalysisIfAvailable if you do), but it can tell you if you need to preserve the pass at least.</p>


<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hardwareloops-cpp-/hardwareloopslegacy/#a090edab056118e7dae834ce8e11e8157">anonymous{HardwareLoops.cpp}::HardwareLoopsLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopsimplify-cpp-/loopsimplify/#ae6b772642c62e8f8d03d9a75148b12a2">anonymous{LoopSimplify.cpp}::LoopSimplify::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcloopinstrformprep-cpp-/ppcloopinstrformprep/#a8d1182a1362bef2929d09ce054e8fa5d">anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopunrollpass-cpp-/loopunroll/#a176b0f7a9dc90d996cae2767b3aea0ca">anonymous{LoopUnrollPass.cpp}::LoopUnroll::runOnLoop</a>.</p>

</div>
</div>

### preparePassManager() {#aa5f61a8789f87816c5f494d42a70f01f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pass::preparePassManager (<a href="/web-llvm/docs/api/classes/llvm/pmstack">PMStack</a> &amp;)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if available pass managers are suitable for this pass or not.</p>

<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

### print() {#a061b4c01e9c189208dbfd3c77fdb9a5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pass::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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

<p>print - Print out the internal state of the pass.</p>


<p>This is called by Analyze to print out the contents of an analysis. Otherwise it is not necessary to implement this method. Beware that the module pointer MAY be null. This automatically forwards to a virtual function that does not provide the Module* in case the analysis doesn't need it it can just be ignored.</p>


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

### releaseMemory() {#aeb6e74b0f36a0acd1d20149ef088715a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pass::releaseMemory ()</td>
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

<p><a href="#aeb6e74b0f36a0acd1d20149ef088715a">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed.</p>


<p>The default behavior of passes is to hold onto memory for the entire duration of their lifetime (which is the entire compile time). For pipelined passes, this is not a big deal because that memory gets recycled every time the pass is invoked on another program unit. For IP passes, it is more important to free memory when it is unused.</p>


<p>Optionally implement this function to release pass memory when it is no longer used.</p>


<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a35df5259dc1bc4f526a32a2d18cb3f59">llvm::legacy::FunctionPassManagerImpl::releaseMemoryOnTheFly</a>.</p>

</div>
</div>

### setResolver() {#a2423fcc912a698d4f36c9c9380b53a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pass::setResolver (<a href="/web-llvm/docs/api/classes/llvm/analysisresolver">AnalysisResolver</a> * AR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

### verifyAnalysis() {#ac8ef6f57d4ec869a7f1007aeddf2b169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Pass::verifyAnalysis ()</td>
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

<p><a href="#ac8ef6f57d4ec869a7f1007aeddf2b169">verifyAnalysis()</a> - This member can be implemented by a analysis pass to check state of analysis information.</p>

<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#a0d122b07004ba08f932973d84f90db54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassKind llvm::Pass::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

</div>
</div>

### PassID {#af3b74f8adddf230d701f86af34a3ce67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void* llvm::Pass::PassID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

</div>
</div>

### Resolver {#a904990eb2e4e1c22e464cd1502254bcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisResolver* llvm::Pass::Resolver = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createPass() {#a2ed7d79d79dffe7368c3d3cdf40dd80e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * Pass::createPass (<a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> ID)</td>
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



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/structs/initialize-pass/insertedpass/#aa6ddb800bea767194940505993f2e4b1">INITIALIZE_PASS::InsertedPass::getInsertedPass</a>.</p>

</div>
</div>

### lookupPassInfo() {#aab174263c400ece13a7278990e102fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PassInfo * Pass::lookupPassInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * TI)</td>
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



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-passtiminginfo-cpp-/legacy/passtiminginfo/#a6a4d99a79c2bcaaf0e30b92826156793">llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::getPassTimer</a>.</p>

</div>
</div>

### lookupPassInfo() {#a992ff669acca94459037cfb1f41cb9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PassInfo * Pass::lookupPassInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arg)</td>
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



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/passanalysissupport-h">PassAnalysisSupport.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/pass-cpp">Pass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
