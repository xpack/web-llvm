---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loopidiomrecognize-cpp-/memmoveverifier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemmoveVerifier` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{LoopIdiomRecognize.cpp}::MemmoveVerifier { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1b04de670416ee6d872ad577e5c5074">MemmoveVerifier</a> (const Value &amp;LoadBasePtr, const Value &amp;StoreBasePtr, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f0412aee208de4e6fe854c4c3b50937">loadAndStoreMayFormMemmove</a> (unsigned StoreSize, bool IsNegStride, const Instruction &amp;TheLoad, bool IsMemCpy) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a40f8a8a26c9c96929ba8c79d09f0fc">IsSameObject</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d50f6b19481b62a3cfaffd4afbccd30">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7fc2057e8d707a85a15b2f8954ac6c">LoadOff</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe50ae1d8bc1aafd5f803db645979e76">StoreOff</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a639bdb0bd61e664214c1ddab22ba2caa">BP1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6895eeb9ab0549c9d955a247f9b8148d">BP2</a></td>
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


<p>Definition at line 1197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp">LoopIdiomRecognize.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MemmoveVerifier() {#ac1b04de670416ee6d872ad577e5c5074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopIdiomRecognize.cpp}::MemmoveVerifier::MemmoveVerifier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; LoadBasePtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; StoreBasePtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp">LoopIdiomRecognize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3ac5d9eb48038aa973017317279eadf5">llvm::GetPointerBaseWithConstantOffset</a> and <a href="#a4a40f8a8a26c9c96929ba8c79d09f0fc">IsSameObject</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### loadAndStoreMayFormMemmove() {#a2f0412aee208de4e6fe854c4c3b50937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopIdiomRecognize.cpp}::MemmoveVerifier::loadAndStoreMayFormMemmove (unsigned StoreSize, bool IsNegStride, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; TheLoad, bool IsMemCpy)</td>
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



<p>Definition at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp">LoopIdiomRecognize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsSameObject {#a4a40f8a8a26c9c96929ba8c79d09f0fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{LoopIdiomRecognize.cpp}::MemmoveVerifier::IsSameObject</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1238 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp">LoopIdiomRecognize.cpp</a>.</p>


<p>Referenced by <a href="#ac1b04de670416ee6d872ad577e5c5074">MemmoveVerifier</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BP1 {#a639bdb0bd61e664214c1ddab22ba2caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value* anonymous{LoopIdiomRecognize.cpp}::MemmoveVerifier::BP1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp">LoopIdiomRecognize.cpp</a>.</p>

</div>
</div>

### BP2 {#a6895eeb9ab0549c9d955a247f9b8148d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value* anonymous{LoopIdiomRecognize.cpp}::MemmoveVerifier::BP2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp">LoopIdiomRecognize.cpp</a>.</p>

</div>
</div>

### DL {#a5d50f6b19481b62a3cfaffd4afbccd30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{LoopIdiomRecognize.cpp}::MemmoveVerifier::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp">LoopIdiomRecognize.cpp</a>.</p>

</div>
</div>

### LoadOff {#a7e7fc2057e8d707a85a15b2f8954ac6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{LoopIdiomRecognize.cpp}::MemmoveVerifier::LoadOff = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp">LoopIdiomRecognize.cpp</a>.</p>

</div>
</div>

### StoreOff {#abe50ae1d8bc1aafd5f803db645979e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{LoopIdiomRecognize.cpp}::MemmoveVerifier::StoreOff = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp">LoopIdiomRecognize.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp">LoopIdiomRecognize.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
