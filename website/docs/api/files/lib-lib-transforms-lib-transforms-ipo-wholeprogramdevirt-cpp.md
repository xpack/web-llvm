---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `WholeProgramDevirt.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">llvm/Transforms/IPO/WholeProgramDevirt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemapinfo-h">llvm/ADT/DenseMapInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/basicaliasanalysis-h">llvm/Analysis/BasicAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typemetadatautils-h">llvm/Analysis/TypeMetadataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">llvm/Bitcode/BitcodeReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">llvm/Bitcode/BitcodeWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">llvm/IR/GlobalAlias.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">llvm/IR/ModuleSummaryIndexYAML.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/globpattern-h">llvm/Support/GlobPattern.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/ipo-h">llvm/Transforms/IPO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionattrs-h">llvm/Transforms/IPO/FunctionAttrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callpromotionutils-h">llvm/Transforms/Utils/CallPromotionUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">llvm/Transforms/Utils/Evaluator.h</a>"
#include &lt;algorithm&gt;
#include &lt;cstddef&gt;
#include &lt;map&gt;
#include &lt;set&gt;
#include &lt;string&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-wholeprogramdevirt-cpp-">anonymous{WholeProgramDevirt.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/patternlist">PatternList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslot">VTableSlot</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/densemapinfo-fbbd89e197847d24411e9fd99b4d0911">DenseMapInfo&lt;VTableSlot&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/densemapinfo-b15fb43ec6f8abbffe4d2a73ea4ec543">DenseMapInfo&lt;VTableSlotSummary&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/virtualcallsite">VirtualCallSite</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo">CallSiteInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo">VTableSlotInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule">DevirtModule</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex">DevirtIndex</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">WPDCheckMode { <a href="#a0e65aef39009b683d7acb5884ae47421">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mechanism to add runtime checking of devirtualization decisions, optionally trapping or falling back to indirect call on any that are not correct. <a href="#a0e65aef39009b683d7acb5884ae47421">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e51f776bd61eeb7797b58758cb6992">STATISTIC</a> (NumDevirtTargets, "Number of whole program devirtualization targets")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2649b20360647125896c6227a6cf8593">STATISTIC</a> (NumSingleImpl, "Number of single implementation devirtualizations")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a149241ceac952de5c74e296e0a1e3f7b">STATISTIC</a> (NumBranchFunnel, "Number of branch funnels")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa0e834431615385b92b415c9297519a">STATISTIC</a> (NumUniformRetVal, "Number of uniform return value optimizations")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b2c8ae5dc78a0e3e76588b4ff3799fe">STATISTIC</a> (NumUniqueRetVal, "Number of unique return value optimizations")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ccb420b46ac0a5c0ad6c279bfb5d61">STATISTIC</a> (NumVirtConstProp1Bit, "Number of 1 bit virtual constant propagations")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7bf15a60e2eaad1aad772f4fe7b89f7">STATISTIC</a> (NumVirtConstProp, "Number of virtual constant propagations")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af640debffd735af4dfdeaf7dcb1ec2a1">mustBeUnreachableFunction</a> (ValueInfo TheFnVI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3edf584072455be140ab0118e60cbf2d">typeIDVisibleToRegularObj</a> (StringRef TypeID, function_ref&lt; bool(StringRef)&gt; IsVisibleToRegularObj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f247de1d62de65df435321729d15e89">skipUpdateDueToValidation</a> (GlobalVariable &amp;GV, function_ref&lt; bool(StringRef)&gt; IsVisibleToRegularObj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f84f6f1a3f90b174404388b1bce971a">checkCombinedSummaryForTesting</a> (ModuleSummaryIndex *Summary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8309e74a87a287dfe316da0535c4722">AddCalls</a> (VTableSlotInfo &amp;SlotInfo, const ValueInfo &amp;Callee)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a38a0bdae7fb49d99f161aa6de0379d7e">PassSummaryAction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f21389b7e3a9bbbe8eb56e7350f7ff">ClSummaryAction</a>("wholeprogramdevirt-summary-action", cl::desc("What to do with the summary when running this pass"), cl::values(clEnumValN(PassSummaryAction::None, "none", "Do nothing"), clEnumValN(PassSummaryAction::Import, "import", "Import typeid resolutions from summary and globals"), clEnumValN(PassSummaryAction::Export, "export", "Export typeid resolutions to summary and globals")), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cc0469b2ea8f4a2b3dbf68c0ec3ea57">ClReadSummary</a>("wholeprogramdevirt-read-summary", cl::desc("Read summary from given bitcode or YAML file before running pass"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51db681461de4b51651e3b82923c93b9">ClWriteSummary</a>("wholeprogramdevirt-write-summary", cl::desc("Write summary to given bitcode or YAML file after running pass. " "Output file format is deduced from extension: *.bc means writing " "bitcode, otherwise YAML"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72816be62cfd193f3cf78d55c0b29546">ClThreshold</a>("wholeprogramdevirt-branch-funnel-threshold", cl::Hidden, cl::init(10), cl::desc("Maximum number of call targets per " "call site to enable branch funnels"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0749a3f0019d8d6f49681ae6a6bd51">PrintSummaryDevirt</a>("wholeprogramdevirt-print-index-based", cl::Hidden, cl::desc("Print index-based devirtualization messages"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2886290cb6ad3d8ddf30d1e8035a235c">WholeProgramVisibility</a>("whole-program-visibility", cl::Hidden, cl::desc("Enable whole program visibility"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a way to force enable whole program visibility in tests. <a href="#a2886290cb6ad3d8ddf30d1e8035a235c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02a51fbe29ad30cc1b0ad02e982078ce">DisableWholeProgramVisibility</a>("disable-whole-program-visibility", cl::Hidden, cl::desc("Disable whole program visibility (overrides enabling options)"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a way to force disable whole program for debugging or workarounds, when enabled via the linker. <a href="#a02a51fbe29ad30cc1b0ad02e982078ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4acfa59172dc9825ef4c1362be8d31e7">SkipFunctionNames</a>("wholeprogramdevirt-skip", cl::desc("Prevent function(s) from being devirtualized"), cl::Hidden, cl::CommaSeparated)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide way to prevent certain function from being devirtualized. <a href="#a4acfa59172dc9825ef4c1362be8d31e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e98b87a580ee2727a894cafc57a73e">WholeProgramDevirtKeepUnreachableFunction</a>("wholeprogramdevirt-keep-unreachable-function", cl::desc("Regard unreachable functions as possible devirtualize targets."), cl::Hidden, cl::init(true))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>With Clang, a pure virtual class's deleting destructor is emitted as a <span class="doxyComputerOutput">llvm.trap</span> intrinsic followed by an unreachable IR instruction. <a href="#a92e98b87a580ee2727a894cafc57a73e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbc86a288e23ad77b686ef73a834a4c6">WholeProgramDevirtCutoff</a>("wholeprogramdevirt-cutoff", cl::desc("Max number of devirtualizations for devirt module pass"), cl::init(0))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If explicitly specified, the devirt module pass will stop transformation once the total number of devirtualizations reach the cutoff value. <a href="#acbc86a288e23ad77b686ef73a834a4c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#a0e65aef39009b683d7acb5884ae47421">WPDCheckMode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852c15f62fd7d543b4bde0c6010ba7ab">DevirtCheckMode</a>("wholeprogramdevirt-check", cl::Hidden, cl::desc("Type of checking for incorrect devirtualizations"), cl::values(clEnumValN(WPDCheckMode::None, "none", "No checking"), clEnumValN(WPDCheckMode::Trap, "trap", "Trap when incorrect"), clEnumValN(WPDCheckMode::Fallback, "fallback", "Fallback to indirect when incorrect")))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"wholeprogramdevirt"</td>
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


<div class="doxySectionDef">

## Enumerations

### WPDCheckMode {#a0e65aef39009b683d7acb5884ae47421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum WPDCheckMode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mechanism to add runtime checking of devirtualization decisions, optionally trapping or falling back to indirect call on any that are not correct.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="a0e65aef39009b683d7acb5884ae47421ac9d3e887722f2bc482bcca9d41c512af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Trap<a id="a0e65aef39009b683d7acb5884ae47421a178e499decd0c21272bc34e4b3056eab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Fallback<a id="a0e65aef39009b683d7acb5884ae47421aad98505ec3c6cabbb406c37037410854"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>Trapping mode is useful for debugging undefined behavior leading to failures with WPD. Fallback mode is useful for ensuring safety when whole program visibility may be compromised.</p>


<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### AddCalls() {#aa8309e74a87a287dfe316da0535c4722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddCalls (VTableSlotInfo &amp; SlotInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &amp; Callee)</td>
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



<p>Definition at line 1291 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#aa8309e74a87a287dfe316da0535c4722">AddCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eeaa494eb85f92e884f7e730d15a4dec9c7">CallSiteInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa4194726ee334e1085d93e002837b73f0">llvm::CalleeInfo::Hot</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#aa8309e74a87a287dfe316da0535c4722">AddCalls</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex/#a0e99a7c09395086976fe39e08dbe36a6">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::trySingleImplDevirt</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ae9f4748bfea60c7f38b8a1f4357b0150">anonymous{WholeProgramDevirt.cpp}::DevirtModule::trySingleImplDevirt</a>.</p>

</div>
</div>

### checkCombinedSummaryForTesting() {#a3f84f6f1a3f90b174404388b1bce971a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkCombinedSummaryForTesting (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * Summary)</td>
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



<p>Definition at line 988 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a9020e4076f17c245550360c81bb4702e">ClSummaryAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a67b09ea4ea9bc853c7893d7c5e61cec5">llvm::ModuleSummaryIndex::getRegularLTOModuleName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38a0bdae7fb49d99f161aa6de0379d7ea72d6d7a1885885bb55a565fd1070581a">llvm::Import</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#adf63c9ebc3de0773617afcdbd321f43b">anonymous{WholeProgramDevirt.cpp}::DevirtModule::runForTesting</a>.</p>

</div>
</div>

### mustBeUnreachableFunction() {#af640debffd735af4dfdeaf7dcb1ec2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool mustBeUnreachableFunction (<a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> TheFnVI)</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/valueinfo/#a5af9ad3b2fb92028275237b208fb89c3">llvm::ValueInfo::getSummaryList</a> and <a href="#a92e98b87a580ee2727a894cafc57a73e">WholeProgramDevirtKeepUnreachableFunction</a>.</p>

</div>
</div>

### skipUpdateDueToValidation() {#a9f247de1d62de65df435321729d15e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool skipUpdateDueToValidation (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; GV, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; IsVisibleToRegularObj)</td>
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



<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#aef569d822dbf572ae71954d6831ce8a9">llvm::GlobalObject::getMetadata</a> and <a href="#a3edf584072455be140ab0118e60cbf2d">typeIDVisibleToRegularObj</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af8b10064b29ab4bb0c85f28342ce72dd">llvm::updateVCallVisibilityInModule</a>.</p>

</div>
</div>

### STATISTIC() {#a32e51f776bd61eeb7797b58758cb6992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumDevirtTargets, "Number of whole program devirtualization targets")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a2649b20360647125896c6227a6cf8593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumSingleImpl, "Number of single implementation devirtualizations")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a149241ceac952de5c74e296e0a1e3f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumBranchFunnel, "Number of branch funnels")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#afa0e834431615385b92b415c9297519a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumUniformRetVal, "Number of uniform return value optimizations")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a2b2c8ae5dc78a0e3e76588b4ff3799fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumUniqueRetVal, "Number of unique return value optimizations")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a34ccb420b46ac0a5c0ad6c279bfb5d61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumVirtConstProp1Bit, "Number of 1 bit virtual constant propagations")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ab7bf15a60e2eaad1aad772f4fe7b89f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumVirtConstProp, "Number of virtual constant propagations")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

### typeIDVisibleToRegularObj() {#a3edf584072455be140ab0118e60cbf2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool typeIDVisibleToRegularObj (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeID, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; IsVisibleToRegularObj)</td>
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



<p>Definition at line 820 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7171872e2fc0462bcac2e88e41da9579">llvm::getVisibleToRegularObjVtableGUIDs</a> and <a href="#a9f247de1d62de65df435321729d15e89">skipUpdateDueToValidation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ClReadSummary {#a9cc0469b2ea8f4a2b3dbf68c0ec3ea57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; ClReadSummary("wholeprogramdevirt-read-summary", cl::desc( "Read summary from given bitcode or YAML file before running pass"), cl::Hidden)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

### ClSummaryAction {#a16f21389b7e3a9bbbe8eb56e7350f7ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; PassSummaryAction &gt; ClSummaryAction("wholeprogramdevirt-summary-action", cl::desc("What to do with the summary when running this pass"), cl::values(clEnumValN(PassSummaryAction::None, "none", "Do nothing"), clEnumValN(PassSummaryAction::Import, "import", "Import typeid resolutions from summary and globals"), clEnumValN(PassSummaryAction::Export, "export", "Export typeid resolutions to summary and globals")), cl::Hidden)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

### ClThreshold {#a72816be62cfd193f3cf78d55c0b29546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ClThreshold("wholeprogramdevirt-branch-funnel-threshold", cl::Hidden, cl::init(10), cl::desc("Maximum number of call targets per " "call site to enable branch funnels"))</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ad722656aa63d87c356ec659228865f65">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryICallBranchFunnel</a>.</p>

</div>
</div>

### ClWriteSummary {#a51db681461de4b51651e3b82923c93b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; ClWriteSummary("wholeprogramdevirt-write-summary", cl::desc("Write summary to given bitcode or YAML file after running pass. " "Output file format is deduced from extension: *.bc means writing " "bitcode, otherwise YAML"), cl::Hidden)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

### DevirtCheckMode {#a852c15f62fd7d543b4bde0c6010ba7ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; WPDCheckMode &gt; DevirtCheckMode("wholeprogramdevirt-check", cl::Hidden, cl::desc("Type of checking for incorrect devirtualizations"), cl::values(clEnumValN(WPDCheckMode::None, "none", "No checking"), clEnumValN(WPDCheckMode::Trap, "trap", "Trap when incorrect"), clEnumValN(WPDCheckMode::Fallback, "fallback", "Fallback to indirect when incorrect")))</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>.</p>

</div>
</div>

### DisableWholeProgramVisibility {#a02a51fbe29ad30cc1b0ad02e982078ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableWholeProgramVisibility("disable-whole-program-visibility", cl::Hidden, cl::desc("Disable whole program visibility (overrides enabling options)"))</td>
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

<p>Provide a way to force disable whole program for debugging or workarounds, when enabled via the linker.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5539cdf767bc394f56b5b8374c6b17d3">llvm::hasWholeProgramVisibility</a>.</p>

</div>
</div>

### PrintSummaryDevirt {#acf0749a3f0019d8d6f49681ae6a6bd51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintSummaryDevirt("wholeprogramdevirt-print-index-based", cl::Hidden, cl::desc("Print index-based devirtualization messages"))</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex/#ad6378f806ed88c9d72ddcb04dacd75ce">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::run</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex/#a0e99a7c09395086976fe39e08dbe36a6">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::trySingleImplDevirt</a>.</p>

</div>
</div>

### SkipFunctionNames {#a4acfa59172dc9825ef4c1362be8d31e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; SkipFunctionNames("wholeprogramdevirt-skip", cl::desc("Prevent function(s) from being devirtualized"), cl::Hidden, cl::CommaSeparated)</td>
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

<p>Provide way to prevent certain function from being devirtualized.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex/#aee5db647c9814cb99c752697414e3399">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::DevirtIndex</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ac7da757da2141faa2d1d0c429bd4e1e2">anonymous{WholeProgramDevirt.cpp}::DevirtModule::DevirtModule</a>.</p>

</div>
</div>

### WholeProgramDevirtCutoff {#acbc86a288e23ad77b686ef73a834a4c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; WholeProgramDevirtCutoff("wholeprogramdevirt-cutoff", cl::desc("Max number of devirtualizations for devirt module pass"), cl::init(0))</td>
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

<p>If explicitly specified, the devirt module pass will stop transformation once the total number of devirtualizations reach the cutoff value.</p>


<p>Setting this option to 0 explicitly will do 0 devirtualization.</p>


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>.</p>

</div>
</div>

### WholeProgramDevirtKeepUnreachableFunction {#a92e98b87a580ee2727a894cafc57a73e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; WholeProgramDevirtKeepUnreachableFunction("wholeprogramdevirt-keep-unreachable-function", cl::desc("Regard unreachable functions as possible devirtualize targets."), cl::Hidden, cl::init(true))</td>
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

<p>With Clang, a pure virtual class's deleting destructor is emitted as a <span class="doxyComputerOutput">llvm.trap</span> intrinsic followed by an unreachable IR instruction.</p>


<p>In the context of whole program devirtualization, the deleting destructor of a pure virtual class won't be invoked by the source code so safe to skip as a devirtualize target.</p>


<p>However, not all unreachable functions are safe to skip. In some cases, the program intends to run such functions and terminate, for instance, a unit test may run a death test. A non-test program might (or allowed to) invoke such functions to report failures (whether/when it's a good practice or not is a different topic).</p>


<p>This option is enabled to keep an unreachable function as a possible devirtualize target to conservatively keep the program behavior.</p>


<p>TODO: Make a pure virtual class's deleting destructor precisely identifiable in Clang's codegen for more devirtualization in LLVM.</p>


<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a91cdd27c8deb2678870c535c9205fcc4">anonymous{WholeProgramDevirt.cpp}::DevirtModule::mustBeUnreachableFunction</a> and <a href="#af640debffd735af4dfdeaf7dcb1ec2a1">mustBeUnreachableFunction</a>.</p>

</div>
</div>

### WholeProgramVisibility {#a2886290cb6ad3d8ddf30d1e8035a235c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; WholeProgramVisibility("whole-program-visibility", cl::Hidden, cl::desc("Enable whole program visibility"))</td>
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

<p>Provide a way to force enable whole program visibility in tests.</p>


<p>This is needed to support legacy tests that don't contain !vcall_visibility metadata (the mere presense of type tests previously implied hidden visibility).</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5539cdf767bc394f56b5b8374c6b17d3">llvm::hasWholeProgramVisibility</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"wholeprogramdevirt"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
