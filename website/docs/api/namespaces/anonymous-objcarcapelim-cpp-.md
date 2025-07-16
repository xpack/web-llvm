---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-objcarcapelim-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{ObjCARCAPElim.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{ObjCARCAPElim.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a083ed14a6ddbd8d83b33f068cd2b4470">MayAutorelease</a> (const CallBase &amp;CB, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interprocedurally determine if calls made by the given call site can possibly produce autoreleases. <a href="#a083ed14a6ddbd8d83b33f068cd2b4470">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b0a789cfd1294b6998186af696abf1">OptimizeBB</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc5959a169d48b207404d44b7867477">runImpl</a> (Module &amp;M)</td>
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

### MayAutorelease() {#a083ed14a6ddbd8d83b33f068cd2b4470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCAPElim.cpp}::MayAutorelease (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interprocedurally determine if calls made by the given call site can possibly produce autoreleases.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcapelim-cpp">ObjCARCAPElim.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a083ed14a6ddbd8d83b33f068cd2b4470">MayAutorelease</a>.</p>


<p>Referenced by <a href="#a083ed14a6ddbd8d83b33f068cd2b4470">MayAutorelease</a> and <a href="#a50b0a789cfd1294b6998186af696abf1">OptimizeBB</a>.</p>

</div>
</div>

### OptimizeBB() {#a50b0a789cfd1294b6998186af696abf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCAPElim.cpp}::OptimizeBB (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcapelim-cpp">ObjCARCAPElim.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2a4ee466dcf60bef3376060be50d45cdda">llvm::objcarc::AutoreleasepoolPop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2a56a1f8ca583bf2a38d53b7e7825bd269">llvm::objcarc::AutoreleasepoolPush</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2a216b693ce70a5639bd2e33cdbb0d82d8">llvm::objcarc::CallOrUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a86cdbdf3773be3c67bc193b473b75708">llvm::objcarc::GetBasicARCInstKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a> and <a href="#a083ed14a6ddbd8d83b33f068cd2b4470">MayAutorelease</a>.</p>


<p>Referenced by <a href="#a9bc5959a169d48b207404d44b7867477">runImpl</a>.</p>

</div>
</div>

### runImpl() {#a9bc5959a169d48b207404d44b7867477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCAPElim.cpp}::runImpl (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcapelim-cpp">ObjCARCAPElim.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a6771e7364c5ab8a6354f744fe5bbc62b">llvm::objcarc::EnableARCOpts</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a0698d5bcabbfbca4f56a9d7a81cecb25">llvm::GlobalVariable::getInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#aec2d700d8b1e57f830a673c39a1f30dc">llvm::GlobalVariable::hasDefinitiveInitializer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a255df46f4454af8706323670d5e7f7b6">llvm::objcarc::ModuleHasARC</a> and <a href="#a50b0a789cfd1294b6998186af696abf1">OptimizeBB</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcapelim-cpp">ObjCARCAPElim.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
