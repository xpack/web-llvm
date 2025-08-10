---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/machoplatform/machojitdylibdepinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MachOJITDylibDepInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::MachOPlatform::MachOJITDylibDepInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">llvm/ExecutionEngine/Orc/MachOPlatform.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df77398f07c9458bb12c34aaabffa77">Sealed</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affb3c81497df3f5a7fa7e4e25fc23bf5">DepHeaders</a></td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### DepHeaders {#affb3c81497df3f5a7fa7e4e25fc23bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ExecutorAddr&gt; llvm::orc::MachOPlatform::MachOJITDylibDepInfo::DepHeaders</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c6d176ad220170898e4bb610fa876dea/#aaa591638ab9fae696ba212c5d0f44016">llvm::orc::shared::SPSSerializationTraits&lt; SPSMachOJITDylibDepInfo, MachOPlatform::MachOJITDylibDepInfo &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c6d176ad220170898e4bb610fa876dea/#a07ab5c0b65a381983d21ff6567bd217f">llvm::orc::shared::SPSSerializationTraits&lt; SPSMachOJITDylibDepInfo, MachOPlatform::MachOJITDylibDepInfo &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c6d176ad220170898e4bb610fa876dea/#a16d0ec6d2d16f157a70e89b9ed7caaf4">llvm::orc::shared::SPSSerializationTraits&lt; SPSMachOJITDylibDepInfo, MachOPlatform::MachOJITDylibDepInfo &gt;::size</a>.</p>

</div>
</div>

### Sealed {#a7df77398f07c9458bb12c34aaabffa77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::MachOPlatform::MachOJITDylibDepInfo::Sealed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c6d176ad220170898e4bb610fa876dea/#aaa591638ab9fae696ba212c5d0f44016">llvm::orc::shared::SPSSerializationTraits&lt; SPSMachOJITDylibDepInfo, MachOPlatform::MachOJITDylibDepInfo &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c6d176ad220170898e4bb610fa876dea/#a07ab5c0b65a381983d21ff6567bd217f">llvm::orc::shared::SPSSerializationTraits&lt; SPSMachOJITDylibDepInfo, MachOPlatform::MachOJITDylibDepInfo &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c6d176ad220170898e4bb610fa876dea/#a16d0ec6d2d16f157a70e89b9ed7caaf4">llvm::orc::shared::SPSSerializationTraits&lt; SPSMachOJITDylibDepInfo, MachOPlatform::MachOJITDylibDepInfo &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
