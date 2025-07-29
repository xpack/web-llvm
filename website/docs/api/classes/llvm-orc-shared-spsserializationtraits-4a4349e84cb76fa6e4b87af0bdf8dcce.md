---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-4a4349e84cb76fa6e4b87af0bdf8dcce
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
class llvm::orc::shared::SPSSerializationTraits&lt;SPSELFPerObjectSectionsToRegister, ELFPerObjectSectionsToRegister&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">llvm/ExecutionEngine/Orc/ELFNixPlatform.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ac0088fa183c52618e40e7ab3dca1a7">size</a> (const ELFPerObjectSectionsToRegister &amp;MOPOSR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27a57a0f4e5f35eb2cb6c2fbd24190ce">serialize</a> (SPSOutputBuffer &amp;OB, const ELFPerObjectSectionsToRegister &amp;MOPOSR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad690ce917abf90578acd9e6dfdf7b4d6">deserialize</a> (SPSInputBuffer &amp;IB, ELFPerObjectSectionsToRegister &amp;MOPOSR)</td>
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


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#ad690ce917abf90578acd9e6dfdf7b4d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSELFPerObjectSectionsToRegister, ELFPerObjectSectionsToRegister &gt;::deserialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a> &amp; IB, <a href="/web-llvm/docs/api/structs/llvm/orc/elfperobjectsectionstoregister">ELFPerObjectSectionsToRegister</a> &amp; MOPOSR)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/elfperobjectsectionstoregister/#a38b589e6bd23ea5573fd33788799f314">llvm::orc::ELFPerObjectSectionsToRegister::EHFrameSection</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/elfperobjectsectionstoregister/#a5a43adb119624c1fc2ef1a200a056058">llvm::orc::ELFPerObjectSectionsToRegister::ThreadDataSection</a>.</p>

</div>
</div>

### serialize() {#a27a57a0f4e5f35eb2cb6c2fbd24190ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSELFPerObjectSectionsToRegister, ELFPerObjectSectionsToRegister &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/elfperobjectsectionstoregister">ELFPerObjectSectionsToRegister</a> &amp; MOPOSR)</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/elfperobjectsectionstoregister/#a38b589e6bd23ea5573fd33788799f314">llvm::orc::ELFPerObjectSectionsToRegister::EHFrameSection</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/elfperobjectsectionstoregister/#a5a43adb119624c1fc2ef1a200a056058">llvm::orc::ELFPerObjectSectionsToRegister::ThreadDataSection</a>.</p>

</div>
</div>

### size() {#a2ac0088fa183c52618e40e7ab3dca1a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSELFPerObjectSectionsToRegister, ELFPerObjectSectionsToRegister &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/elfperobjectsectionstoregister">ELFPerObjectSectionsToRegister</a> &amp; MOPOSR)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/elfperobjectsectionstoregister/#a38b589e6bd23ea5573fd33788799f314">llvm::orc::ELFPerObjectSectionsToRegister::EHFrameSection</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/elfperobjectsectionstoregister/#a5a43adb119624c1fc2ef1a200a056058">llvm::orc::ELFPerObjectSectionsToRegister::ThreadDataSection</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
