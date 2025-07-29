---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizerbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachODebugObjectSynthesizerBase` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/gdbjitdebuginforegistrationplugin/debugsectionsynthesizer">DebugSectionSynthesizer</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer">MachODebugObjectSynthesizer&lt;MachOTraits&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60d7d9558254099ae5719da27ee1ab62">MachODebugObjectSynthesizerBase</a> (LinkGraph &amp;G, ExecutorAddr RegisterActionAddr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5656e827c97a1a6149d363e3ccb689e0">~MachODebugObjectSynthesizerBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e160e39a23517dff688b6bb5dfa1c06">preserveDebugSections</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81a48d0c6ddf38b9a1cf710b35a6e4a">G</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af37c05c5933699849a6cd927848c38fb">RegisterActionAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bdb53614bf065ddc9a5517c445587be">isDebugSection</a> (Section &amp;Sec)</td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachODebugObjectSynthesizerBase() {#a60d7d9558254099ae5719da27ee1ab62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>


<p>References <a href="#ad81a48d0c6ddf38b9a1cf710b35a6e4a">G</a> and <a href="#af37c05c5933699849a6cd927848c38fb">RegisterActionAddr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachODebugObjectSynthesizerBase() {#a5656e827c97a1a6149d363e3ccb689e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::~MachODebugObjectSynthesizerBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### preserveDebugSections() {#a2e160e39a23517dff688b6bb5dfa1c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::preserveDebugSections ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ad81a48d0c6ddf38b9a1cf710b35a6e4a">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#aa080c38d82f500daf23c736bba23b17b">isDebugSection</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp/#acae955762ff692143c725860c779150d">SynthDebugSectionName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### G {#ad81a48d0c6ddf38b9a1cf710b35a6e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraph&amp; anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::G</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a21d1557ff7212b52d2935836c8619919">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::completeSynthesisAndRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a1b02742a18bc0124c7cb534da9a59979">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::MachODebugObjectSynthesizer</a>, <a href="#a60d7d9558254099ae5719da27ee1ab62">MachODebugObjectSynthesizerBase</a>, <a href="#a2e160e39a23517dff688b6bb5dfa1c06">preserveDebugSections</a> and <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a59a5eeccde7b8eef0833cee7b914443b">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::startSynthesis</a>.</p>

</div>
</div>

### RegisterActionAddr {#af37c05c5933699849a6cd927848c38fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::RegisterActionAddr</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a21d1557ff7212b52d2935836c8619919">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::completeSynthesisAndRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a1b02742a18bc0124c7cb534da9a59979">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::MachODebugObjectSynthesizer</a> and <a href="#a60d7d9558254099ae5719da27ee1ab62">MachODebugObjectSynthesizerBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isDebugSection() {#a4bdb53614bf065ddc9a5517c445587be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::isDebugSection (<a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; Sec)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/debuggersupportplugin-cpp">DebuggerSupportPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/section/#a4341a84fa2a242e35a38f0f9b5e5b832">llvm::jitlink::Section::getName</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

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
