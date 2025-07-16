---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/diagnosticinfooptimizationbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DiagnosticInfoOptimizationBase` Class Reference

<p>Common features for diagnostics dealing with optimization remarks that are used by both IR and MIR passes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DiagnosticInfoOptimizationBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfowithlocationbase">DiagnosticInfoWithLocationBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common features for diagnostics with an associated location. <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfowithlocationbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization">DiagnosticInfoIROptimization</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common features for diagnostics dealing with optimization remarks that are used by IR passes. <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomiroptimization">DiagnosticInfoMIROptimization</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common features for diagnostics dealing with optimization remarks that are used by machine passes. <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomiroptimization/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a4821cc4da0f7c13aee43edf840e07">DiagnosticInfoOptimizationBase</a> (enum DiagnosticKind Kind, enum DiagnosticSeverity Severity, const char *PassName, StringRef RemarkName, const Function &amp;Fn, const DiagnosticLocation &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic. <a href="#ae3a4821cc4da0f7c13aee43edf840e07">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a416feb56f85aad62df6f3e1c5ccca65d">insert</a> (StringRef S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46ffecc69d94cfe2423e2ff2fbc85ba">insert</a> (Argument A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa15cf23b0c5e77fbbbb01201a966983">insert</a> (setIsVerbose V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab060635dd8d046110cd2cfa476211ccc">insert</a> (setExtraArgs EA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ad2c89e20662a91116db4c738b4f1fe">print</a> (DiagnosticPrinter &amp;DP) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae68c6c41365eb4602d037a38616cf33f">isEnabled</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this optimization remark is enabled by one of of the LLVM command line flags (-pass-remarks, -pass-remarks-missed, or -pass-remarks-analysis). <a href="#ae68c6c41365eb4602d037a38616cf33f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51e48dc15ff1e5851f1ac88b2f959ff3">getPassName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb9558eea7842824a60c3fc8b811080">getRemarkName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a579ac4d6814d2caddee0904ca72250c7">getMsg</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affaf002fae858d6fabe51a135b30e8be">getHotness</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd98d79d7a2ca75caeab35a0d2db8d65">setHotness</a> (std::optional&lt; uint64_t &gt; H)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1de63cb3253501d33ed8e167e6c7c46b">isVerbose</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument">Argument</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28075ff7b9bfa348af9bc9d9a1153bd5">getArgs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99af84a347f9cc19e1e0619ac1c032c1">isPassed</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a068a3fa48cd9776787a65d35fc3a1540">isMissed</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59398609f5fc5db6b02841880a9ff00e">isAnalysis</a> () const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b9b11107e5d9c73301e16d839f6c7d7">PassName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Name of the pass that triggers this report. <a href="#a3b9b11107e5d9c73301e16d839f6c7d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f8e0c579b9530254084bbb00a0e727">RemarkName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Textual identifier for the remark (single-word, camel-case). <a href="#a54f8e0c579b9530254084bbb00a0e727">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5bcee0ca78b8b182347c60f4bfacc20">Hotness</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If profile information is available, this is the number of times the corresponding code was executed in a profile instrumentation run. <a href="#aa5bcee0ca78b8b182347c60f4bfacc20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument">Argument</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ae6473bab457dfb88ec9210629760e">Args</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Arguments collected via the streaming interface. <a href="#ab3ae6473bab457dfb88ec9210629760e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd8fe41b03328fe77ae87cbb1a1634b">IsVerbose</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The remark is expected to be noisy. <a href="#a6bd8fe41b03328fe77ae87cbb1a1634b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29c7d52bba1460195faad9f489059426">FirstExtraArgIndex</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If positive, the index of the first argument that only appear in the optimization records and not in the remark printed in the compiler output. <a href="#a29c7d52bba1460195faad9f489059426">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad92ac2b2b2d4a1ba7b51a9070910f1db">classof</a> (const DiagnosticInfo *DI)</td>
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

<p>Common features for diagnostics dealing with optimization remarks that are used by both IR and MIR passes.</p>

<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DiagnosticInfoOptimizationBase() {#ae3a4821cc4da0f7c13aee43edf840e07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DiagnosticInfoOptimizationBase::DiagnosticInfoOptimizationBase (enum <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594">DiagnosticKind</a> Kind, enum <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5c">DiagnosticSeverity</a> Severity, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc)</td>
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

<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic.</p>


<p><span class="doxyComputerOutput">RemarkName</span> is a textual identifier for the remark (single-word, camel-case). <span class="doxyComputerOutput">Fn</span> is the function where the diagnostic is being emitted. <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> is the location information to use in the diagnostic. If line table information is available, the diagnostic will include the source code location.</p>


<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfowithlocationbase/#aca991454271008ccddc187789d107d34">llvm::DiagnosticInfoWithLocationBase::DiagnosticInfoWithLocationBase</a>, <a href="#a3b9b11107e5d9c73301e16d839f6c7d7">PassName</a> and <a href="#a54f8e0c579b9530254084bbb00a0e727">RemarkName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a301d0e866440a41b832972c897f2dc5c">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#aa192c95c53dffca890dcffcae58795f0">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomiroptimization/#a4d8ba0921d348dc62437d2fd3ce00061">llvm::DiagnosticInfoMIROptimization::DiagnosticInfoMIROptimization</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getArgs() {#a28075ff7b9bfa348af9bc9d9a1153bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Argument &gt; llvm::DiagnosticInfoOptimizationBase::getArgs ()</td>
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



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Reference <a href="#ab3ae6473bab457dfb88ec9210629760e">Args</a>.</p>

</div>
</div>

### getHotness() {#affaf002fae858d6fabe51a135b30e8be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::DiagnosticInfoOptimizationBase::getHotness ()</td>
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



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Reference <a href="#aa5bcee0ca78b8b182347c60f4bfacc20">Hotness</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter/#aae6a98aea85aa3af87357cc5448db499">llvm::OptimizationRemarkEmitter::emit</a>.</p>

</div>
</div>

### getMsg() {#a579ac4d6814d2caddee0904ca72250c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string DiagnosticInfoOptimizationBase::getMsg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#ab3ae6473bab457dfb88ec9210629760e">Args</a>, <a href="#a29c7d52bba1460195faad9f489059426">FirstExtraArgIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp/#ae02f5a84142c2d7909ce301489a6adef">EmitAndPrintRemark</a> and <a href="#a6ad2c89e20662a91116db4c738b4f1fe">print</a>.</p>

</div>
</div>

### getPassName() {#a51e48dc15ff1e5851f1ac88b2f959ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DiagnosticInfoOptimizationBase::getPassName ()</td>
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



<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Reference <a href="#a3b9b11107e5d9c73301e16d839f6c7d7">PassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/llvmremarkstreamer/#afb8676fe8d06d8d0bd1c4d3db2107769">llvm::LLVMRemarkStreamer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremark/#a39d9cdb595768f3e86c3f86f4ba33c00">llvm::MachineOptimizationRemark::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#a21c55fb64c1decb01f6dfe60ba7b6c1d">llvm::MachineOptimizationRemarkAnalysis::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkmissed/#a22479d91f2c90bb3032810dfa2864527">llvm::MachineOptimizationRemarkMissed::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a551a7d26da872a1e686a9d0d4a72d49b">llvm::OptimizationRemark::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a0f1ed99116e727b8a7af8cf48889e7b6">llvm::OptimizationRemarkAnalysis::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#aafff42ca513f5f2e742201442cb299ef">llvm::OptimizationRemarkMissed::isEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#aaa6a70f38583335812228b905db94bb7">llvm::OptimizationRemarkAnalysis::shouldAlwaysPrint</a>.</p>

</div>
</div>

### getRemarkName() {#abbb9558eea7842824a60c3fc8b811080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DiagnosticInfoOptimizationBase::getRemarkName ()</td>
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



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Reference <a href="#a54f8e0c579b9530254084bbb00a0e727">RemarkName</a>.</p>

</div>
</div>

### insert() {#a416feb56f85aad62df6f3e1c5ccca65d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DiagnosticInfoOptimizationBase::insert (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>Reference <a href="#ab3ae6473bab457dfb88ec9210629760e">Args</a>.</p>

</div>
</div>

### insert() {#af46ffecc69d94cfe2423e2ff2fbc85ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DiagnosticInfoOptimizationBase::insert (<a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument">Argument</a> A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#ab3ae6473bab457dfb88ec9210629760e">Args</a>.</p>

</div>
</div>

### insert() {#aaa15cf23b0c5e77fbbbb01201a966983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DiagnosticInfoOptimizationBase::insert (<a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/setisverbose">setIsVerbose</a> V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>Reference <a href="#a6bd8fe41b03328fe77ae87cbb1a1634b">IsVerbose</a>.</p>

</div>
</div>

### insert() {#ab060635dd8d046110cd2cfa476211ccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DiagnosticInfoOptimizationBase::insert (<a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/setextraargs">setExtraArgs</a> EA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#ab3ae6473bab457dfb88ec9210629760e">Args</a> and <a href="#a29c7d52bba1460195faad9f489059426">FirstExtraArgIndex</a>.</p>

</div>
</div>

### isAnalysis() {#a59398609f5fc5db6b02841880a9ff00e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticInfoOptimizationBase::isAnalysis ()</td>
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



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a7dd37b39b11727c3cb52146531813b30">llvm::DK_MachineOptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a27ed101669b84c58dbf9363fe96bdf64">llvm::DK_OptimizationRemarkAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a6ee6158fd6a3b235dbb41acfe4f9930f">llvm::DiagnosticInfo::getKind</a>.</p>

</div>
</div>

### isEnabled() {#ae68c6c41365eb4602d037a38616cf33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::DiagnosticInfoOptimizationBase::isEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this optimization remark is enabled by one of of the LLVM command line flags (-pass-remarks, -pass-remarks-missed, or -pass-remarks-analysis).</p>


<p>Note that this only handles the LLVM flags. We cannot access Clang flags from here (they are handled in BackendConsumer::OptimizationRemarkHandler).</p>


<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>

</div>
</div>

### isMissed() {#a068a3fa48cd9776787a65d35fc3a1540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticInfoOptimizationBase::isMissed ()</td>
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



<p>Definition at line 574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594aa12ba73e439ce4c158fccc1abf0746d1">llvm::DK_MachineOptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a60172d67189a80dd366981444c7e6fe9">llvm::DK_OptimizationRemarkMissed</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a6ee6158fd6a3b235dbb41acfe4f9930f">llvm::DiagnosticInfo::getKind</a>.</p>

</div>
</div>

### isPassed() {#a99af84a347f9cc19e1e0619ac1c032c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticInfoOptimizationBase::isPassed ()</td>
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



<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a4b4e6d81022a14f72a9d207cde6e2cb1">llvm::DK_MachineOptimizationRemark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a959ff2a8ed63f995237f5a1c77db0df6">llvm::DK_OptimizationRemark</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a6ee6158fd6a3b235dbb41acfe4f9930f">llvm::DiagnosticInfo::getKind</a>.</p>

</div>
</div>

### isVerbose() {#a1de63cb3253501d33ed8e167e6c7c46b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticInfoOptimizationBase::isVerbose ()</td>
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



<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Reference <a href="#a6bd8fe41b03328fe77ae87cbb1a1634b">IsVerbose</a>.</p>

</div>
</div>

### print() {#a6ad2c89e20662a91116db4c738b4f1fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DiagnosticInfoOptimizationBase::print (<a href="/web-llvm/docs/api/classes/llvm/diagnosticprinter">DiagnosticPrinter</a> &amp; DP)</td>
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




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#afe1ba88d90b63845116236a764a670a3">DiagnosticInfo::print</a>.</p></dd>
</dl>


<p>Declaration at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfowithlocationbase/#a1f8e30e4b79049f59395eb471b4ddcf4">llvm::DiagnosticInfoWithLocationBase::getLocationStr</a>, <a href="#a579ac4d6814d2caddee0904ca72250c7">getMsg</a> and <a href="#aa5bcee0ca78b8b182347c60f4bfacc20">Hotness</a>.</p>

</div>
</div>

### setHotness() {#acd98d79d7a2ca75caeab35a0d2db8d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DiagnosticInfoOptimizationBase::setHotness (std::optional&lt; uint64_t &gt; H)</td>
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



<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a> and <a href="#aa5bcee0ca78b8b182347c60f4bfacc20">Hotness</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Args {#ab3ae6473bab457dfb88ec9210629760e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Argument, 4&gt; llvm::DiagnosticInfoOptimizationBase::Args</td>
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

<p>Arguments collected via the streaming interface.</p>

<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a301d0e866440a41b832972c897f2dc5c">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="#a28075ff7b9bfa348af9bc9d9a1153bd5">getArgs</a>, <a href="#a579ac4d6814d2caddee0904ca72250c7">getMsg</a>, <a href="#af46ffecc69d94cfe2423e2ff2fbc85ba">insert</a>, <a href="#ab060635dd8d046110cd2cfa476211ccc">insert</a> and <a href="#a416feb56f85aad62df6f3e1c5ccca65d">insert</a>.</p>

</div>
</div>

### FirstExtraArgIndex {#a29c7d52bba1460195faad9f489059426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::DiagnosticInfoOptimizationBase::FirstExtraArgIndex = -1</td>
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

<p>If positive, the index of the first argument that only appear in the optimization records and not in the remark printed in the compiler output.</p>

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="#a579ac4d6814d2caddee0904ca72250c7">getMsg</a> and <a href="#ab060635dd8d046110cd2cfa476211ccc">insert</a>.</p>

</div>
</div>

### Hotness {#aa5bcee0ca78b8b182347c60f4bfacc20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::DiagnosticInfoOptimizationBase::Hotness</td>
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

<p>If profile information is available, this is the number of times the corresponding code was executed in a profile instrumentation run.</p>

<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="#affaf002fae858d6fabe51a135b30e8be">getHotness</a>, <a href="#a6ad2c89e20662a91116db4c738b4f1fe">print</a> and <a href="#acd98d79d7a2ca75caeab35a0d2db8d65">setHotness</a>.</p>

</div>
</div>

### IsVerbose {#a6bd8fe41b03328fe77ae87cbb1a1634b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticInfoOptimizationBase::IsVerbose = false</td>
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

<p>The remark is expected to be noisy.</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="#aaa15cf23b0c5e77fbbbb01201a966983">insert</a> and <a href="#a1de63cb3253501d33ed8e167e6c7c46b">isVerbose</a>.</p>

</div>
</div>

### PassName {#a3b9b11107e5d9c73301e16d839f6c7d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::DiagnosticInfoOptimizationBase::PassName</td>
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

<p>Name of the pass that triggers this report.</p>


<p>If this matches the regular expression given in -Rpass=regexp, then the remark will be emitted.</p>


<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a301d0e866440a41b832972c897f2dc5c">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#aa192c95c53dffca890dcffcae58795f0">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomiroptimization/#a4d8ba0921d348dc62437d2fd3ce00061">llvm::DiagnosticInfoMIROptimization::DiagnosticInfoMIROptimization</a>, <a href="#ae3a4821cc4da0f7c13aee43edf840e07">DiagnosticInfoOptimizationBase</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationfailure/#a11b5ef0c89ca056e53c24affefe7d3cc">llvm::DiagnosticInfoOptimizationFailure::DiagnosticInfoOptimizationFailure</a>, <a href="#a51e48dc15ff1e5851f1ac88b2f959ff3">getPassName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremark/#ac23eab1baee9b460a0288c92e4526af3">llvm::MachineOptimizationRemark::MachineOptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#ae27db372034ab8b6712c9bbb80d299c5">llvm::MachineOptimizationRemarkAnalysis::MachineOptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#a23badf68951303c8ef0664e24f181100">llvm::MachineOptimizationRemarkAnalysis::MachineOptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkmissed/#a9c71a8a0dda8332ca7321c7ab5420e9a">llvm::MachineOptimizationRemarkMissed::MachineOptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a940829469e382e9dea15a5c8645a8387">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a3891f0f63dbc838b810554621a2b621d">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a2ad3eae0e100b9e6eca74ee28144ba1d">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a48bdcbaf3e1f8e4e09c3507ce7d0afd6">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#ab4fa4fd4a389f0d81f5f413d21b2c4c4">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a1a799ad8c42497bd62234ffd72ca97f3">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a7d0a9378ede1f0821eb273c8e797df06">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a917b13e15387aa72cbd54f48929bcedb">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#ad3c742fcad66bf2ca0afe6d1b58b6c8b">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysisaliasing/#a316fb21374c6a171a407d9d5d64e37be">llvm::OptimizationRemarkAnalysisAliasing::OptimizationRemarkAnalysisAliasing</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysisfpcommute/#a8314f3ba49d1ebaea8d778518d4320c5">llvm::OptimizationRemarkAnalysisFPCommute::OptimizationRemarkAnalysisFPCommute</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a95945fd7efc21c965b5bce7cb8a5685c">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a06e5af98c78a206608155e558697d011">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a> and <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a23879092a3f056766816230baa431981">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a>.</p>

</div>
</div>

### RemarkName {#a54f8e0c579b9530254084bbb00a0e727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DiagnosticInfoOptimizationBase::RemarkName</td>
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

<p>Textual identifier for the remark (single-word, camel-case).</p>


<p>Can be used by external tools reading the output file for optimization remarks to identify the remark.</p>


<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a301d0e866440a41b832972c897f2dc5c">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomiroptimization/#a4d8ba0921d348dc62437d2fd3ce00061">llvm::DiagnosticInfoMIROptimization::DiagnosticInfoMIROptimization</a>, <a href="#ae3a4821cc4da0f7c13aee43edf840e07">DiagnosticInfoOptimizationBase</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationfailure/#a11b5ef0c89ca056e53c24affefe7d3cc">llvm::DiagnosticInfoOptimizationFailure::DiagnosticInfoOptimizationFailure</a>, <a href="#abbb9558eea7842824a60c3fc8b811080">getRemarkName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremark/#ac23eab1baee9b460a0288c92e4526af3">llvm::MachineOptimizationRemark::MachineOptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#ae27db372034ab8b6712c9bbb80d299c5">llvm::MachineOptimizationRemarkAnalysis::MachineOptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#a23badf68951303c8ef0664e24f181100">llvm::MachineOptimizationRemarkAnalysis::MachineOptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkmissed/#a9c71a8a0dda8332ca7321c7ab5420e9a">llvm::MachineOptimizationRemarkMissed::MachineOptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a940829469e382e9dea15a5c8645a8387">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a3891f0f63dbc838b810554621a2b621d">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a2ad3eae0e100b9e6eca74ee28144ba1d">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#ab4fa4fd4a389f0d81f5f413d21b2c4c4">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a1a799ad8c42497bd62234ffd72ca97f3">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a7d0a9378ede1f0821eb273c8e797df06">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#ad3c742fcad66bf2ca0afe6d1b58b6c8b">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysisaliasing/#a316fb21374c6a171a407d9d5d64e37be">llvm::OptimizationRemarkAnalysisAliasing::OptimizationRemarkAnalysisAliasing</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysisfpcommute/#a8314f3ba49d1ebaea8d778518d4320c5">llvm::OptimizationRemarkAnalysisFPCommute::OptimizationRemarkAnalysisFPCommute</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a95945fd7efc21c965b5bce7cb8a5685c">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a06e5af98c78a206608155e558697d011">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a> and <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a23879092a3f056766816230baa431981">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ad92ac2b2b2d4a1ba7b51a9070910f1db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticInfoOptimizationBase::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> * DI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a9a0080fe6649135b91c5d3590be8f336">llvm::DK_FirstMachineRemark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594ad21f1ad0ee8344122ab612c3a84c4ab8">llvm::DK_FirstRemark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a287b1ee4491e6ca4641731593b76e295">llvm::DK_LastMachineRemark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a593e413dd08602726f04e60e38539035">llvm::DK_LastRemark</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a6ee6158fd6a3b235dbb41acfe4f9930f">llvm::DiagnosticInfo::getKind</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
