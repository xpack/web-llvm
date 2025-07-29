---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/detail/wrapperfunctionhandlerhelper-7c3af4493e13c390f8fe71bfe3aa2569
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WrapperFunctionHandlerHelper` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename RetT, typename... ArgTs, template&lt; typename &gt; class ResultSerializer, typename... SPSTagTs&gt;
class llvm::orc::shared::detail::WrapperFunctionHandlerHelper&lt;RetT(ArgTs...), ResultSerializer, SPSTagTs...&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">llvm/ExecutionEngine/Orc/Shared/WrapperFunctionUtils.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/detail/wrapperfunctionhandlerhelper-f451fc7537a691bd25ddab4c2ea4d1ad">WrapperFunctionHandlerHelper&lt;RetT(*)(ArgTs...), ResultSerializer, SPSTagTs...&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/detail/wrapperfunctionhandlerhelper-b5f79378f3af1dc0c3946def18cf5bb1">WrapperFunctionHandlerHelper&lt;RetT(ClassT::*)(ArgTs...) const, ResultSerializer, SPSTagTs...&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/detail/wrapperfunctionhandlerhelper-d0a0d87aaeae4d79538f40ec220fcd95">WrapperFunctionHandlerHelper&lt;RetT(ClassT::*)(ArgTs...), ResultSerializer, SPSTagTs...&gt;</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c58d179373d0298a5a2867f64269f90">ArgTuple</a> = std::tuple&lt; std::decay_t&lt; ArgTs &gt;... &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af527977bda94a87063b3864a6c5c0813">ArgIndices</a> = std::make_index_sequence&lt; std::tuple_size&lt; <a href="#a3c58d179373d0298a5a2867f64269f90">ArgTuple</a> &gt;::value &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HandlerT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult">WrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a19c8925a4743ab7ae90d500b47989e19">apply</a> (HandlerT &amp;&amp;H, const char *ArgData, size_t ArgSize)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;std::size_t... I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae429fa66518a5b6f04dc86f89df89b6a">deserialize</a> (const char *ArgData, size_t ArgSize, ArgTuple &amp;Args, std::index_sequence&lt; I... &gt;)</td>
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


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ArgIndices {#af527977bda94a87063b3864a6c5c0813}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RetT, typename... ArgTs, template&lt; typename &gt; class ResultSerializer, typename... SPSTagTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::detail::WrapperFunctionHandlerHelper&lt; RetT(ArgTs...), ResultSerializer, SPSTagTs... &gt;::ArgIndices =  std::make_index_sequence&lt;std::tuple_size&lt;ArgTuple&gt;::value&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

### ArgTuple {#a3c58d179373d0298a5a2867f64269f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RetT, typename... ArgTs, template&lt; typename &gt; class ResultSerializer, typename... SPSTagTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::detail::WrapperFunctionHandlerHelper&lt; RetT(ArgTs...), ResultSerializer, SPSTagTs... &gt;::ArgTuple =  std::tuple&lt;std::decay_t&lt;ArgTs&gt;...&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### apply() {#a19c8925a4743ab7ae90d500b47989e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HandlerT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WrapperFunctionResult llvm::orc::shared::detail::WrapperFunctionHandlerHelper&lt; RetT(ArgTs...), ResultSerializer, SPSTagTs... &gt;::apply (HandlerT &amp;&amp; H, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ArgData, size_t ArgSize)</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/shared/detail/wrapperfunctionhandlercaller/#ab34d255b527b4fa3c3c7b56ecedf1943">llvm::orc::shared::detail::WrapperFunctionHandlerCaller&lt; RetT &gt;::call</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult/#ae0a341aa5651a0e6b296119ad73cdef5">llvm::orc::shared::WrapperFunctionResult::createOutOfBandError</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### deserialize() {#ae429fa66518a5b6f04dc86f89df89b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;std::size_t... I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::detail::WrapperFunctionHandlerHelper&lt; RetT(ArgTs...), ResultSerializer, SPSTagTs... &gt;::deserialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ArgData, size_t ArgSize, <a href="#a3c58d179373d0298a5a2867f64269f90">ArgTuple</a> &amp; Args, std::index_sequence&lt; I... &gt;)</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
