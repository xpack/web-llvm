---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-c4c9d06010351644bf0ec9c5d491d476
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SPSSerializationTraits` Class Template Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::shared::SPSSerializationTraits&lt;SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">llvm/ExecutionEngine/Orc/Shared/TargetProcessControlTypes.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc7a91bd2ad243a8ced4516a989d2e4">SFRAL</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple/#a4ac958780d60988306a818239d07657c">SPSSharedMemorySegFinalizeRequest::AsArgList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a902bb30f743033e6dd8f526e98718e3f">size</a> (const tpctypes::SharedMemorySegFinalizeRequest &amp;SFR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81036c9028f35e0288e852a8728a2819">serialize</a> (SPSOutputBuffer &amp;OB, const tpctypes::SharedMemorySegFinalizeRequest &amp;SFR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ac62a1372408f79dd7e686eeb99729">deserialize</a> (SPSInputBuffer &amp;IB, tpctypes::SharedMemorySegFinalizeRequest &amp;SFR)</td>
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


<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### SFRAL {#a7dc7a91bd2ad243a8ced4516a989d2e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::SFRAL =  SPSSharedMemorySegFinalizeRequest::AsArgList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#a52ac62a1372408f79dd7e686eeb99729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::deserialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a> &amp; IB, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest">tpctypes::SharedMemorySegFinalizeRequest</a> &amp; SFR)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#a291bd7c0717557dd244547b23c8c7c41">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#af8722c220368ae6ec29f1659a9db656d">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::RAG</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#a285451feed03fc082fba2259ac6f1f2d">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::Size</a>.</p>

</div>
</div>

### serialize() {#a81036c9028f35e0288e852a8728a2819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest">tpctypes::SharedMemorySegFinalizeRequest</a> &amp; SFR)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#a291bd7c0717557dd244547b23c8c7c41">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#af8722c220368ae6ec29f1659a9db656d">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::RAG</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#a285451feed03fc082fba2259ac6f1f2d">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::Size</a>.</p>

</div>
</div>

### size() {#a902bb30f743033e6dd8f526e98718e3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest">tpctypes::SharedMemorySegFinalizeRequest</a> &amp; SFR)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#a291bd7c0717557dd244547b23c8c7c41">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#af8722c220368ae6ec29f1659a9db656d">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::RAG</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest/#a285451feed03fc082fba2259ac6f1f2d">llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::Size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
