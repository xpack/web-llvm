---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64targettransforminfo-cpp-/tailfoldingoption
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TailFoldingOption` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption { ... }
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5df8b2fca0d3dc356531c2f218468d2f">operator=</a> (const std::string &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a914ecb2005e7f0036893d8673b0899da">satisfies</a> (TailFoldingOpts DefaultBits, TailFoldingOpts Required) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a034082a159f51b1d563d96ab010376cc">setInitialBits</a> (TailFoldingOpts Bits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa414e18450efcf7dd7c1828970045323">setNeedsDefault</a> (bool V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d3a04451588263142a969ed5cb69084">setEnableBit</a> (TailFoldingOpts Bit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6ef41b5734495b1c28682a30abd1c61">setDisableBit</a> (TailFoldingOpts Bit)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5e573318939ed02d1196abaa42dbfb9">getBits</a> (TailFoldingOpts DefaultBits) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af87f4dc6f80a34ffbda0f9668e3fa7">reportError</a> (std::string Opt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a65727c105217673af8de338841bfe9">InitialBits</a> = TailFoldingOpts::Disabled</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acebbddae9677ffd2384e734242c8ffdc">EnableBits</a> = TailFoldingOpts::Disabled</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb73cb936b597ae440e26fa1e515c2ad">DisableBits</a> = TailFoldingOpts::Disabled</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24ae6bf7981e13ab38c770d1fe7e54a5">NeedsDefault</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator=() {#a5df8b2fca0d3dc356531c2f218468d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Val)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafab1c94ca2fbc3e78fc30069c8d0f01680">llvm::All</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafab9f5c797ebbf55adccdd8539a65a0241">llvm::Disabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafae6e6ea6e9749f93edb712ccdd8c6c739">llvm::Recurrences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafa9a819585a6c0017acaff053c740cec70">llvm::Reductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#aecb8af888c92e0b415ae5021d9c7a59a">reportError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafa67f115c1fddc4ce1aeb1c754001585bc">llvm::Reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafa1fbb1e3943c2c6c560247ac8f9289780">llvm::Simple</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### satisfies() {#a914ecb2005e7f0036893d8673b0899da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::satisfies (<a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a> DefaultBits, <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a> Required)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp/#a8b337b7ad70a02d9f16846802e59f5f4">getBits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getBits() {#ae5e573318939ed02d1196abaa42dbfb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TailFoldingOpts anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::getBits (<a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a> DefaultBits)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### reportError() {#a0af87f4dc6f80a34ffbda0f9668e3fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::reportError (std::string Opt)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### setDisableBit() {#ac6ef41b5734495b1c28682a30abd1c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::setDisableBit (<a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a> Bit)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### setEnableBit() {#a0d3a04451588263142a969ed5cb69084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::setEnableBit (<a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a> Bit)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### setInitialBits() {#a034082a159f51b1d563d96ab010376cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::setInitialBits (<a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a> Bits)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### setNeedsDefault() {#aa414e18450efcf7dd7c1828970045323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::setNeedsDefault (bool V)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DisableBits {#aeb73cb936b597ae440e26fa1e515c2ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TailFoldingOpts anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::DisableBits = TailFoldingOpts::Disabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### EnableBits {#acebbddae9677ffd2384e734242c8ffdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TailFoldingOpts anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::EnableBits = TailFoldingOpts::Disabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### InitialBits {#a2a65727c105217673af8de338841bfe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TailFoldingOpts anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::InitialBits = TailFoldingOpts::Disabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### NeedsDefault {#a24ae6bf7981e13ab38c770d1fe7e54a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::NeedsDefault = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp">AArch64TargetTransformInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
