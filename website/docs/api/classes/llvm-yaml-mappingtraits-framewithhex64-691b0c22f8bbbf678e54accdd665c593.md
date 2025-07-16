---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/yaml/mappingtraits/framewithhex64-691b0c22f8bbbf678e54accdd665c593
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FrameWithHex64` Class Template Reference



## Declaration

<div class="doxyDeclaration">
class llvm::yaml::MappingTraits::FrameWithHex64&lt;memprof::Frame &gt;::FrameWithHex64 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">llvm/ProfileData/MemProfYAML.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca45c081ca47fc1ef7a562f0cf9d917">FrameWithHex64</a> (IO &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abffe70a90a3ce9e814ec5c78c99e2de2">FrameWithHex64</a> (IO &amp;, const memprof::Frame &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/memprof/frame">memprof::Frame</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe4c7e84aef1d8032cd3963951c69545">denormalize</a> (IO &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">memprof::GUIDHex64</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a0729056594e1f74d7efb591a790736">Function</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">decltype(memprof::Frame::LineOffset)</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b225bd55c0fb997b2a0af460334242a">LineOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">decltype(memprof::Frame::Column)</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f8afafcbc1134c87bdfe93a0451657">Column</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">decltype(memprof::Frame::IsInlineFrame)</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e6d4c79761c044ed60bbfabc9a6bef">IsInlineFrame</a> = false</td>
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


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FrameWithHex64() {#a9ca45c081ca47fc1ef7a562f0cf9d917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::MappingTraits&lt; memprof::Frame &gt;::FrameWithHex64::FrameWithHex64 (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp;)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>

</div>
</div>

### FrameWithHex64() {#abffe70a90a3ce9e814ec5c78c99e2de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::MappingTraits&lt; memprof::Frame &gt;::FrameWithHex64::FrameWithHex64 (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/frame">memprof::Frame</a> &amp; F)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>


<p>References <a href="#ab5f8afafcbc1134c87bdfe93a0451657">Column</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a9a0729056594e1f74d7efb591a790736">Function</a>, <a href="#a72e6d4c79761c044ed60bbfabc9a6bef">IsInlineFrame</a> and <a href="#a2b225bd55c0fb997b2a0af460334242a">LineOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### denormalize() {#afe4c7e84aef1d8032cd3963951c69545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">memprof::Frame llvm::yaml::MappingTraits&lt; memprof::Frame &gt;::FrameWithHex64::denormalize (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp;)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>


<p>References <a href="#ab5f8afafcbc1134c87bdfe93a0451657">Column</a>, <a href="#a9a0729056594e1f74d7efb591a790736">Function</a>, <a href="#a72e6d4c79761c044ed60bbfabc9a6bef">IsInlineFrame</a> and <a href="#a2b225bd55c0fb997b2a0af460334242a">LineOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Column {#ab5f8afafcbc1134c87bdfe93a0451657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">decltype(memprof::Frame::Column) llvm::yaml::MappingTraits&lt; memprof::Frame &gt;::FrameWithHex64::Column = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>


<p>Referenced by <a href="#afe4c7e84aef1d8032cd3963951c69545">denormalize</a> and <a href="#abffe70a90a3ce9e814ec5c78c99e2de2">FrameWithHex64</a>.</p>

</div>
</div>

### Function {#a9a0729056594e1f74d7efb591a790736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">memprof::GUIDHex64 llvm::yaml::MappingTraits&lt; memprof::Frame &gt;::FrameWithHex64::Function = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>


<p>Referenced by <a href="#afe4c7e84aef1d8032cd3963951c69545">denormalize</a> and <a href="#abffe70a90a3ce9e814ec5c78c99e2de2">FrameWithHex64</a>.</p>

</div>
</div>

### IsInlineFrame {#a72e6d4c79761c044ed60bbfabc9a6bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">decltype(memprof::Frame::IsInlineFrame) llvm::yaml::MappingTraits&lt; memprof::Frame &gt;::FrameWithHex64::IsInlineFrame = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>


<p>Referenced by <a href="#afe4c7e84aef1d8032cd3963951c69545">denormalize</a> and <a href="#abffe70a90a3ce9e814ec5c78c99e2de2">FrameWithHex64</a>.</p>

</div>
</div>

### LineOffset {#a2b225bd55c0fb997b2a0af460334242a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">decltype(memprof::Frame::LineOffset) llvm::yaml::MappingTraits&lt; memprof::Frame &gt;::FrameWithHex64::LineOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>


<p>Referenced by <a href="#afe4c7e84aef1d8032cd3963951c69545">denormalize</a> and <a href="#abffe70a90a3ce9e814ec5c78c99e2de2">FrameWithHex64</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
