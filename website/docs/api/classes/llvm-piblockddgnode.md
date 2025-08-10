---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/piblockddgnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PiBlockDDGNode` Class

<p>Subclass of <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> representing a pi-block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PiBlockDDGNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">llvm/Analysis/DDG.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data <a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> Graph <a href="/web-llvm/docs/api/classes/node">Node</a> The graph can represent the following types of nodes: <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4c4b562d85a426f90c8ebdb70c14c87">PiNodeList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> *, 4 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a495ca4b0fce6fb1dedbdbe171f74ce7c">PiBlockDDGNode</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92fb1b668553a71e9614ce16752429b3">PiBlockDDGNode</a> (const PiNodeList &amp;List)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addeddd9f90516c98c3cd9dc945d46377">PiBlockDDGNode</a> (const PiBlockDDGNode &amp;N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adce32ebae1d8ec671b813c8ed69c7e95">PiBlockDDGNode</a> (PiBlockDDGNode &amp;&amp;N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8210b30578f0a4344ab58cc4a5091a7">~PiBlockDDGNode</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/piblockddgnode">PiBlockDDGNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb73a3b9c62727e383e93d0bac6df38b">operator=</a> (const PiBlockDDGNode &amp;N)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/piblockddgnode">PiBlockDDGNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1866bf2b3eb3ee1bf9958a0d25346080">operator=</a> (PiBlockDDGNode &amp;&amp;N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae4c4b562d85a426f90c8ebdb70c14c87">PiNodeList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a8e9d9720b09df952d99618112104fc">getNodes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the list of nodes in this pi-block. <a href="#a4a8e9d9720b09df952d99618112104fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae4c4b562d85a426f90c8ebdb70c14c87">PiNodeList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae626c237f9ea39bef42ea45ca4dde8be">getNodes</a> ()</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae4c4b562d85a426f90c8ebdb70c14c87">PiNodeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa38545a088c44fc4bb266a8dd2cb90">NodeList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of nodes in this pi-block. <a href="#a6aa38545a088c44fc4bb266a8dd2cb90">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab150d005f95305f5a7a9b8e4dafba5c1">classof</a> (const DDGNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Define classof to be able to use isa&lt;&gt;, cast&lt;&gt;, dyn_cast&lt;&gt;, etc. <a href="#ab150d005f95305f5a7a9b8e4dafba5c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Subclass of <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> representing a pi-block.</p>


<p>A pi-block represents a group of DDG nodes that are part of a strongly-connected component of the graph. Replacing all the SCCs with pi-blocks results in an acyclic representation of the DDG. For example if we have: {a -&gt; b}, {b -&gt; c, d}, {c -&gt; a} the cycle a -&gt; b -&gt; c -&gt; a is abstracted into a pi-block "p" as follows: {p -&gt; d} with "p" containing: {a -&gt; b}, {b -&gt; c}, {c -&gt; a}</p>


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### PiNodeList {#ae4c4b562d85a426f90c8ebdb70c14c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PiBlockDDGNode::PiNodeList =  SmallVector&lt;DDGNode *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PiBlockDDGNode() {#a495ca4b0fce6fb1dedbdbe171f74ce7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PiBlockDDGNode::PiBlockDDGNode ()</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a495ca4b0fce6fb1dedbdbe171f74ce7c">PiBlockDDGNode</a>.</p>


<p>Referenced by <a href="#ae626c237f9ea39bef42ea45ca4dde8be">getNodes</a>, <a href="#acb73a3b9c62727e383e93d0bac6df38b">operator=</a>, <a href="#a1866bf2b3eb3ee1bf9958a0d25346080">operator=</a>, <a href="#a495ca4b0fce6fb1dedbdbe171f74ce7c">PiBlockDDGNode</a>, <a href="#addeddd9f90516c98c3cd9dc945d46377">PiBlockDDGNode</a> and <a href="#adce32ebae1d8ec671b813c8ed69c7e95">PiBlockDDGNode</a>.</p>

</div>
</div>

### PiBlockDDGNode() {#a92fb1b668553a71e9614ce16752429b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PiBlockDDGNode::PiBlockDDGNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae4c4b562d85a426f90c8ebdb70c14c87">PiNodeList</a> &amp; List)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp">DDG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#ac99ab0fd850d6f478f99517938097685">llvm::DDGNode::DDGNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#a9e62e0231f8734aef5117531a8bd71aaa1051cf7d554575e3bd3f8099929b8f98">llvm::DDGNode::PiBlock</a>.</p>

</div>
</div>

### PiBlockDDGNode() {#addeddd9f90516c98c3cd9dc945d46377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PiBlockDDGNode::PiBlockDDGNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode">PiBlockDDGNode</a> &amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp">DDG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#ac99ab0fd850d6f478f99517938097685">llvm::DDGNode::DDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#a987eb1fb9e730e3a841b43852e4b42b7">llvm::DDGNode::getKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#a9e62e0231f8734aef5117531a8bd71aaa1051cf7d554575e3bd3f8099929b8f98">llvm::DDGNode::PiBlock</a> and <a href="#a495ca4b0fce6fb1dedbdbe171f74ce7c">PiBlockDDGNode</a>.</p>

</div>
</div>

### PiBlockDDGNode() {#adce32ebae1d8ec671b813c8ed69c7e95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PiBlockDDGNode::PiBlockDDGNode (<a href="/web-llvm/docs/api/classes/llvm/piblockddgnode">PiBlockDDGNode</a> &amp;&amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp">DDG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#ac99ab0fd850d6f478f99517938097685">llvm::DDGNode::DDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#a987eb1fb9e730e3a841b43852e4b42b7">llvm::DDGNode::getKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#a9e62e0231f8734aef5117531a8bd71aaa1051cf7d554575e3bd3f8099929b8f98">llvm::DDGNode::PiBlock</a> and <a href="#a495ca4b0fce6fb1dedbdbe171f74ce7c">PiBlockDDGNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PiBlockDDGNode() {#ab8210b30578f0a4344ab58cc4a5091a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PiBlockDDGNode::~PiBlockDDGNode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp">DDG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#acb73a3b9c62727e383e93d0bac6df38b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PiBlockDDGNode &amp; llvm::PiBlockDDGNode::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode">PiBlockDDGNode</a> &amp; N)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a495ca4b0fce6fb1dedbdbe171f74ce7c">PiBlockDDGNode</a>.</p>

</div>
</div>

### operator=() {#a1866bf2b3eb3ee1bf9958a0d25346080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PiBlockDDGNode &amp; llvm::PiBlockDDGNode::operator= (<a href="/web-llvm/docs/api/classes/llvm/piblockddgnode">PiBlockDDGNode</a> &amp;&amp; N)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#accdf63db7987e2c51befc218dbf23c13">llvm::DDGNode::operator=</a> and <a href="#a495ca4b0fce6fb1dedbdbe171f74ce7c">PiBlockDDGNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNodes() {#a4a8e9d9720b09df952d99618112104fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PiNodeList &amp; llvm::PiBlockDDGNode::getNodes ()</td>
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

<p>Get the list of nodes in this pi-block.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getNodes() {#ae626c237f9ea39bef42ea45ca4dde8be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PiNodeList &amp; llvm::PiBlockDDGNode::getNodes ()</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>Reference <a href="#a495ca4b0fce6fb1dedbdbe171f74ce7c">PiBlockDDGNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NodeList {#a6aa38545a088c44fc4bb266a8dd2cb90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PiNodeList llvm::PiBlockDDGNode::NodeList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of nodes in this pi-block.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ab150d005f95305f5a7a9b8e4dafba5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PiBlockDDGNode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> * N)</td>
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

<p>Define classof to be able to use isa&lt;&gt;, cast&lt;&gt;, dyn_cast&lt;&gt;, etc.</p>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#ac99ab0fd850d6f478f99517938097685">llvm::DDGNode::DDGNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#a9e62e0231f8734aef5117531a8bd71aaa1051cf7d554575e3bd3f8099929b8f98">llvm::DDGNode::PiBlock</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
