---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-globalmerge-cpp-/globalmergeimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GlobalMergeImpl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{GlobalMerge.cpp}::GlobalMergeImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41919fdcc1f1177cab71dbf318873f4d">GlobalMergeImpl</a> (const TargetMachine *TM, GlobalMergeOptions Opt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fbe2dcb11cb3bb78be4d97f388b0c5d">run</a> (Module &amp;M)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096207dea1db57f7fb4dd39ac34fae40">doMerge</a> (SmallVectorImpl&lt; GlobalVariable * &gt; &amp;Globals, Module &amp;M, bool isConst, unsigned AddrSpace) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ca82d1bfceeeb7d233f3369117c89f">doMerge</a> (const SmallVectorImpl&lt; GlobalVariable * &gt; &amp;Globals, const BitVector &amp;GlobalSet, Module &amp;M, bool isConst, unsigned AddrSpace) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge everything in <span class="doxyComputerOutput">Globals</span> for which the corresponding bit in <span class="doxyComputerOutput">GlobalSet</span> is set. <a href="#a90ca82d1bfceeeb7d233f3369117c89f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fc09fb838f59fed98a6f167fa977011">isMustKeepGlobalVariable</a> (const GlobalVariable *GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the given variable has been identified as must keep. <a href="#a4fc09fb838f59fed98a6f167fa977011">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8560f510f9697a78dcea7a156c125647">setMustKeepGlobalVariables</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect every variables marked as "used" or used in a landing pad instruction for this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="#a8560f510f9697a78dcea7a156c125647">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04b6df248c43d33b1f33430b27880a8f">collectUsedGlobalVariables</a> (Module &amp;M, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect every variables marked as "used". <a href="#a04b6df248c43d33b1f33430b27880a8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb652cb4b93a8cc3ff3228019fd258ec">TM</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/globalmergeoptions">GlobalMergeOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09abb233077f0ac39b14862c0bb351e1">Opt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4604d54933fd594e6942cb7d6599ee">IsMachO</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dee4c84827bbc0923e779d39e85e84f">MustKeepGlobalVariables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> that must not be merged away. <a href="#a7dee4c84827bbc0923e779d39e85e84f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GlobalMergeImpl() {#a41919fdcc1f1177cab71dbf318873f4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::GlobalMergeImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM, <a href="/web-llvm/docs/api/structs/llvm/globalmergeoptions">GlobalMergeOptions</a> Opt)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a9fbe2dcb11cb3bb78be4d97f388b0c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobalMergeImpl::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp/#ac8d706cc05787b7897af799445df6ab4">EnableGlobalMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a0b2e3fb45c4435c29abebf7768a77cd6">llvm::GlobalObject::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a913a5d4b2cddde762446bd494e81a3f2">llvm::GlobalValue::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a1847e956a0087fefdb49e2a9583c7d18">llvm::GlobalValue::hasExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a794d6b65a466293b4ce971189b2e9ab1">llvm::GlobalVariable::hasImplicitSection</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#aa859e108741fa64681b63f0c0c672512">llvm::GlobalVariable::isConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a444e46ff0a17a6c9480eb151bd42c9bc">llvm::Triple::isOSBinFormatMachO</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp/#a61c689c74953fd5b39b85cb2d9cd356a">isSpecialMachOSection</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a40631ccf8ca06c1942f13f4872ed8e86">llvm::GlobalValue::isTagged</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a239427c2c3a01e23bd15b29633696536">llvm::GlobalValue::isThreadLocal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectUsedGlobalVariables() {#a04b6df248c43d33b1f33430b27880a8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalMergeImpl::collectUsedGlobalVariables (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect every variables marked as "used".</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

### doMerge() {#a096207dea1db57f7fb4dd39ac34fae40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobalMergeImpl::doMerge (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; &amp; Globals, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, bool isConst, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

### doMerge() {#a90ca82d1bfceeeb7d233f3369117c89f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobalMergeImpl::doMerge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; &amp; Globals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; GlobalSet, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, bool isConst, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge everything in <span class="doxyComputerOutput">Globals</span> for which the corresponding bit in <span class="doxyComputerOutput">GlobalSet</span> is set.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

### isMustKeepGlobalVariable() {#a4fc09fb838f59fed98a6f167fa977011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GlobalMerge.cpp}::GlobalMergeImpl::isMustKeepGlobalVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
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

<p>Check if the given variable has been identified as must keep.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setMustKeepGlobalVariables must have been called on the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> that contains GV</p></dd>
</dl>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

### setMustKeepGlobalVariables() {#a8560f510f9697a78dcea7a156c125647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalMergeImpl::setMustKeepGlobalVariables (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect every variables marked as "used" or used in a landing pad instruction for this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsMachO {#a9f4604d54933fd594e6942cb7d6599ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GlobalMerge.cpp}::GlobalMergeImpl::IsMachO = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

### MustKeepGlobalVariables {#a7dee4c84827bbc0923e779d39e85e84f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;const GlobalVariable *, 16&gt; anonymous{GlobalMerge.cpp}::GlobalMergeImpl::MustKeepGlobalVariables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> that must not be merged away.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

### Opt {#a09abb233077f0ac39b14862c0bb351e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalMergeOptions anonymous{GlobalMerge.cpp}::GlobalMergeImpl::Opt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

### TM {#afb652cb4b93a8cc3ff3228019fd258ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine* anonymous{GlobalMerge.cpp}::GlobalMergeImpl::TM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
