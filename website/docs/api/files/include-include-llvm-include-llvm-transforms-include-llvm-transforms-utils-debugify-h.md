---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Debugify.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriterpass-h">llvm/Bitcode/BitcodeWriterPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irprintingpasses-h">llvm/IR/IRPrintingPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">llvm/IR/LegacyPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">llvm/IR/PassInstrumentation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/debuginfoperpass">DebugInfoPerPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to track the Debug Info Metadata information. <a href="/web-llvm/docs/api/structs/debuginfoperpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/newpmdebugifypass">NewPMDebugifyPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/debugifystatistics">DebugifyStatistics</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track how much <span class="doxyComputerOutput">debugify</span> information (in the <span class="doxyComputerOutput">synthetic</span> mode only) has been lost. <a href="/web-llvm/docs/api/structs/debugifystatistics/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/newpmcheckdebugifypass">NewPMCheckDebugifyPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugifyeachinstrumentation">DebugifyEachInstrumentation</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugifycustompassmanager">DebugifyCustomPassManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/debugifycustompassmanager">DebugifyCustomPassManager</a> wraps each pass with the debugify passes if needed. <a href="/web-llvm/docs/api/classes/llvm/debugifycustompassmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b96511d25a6961a44edfbfbf7868ba4">DebugFnMap</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">llvm::DISubprogram</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73236f7f4b807ff6fbbb80d8783beb91">DebugInstMap</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a> *, bool &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f4c7f22c84b7c35e08b9a633ce258d">DebugVarMap</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">llvm::DILocalVariable</a> *, unsigned &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a837564d2ec7dc9b49a534242135e1997">WeakInstValueMap</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/weakvh">llvm::WeakVH</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71d63972eed599c71843cc4fe51df0e4">DebugifyStatsMap</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a>, <a href="/web-llvm/docs/api/structs/debugifystatistics">DebugifyStatistics</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map pass names to a per-pass <a href="/web-llvm/docs/api/structs/debugifystatistics">DebugifyStatistics</a> instance. <a href="#a71d63972eed599c71843cc4fe51df0e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DebugifyMode { <a href="#a050aa76ace891cf5971722766fe14b1b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to check whether we track synthetic or original debug info. <a href="#a050aa76ace891cf5971722766fe14b1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulepass">llvm::ModulePass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852b17c1bcf77c05da7b100159512462">createDebugifyModulePass</a> (enum DebugifyMode Mode=DebugifyMode::SyntheticDebugInfo, llvm::StringRef NameOfWrappedPass="", DebugInfoPerPass *DebugInfoBeforePass=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">llvm::FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbed89a81d48a6b50e870dd57c48a53b">createDebugifyFunctionPass</a> (enum DebugifyMode Mode=DebugifyMode::SyntheticDebugInfo, llvm::StringRef NameOfWrappedPass="", DebugInfoPerPass *DebugInfoBeforePass=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulepass">llvm::ModulePass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d798f3ea7f1752372e198b55679d68b">createCheckDebugifyModulePass</a> (bool Strip=false, llvm::StringRef NameOfWrappedPass="", DebugifyStatsMap *StatsMap=nullptr, enum DebugifyMode Mode=DebugifyMode::SyntheticDebugInfo, DebugInfoPerPass *DebugInfoBeforePass=nullptr, llvm::StringRef OrigDIVerifyBugsReportFilePath="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">llvm::FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80bee275658d4cea6785d8b997308ef">createCheckDebugifyFunctionPass</a> (bool Strip=false, llvm::StringRef NameOfWrappedPass="", DebugifyStatsMap *StatsMap=nullptr, enum DebugifyMode Mode=DebugifyMode::SyntheticDebugInfo, DebugInfoPerPass *DebugInfoBeforePass=nullptr, llvm::StringRef OrigDIVerifyBugsReportFilePath="")</td>
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

## Typedefs

### DebugFnMap {#a4b96511d25a6961a44edfbfbf7868ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DebugFnMap = 
    llvm::MapVector&lt;const llvm::Function *, const llvm::DISubprogram *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>

</div>
</div>

### DebugifyStatsMap {#a71d63972eed599c71843cc4fe51df0e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DebugifyStatsMap =  llvm::MapVector&lt;llvm::StringRef, DebugifyStatistics&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map pass names to a per-pass <a href="/web-llvm/docs/api/structs/debugifystatistics">DebugifyStatistics</a> instance.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>

</div>
</div>

### DebugInstMap {#a73236f7f4b807ff6fbbb80d8783beb91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DebugInstMap =  llvm::MapVector&lt;const llvm::Instruction *, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>

</div>
</div>

### DebugVarMap {#a88f4c7f22c84b7c35e08b9a633ce258d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DebugVarMap =  llvm::MapVector&lt;const llvm::DILocalVariable *, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>

</div>
</div>

### WeakInstValueMap {#a837564d2ec7dc9b49a534242135e1997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using WeakInstValueMap = 
    llvm::MapVector&lt;const llvm::Instruction *, llvm::WeakVH&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### DebugifyMode {#a050aa76ace891cf5971722766fe14b1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class DebugifyMode </td>
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

<p>Used to check whether we track synthetic or original debug info.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoDebugify<a id="a050aa76ace891cf5971722766fe14b1ba92384d0ff56c0b84a26c9eff2cb0c16e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SyntheticDebugInfo<a id="a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OriginalDebugInfo<a id="a050aa76ace891cf5971722766fe14b1ba991e1027ad91114d5c5c28b14ca36637"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### createCheckDebugifyFunctionPass() {#ac80bee275658d4cea6785d8b997308ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FunctionPass * createCheckDebugifyFunctionPass (bool Strip=false, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> NameOfWrappedPass="", <a href="#a71d63972eed599c71843cc4fe51df0e4">DebugifyStatsMap</a> * StatsMap=nullptr, enum <a href="#a050aa76ace891cf5971722766fe14b1b">DebugifyMode</a> Mode=<a href="#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">DebugifyMode::SyntheticDebugInfo</a>, <a href="/web-llvm/docs/api/structs/debuginfoperpass">DebugInfoPerPass</a> * DebugInfoBeforePass=nullptr, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> OrigDIVerifyBugsReportFilePath="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>, definition at line 1026 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifyfunctionpass/#a12c6f1b4a473dba4a357c2ecff32307d">anonymous{Debugify.cpp}::CheckDebugifyFunctionPass::CheckDebugifyFunctionPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="#a050aa76ace891cf5971722766fe14b1ba991e1027ad91114d5c5c28b14ca36637">OriginalDebugInfo</a> and <a href="#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">SyntheticDebugInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debugifycustompassmanager/#a3fcb5818d26eaf75c2b5a96903fd7cf4">llvm::DebugifyCustomPassManager::add</a>.</p>

</div>
</div>

### createCheckDebugifyModulePass() {#a8d798f3ea7f1752372e198b55679d68b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ModulePass * createCheckDebugifyModulePass (bool Strip=false, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> NameOfWrappedPass="", <a href="#a71d63972eed599c71843cc4fe51df0e4">DebugifyStatsMap</a> * StatsMap=nullptr, enum <a href="#a050aa76ace891cf5971722766fe14b1b">DebugifyMode</a> Mode=<a href="#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">DebugifyMode::SyntheticDebugInfo</a>, <a href="/web-llvm/docs/api/structs/debuginfoperpass">DebugInfoPerPass</a> * DebugInfoBeforePass=nullptr, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> OrigDIVerifyBugsReportFilePath="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>, definition at line 1014 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifymodulepass/#abb2ac946e56f8a7d15204bb6abb6697a">anonymous{Debugify.cpp}::CheckDebugifyModulePass::CheckDebugifyModulePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="#a050aa76ace891cf5971722766fe14b1ba991e1027ad91114d5c5c28b14ca36637">OriginalDebugInfo</a> and <a href="#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">SyntheticDebugInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debugifycustompassmanager/#a3fcb5818d26eaf75c2b5a96903fd7cf4">llvm::DebugifyCustomPassManager::add</a>.</p>

</div>
</div>

### createDebugifyFunctionPass() {#adbed89a81d48a6b50e870dd57c48a53b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FunctionPass * createDebugifyFunctionPass (enum <a href="#a050aa76ace891cf5971722766fe14b1b">DebugifyMode</a> Mode=<a href="#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">DebugifyMode::SyntheticDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> NameOfWrappedPass="", <a href="/web-llvm/docs/api/structs/debuginfoperpass">DebugInfoPerPass</a> * DebugInfoBeforePass=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>, definition at line 991 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifyfunctionpass/#a0558468ab0facd9987e1b51dd9f6920b">anonymous{Debugify.cpp}::DebugifyFunctionPass::DebugifyFunctionPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="#a050aa76ace891cf5971722766fe14b1ba991e1027ad91114d5c5c28b14ca36637">OriginalDebugInfo</a> and <a href="#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">SyntheticDebugInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debugifycustompassmanager/#a3fcb5818d26eaf75c2b5a96903fd7cf4">llvm::DebugifyCustomPassManager::add</a>.</p>

</div>
</div>

### createDebugifyModulePass() {#a852b17c1bcf77c05da7b100159512462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ModulePass * createDebugifyModulePass (enum <a href="#a050aa76ace891cf5971722766fe14b1b">DebugifyMode</a> Mode=<a href="#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">DebugifyMode::SyntheticDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> NameOfWrappedPass="", <a href="/web-llvm/docs/api/structs/debuginfoperpass">DebugInfoPerPass</a> * DebugInfoBeforePass=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>, definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifymodulepass/#a276d108dd34a0b135ec4d6e9de798f31">anonymous{Debugify.cpp}::DebugifyModulePass::DebugifyModulePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="#a050aa76ace891cf5971722766fe14b1ba991e1027ad91114d5c5c28b14ca36637">OriginalDebugInfo</a> and <a href="#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">SyntheticDebugInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debugifycustompassmanager/#a3fcb5818d26eaf75c2b5a96903fd7cf4">llvm::DebugifyCustomPassManager::add</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
