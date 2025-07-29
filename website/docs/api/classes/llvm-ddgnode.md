---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ddgnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DDGNode` Class

<p>Data <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> Graph <a href="/web-llvm/docs/api/classes/node">Node</a> The graph can represent the following types of nodes: <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DDGNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">llvm/Analysis/DDG.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dgnode">DGNode&lt;NodeType, EdgeType&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represent a node in the directed graph. <a href="/web-llvm/docs/api/classes/llvm/dgnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/piblockddgnode">PiBlockDDGNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subclass of <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> representing a pi-block. <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rootddgnode">RootDDGNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subclass of <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> representing the root node of the graph. <a href="/web-llvm/docs/api/classes/llvm/rootddgnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simpleddgnode">SimpleDDGNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subclass of <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> representing single or multi-instruction nodes. <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8794d8cd663b73e93738b48ad9e1579d">InstructionListType</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeKind { <a href="#a9e62e0231f8734aef5117531a8bd71aa">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac99ab0fd850d6f478f99517938097685">DDGNode</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa78e2475935e977048f0e725e05d4e61">DDGNode</a> (const NodeKind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e38729bad92e0a8ee0ee5d216f79dc3">DDGNode</a> (const DDGNode &amp;N)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50418bd65b9095d0414334bafaef3f6d">DDGNode</a> (DDGNode &amp;&amp;N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb1a8b5472ed74c90fcdffa8c3e95cfb">~DDGNode</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accdf63db7987e2c51befc218dbf23c13">operator=</a> (const DDGNode &amp;N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a294539478d1eb721ea18ba41f97653fb">operator=</a> (DDGNode &amp;&amp;N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9e62e0231f8734aef5117531a8bd71aa">NodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987eb1fb9e730e3a841b43852e4b42b7">getKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Getter for the kind of this node. <a href="#a987eb1fb9e730e3a841b43852e4b42b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af91d9f50a649787e882b7383c7e997d3">collectInstructions</a> (llvm::function_ref&lt; bool(Instruction *)&gt; const &amp;Pred, InstructionListType &amp;IList) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect a list of instructions, in <span class="doxyComputerOutput">IList</span>, for which predicate <span class="doxyComputerOutput">Pred</span> evaluates to true when iterating over instructions of this node. <a href="#af91d9f50a649787e882b7383c7e997d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29667168c1b5042771a8386cd883e87">setKind</a> (NodeKind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setter for the kind of this node. <a href="#ac29667168c1b5042771a8386cd883e87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9e62e0231f8734aef5117531a8bd71aa">NodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308b6850a4bebc4648581634529616e3">Kind</a></td>
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

<p>Data <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> Graph <a href="/web-llvm/docs/api/classes/node">Node</a> The graph can represent the following types of nodes:</p>


<ol class="doxyList" type="1">
<li>Single instruction node containing just one instruction.</li>
<li>Multiple instruction node where two or more instructions from the same basic block are merged into one node.</li>
<li>Pi-block node which is a group of other DDG nodes that are part of a strongly-connected component of the graph. A pi-block node contains more than one single or multiple instruction nodes. The root node cannot be part of a pi-block.</li>
<li>Root node is a special node that connects to all components such that there is always a path from it to any node in the graph.</li>
</ol>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### InstructionListType {#a8794d8cd663b73e93738b48ad9e1579d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DDGNode::InstructionListType =  SmallVectorImpl&lt;Instruction *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### NodeKind {#a9e62e0231f8734aef5117531a8bd71aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DDGNode::NodeKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unknown<a id="a9e62e0231f8734aef5117531a8bd71aaa88183b946cc5f0e8c96b2e66e1c74a7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SingleInstruction<a id="a9e62e0231f8734aef5117531a8bd71aaa759b1d3fabad8b1dc73156838022ef18"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MultiInstruction<a id="a9e62e0231f8734aef5117531a8bd71aaa3610ec110265e7aee3bbd0ed7d3b3f2d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PiBlock<a id="a9e62e0231f8734aef5117531a8bd71aaa1051cf7d554575e3bd3f8099929b8f98"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Root<a id="a9e62e0231f8734aef5117531a8bd71aaafa03eb688ad8aa1db593d33dabd89bad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DDGNode() {#ac99ab0fd850d6f478f99517938097685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DDGNode::DDGNode ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#ab150d005f95305f5a7a9b8e4dafba5c1">llvm::PiBlockDDGNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/rootddgnode/#a57ed505e0c156e8381481d8b87354a14">llvm::RootDDGNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a4e7421b58370c9e1d947644fff1c54c2">llvm::SimpleDDGNode::classof</a>, <a href="#af91d9f50a649787e882b7383c7e997d3">collectInstructions</a>, <a href="#a4e38729bad92e0a8ee0ee5d216f79dc3">DDGNode</a>, <a href="#a50418bd65b9095d0414334bafaef3f6d">DDGNode</a>, <a href="#accdf63db7987e2c51befc218dbf23c13">operator=</a>, <a href="#a294539478d1eb721ea18ba41f97653fb">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#addeddd9f90516c98c3cd9dc945d46377">llvm::PiBlockDDGNode::PiBlockDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#a92fb1b668553a71e9614ce16752429b3">llvm::PiBlockDDGNode::PiBlockDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#adce32ebae1d8ec671b813c8ed69c7e95">llvm::PiBlockDDGNode::PiBlockDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/rootddgnode/#a10399d1b55204e327ac572d857d1d723">llvm::RootDDGNode::RootDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/rootddgnode/#ae091c0615ac8b3a516724b5c46d83fd5">llvm::RootDDGNode::RootDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a6d07b91e9c9cf1265790ca3d94682f9f">llvm::SimpleDDGNode::SimpleDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#ac57f354449321edf17cca182c6cb8272">llvm::SimpleDDGNode::SimpleDDGNode</a> and <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a14413e4111fa6738de29e2a7e1d8111b">llvm::SimpleDDGNode::SimpleDDGNode</a>.</p>

</div>
</div>

### DDGNode() {#aa78e2475935e977048f0e725e05d4e61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DDGNode::DDGNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a9e62e0231f8734aef5117531a8bd71aa">NodeKind</a> K)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>

</div>
</div>

### DDGNode() {#a4e38729bad92e0a8ee0ee5d216f79dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DDGNode::DDGNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="#ac99ab0fd850d6f478f99517938097685">DDGNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### DDGNode() {#a50418bd65b9095d0414334bafaef3f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DDGNode::DDGNode (<a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp;&amp; N)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="#ac99ab0fd850d6f478f99517938097685">DDGNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DDGNode() {#acb1a8b5472ed74c90fcdffa8c3e95cfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DDGNode::~DDGNode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#accdf63db7987e2c51befc218dbf23c13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DDGNode &amp; llvm::DDGNode::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; N)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="#ac99ab0fd850d6f478f99517938097685">DDGNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/dgnode/#a16f8c40b391815643da5e7ac016241a2">llvm::DGNode&lt; NodeType, EdgeType &gt;::operator=</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#a1866bf2b3eb3ee1bf9958a0d25346080">llvm::PiBlockDDGNode::operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a48e9864977966d2bef1d8e2d5217452f">llvm::SimpleDDGNode::operator=</a>.</p>

</div>
</div>

### operator=() {#a294539478d1eb721ea18ba41f97653fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DDGNode &amp; llvm::DDGNode::operator= (<a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp;&amp; N)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="#ac99ab0fd850d6f478f99517938097685">DDGNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/dgnode/#a16f8c40b391815643da5e7ac016241a2">llvm::DGNode&lt; NodeType, EdgeType &gt;::operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### collectInstructions() {#af91d9f50a649787e882b7383c7e997d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DDGNode::collectInstructions (<a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *)&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Pred, <a href="#a8794d8cd663b73e93738b48ad9e1579d">InstructionListType</a> &amp; IList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect a list of instructions, in <span class="doxyComputerOutput">IList</span>, for which predicate <span class="doxyComputerOutput">Pred</span> evaluates to true when iterating over instructions of this node.</p>


<p>Return true if at least one instruction was collected, and false otherwise.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp">DDG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac99ab0fd850d6f478f99517938097685">DDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getKind() {#a987eb1fb9e730e3a841b43852e4b42b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeKind llvm::DDGNode::getKind ()</td>
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

<p>Getter for the kind of this node.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#addeddd9f90516c98c3cd9dc945d46377">llvm::PiBlockDDGNode::PiBlockDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#adce32ebae1d8ec671b813c8ed69c7e95">llvm::PiBlockDDGNode::PiBlockDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a6d07b91e9c9cf1265790ca3d94682f9f">llvm::SimpleDDGNode::SimpleDDGNode</a> and <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a14413e4111fa6738de29e2a7e1d8111b">llvm::SimpleDDGNode::SimpleDDGNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### setKind() {#ac29667168c1b5042771a8386cd883e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DDGNode::setKind (<a href="#a9e62e0231f8734aef5117531a8bd71aa">NodeKind</a> K)</td>
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

<p>Setter for the kind of this node.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#a308b6850a4bebc4648581634529616e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeKind llvm::DDGNode::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp">DDG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
