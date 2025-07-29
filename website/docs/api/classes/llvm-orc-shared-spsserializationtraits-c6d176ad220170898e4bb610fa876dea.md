---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-c6d176ad220170898e4bb610fa876dea
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SPSSerializationTraits` Class Template



## Declaration

<div class="doxyDeclaration">
class llvm::orc::shared::SPSSerializationTraits&lt;SPSMachOJITDylibDepInfo, MachOPlatform::MachOJITDylibDepInfo&gt; { ... }
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d0ec6d2d16f157a70e89b9ed7caaf4">size</a> (const MachOPlatform::MachOJITDylibDepInfo &amp;DDI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07ab5c0b65a381983d21ff6567bd217f">serialize</a> (SPSOutputBuffer &amp;OB, const MachOPlatform::MachOJITDylibDepInfo &amp;DDI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa591638ab9fae696ba212c5d0f44016">deserialize</a> (SPSInputBuffer &amp;IB, MachOPlatform::MachOJITDylibDepInfo &amp;DDI)</td>
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


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#aaa591638ab9fae696ba212c5d0f44016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSMachOJITDylibDepInfo, MachOPlatform::MachOJITDylibDepInfo &gt;::deserialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a> &amp; IB, <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/machojitdylibdepinfo">MachOPlatform::MachOJITDylibDepInfo</a> &amp; DDI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/machojitdylibdepinfo/#affb3c81497df3f5a7fa7e4e25fc23bf5">llvm::orc::MachOPlatform::MachOJITDylibDepInfo::DepHeaders</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/machojitdylibdepinfo/#a7df77398f07c9458bb12c34aaabffa77">llvm::orc::MachOPlatform::MachOJITDylibDepInfo::Sealed</a>.</p>

</div>
</div>

### serialize() {#a07ab5c0b65a381983d21ff6567bd217f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSMachOJITDylibDepInfo, MachOPlatform::MachOJITDylibDepInfo &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/machojitdylibdepinfo">MachOPlatform::MachOJITDylibDepInfo</a> &amp; DDI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/machojitdylibdepinfo/#affb3c81497df3f5a7fa7e4e25fc23bf5">llvm::orc::MachOPlatform::MachOJITDylibDepInfo::DepHeaders</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/machojitdylibdepinfo/#a7df77398f07c9458bb12c34aaabffa77">llvm::orc::MachOPlatform::MachOJITDylibDepInfo::Sealed</a>.</p>

</div>
</div>

### size() {#a16d0ec6d2d16f157a70e89b9ed7caaf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSMachOJITDylibDepInfo, MachOPlatform::MachOJITDylibDepInfo &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/machojitdylibdepinfo">MachOPlatform::MachOJITDylibDepInfo</a> &amp; DDI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/machojitdylibdepinfo/#affb3c81497df3f5a7fa7e4e25fc23bf5">llvm::orc::MachOPlatform::MachOJITDylibDepInfo::DepHeaders</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/machojitdylibdepinfo/#a7df77398f07c9458bb12c34aaabffa77">llvm::orc::MachOPlatform::MachOJITDylibDepInfo::Sealed</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
