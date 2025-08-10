---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/selfexecutorprocesscontrol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SelfExecutorProcessControl` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> implementation targeting the current process. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::SelfExecutorProcessControl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">llvm/ExecutionEngine/Orc/ExecutorProcessControl.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemoryaccess">InProcessMemoryAccess</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5005b8f3deda0a47253e985ed2ca3591">SelfExecutorProcessControl</a> (std::shared_ptr&lt; SymbolStringPool &gt; SSP, std::unique_ptr&lt; TaskDispatcher &gt; D, Triple TargetTriple, unsigned PageSize, std::unique_ptr&lt; jitlink::JITLinkMemoryManager &gt; MemMgr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac95e98c378e0095b769073c8f459e21">runAsMain</a> (ExecutorAddr MainFnAddr, ArrayRef&lt; std::string &gt; Args) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run function with a main-like signature. <a href="#aac95e98c378e0095b769073c8f459e21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95d2cbff7443f6cf07d3c3e8f4198b37">runAsVoidFunction</a> (ExecutorAddr VoidFnAddr) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run function with a int (*)(void) signature. <a href="#a95d2cbff7443f6cf07d3c3e8f4198b37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afccfa89bd18bf4723d4176fdcdc700e9">runAsIntFunction</a> (ExecutorAddr IntFnAddr, int Arg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run function with a int (*)(int) signature. <a href="#afccfa89bd18bf4723d4176fdcdc700e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3e5050d43a1deb05a2878c74eb99abd">callWrapperAsync</a> (ExecutorAddr WrapperFnAddr, IncomingWFRHandler OnComplete, ArrayRef&lt; char &gt; ArgBuffer) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function in the executor. <a href="#ab3e5050d43a1deb05a2878c74eb99abd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70b5731dbe77edbd06e480a185fb9c6e">disconnect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disconnect from the target process. <a href="#a70b5731dbe77edbd06e480a185fb9c6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a791ec0843cc10da4c64ae6d79f8381d8">tpctypes::DylibHandle</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d18591fc4eed1d217ebd6e945c4ee09">loadDylib</a> (const char *DylibPath) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load the dynamic library at the given path and return a handle to it. <a href="#a5d18591fc4eed1d217ebd6e945c4ee09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70155269e3697b07e5cb67b50add9b1f">lookupSymbolsAsync</a> (ArrayRef&lt; LookupRequest &gt; Request, SymbolLookupCompleteFn F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for symbols in the target process. <a href="#a70155269e3697b07e5cb67b50add9b1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d6938a72c8468c613099cc6d2284f3">OwnedMemMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cfa96ad49e66a53e6585bf193a641d1">GlobalManglingPrefix</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol">SelfExecutorProcessControl</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae15684412736f37c545f8f2ec65cce56">Create</a> (std::shared_ptr&lt; SymbolStringPool &gt; SSP=nullptr, std::unique_ptr&lt; TaskDispatcher &gt; D=nullptr, std::unique_ptr&lt; jitlink::JITLinkMemoryManager &gt; MemMgr=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol">SelfExecutorProcessControl</a> with the given symbol string pool and memory manager. <a href="#ae15684412736f37c545f8f2ec65cce56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9c9775b3204d92fec5f7eeef8f9b2b5">jitDispatchViaWrapperFunctionManager</a> (void *Ctx, const void *FnTag, const char *Data, size_t Size)</td>
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

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> implementation targeting the current process.</p>

<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SelfExecutorProcessControl() {#a5005b8f3deda0a47253e985ed2ca3591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> &gt; SSP, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a> &gt; D, <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TargetTriple, unsigned PageSize, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &gt; MemMgr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager/#a6cfb7c36eddb6eeab4a0dbece2b7f21c">llvm::orc::UnwindInfoManager::addBootstrapSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2eb4c57e962ea964e0917f7dee774c93">llvm::orc::addDefaultBootstrapValuesForHostProcess</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a74714a7a45a2501fda9da5b5066425b8">llvm::orc::ExecutorProcessControl::BootstrapMap</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a644afbfdc6251cffa535988ec59c259e">llvm::orc::ExecutorProcessControl::BootstrapSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a30812e122ddf831a3226a84f0d5caa40">llvm::orc::ExecutorProcessControl::D</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#ab10c2e8e258477c2c02ce7903e223df0">llvm::orc::ExecutorProcessControl::DylibMgr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#abb438764fe4565ba9704400b74cf38ab">llvm::orc::ExecutorProcessControl::ExecutorProcessControl</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a8adb0ae35f7e95c960c86cfe19bc7215">llvm::orc::ExecutorAddr::fromPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a774becf3d10728695b270703bca011ec">llvm::sys::Process::getPageSizeEstimate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemoryaccess/#a2b8eaa1386313ab62e44088a6ccb6356">llvm::orc::InProcessMemoryAccess::InProcessMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a444e46ff0a17a6c9480eb151bd42c9bc">llvm::Triple::isOSBinFormatMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a408bb953a401290b10daa97f87531a37">llvm::orc::ExecutorProcessControl::JDI</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#ad8710c264afee46f88cd003b98ae8f86">llvm::orc::ExecutorProcessControl::MemAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a86d16d153b1dc4d9d280a7e4ceee8d5e">llvm::orc::ExecutorProcessControl::MemMgr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a887a86a6014e53f51ffede51edae5987">llvm::orc::ExecutorProcessControl::PageSize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a58fe1bcc0c0139d754c0d01cce3b42bf">llvm::orc::ExecutorProcessControl::SSP</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a43e46ade7cdd5c5a944e4e0b436eebcc">llvm::orc::ExecutorProcessControl::TargetTriple</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager/#a51bab61aaf00c3a0395daa426022ada3">llvm::orc::UnwindInfoManager::TryEnable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### callWrapperAsync() {#ab3e5050d43a1deb05a2878c74eb99abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SelfExecutorProcessControl::callWrapperAsync (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/incomingwfrhandler">IncomingWFRHandler</a> OnComplete, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; ArgBuffer)</td>
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


<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a>.</p>

</div>
</div>

### disconnect() {#a70b5731dbe77edbd06e480a185fb9c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::SelfExecutorProcessControl::disconnect ()</td>
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


<p>Declaration at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a30812e122ddf831a3226a84f0d5caa40">llvm::orc::ExecutorProcessControl::D</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### runAsIntFunction() {#afccfa89bd18bf4723d4176fdcdc700e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int32_t &gt; llvm::orc::SelfExecutorProcessControl::runAsIntFunction (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> IntFnAddr, int Arg)</td>
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

<p>Declaration at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a4b98a575435b7792989794e2e617461d">llvm::orc::runAsIntFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a>.</p>

</div>
</div>

### runAsMain() {#aac95e98c378e0095b769073c8f459e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int32_t &gt; llvm::orc::SelfExecutorProcessControl::runAsMain (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> MainFnAddr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt; Args)</td>
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

<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ae96b02ba0679637389c230e9536a40fc">llvm::orc::runAsMain</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a>.</p>

</div>
</div>

### runAsVoidFunction() {#a95d2cbff7443f6cf07d3c3e8f4198b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int32_t &gt; llvm::orc::SelfExecutorProcessControl::runAsVoidFunction (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> VoidFnAddr)</td>
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

<p>Declaration at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a3967432b472134605de76e49e274064b">llvm::orc::runAsVoidFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### loadDylib() {#a5d18591fc4eed1d217ebd6e945c4ee09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; tpctypes::DylibHandle &gt; llvm::orc::SelfExecutorProcessControl::loadDylib (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * DylibPath)</td>
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


<p>Declaration at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>

</div>
</div>

### lookupSymbolsAsync() {#a70155269e3697b07e5cb67b50add9b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SelfExecutorProcessControl::lookupSymbolsAsync (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/dylibmanager/lookuprequest">LookupRequest</a> &gt; Request, <a href="/web-llvm/docs/api/classes/llvm/orc/dylibmanager/#ae71ec09d3b629cd60c40a90681bf09d3">SymbolLookupCompleteFn</a> F)</td>
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


<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GlobalManglingPrefix {#a6cfa96ad49e66a53e6585bf193a641d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::orc::SelfExecutorProcessControl::GlobalManglingPrefix = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>

</div>
</div>

### OwnedMemMgr {#a29d6938a72c8468c613099cc6d2284f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;jitlink::JITLinkMemoryManager&gt; llvm::orc::SelfExecutorProcessControl::OwnedMemMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#ae15684412736f37c545f8f2ec65cce56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; SelfExecutorProcessControl &gt; &gt; llvm::orc::SelfExecutorProcessControl::Create (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> &gt; SSP=nullptr, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a> &gt; D=nullptr, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &gt; MemMgr=nullptr)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol">SelfExecutorProcessControl</a> with the given symbol string pool and memory manager.</p>


<p>If no symbol string pool is given then one will be created. If no memory manager is given a <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager">jitlink::InProcessMemoryManager</a> will be created and used by default.</p>


<p>Declaration at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a30812e122ddf831a3226a84f0d5caa40">llvm::orc::ExecutorProcessControl::D</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a2b6f374dc4eb2a7f84cc346e5630e132">llvm::sys::Process::getPageSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aab375071f641a086c0d7067635ccd3dc">llvm::sys::getProcessTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a86d16d153b1dc4d9d280a7e4ceee8d5e">llvm::orc::ExecutorProcessControl::MemMgr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a887a86a6014e53f51ffede51edae5987">llvm::orc::ExecutorProcessControl::PageSize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a58fe1bcc0c0139d754c0d01cce3b42bf">llvm::orc::ExecutorProcessControl::SSP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a0dd10d6063d14925c308957d2c642fea">llvm::orc::LLJIT::LLJIT</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### jitDispatchViaWrapperFunctionManager() {#aa9c9775b3204d92fec5f7eeef8f9b2b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">shared::CWrapperFunctionResult llvm::orc::SelfExecutorProcessControl::jitDispatchViaWrapperFunctionManager (void * Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * FnTag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Data, size_t Size)</td>
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



<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executorprocesscontrol-cpp">ExecutorProcessControl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
