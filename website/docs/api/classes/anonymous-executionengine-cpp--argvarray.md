---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-executionengine-cpp-/argvarray
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ArgvArray` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{ExecutionEngine.cpp}::ArgvArray { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b5f64c809ca91e2a09b5b97d80e23a7">reset</a> (LLVMContext &amp;C, ExecutionEngine *EE, const std::vector&lt; std::string &gt; &amp;InputArgv)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn a vector of strings into a nice argv style array of pointers to null terminated strings. <a href="#a3b5f64c809ca91e2a09b5b97d80e23a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; char[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bf45e3a2b7a1649a73f8737193e0b4d">Array</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; char[]&gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab07736ab61f7b691819663a346ec6e35">Values</a></td>
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


<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### reset() {#a3b5f64c809ca91e2a09b5b97d80e23a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * ArgvArray::reset (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> * EE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; InputArgv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Turn a vector of strings into a nice argv style array of pointers to null terminated strings.</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a221f82626a9fd6d8dc7c76e097940b07">llvm::ExecutionEngine::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#ac4d8e60ce9a5b62049e6b71f19a24c8b">llvm::DataLayout::getPointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77905b5e34e8754df1ed4051e0ad9d1a">llvm::PTOGV</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a08ed33d3b3f8b9e21167918d5de40014">llvm::ExecutionEngine::StoreValueToMemory</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Array {#a6bf45e3a2b7a1649a73f8737193e0b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;char[]&gt; anonymous{ExecutionEngine.cpp}::ArgvArray::Array</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>

</div>
</div>

### Values {#ab07736ab61f7b691819663a346ec6e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;char[]&gt; &gt; anonymous{ExecutionEngine.cpp}::ArgvArray::Values</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
