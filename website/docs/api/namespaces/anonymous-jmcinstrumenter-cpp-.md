---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-jmcinstrumenter-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{JMCInstrumenter.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{JMCInstrumenter.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-jmcinstrumenter-cpp-/jmcinstrumenter">JMCInstrumenter</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf0c2486053fb36198712fec3c354365">getFlagName</a> (DISubprogram &amp;SP, bool UseX86FastCall)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af680d052a24c294259bd765f02906202">attachDebugInfo</a> (GlobalVariable &amp;GV, DISubprogram &amp;SP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7704ada0af8cb169e6cf9dd2dec6171c">getCheckFunctionType</a> (LLVMContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea6556d942d972a777204187dd1600e5">createDefaultCheckFunction</a> (Module &amp;M, bool UseX86FastCall)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac62651c895b0e9dae6359cca86141ba9">CheckFunctionName</a>[] = "__CheckForDebuggerJustMyCode"</td>
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

### attachDebugInfo() {#af680d052a24c294259bd765f02906202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{JMCInstrumenter.cpp}::attachDebugInfo (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; GV, <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> &amp; SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp">JMCInstrumenter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalobject/#aa1b0638c63ba711320b3bb9c69367ed6">llvm::GlobalObject::addMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af680d052a24c294259bd765f02906202">attachDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>.</p>


<p>Referenced by <a href="#af680d052a24c294259bd765f02906202">attachDebugInfo</a>.</p>

</div>
</div>

### createDefaultCheckFunction() {#aea6556d942d972a777204187dd1600e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * anonymous{JMCInstrumenter.cpp}::createDefaultCheckFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, bool UseX86FastCall)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp">JMCInstrumenter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#aa5087b607af833220d9ebab0c88c83c1">llvm::Function::addParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/returninst/#a932710d4c1c965497707751eb4f7948f">llvm::ReturnInst::Create</a>, <a href="#aea6556d942d972a777204187dd1600e5">createDefaultCheckFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="#a7704ada0af8cb169e6cf9dd2dec6171c">getCheckFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">llvm::GlobalValue::Global</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a38c97622dccff7ae31fe0be3b21c9b3d">llvm::GlobalValue::setUnnamedAddr</a>.</p>


<p>Referenced by <a href="#aea6556d942d972a777204187dd1600e5">createDefaultCheckFunction</a>.</p>

</div>
</div>

### getCheckFunctionType() {#a7704ada0af8cb169e6cf9dd2dec6171c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * anonymous{JMCInstrumenter.cpp}::getCheckFunctionType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp">JMCInstrumenter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="#a7704ada0af8cb169e6cf9dd2dec6171c">getCheckFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>.</p>


<p>Referenced by <a href="#aea6556d942d972a777204187dd1600e5">createDefaultCheckFunction</a> and <a href="#a7704ada0af8cb169e6cf9dd2dec6171c">getCheckFunctionType</a>.</p>

</div>
</div>

### getFlagName() {#aaf0c2486053fb36198712fec3c354365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{JMCInstrumenter.cpp}::getFlagName (<a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> &amp; SP, bool UseX86FastCall)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp">JMCInstrumenter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba816fb56fad484d9cd712825dcacaa6">llvm::djbHash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="#aaf0c2486053fb36198712fec3c354365">getFlagName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">llvm::sys::path::native</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa950616e5405e4ef51a87d384180e7aa1">llvm::sys::path::posix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a03907c7df68a93c377bf90c5bdd78ca3">llvm::sys::path::remove_filename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3beda524b0772ca36035db4399a6a571">llvm::utohexstr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa20919b5752b40386cb56aff9b8f07723">llvm::sys::path::windows_backslash</a>.</p>


<p>Referenced by <a href="#aaf0c2486053fb36198712fec3c354365">getFlagName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CheckFunctionName {#ac62651c895b0e9dae6359cca86141ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char anonymous{JMCInstrumenter.cpp}::CheckFunctionName[] = "__CheckForDebuggerJustMyCode"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp">JMCInstrumenter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp">JMCInstrumenter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
