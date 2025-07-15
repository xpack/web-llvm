---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/lto/ltollvmcontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LTOLLVMContext` Struct Reference

<p>A derived class of <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> that initializes itself according to a given <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> object. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::lto::LTOLLVMContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">llvm/LTO/Config.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an important class for using LLVM in a threaded context. <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce6014f3756bf479e3592ed2ae5f769">LTOLLVMContext</a> (const Config &amp;C)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1d9ed2529f1248d760979b7b53a64394">DiagnosticHandlerFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab68cfda3ece4ea1114fcdd69c8702929">DiagHandler</a></td>
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

## Description {#details}

<p>A derived class of <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> that initializes itself according to a given <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> object.</p>


<p>The purpose of this class is to tie ownership of the diagnostic handler to the context, as opposed to the <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> object (which may be ephemeral).</p>


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LTOLLVMContext() {#afce6014f3756bf479e3592ed2ae5f769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::lto::LTOLLVMContext::LTOLLVMContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; C)</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ab68cfda3ece4ea1114fcdd69c8702929">DiagHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a495179fcb4553807d7aa184d083dde47">llvm::LLVMContext::enableDebugTypeODRUniquing</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#af00a4d3e0ec33c889e807f9e507493ee">llvm::LLVMContext::setDiagnosticHandler</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#ab9f1ae83b6064a4d27b44857afd71100">llvm::LLVMContext::setDiscardValueNames</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DiagHandler {#ab68cfda3ece4ea1114fcdd69c8702929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticHandlerFunction llvm::lto::LTOLLVMContext::DiagHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="#afce6014f3756bf479e3592ed2ae5f769">LTOLLVMContext</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
