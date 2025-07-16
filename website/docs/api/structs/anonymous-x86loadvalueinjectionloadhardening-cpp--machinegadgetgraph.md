---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-x86loadvalueinjectionloadhardening-cpp-/machinegadgetgraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MachineGadgetGraph` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablegraph">ImmutableGraph&lt;NodeValueT, EdgeValueT&gt;</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a707296fe8af03c38e966aa534c1e6d2d">GraphT</a> = <a href="/web-llvm/docs/api/classes/llvm/immutablegraph">ImmutableGraph</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, int &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a694b90ecd945bb15674c6d2365b815">Node</a> = typename GraphT::Node</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c90309be0c4178e510acc6cfd2d3cf7">Edge</a> = typename GraphT::Edge</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeefb7a4c3ff6ccb7652ef4ab9f964956">size_type</a> = typename <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/#a6000637a017edb428a4b49d690351e42">GraphT::size_type</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a360c3c9b038c24a6b36eff6bdadc63fb">MachineGadgetGraph</a> (std::unique_ptr&lt; Node[]&gt; Nodes, std::unique_ptr&lt; Edge[]&gt; Edges, size_type NodesSize, size_type EdgesSize, int NumFences=0, int NumGadgets=0)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae23df5cedbb4f37f2cfcaeab7ca39dcd">NumFences</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ff975663a228a1a6e8ceba7f62adb8b">NumGadgets</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcd1c9400c9fb71f6417dfaefb71c6c6">isCFGEdge</a> (const Edge &amp;E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72d45b3ad4bd84e88d5792e119e858e0">isGadgetEdge</a> (const Edge &amp;E)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7e9b5bd0e036cea5be8be26647433d6">GadgetEdgeSentinel</a> = -1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba926a6272cdbea58acdefc4a9f8cb62">ArgNodeSentinel</a> = nullptr</td>
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


<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Edge {#a3c90309be0c4178e510acc6cfd2d3cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph::Edge =  typename GraphT::Edge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>

</div>
</div>

### GraphT {#a707296fe8af03c38e966aa534c1e6d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph::GraphT =  ImmutableGraph&lt;MachineInstr *, int&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>

</div>
</div>

### Node {#a5a694b90ecd945bb15674c6d2365b815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph::Node =  typename GraphT::Node</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>

</div>
</div>

### size\_type {#aeefb7a4c3ff6ccb7652ef4ab9f964956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph::size_type =  typename GraphT::size_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineGadgetGraph() {#a360c3c9b038c24a6b36eff6bdadc63fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph::MachineGadgetGraph (std::unique_ptr&lt; <a href="#a5a694b90ecd945bb15674c6d2365b815">Node</a>[]&gt; Nodes, std::unique_ptr&lt; <a href="#a3c90309be0c4178e510acc6cfd2d3cf7">Edge</a>[]&gt; Edges, <a href="#aeefb7a4c3ff6ccb7652ef4ab9f964956">size_type</a> NodesSize, <a href="#aeefb7a4c3ff6ccb7652ef4ab9f964956">size_type</a> EdgesSize, int NumFences=0, int NumGadgets=0)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#ae23df5cedbb4f37f2cfcaeab7ca39dcd">NumFences</a> and <a href="#a8ff975663a228a1a6e8ceba7f62adb8b">NumGadgets</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### NumFences {#ae23df5cedbb4f37f2cfcaeab7ca39dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph::NumFences</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<p>Referenced by <a href="#a360c3c9b038c24a6b36eff6bdadc63fb">MachineGadgetGraph</a>.</p>

</div>
</div>

### NumGadgets {#a8ff975663a228a1a6e8ceba7f62adb8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph::NumGadgets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<p>Referenced by <a href="#a360c3c9b038c24a6b36eff6bdadc63fb">MachineGadgetGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isCFGEdge() {#adcd1c9400c9fb71f6417dfaefb71c6c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph::isCFGEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c90309be0c4178e510acc6cfd2d3cf7">Edge</a> &amp; E)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<p>Reference <a href="#ac7e9b5bd0e036cea5be8be26647433d6">GadgetEdgeSentinel</a>.</p>

</div>
</div>

### isGadgetEdge() {#a72d45b3ad4bd84e88d5792e119e858e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86LoadValueInjectionLoadHardening.cpp}::MachineGadgetGraph::isGadgetEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c90309be0c4178e510acc6cfd2d3cf7">Edge</a> &amp; E)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<p>Reference <a href="#ac7e9b5bd0e036cea5be8be26647433d6">GadgetEdgeSentinel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ArgNodeSentinel {#aba926a6272cdbea58acdefc4a9f8cb62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * MachineGadgetGraph::ArgNodeSentinel = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-6d84867e0ca5367d344863bb152df797/#a3a02e36f305ceaebb8f7567360f1861b">llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::getNodeAttributes</a> and <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-6d84867e0ca5367d344863bb152df797/#a51fde136cfecc90dfede7499db803192">llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::getNodeLabel</a>.</p>

</div>
</div>

### GadgetEdgeSentinel {#ac7e9b5bd0e036cea5be8be26647433d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachineGadgetGraph::GadgetEdgeSentinel = -1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a>.</p>


<p>Referenced by <a href="#adcd1c9400c9fb71f6417dfaefb71c6c6">isCFGEdge</a> and <a href="#a72d45b3ad4bd84e88d5792e119e858e0">isGadgetEdge</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp">X86LoadValueInjectionLoadHardening.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
