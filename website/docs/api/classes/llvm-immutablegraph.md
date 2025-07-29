---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/immutablegraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ImmutableGraph` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename NodeValueT, typename EdgeValueT&gt;
class llvm::ImmutableGraph&lt;NodeValueT, EdgeValueT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">Target/X86/ImmutableGraph.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9ed10fc044a933a98c202e19765b1725">node_value_type</a> = NodeValueT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e1671fb5d9cbaaecf5660bdb8fee37a">edge_value_type</a> = EdgeValueT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6000637a017edb428a4b49d690351e42">size_type</a> = int</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a225f24405416d2f3a8340754a76492cf">Traits</a> = <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/immutablegraph">ImmutableGraph</a>&lt; NodeValueT, EdgeValueT &gt; * &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a02a1080fc730481b99642f5e2618b504">ImmutableGraphBuilder</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac55c6f9357e44ad24ea5f40b7975ebd0">ImmutableGraph</a> (std::unique_ptr&lt; Node[]&gt; Nodes, std::unique_ptr&lt; Edge[]&gt; Edges, size_type NodesSize, size_type EdgesSize)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4ce956359bfd89160f0c591d1cc4a37d">ImmutableGraph</a> (const ImmutableGraph &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5dee8f7accdfa3bbcac4c7467d31edda">ImmutableGraph</a> (ImmutableGraph &amp;&amp;)=delete</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablegraph">ImmutableGraph</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a60c60de0c493680bee085825d8869c27">operator=</a> (const ImmutableGraph &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablegraph">ImmutableGraph</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b416ee524ef298b3da06849c4561e4b">operator=</a> (ImmutableGraph &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af69d301a9a257d24a6b0db76ea19af30">nodes</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/node">Node</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0a36278d58291d94abb79e3c42b0da80">nodes_begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a24d580253e70f01bd7316f249f17482f">nodes_end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a12f4d7d345f1f0d240d4a049b1f80636">edges</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edge">Edge</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a38fd04606f46bf4f47a3cde52b472ef6">edges_begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f470a29896f1b82aa0723b9eae24e34">edges_end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a6000637a017edb428a4b49d690351e42">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a39355daa70666da4e5e3252e65d76ff4">nodes_size</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a6000637a017edb428a4b49d690351e42">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a69a93e1c3ffb0fd8e95ca056f9b10760">edges_size</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a6000637a017edb428a4b49d690351e42">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a41c7e9ffbcfe3525fa5e59747d7ea6cd">getNodeIndex</a> (const Node &amp;N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a6000637a017edb428a4b49d690351e42">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46cb265b0435863520aa2cd4666bda41">getEdgeIndex</a> (const Edge &amp;E) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/node">Node</a>[]&gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a15f88eb2bc0a59f8dd6bb709cf90549f">Nodes</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edge">Edge</a>[]&gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8cafbb0f6be60253d7fb14e0791b2db">Edges</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a6000637a017edb428a4b49d690351e42">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9ef53cc0aa0a5ae188016f2170344d49">NodesSize</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeValueT, typename EdgeValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a6000637a017edb428a4b49d690351e42">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4bc2e2ca5abb01af95834c725b64c67b">EdgesSize</a></td>
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


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### edge\_value\_type {#a8e1671fb5d9cbaaecf5660bdb8fee37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::edge_value_type =  EdgeValueT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### node\_value\_type {#a9ed10fc044a933a98c202e19765b1725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::node_value_type =  NodeValueT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### size\_type {#a6000637a017edb428a4b49d690351e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::size_type =  int</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### Traits {#a225f24405416d2f3a8340754a76492cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::Traits =  GraphTraits&lt;ImmutableGraph&lt;NodeValueT, EdgeValueT&gt; *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ImmutableGraphBuilder {#a02a1080fc730481b99642f5e2618b504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/immutablegraphbuilder">ImmutableGraphBuilder</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### ImmutableGraph() {#ac55c6f9357e44ad24ea5f40b7975ebd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::ImmutableGraph (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/node">Node</a>[]&gt; Nodes, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edge">Edge</a>[]&gt; Edges, <a href="#a6000637a017edb428a4b49d690351e42">size_type</a> NodesSize, <a href="#a6000637a017edb428a4b49d690351e42">size_type</a> EdgesSize)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edgeset/#a39dad974eb75445be1bd3f2b2c1f3857">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::EdgeSet</a> and <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset/#a71c094f9dabd89f5ff79c1dbabc70660">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::NodeSet</a>.</p>

</div>
</div>

### ImmutableGraph() {#a4ce956359bfd89160f0c591d1cc4a37d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::ImmutableGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph">ImmutableGraph</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### ImmutableGraph() {#a5dee8f7accdfa3bbcac4c7467d31edda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::ImmutableGraph (<a href="/web-llvm/docs/api/classes/llvm/immutablegraph">ImmutableGraph</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#a60c60de0c493680bee085825d8869c27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableGraph &amp; llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph">ImmutableGraph</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### operator=() {#a0b416ee524ef298b3da06849c4561e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableGraph &amp; llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/immutablegraph">ImmutableGraph</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### edges() {#a12f4d7d345f1f0d240d4a049b1f80636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Edge &gt; llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::edges ()</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Referenced by <a href="#a38fd04606f46bf4f47a3cde52b472ef6">llvm::ImmutableGraph&lt; MachineInstr *, int &gt;::edges_begin</a> and <a href="#a5f470a29896f1b82aa0723b9eae24e34">llvm::ImmutableGraph&lt; MachineInstr *, int &gt;::edges_end</a>.</p>

</div>
</div>

### edges\_begin() {#a38fd04606f46bf4f47a3cde52b472ef6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Edge * llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::edges_begin ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Referenced by <a href="#a46cb265b0435863520aa2cd4666bda41">llvm::ImmutableGraph&lt; MachineInstr *, int &gt;::getEdgeIndex</a>.</p>

</div>
</div>

### edges\_end() {#a5f470a29896f1b82aa0723b9eae24e34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Edge * llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::edges_end ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### edges\_size() {#a69a93e1c3ffb0fd8e95ca056f9b10760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::edges_size ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edgeset/#a39dad974eb75445be1bd3f2b2c1f3857">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::EdgeSet</a>.</p>

</div>
</div>

### getEdgeIndex() {#a46cb265b0435863520aa2cd4666bda41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::getEdgeIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edge">Edge</a> &amp; E)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### getNodeIndex() {#a41c7e9ffbcfe3525fa5e59747d7ea6cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::getNodeIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/node">Node</a> &amp; N)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### nodes() {#af69d301a9a257d24a6b0db76ea19af30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Node &gt; llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::nodes ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Referenced by <a href="#a0a36278d58291d94abb79e3c42b0da80">llvm::ImmutableGraph&lt; MachineInstr *, int &gt;::nodes_begin</a> and <a href="#a24d580253e70f01bd7316f249f17482f">llvm::ImmutableGraph&lt; MachineInstr *, int &gt;::nodes_end</a>.</p>

</div>
</div>

### nodes\_begin() {#a0a36278d58291d94abb79e3c42b0da80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Node * llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::nodes_begin ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Referenced by <a href="#a41c7e9ffbcfe3525fa5e59747d7ea6cd">llvm::ImmutableGraph&lt; MachineInstr *, int &gt;::getNodeIndex</a>.</p>

</div>
</div>

### nodes\_end() {#a24d580253e70f01bd7316f249f17482f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Node * llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::nodes_end ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### nodes\_size() {#a39355daa70666da4e5e3252e65d76ff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::nodes_size ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset/#a71c094f9dabd89f5ff79c1dbabc70660">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::NodeSet</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Edges {#ac8cafbb0f6be60253d7fb14e0791b2db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Edge[]&gt; llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::Edges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### EdgesSize {#a4bc2e2ca5abb01af95834c725b64c67b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgesSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### Nodes {#a15f88eb2bc0a59f8dd6bb709cf90549f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Node[]&gt; llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::Nodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### NodesSize {#a9ef53cc0aa0a5ae188016f2170344d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeValueT, typename EdgeValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodesSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
