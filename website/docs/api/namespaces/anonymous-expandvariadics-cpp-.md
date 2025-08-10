---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-expandvariadics-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{ExpandVariadics.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{ExpandVariadics.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/variadicabiinfo">VariadicABIInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics">ExpandVariadics</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/amdgpu">Amdgpu</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/nvptx">NVPTX</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/wasm">Wasm</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9912cc0ddb2acf81deb09928b564dcc5">commandLineOverride</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4540c0cbec2275709abb4da6a19ff0a">getPreexistingDeclaration</a> (Module *M, Intrinsic::ID Id, ArrayRef&lt; Type * &gt; Tys={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a4981871ea1a597d1b8aa1a8ac9326e76">ExpandVariadicsMode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacaf29f01b880fecaebfb2b3f75046e6">ExpandVariadicsModeOption</a>(DEBUG_TYPE "-override", cl::desc("Override the behaviour of " DEBUG_TYPE), cl::init(ExpandVariadicsMode::Unspecified), cl::values(clEnumValN(ExpandVariadicsMode::Unspecified, "unspecified", "Use the implementation defaults"), clEnumValN(ExpandVariadicsMode::Disable, "disable", "Disable the pass entirely"), clEnumValN(ExpandVariadicsMode::Optimize, "optimize", "Optimise without changing ABI"), clEnumValN(ExpandVariadicsMode::Lowering, "lowering", "Change variadic calling convention")))</td>
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

### commandLineOverride() {#a9912cc0ddb2acf81deb09928b564dcc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ExpandVariadics.cpp}::commandLineOverride ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/expandvariadics-cpp">ExpandVariadics.cpp</a>.</p>


<p>References <a href="#aacaf29f01b880fecaebfb2b3f75046e6">ExpandVariadicsModeOption</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4981871ea1a597d1b8aa1a8ac9326e76a6fcdc090caeade09d0efd6253932b6f5">llvm::Unspecified</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/wasm/#a96d039c96afbf67ded647b706f78ca98">anonymous{ExpandVariadics.cpp}::Wasm::enableForTarget</a> and <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a134c341d80127bc7b6d97367c75f1ee2">anonymous{ExpandVariadics.cpp}::ExpandVariadics::ExpandVariadics</a>.</p>

</div>
</div>

### getPreexistingDeclaration() {#af4540c0cbec2275709abb4da6a19ff0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * anonymous{ExpandVariadics.cpp}::getPreexistingDeclaration (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> Id, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/expandvariadics-cpp">ExpandVariadics.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#aa3c62e205e5ee59bf14ce978b994254b">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandIntrinsicUsers</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ExpandVariadicsModeOption {#aacaf29f01b880fecaebfb2b3f75046e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; ExpandVariadicsMode &gt; anonymous{ExpandVariadics.cpp}::ExpandVariadicsModeOption(DEBUG_TYPE "-override", cl::desc("Override the behaviour of " DEBUG_TYPE), cl::init(ExpandVariadicsMode::Unspecified), cl::values(clEnumValN(ExpandVariadicsMode::Unspecified, "unspecified", "Use the implementation defaults"), clEnumValN(ExpandVariadicsMode::Disable, "disable", "Disable the pass entirely"), clEnumValN(ExpandVariadicsMode::Optimize, "optimize", "Optimise without changing ABI"), clEnumValN(ExpandVariadicsMode::Lowering, "lowering", "Change variadic calling convention")))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/expandvariadics-cpp">ExpandVariadics.cpp</a>.</p>


<p>Referenced by <a href="#a9912cc0ddb2acf81deb09928b564dcc5">commandLineOverride</a> and <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a134c341d80127bc7b6d97367c75f1ee2">anonymous{ExpandVariadics.cpp}::ExpandVariadics::ExpandVariadics</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/expandvariadics-cpp">ExpandVariadics.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
