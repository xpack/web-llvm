---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/simpleremoteepctransportclient
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SimpleRemoteEPCTransportClient` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::SimpleRemoteEPCTransportClient { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">llvm/ExecutionEngine/Orc/Shared/SimpleRemoteEPCUtils.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepcserver">SimpleRemoteEPCServer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A simple EPC server implementation. <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepcserver/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">HandleMessageAction { <a href="#a0cae86f42eaefdba4b602c77afb1e035">...</a> }</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6c8e45cc780da3a5e5045424b4eaf5">~SimpleRemoteEPCTransportClient</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#a0cae86f42eaefdba4b602c77afb1e035">HandleMessageAction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756770283ea204755873a23eb1324f69">handleMessage</a> (SimpleRemoteEPCOpcode OpC, uint64_t SeqNo, ExecutorAddr TagAddr, SimpleRemoteEPCArgBytesVector ArgBytes)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle receipt of a message. <a href="#a756770283ea204755873a23eb1324f69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8477fb0a7c21a1860bd529ebbb3b09ea">handleDisconnect</a> (Error Err)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle a disconnection from the underlying transport. <a href="#a8477fb0a7c21a1860bd529ebbb3b09ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### HandleMessageAction {#a0cae86f42eaefdba4b602c77afb1e035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::orc::SimpleRemoteEPCTransportClient::HandleMessageAction </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ContinueSession<a id="a0cae86f42eaefdba4b602c77afb1e035a5e8b6f0100b3a1ab9b994fc190a1b14d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndSession<a id="a0cae86f42eaefdba4b602c77afb1e035abd48e7a3495d02791216dca8b8ad1837"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SimpleRemoteEPCTransportClient() {#abe6c8e45cc780da3a5e5045424b4eaf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SimpleRemoteEPCTransportClient::~SimpleRemoteEPCTransportClient ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### handleDisconnect() {#a8477fb0a7c21a1860bd529ebbb3b09ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::orc::SimpleRemoteEPCTransportClient::handleDisconnect (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle a disconnection from the underlying transport.</p>


<p>No further messages should be sent to handleMessage after this is called. Err may contain an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> value indicating unexpected disconnection. This allows clients to log such errors, but no attempt should be made at recovery (which should be handled inside the transport class, if it is supported at all).</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a>.</p>

</div>
</div>

### handleMessage() {#a756770283ea204755873a23eb1324f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; HandleMessageAction &gt; llvm::orc::SimpleRemoteEPCTransportClient::handleMessage (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47">SimpleRemoteEPCOpcode</a> OpC, uint64_t SeqNo, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> TagAddr, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7b57ebab4d32c81530df07ac39a3b0ca">SimpleRemoteEPCArgBytesVector</a> ArgBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle receipt of a message.</p>


<p>Returns an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> if the message cannot be handled, 'EndSession' if the client will not accept any further messages, and 'ContinueSession' otherwise.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
