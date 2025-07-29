---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/globaldcepass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GlobalDCEPass` Class

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> to remove unused function declarations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GlobalDCEPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">llvm/Transforms/IPO/GlobalDCE.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b178be358872e3d9fc7330351d61ce">GlobalDCEPass</a> (bool InLTOPostLink=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae98558816f50b4a9f6f7244b2deadd53">run</a> (Module &amp;M, ModuleAnalysisManager &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8826f287bdb4166b59a1f3f9644a9741">printPipeline</a> (raw_ostream &amp;OS, function_ref&lt; StringRef(StringRef)&gt; MapClassName2PassName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb730e2b29d512e50fc1ed9095f920ec">UpdateGVDependencies</a> (GlobalValue &amp;GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e6cda3bea3705699fcd36b98cd32748">MarkLive</a> (GlobalValue &amp;GV, SmallVectorImpl&lt; GlobalValue * &gt; *Updates=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark Global value as Live. <a href="#a9e6cda3bea3705699fcd36b98cd32748">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60514627816ec439cfbeb6ed5cce2147">AddVirtualFunctionDependencies</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b42c76a2020856ece2ee6b1249d276">ScanVTables</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c475e09b477874dd8a2cc85957f2b0b">ScanTypeCheckedLoadIntrinsics</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009f6bd3248be29f4a77d37a7838c352">ScanVTableLoad</a> (Function *Caller, Metadata *TypeId, uint64_t CallOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eb2fe6ff158cc3c28511dd67f87f93d">ComputeDependencies</a> (Value *V, SmallPtrSetImpl&lt; GlobalValue * &gt; &amp;U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the set of <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> that depends from V. <a href="#a2eb2fe6ff158cc3c28511dd67f87f93d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1994dc1989fd9ff21d4f2425e2e5b4f">InLTOPostLink</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82143d35da5daa1cd085db5faa73f212">AliveGlobals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201af7c1ba99e1f255af2565f108d3c4">GVDependencies</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global -&gt; Global that uses this global. <a href="#a201af7c1ba99e1f255af2565f108d3c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, 8 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d52e5b5529f2df19016d4795ddde4e">ConstantDependenciesCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> -&gt; Globals that use this global cache. <a href="#ad5d52e5b5529f2df19016d4795ddde4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_multimap&lt; <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c494e227e215b2d52da033f7139e25d">ComdatMembers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> -&gt; Globals in that <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> section. <a href="#a9c494e227e215b2d52da033f7139e25d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, uint64_t &gt;, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a167a40492adf3f78d76e0b85ffbf3af7">TypeIdMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>!type metadata -&gt; set of (vtable, offset) pairs <a href="#a167a40492adf3f78d76e0b85ffbf3af7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa8300a0d579e8598e0f7098cbf26c62">VFESafeVTables</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> to remove unused function declarations.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GlobalDCEPass() {#ad0b178be358872e3d9fc7330351d61ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalDCEPass::GlobalDCEPass (bool InLTOPostLink=false)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printPipeline() {#a8826f287bdb4166b59a1f3f9644a9741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalDCEPass::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; MapClassName2PassName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>, definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globaldce-cpp">GlobalDCE.cpp</a>.</p>


<p>Reference <a href="#a8826f287bdb4166b59a1f3f9644a9741">printPipeline</a>.</p>


<p>Referenced by <a href="#a8826f287bdb4166b59a1f3f9644a9741">printPipeline</a>.</p>

</div>
</div>

### run() {#ae98558816f50b4a9f6f7244b2deadd53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses GlobalDCEPass::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globaldce-cpp">GlobalDCE.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a7c733400ba8d113fd2976d4fea0db981">llvm::GlobalValue::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a43721e1e88567116e8fca545125d86bf">llvm::GlobalValue::getComdat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globaldce-cpp/#a7510b70799a0e939f76ca33b6d05c925">isEmptyFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b369f94d5ebc6e107a988f17b42b3eb">llvm::isSafeToDestroyConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71b27c25d18516bdcb3f3a44ebf6185b">llvm::optimizeGlobalCtorsList</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a960620248182018e566b095f06a605df">llvm::Constant::removeDeadConstantUsers</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adb95b461a284d8670fc10d24d56cbf56">llvm::replaceRelativePointerUsersWithZero</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AddVirtualFunctionDependencies() {#a60514627816ec439cfbeb6ed5cce2147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalDCEPass::AddVirtualFunctionDependencies (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globaldce-cpp">GlobalDCE.cpp</a>.</p>

</div>
</div>

### ComputeDependencies() {#a2eb2fe6ff158cc3c28511dd67f87f93d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalDCEPass::ComputeDependencies (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt; &amp; Deps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the set of <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> that depends from V.</p>


<p>The recursion stops as soon as a <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> is met.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globaldce-cpp">GlobalDCE.cpp</a>.</p>

</div>
</div>

### MarkLive() {#a9e6cda3bea3705699fcd36b98cd32748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalDCEPass::MarkLive (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt; * Updates=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark Global value as Live.</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globaldce-cpp">GlobalDCE.cpp</a>.</p>

</div>
</div>

### ScanTypeCheckedLoadIntrinsics() {#a2c475e09b477874dd8a2cc85957f2b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalDCEPass::ScanTypeCheckedLoadIntrinsics (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globaldce-cpp">GlobalDCE.cpp</a>.</p>

</div>
</div>

### ScanVTableLoad() {#a009f6bd3248be29f4a77d37a7838c352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalDCEPass::ScanVTableLoad (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Caller, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * TypeId, uint64_t CallOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globaldce-cpp">GlobalDCE.cpp</a>.</p>

</div>
</div>

### ScanVTables() {#ac8b42c76a2020856ece2ee6b1249d276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalDCEPass::ScanVTables (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globaldce-cpp">GlobalDCE.cpp</a>.</p>

</div>
</div>

### UpdateGVDependencies() {#afb730e2b29d512e50fc1ed9095f920ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalDCEPass::UpdateGVDependencies (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globaldce-cpp">GlobalDCE.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AliveGlobals {#a82143d35da5daa1cd085db5faa73f212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;GlobalValue*, 32&gt; llvm::GlobalDCEPass::AliveGlobals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>.</p>

</div>
</div>

### ComdatMembers {#a9c494e227e215b2d52da033f7139e25d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_multimap&lt;Comdat *, GlobalValue *&gt; llvm::GlobalDCEPass::ComdatMembers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> -&gt; Globals in that <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> section.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>.</p>

</div>
</div>

### ConstantDependenciesCache {#ad5d52e5b5529f2df19016d4795ddde4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;Constant *, SmallPtrSet&lt;GlobalValue *, 8&gt; &gt; llvm::GlobalDCEPass::ConstantDependenciesCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> -&gt; Globals that use this global cache.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>.</p>

</div>
</div>

### GVDependencies {#a201af7c1ba99e1f255af2565f108d3c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;GlobalValue *, SmallPtrSet&lt;GlobalValue *, 4&gt; &gt; llvm::GlobalDCEPass::GVDependencies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global -&gt; Global that uses this global.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>.</p>

</div>
</div>

### InLTOPostLink {#ad1994dc1989fd9ff21d4f2425e2e5b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalDCEPass::InLTOPostLink = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>.</p>

</div>
</div>

### TypeIdMap {#a167a40492adf3f78d76e0b85ffbf3af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Metadata *, SmallSet&lt;std::pair&lt;GlobalVariable *, uint64_t&gt;, 4&gt; &gt; llvm::GlobalDCEPass::TypeIdMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>!type metadata -&gt; set of (vtable, offset) pairs</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>.</p>

</div>
</div>

### VFESafeVTables {#aaa8300a0d579e8598e0f7098cbf26c62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;GlobalValue *, 32&gt; llvm::GlobalDCEPass::VFESafeVTables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/globaldce-h">GlobalDCE.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globaldce-cpp">GlobalDCE.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
