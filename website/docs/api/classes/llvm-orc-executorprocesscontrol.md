---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/executorprocesscontrol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ExecutorProcessControl` Class

<p><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> supports interaction with a JIT target process. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ExecutorProcessControl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">llvm/ExecutionEngine/Orc/ExecutorProcessControl.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol">SelfExecutorProcessControl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> implementation targeting the current process. <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol">UnsupportedExecutorProcessControl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> instance that asserts if any of its methods are used. <a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb438764fe4565ba9704400b74cf38ab">ExecutorProcessControl</a> (std::shared_ptr&lt; SymbolStringPool &gt; SSP, std::unique_ptr&lt; TaskDispatcher &gt; D)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe55d7fe25145ade3cd207703bd28b3">~ExecutorProcessControl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3631f9109f6d1422c68b7628c0a0573">getExecutionSession</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> associated with this instance. <a href="#ab3631f9109f6d1422c68b7628c0a0573">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6461773648a1bc1717ce65bf3247e909">intern</a> (StringRef SymName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Intern a symbol name in the <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a>. <a href="#a6461773648a1bc1717ce65bf3247e909">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e1dd9778ba22121cbf5d9f69597377">getSymbolStringPool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a shared pointer to the <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> for this instance. <a href="#a75e1dd9778ba22121cbf5d9f69597377">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af759539063517970e6256c1ccebdd4ee">getDispatcher</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a590d6e44240bce2fcf173b11ee2fe1be">getTargetTriple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> for the target process. <a href="#a590d6e44240bce2fcf173b11ee2fe1be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8827238488b1ce8b05a3054a5bda4c3e">getPageSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the page size for the target process. <a href="#a8827238488b1ce8b05a3054a5bda4c3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/executorprocesscontrol/jitdispatchinfo">JITDispatchInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9382f09a7c29aa5edde7c64f3ad1e8d0">getJITDispatchInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the JIT dispatch function and context address for the executor. <a href="#a9382f09a7c29aa5edde7c64f3ad1e8d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess">MemoryAccess</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acac882e2638ebe645c1226976e87a674">getMemoryAccess</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess">MemoryAccess</a> object for the target process. <a href="#acac882e2638ebe645c1226976e87a674">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1068806ac2e90b55bbd145d923f09777">getMemMgr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a JITLinkMemoryManager for the target process. <a href="#a1068806ac2e90b55bbd145d923f09777">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/dylibmanager">DylibManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab68f0fe783c50ddf340d5d709c1d08a9">getDylibMgr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/orc/dylibmanager">DylibManager</a> for the target process. <a href="#ab68f0fe783c50ddf340d5d709c1d08a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::vector&lt; char &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ccd16237cf9693dbf3c55f594ab9497">getBootstrapMap</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the bootstrap map. <a href="#a3ccd16237cf9693dbf3c55f594ab9497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename SPSTagT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2dc8aa3190f19a2085f418b95cd8194a">getBootstrapMapValue</a> (StringRef Key, std::optional&lt; T &gt; &amp;Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up and SPS-deserialize a bootstrap map value. <a href="#a2dc8aa3190f19a2085f418b95cd8194a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79094e0d6941ab427ac6ecff3a6b7b55">getBootstrapSymbolsMap</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the bootstrap symbol map. <a href="#a79094e0d6941ab427ac6ecff3a6b7b55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab12eb0f7563916a37da32e520dc1ecf">getBootstrapSymbols</a> (ArrayRef&lt; std::pair&lt; ExecutorAddr &amp;, StringRef &gt; &gt; Pairs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>&amp;, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) pair, looks up the string in the bootstrap symbols map and writes its address to the <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> if found. <a href="#aab12eb0f7563916a37da32e520dc1ecf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f007606935ffd8cce497cc85266d796">runAsMain</a> (ExecutorAddr MainFnAddr, ArrayRef&lt; std::string &gt; Args)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run function with a main-like signature. <a href="#a1f007606935ffd8cce497cc85266d796">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d1ee134a86d5409efdcf07e177bc1b9">runAsVoidFunction</a> (ExecutorAddr VoidFnAddr)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run function with a int (*)(void) signature. <a href="#a7d1ee134a86d5409efdcf07e177bc1b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1311188c70924fb09c232f055985e8ae">runAsIntFunction</a> (ExecutorAddr IntFnAddr, int Arg)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run function with a int (*)(int) signature. <a href="#a1311188c70924fb09c232f055985e8ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3528e929721c0c2bbb0ea09688eb8eb9">callWrapperAsync</a> (ExecutorAddr WrapperFnAddr, IncomingWFRHandler OnComplete, ArrayRef&lt; char &gt; ArgBuffer)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function in the executor. <a href="#a3528e929721c0c2bbb0ea09688eb8eb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RunPolicyT, typename FnT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa84549ad8ace430ee3f082604fa90633">callWrapperAsync</a> (RunPolicyT &amp;&amp;Runner, ExecutorAddr WrapperFnAddr, FnT &amp;&amp;OnComplete, ArrayRef&lt; char &gt; ArgBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function in the executor using the given Runner to dispatch OnComplete when the result is ready. <a href="#aa84549ad8ace430ee3f082604fa90633">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FnT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a12a2f5fbb8fd996dda1215f2a960fd3f">callWrapperAsync</a> (ExecutorAddr WrapperFnAddr, FnT &amp;&amp;OnComplete, ArrayRef&lt; char &gt; ArgBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function in the executor. <a href="#a12a2f5fbb8fd996dda1215f2a960fd3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult">shared::WrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1140ddd9e676afc51207f47d6730acf9">callWrapper</a> (ExecutorAddr WrapperFnAddr, ArrayRef&lt; char &gt; ArgBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function in the executor. <a href="#a1140ddd9e676afc51207f47d6730acf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a17f9962c6727ed170f8b494243302732">callSPSWrapperAsync</a> (RunPolicyT &amp;&amp;Runner, ExecutorAddr WrapperFnAddr, SendResultT &amp;&amp;SendResult, const ArgTs &amp;...Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function using SPS to serialize the arguments and deserialize the results. <a href="#a17f9962c6727ed170f8b494243302732">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3233c5b7439500375aba08633ec68794">callSPSWrapperAsync</a> (ExecutorAddr WrapperFnAddr, SendResultT &amp;&amp;SendResult, const ArgTs &amp;...Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function using SPS to serialize the arguments and deserialize the results. <a href="#a3233c5b7439500375aba08633ec68794">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSSignature, typename... WrapperCallArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a955b3e2910b75b483c867cf4e79bb78e">callSPSWrapper</a> (ExecutorAddr WrapperFnAddr, WrapperCallArgTs &amp;&amp;...WrapperCallArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function using SPS to serialize the arguments and deserialize the results. <a href="#a955b3e2910b75b483c867cf4e79bb78e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6646c3c9c9192b203f0faf6821160afc">disconnect</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disconnect from the target process. <a href="#a6646c3c9c9192b203f0faf6821160afc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58fe1bcc0c0139d754c0d01cce3b42bf">SSP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30812e122ddf831a3226a84f0d5caa40">D</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae63a1019e9fd3ba61c6923c1213bb131">ES</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e46ade7cdd5c5a944e4e0b436eebcc">TargetTriple</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a887a86a6014e53f51ffede51edae5987">PageSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/executorprocesscontrol/jitdispatchinfo">JITDispatchInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a408bb953a401290b10daa97f87531a37">JDI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8710c264afee46f88cd003b98ae8f86">MemAccess</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86d16d153b1dc4d9d280a7e4ceee8d5e">MemMgr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/dylibmanager">DylibManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab10c2e8e258477c2c02ce7903e223df0">DylibMgr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::vector&lt; char &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74714a7a45a2501fda9da5b5066425b8">BootstrapMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a644afbfdc6251cffa535988ec59c259e">BootstrapSymbols</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> supports interaction with a JIT target process.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ExecutionSession {#ae073d99ba71b23b530556f075655fc61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a>.</p>


<p>Referenced by <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a> and <a href="#ab3631f9109f6d1422c68b7628c0a0573">getExecutionSession</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ExecutorProcessControl() {#abb438764fe4565ba9704400b74cf38ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutorProcessControl::ExecutorProcessControl (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> &gt; SSP, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a> &gt; D)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>References <a href="#a30812e122ddf831a3226a84f0d5caa40">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a58fe1bcc0c0139d754c0d01cce3b42bf">SSP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc/#af1372961e954f0dad1ec0e4a04dd5220">llvm::orc::SimpleRemoteEPC::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol/#a19bfb4bd3753f07c39a881a7718e0fac">llvm::orc::UnsupportedExecutorProcessControl::UnsupportedExecutorProcessControl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ExecutorProcessControl() {#afbe55d7fe25145ade3cd207703bd28b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutorProcessControl::~ExecutorProcessControl ()</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### callSPSWrapper() {#a955b3e2910b75b483c867cf4e79bb78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSSignature, typename... WrapperCallArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutorProcessControl::callSPSWrapper (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, WrapperCallArgTs &amp;&amp;... WrapperCallArgs)</td>
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

<p>Run a wrapper function using SPS to serialize the arguments and deserialize the results.</p>


<p>If SPSSignature is a non-void function signature then the second argument (the first in the Args list) should be a reference to a return value.</p>


<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a1140ddd9e676afc51207f47d6730acf9">callWrapper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc/#af6ac6028d1ca8cb645402b4fafc88452">llvm::orc::SimpleRemoteEPC::runAsIntFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc/#a3ac93f1af0581195d51da5070d0b2791">llvm::orc::SimpleRemoteEPC::runAsMain</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc/#ae2902337e404cc39c82cc2c8bf435c0a">llvm::orc::SimpleRemoteEPC::runAsVoidFunction</a>.</p>

</div>
</div>

### callSPSWrapperAsync() {#a17f9962c6727ed170f8b494243302732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSSignature, typename RunPolicyT, typename SendResultT, typename... ArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutorProcessControl::callSPSWrapperAsync (RunPolicyT &amp;&amp; Runner, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, SendResultT &amp;&amp; SendResult, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ArgTs &amp;... Args)</td>
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

<p>Run a wrapper function using SPS to serialize the arguments and deserialize the results.</p>

<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a3528e929721c0c2bbb0ea09688eb8eb9">callWrapperAsync</a>.</p>


<p>Referenced by <a href="#a3233c5b7439500375aba08633ec68794">callSPSWrapperAsync</a>.</p>

</div>
</div>

### callSPSWrapperAsync() {#a3233c5b7439500375aba08633ec68794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSSignature, typename SendResultT, typename... ArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutorProcessControl::callSPSWrapperAsync (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, SendResultT &amp;&amp; SendResult, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ArgTs &amp;... Args)</td>
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

<p>Run a wrapper function using SPS to serialize the arguments and deserialize the results.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>References <a href="#a17f9962c6727ed170f8b494243302732">callSPSWrapperAsync</a> and <a href="#a30812e122ddf831a3226a84f0d5caa40">D</a>.</p>

</div>
</div>

### callWrapper() {#a1140ddd9e676afc51207f47d6730acf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">shared::WrapperFunctionResult llvm::orc::ExecutorProcessControl::callWrapper (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; ArgBuffer)</td>
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

<p>Run a wrapper function in the executor.</p>


<p>The wrapper function should be callable as:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">CWrapperFunctionResult fn(uint8_t *<a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">Data</a>, uint64_t <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>);</span></span></div>

</div>


<p>{.cpp}</p>


<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a3528e929721c0c2bbb0ea09688eb8eb9">callWrapperAsync</a>.</p>


<p>Referenced by <a href="#a955b3e2910b75b483c867cf4e79bb78e">callSPSWrapper</a>.</p>

</div>
</div>

### callWrapperAsync() {#a3528e929721c0c2bbb0ea09688eb8eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::orc::ExecutorProcessControl::callWrapperAsync (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/incomingwfrhandler">IncomingWFRHandler</a> OnComplete, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; ArgBuffer)</td>
</tr>
</table>
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


<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="#a17f9962c6727ed170f8b494243302732">callSPSWrapperAsync</a>, <a href="#a1140ddd9e676afc51207f47d6730acf9">callWrapper</a>, <a href="#a12a2f5fbb8fd996dda1215f2a960fd3f">callWrapperAsync</a> and <a href="#aa84549ad8ace430ee3f082604fa90633">callWrapperAsync</a>.</p>

</div>
</div>

### callWrapperAsync() {#aa84549ad8ace430ee3f082604fa90633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RunPolicyT, typename FnT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutorProcessControl::callWrapperAsync (RunPolicyT &amp;&amp; Runner, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, FnT &amp;&amp; OnComplete, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; ArgBuffer)</td>
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

<p>Run a wrapper function in the executor using the given Runner to dispatch OnComplete when the result is ready.</p>

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a3528e929721c0c2bbb0ea09688eb8eb9">callWrapperAsync</a>.</p>

</div>
</div>

### callWrapperAsync() {#a12a2f5fbb8fd996dda1215f2a960fd3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FnT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutorProcessControl::callWrapperAsync (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, FnT &amp;&amp; OnComplete, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; ArgBuffer)</td>
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

<p>Run a wrapper function in the executor.</p>


<p>OnComplete will be dispatched as a <a href="/web-llvm/docs/api/classes/llvm/orc/genericnamedtask">GenericNamedTask</a> using this instance's TaskDispatch object.</p>


<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>References <a href="#a3528e929721c0c2bbb0ea09688eb8eb9">callWrapperAsync</a> and <a href="#a30812e122ddf831a3226a84f0d5caa40">D</a>.</p>

</div>
</div>

### disconnect() {#a6646c3c9c9192b203f0faf6821160afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::orc::ExecutorProcessControl::disconnect ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Disconnect from the target process.</p>


<p>This should be called after the JIT session is shut down.</p>


<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>

</div>
</div>

### getBootstrapMap() {#a3ccd16237cf9693dbf3c55f594ab9497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringMap&lt; std::vector&lt; char &gt; &gt; &amp; llvm::orc::ExecutorProcessControl::getBootstrapMap ()</td>
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

<p>Returns the bootstrap map.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a74714a7a45a2501fda9da5b5066425b8">BootstrapMap</a>.</p>

</div>
</div>

### getBootstrapMapValue() {#a2dc8aa3190f19a2085f418b95cd8194a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename SPSTagT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutorProcessControl::getBootstrapMapValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, std::optional&lt; T &gt; &amp; Val)</td>
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

<p>Look up and SPS-deserialize a bootstrap map value.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>References <a href="#a74714a7a45a2501fda9da5b5066425b8">BootstrapMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getBootstrapSymbols() {#aab12eb0f7563916a37da32e520dc1ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutorProcessControl::getBootstrapSymbols (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt; Pairs)</td>
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

<p>For each (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>&amp;, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) pair, looks up the string in the bootstrap symbols map and writes its address to the <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> if found.</p>


<p>If any symbol is not found then the function returns an error.</p>


<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>References <a href="#a644afbfdc6251cffa535988ec59c259e">BootstrapSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getBootstrapSymbolsMap() {#a79094e0d6941ab427ac6ecff3a6b7b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringMap&lt; ExecutorAddr &gt; &amp; llvm::orc::ExecutorProcessControl::getBootstrapSymbolsMap ()</td>
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

<p>Returns the bootstrap symbol map.</p>

<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a644afbfdc6251cffa535988ec59c259e">BootstrapSymbols</a>.</p>

</div>
</div>

### getDispatcher() {#af759539063517970e6256c1ccebdd4ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TaskDispatcher &amp; llvm::orc::ExecutorProcessControl::getDispatcher ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a30812e122ddf831a3226a84f0d5caa40">D</a>.</p>

</div>
</div>

### getDylibMgr() {#ab68f0fe783c50ddf340d5d709c1d08a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DylibManager &amp; llvm::orc::ExecutorProcessControl::getDylibMgr ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/orc/dylibmanager">DylibManager</a> for the target process.</p>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab10c2e8e258477c2c02ce7903e223df0">DylibMgr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator/#a0be4b6ee27375703c0be30f0b730d0ba">llvm::orc::EPCDynamicLibrarySearchGenerator::Load</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a578c0003fa8d6a75ea0e805e20104439">llvm::orc::lookupAndRecordAddrs</a>.</p>

</div>
</div>

### getExecutionSession() {#ab3631f9109f6d1422c68b7628c0a0573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession &amp; llvm::orc::ExecutorProcessControl::getExecutionSession ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> associated with this instance.</p>


<p>Not callable until the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> has been associated.</p>


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae63a1019e9fd3ba61c6923c1213bb131">ES</a> and <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc/#af21de81dd1759e3d1385c8ed7c0aa472">llvm::orc::SimpleRemoteEPC::callWrapperAsync</a>.</p>

</div>
</div>

### getJITDispatchInfo() {#a9382f09a7c29aa5edde7c64f3ad1e8d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const JITDispatchInfo &amp; llvm::orc::ExecutorProcessControl::getJITDispatchInfo ()</td>
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

<p>Get the JIT dispatch function and context address for the executor.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a408bb953a401290b10daa97f87531a37">JDI</a>.</p>

</div>
</div>

### getMemMgr() {#a1068806ac2e90b55bbd145d923f09777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">jitlink::JITLinkMemoryManager &amp; llvm::orc::ExecutorProcessControl::getMemMgr ()</td>
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

<p>Return a JITLinkMemoryManager for the target process.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a86d16d153b1dc4d9d280a7e4ceee8d5e">MemMgr</a>.</p>

</div>
</div>

### getMemoryAccess() {#acac882e2638ebe645c1226976e87a674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess &amp; llvm::orc::ExecutorProcessControl::getMemoryAccess ()</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess">MemoryAccess</a> object for the target process.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad8710c264afee46f88cd003b98ae8f86">MemAccess</a>.</p>

</div>
</div>

### getPageSize() {#a8827238488b1ce8b05a3054a5bda4c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::orc::ExecutorProcessControl::getPageSize ()</td>
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

<p>Get the page size for the target process.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a887a86a6014e53f51ffede51edae5987">PageSize</a>.</p>

</div>
</div>

### getSymbolStringPool() {#a75e1dd9778ba22121cbf5d9f69597377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt; SymbolStringPool &gt; llvm::orc::ExecutorProcessControl::getSymbolStringPool ()</td>
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

<p>Return a shared pointer to the <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> for this instance.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a58fe1bcc0c0139d754c0d01cce3b42bf">SSP</a>.</p>

</div>
</div>

### getTargetTriple() {#a590d6e44240bce2fcf173b11ee2fe1be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::orc::ExecutorProcessControl::getTargetTriple ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> for the target process.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a43e46ade7cdd5c5a944e4e0b436eebcc">TargetTriple</a>.</p>

</div>
</div>

### intern() {#a6461773648a1bc1717ce65bf3247e909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPtr llvm::orc::ExecutorProcessControl::intern (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymName)</td>
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

<p>Intern a symbol name in the <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a>.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="#a58fe1bcc0c0139d754c0d01cce3b42bf">SSP</a>.</p>

</div>
</div>

### runAsIntFunction() {#a1311188c70924fb09c232f055985e8ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; int32_t &gt; llvm::orc::ExecutorProcessControl::runAsIntFunction (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> IntFnAddr, int Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run function with a int (*)(int) signature.</p>

<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>

</div>
</div>

### runAsMain() {#a1f007606935ffd8cce497cc85266d796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; int32_t &gt; llvm::orc::ExecutorProcessControl::runAsMain (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> MainFnAddr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt; Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run function with a main-like signature.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>

</div>
</div>

### runAsVoidFunction() {#a7d1ee134a86d5409efdcf07e177bc1b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; int32_t &gt; llvm::orc::ExecutorProcessControl::runAsVoidFunction (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> VoidFnAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run function with a int (*)(void) signature.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BootstrapMap {#a74714a7a45a2501fda9da5b5066425b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::vector&lt;char&gt; &gt; llvm::orc::ExecutorProcessControl::BootstrapMap</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="#a3ccd16237cf9693dbf3c55f594ab9497">getBootstrapMap</a>, <a href="#a2dc8aa3190f19a2085f418b95cd8194a">getBootstrapMapValue</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a>.</p>

</div>
</div>

### BootstrapSymbols {#a644afbfdc6251cffa535988ec59c259e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;ExecutorAddr&gt; llvm::orc::ExecutorProcessControl::BootstrapSymbols</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="#aab12eb0f7563916a37da32e520dc1ecf">getBootstrapSymbols</a>, <a href="#a79094e0d6941ab427ac6ecff3a6b7b55">getBootstrapSymbolsMap</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a>.</p>

</div>
</div>

### D {#a30812e122ddf831a3226a84f0d5caa40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TaskDispatcher&gt; llvm::orc::ExecutorProcessControl::D</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="#a3233c5b7439500375aba08633ec68794">callSPSWrapperAsync</a>, <a href="#a12a2f5fbb8fd996dda1215f2a960fd3f">callWrapperAsync</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#ae15684412736f37c545f8f2ec65cce56">llvm::orc::SelfExecutorProcessControl::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc/#a4753da41da67751c4d4a706a90eeeeec">llvm::orc::SimpleRemoteEPC::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a70b5731dbe77edbd06e480a185fb9c6e">llvm::orc::SelfExecutorProcessControl::disconnect</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc/#ab4c26bc089f703fd592ca80cdeb9bd3f">llvm::orc::SimpleRemoteEPC::disconnect</a>, <a href="#abb438764fe4565ba9704400b74cf38ab">ExecutorProcessControl</a>, <a href="#af759539063517970e6256c1ccebdd4ee">getDispatcher</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc/#af1372961e954f0dad1ec0e4a04dd5220">llvm::orc::SimpleRemoteEPC::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol/#a19bfb4bd3753f07c39a881a7718e0fac">llvm::orc::UnsupportedExecutorProcessControl::UnsupportedExecutorProcessControl</a>.</p>

</div>
</div>

### DylibMgr {#ab10c2e8e258477c2c02ce7903e223df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DylibManager* llvm::orc::ExecutorProcessControl::DylibMgr = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="#ab68f0fe783c50ddf340d5d709c1d08a9">getDylibMgr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc/#af1372961e954f0dad1ec0e4a04dd5220">llvm::orc::SimpleRemoteEPC::operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a>.</p>

</div>
</div>

### ES {#ae63a1019e9fd3ba61c6923c1213bb131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession* llvm::orc::ExecutorProcessControl::ES = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="#ab3631f9109f6d1422c68b7628c0a0573">getExecutionSession</a>.</p>

</div>
</div>

### JDI {#a408bb953a401290b10daa97f87531a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDispatchInfo llvm::orc::ExecutorProcessControl::JDI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="#a9382f09a7c29aa5edde7c64f3ad1e8d0">getJITDispatchInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a>.</p>

</div>
</div>

### MemAccess {#ad8710c264afee46f88cd003b98ae8f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess* llvm::orc::ExecutorProcessControl::MemAccess = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="#acac882e2638ebe645c1226976e87a674">getMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol/#a19bfb4bd3753f07c39a881a7718e0fac">llvm::orc::UnsupportedExecutorProcessControl::UnsupportedExecutorProcessControl</a>.</p>

</div>
</div>

### MemMgr {#a86d16d153b1dc4d9d280a7e4ceee8d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">jitlink::JITLinkMemoryManager* llvm::orc::ExecutorProcessControl::MemMgr = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#ae15684412736f37c545f8f2ec65cce56">llvm::orc::SelfExecutorProcessControl::Create</a>, <a href="#a1068806ac2e90b55bbd145d923f09777">getMemMgr</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a>.</p>

</div>
</div>

### PageSize {#a887a86a6014e53f51ffede51edae5987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::orc::ExecutorProcessControl::PageSize = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#ae15684412736f37c545f8f2ec65cce56">llvm::orc::SelfExecutorProcessControl::Create</a>, <a href="#a8827238488b1ce8b05a3054a5bda4c3e">getPageSize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol/#a19bfb4bd3753f07c39a881a7718e0fac">llvm::orc::UnsupportedExecutorProcessControl::UnsupportedExecutorProcessControl</a>.</p>

</div>
</div>

### SSP {#a58fe1bcc0c0139d754c0d01cce3b42bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;SymbolStringPool&gt; llvm::orc::ExecutorProcessControl::SSP</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#ae15684412736f37c545f8f2ec65cce56">llvm::orc::SelfExecutorProcessControl::Create</a>, <a href="#abb438764fe4565ba9704400b74cf38ab">ExecutorProcessControl</a>, <a href="#a75e1dd9778ba22121cbf5d9f69597377">getSymbolStringPool</a>, <a href="#a6461773648a1bc1717ce65bf3247e909">intern</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc/#af1372961e954f0dad1ec0e4a04dd5220">llvm::orc::SimpleRemoteEPC::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol/#a19bfb4bd3753f07c39a881a7718e0fac">llvm::orc::UnsupportedExecutorProcessControl::UnsupportedExecutorProcessControl</a>.</p>

</div>
</div>

### TargetTriple {#a43e46ade7cdd5c5a944e4e0b436eebcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::orc::ExecutorProcessControl::TargetTriple</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Referenced by <a href="#a590d6e44240bce2fcf173b11ee2fe1be">getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol/#a19bfb4bd3753f07c39a881a7718e0fac">llvm::orc::UnsupportedExecutorProcessControl::UnsupportedExecutorProcessControl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
