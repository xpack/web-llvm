---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/attributorconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AttributorConfig` Struct Reference

<p>Configuration for the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AttributorConfig { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ca0c715e59e7be8f1fdfde5f6b56f3d">OptimizationRemarkGetter</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A callback function that returns an ORE object from a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> pointer. <a href="#a8ca0c715e59e7be8f1fdfde5f6b56f3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8703c0234391786225846aa8e7fdad1e">IPOAmendableCBTy</a> = std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af949d20dda8a0a31b5b49d2e4067372a">AttributorConfig</a> (CallGraphUpdater &amp;CGUpdater)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af398ef0df0e0b9d6840d7d8c9ef0be53">IsModulePass</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is the user of the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> a module pass or not. <a href="#af398ef0df0e0b9d6840d7d8c9ef0be53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80aad4aa45c7a3c03ac55995f127c903">DeleteFns</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to determine if we can delete functions or keep dead ones around. <a href="#a80aad4aa45c7a3c03ac55995f127c903">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3df192ae0cdf572691dd5ff490278739">RewriteSignatures</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to determine if we rewrite function signatures. <a href="#a3df192ae0cdf572691dd5ff490278739">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d73bb34e01f98a095edeaff5338ecc">DefaultInitializeLiveInternals</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to determine if we want to initialize all default AAs for an internal function marked live. <a href="#af5d73bb34e01f98a095edeaff5338ecc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02c61ed9ab663796cbee7b0626516e73">UseLiveness</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to determine if we should skip all liveness checks early on. <a href="#a02c61ed9ab663796cbee7b0626516e73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3ba54ea61fc657e987b55fc5b82c92">IsClosedWorldModule</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to indicate if the entire world is contained in this module, that is, no outside functions exist. <a href="#a8a3ba54ea61fc657e987b55fc5b82c92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04ea2fc0b7c81a7bb90ced540e3b075a">InitializationCallback</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback function to be invoked on internal functions marked live. <a href="#a04ea2fc0b7c81a7bb90ced540e3b075a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; bool(<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp;AA, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp;CB, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;AssumedCallee, unsigned NumAssumedCallees)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3e784c98e9fe15787ea751bccce26dd">IndirectCalleeSpecializationCallback</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback function to determine if an indirect call targets should be made direct call targets (with an if-cascade). <a href="#af3e784c98e9fe15787ea751bccce26dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callgraphupdater">CallGraphUpdater</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac232da74a268621612b159cc38d4fbbe">CGUpdater</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to update an underlying call graph and to delete functions. <a href="#ac232da74a268621612b159cc38d4fbbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30934b17f16874888877afed7bec5029">Allowed</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If not null, a set limiting the attribute opportunities. <a href="#a30934b17f16874888877afed7bec5029">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a068d18c1fc465f017895d6512d47467b">MaxFixpointIterations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum number of iterations to run until fixpoint. <a href="#a068d18c1fc465f017895d6512d47467b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8ca0c715e59e7be8f1fdfde5f6b56f3d">OptimizationRemarkGetter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a584c356b083da5f7ca5ece1765a7e206">OREGetter</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ffd7d836cc546feb2fb671fd3cf0b73">PassName</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a3ffd7d836cc546feb2fb671fd3cf0b73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8703c0234391786225846aa8e7fdad1e">IPOAmendableCBTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae035d742240265c163de74c1f6f07082">IPOAmendableCB</a></td>
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

<p>Configuration for the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a>.</p>

<p>Definition at line 1431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### IPOAmendableCBTy {#a8703c0234391786225846aa8e7fdad1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AttributorConfig::IPOAmendableCBTy =  std::function&lt;bool(const Function &amp;F)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### OptimizationRemarkGetter {#a8ca0c715e59e7be8f1fdfde5f6b56f3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AttributorConfig::OptimizationRemarkGetter = 
      function_ref&lt;OptimizationRemarkEmitter &amp;(Function *)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A callback function that returns an ORE object from a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> pointer.</p>


<p>{</p>


<p>Definition at line 1482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AttributorConfig() {#af949d20dda8a0a31b5b49d2e4067372a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributorConfig::AttributorConfig (<a href="/web-llvm/docs/api/classes/llvm/callgraphupdater">CallGraphUpdater</a> &amp; CGUpdater)</td>
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



<p>Definition at line 1433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#ac232da74a268621612b159cc38d4fbbe">CGUpdater</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Allowed {#a30934b17f16874888877afed7bec5029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;const char *&gt;* llvm::AttributorConfig::Allowed = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If not null, a set limiting the attribute opportunities.</p>

<p>Definition at line 1475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### CGUpdater {#ac232da74a268621612b159cc38d4fbbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallGraphUpdater&amp; llvm::AttributorConfig::CGUpdater</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to update an underlying call graph and to delete functions.</p>

<p>Definition at line 1472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#af949d20dda8a0a31b5b49d2e4067372a">AttributorConfig</a>.</p>

</div>
</div>

### DefaultInitializeLiveInternals {#af5d73bb34e01f98a095edeaff5338ecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributorConfig::DefaultInitializeLiveInternals = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to determine if we want to initialize all default AAs for an internal function marked live.</p>


<p>See also: InitializationCallback&gt;</p>


<p>Definition at line 1452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### DeleteFns {#a80aad4aa45c7a3c03ac55995f127c903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributorConfig::DeleteFns = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to determine if we can delete functions or keep dead ones around.</p>

<p>Definition at line 1445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### IndirectCalleeSpecializationCallback {#af3e784c98e9fe15787ea751bccce26dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;bool(Attributor &amp;A, const AbstractAttribute &amp;AA, CallBase &amp;CB, Function &amp;AssumedCallee, unsigned NumAssumedCallees)&gt; llvm::AttributorConfig::IndirectCalleeSpecializationCallback = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback function to determine if an indirect call targets should be made direct call targets (with an if-cascade).</p>

<p>Definition at line 1469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### InitializationCallback {#a04ea2fc0b7c81a7bb90ced540e3b075a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(Attributor &amp;A, const Function &amp;F)&gt; llvm::AttributorConfig::InitializationCallback</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback function to be invoked on internal functions marked live.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      nullptr
</div>
</dd>
</dl>

<p>Definition at line 1462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### IPOAmendableCB {#ae035d742240265c163de74c1f6f07082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IPOAmendableCBTy llvm::AttributorConfig::IPOAmendableCB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### IsClosedWorldModule {#a8a3ba54ea61fc657e987b55fc5b82c92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributorConfig::IsClosedWorldModule = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to indicate if the entire world is contained in this module, that is, no outside functions exist.</p>

<p>Definition at line 1459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### IsModulePass {#af398ef0df0e0b9d6840d7d8c9ef0be53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributorConfig::IsModulePass = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is the user of the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> a module pass or not.</p>


<p>This determines what IR we can look at and modify. If it is a module pass we might deduce facts outside the initial function set and modify functions outside that set, but only as part of the optimization of the functions in the initial function set. For CGSCC passes we can look at the IR of the module slice but never run any deduction, or perform any modification, outside the initial function set (which we assume is the SCC).</p>


<p>Definition at line 1442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### MaxFixpointIterations {#a068d18c1fc465f017895d6512d47467b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::AttributorConfig::MaxFixpointIterations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum number of iterations to run until fixpoint.</p>

<p>Definition at line 1478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### OREGetter {#a584c356b083da5f7ca5ece1765a7e206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkGetter llvm::AttributorConfig::OREGetter = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### PassName {#a3ffd7d836cc546feb2fb671fd3cf0b73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::AttributorConfig::PassName = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>


<p>The name of the pass running the attributor, used to emit remarks.</p>


<p>Definition at line 1488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### RewriteSignatures {#a3df192ae0cdf572691dd5ff490278739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributorConfig::RewriteSignatures = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to determine if we rewrite function signatures.</p>

<p>Definition at line 1448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### UseLiveness {#a02c61ed9ab663796cbee7b0626516e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributorConfig::UseLiveness = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to determine if we should skip all liveness checks early on.</p>

<p>Definition at line 1455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
