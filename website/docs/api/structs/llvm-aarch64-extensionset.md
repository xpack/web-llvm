---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/aarch64/extensionset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ExtensionSet` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::AArch64::ExtensionSet { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">llvm/TargetParser/AArch64TargetParser.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f5511f900f363e101eac0e41bc4897">ExtensionSet</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb97b8dc93c00e11322ab50d38af5cc">enable</a> (ArchExtKind E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d8949e52db708a022cbbcdcb7c208b9">disable</a> (ArchExtKind E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a63a256c9ab499323f8b43f3fa735b4">addCPUDefaults</a> (const CpuInfo &amp;CPU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5407a967d3a81aaf557ecbf7a934be9">addArchDefaults</a> (const ArchInfo &amp;Arch)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47d4274efc34b5d09e3d8142be273a11">parseModifier</a> (StringRef Modifier, const bool AllowNoDashForm=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed6b5ea3f92894e52b1c3f80ed8328e9">reconstructFromParsedFeatures</a> (const std::vector&lt; std::string &gt; &amp;Features, std::vector&lt; std::string &gt; &amp;NonExtensions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a99f85cae5335e38e992e25213e742e1f">toLLVMFeatureList</a> (std::vector&lt; T &gt; &amp;Features) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab27024b311d3f9c74cc7925e9453b41e">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ab9eb507e3ecbe2013467afa449ffa0f9">ExtensionBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31a57bddab98fb8e4964c8ce7170783">Enabled</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ab9eb507e3ecbe2013467afa449ffa0f9">ExtensionBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b2247af51e8857f2055d9406c07142f">Touched</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aarch64/archinfo">ArchInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace6581565c112029afb741683c7b254c">BaseArch</a></td>
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


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ExtensionSet() {#a44f5511f900f363e101eac0e41bc4897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AArch64::ExtensionSet::ExtensionSet ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>.</p>


<p>References <a href="#ace6581565c112029afb741683c7b254c">BaseArch</a>, <a href="#ad31a57bddab98fb8e4964c8ce7170783">Enabled</a> and <a href="#a3b2247af51e8857f2055d9406c07142f">Touched</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addArchDefaults() {#ae5407a967d3a81aaf557ecbf7a934be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64::ExtensionSet::addArchDefaults (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aarch64/archinfo">ArchInfo</a> &amp; Arch)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>, definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp">AArch64TargetParser.cpp</a>.</p>


<p>References <a href="#ace6581565c112029afb741683c7b254c">BaseArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/aarch64/archinfo/#a51fc137709da12700c485a2bc19c0a33">llvm::AArch64::ArchInfo::DefaultExts</a>, <a href="#a8cb97b8dc93c00e11322ab50d38af5cc">enable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-cpp/#aeb3e6d0c41c374eb76421fe8549919e5">Extensions</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/aarch64/archinfo/#aaa32711032a63c63164a2eb89a7e40eb">llvm::AArch64::ArchInfo::Name</a> and <a href="/web-llvm/docs/api/classes/llvm/bitset/#acccf045b3bb2e2c65278ef58ddbedea8">llvm::Bitset&lt; NumBits &gt;::test</a>.</p>

</div>
</div>

### addCPUDefaults() {#a7a63a256c9ab499323f8b43f3fa735b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64::ExtensionSet::addCPUDefaults (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aarch64/cpuinfo">CpuInfo</a> &amp; CPU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp">AArch64TargetParser.cpp</a>.</p>


<p>References <a href="#ace6581565c112029afb741683c7b254c">BaseArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8cb97b8dc93c00e11322ab50d38af5cc">enable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-cpp/#aeb3e6d0c41c374eb76421fe8549919e5">Extensions</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/bitset/#acccf045b3bb2e2c65278ef58ddbedea8">llvm::Bitset&lt; NumBits &gt;::test</a>.</p>

</div>
</div>

### disable() {#a8d8949e52db708a022cbbcdcb7c208b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64::ExtensionSet::disable (ArchExtKind E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp">AArch64TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8d8949e52db708a022cbbcdcb7c208b9">disable</a>, <a href="#ad31a57bddab98fb8e4964c8ce7170783">Enabled</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp/#a9725d50c0bb446f78899810808767173">lookupExtensionByID</a> and <a href="#a3b2247af51e8857f2055d9406c07142f">Touched</a>.</p>


<p>Referenced by <a href="#a8d8949e52db708a022cbbcdcb7c208b9">disable</a> and <a href="#a47d4274efc34b5d09e3d8142be273a11">parseModifier</a>.</p>

</div>
</div>

### dump() {#ab27024b311d3f9c74cc7925e9453b41e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64::ExtensionSet::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>, definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp">AArch64TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a> and <a href="#a99f85cae5335e38e992e25213e742e1f">toLLVMFeatureList</a>.</p>

</div>
</div>

### enable() {#a8cb97b8dc93c00e11322ab50d38af5cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64::ExtensionSet::enable (ArchExtKind E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp">AArch64TargetParser.cpp</a>.</p>


<p>References <a href="#ace6581565c112029afb741683c7b254c">BaseArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8cb97b8dc93c00e11322ab50d38af5cc">enable</a>, <a href="#ad31a57bddab98fb8e4964c8ce7170783">Enabled</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp/#a9725d50c0bb446f78899810808767173">lookupExtensionByID</a> and <a href="#a3b2247af51e8857f2055d9406c07142f">Touched</a>.</p>


<p>Referenced by <a href="#ae5407a967d3a81aaf557ecbf7a934be9">addArchDefaults</a>, <a href="#a7a63a256c9ab499323f8b43f3fa735b4">addCPUDefaults</a>, <a href="#a8cb97b8dc93c00e11322ab50d38af5cc">enable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#afe6b6a41ff4717d81f9c6a58edf21b07">llvm::AArch64::getCpuSupportsMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a631930ac8ee64052b5ee41d928a65a2d">llvm::AArch64::getFMVPriority</a> and <a href="#a47d4274efc34b5d09e3d8142be273a11">parseModifier</a>.</p>

</div>
</div>

### parseModifier() {#a47d4274efc34b5d09e3d8142be273a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64::ExtensionSet::parseModifier (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Modifier, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool AllowNoDashForm=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp">AArch64TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8d8949e52db708a022cbbcdcb7c208b9">disable</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="#a8cb97b8dc93c00e11322ab50d38af5cc">enable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a1a125d48909fc453d01785064bfb5e67">llvm::AArch64::parseArchExtension</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

</div>
</div>

### reconstructFromParsedFeatures() {#aed6b5ea3f92894e52b1c3f80ed8328e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64::ExtensionSet::reconstructFromParsedFeatures (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; Features, std::vector&lt; std::string &gt; &amp; NonExtensions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp">AArch64TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad31a57bddab98fb8e4964c8ce7170783">Enabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ac86711dd664d206e40b114dcdd856c9a">llvm::AArch64::targetFeatureToExtension</a> and <a href="#a3b2247af51e8857f2055d9406c07142f">Touched</a>.</p>

</div>
</div>

### toLLVMFeatureList() {#a99f85cae5335e38e992e25213e742e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64::ExtensionSet::toLLVMFeatureList (std::vector&lt; T &gt; &amp; Features)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>.</p>


<p>References <a href="#ace6581565c112029afb741683c7b254c">BaseArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#ad31a57bddab98fb8e4964c8ce7170783">Enabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-cpp/#aeb3e6d0c41c374eb76421fe8549919e5">Extensions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a3b2247af51e8857f2055d9406c07142f">Touched</a>.</p>


<p>Referenced by <a href="#ab27024b311d3f9c74cc7925e9453b41e">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BaseArch {#ace6581565c112029afb741683c7b254c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ArchInfo* llvm::AArch64::ExtensionSet::BaseArch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>.</p>


<p>Referenced by <a href="#ae5407a967d3a81aaf557ecbf7a934be9">addArchDefaults</a>, <a href="#a7a63a256c9ab499323f8b43f3fa735b4">addCPUDefaults</a>, <a href="#a8cb97b8dc93c00e11322ab50d38af5cc">enable</a>, <a href="#a44f5511f900f363e101eac0e41bc4897">ExtensionSet</a> and <a href="#a99f85cae5335e38e992e25213e742e1f">toLLVMFeatureList</a>.</p>

</div>
</div>

### Enabled {#ad31a57bddab98fb8e4964c8ce7170783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExtensionBitset llvm::AArch64::ExtensionSet::Enabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>.</p>


<p>Referenced by <a href="#a8d8949e52db708a022cbbcdcb7c208b9">disable</a>, <a href="#a8cb97b8dc93c00e11322ab50d38af5cc">enable</a>, <a href="#a44f5511f900f363e101eac0e41bc4897">ExtensionSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#afe6b6a41ff4717d81f9c6a58edf21b07">llvm::AArch64::getCpuSupportsMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a631930ac8ee64052b5ee41d928a65a2d">llvm::AArch64::getFMVPriority</a>, <a href="#aed6b5ea3f92894e52b1c3f80ed8328e9">reconstructFromParsedFeatures</a> and <a href="#a99f85cae5335e38e992e25213e742e1f">toLLVMFeatureList</a>.</p>

</div>
</div>

### Touched {#a3b2247af51e8857f2055d9406c07142f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExtensionBitset llvm::AArch64::ExtensionSet::Touched</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a>.</p>


<p>Referenced by <a href="#a8d8949e52db708a022cbbcdcb7c208b9">disable</a>, <a href="#a8cb97b8dc93c00e11322ab50d38af5cc">enable</a>, <a href="#a44f5511f900f363e101eac0e41bc4897">ExtensionSet</a>, <a href="#aed6b5ea3f92894e52b1c3f80ed8328e9">reconstructFromParsedFeatures</a> and <a href="#a99f85cae5335e38e992e25213e742e1f">toLLVMFeatureList</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">AArch64TargetParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp">AArch64TargetParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
