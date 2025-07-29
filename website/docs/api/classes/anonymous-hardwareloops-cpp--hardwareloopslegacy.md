---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hardwareloops-cpp-/hardwareloopslegacy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HardwareLoopsLegacy` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{HardwareLoops.cpp}::HardwareLoopsLegacy { ... }
</div>

## Base class

<table class="doxyMembersIndex">

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615f2d90d7ae440a010bd7dc6b51ba08">HardwareLoopsLegacy</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a090edab056118e7dae834ce8e11e8157">runOnFunction</a> (Function &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass. <a href="#a090edab056118e7dae834ce8e11e8157">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac18db99454865f90f10be7c256f3471f">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#ac18db99454865f90f10be7c256f3471f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a6f632c7ea9502ff917165d2d8b7ed">ID</a> = 0</td>
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


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp">HardwareLoops.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HardwareLoopsLegacy() {#a615f2d90d7ae440a010bd7dc6b51ba08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HardwareLoops.cpp}::HardwareLoopsLegacy::HardwareLoopsLegacy ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp">HardwareLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#ad0a6f632c7ea9502ff917165d2d8b7ed">ID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a682a047d4da7090602b597165716690f">llvm::initializeHardwareLoopsLegacyPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#ac18db99454865f90f10be7c256f3471f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HardwareLoops.cpp}::HardwareLoopsLegacy::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp">HardwareLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>.</p>

</div>
</div>

### runOnFunction() {#a090edab056118e7dae834ce8e11e8157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HardwareLoopsLegacy::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp">HardwareLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp/#a0c16f34d2c71daf6dc2c13a56a545345">CounterBitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp/#a5ab0c5e0f855ddf939af871b1b72dd7f">ForceGuardLoopEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp/#afd552f1580b5528f0c392c76bb779189">ForceHardwareLoopPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp/#aa72c48b3f8ac628fede23744341d46b1">ForceHardwareLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp/#a04b3b2d853d3affdf4a617374e1fc58b">ForceNestedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#af94c014e968489e96c7d4353a84ad7f5">llvm::Pass::getAnalysisIfAvailable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e3d3c6d4e33a4f5ca579ee7939f0349">llvm::LCSSAID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp/#aa402cb41caef5a8ea009ac87ca1f2cff">LoopDecrement</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a0b4a511579939b07831db90c3fc98996">llvm::Pass::mustPreserveAnalysisID</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopoptions/#a6ed6844557ade9f9a3e5fae998969df2">llvm::HardwareLoopOptions::setCounterBitwidth</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopoptions/#a3eb1385fe18fe7d6a2134bc0ec5856f6">llvm::HardwareLoopOptions::setDecrement</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopoptions/#a6373d300c63c13d0ca46f4e96d744021">llvm::HardwareLoopOptions::setForce</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopoptions/#a477add77b55279ff9c0599270d91bef8">llvm::HardwareLoopOptions::setForceGuard</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopoptions/#a294de0f65296d3b639a2b6423f2773c6">llvm::HardwareLoopOptions::setForceNested</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopoptions/#aa943db259fd227382a5379963c94d0b5">llvm::HardwareLoopOptions::setForcePhi</a> and <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ad0a6f632c7ea9502ff917165d2d8b7ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char HardwareLoopsLegacy::ID = 0</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp">HardwareLoops.cpp</a>.</p>


<p>Referenced by <a href="#a615f2d90d7ae440a010bd7dc6b51ba08">HardwareLoopsLegacy</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp">HardwareLoops.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
