---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachODebugObjectSynthesizer` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename MachOTraits&gt;
class anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt;MachOTraits&gt; { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizerbase">MachODebugObjectSynthesizerBase</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MachOTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa406e0e918fe8a9adfea0ff0aa9063b0">BuilderType</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder">MachOBuilder</a>&lt; MachOTraits &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MachOTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1b02742a18bc0124c7cb534da9a59979">MachODebugObjectSynthesizer</a> (ExecutionSession &amp;ES, LinkGraph &amp;G, ExecutorAddr RegisterActionAddr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MachOTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a59a5eeccde7b8eef0833cee7b914443b">startSynthesis</a> () override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MachOTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21d1557ff7212b52d2935836c8619919">completeSynthesisAndRegister</a> () override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MachOTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a60d7d9558254099ae5719da27ee1ab62">MachODebugObjectSynthesizerBase</a> (LinkGraph &amp;G, ExecutorAddr RegisterActionAddr)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MachOTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ea8b6174debd8357af15e5e3e0cf524">MachOContainerBlock</a> = nullptr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MachOTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder">MachOBuilder</a>&lt; MachOTraits &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1079b7a73cd47fe123cbecb6b61a7564">Builder</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MachOTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder">MachOBuilder</a>&lt; MachOTraits &gt;::Segment *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8182ec9dd5df5ae23c6ab9bcfffb499a">Seg</a> = nullptr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MachOTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; StabSymbolsEntry &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa766002c5cbbf65692c7200b0c153440">StabSymbols</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MachOTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; SectionPair, 16 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae261dc38ba89ff21df6f54f2554a3a67">DebugSections</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MachOTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; SectionPair, 16 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aada4976b50a8900e789b698ff5331034">NonDebugSections</a></td>
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


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BuilderType {#aa406e0e918fe8a9adfea0ff0aa9063b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MachOTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::BuilderType =  MachOBuilder&lt;MachOTraits&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachODebugObjectSynthesizer() {#a1b02742a18bc0124c7cb534da9a59979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MachOTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::MachODebugObjectSynthesizer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> RegisterActionAddr)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizerbase/#ad81a48d0c6ddf38b9a1cf710b35a6e4a">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::G</a>, <a href="#a60d7d9558254099ae5719da27ee1ab62">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::MachODebugObjectSynthesizerBase</a> and <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizerbase/#af37c05c5933699849a6cd927848c38fb">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::RegisterActionAddr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### completeSynthesisAndRegister() {#a21d1557ff7212b52d2935836c8619919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MachOTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::completeSynthesisAndRegister ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall/#ac924edcd8ad4ceeebcbcea4ca04a793b">llvm::orc::shared::WrapperFunctionCall::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizerbase/#ad81a48d0c6ddf38b9a1cf710b35a6e4a">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/sectionrange/#a2bdaae5409de01024779602e8ba48181">llvm::jitlink::SectionRange::getEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/sectionrange/#a9de39d13fcb57d2263c7bb65765df453">llvm::jitlink::SectionRange::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/sectionrange/#ab7bd439fefcb561d029d76b2ca9bc500">llvm::jitlink::SectionRange::getStart</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a4ee908fb9052f020e3c50e3f1a7d81c5">llvm::orc::ExecutorAddr::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizerbase/#af37c05c5933699849a6cd927848c38fb">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::RegisterActionAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a194b9b14fac1e84995be68484867a709">llvm::MachO::S_ATTR_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### MachODebugObjectSynthesizerBase() {#a60d7d9558254099ae5719da27ee1ab62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MachOTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::MachODebugObjectSynthesizerBase (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> RegisterActionAddr)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>


<p>Referenced by <a href="#a1b02742a18bc0124c7cb534da9a59979">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::MachODebugObjectSynthesizer</a>.</p>

</div>
</div>

### startSynthesis() {#a59a5eeccde7b8eef0833cee7b914443b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MachOTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::startSynthesis ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ac2c31b7b3c778d12aa176f9253511f37">llvm::StringRef::count</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ad6f9fa82bb8b6a5dae98b9d9d346d913">llvm::DWARFContext::create</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/sectionrange/#a7d8104b395275d3ea6a27be2fc68df2d">llvm::jitlink::SectionRange::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizerbase/#ad81a48d0c6ddf38b9a1cf710b35a6e4a">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#a69c476ec14d664758c5ae473e73526f7">llvm::jitlink::Block::getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#a4e670b08f3b3affac8a6916a2fc04b23">llvm::jitlink::Block::getContent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3f499fbedb1116d9243b169e32f12367">llvm::MachO::getCPUSubType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ada5bfd87ed7d3e85e1447626b2692055">llvm::MachO::getCPUType</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/sectionrange/#a05505cc35d525e94455a991a175318f6">llvm::jitlink::SectionRange::getFirstBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#aa637382b37ac3809d3998c2ed8fb3118">llvm::jitlink::Block::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/sectionrange/#a9de39d13fcb57d2263c7bb65765df453">llvm::jitlink::SectionRange::getSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#aa080c38d82f500daf23c736bba23b17b">isDebugSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/errorinfobase/#aef3388cbd70a2f78453456a8ecef6311">llvm::ErrorInfoBase::log</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa0720b97729bd97889599a4dc76faf0dc">llvm::MachO::MH_OBJECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a16655d8dcb288f8b3bdc27c0ed3bdc69afaec06a130073991fdc732d8a920371d">llvm::MachO::N_BNSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a16655d8dcb288f8b3bdc27c0ed3bdc69a66256c712e00f573954429eb281bb781">llvm::MachO::N_ENSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a16655d8dcb288f8b3bdc27c0ed3bdc69aec1f181c361a427083509a1dba667a31">llvm::MachO::N_FUN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a16655d8dcb288f8b3bdc27c0ed3bdc69aab0ae90db4c3045120b521ce97612bd8">llvm::MachO::N_GSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a16655d8dcb288f8b3bdc27c0ed3bdc69a3f9a85251deb79fed4404067f80782a6">llvm::MachO::N_OSO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a16655d8dcb288f8b3bdc27c0ed3bdc69ae654f2a2ee63f7bf16c6c22d59b9c32f">llvm::MachO::N_SO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#abdd6ae2070338087f3d5d54200d708d6a777f2725a7af3806c6bb86c58bc0b5c8">llvm::orc::NoAlloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a7a1a5f3e79fdc91edf2f5ead9d66abb4">llvm::orc::Read</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp/#acae955762ff692143c725860c779150d">SynthDebugSectionName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Builder {#a1079b7a73cd47fe123cbecb6b61a7564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MachOTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOBuilder&lt;MachOTraits&gt; anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>

</div>
</div>

### DebugSections {#ae261dc38ba89ff21df6f54f2554a3a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MachOTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SectionPair, 16&gt; anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::DebugSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>

</div>
</div>

### MachOContainerBlock {#a7ea8b6174debd8357af15e5e3e0cf524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MachOTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block* anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::MachOContainerBlock = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>

</div>
</div>

### NonDebugSections {#aada4976b50a8900e789b698ff5331034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MachOTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SectionPair, 16&gt; anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::NonDebugSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>

</div>
</div>

### Seg {#a8182ec9dd5df5ae23c6ab9bcfffb499a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MachOTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOBuilder&lt;MachOTraits&gt;::Segment* anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::Seg = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>

</div>
</div>

### StabSymbols {#aa766002c5cbbf65692c7200b0c153440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MachOTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;StabSymbolsEntry&gt; anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::StabSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
