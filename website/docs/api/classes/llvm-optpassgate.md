---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/optpassgate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OptPassGate` Class

<p>Extensions to this class implement mechanisms to disable passes and individual optimizations at compile time. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::OptPassGate { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/optbisect-h">llvm/IR/OptBisect.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optbisect">OptBisect</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class implements a mechanism to disable passes and individual optimizations at compile time based on a command line option (-opt-bisect-limit) in order to perform a bisecting search for optimization-related problems. <a href="/web-llvm/docs/api/classes/llvm/optbisect/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affc8ba09f6b5795a99112ec0c84be0d8">~OptPassGate</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59de8deea51271200bbfc1e5be45ee3c">shouldRunPass</a> (const StringRef PassName, StringRef IRDescription)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IRDescription is a textual description of the IR unit the pass is running over. <a href="#a59de8deea51271200bbfc1e5be45ee3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0324a149fd3db35e2f789c91a4d30da4">isEnabled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a0324a149fd3db35e2f789c91a4d30da4">isEnabled()</a> should return true before calling <a href="#a59de8deea51271200bbfc1e5be45ee3c">shouldRunPass()</a>. <a href="#a0324a149fd3db35e2f789c91a4d30da4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Extensions to this class implement mechanisms to disable passes and individual optimizations at compile time.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/optbisect-h">OptBisect.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~OptPassGate() {#affc8ba09f6b5795a99112ec0c84be0d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::OptPassGate::~OptPassGate ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/optbisect-h">OptBisect.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isEnabled() {#a0324a149fd3db35e2f789c91a4d30da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::OptPassGate::isEnabled ()</td>
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

<p><a href="#a0324a149fd3db35e2f789c91a4d30da4">isEnabled()</a> should return true before calling <a href="#a59de8deea51271200bbfc1e5be45ee3c">shouldRunPass()</a>.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/optbisect-h">OptBisect.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/optpassgateinstrumentation/#ab2b73a9eaecb02a4ec3beebaa431b972">llvm::OptPassGateInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#ac97db8f0e4f4a0946dddf617f45f6c8b">llvm::LoopPass::skipLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2a3749e0f47aa3b73df3ac0e66a78771">llvm::RegionPass::skipRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#a978ee5e9b5b33e10cea60aea38f80788">llvm::CallGraphSCCPass::skipSCC</a>.</p>

</div>
</div>

### shouldRunPass() {#a59de8deea51271200bbfc1e5be45ee3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::OptPassGate::shouldRunPass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IRDescription)</td>
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

<p>IRDescription is a textual description of the IR unit the pass is running over.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/optbisect-h">OptBisect.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/looppass/#ac97db8f0e4f4a0946dddf617f45f6c8b">llvm::LoopPass::skipLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2a3749e0f47aa3b73df3ac0e66a78771">llvm::RegionPass::skipRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#a978ee5e9b5b33e10cea60aea38f80788">llvm::CallGraphSCCPass::skipSCC</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/optbisect-h">OptBisect.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
