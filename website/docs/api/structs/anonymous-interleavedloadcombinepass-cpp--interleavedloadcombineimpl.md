---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-interleavedloadcombinepass-cpp-/interleavedloadcombineimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `InterleavedLoadCombineImpl` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombineImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4ce5793d7ccee9da0ef5cf72c84223">InterleavedLoadCombineImpl</a> (Function &amp;F, DominatorTree &amp;DT, MemorySSA &amp;MSSA, const TargetTransformInfo &amp;TTI, const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67598b6a57000bd24f98853c3c692ce8">run</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan the function for interleaved load candidates and execute the replacement if applicable. <a href="#a67598b6a57000bd24f98853c3c692ce8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affa230bf43a2c968a2689fd909a39800">findFirstLoad</a> (const std::set&lt; LoadInst * &gt; &amp;LIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the instruction in sets LIs that dominates all others, return nullptr if there is none. <a href="#affa230bf43a2c968a2689fd909a39800">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b3c8ec7b2c10b86e2b62f53a44e41e">combine</a> (std::list&lt; VectorInfo &gt; &amp;InterleavedLoad, OptimizationRemarkEmitter &amp;ORE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace interleaved load candidates. <a href="#a76b3c8ec7b2c10b86e2b62f53a44e41e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6998cf02248e1425224265eb94342f10">findPattern</a> (std::list&lt; VectorInfo &gt; &amp;Candidates, std::list&lt; VectorInfo &gt; &amp;InterleavedLoad, unsigned Factor, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a set of <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> containing candidates for a given interleave factor, find a set that represents a 'factor' interleaved load. <a href="#a6998cf02248e1425224265eb94342f10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2055375ca9cf70db58ae2aa1cce2968">F</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> this pass is working on. <a href="#ab2055375ca9cf70db58ae2aa1cce2968">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e80738cbf7b793b0f8e20aabfc54957">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dominator Tree Analysis. <a href="#a6e80738cbf7b793b0f8e20aabfc54957">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0408d9bb0d1a6c6b4ed4354f20d9d8f1">MSSA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> Alias Analyses. <a href="#a0408d9bb0d1a6c6b4ed4354f20d9d8f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed47fac7c092712f69b1c2e2d8d68e2">TLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Lowering Information. <a href="#a9ed47fac7c092712f69b1c2e2d8d68e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a266d8811bb22ce142f2d6aa84e09f871">TTI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Transform Information. <a href="#a266d8811bb22ce142f2d6aa84e09f871">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InterleavedLoadCombineImpl() {#aff4ce5793d7ccee9da0ef5cf72c84223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombineImpl::InterleavedLoadCombineImpl (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> &amp; MSSA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a67598b6a57000bd24f98853c3c692ce8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterleavedLoadCombineImpl::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan the function for interleaved load candidates and execute the replacement if applicable.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a512a96bc40ecd933dab9e74af6be51b0">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromSVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/interleavedloadcombine/#adef67ae3266f48eacb955c2d515737ef">anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombine::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### combine() {#a76b3c8ec7b2c10b86e2b62f53a44e41e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterleavedLoadCombineImpl::combine (std::list&lt; <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> &gt; &amp; InterleavedLoad, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace interleaved load candidates.</p>


<p>It does additional analyses if this makes sense. Returns true on success and false of nothing has been changed.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

### findFirstLoad() {#affa230bf43a2c968a2689fd909a39800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst * InterleavedLoadCombineImpl::findFirstLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * &gt; &amp; LIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the instruction in sets LIs that dominates all others, return nullptr if there is none.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

### findPattern() {#a6998cf02248e1425224265eb94342f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterleavedLoadCombineImpl::findPattern (std::list&lt; <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> &gt; &amp; Candidates, std::list&lt; <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> &gt; &amp; InterleavedLoad, unsigned Factor, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a set of <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo">VectorInfo</a> containing candidates for a given interleave factor, find a set that represents a 'factor' interleaved load.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DT {#a6e80738cbf7b793b0f8e20aabfc54957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombineImpl::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dominator Tree Analysis.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

### F {#ab2055375ca9cf70db58ae2aa1cce2968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombineImpl::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> this pass is working on.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

### MSSA {#a0408d9bb0d1a6c6b4ed4354f20d9d8f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA&amp; anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombineImpl::MSSA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> Alias Analyses.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

### TLI {#a9ed47fac7c092712f69b1c2e2d8d68e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering&amp; anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombineImpl::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Lowering Information.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

### TTI {#a266d8811bb22ce142f2d6aa84e09f871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo&amp; anonymous{InterleavedLoadCombinePass.cpp}::InterleavedLoadCombineImpl::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Transform Information.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
