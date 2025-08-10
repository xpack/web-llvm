---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/targetpassconfig-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `TargetPassConfig.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/basicaliasanalysis-h">llvm/Analysis/BasicAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">llvm/Analysis/CallGraphSCCPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scopednoaliasaa-h">llvm/Analysis/ScopedNoAliasAA.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">llvm/Analysis/TypeBasedAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">llvm/CodeGen/BasicBlockSectionsProfileReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/cseconfigbase-h">llvm/CodeGen/CSEConfigBase.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegentargetmachineimpl-h">llvm/CodeGen/CodeGenTargetMachineImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepassregistry-h">llvm/CodeGen/MachinePassRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">llvm/CodeGen/RegAllocRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irprintingpasses-h">llvm/IR/IRPrintingPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">llvm/IR/LegacyPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">llvm/IR/PassInstrumentation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">llvm/IR/Verifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">llvm/Support/CodeGen.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h">llvm/Support/Discriminator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/saveandrestore-h">llvm/Support/SaveAndRestore.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">llvm/Support/Threading.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">llvm/Support/WithColor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/cgpassbuilderoption-h">llvm/Target/CGPassBuilderOption.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/objcarc-h">llvm/Transforms/ObjCARC.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/scalar-h">llvm/Transforms/Scalar.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/utils-h">llvm/Transforms/Utils.h</a>"
#include &lt;cassert&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/initialize-pass">INITIALIZE_PASS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a>. <a href="/web-llvm/docs/api/namespaces/initialize-pass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/initialize-pass/insertedpass">InsertedPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passconfigimpl">PassConfigImpl</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/identifyingpassptr">IdentifyingPassPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc4cdd2f2a06f7a2f5f880fb98e78c6">applyDisable</a> (IdentifyingPassPtr PassID, bool Override)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow standard passes to be disabled by command line options. <a href="#aadc4cdd2f2a06f7a2f5f880fb98e78c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/identifyingpassptr">IdentifyingPassPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> (AnalysisID StandardID, IdentifyingPassPtr TargetID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow standard passes to be disabled by the command line, regardless of who is adding the pass. <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3a0aa6f7fa6a74d1af3ca21fbe3e39a">getFSProfileFile</a> (const TargetMachine *TM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a377b60f1ad7bd50ebecab462d9258896">getFSRemappingFile</a> (const TargetMachine *TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fd5fd11f1d85fee7e28a197e915aa0d">getPassInfo</a> (StringRef PassName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c5faae50cf1ccc5bf0d1936557030ec">getPassIDFromName</a> (StringRef PassName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d52a5b3d278b07fa7992477cc3c5474">getPassNameAndInstanceNum</a> (StringRef PassName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28529cf510b576b2120abfad90d6a9c3">useDefaultRegisterAllocator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>-regalloc=... command line option. <a href="#a28529cf510b576b2120abfad90d6a9c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cd1b5df9d07c4cea37c4677055341a9">initializeDefaultRegisterAllocatorOnce</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fcb229237316202c5643e864a7dd5b7">EnableIPRA</a>("enable-ipra", cl::init(false), cl::Hidden, cl::desc("Enable interprocedural register allocation " "to reduce load/store at procedure calls."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b4945fed28fc3d0788e1a6233e6743">DisablePostRASched</a>("disable-post-ra", cl::Hidden, cl::desc("Disable Post Regalloc Scheduler"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1573caf1ac588729497c390e1fbce33">DisableBranchFold</a>("disable-branch-fold", cl::Hidden, cl::desc("Disable branch folding"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982818ef1bd50f5a3840680d7bf0406f">DisableTailDuplicate</a>("disable-tail-duplicate", cl::Hidden, cl::desc("Disable tail duplication"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab336ebad07a345e6f2454ddb405de76f">DisableEarlyTailDup</a>("disable-early-taildup", cl::Hidden, cl::desc("Disable pre-register allocation tail duplication"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7307abffefcf592698c3cdb5b5eafa3f">DisableBlockPlacement</a>("disable-block-placement", cl::Hidden, cl::desc("Disable probability-driven block placement"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b85a59ddb4b9d2442a91103206e99a8">EnableBlockPlacementStats</a>("enable-block-placement-stats", cl::Hidden, cl::desc("Collect probability-driven block placement stats"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c86659c42897727dee87a569206f10">DisableSSC</a>("disable-ssc", cl::Hidden, cl::desc("Disable Stack Slot Coloring"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f23ca5722402b94439dba4640c965e">DisableMachineDCE</a>("disable-machine-dce", cl::Hidden, cl::desc("Disable Machine Dead Code Elimination"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8577496ffdbef54d40e9bbd1d52b4b">DisableEarlyIfConversion</a>("disable-early-ifcvt", cl::Hidden, cl::desc("Disable Early If-conversion"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9690325041d5f5b98a687e7c87613359">DisableMachineLICM</a>("disable-machine-licm", cl::Hidden, cl::desc("Disable Machine LICM"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca6f6c306312feee4de80aa2af101fc">DisableMachineCSE</a>("disable-machine-cse", cl::Hidden, cl::desc("Disable Machine Common Subexpression Elimination"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44">cl::boolOrDefault</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef990f408b84ac05c67735579e5c3ac0">OptimizeRegAlloc</a>("optimize-regalloc", cl::Hidden, cl::desc("Enable optimized register allocation compilation path."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3f73ff8f479b9456816310fec99d30">DisablePostRAMachineLICM</a>("disable-postra-machine-licm", cl::Hidden, cl::desc("Disable Machine LICM"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dd52f27168c302a4839a340b8ae0128">DisableMachineSink</a>("disable-machine-sink", cl::Hidden, cl::desc("Disable Machine Sinking"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c5133319a2d941f81372b943d99ec1b">DisablePostRAMachineSink</a>("disable-postra-machine-sink", cl::Hidden, cl::desc("Disable PostRA Machine Sinking"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0261437738888dacdb69091296bc08d">DisableLSR</a>("disable-lsr", cl::Hidden, cl::desc("Disable Loop Strength Reduction Pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3a92e813bb04060b35c07844158b6ea">DisableConstantHoisting</a>("disable-constant-hoisting", cl::Hidden, cl::desc("Disable ConstantHoisting"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa230af5948fe3d62a51ecd26e741428f">DisableCGP</a>("disable-cgp", cl::Hidden, cl::desc("Disable Codegen Prepare"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc0f2984714c731d0e5f5d5fccb3191">DisableCopyProp</a>("disable-copyprop", cl::Hidden, cl::desc("Disable Copy Propagation pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e53a219aa47fbe42d25db8a8347b80">DisablePartialLibcallInlining</a>("disable-partial-libcall-inlining", cl::Hidden, cl::desc("Disable Partial Libcall Inlining"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec2182d411cc891680b677e628afbe7">DisableAtExitBasedGlobalDtorLowering</a>("disable-atexit-based-global-dtor-lowering", cl::Hidden, cl::desc("For MachO, disable atexit()-based global destructor lowering"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d21654b247d5eeed228cb34f7e5d43">EnableImplicitNullChecks</a>("enable-implicit-null-checks", cl::desc("Fold null checks into faulting memory operations"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5ce995b824a3550e33c09e50dc40f52">DisableMergeICmps</a>("disable-mergeicmps", cl::desc("Disable MergeICmps Pass"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2299fa2c21b5a1fc242277cbc08a739b">PrintISelInput</a>("print-isel-input", cl::Hidden, cl::desc("Print LLVM IR input to isel pass"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44">cl::boolOrDefault</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b5ce4f0064aa134408b5e3893b7e9a9">VerifyMachineCode</a>("verify-machineinstrs", cl::Hidden, cl::desc("Verify generated machine code"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44">cl::boolOrDefault</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14168232865ff09f2d3ad739add14ac2">DebugifyAndStripAll</a>("debugify-and-strip-all-safe", cl::Hidden, cl::desc("Debugify MIR before and Strip debug after " "each pass except those known to be unsafe " "when debug info is present"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44">cl::boolOrDefault</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af96729c00184c0c3bcf16e87970f2a66">DebugifyCheckAndStripAll</a>("debugify-check-and-strip-all-safe", cl::Hidden, cl::desc("Debugify MIR before, by checking and stripping the debug info after, " "each pass except those known to be unsafe when debug info is " "present"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ad16d2d781480402236239b1a788d96c2">RunOutliner</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5dd57fe00bc1a361772ad1b5c2a1e7a">EnableMachineOutliner</a>("enable-machine-outliner", cl::desc("Enable the machine outliner"), cl::Hidden, cl::ValueOptional, cl::init(RunOutliner::TargetDefault), cl::values(clEnumValN(RunOutliner::AlwaysOutline, "always", "Run on all functions guaranteed to be beneficial"), clEnumValN(RunOutliner::NeverOutline, "never", "Disable all outlining"), clEnumValN(RunOutliner::AlwaysOutline, "", "")))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab836a5e004fbd2222bd8c33855fb261f">EnableGlobalMergeFunc</a>("enable-global-merge-func", cl::Hidden, cl::desc("Enable global merge functions that are based on hash function"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ee863797dd338d939c22158b0fa790">DisableCFIFixup</a>("disable-cfi-fixup", cl::Hidden, cl::desc("Disable the CFI fixup pass"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44">cl::boolOrDefault</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab52b96d1a3411ab27fabf09fe3bbc470">EnableFastISelOption</a>("fast-isel", cl::Hidden, cl::desc("Enable the \"fast\" instruction selector"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44">cl::boolOrDefault</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96ee83741efbaafdb0df1eb8eff27d1b">EnableGlobalISelOption</a>("global-isel", cl::Hidden, cl::desc("Enable the \"global\" instruction selector"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d7d3b681d1917147ae0150ec7a8c079">PrintAfterISel</a>("print-after-isel", cl::init(false), cl::Hidden, cl::desc("Print machine instrs after ISel"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af69c47ced839e86a65b94b0a33ee5c2a">GlobalISelAbortMode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20e964f01df782dce21a79324824bc8">EnableGlobalISelAbort</a>("global-isel-abort", cl::Hidden, cl::desc("Enable abort calls when \"global\" instruction selection " "fails to lower/select an instruction"), cl::values(clEnumValN(GlobalISelAbortMode::Disable, "0", "Disable the abort"), clEnumValN(GlobalISelAbortMode::Enable, "1", "Enable the abort"), clEnumValN(GlobalISelAbortMode::DisableWithDiag, "2", "Disable the abort but emit a diagnostic on failure")))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a754b4f2d62c2cb8a9a172e08e3556bdd">DisableRAFSProfileLoader</a>("disable-ra-fsprofile-loader", cl::init(false), cl::Hidden, cl::desc("Disable MIRProfileLoader before RegAlloc"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9f9751dfb368fdd6db8d296f6b9cb2a">DisableLayoutFSProfileLoader</a>("disable-layout-fsprofile-loader", cl::init(false), cl::Hidden, cl::desc("Disable MIRProfileLoader before BlockPlacement"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af666c434131d8e60b8978afc46f7af4e">FSProfileFile</a>("fs-profile-file", cl::init(""), cl::value_desc("filename"), cl::desc("Flow Sensitive profile file name."), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a814700c705e4876b0f7fbca69811ba72">FSRemappingFile</a>("fs-remapping-file", cl::init(""), cl::value_desc("filename"), cl::desc("Flow Sensitive profile remapping file name."), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36047825707739faa5a23dc3e7a8953">MISchedPostRA</a>("misched-postra", cl::Hidden, cl::desc("Run MachineScheduler post regalloc (independent of preRA sched)"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ffb2e528b44f0c9a785d0458264ba03">EarlyLiveIntervals</a>("early-live-intervals", cl::Hidden, cl::desc("Run live interval analysis earlier in the pipeline"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a412dd9d0ed67856ff755ca2264d3e7b4">DisableReplaceWithVecLib</a>("disable-replace-with-vec-lib", cl::Hidden, cl::desc("Disable replace with vector math call pass"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d2c0d6ec280e108ba4b506decb8e11c">StartAfterOptName</a>[] = "start-after"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Option names for limiting the codegen pipeline. <a href="#a9d2c0d6ec280e108ba4b506decb8e11c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea67ebcc3278fadd1a83adbd6f0d5e0">StartBeforeOptName</a>[] = "start-before"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e8e4a2abcc0867c475e6cec4d48c07">StopAfterOptName</a>[] = "stop-after"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b2567373b80b37bcdabfa129c003a46">StopBeforeOptName</a>[] = "stop-before"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d4e751a7a3000d9acfd17e8f705a47a">StartAfterOpt</a>(StringRef(StartAfterOptName), cl::desc("Resume compilation after a specific pass"), cl::value_desc("pass-name"), cl::init(""), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a24b91142e981f7915594033a8aa26">StartBeforeOpt</a>(StringRef(StartBeforeOptName), cl::desc("Resume compilation before a specific pass"), cl::value_desc("pass-name"), cl::init(""), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a783106f63c0504ebca077096fae4dec7">StopAfterOpt</a>(StringRef(StopAfterOptName), cl::desc("Stop compilation after a specific pass"), cl::value_desc("pass-name"), cl::init(""), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6cb7266b461861bc32a0d0798362a17">StopBeforeOpt</a>(StringRef(StopBeforeOptName), cl::desc("Stop compilation before a specific pass"), cl::value_desc("pass-name"), cl::init(""), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a416aab325bbbf945515a41696363f511">EnableMachineFunctionSplitter</a>("enable-split-machine-functions", cl::Hidden, cl::desc("Split out cold blocks from machine functions based on profile " "information."))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable the machine function splitter pass. <a href="#a416aab325bbbf945515a41696363f511">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06cace0c7d26e9dc86c2586a987fe20e">DisableExpandReductions</a>("disable-expand-reductions", cl::init(false), cl::Hidden, cl::desc("Disable the expand reduction intrinsics pass from running"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable the expand reductions pass for testing. <a href="#a06cace0c7d26e9dc86c2586a987fe20e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e81429317cf832a7e2367c98629474f">DisableSelectOptimize</a>("disable-select-optimize", cl::init(true), cl::Hidden, cl::desc("Disable the select-optimization pass from running"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable the select optimization pass. <a href="#a7e81429317cf832a7e2367c98629474f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06dbeeeecd4faac66a1476f67e5a256">GCEmptyBlocks</a>("gc-empty-basic-blocks", cl::init(false), cl::Hidden, cl::desc("Enable garbage-collecting empty basic blocks"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable garbage-collecting empty basic blocks. <a href="#ab06dbeeeecd4faac66a1476f67e5a256">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a5027ab1515cef6c0779b6db4adef1">SplitStaticData</a>("split-static-data", cl::Hidden, cl::init(false), cl::desc("Split static data sections into hot and cold " "sections using profile information"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; RegisterRegAlloc::FunctionPassCtor, false, <a href="/web-llvm/docs/api/classes/llvm/registerpassparser">RegisterPassParser</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/registerregalloc">RegisterRegAlloc</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ad36388c3fc5c02ed576b30e636c26">RegAlloc</a>("regalloc", cl::Hidden, cl::init(&useDefaultRegisterAllocator), cl::desc("Register allocator to use"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/once-flag">llvm::once_flag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a22a0a83da7865dbf36273336891542">InitializeDefaultRegisterAllocatorFlag</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A dummy default pass factory indicates whether the register allocator is overridden on the command line. <a href="#a1a22a0a83da7865dbf36273336891542">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/registerregalloc">RegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5ee87120bee5ec52c2aae7bebf74063">defaultRegAlloc</a>("default", "pick register allocator based on -O option", useDefaultRegisterAllocator)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc50b9b81c1d03c606a12cfa0ce094dc">SET_OPTION</a>(Option)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657504030de6b1a3c580878f1c1632c1">SET_BOOLEAN_OPTION</a>(Option)&nbsp;&nbsp;&nbsp;Opt.Option = Option;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac37c74de68ba47bcdda14bf70e4cadec">DISABLE_PASS</a>(Option, Name)&nbsp;&nbsp;&nbsp;...</td>
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

## Functions

### applyDisable() {#aadc4cdd2f2a06f7a2f5f880fb98e78c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IdentifyingPassPtr applyDisable (<a href="/web-llvm/docs/api/classes/llvm/identifyingpassptr">IdentifyingPassPtr</a> PassID, bool Override)</td>
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

<p>Allow standard passes to be disabled by command line options.</p>


<p>This supports simple binary flags that either suppress the pass or do nothing. i.e. -disable-mypass=false has no effect. These should be converted to boolOrDefault in order to use applyOverride.</p>


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a>.</p>

</div>
</div>

### getFSProfileFile() {#aa3a0aa6f7fa6a74d1af3ca21fbe3e39a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getFSProfileFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM)</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>References <a href="#af666c434131d8e60b8978afc46f7af4e">FSProfileFile</a> and <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4f011091f5fa9e924c851251a4293a20">llvm::TargetPassConfig::addBlockPlacement</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a>.</p>

</div>
</div>

### getFSRemappingFile() {#a377b60f1ad7bd50ebecab462d9258896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getFSRemappingFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM)</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>References <a href="#a814700c705e4876b0f7fbca69811ba72">FSRemappingFile</a> and <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4f011091f5fa9e924c851251a4293a20">llvm::TargetPassConfig::addBlockPlacement</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a>.</p>

</div>
</div>

### getPassIDFromName() {#a3c5faae50cf1ccc5bf0d1936557030ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisID getPassIDFromName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>References <a href="#a8fd5fd11f1d85fee7e28a197e915aa0d">getPassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/passinfo/#afa9af549f3d775035bdc272c1f35d632">llvm::PassInfo::getTypeInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>

</div>
</div>

### getPassInfo() {#a8fd5fd11f1d85fee7e28a197e915aa0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PassInfo * getPassInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a58f089b4fc400d1bfb6f2e6d21a00dbb">llvm::PassRegistry::getPassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a43fed8d1dfacc9362ed5b08f841782f8">llvm::PMTopLevelManager::findAnalysisPassInfo</a> and <a href="#a3c5faae50cf1ccc5bf0d1936557030ec">getPassIDFromName</a>.</p>

</div>
</div>

### getPassNameAndInstanceNum() {#a4d52a5b3d278b07fa7992477cc3c5474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; StringRef, unsigned &gt; getPassNameAndInstanceNum (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a2adec695334610982e70d013e958a4fd">llvm::TargetPassConfig::getStartStopInfo</a>.</p>

</div>
</div>

### initializeDefaultRegisterAllocatorOnce() {#a7cd1b5df9d07c4cea37c4677055341a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initializeDefaultRegisterAllocatorOnce ()</td>
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



<p>Definition at line 1350 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a64385ccd715f0aa796300d361b525e4c">llvm::RegisterRegAllocBase&lt; RegisterRegAlloc &gt;::getDefault</a>, <a href="#a21ad36388c3fc5c02ed576b30e636c26">RegAlloc</a> and <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a96bb0f039016d0b9999a18a660a38f5b">llvm::RegisterRegAllocBase&lt; RegisterRegAlloc &gt;::setDefault</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a521c0fd2e8307b5b136c2e8b984a9316">llvm::TargetPassConfig::createRegAllocPass</a>.</p>

</div>
</div>

### overridePass() {#a44e47b2bfc045db917bcbfbaf8be40ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IdentifyingPassPtr overridePass (<a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> StandardID, <a href="/web-llvm/docs/api/classes/llvm/identifyingpassptr">IdentifyingPassPtr</a> TargetID)</td>
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

<p>Allow standard passes to be disabled by the command line, regardless of who is adding the pass.</p>


<p>StandardID is the pass identified in the standard pass pipeline and provided to addPass(). It may be a target-specific <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> in the case that the target directly adds its own pass, but in that case we harmlessly fall through.</p>


<p>TargetID is the pass that the target has configured to override StandardID.</p>


<p>StandardID may be a pseudo <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. In that case TargetID is the name of the real pass to run. This allows multiple options to control a single pass depending on where in the pipeline that pass is added.</p>


<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>References <a href="#aadc4cdd2f2a06f7a2f5f880fb98e78c6">applyDisable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae39ec6579da91ce8fa292f0a7205d98d">llvm::BranchFolderPassID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af84508d5d676c86da43af3573b6297ea">llvm::DeadMachineInstructionElimID</a>, <a href="#a7307abffefcf592698c3cdb5b5eafa3f">DisableBlockPlacement</a>, <a href="#ac1573caf1ac588729497c390e1fbce33">DisableBranchFold</a>, <a href="#aebc0f2984714c731d0e5f5d5fccb3191">DisableCopyProp</a>, <a href="#a3c8577496ffdbef54d40e9bbd1d52b4b">DisableEarlyIfConversion</a>, <a href="#ab336ebad07a345e6f2454ddb405de76f">DisableEarlyTailDup</a>, <a href="#acca6f6c306312feee4de80aa2af101fc">DisableMachineCSE</a>, <a href="#a33f23ca5722402b94439dba4640c965e">DisableMachineDCE</a>, <a href="#a9690325041d5f5b98a687e7c87613359">DisableMachineLICM</a>, <a href="#a0dd52f27168c302a4839a340b8ae0128">DisableMachineSink</a>, <a href="#a8b3f73ff8f479b9456816310fec99d30">DisablePostRAMachineLICM</a>, <a href="#a9c5133319a2d941f81372b943d99ec1b">DisablePostRAMachineSink</a>, <a href="#a29b4945fed28fc3d0788e1a6233e6743">DisablePostRASched</a>, <a href="#ab5c86659c42897727dee87a569206f10">DisableSSC</a>, <a href="#a982818ef1bd50f5a3840680d7bf0406f">DisableTailDuplicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57e66365c51f9fe42173246196dc25f1">llvm::EarlyIfConverterLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08efde8583f615980c38b4e29760fae8">llvm::EarlyMachineLICMID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab82e9cd8759ab1db940ed0389c68d920">llvm::EarlyTailDuplicateLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc14e69cab3ee0a21fdfdd40632b7ee1">llvm::MachineBlockPlacementID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af5dc78ed1fd5966782d85bf389333790">llvm::MachineCopyPropagationID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab243cd86bbcb539fad948485fad842fc">llvm::MachineCSELegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec913d7a94874651981c1017ac8ef6e0">llvm::MachineLICMID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a307065c6152b458d2b8ceaea1823d7">llvm::MachineSinkingID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d5462b10402ee83291fda8b0b74f437">llvm::PostRAMachineSinkingID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f5fd09bcdb3ea958016747ab1e9f4f7">llvm::PostRASchedulerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a947df27369e5b0e5d44b3109f1cc592d">llvm::StackSlotColoringID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a35f37733d6182da960aeaa10f5df2e16">llvm::TailDuplicateLegacyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abbdfb7c510cf5e39fa2d7a5c7d83b8f1">llvm::TargetPassConfig::isPassSubstitutedOrOverridden</a>.</p>

</div>
</div>

### useDefaultRegisterAllocator() {#a28529cf510b576b2120abfad90d6a9c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * useDefaultRegisterAllocator ()</td>
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

<p>-regalloc=... command line option.</p>

<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a662881e8843762cf5faebe3885d8f482">llvm::TargetPassConfig::addRegAssignAndRewriteFast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a521c0fd2e8307b5b136c2e8b984a9316">llvm::TargetPassConfig::createRegAllocPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a6f81ebaba440d56ca78c806f562c9a1b">llvm::TargetPassConfig::isCustomizedRegAlloc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DebugifyAndStripAll {#a14168232865ff09f2d3ad739add14ac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; cl::boolOrDefault &gt; DebugifyAndStripAll("debugify-and-strip-all-safe", cl::Hidden, cl::desc("Debugify MIR before and Strip debug after " "each pass except those known to be unsafe " "when debug info is present"))</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a3934493a220cc8501fecdb1b46ed53b5">llvm::TargetPassConfig::addMachinePostPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ad19c346784e85496fca879ea9b36fb8e">llvm::TargetPassConfig::addMachinePrePasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### DebugifyCheckAndStripAll {#af96729c00184c0c3bcf16e87970f2a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; cl::boolOrDefault &gt; DebugifyCheckAndStripAll("debugify-check-and-strip-all-safe", cl::Hidden, cl::desc( "Debugify MIR before, by checking and stripping the debug info after, " "each pass except those known to be unsafe when debug info is " "present"))</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a3934493a220cc8501fecdb1b46ed53b5">llvm::TargetPassConfig::addMachinePostPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ad19c346784e85496fca879ea9b36fb8e">llvm::TargetPassConfig::addMachinePrePasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### defaultRegAlloc {#ac5ee87120bee5ec52c2aae7bebf74063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterRegAlloc defaultRegAlloc("default", "pick register allocator based on -O option", useDefaultRegisterAllocator)</td>
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



<p>Definition at line 1346 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>

</div>
</div>

### DisableAtExitBasedGlobalDtorLowering {#a1ec2182d411cc891680b677e628afbe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableAtExitBasedGlobalDtorLowering("disable-atexit-based-global-dtor-lowering", cl::Hidden, cl::desc("For MachO, disable atexit()-based global destructor lowering"))</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### DisableBlockPlacement {#a7307abffefcf592698c3cdb5b5eafa3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableBlockPlacement("disable-block-placement", cl::Hidden, cl::desc("Disable probability-driven block placement"))</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisableBranchFold {#ac1573caf1ac588729497c390e1fbce33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableBranchFold("disable-branch-fold", cl::Hidden, cl::desc("Disable branch folding"))</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisableCFIFixup {#a85ee863797dd338d939c22158b0fa790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableCFIFixup("disable-cfi-fixup", cl::Hidden, cl::desc("Disable the CFI fixup pass"))</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### DisableCGP {#aa230af5948fe3d62a51ecd26e741428f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableCGP("disable-cgp", cl::Hidden, cl::desc("Disable Codegen Prepare"))</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a3082a93fec84f7658664ce7b4840b15c">llvm::TargetPassConfig::addCodeGenPrepare</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### DisableConstantHoisting {#ab3a92e813bb04060b35c07844158b6ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableConstantHoisting("disable-constant-hoisting", cl::Hidden, cl::desc("Disable ConstantHoisting"))</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### DisableCopyProp {#aebc0f2984714c731d0e5f5d5fccb3191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableCopyProp("disable-copyprop", cl::Hidden, cl::desc("Disable Copy Propagation pass"))</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisableEarlyIfConversion {#a3c8577496ffdbef54d40e9bbd1d52b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableEarlyIfConversion("disable-early-ifcvt", cl::Hidden, cl::desc("Disable Early If-conversion"))</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisableEarlyTailDup {#ab336ebad07a345e6f2454ddb405de76f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableEarlyTailDup("disable-early-taildup", cl::Hidden, cl::desc("Disable pre-register allocation tail duplication"))</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisableExpandReductions {#a06cace0c7d26e9dc86c2586a987fe20e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableExpandReductions("disable-expand-reductions", cl::init(false), cl::Hidden, cl::desc("Disable the expand reduction intrinsics pass from running"))</td>
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

<p>Disable the expand reductions pass for testing.</p>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### DisableLayoutFSProfileLoader {#ad9f9751dfb368fdd6db8d296f6b9cb2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableLayoutFSProfileLoader("disable-layout-fsprofile-loader", cl::init(false), cl::Hidden, cl::desc("Disable MIRProfileLoader before BlockPlacement"))</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4f011091f5fa9e924c851251a4293a20">llvm::TargetPassConfig::addBlockPlacement</a>.</p>

</div>
</div>

### DisableLSR {#af0261437738888dacdb69091296bc08d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableLSR("disable-lsr", cl::Hidden, cl::desc("Disable Loop Strength Reduction Pass"))</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### DisableMachineCSE {#acca6f6c306312feee4de80aa2af101fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableMachineCSE("disable-machine-cse", cl::Hidden, cl::desc("Disable Machine Common Subexpression Elimination"))</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisableMachineDCE {#a33f23ca5722402b94439dba4640c965e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableMachineDCE("disable-machine-dce", cl::Hidden, cl::desc("Disable Machine Dead Code Elimination"))</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisableMachineLICM {#a9690325041d5f5b98a687e7c87613359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableMachineLICM("disable-machine-licm", cl::Hidden, cl::desc("Disable Machine LICM"))</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisableMachineSink {#a0dd52f27168c302a4839a340b8ae0128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableMachineSink("disable-machine-sink", cl::Hidden, cl::desc("Disable Machine Sinking"))</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisableMergeICmps {#ae5ce995b824a3550e33c09e50dc40f52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableMergeICmps("disable-mergeicmps", cl::desc("Disable MergeICmps Pass"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### DisablePartialLibcallInlining {#a60e53a219aa47fbe42d25db8a8347b80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisablePartialLibcallInlining("disable-partial-libcall-inlining", cl::Hidden, cl::desc("Disable Partial Libcall Inlining"))</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### DisablePostRAMachineLICM {#a8b3f73ff8f479b9456816310fec99d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisablePostRAMachineLICM("disable-postra-machine-licm", cl::Hidden, cl::desc("Disable Machine LICM"))</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisablePostRAMachineSink {#a9c5133319a2d941f81372b943d99ec1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisablePostRAMachineSink("disable-postra-machine-sink", cl::Hidden, cl::desc("Disable PostRA Machine Sinking"))</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisablePostRASched {#a29b4945fed28fc3d0788e1a6233e6743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisablePostRASched("disable-post-ra", cl::Hidden, cl::desc("Disable Post Regalloc Scheduler"))</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisableRAFSProfileLoader {#a754b4f2d62c2cb8a9a172e08e3556bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableRAFSProfileLoader("disable-ra-fsprofile-loader", cl::init(false), cl::Hidden, cl::desc("Disable MIRProfileLoader before RegAlloc"))</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### DisableReplaceWithVecLib {#a412dd9d0ed67856ff755ca2264d3e7b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableReplaceWithVecLib("disable-replace-with-vec-lib", cl::Hidden, cl::desc("Disable replace with vector math call pass"))</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>.</p>

</div>
</div>

### DisableSelectOptimize {#a7e81429317cf832a7e2367c98629474f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableSelectOptimize("disable-select-optimize", cl::init(true), cl::Hidden, cl::desc("Disable the select-optimization pass from running"))</td>
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

<p>Disable the select optimization pass.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86cmovconversion-cpp-/x86cmovconverterpass/#a2b90fb87402f7118da2019ae5b84f0b1">anonymous{X86CmovConversion.cpp}::X86CmovConverterPass::runOnMachineFunction</a>.</p>

</div>
</div>

### DisableSSC {#ab5c86659c42897727dee87a569206f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableSSC("disable-ssc", cl::Hidden, cl::desc("Disable Stack Slot Coloring"))</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### DisableTailDuplicate {#a982818ef1bd50f5a3840680d7bf0406f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableTailDuplicate("disable-tail-duplicate", cl::Hidden, cl::desc("Disable tail duplication"))</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a44e47b2bfc045db917bcbfbaf8be40ac">overridePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### EarlyLiveIntervals {#a8ffb2e528b44f0c9a785d0458264ba03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EarlyLiveIntervals("early-live-intervals", cl::Hidden, cl::desc("Run live interval analysis earlier in the pipeline"))</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a6481662c2fc1eb7d95b5a32939e24b94">llvm::TargetPassConfig::addOptimizedRegAlloc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### EnableBlockPlacementStats {#a2b85a59ddb4b9d2442a91103206e99a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableBlockPlacementStats("enable-block-placement-stats", cl::Hidden, cl::desc("Collect probability-driven block placement stats"))</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4f011091f5fa9e924c851251a4293a20">llvm::TargetPassConfig::addBlockPlacement</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### EnableFastISelOption {#ab52b96d1a3411ab27fabf09fe3bbc470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; cl::boolOrDefault &gt; EnableFastISelOption("fast-isel", cl::Hidden, cl::desc("Enable the \"fast\" instruction selector"))</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abd0a30a0d745cbd0dbdbc8bdf18afe7e">llvm::TargetPassConfig::addCoreISelPasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### EnableGlobalISelAbort {#ab20e964f01df782dce21a79324824bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; GlobalISelAbortMode &gt; EnableGlobalISelAbort("global-isel-abort", cl::Hidden, cl::desc("Enable abort calls when \"global\" instruction selection " "fails to lower/select an instruction"), cl::values( clEnumValN(GlobalISelAbortMode::Disable, "0", "Disable the abort"), clEnumValN(GlobalISelAbortMode::Enable, "1", "Enable the abort"), clEnumValN(GlobalISelAbortMode::DisableWithDiag, "2", "Disable the abort but emit a diagnostic on failure")))</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a>.</p>

</div>
</div>

### EnableGlobalISelOption {#a96ee83741efbaafdb0df1eb8eff27d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; cl::boolOrDefault &gt; EnableGlobalISelOption("global-isel", cl::Hidden, cl::desc("Enable the \"global\" instruction selector"))</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abd0a30a0d745cbd0dbdbc8bdf18afe7e">llvm::TargetPassConfig::addCoreISelPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#aef67bcdb0247f9b4b984725fa065e1ce">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitPHINode</a>.</p>

</div>
</div>

### EnableGlobalMergeFunc {#ab836a5e004fbd2222bd8c33855fb261f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGlobalMergeFunc("enable-global-merge-func", cl::Hidden, cl::desc("Enable global merge functions that are based on hash function"))</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### EnableImplicitNullChecks {#a06d21654b247d5eeed228cb34f7e5d43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableImplicitNullChecks("enable-implicit-null-checks", cl::desc("Fold null checks into faulting memory operations"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### EnableIPRA {#a9fcb229237316202c5643e864a7dd5b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableIPRA("enable-ipra", cl::init(false), cl::Hidden, cl::desc("Enable interprocedural register allocation " "to reduce load/store at procedure calls."))</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a>.</p>

</div>
</div>

### EnableMachineFunctionSplitter {#a416aab325bbbf945515a41696363f511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableMachineFunctionSplitter("enable-split-machine-functions", cl::Hidden, cl::desc("Split out cold blocks from machine functions based on profile " "information."))</td>
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

<p>Enable the machine function splitter pass.</p>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a> and <a href="/web-llvm/docs/api/structs/llvm/codegen/registercodegenflags/#a75d2af90ba0606f11c58571ce040d267">llvm::codegen::RegisterCodeGenFlags::RegisterCodeGenFlags</a>.</p>

</div>
</div>

### EnableMachineOutliner {#ae5dd57fe00bc1a361772ad1b5c2a1e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; RunOutliner &gt; EnableMachineOutliner("enable-machine-outliner", cl::desc("Enable the machine outliner"), cl::Hidden, cl::ValueOptional, cl::init(RunOutliner::TargetDefault), cl::values(clEnumValN(RunOutliner::AlwaysOutline, "always", "Run on all functions guaranteed to be beneficial"), clEnumValN(RunOutliner::NeverOutline, "never", "Disable all outlining"), clEnumValN(RunOutliner::AlwaysOutline, "", "")))</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### FSProfileFile {#af666c434131d8e60b8978afc46f7af4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; FSProfileFile("fs-profile-file", cl::init(""), cl::value_desc("filename"), cl::desc("Flow Sensitive profile file name."), cl::Hidden)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a> and <a href="#aa3a0aa6f7fa6a74d1af3ca21fbe3e39a">getFSProfileFile</a>.</p>

</div>
</div>

### FSRemappingFile {#a814700c705e4876b0f7fbca69811ba72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; FSRemappingFile("fs-remapping-file", cl::init(""), cl::value_desc("filename"), cl::desc("Flow Sensitive profile remapping file name."), cl::Hidden)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#a377b60f1ad7bd50ebecab462d9258896">getFSRemappingFile</a>.</p>

</div>
</div>

### GCEmptyBlocks {#ab06dbeeeecd4faac66a1476f67e5a256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; GCEmptyBlocks("gc-empty-basic-blocks", cl::init(false), cl::Hidden, cl::desc("Enable garbage-collecting empty basic blocks"))</td>
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

<p>Enable garbage-collecting empty basic blocks.</p>

<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### InitializeDefaultRegisterAllocatorFlag {#a1a22a0a83da7865dbf36273336891542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::once_flag InitializeDefaultRegisterAllocatorFlag</td>
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

<p>A dummy default pass factory indicates whether the register allocator is overridden on the command line.</p>

<p>Definition at line 1343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a521c0fd2e8307b5b136c2e8b984a9316">llvm::TargetPassConfig::createRegAllocPass</a>.</p>

</div>
</div>

### MISchedPostRA {#ae36047825707739faa5a23dc3e7a8953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; MISchedPostRA("misched-postra", cl::Hidden, cl::desc( "Run MachineScheduler post regalloc (independent of preRA sched)"))</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### OptimizeRegAlloc {#aef990f408b84ac05c67735579e5c3ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; cl::boolOrDefault &gt; OptimizeRegAlloc("optimize-regalloc", cl::Hidden, cl::desc("Enable optimized register allocation compilation path."))</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a6e1fdfe760cddafee7d4a7bd4fe9bf1e">llvm::TargetPassConfig::getOptimizeRegAlloc</a>.</p>

</div>
</div>

### PrintAfterISel {#a4d7d3b681d1917147ae0150ec7a8c079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintAfterISel("print-after-isel", cl::init(false), cl::Hidden, cl::desc("Print machine instrs after ISel"))</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a123cf7df9bb0d6c21219b0d9f1f68811">llvm::TargetPassConfig::addPrintPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### PrintISelInput {#a2299fa2c21b5a1fc242277cbc08a739b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintISelInput("print-isel-input", cl::Hidden, cl::desc("Print LLVM IR input to isel pass"))</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#acd370e6335630ad711de582b8bb2fd72">llvm::TargetPassConfig::addISelPrepare</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### RegAlloc {#a21ad36388c3fc5c02ed576b30e636c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; RegisterRegAlloc::FunctionPassCtor, false, RegisterPassParser&lt; RegisterRegAlloc &gt; &gt; RegAlloc("regalloc", cl::Hidden, cl::init(&amp;useDefaultRegisterAllocator), cl::desc("Register allocator to use"))</td>
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



<p>Definition at line 1086 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a662881e8843762cf5faebe3885d8f482">llvm::TargetPassConfig::addRegAssignAndRewriteFast</a>, <a href="#a7cd1b5df9d07c4cea37c4677055341a9">initializeDefaultRegisterAllocatorOnce</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a6f81ebaba440d56ca78c806f562c9a1b">llvm::TargetPassConfig::isCustomizedRegAlloc</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a02a18e7b86433276cfda5efe4c95fdf5">llvm::TargetPassConfig::usingDefaultRegAlloc</a>.</p>

</div>
</div>

### SplitStaticData {#a89a5027ab1515cef6c0779b6db4adef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SplitStaticData("split-static-data", cl::Hidden, cl::init(false), cl::desc("Split static data sections into hot and cold " "sections using profile information"))</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a>.</p>

</div>
</div>

### StartAfterOpt {#a6d4e751a7a3000d9acfd17e8f705a47a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; StartAfterOpt(StringRef(StartAfterOptName), cl::desc("Resume compilation after a specific pass"), cl::value_desc("pass-name"), cl::init(""), cl::Hidden)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aa8b1a68d7df4c01aab346bc78ecaf283">llvm::TargetPassConfig::getLimitedCodeGenPipelineReason</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a2adec695334610982e70d013e958a4fd">llvm::TargetPassConfig::getStartStopInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a26ea3eee7271935ffb8a4afccc131c7f">llvm::TargetPassConfig::hasLimitedCodeGenPipeline</a>.</p>

</div>
</div>

### StartAfterOptName {#a9d2c0d6ec280e108ba4b506decb8e11c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char StartAfterOptName[] = "start-after"</td>
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

<p>Option names for limiting the codegen pipeline.</p>


<p>Those are used in error reporting and we didn't want to duplicate their names all over the place.</p>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aa8b1a68d7df4c01aab346bc78ecaf283">llvm::TargetPassConfig::getLimitedCodeGenPipelineReason</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a2adec695334610982e70d013e958a4fd">llvm::TargetPassConfig::getStartStopInfo</a>.</p>

</div>
</div>

### StartBeforeOpt {#aa6a24b91142e981f7915594033a8aa26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; StartBeforeOpt(StringRef(StartBeforeOptName), cl::desc("Resume compilation before a specific pass"), cl::value_desc("pass-name"), cl::init(""), cl::Hidden)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aa8b1a68d7df4c01aab346bc78ecaf283">llvm::TargetPassConfig::getLimitedCodeGenPipelineReason</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a2adec695334610982e70d013e958a4fd">llvm::TargetPassConfig::getStartStopInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a26ea3eee7271935ffb8a4afccc131c7f">llvm::TargetPassConfig::hasLimitedCodeGenPipeline</a>.</p>

</div>
</div>

### StartBeforeOptName {#a8ea67ebcc3278fadd1a83adbd6f0d5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char StartBeforeOptName[] = "start-before"</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aa8b1a68d7df4c01aab346bc78ecaf283">llvm::TargetPassConfig::getLimitedCodeGenPipelineReason</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a2adec695334610982e70d013e958a4fd">llvm::TargetPassConfig::getStartStopInfo</a>.</p>

</div>
</div>

### StopAfterOpt {#a783106f63c0504ebca077096fae4dec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; StopAfterOpt(StringRef(StopAfterOptName), cl::desc("Stop compilation after a specific pass"), cl::value_desc("pass-name"), cl::init(""), cl::Hidden)</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aa8b1a68d7df4c01aab346bc78ecaf283">llvm::TargetPassConfig::getLimitedCodeGenPipelineReason</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a2adec695334610982e70d013e958a4fd">llvm::TargetPassConfig::getStartStopInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ad0db8596710a5666b67e513da0d9b415">llvm::TargetPassConfig::willCompleteCodeGenPipeline</a>.</p>

</div>
</div>

### StopAfterOptName {#a04e8e4a2abcc0867c475e6cec4d48c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char StopAfterOptName[] = "stop-after"</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aa8b1a68d7df4c01aab346bc78ecaf283">llvm::TargetPassConfig::getLimitedCodeGenPipelineReason</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a2adec695334610982e70d013e958a4fd">llvm::TargetPassConfig::getStartStopInfo</a>.</p>

</div>
</div>

### StopBeforeOpt {#ac6cb7266b461861bc32a0d0798362a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; StopBeforeOpt(StringRef(StopBeforeOptName), cl::desc("Stop compilation before a specific pass"), cl::value_desc("pass-name"), cl::init(""), cl::Hidden)</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aa8b1a68d7df4c01aab346bc78ecaf283">llvm::TargetPassConfig::getLimitedCodeGenPipelineReason</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a2adec695334610982e70d013e958a4fd">llvm::TargetPassConfig::getStartStopInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ad0db8596710a5666b67e513da0d9b415">llvm::TargetPassConfig::willCompleteCodeGenPipeline</a>.</p>

</div>
</div>

### StopBeforeOptName {#a3b2567373b80b37bcdabfa129c003a46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char StopBeforeOptName[] = "stop-before"</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aa8b1a68d7df4c01aab346bc78ecaf283">llvm::TargetPassConfig::getLimitedCodeGenPipelineReason</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a2adec695334610982e70d013e958a4fd">llvm::TargetPassConfig::getStartStopInfo</a>.</p>

</div>
</div>

### VerifyMachineCode {#a5b5ce4f0064aa134408b5e3893b7e9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; cl::boolOrDefault &gt; VerifyMachineCode("verify-machineinstrs", cl::Hidden, cl::desc("Verify generated machine code"))</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ae4433b84f2a85686e6ec21134626dab0">llvm::TargetPassConfig::addVerifyPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DISABLE\_PASS {#ac37c74de68ba47bcdda14bf70e4cadec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DISABLE_PASS(Option, Name)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Option &amp;&amp; <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">P.contains</a>(#Name))                                             \
    return false;
</div>
</dd>
</dl>

<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>.</p>

</div>
</div>

### SET\_BOOLEAN\_OPTION {#a657504030de6b1a3c580878f1c1632c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SET_BOOLEAN_OPTION(Option)&nbsp;&nbsp;&nbsp;Opt.Option = Option;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

### SET\_OPTION {#afc50b9b81c1d03c606a12cfa0ce094dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SET_OPTION(Option)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Option.getNumOccurrences())                                              \
    Opt.Option = Option;
</div>
</dd>
</dl>

<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
