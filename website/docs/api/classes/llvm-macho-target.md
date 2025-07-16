---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/target
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Target` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MachO::Target { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/target-h">llvm/TextAPI/Target.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0861396380ac0f34248d539b8f74baa2">Target</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a74d5ae8a1267c806da8b3a0dc0130">Target</a> (Architecture Arch, PlatformType Platform, VersionTuple MinDeployment={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae060502909a83311796c0e2a11ac6153">Target</a> (const llvm::Triple &amp;Triple)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b01d165e54568f5471186d3bdbfc70">operator std::string</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee9dc737c9effa286ef632263cd45696">Arch</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3cdacd46a54ada4abe329c88c7a92504">PlatformType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a508e7395c12db82efde5c42ecf8985cc">Platform</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af53288d4cf3773021c4dd4aaefc4e861">MinDeployment</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac60f765fb1e3ea2626663548ace96890">create</a> (StringRef Target)</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/target-h">Target.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Target() {#a0861396380ac0f34248d539b8f74baa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::Target::Target ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/target-h">Target.h</a>.</p>


<p>Referenced by <a href="#ac60f765fb1e3ea2626663548ace96890">create</a>.</p>

</div>
</div>

### Target() {#a72a74d5ae8a1267c806da8b3a0dc0130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::Target::Target (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> Arch, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3cdacd46a54ada4abe329c88c7a92504">PlatformType</a> Platform, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> MinDeployment={})</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/target-h">Target.h</a>.</p>


<p>References <a href="#aee9dc737c9effa286ef632263cd45696">Arch</a>, <a href="#af53288d4cf3773021c4dd4aaefc4e861">MinDeployment</a> and <a href="#a508e7395c12db82efde5c42ecf8985cc">Platform</a>.</p>

</div>
</div>

### Target() {#ae060502909a83311796c0e2a11ac6153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::Target::Target (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a> &amp; Triple)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/target-h">Target.h</a>.</p>


<p>References <a href="#aee9dc737c9effa286ef632263cd45696">Arch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac65f424efa3af89c66f5c8ce5eaecc8c">llvm::MachO::mapToArchitecture</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a74b6fee77fe76fef829c29a931a6bdca">llvm::MachO::mapToPlatformType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a44bd2d03a8b75fb4924e7f83430c0c71">llvm::MachO::mapToSupportedOSVersion</a>, <a href="#af53288d4cf3773021c4dd4aaefc4e861">MinDeployment</a> and <a href="#a508e7395c12db82efde5c42ecf8985cc">Platform</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator std::string() {#ad0b01d165e54568f5471186d3bdbfc70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::Target::operator std::string ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/target-h">Target.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/target-cpp">Target.cpp</a>.</p>


<p>References <a href="#aee9dc737c9effa286ef632263cd45696">Arch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a2a0395d53f0485827bc5782c0b64a4e8">llvm::MachO::getArchitectureName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9d8c760e4070b3363f0000b33c567b37">llvm::MachO::getPlatformName</a>, <a href="#af53288d4cf3773021c4dd4aaefc4e861">MinDeployment</a>, <a href="#a508e7395c12db82efde5c42ecf8985cc">Platform</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Arch {#aee9dc737c9effa286ef632263cd45696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Architecture llvm::MachO::Target::Arch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/target-h">Target.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile/#af93c3d5e4065c12400adea999f45dd63">llvm::MachO::InterfaceFile::extract</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a5578664949285327a4d62f8d4433c102">anonymous{TextStubV5.cpp}::getFormattedStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a0c7a01c33f06ce5b51a5037522858155">llvm::MachO::getTargetTripleName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae7b7b478eaa922bb6b4e353e02beb273">llvm::MachO::mapToArchitectureSet</a>, <a href="#ad0b01d165e54568f5471186d3bdbfc70">operator std::string</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile/#a310e207bf104197229a0a5789e294389">llvm::MachO::InterfaceFile::remove</a>, <a href="#a72a74d5ae8a1267c806da8b3a0dc0130">Target</a>, <a href="#ae060502909a83311796c0e2a11ac6153">Target</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/symbol/#a4ae31734e36e7d641b8f0645f18c792f">llvm::MachO::Symbol::targets</a>.</p>

</div>
</div>

### MinDeployment {#af53288d4cf3773021c4dd4aaefc4e861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple llvm::MachO::Target::MinDeployment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/target-h">Target.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a0c7a01c33f06ce5b51a5037522858155">llvm::MachO::getTargetTripleName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a831b4360f0de17f260ef2423128e570c">llvm::MachO::mapToPlatformVersionSet</a>, <a href="#ad0b01d165e54568f5471186d3bdbfc70">operator std::string</a>, <a href="#a72a74d5ae8a1267c806da8b3a0dc0130">Target</a> and <a href="#ae060502909a83311796c0e2a11ac6153">Target</a>.</p>

</div>
</div>

### Platform {#a508e7395c12db82efde5c42ecf8985cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PlatformType llvm::MachO::Target::Platform</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/target-h">Target.h</a>.</p>


<p>Referenced by <a href="#ac60f765fb1e3ea2626663548ace96890">create</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a5578664949285327a4d62f8d4433c102">anonymous{TextStubV5.cpp}::getFormattedStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a0c7a01c33f06ce5b51a5037522858155">llvm::MachO::getTargetTripleName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa63f1bd00437a364087d0441126ec074">llvm::MachO::mapToPlatformSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a831b4360f0de17f260ef2423128e570c">llvm::MachO::mapToPlatformVersionSet</a>, <a href="#ad0b01d165e54568f5471186d3bdbfc70">operator std::string</a>, <a href="#a72a74d5ae8a1267c806da8b3a0dc0130">Target</a> and <a href="#ae060502909a83311796c0e2a11ac6153">Target</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#ac60f765fb1e3ea2626663548ace96890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Target &gt; llvm::MachO::Target::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Target)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/target-h">Target.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/target-cpp">Target.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a10005555774b1ad4d2a65a0904f3c573">llvm::MachO::getArchitectureFromName</a>, <a href="#a508e7395c12db82efde5c42ecf8985cc">Platform</a>, <a href="#a0861396380ac0f34248d539b8f74baa2">Target</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8fb0a43aab6ba906212950167775dbb1">llvm::TargetValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#ae32520c146488ec59560dd75567ba9b0">anonymous{TextStubV5.cpp}::StubParser::getTargets</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#a841ed7fbb14a5ba056989d1e19eef248">anonymous{TextStubV5.cpp}::StubParser::getTargetsSection</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-7951feb4acaca0bea35ca5b72c38a34c/#a838b38d545bef32de151ff5062f9120f">llvm::yaml::ScalarTraits&lt; Target &gt;::input</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/target-h">Target.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/target-cpp">Target.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
