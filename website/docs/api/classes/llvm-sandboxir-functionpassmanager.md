---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/functionpassmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FunctionPassManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::FunctionPassManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">llvm/SandboxIR/PassManager.h</a>"
</div>

## Base class

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdd8920d5bf143b7e660934772308c6c">FunctionPassManager</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63cd2ea5ef280233c1c05100774c9e8c">FunctionPassManager</a> (StringRef Name, StringRef Pipeline, CreatePassFunc CreatePass)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5cdbdaeb5d495e6590774bcfe2e59b1">runOnFunction</a> (Function &amp;F, const Analyses &amp;A) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if it modifies <span class="doxyComputerOutput">F</span>. <a href="#ad5cdbdaeb5d495e6590774bcfe2e59b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionPassManager() {#acdd8920d5bf143b7e660934772308c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::FunctionPassManager::FunctionPassManager (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass/#a5af8e0807e55ac77fb4f4b3d3c633e9e">llvm::sandboxir::Pass::Name</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#a1e1411cecb7e848d94591dcc1b4c0c32">llvm::sandboxir::PassManager&lt; FunctionPass, FunctionPass &gt;::PassManager</a>.</p>

</div>
</div>

### FunctionPassManager() {#a63cd2ea5ef280233c1c05100774c9e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::FunctionPassManager::FunctionPassManager (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Pipeline, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#a49776eae204190a6aeb2bae228f7d938">CreatePassFunc</a> CreatePass)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass/#a5af8e0807e55ac77fb4f4b3d3c633e9e">llvm::sandboxir::Pass::Name</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#a1e1411cecb7e848d94591dcc1b4c0c32">llvm::sandboxir::PassManager&lt; FunctionPass, FunctionPass &gt;::PassManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runOnFunction() {#ad5cdbdaeb5d495e6590774bcfe2e59b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::FunctionPassManager::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/analyses">Analyses</a> &amp; A)</td>
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

<p>\Returns true if it modifies <span class="doxyComputerOutput">F</span>.</p>

<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>, definition at line 13 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/passmanager-cpp">PassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#ac6205116f9e954e988534ec98b459ff4">llvm::sandboxir::PassManager&lt; FunctionPass, FunctionPass &gt;::Passes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/passmanager-cpp">PassManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
