---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/legacypassmanager-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LegacyPassManager.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">llvm/IR/LegacyPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irprintingpasses-h">llvm/IR/IRPrintingPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">llvm/IR/LegacyPassManagers.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passtiminginfo-h">llvm/IR/PassTimingInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/printpasses-h">llvm/IR/PrintPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/chrono-h">llvm/Support/Chrono.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timeprofiler-h">llvm/Support/TimeProfiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timer-h">llvm/Support/Timer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-legacypassmanager-cpp-">anonymous{LegacyPassManager.cpp}</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/legacy">legacy</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecfc696c759c52249220099347df84da">UseNewDbgInfoFormat</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; enum PassDebugLevel &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2826de8d07a024768740aec3f6f99dc">PassDebugging</a>("debug-pass", cl::Hidden, cl::desc("Print legacy PassManager debugging information"), cl::values(clEnumVal(Disabled, "disable debug output"), clEnumVal(Arguments, "print pass arguments to pass to 'opt'"), clEnumVal(Structure, "print pass structure before run()"), clEnumVal(Executions, "print pass name before it is executed"), clEnumVal(Details, "print pass details when it is executed")))</td>
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

## Variables

### PassDebugging {#af2826de8d07a024768740aec3f6f99dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; enum PassDebugLevel &gt; PassDebugging("debug-pass", cl::Hidden, cl::desc("Print legacy PassManager debugging information"), cl::values(clEnumVal(Disabled, "disable debug output"), clEnumVal(Arguments, "print pass arguments to pass to 'opt'"), clEnumVal(Structure, "print pass structure before run()"), clEnumVal(Executions, "print pass name before it is executed"), clEnumVal(Details, "print pass details when it is executed")))</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/legacy/#a69f210423dc938bf8104c32ccee0d6eb">llvm::legacy::debugPassSpecified</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a9bcf6682702cbde1eeeb006b7e49cf62">llvm::PMTopLevelManager::dumpArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a0ced924c11b3eddbfccd9c186f38a389">llvm::PMDataManager::dumpLastUses</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#aa58716ef5ab4c044f1f90f257bf91e6a">llvm::PMTopLevelManager::dumpPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aff93635e4ea28861beb90faece603b3d">llvm::PMDataManager::dumpPassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#adfe9cc105a283f4d7e4e56c6d4440adb">llvm::PMDataManager::dumpPreservedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a799e97f6f38435a58b8ecf6a85eb7399">llvm::PMDataManager::dumpRequiredSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#af71955a48208ff25a6c8b5f6f2890417">llvm::PMDataManager::dumpUsedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a38a662fbda7962b4e36e614ac16062c9">llvm::PMDataManager::isPassDebuggingExecutionsOrMore</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a09ac67e36db813f2a3e69173f7638037">llvm::PMDataManager::removeDeadPasses</a> and <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#af740891e192aa63a0fbbfe317301cbdb">llvm::PMDataManager::removeNotPreservedAnalysis</a>.</p>

</div>
</div>

### UseNewDbgInfoFormat {#aecfc696c759c52249220099347df84da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; UseNewDbgInfoFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
