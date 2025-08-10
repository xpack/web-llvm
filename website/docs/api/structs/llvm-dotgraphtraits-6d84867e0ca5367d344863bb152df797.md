---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dotgraphtraits-6d84867e0ca5367d344863bb152df797
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DOTGraphTraits` Struct Template



## Declaration

<div class="doxyDeclaration">
struct llvm::DOTGraphTraits&lt;MachineGadgetGraph *&gt; { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits">DefaultDOTGraphTraits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits">DefaultDOTGraphTraits</a> - This class provides the default implementations of all of the <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits">DOTGraphTraits</a> methods. <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f49ef4df1059829cb9069e7c095acc2">GraphType</a> = MachineGadgetGraph</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cc16e650ce0dbe93a733c1b11f6a618">Traits</a> = <a href="/web-llvm/docs/api/structs/llvm/graphtraits">llvm::GraphTraits</a>&lt; <a href="#a5f49ef4df1059829cb9069e7c095acc2">GraphType</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1c005a2d0f7c4eb2bbdf284b59323a">NodeRef</a> = typename <a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">Traits::NodeRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9ba7375bbc566bdaa4d01f862fb740">EdgeRef</a> = typename Traits::EdgeRef</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e606b7453007349db513ba8353387de">ChildIteratorType</a> = typename Traits::ChildIteratorType</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7233c81d30abb041973c212e7eb1f225">ChildEdgeIteratorType</a> = typename Traits::ChildEdgeIteratorType</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaf8943dec79aef244f9c29e40a33e71">DOTGraphTraits</a> (bool IsSimple=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51fde136cfecc90dfede7499db803192">getNodeLabel</a> (NodeRef Node, GraphType *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a02e36f305ceaebb8f7567360f1861b">getNodeAttributes</a> (NodeRef Node, GraphType *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f6e5498d4892a70ee5bba56c70c446">getEdgeAttributes</a> (NodeRef, ChildIteratorType E, GraphType *)</td>
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


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ChildEdgeIteratorType {#a7233c81d30abb041973c212e7eb1f225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::ChildEdgeIteratorType =  typename Traits::ChildEdgeIteratorType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>

</div>
</div>

### ChildIteratorType {#a4e606b7453007349db513ba8353387de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::ChildIteratorType =  typename Traits::ChildIteratorType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>

</div>
</div>

### EdgeRef {#a6c9ba7375bbc566bdaa4d01f862fb740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::EdgeRef =  typename Traits::EdgeRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>

</div>
</div>

### GraphType {#a5f49ef4df1059829cb9069e7c095acc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::GraphType =  MachineGadgetGraph</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>

</div>
</div>

### NodeRef {#a2e1c005a2d0f7c4eb2bbdf284b59323a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::NodeRef =  typename Traits::NodeRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>

</div>
</div>

### Traits {#a9cc16e650ce0dbe93a733c1b11f6a618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::Traits =  llvm::GraphTraits&lt;GraphType *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DOTGraphTraits() {#afaf8943dec79aef244f9c29e40a33e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::DOTGraphTraits (bool IsSimple=false)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#a8a0585a182245d87b224f4a26a41cf16">llvm::DefaultDOTGraphTraits::DefaultDOTGraphTraits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNodeLabel() {#a51fde136cfecc90dfede7499db803192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::getNodeLabel (<a href="#a2e1c005a2d0f7c4eb2bbdf284b59323a">NodeRef</a> Node, <a href="#a5f49ef4df1059829cb9069e7c095acc2">GraphType</a> *)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-x86loadvalueinjectionloadhardening-cpp-/machinegadgetgraph/#aba926a6272cdbea58acdefc4a9f8cb62">anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph::ArgNodeSentinel</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEdgeAttributes() {#a53f6e5498d4892a70ee5bba56c70c446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::getEdgeAttributes (<a href="#a2e1c005a2d0f7c4eb2bbdf284b59323a">NodeRef</a>, <a href="#a4e606b7453007349db513ba8353387de">ChildIteratorType</a> E, <a href="#a5f49ef4df1059829cb9069e7c095acc2">GraphType</a> *)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>

</div>
</div>

### getNodeAttributes() {#a3a02e36f305ceaebb8f7567360f1861b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::getNodeAttributes (<a href="#a2e1c005a2d0f7c4eb2bbdf284b59323a">NodeRef</a> Node, <a href="#a5f49ef4df1059829cb9069e7c095acc2">GraphType</a> *)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-x86loadvalueinjectionloadhardening-cpp-/machinegadgetgraph/#aba926a6272cdbea58acdefc4a9f8cb62">anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph::ArgNodeSentinel</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
