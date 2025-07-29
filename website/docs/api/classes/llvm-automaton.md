---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/automaton
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Automaton` Class Template

<p>A deterministic finite-state automaton. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ActionT&gt;
class llvm::Automaton&lt;ActionT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">llvm/Support/Automaton.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ActionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ed601358dcead55d7299f124c7417aa">MapTy</a> = std::map&lt; std::pair&lt; uint64_t, ActionT &gt;, std::pair&lt; uint64_t, unsigned &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from {State, Action} to {NewState, TransitionInfoIdx}. <a href="#a3ed601358dcead55d7299f124c7417aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename InfoT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#adbfe7e804f0c334162d71db7e2f77ded">Automaton</a> (ArrayRef&lt; InfoT &gt; Transitions, ArrayRef&lt; NfaStatePair &gt; TranscriptionTable={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an automaton. <a href="#adbfe7e804f0c334162d71db7e2f77ded">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ActionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a9ade48998a5f4ef2d6c9b7ceecbe209d">Automaton</a> (const Automaton &amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ActionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a30f80f4c7e00f9a31b9d6e6221805b4d">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the automaton to its initial state. <a href="#a30f80f4c7e00f9a31b9d6e6221805b4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ActionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab475bbd3819025a90bd009e18988bb40">enableTranscription</a> (bool Enable=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable or disable transcription. <a href="#ab475bbd3819025a90bd009e18988bb40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ActionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa2620d2287c9bf8cd15da84914af65e2">add</a> (const ActionT &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transition the automaton based on input symbol A. <a href="#aa2620d2287c9bf8cd15da84914af65e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ActionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b955bf418dc9539b07a58a6e94ec638">canAdd</a> (const ActionT &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the automaton can be transitioned based on input symbol A. <a href="#a8b955bf418dc9539b07a58a6e94ec638">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ActionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad6fe99d549af75e18cd1e383e70c5beb">getNfaPaths</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a7c51673db3dd1c6d2088fc30224393d3">NfaPath</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain a set of possible paths through the input nondeterministic automaton that could be obtained from the sequence of input actions presented to this deterministic automaton. <a href="#ad6fe99d549af75e18cd1e383e70c5beb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ActionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::shared_ptr&lt; MapTy &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa83ee188c66f74ed78d5eb6b0e2b7e94">M</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ActionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/internal/nfatranscriber">internal::NfaTranscriber</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a863c0781f406ba2bf7f2d79472b2d0c7">Transcriber</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An optional transcription object. <a href="#a863c0781f406ba2bf7f2d79472b2d0c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ActionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4775b526d6e6e28d07266cb148732f75">State</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The initial DFA state is 1. <a href="#a4775b526d6e6e28d07266cb148732f75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ActionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aca89c3fcad786aea10404e4c6b9734e2">Transcribe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we should transcribe and false if not (even if Transcriber is defined). <a href="#aca89c3fcad786aea10404e4c6b9734e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A deterministic finite-state automaton.</p>


<p>The automaton is defined in <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>; this object drives an automaton defined by tblgen-emitted tables.</p>


<p>An automaton accepts a sequence of input tokens ("actions"). This class is templated on the type of these actions.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### MapTy {#a3ed601358dcead55d7299f124c7417aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ActionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Automaton&lt; ActionT &gt;::MapTy =  std::map&lt;std::pair&lt;uint64_t, ActionT&gt;, std::pair&lt;uint64_t, unsigned&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from {State, Action} to {NewState, TransitionInfoIdx}.</p>


<p>TransitionInfoIdx is used by the DfaTranscriber to analyze the transition. FIXME: This uses a std::map because ActionT can be a pair type including an enum. In particular <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo&lt;ActionT&gt;</a> must be defined to use <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> here. This is a shared_ptr to allow very quick copy-construction of Automata; this state is immutable after construction so this is safe.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Automaton() {#adbfe7e804f0c334162d71db7e2f77ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename InfoT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Automaton&lt; ActionT &gt;::Automaton (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; InfoT &gt; Transitions, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/nfastatepair">NfaStatePair</a> &gt; TranscriptionTable={})</td>
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

<p>Create an automaton.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Transitions</td>
<td class="doxyParamItemDescription"><p>The Transitions table as created by <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>. Note that because the action type differs per automaton, the table type is templated as <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;InfoT&gt;</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TranscriptionTable</td>
<td class="doxyParamItemDescription"><p>The TransitionInfo table as created by <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Providing the TranscriptionTable argument as non-empty will enable the use of transcription, which analyzes the possible paths in the original NFA taken by the DFA. NOTE: This is substantially more work than simply driving the DFA, so unless you require the getPaths() method leave this empty.</p>


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>


<p>Referenced by <a href="#a9ade48998a5f4ef2d6c9b7ceecbe209d">llvm::Automaton&lt; ActionT &gt;::Automaton</a>.</p>

</div>
</div>

### Automaton() {#a9ade48998a5f4ef2d6c9b7ceecbe209d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ActionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Automaton&lt; ActionT &gt;::Automaton (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/automaton">Automaton</a> &amp; Other)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>


<p>References <a href="#adbfe7e804f0c334162d71db7e2f77ded">llvm::Automaton&lt; ActionT &gt;::Automaton</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#aa2620d2287c9bf8cd15da84914af65e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ActionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Automaton&lt; ActionT &gt;::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ActionT &amp; A)</td>
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

<p>Transition the automaton based on input symbol A.</p>


<p>Return true if the automaton transitioned to a valid state, false if the automaton transitioned to an invalid state.</p>


<p>If this function returns false, all methods are undefined until <a href="#a30f80f4c7e00f9a31b9d6e6221805b4d">reset()</a> is called.</p>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### canAdd() {#a8b955bf418dc9539b07a58a6e94ec638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ActionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Automaton&lt; ActionT &gt;::canAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ActionT &amp; A)</td>
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

<p>Return true if the automaton can be transitioned based on input symbol A.</p>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### enableTranscription() {#ab475bbd3819025a90bd009e18988bb40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ActionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Automaton&lt; ActionT &gt;::enableTranscription (bool Enable=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Enable or disable transcription.</p>


<p>Transcription is only available if TranscriptionTable was provided to the constructor.</p>


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a>.</p>

</div>
</div>

### getNfaPaths() {#ad6fe99d549af75e18cd1e383e70c5beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ActionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; NfaPath &gt; llvm::Automaton&lt; ActionT &gt;::getNfaPaths ()</td>
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

<p>Obtain a set of possible paths through the input nondeterministic automaton that could be obtained from the sequence of input actions presented to this deterministic automaton.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### reset() {#a30f80f4c7e00f9a31b9d6e6221805b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ActionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Automaton&lt; ActionT &gt;::reset ()</td>
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

<p>Reset the automaton to its initial state.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### M {#aa83ee188c66f74ed78d5eb6b0e2b7e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ActionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;MapTy&gt; llvm::Automaton&lt; ActionT &gt;::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>

</div>
</div>

### State {#a4775b526d6e6e28d07266cb148732f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ActionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::Automaton&lt; ActionT &gt;::State = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The initial DFA state is 1.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>

</div>
</div>

### Transcribe {#aca89c3fcad786aea10404e4c6b9734e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ActionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Automaton&lt; ActionT &gt;::Transcribe</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if we should transcribe and false if not (even if Transcriber is defined).</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>

</div>
</div>

### Transcriber {#a863c0781f406ba2bf7f2d79472b2d0c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ActionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;internal::NfaTranscriber&gt; llvm::Automaton&lt; ActionT &gt;::Transcriber</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An optional transcription object.</p>


<p>This uses much more state than simply traversing the DFA for acceptance, so is heap allocated.</p>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/automaton-h">Automaton.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
