---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/functionpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FunctionPass` Class

<p>A pass that runs on a sandbox::Function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::FunctionPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">llvm/SandboxIR/Pass.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass">Pass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base class of a Sandbox IR <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass">Pass</a>. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager">PassManager&lt;ParentPass, ContainedPass&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/bottomupvec">BottomUpVec</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/regionsfrommetadata">RegionsFromMetadata</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0cb4a456ac5281b4f3baf5e55b4044">FunctionPass</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Name</span> can't contain any spaces or start with '-'. <a href="#a0e0cb4a456ac5281b4f3baf5e55b4044">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bee0dc60a62c81496ff0d850848271d">runOnFunction</a> (Function &amp;F, const Analyses &amp;A)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if it modifies <span class="doxyComputerOutput">F</span>. <a href="#a1bee0dc60a62c81496ff0d850848271d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A pass that runs on a sandbox::Function.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionPass() {#a0e0cb4a456ac5281b4f3baf5e55b4044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::FunctionPass::FunctionPass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p><span class="doxyComputerOutput">Name</span> can't contain any spaces or start with '-'.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass/#a5af8e0807e55ac77fb4f4b3d3c633e9e">llvm::sandboxir::Pass::Name</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass/#abb15311ea19cab0aadaa56a7bf91893a">llvm::sandboxir::Pass::Pass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/bottomupvec/#a121d3320d95d3836b765bf8e8cbb4de8">llvm::sandboxir::BottomUpVec::BottomUpVec</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/regionsfrommetadata/#abf6f2dd80ab90276835a0d54c1272f42">llvm::sandboxir::RegionsFromMetadata::RegionsFromMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runOnFunction() {#a1bee0dc60a62c81496ff0d850848271d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::sandboxir::FunctionPass::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/analyses">Analyses</a> &amp; A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns true if it modifies <span class="doxyComputerOutput">F</span>.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
