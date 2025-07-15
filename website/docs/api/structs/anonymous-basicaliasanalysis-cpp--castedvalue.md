---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CastedValue` Struct Reference

<p>Represents zext(sext(trunc(V))). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{BasicAliasAnalysis.cpp}::CastedValue { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a5ec3d918e562a5b1a7927f13518ed8">CastedValue</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2aaf56894b1ec5e9ef3fb9df4e141bd">CastedValue</a> (const Value *V, unsigned ZExtBits, unsigned SExtBits, unsigned TruncBits, bool IsNonNegative)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6cb84a3f7e823cbddebde07da81d398">getBitWidth</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue">CastedValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a76515fd7db6500d61cac6863fd6e94">withValue</a> (const Value *NewV, bool PreserveNonNeg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue">CastedValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096cb21b10c3d48f35a912947974c872">withZExtOfValue</a> (const Value *NewV, bool ZExtNonNegative) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace V with zext(NewV) <a href="#a096cb21b10c3d48f35a912947974c872">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue">CastedValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed4aebc49d7a699dc40a248391f0ac1">withSExtOfValue</a> (const Value *NewV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace V with sext(NewV) <a href="#a5ed4aebc49d7a699dc40a248391f0ac1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6216e095ec50beb58f5fa0306f057f5">evaluateWith</a> (APInt N) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5333260b4104fef104ea3459553cae1">evaluateWith</a> (ConstantRange N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa11d2e2cac5e70f381f2edfc28322b32">canDistributeOver</a> (bool NUW, bool NSW) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47b902b0ff11d91436480ec6e7b4b1bd">hasSameCastsAs</a> (const CastedValue &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4580be670e873b2cb68b49ca97da7ef5">V</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4979bf7334784fac6bb213a62a3386b3">ZExtBits</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bc16926f9fd4511304d06379845e914">SExtBits</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe0148bf65f6c0eb81a3d807fb12a410">TruncBits</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a0e1440d27c963222e5b1f84ccf3f8d">IsNonNegative</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether trunc(V) is non-negative. <a href="#a1a0e1440d27c963222e5b1f84ccf3f8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents zext(sext(trunc(V))).</p>

<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CastedValue() {#a2a5ec3d918e562a5b1a7927f13518ed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BasicAliasAnalysis.cpp}::CastedValue::CastedValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Reference <a href="#a4580be670e873b2cb68b49ca97da7ef5">V</a>.</p>


<p>Referenced by <a href="#a47b902b0ff11d91436480ec6e7b4b1bd">hasSameCastsAs</a>, <a href="#a5ed4aebc49d7a699dc40a248391f0ac1">withSExtOfValue</a>, <a href="#a5a76515fd7db6500d61cac6863fd6e94">withValue</a> and <a href="#a096cb21b10c3d48f35a912947974c872">withZExtOfValue</a>.</p>

</div>
</div>

### CastedValue() {#ad2aaf56894b1ec5e9ef3fb9df4e141bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BasicAliasAnalysis.cpp}::CastedValue::CastedValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned ZExtBits, unsigned SExtBits, unsigned TruncBits, bool IsNonNegative)</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#a1a0e1440d27c963222e5b1f84ccf3f8d">IsNonNegative</a>, <a href="#a0bc16926f9fd4511304d06379845e914">SExtBits</a>, <a href="#abe0148bf65f6c0eb81a3d807fb12a410">TruncBits</a>, <a href="#a4580be670e873b2cb68b49ca97da7ef5">V</a> and <a href="#a4979bf7334784fac6bb213a62a3386b3">ZExtBits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canDistributeOver() {#aa11d2e2cac5e70f381f2edfc28322b32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BasicAliasAnalysis.cpp}::CastedValue::canDistributeOver (bool NUW, bool NSW)</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#a0bc16926f9fd4511304d06379845e914">SExtBits</a> and <a href="#a4979bf7334784fac6bb213a62a3386b3">ZExtBits</a>.</p>

</div>
</div>

### evaluateWith() {#ad6216e095ec50beb58f5fa0306f057f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt anonymous{BasicAliasAnalysis.cpp}::CastedValue::evaluateWith (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> N)</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a0bc16926f9fd4511304d06379845e914">SExtBits</a>, <a href="#abe0148bf65f6c0eb81a3d807fb12a410">TruncBits</a>, <a href="#a4580be670e873b2cb68b49ca97da7ef5">V</a> and <a href="#a4979bf7334784fac6bb213a62a3386b3">ZExtBits</a>.</p>

</div>
</div>

### evaluateWith() {#af5333260b4104fef104ea3459553cae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange anonymous{BasicAliasAnalysis.cpp}::CastedValue::evaluateWith (<a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> N)</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="#a1a0e1440d27c963222e5b1f84ccf3f8d">IsNonNegative</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a0bc16926f9fd4511304d06379845e914">SExtBits</a>, <a href="#abe0148bf65f6c0eb81a3d807fb12a410">TruncBits</a>, <a href="#a4580be670e873b2cb68b49ca97da7ef5">V</a> and <a href="#a4979bf7334784fac6bb213a62a3386b3">ZExtBits</a>.</p>

</div>
</div>

### getBitWidth() {#ab6cb84a3f7e823cbddebde07da81d398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BasicAliasAnalysis.cpp}::CastedValue::getBitWidth ()</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#a0bc16926f9fd4511304d06379845e914">SExtBits</a>, <a href="#abe0148bf65f6c0eb81a3d807fb12a410">TruncBits</a>, <a href="#a4580be670e873b2cb68b49ca97da7ef5">V</a> and <a href="#a4979bf7334784fac6bb213a62a3386b3">ZExtBits</a>.</p>

</div>
</div>

### hasSameCastsAs() {#a47b902b0ff11d91436480ec6e7b4b1bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BasicAliasAnalysis.cpp}::CastedValue::hasSameCastsAs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue">CastedValue</a> &amp; Other)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#a2a5ec3d918e562a5b1a7927f13518ed8">CastedValue</a>, <a href="#a1a0e1440d27c963222e5b1f84ccf3f8d">IsNonNegative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a0bc16926f9fd4511304d06379845e914">SExtBits</a>, <a href="#abe0148bf65f6c0eb81a3d807fb12a410">TruncBits</a>, <a href="#a4580be670e873b2cb68b49ca97da7ef5">V</a> and <a href="#a4979bf7334784fac6bb213a62a3386b3">ZExtBits</a>.</p>

</div>
</div>

### withSExtOfValue() {#a5ed4aebc49d7a699dc40a248391f0ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastedValue anonymous{BasicAliasAnalysis.cpp}::CastedValue::withSExtOfValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewV)</td>
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

<p>Replace V with sext(NewV)</p>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#a2a5ec3d918e562a5b1a7927f13518ed8">CastedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a1a0e1440d27c963222e5b1f84ccf3f8d">IsNonNegative</a>, <a href="#a0bc16926f9fd4511304d06379845e914">SExtBits</a>, <a href="#abe0148bf65f6c0eb81a3d807fb12a410">TruncBits</a>, <a href="#a4580be670e873b2cb68b49ca97da7ef5">V</a> and <a href="#a4979bf7334784fac6bb213a62a3386b3">ZExtBits</a>.</p>

</div>
</div>

### withValue() {#a5a76515fd7db6500d61cac6863fd6e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastedValue anonymous{BasicAliasAnalysis.cpp}::CastedValue::withValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewV, bool PreserveNonNeg)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#a2a5ec3d918e562a5b1a7927f13518ed8">CastedValue</a>, <a href="#a1a0e1440d27c963222e5b1f84ccf3f8d">IsNonNegative</a>, <a href="#a0bc16926f9fd4511304d06379845e914">SExtBits</a>, <a href="#abe0148bf65f6c0eb81a3d807fb12a410">TruncBits</a> and <a href="#a4979bf7334784fac6bb213a62a3386b3">ZExtBits</a>.</p>

</div>
</div>

### withZExtOfValue() {#a096cb21b10c3d48f35a912947974c872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastedValue anonymous{BasicAliasAnalysis.cpp}::CastedValue::withZExtOfValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewV, bool ZExtNonNegative)</td>
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

<p>Replace V with zext(NewV)</p>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#a2a5ec3d918e562a5b1a7927f13518ed8">CastedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a1a0e1440d27c963222e5b1f84ccf3f8d">IsNonNegative</a>, <a href="#a0bc16926f9fd4511304d06379845e914">SExtBits</a>, <a href="#abe0148bf65f6c0eb81a3d807fb12a410">TruncBits</a>, <a href="#a4580be670e873b2cb68b49ca97da7ef5">V</a> and <a href="#a4979bf7334784fac6bb213a62a3386b3">ZExtBits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsNonNegative {#a1a0e1440d27c963222e5b1f84ccf3f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BasicAliasAnalysis.cpp}::CastedValue::IsNonNegative = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether trunc(V) is non-negative.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#ad2aaf56894b1ec5e9ef3fb9df4e141bd">CastedValue</a>, <a href="#af5333260b4104fef104ea3459553cae1">evaluateWith</a>, <a href="#a47b902b0ff11d91436480ec6e7b4b1bd">hasSameCastsAs</a>, <a href="#a5ed4aebc49d7a699dc40a248391f0ac1">withSExtOfValue</a>, <a href="#a5a76515fd7db6500d61cac6863fd6e94">withValue</a> and <a href="#a096cb21b10c3d48f35a912947974c872">withZExtOfValue</a>.</p>

</div>
</div>

### SExtBits {#a0bc16926f9fd4511304d06379845e914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BasicAliasAnalysis.cpp}::CastedValue::SExtBits = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#aa11d2e2cac5e70f381f2edfc28322b32">canDistributeOver</a>, <a href="#ad2aaf56894b1ec5e9ef3fb9df4e141bd">CastedValue</a>, <a href="#ad6216e095ec50beb58f5fa0306f057f5">evaluateWith</a>, <a href="#af5333260b4104fef104ea3459553cae1">evaluateWith</a>, <a href="#ab6cb84a3f7e823cbddebde07da81d398">getBitWidth</a>, <a href="#a47b902b0ff11d91436480ec6e7b4b1bd">hasSameCastsAs</a>, <a href="#a5ed4aebc49d7a699dc40a248391f0ac1">withSExtOfValue</a>, <a href="#a5a76515fd7db6500d61cac6863fd6e94">withValue</a> and <a href="#a096cb21b10c3d48f35a912947974c872">withZExtOfValue</a>.</p>

</div>
</div>

### TruncBits {#abe0148bf65f6c0eb81a3d807fb12a410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BasicAliasAnalysis.cpp}::CastedValue::TruncBits = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#ad2aaf56894b1ec5e9ef3fb9df4e141bd">CastedValue</a>, <a href="#ad6216e095ec50beb58f5fa0306f057f5">evaluateWith</a>, <a href="#af5333260b4104fef104ea3459553cae1">evaluateWith</a>, <a href="#ab6cb84a3f7e823cbddebde07da81d398">getBitWidth</a>, <a href="#a47b902b0ff11d91436480ec6e7b4b1bd">hasSameCastsAs</a>, <a href="#a5ed4aebc49d7a699dc40a248391f0ac1">withSExtOfValue</a>, <a href="#a5a76515fd7db6500d61cac6863fd6e94">withValue</a> and <a href="#a096cb21b10c3d48f35a912947974c872">withZExtOfValue</a>.</p>

</div>
</div>

### V {#a4580be670e873b2cb68b49ca97da7ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value* anonymous{BasicAliasAnalysis.cpp}::CastedValue::V</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#a2a5ec3d918e562a5b1a7927f13518ed8">CastedValue</a>, <a href="#ad2aaf56894b1ec5e9ef3fb9df4e141bd">CastedValue</a>, <a href="#ad6216e095ec50beb58f5fa0306f057f5">evaluateWith</a>, <a href="#af5333260b4104fef104ea3459553cae1">evaluateWith</a>, <a href="#ab6cb84a3f7e823cbddebde07da81d398">getBitWidth</a>, <a href="#a47b902b0ff11d91436480ec6e7b4b1bd">hasSameCastsAs</a>, <a href="#a5ed4aebc49d7a699dc40a248391f0ac1">withSExtOfValue</a> and <a href="#a096cb21b10c3d48f35a912947974c872">withZExtOfValue</a>.</p>

</div>
</div>

### ZExtBits {#a4979bf7334784fac6bb213a62a3386b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BasicAliasAnalysis.cpp}::CastedValue::ZExtBits = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#aa11d2e2cac5e70f381f2edfc28322b32">canDistributeOver</a>, <a href="#ad2aaf56894b1ec5e9ef3fb9df4e141bd">CastedValue</a>, <a href="#ad6216e095ec50beb58f5fa0306f057f5">evaluateWith</a>, <a href="#af5333260b4104fef104ea3459553cae1">evaluateWith</a>, <a href="#ab6cb84a3f7e823cbddebde07da81d398">getBitWidth</a>, <a href="#a47b902b0ff11d91436480ec6e7b4b1bd">hasSameCastsAs</a>, <a href="#a5ed4aebc49d7a699dc40a248391f0ac1">withSExtOfValue</a>, <a href="#a5a76515fd7db6500d61cac6863fd6e94">withValue</a> and <a href="#a096cb21b10c3d48f35a912947974c872">withZExtOfValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
