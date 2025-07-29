---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppclowermassventries-cpp-/ppclowermassventries
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCLowerMASSVEntries` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{PPCLowerMASSVEntries.cpp}::PPCLowerMASSVEntries { ... }
</div>

## Base class

<table class="doxyMembersIndex">

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a634a1e3c9c4aa85b8fd37d5fce6b7c5e">PPCLowerMASSVEntries</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc7b9162f72717ab77864ee9b4b48030">runOnModule</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnModule - Virtual method overriden by subclasses to process the module being operated on. <a href="#afc7b9162f72717ab77864ee9b4b48030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a300c5ec920acdddd21bd80a5fa0dcabd">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a300c5ec920acdddd21bd80a5fa0dcabd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ef3feaa598c937267b5c8343c0c09b2">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a9ef3feaa598c937267b5c8343c0c09b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a653cf30b00953d2d432e7a985eabca11">handlePowSpecialCases</a> (CallInst *CI, Function &amp;Func, Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there are proper fast-math flags, this function creates llvm.pow intrinsics when the exponent is 0.25 or 0.75. <a href="#a653cf30b00953d2d432e7a985eabca11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ce05d9c7b148f66fdb011c9ca3110a5">lowerMASSVCall</a> (CallInst *CI, Function &amp;Func, Module &amp;M, const PPCSubtarget *Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lowers generic MASSV entries to PowerPC subtarget-specific MASSV entries. <a href="#a9ce05d9c7b148f66fdb011c9ca3110a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a062dfdc7d144247c5c6e3d95781400c2">isMASSVFunc</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the specified function name represents an entry in the MASSV library. <a href="#a062dfdc7d144247c5c6e3d95781400c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ccede6d16713e90d7c48d5c62e9e730">getCPUSuffix</a> (const PPCSubtarget *Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a string corresponding to the specified PowerPC subtarget. <a href="#a6ccede6d16713e90d7c48d5c62e9e730">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab68cb2f3820fffd900fe2191802693">createMASSVFuncName</a> (Function &amp;Func, const PPCSubtarget *Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates PowerPC subtarget-specific name corresponding to the specified generic MASSV function, and the PowerPC subtarget. <a href="#a1ab68cb2f3820fffd900fe2191802693">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4470c665f5e3712e9bec2db150e7d587">ID</a> = 0</td>
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


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCLowerMASSVEntries() {#a634a1e3c9c4aa85b8fd37d5fce6b7c5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCLowerMASSVEntries.cpp}::PPCLowerMASSVEntries::PPCLowerMASSVEntries ()</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a>.</p>


<p>References <a href="#a4470c665f5e3712e9bec2db150e7d587">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/modulepass/#a723659a08d210f4f566887bda3f9f976">llvm::ModulePass::ModulePass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp/#a08cae1d93d03339285413846901c7fc2">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a9ef3feaa598c937267b5c8343c0c09b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCLowerMASSVEntries.cpp}::PPCLowerMASSVEntries::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>.</p>

</div>
</div>

### getPassName() {#a300c5ec920acdddd21bd80a5fa0dcabd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{PPCLowerMASSVEntries.cpp}::PPCLowerMASSVEntries::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a>.</p>

</div>
</div>

### runOnModule() {#afc7b9162f72717ab77864ee9b4b48030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLowerMASSVEntries::runOnModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>runOnModule - Virtual method overriden by subclasses to process the module being operated on.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#af94c014e968489e96c7d4353a84ad7f5">llvm::Pass::getAnalysisIfAvailable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### handlePowSpecialCases() {#a653cf30b00953d2d432e7a985eabca11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLowerMASSVEntries::handlePowSpecialCases (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there are proper fast-math flags, this function creates llvm.pow intrinsics when the exponent is 0.25 or 0.75.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a>.</p>

</div>
</div>

### lowerMASSVCall() {#a9ce05d9c7b148f66fdb011c9ca3110a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLowerMASSVEntries::lowerMASSVCall (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> * Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lowers generic MASSV entries to PowerPC subtarget-specific MASSV entries.</p>


<p>e.g.: __sind2_massv --&gt; __sind2_P9 for a Power9 subtarget. Both function prototypes and their callsites are updated during lowering.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### createMASSVFuncName() {#a1ab68cb2f3820fffd900fe2191802693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string PPCLowerMASSVEntries::createMASSVFuncName (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> * Subtarget)</td>
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

<p>Creates PowerPC subtarget-specific name corresponding to the specified generic MASSV function, and the PowerPC subtarget.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a>.</p>

</div>
</div>

### getCPUSuffix() {#a6ccede6d16713e90d7c48d5c62e9e730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef PPCLowerMASSVEntries::getCPUSuffix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> * Subtarget)</td>
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

<p>Returns a string corresponding to the specified PowerPC subtarget.</p>


<p>e.g.: "_P8" for Power8, "_P9" for Power9. The string is used as a suffix while generating subtarget-specific MASSV library functions. Current support includes minimum subtarget Power8 for Linux and Power7 for AIX.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a>.</p>

</div>
</div>

### isMASSVFunc() {#a062dfdc7d144247c5c6e3d95781400c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLowerMASSVEntries::isMASSVFunc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Checks if the specified function name represents an entry in the MASSV library.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a4470c665f5e3712e9bec2db150e7d587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char PPCLowerMASSVEntries::ID = 0</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a>.</p>


<p>Referenced by <a href="#a634a1e3c9c4aa85b8fd37d5fce6b7c5e">PPCLowerMASSVEntries</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppclowermassventries-cpp">PPCLowerMASSVEntries.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
