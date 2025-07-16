---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/lljitbuildersetters
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LLJITBuilderSetters` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename JITType, typename SetterImpl, typename State&gt;
class llvm::orc::LLJITBuilderSetters&lt;JITType, SetterImpl, State&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">llvm/ExecutionEngine/Orc/LLJIT.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lllazyjitbuildersetters">LLLazyJITBuilderSetters&lt;JITType, SetterImpl, State&gt;</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8dc599cb2907f39f4d0787b5de3c4c32">setExecutorProcessControl</a> (std::unique_ptr&lt; ExecutorProcessControl &gt; EPC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set an <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> for this instance. <a href="#a8dc599cb2907f39f4d0787b5de3c4c32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aceb87797114eb55355292057b727863b">setExecutionSession</a> (std::unique_ptr&lt; ExecutionSession &gt; ES)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set an <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> for this instance. <a href="#aceb87797114eb55355292057b727863b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a864eff24ba41102940ab527411f2e1a1">setJITTargetMachineBuilder</a> (JITTargetMachineBuilder JTMB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> for this instance. <a href="#a864eff24ba41102940ab527411f2e1a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a13c734cdb8aad780bd9b9b2baa7c3681">getJITTargetMachineBuilder</a> () -&gt; std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a>. <a href="#a13c734cdb8aad780bd9b9b2baa7c3681">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7fd0841ee44c0f2ab2f3434c732495b1">setDataLayout</a> (std::optional&lt; DataLayout &gt; DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> for this instance. <a href="#a7fd0841ee44c0f2ab2f3434c732495b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a03b8623cebbf8db82fe51e09fb9aef22">setLinkProcessSymbolsByDefault</a> (bool LinkProcessSymbolsByDefault)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The LinkProcessSymbolsDyDefault flag determines whether the "Process" <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> will be added to the default link order at <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> construction time. <a href="#a03b8623cebbf8db82fe51e09fb9aef22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af09d70e8bfc7d790640f2e1be1cdf1eb">setProcessSymbolsJITDylibSetup</a> (LLJITBuilderState::ProcessSymbolsJITDylibSetupFunction SetupProcessSymbolsJITDylib)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a setup function for the process symbols dylib. <a href="#af09d70e8bfc7d790640f2e1be1cdf1eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9431484a847d2729f9a07481255a5db6">setObjectLinkingLayerCreator</a> (LLJITBuilderState::ObjectLinkingLayerCreator CreateObjectLinkingLayer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set an <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> creation function. <a href="#a9431484a847d2729f9a07481255a5db6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a59661d11818c97db12857fc12e5c7c">setCompileFunctionCreator</a> (LLJITBuilderState::CompileFunctionCreator CreateCompileFunction)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a CompileFunctionCreator. <a href="#a3a59661d11818c97db12857fc12e5c7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a31a54545a741390d14c0a3be51574060">setPrePlatformSetup</a> (unique_function&lt; Error(LLJIT &amp;)&gt; PrePlatformSetup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a setup function to be run just before the PlatformSetupFunction is run. <a href="#a31a54545a741390d14c0a3be51574060">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab73d2cdea504ee56114cc8a4857d4942">setPlatformSetUp</a> (LLJITBuilderState::PlatformSetupFunction SetUpPlatform)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up an PlatformSetupFunction. <a href="#ab73d2cdea504ee56114cc8a4857d4942">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a11621cccb20125d53fecbb04ebe86e63">setNotifyCreatedCallback</a> (LLJITBuilderState::NotifyCreatedFunction Callback)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up a callback after successful construction of the JIT. <a href="#a11621cccb20125d53fecbb04ebe86e63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76ce6b4b4b67bc1e6f26d146e748ae29">setNumCompileThreads</a> (unsigned NumCompileThreads)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the number of compile threads to use. <a href="#a76ce6b4b4b67bc1e6f26d146e748ae29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae21f57fe6141499a35b81f27bd3e9a6f">setSupportConcurrentCompilation</a> (std::optional&lt; bool &gt; SupportConcurrentCompilation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If set, this forces <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> concurrent compilation support to be either on or off. <a href="#ae21f57fe6141499a35b81f27bd3e9a6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac6e077456ace4ec4b9e0e79235dc2f52">create</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; JITType &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an instance of the JIT. <a href="#ac6e077456ace4ec4b9e0e79235dc2f52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af3e62a93b72970945ba5723691d727b5">impl</a> ()</td>
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


<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### create() {#ac6e077456ace4ec4b9e0e79235dc2f52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; JITType &gt; &gt; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::create ()</td>
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

<p>Create an instance of the JIT.</p>

<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getJITTargetMachineBuilder() {#a13c734cdb8aad780bd9b9b2baa7c3681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; JITTargetMachineBuilder &gt; &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::getJITTargetMachineBuilder ()</td>
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

<p>Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a>.</p>

<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setCompileFunctionCreator() {#a3a59661d11818c97db12857fc12e5c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setCompileFunctionCreator (<a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#af846158a4c64b54eef46a1fea05ab310">LLJITBuilderState::CompileFunctionCreator</a> CreateCompileFunction)</td>
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

<p>Set a CompileFunctionCreator.</p>


<p>If this method is not called, a default creation function wil be used that will construct a basic IR compile function that is compatible with the selected number of threads (<a href="/web-llvm/docs/api/classes/llvm/orc/simplecompiler">SimpleCompiler</a> for '0' compile threads, <a href="/web-llvm/docs/api/classes/llvm/orc/concurrentircompiler">ConcurrentIRCompiler</a> otherwise).</p>


<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setDataLayout() {#a7fd0841ee44c0f2ab2f3434c732495b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setDataLayout (std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &gt; DL)</td>
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

<p>Set a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> for this instance.</p>


<p>If no data layout is specified then the target's default data layout will be used.</p>


<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setExecutionSession() {#aceb87797114eb55355292057b727863b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setExecutionSession (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &gt; ES)</td>
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

<p>Set an <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> for this instance.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setExecutorProcessControl() {#a8dc599cb2907f39f4d0787b5de3c4c32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setExecutorProcessControl (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &gt; EPC)</td>
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

<p>Set an <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> for this instance.</p>


<p>This should not be called if <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> has already been set.</p>


<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setJITTargetMachineBuilder() {#a864eff24ba41102940ab527411f2e1a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setJITTargetMachineBuilder (<a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> JTMB)</td>
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

<p>Set the <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> for this instance.</p>


<p>If this method is not called, <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder/#aa67d14db111b10a6a09cb70fa5f4e084">JITTargetMachineBuilder::detectHost</a> will be used to construct a default target machine builder for the host platform.</p>


<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setLinkProcessSymbolsByDefault() {#a03b8623cebbf8db82fe51e09fb9aef22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setLinkProcessSymbolsByDefault (bool LinkProcessSymbolsByDefault)</td>
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

<p>The LinkProcessSymbolsDyDefault flag determines whether the "Process" <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> will be added to the default link order at <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> construction time.</p>


<p>If true, the <a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> will be added as the last item in the default link order. If false (or if the <a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is disabled via setProcessSymbolsJITDylibSetup) then the <a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> will not appear in the default link order.</p>


<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setNotifyCreatedCallback() {#a11621cccb20125d53fecbb04ebe86e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setNotifyCreatedCallback (<a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a59b39c299260cc98a016c88b7684626e">LLJITBuilderState::NotifyCreatedFunction</a> Callback)</td>
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

<p>Set up a callback after successful construction of the JIT.</p>


<p>This is useful to attach generators to JITDylibs or inject initial symbol definitions.</p>


<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setNumCompileThreads() {#a76ce6b4b4b67bc1e6f26d146e748ae29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setNumCompileThreads (unsigned NumCompileThreads)</td>
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

<p>Set the number of compile threads to use.</p>


<p>If set to zero, compilation will be performed on the execution thread when JITing in-process. If set to any other number N, a thread pool of N threads will be created for compilation.</p>


<p>If this method is not called, behavior will be as if it were called with a zero argument.</p>


<p>This setting should not be used if a custom <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> or <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> object is set: in those cases a custom <a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a> should be used instead.</p>


<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setObjectLinkingLayerCreator() {#a9431484a847d2729f9a07481255a5db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setObjectLinkingLayerCreator (<a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a0c814481775a4e5e618bb12624914357">LLJITBuilderState::ObjectLinkingLayerCreator</a> CreateObjectLinkingLayer)</td>
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

<p>Set an <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> creation function.</p>


<p>If this method is not called, a default creation function will be used that will construct an <a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer">RTDyldObjectLinkingLayer</a>.</p>


<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setPlatformSetUp() {#ab73d2cdea504ee56114cc8a4857d4942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setPlatformSetUp (<a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#ae4af55a290a38d4fdc809fcac453ca52">LLJITBuilderState::PlatformSetupFunction</a> SetUpPlatform)</td>
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

<p>Set up an PlatformSetupFunction.</p>


<p>If this method is not called then setUpGenericLLVMIRPlatform will be used to configure the JIT's platform support.</p>


<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setPrePlatformSetup() {#a31a54545a741390d14c0a3be51574060}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setPrePlatformSetup (<a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> &amp;)&gt; PrePlatformSetup)</td>
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

<p>Set a setup function to be run just before the PlatformSetupFunction is run.</p>


<p>This can be used to customize the <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> instance before the platform is set up. E.g. By installing a debugger support plugin before the platform is set up (when the ORC runtime is loaded) we enable debugging of the runtime itself.</p>


<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setProcessSymbolsJITDylibSetup() {#af09d70e8bfc7d790640f2e1be1cdf1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setProcessSymbolsJITDylibSetup (<a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#af756c328268fed9a73465567e66d4c79">LLJITBuilderState::ProcessSymbolsJITDylibSetupFunction</a> SetupProcessSymbolsJITDylib)</td>
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

<p>Set a setup function for the process symbols dylib.</p>


<p>If not provided, but LinkProcessSymbolsJITDylibByDefault is true, then the process-symbols <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> will be configured with a <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator">DynamicLibrarySearchGenerator</a> with a default symbol filter.</p>


<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setSupportConcurrentCompilation() {#ae21f57fe6141499a35b81f27bd3e9a6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setSupportConcurrentCompilation (std::optional&lt; bool &gt; SupportConcurrentCompilation)</td>
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

<p>If set, this forces <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> concurrent compilation support to be either on or off.</p>


<p>This controls the selection of compile function (concurrent vs single threaded) and whether or not sub-modules are cloned to new contexts for lazy emission.</p>


<p>If not explicitly set then concurrency support will be turned on if NumCompileThreads is set to a non-zero value, or if a custom <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> or <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> instance is provided.</p>


<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### impl() {#af3e62a93b72970945ba5723691d727b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Referenced by <a href="#ac6e077456ace4ec4b9e0e79235dc2f52">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::create</a>, <a href="#a13c734cdb8aad780bd9b9b2baa7c3681">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::getJITTargetMachineBuilder</a>, <a href="#a3a59661d11818c97db12857fc12e5c7c">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setCompileFunctionCreator</a>, <a href="#a7fd0841ee44c0f2ab2f3434c732495b1">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setDataLayout</a>, <a href="#aceb87797114eb55355292057b727863b">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setExecutionSession</a>, <a href="#a8dc599cb2907f39f4d0787b5de3c4c32">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setExecutorProcessControl</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lllazyjitbuildersetters/#a9a821ccdd243900fb791319079728b2c">llvm::orc::LLLazyJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setIndirectStubsManagerBuilder</a>, <a href="#a864eff24ba41102940ab527411f2e1a1">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setJITTargetMachineBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lllazyjitbuildersetters/#a82c042423f9eebda0fc46dee8e08bdbe">llvm::orc::LLLazyJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setLazyCallthroughManager</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lllazyjitbuildersetters/#a7a500f0480232138cffea2a70eb31dda">llvm::orc::LLLazyJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setLazyCompileFailureAddr</a>, <a href="#a03b8623cebbf8db82fe51e09fb9aef22">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setLinkProcessSymbolsByDefault</a>, <a href="#a11621cccb20125d53fecbb04ebe86e63">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setNotifyCreatedCallback</a>, <a href="#a76ce6b4b4b67bc1e6f26d146e748ae29">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setNumCompileThreads</a>, <a href="#a9431484a847d2729f9a07481255a5db6">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setObjectLinkingLayerCreator</a>, <a href="#ab73d2cdea504ee56114cc8a4857d4942">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setPlatformSetUp</a>, <a href="#a31a54545a741390d14c0a3be51574060">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setPrePlatformSetup</a>, <a href="#af09d70e8bfc7d790640f2e1be1cdf1eb">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setProcessSymbolsJITDylibSetup</a> and <a href="#ae21f57fe6141499a35b81f27bd3e9a6f">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setSupportConcurrentCompilation</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
