---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/pass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Pass` Class

<p>The base class of a Sandbox IR <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass">Pass</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::Pass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">llvm/SandboxIR/Pass.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/functionpass">FunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pass that runs on a sandbox::Function. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/regionpass">RegionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pass that runs on a sandbox::Region. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/regionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0348c697d8f9f73e6c79fd14076fa30">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb15311ea19cab0aadaa56a7bf91893a">Pass</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Name</span> can't contain any spaces or start with '-'. <a href="#abb15311ea19cab0aadaa56a7bf91893a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef81971c3480cc231398045f181148a">~Pass</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd425fe36e3defee0e95b3b52cac0ae6">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the name of the pass. <a href="#afd425fe36e3defee0e95b3b52cac0ae6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4725099d02b2c60f33fca89e8672194">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3bff551737ed859e8a281d830f1c05d">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e381c4633a97684b40d4f97c1709d2">printPipeline</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to <a href="#ae4725099d02b2c60f33fca89e8672194">print()</a> but adds a newline. Used for testing. <a href="#a44e381c4633a97684b40d4f97c1709d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5af8e0807e55ac77fb4f4b3d3c633e9e">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The pass name. <a href="#a5af8e0807e55ac77fb4f4b3d3c633e9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The base class of a Sandbox IR <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass">Pass</a>.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#aa0348c697d8f9f73e6c79fd14076fa30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass">Pass</a> &amp; Pass</td>
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


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>


<p>Reference <a href="#abb15311ea19cab0aadaa56a7bf91893a">Pass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Pass() {#abb15311ea19cab0aadaa56a7bf91893a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::Pass::Pass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5af8e0807e55ac77fb4f4b3d3c633e9e">Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functionpass/#a0e0cb4a456ac5281b4f3baf5e55b4044">llvm::sandboxir::FunctionPass::FunctionPass</a>, <a href="#aa0348c697d8f9f73e6c79fd14076fa30">operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/regionpass/#a42cfcfc19f6163c097f68b7a6b29ac8d">llvm::sandboxir::RegionPass::RegionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Pass() {#a3ef81971c3480cc231398045f181148a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::sandboxir::Pass::~Pass ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#ae3bff551737ed859e8a281d830f1c05d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual LLVM_DUMP_METHOD void llvm::sandboxir::Pass::dump ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### getName() {#afd425fe36e3defee0e95b3b52cac0ae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sandboxir::Pass::getName ()</td>
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

<p>\Returns the name of the pass.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>


<p>Reference <a href="#a5af8e0807e55ac77fb4f4b3d3c633e9e">Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#a3f75ee2e53d1aab594375a3345fbddea">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::print</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/bottomupvec/#a47aa4241833389268fb4194c2ed936f5">llvm::sandboxir::BottomUpVec::printPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/regionsfrommetadata/#abe16d0dbd07a949cb155e8338b774369">llvm::sandboxir::RegionsFromMetadata::printPipeline</a>.</p>

</div>
</div>

### print() {#ae4725099d02b2c60f33fca89e8672194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sandboxir::Pass::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>


<p>Reference <a href="#a5af8e0807e55ac77fb4f4b3d3c633e9e">Name</a>.</p>

</div>
</div>

### printPipeline() {#a44e381c4633a97684b40d4f97c1709d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sandboxir::Pass::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Similar to <a href="#ae4725099d02b2c60f33fca89e8672194">print()</a> but adds a newline. Used for testing.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>


<p>Reference <a href="#a5af8e0807e55ac77fb4f4b3d3c633e9e">Name</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Name {#a5af8e0807e55ac77fb4f4b3d3c633e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::sandboxir::Pass::Name</td>
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

<p>The pass name.</p>


<p>This is also used as a command-line flag and should not contain whitespaces.</p>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/pass-h">Pass.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functionpass/#a0e0cb4a456ac5281b4f3baf5e55b4044">llvm::sandboxir::FunctionPass::FunctionPass</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functionpassmanager/#acdd8920d5bf143b7e660934772308c6c">llvm::sandboxir::FunctionPassManager::FunctionPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functionpassmanager/#a63cd2ea5ef280233c1c05100774c9e8c">llvm::sandboxir::FunctionPassManager::FunctionPassManager</a>, <a href="#afd425fe36e3defee0e95b3b52cac0ae6">getName</a>, <a href="#abb15311ea19cab0aadaa56a7bf91893a">Pass</a>, <a href="#ae4725099d02b2c60f33fca89e8672194">print</a>, <a href="#a44e381c4633a97684b40d4f97c1709d2">printPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/regionpass/#a42cfcfc19f6163c097f68b7a6b29ac8d">llvm::sandboxir::RegionPass::RegionPass</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/regionpassmanager/#a29e4969025f1d8292feaa97fb6b5f30d">llvm::sandboxir::RegionPassManager::RegionPassManager</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/regionpassmanager/#a525a0eff9fb4cd189f485b3e9a9b81d5">llvm::sandboxir::RegionPassManager::RegionPassManager</a>.</p>

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
