---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/simpleremoteepc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SimpleRemoteEPC` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::SimpleRemoteEPC { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">llvm/ExecutionEngine/Orc/SimpleRemoteEPC.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> supports interaction with a JIT target process. <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepctransportclient">SimpleRemoteEPCTransportClient</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/dylibmanager">DylibManager</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f60bade0e43fa6464539d0c139e127">PendingCallWrapperResultsMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/incomingwfrhandler">IncomingWFRHandler</a> &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b2cbfc62eb357c72da0f9e18c645042">SimpleRemoteEPC</a> (const SimpleRemoteEPC &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae502362f8f0f307531af6bdee3d0f443">SimpleRemoteEPC</a> (SimpleRemoteEPC &amp;&amp;)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc2b5a826ee89b520e8dccabf2d9499b">SimpleRemoteEPC</a> (std::shared_ptr&lt; SymbolStringPool &gt; SSP, std::unique_ptr&lt; TaskDispatcher &gt; D)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f348cc2f20be9925b6f762a7a14df84">~SimpleRemoteEPC</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a359e785a6b64f374d70fb370ad0934d4">operator=</a> (const SimpleRemoteEPC &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1372961e954f0dad1ec0e4a04dd5220">operator=</a> (SimpleRemoteEPC &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ac93f1af0581195d51da5070d0b2791">runAsMain</a> (ExecutorAddr MainFnAddr, ArrayRef&lt; std::string &gt; Args) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run function with a main-like signature. <a href="#a3ac93f1af0581195d51da5070d0b2791">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2902337e404cc39c82cc2c8bf435c0a">runAsVoidFunction</a> (ExecutorAddr VoidFnAddr) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run function with a int (*)(void) signature. <a href="#ae2902337e404cc39c82cc2c8bf435c0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ac6028d1ca8cb645402b4fafc88452">runAsIntFunction</a> (ExecutorAddr IntFnAddr, int Arg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run function with a int (*)(int) signature. <a href="#af6ac6028d1ca8cb645402b4fafc88452">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21de81dd1759e3d1385c8ed7c0aa472">callWrapperAsync</a> (ExecutorAddr WrapperFnAddr, IncomingWFRHandler OnComplete, ArrayRef&lt; char &gt; ArgBuffer) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function in the executor. <a href="#af21de81dd1759e3d1385c8ed7c0aa472">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4c26bc089f703fd592ca80cdeb9bd3f">disconnect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disconnect from the target process. <a href="#ab4c26bc089f703fd592ca80cdeb9bd3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepctransportclient/#a0cae86f42eaefdba4b602c77afb1e035">HandleMessageAction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f573eb08d6775d4348ae9efd7532f7a">handleMessage</a> (SimpleRemoteEPCOpcode OpC, uint64_t SeqNo, ExecutorAddr TagAddr, SimpleRemoteEPCArgBytesVector ArgBytes) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle receipt of a message. <a href="#a4f573eb08d6775d4348ae9efd7532f7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cbd9c46f77bca6e36af9be20d9ed738">handleDisconnect</a> (Error Err) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle a disconnection from the underlying transport. <a href="#a1cbd9c46f77bca6e36af9be20d9ed738">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a584912754a294f87627fb44d56edc94b">sendMessage</a> (SimpleRemoteEPCOpcode OpC, uint64_t SeqNo, ExecutorAddr TagAddr, ArrayRef&lt; char &gt; ArgBytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4fa44e089a3a007eabf7496057c1c92">handleSetup</a> (uint64_t SeqNo, ExecutorAddr TagAddr, SimpleRemoteEPCArgBytesVector ArgBytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc2b129f7051e01ca44630c2935c6153">setup</a> (Setup S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb6c64a380344599ef865ce564c1a45">handleResult</a> (uint64_t SeqNo, ExecutorAddr TagAddr, SimpleRemoteEPCArgBytesVector ArgBytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2d72766c37a1fe977ff1c6e8ce4f65">handleCallWrapper</a> (uint64_t RemoteSeqNo, ExecutorAddr TagAddr, SimpleRemoteEPCArgBytesVector ArgBytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe4765d6f14d84ee0de9701e343c04d">handleHangup</a> (SimpleRemoteEPCArgBytesVector ArgBytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aada4f1eb4ff075e6e438cd13daf7dea0">getNextSeqNo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a233ef25a2a9adb33fbcdf46685e9ae89">releaseSeqNo</a> (uint64_t SeqNo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a791ec0843cc10da4c64ae6d79f8381d8">tpctypes::DylibHandle</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd23dea682c738a8da0780a1b91f2738">loadDylib</a> (const char *DylibPath) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load the dynamic library at the given path and return a handle to it. <a href="#abd23dea682c738a8da0780a1b91f2738">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11e56da51ed067ea889375b88daecbda">lookupSymbolsAsync</a> (ArrayRef&lt; LookupRequest &gt; Request, SymbolLookupCompleteFn F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for symbols in the target process. <a href="#a11e56da51ed067ea889375b88daecbda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abafcabf7d20c85e00bec0c77cc34562d">SimpleRemoteEPCMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::condition_variable</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf21b9f49a050986f61a58a6126e6ccb">DisconnectCV</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d72df62ca4232485882de9b19698b4b">Disconnected</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e2048a63f4cb8b37134e20e7b4fa87b">DisconnectErr</a> = <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success</a>()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepctransport">SimpleRemoteEPCTransport</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6a6b98d811b81ae84dc6164b358fd6">T</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742f14be9bf19b2050bb5b0742923bc4">OwnedMemMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess">MemoryAccess</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52dd45dfcbb92fb125949415f32c4d30">OwnedMemAccess</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericdylibmanager">EPCGenericDylibManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbae862a35e48711ec9bf3db8088f62b">EPCDylibMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55512723884702646c683095df453c26">RunAsMainAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3673c8660c7f0cf812956fb2fdb6a41">RunAsVoidFunctionAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6475151050aa3d128b28acb19ef1e96">RunAsIntFunctionAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0444451ddc03b46f1bae4af64fa49361">NextSeqNo</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">PendingCallWrapperResultsMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae609f135d8595aa5642fc567828208d4">PendingCallWrapperResults</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename TransportT, typename... TransportTCtorArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4753da41da67751c4d4a706a90eeeeec">Create</a> (std::unique_ptr&lt; TaskDispatcher &gt; D, Setup S, TransportTCtorArgTs &amp;&amp;...TransportTCtorArgs) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> using the given transport type and args. <a href="#a4753da41da67751c4d4a706a90eeeeec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3e9633f1849f0a3f49676a2659922b4">createDefaultMemoryManager</a> (SimpleRemoteEPC &amp;SREPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess">MemoryAccess</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a103b7f0a669896a935f8305884ec7dd4">createDefaultMemoryAccess</a> (SimpleRemoteEPC &amp;SREPC)</td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### PendingCallWrapperResultsMap {#ac2f60bade0e43fa6464539d0c139e127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::SimpleRemoteEPC::PendingCallWrapperResultsMap = 
    DenseMap&lt;uint64_t, IncomingWFRHandler&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SimpleRemoteEPC() {#a8b2cbfc62eb357c72da0f9e18c645042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SimpleRemoteEPC::SimpleRemoteEPC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>


<p>Reference <a href="#a8b2cbfc62eb357c72da0f9e18c645042">SimpleRemoteEPC</a>.</p>


<p>Referenced by <a href="#a4753da41da67751c4d4a706a90eeeeec">Create</a>, <a href="#a359e785a6b64f374d70fb370ad0934d4">operator=</a>, <a href="#af1372961e954f0dad1ec0e4a04dd5220">operator=</a>, <a href="#a8b2cbfc62eb357c72da0f9e18c645042">SimpleRemoteEPC</a> and <a href="#ae502362f8f0f307531af6bdee3d0f443">SimpleRemoteEPC</a>.</p>

</div>
</div>

### SimpleRemoteEPC() {#ae502362f8f0f307531af6bdee3d0f443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SimpleRemoteEPC::SimpleRemoteEPC (<a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>


<p>Reference <a href="#a8b2cbfc62eb357c72da0f9e18c645042">SimpleRemoteEPC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### SimpleRemoteEPC() {#acc2b5a826ee89b520e8dccabf2d9499b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SimpleRemoteEPC::SimpleRemoteEPC (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> &gt; SSP, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a> &gt; D)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SimpleRemoteEPC() {#a3f348cc2f20be9925b6f762a7a14df84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SimpleRemoteEPC::~SimpleRemoteEPC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a359e785a6b64f374d70fb370ad0934d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimpleRemoteEPC &amp; llvm::orc::SimpleRemoteEPC::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>


<p>Reference <a href="#a8b2cbfc62eb357c72da0f9e18c645042">SimpleRemoteEPC</a>.</p>

</div>
</div>

### operator=() {#af1372961e954f0dad1ec0e4a04dd5220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimpleRemoteEPC &amp; llvm::orc::SimpleRemoteEPC::operator= (<a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a30812e122ddf831a3226a84f0d5caa40">llvm::orc::ExecutorProcessControl::D</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#ab10c2e8e258477c2c02ce7903e223df0">llvm::orc::ExecutorProcessControl::DylibMgr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#abb438764fe4565ba9704400b74cf38ab">llvm::orc::ExecutorProcessControl::ExecutorProcessControl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a8b2cbfc62eb357c72da0f9e18c645042">SimpleRemoteEPC</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a58fe1bcc0c0139d754c0d01cce3b42bf">llvm::orc::ExecutorProcessControl::SSP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### callWrapperAsync() {#af21de81dd1759e3d1385c8ed7c0aa472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SimpleRemoteEPC::callWrapperAsync (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/incomingwfrhandler">IncomingWFRHandler</a> OnComplete, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; ArgBuffer)</td>
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

<p>Run a wrapper function in the executor.</p>


<p>The given WFRHandler will be called on the result when it is returned.</p>


<p>The wrapper function should be callable as:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">CWrapperFunctionResult fn(uint8_t *<a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">Data</a>, uint64_t <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>);</span></span></div>

</div>


<p>{.cpp}</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a0fe959195d2bfd3ccc5cd9c358c4b561">llvm::orc::CallWrapper</a>, <a href="#af21de81dd1759e3d1385c8ed7c0aa472">callWrapperAsync</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult/#ae0a341aa5651a0e6b296119ad73cdef5">llvm::orc::shared::WrapperFunctionResult::createOutOfBandError</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#ab3631f9109f6d1422c68b7628c0a0573">llvm::orc::ExecutorProcessControl::getExecutionSession</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#af21de81dd1759e3d1385c8ed7c0aa472">callWrapperAsync</a>.</p>

</div>
</div>

### disconnect() {#ab4c26bc089f703fd592ca80cdeb9bd3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::SimpleRemoteEPC::disconnect ()</td>
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

<p>Disconnect from the target process.</p>


<p>This should be called after the JIT session is shut down.</p>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a30812e122ddf831a3226a84f0d5caa40">llvm::orc::ExecutorProcessControl::D</a> and <a href="#ab4c26bc089f703fd592ca80cdeb9bd3f">disconnect</a>.</p>


<p>Referenced by <a href="#ab4c26bc089f703fd592ca80cdeb9bd3f">disconnect</a>.</p>

</div>
</div>

### handleDisconnect() {#a1cbd9c46f77bca6e36af9be20d9ed738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SimpleRemoteEPC::handleDisconnect (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
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

<p>Handle a disconnection from the underlying transport.</p>


<p>No further messages should be sent to handleMessage after this is called. Err may contain an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> value indicating unexpected disconnection. This allows clients to log such errors, but no attempt should be made at recovery (which should be handled inside the transport class, if it is supported at all).</p>


<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult/#ae0a341aa5651a0e6b296119ad73cdef5">llvm::orc::shared::WrapperFunctionResult::createOutOfBandError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a1cbd9c46f77bca6e36af9be20d9ed738">handleDisconnect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a1cbd9c46f77bca6e36af9be20d9ed738">handleDisconnect</a>.</p>

</div>
</div>

### handleMessage() {#a4f573eb08d6775d4348ae9efd7532f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SimpleRemoteEPCTransportClient::HandleMessageAction &gt; llvm::orc::SimpleRemoteEPC::handleMessage (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47">SimpleRemoteEPCOpcode</a> OpC, uint64_t SeqNo, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> TagAddr, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7b57ebab4d32c81530df07ac39a3b0ca">SimpleRemoteEPCArgBytesVector</a> ArgBytes)</td>
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

<p>Handle receipt of a message.</p>


<p>Returns an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> if the message cannot be handled, 'EndSession' if the client will not accept any further messages, and 'ContinueSession' otherwise.</p>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a0fe959195d2bfd3ccc5cd9c358c4b561">llvm::orc::CallWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepctransportclient/#a0cae86f42eaefdba4b602c77afb1e035a5e8b6f0100b3a1ab9b994fc190a1b14d">llvm::orc::SimpleRemoteEPCTransportClient::ContinueSession</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepctransportclient/#a0cae86f42eaefdba4b602c77afb1e035abd48e7a3495d02791216dca8b8ad1837">llvm::orc::SimpleRemoteEPCTransportClient::EndSession</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#a4f573eb08d6775d4348ae9efd7532f7a">handleMessage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a77bd384c19f071f8d0579398b90df0b6">llvm::orc::Hangup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47ac1412e64d00512f6facfacd333f8c2b3">llvm::orc::LastOpC</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47aad2376beebecdcf7846ba973fa1a005b">llvm::orc::Setup</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a4f573eb08d6775d4348ae9efd7532f7a">handleMessage</a>.</p>

</div>
</div>

### runAsIntFunction() {#af6ac6028d1ca8cb645402b4fafc88452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int32_t &gt; llvm::orc::SimpleRemoteEPC::runAsIntFunction (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> IntFnAddr, int Arg)</td>
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

<p>Run function with a int (*)(int) signature.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a955b3e2910b75b483c867cf4e79bb78e">llvm::orc::ExecutorProcessControl::callSPSWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a> and <a href="#af6ac6028d1ca8cb645402b4fafc88452">runAsIntFunction</a>.</p>


<p>Referenced by <a href="#af6ac6028d1ca8cb645402b4fafc88452">runAsIntFunction</a>.</p>

</div>
</div>

### runAsMain() {#a3ac93f1af0581195d51da5070d0b2791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int32_t &gt; llvm::orc::SimpleRemoteEPC::runAsMain (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> MainFnAddr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt; Args)</td>
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

<p>Run function with a main-like signature.</p>

<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a955b3e2910b75b483c867cf4e79bb78e">llvm::orc::ExecutorProcessControl::callSPSWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a> and <a href="#a3ac93f1af0581195d51da5070d0b2791">runAsMain</a>.</p>


<p>Referenced by <a href="#a3ac93f1af0581195d51da5070d0b2791">runAsMain</a>.</p>

</div>
</div>

### runAsVoidFunction() {#ae2902337e404cc39c82cc2c8bf435c0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int32_t &gt; llvm::orc::SimpleRemoteEPC::runAsVoidFunction (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> VoidFnAddr)</td>
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

<p>Run function with a int (*)(void) signature.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a955b3e2910b75b483c867cf4e79bb78e">llvm::orc::ExecutorProcessControl::callSPSWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a> and <a href="#ae2902337e404cc39c82cc2c8bf435c0a">runAsVoidFunction</a>.</p>


<p>Referenced by <a href="#ae2902337e404cc39c82cc2c8bf435c0a">runAsVoidFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getNextSeqNo() {#aada4f1eb4ff075e6e438cd13daf7dea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::SimpleRemoteEPC::getNextSeqNo ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### handleCallWrapper() {#a5d2d72766c37a1fe977ff1c6e8ce4f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SimpleRemoteEPC::handleCallWrapper (uint64_t RemoteSeqNo, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> TagAddr, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7b57ebab4d32c81530df07ac39a3b0ca">SimpleRemoteEPCArgBytesVector</a> ArgBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>

</div>
</div>

### handleHangup() {#a7fe4765d6f14d84ee0de9701e343c04d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::SimpleRemoteEPC::handleHangup (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7b57ebab4d32c81530df07ac39a3b0ca">SimpleRemoteEPCArgBytesVector</a> ArgBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>

</div>
</div>

### handleResult() {#a2bb6c64a380344599ef865ce564c1a45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::SimpleRemoteEPC::handleResult (uint64_t SeqNo, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> TagAddr, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7b57ebab4d32c81530df07ac39a3b0ca">SimpleRemoteEPCArgBytesVector</a> ArgBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>

</div>
</div>

### handleSetup() {#ad4fa44e089a3a007eabf7496057c1c92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::SimpleRemoteEPC::handleSetup (uint64_t SeqNo, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> TagAddr, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7b57ebab4d32c81530df07ac39a3b0ca">SimpleRemoteEPCArgBytesVector</a> ArgBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>

</div>
</div>

### loadDylib() {#abd23dea682c738a8da0780a1b91f2738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; tpctypes::DylibHandle &gt; llvm::orc::SimpleRemoteEPC::loadDylib (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * DylibPath)</td>
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

<p>Load the dynamic library at the given path and return a handle to it.</p>


<p>If LibraryPath is null this function will return the global handle for the target process.</p>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>

</div>
</div>

### lookupSymbolsAsync() {#a11e56da51ed067ea889375b88daecbda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SimpleRemoteEPC::lookupSymbolsAsync (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/dylibmanager/lookuprequest">LookupRequest</a> &gt; Request, <a href="/web-llvm/docs/api/classes/llvm/orc/dylibmanager/#ae71ec09d3b629cd60c40a90681bf09d3">SymbolLookupCompleteFn</a> F)</td>
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

<p>Search for symbols in the target process.</p>


<p>The result of the lookup is a 2-dimensional array of target addresses that correspond to the lookup order. If a required symbol is not found then this method will return an error. If a weakly referenced symbol is not found then it be assigned a '0' value.</p>


<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>

</div>
</div>

### releaseSeqNo() {#a233ef25a2a9adb33fbcdf46685e9ae89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SimpleRemoteEPC::releaseSeqNo (uint64_t SeqNo)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### sendMessage() {#a584912754a294f87627fb44d56edc94b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::SimpleRemoteEPC::sendMessage (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47">SimpleRemoteEPCOpcode</a> OpC, uint64_t SeqNo, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> TagAddr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; ArgBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>

</div>
</div>

### setup() {#adc2b129f7051e01ca44630c2935c6153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::SimpleRemoteEPC::setup (<a href="/web-llvm/docs/api/structs/llvm/orc/simpleremoteepc/setup">Setup</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DisconnectCV {#acf21b9f49a050986f61a58a6126e6ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::condition_variable llvm::orc::SimpleRemoteEPC::DisconnectCV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### Disconnected {#a4d72df62ca4232485882de9b19698b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::SimpleRemoteEPC::Disconnected = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### DisconnectErr {#a6e2048a63f4cb8b37134e20e7b4fa87b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::SimpleRemoteEPC::DisconnectErr = <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### EPCDylibMgr {#acbae862a35e48711ec9bf3db8088f62b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;EPCGenericDylibManager&gt; llvm::orc::SimpleRemoteEPC::EPCDylibMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### NextSeqNo {#a0444451ddc03b46f1bae4af64fa49361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::SimpleRemoteEPC::NextSeqNo = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### OwnedMemAccess {#a52dd45dfcbb92fb125949415f32c4d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryAccess&gt; llvm::orc::SimpleRemoteEPC::OwnedMemAccess</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### OwnedMemMgr {#a742f14be9bf19b2050bb5b0742923bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;jitlink::JITLinkMemoryManager&gt; llvm::orc::SimpleRemoteEPC::OwnedMemMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### PendingCallWrapperResults {#ae609f135d8595aa5642fc567828208d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PendingCallWrapperResultsMap llvm::orc::SimpleRemoteEPC::PendingCallWrapperResults</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### RunAsIntFunctionAddr {#ab6475151050aa3d128b28acb19ef1e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::SimpleRemoteEPC::RunAsIntFunctionAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### RunAsMainAddr {#a55512723884702646c683095df453c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::SimpleRemoteEPC::RunAsMainAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### RunAsVoidFunctionAddr {#af3673c8660c7f0cf812956fb2fdb6a41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::SimpleRemoteEPC::RunAsVoidFunctionAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### SimpleRemoteEPCMutex {#abafcabf7d20c85e00bec0c77cc34562d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::SimpleRemoteEPC::SimpleRemoteEPCMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### T {#a7d6a6b98d811b81ae84dc6164b358fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SimpleRemoteEPCTransport&gt; llvm::orc::SimpleRemoteEPC::T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#a4753da41da67751c4d4a706a90eeeeec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename TransportT, typename... TransportTCtorArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; SimpleRemoteEPC &gt; &gt; llvm::orc::SimpleRemoteEPC::Create (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a> &gt; D, <a href="/web-llvm/docs/api/structs/llvm/orc/simpleremoteepc/setup">Setup</a> S, TransportTCtorArgTs &amp;&amp;... TransportTCtorArgs)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> using the given transport type and args.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a30812e122ddf831a3226a84f0d5caa40">llvm::orc::ExecutorProcessControl::D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a> and <a href="#a8b2cbfc62eb357c72da0f9e18c645042">SimpleRemoteEPC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### createDefaultMemoryAccess() {#a103b7f0a669896a935f8305884ec7dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ExecutorProcessControl::MemoryAccess &gt; &gt; llvm::orc::SimpleRemoteEPC::createDefaultMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> &amp; SREPC)</td>
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



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>

</div>
</div>

### createDefaultMemoryManager() {#ae3e9633f1849f0a3f49676a2659922b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; jitlink::JITLinkMemoryManager &gt; &gt; llvm::orc::SimpleRemoteEPC::createDefaultMemoryManager (<a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> &amp; SREPC)</td>
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



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/simpleremoteepc-cpp">SimpleRemoteEPC.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
