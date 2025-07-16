---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/namedmdnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NamedMDNode` Class Reference

<p>A tuple of MDNodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::NamedMDNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac636c634045217771bcb260523d98860">op_iterator</a> = op_iterator_impl&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b1786ac1479e5fb494e485a0b5b2527">const_op_iterator</a> = op_iterator_impl&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt;</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f639900c480510650969df9c74d17d">Module</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00c7c817f5f0569525a7e8f905b01934">NamedMDNode</a> (const NamedMDNode &amp;)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9099d9f3b35e0e9ee8c9b3301300c7dd">NamedMDNode</a> (const Twine &amp;N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5787be1b8684e08792726bcd23d9831d">~NamedMDNode</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b8c6e263c8047823d8869cc27dd8008">eraseFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop all references and remove the node from parent module. <a href="#a7b8c6e263c8047823d8869cc27dd8008">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b7697fe1d38e9c8884d9a08b8be88e">dropAllReferences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all uses and clear node vector. <a href="#a65b7697fe1d38e9c8884d9a08b8be88e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2c0af191fb0d4aff661994b0d234e40">clearOperands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop all references to this node's operands. <a href="#ad2c0af191fb0d4aff661994b0d234e40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8578a0e0ed99d2daba95da926662a8d">getParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the module that holds this named metadata collection. <a href="#ae8578a0e0ed99d2daba95da926662a8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acedabe7e58f30ff70468957e71db7986">getParent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa24b566603d206b0e74bf63daf521078">getOperand</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acde8007e0e69969423e2de52343b702f">getNumOperands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae917c72e5b8e15491cd0dbdd44d818f2">addOperand</a> (MDNode *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a543df3cb1eda9d491a7822ef4216e3b1">setOperand</a> (unsigned I, MDNode *New)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e90645e97cbfe08194f0db4d0bdec88">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66312117826bfdbd0e36aef38081b9a4">print</a> (raw_ostream &amp;ROS, bool IsForDebug=false) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267435660ce6b53b9d83d84f8f257241">print</a> (raw_ostream &amp;ROS, ModuleSlotTracker &amp;MST, bool IsForDebug=false) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a367bddd00ba4d448572f39f59da07a14">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac636c634045217771bcb260523d98860">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab09c1670b19abdcee5462c8446fa2311">op_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac636c634045217771bcb260523d98860">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd5b0835b00d3b44fe2c6dbe625600a">op_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0b1786ac1479e5fb494e485a0b5b2527">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b78edfb8d62c0071abb638d18f2101">op_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0b1786ac1479e5fb494e485a0b5b2527">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f102e057dd1bbe3d9c8e7f686b4c35">op_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ac636c634045217771bcb260523d98860">op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc55e223d70c06a924fd5cb248052d9d">operands</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a0b1786ac1479e5fb494e485a0b5b2527">const_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7190f918e3e193eb9f40ff7b7c0e73">operands</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af946b43d301dc0956015c2c03b0527d3">setParent</a> (Module *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9622c23edb4f074adc72d4160f98275d">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4fff564bb7429f441c80ffa3b6c8a5">Parent</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad90c1c9d30e194eb9391f7cb880ea2f9">Operands</a></td>
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

<p>A tuple of MDNodes.</p>


<p>Despite its name, a <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> isn't itself an <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a>.</p>


<p>NamedMDNodes are named module-level entities that contain lists of MDNodes.</p>


<p>It is illegal for a <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> to appear as an operand of an <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a>.</p>


<p>Definition at line 1737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_op\_iterator {#a0b1786ac1479e5fb494e485a0b5b2527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::NamedMDNode::const_op_iterator =  op_iterator_impl&lt;const MDNode *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

### op\_iterator {#ac636c634045217771bcb260523d98860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::NamedMDNode::op_iterator =  op_iterator_impl&lt;MDNode *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LLVMContextImpl {#aa81f87de855d80e4275071841a7e0c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl">LLVMContextImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1738 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>


<p>Referenced by <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>

</div>
</div>

### Module {#a21f639900c480510650969df9c74d17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/module">Module</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>


<p>Referenced by <a href="#ae8578a0e0ed99d2daba95da926662a8d">getParent</a>, <a href="#acedabe7e58f30ff70468957e71db7986">getParent</a> and <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### NamedMDNode() {#a00c7c817f5f0569525a7e8f905b01934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::NamedMDNode::NamedMDNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> &amp;)</td>
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



<p>Definition at line 1795 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### NamedMDNode() {#a9099d9f3b35e0e9ee8c9b3301300c7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDNode::NamedMDNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~NamedMDNode() {#a5787be1b8684e08792726bcd23d9831d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDNode::~NamedMDNode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 1416 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="#a65b7697fe1d38e9c8884d9a08b8be88e">dropAllReferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a81e3dc463e57367ea1eeafe570110894">getNMDOps</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addOperand() {#ae917c72e5b8e15491cd0dbdd44d818f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NamedMDNode::addOperand (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 1431 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a81e3dc463e57367ea1eeafe570110894">getNMDOps</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#ae1b043855cc598a229a8389f9a116f74">anonymous{NVPTXCtorDtorLowering.cpp}::addKernelMetadata</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab371d6b308eb9772bdec63cf7a041407">llvm::CloneModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a36f7af99f64b66e158b210e4433a1aed">llvm::DIBuilder::createCompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acc290ce16055813d4ee68af4c8023a09">llvm::OpenMPIRBuilder::createOffloadEntriesAndInfoMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae744a53dbb2720e5678fb879156761e9">llvm::embedBufferInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eeb42cfad58d947c605b1e21376e0b7">llvm::emitAMDGPUPrintfCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a28b9ee98753ce0b4d46a48966e2b681f">emitDXILVersionTupleMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#aff40ddd6d0fc8a142d051bce619c2dee">emitShaderModelVersionMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a56e0b5e985245544c7a37011c9e19805">emitValidatorVersionMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a68d20206b060ac3ad19f416ed5a4899b">llvm::offloading::getOffloadingEntryInitializer</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#aefaf2c952edc95af7870970731295b45">anonymous{BitcodeReader.cpp}::BitcodeReader::materializeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a09a156bd41fe293ee8743b4beca76960">stripDeadDebugInfoImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a484621a748732e2f39e7a2a0058b3b07">llvm::stripDebugifyMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a457f42a32df73079ac4526c572a2d7fd">updateNVPTXMetadata</a>.</p>

</div>
</div>

### clearOperands() {#ad2c0af191fb0d4aff661994b0d234e40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NamedMDNode::clearOperands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drop all references to this node's operands.</p>

<p>Declaration at line 1804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 1440 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a81e3dc463e57367ea1eeafe570110894">getNMDOps</a>.</p>


<p>Referenced by <a href="#a65b7697fe1d38e9c8884d9a08b8be88e">dropAllReferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a56e0b5e985245544c7a37011c9e19805">emitValidatorVersionMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a09a156bd41fe293ee8743b4beca76960">stripDeadDebugInfoImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a484621a748732e2f39e7a2a0058b3b07">llvm::stripDebugifyMetadata</a>.</p>

</div>
</div>

### dropAllReferences() {#a65b7697fe1d38e9c8884d9a08b8be88e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::NamedMDNode::dropAllReferences ()</td>
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

<p>Remove all uses and clear node vector.</p>

<p>Definition at line 1802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#ad2c0af191fb0d4aff661994b0d234e40">clearOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/dxilupgrade-cpp/#a55a5c0652f51a63dc1ad0f386fe011f2">handleValVerMetadata</a> and <a href="#a5787be1b8684e08792726bcd23d9831d">~NamedMDNode</a>.</p>

</div>
</div>

### dump() {#a367bddd00ba4d448572f39f59da07a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void NamedMDNode::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 5334 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### eraseFromParent() {#a7b8c6e263c8047823d8869cc27dd8008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NamedMDNode::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drop all references and remove the node from parent module.</p>

<p>Declaration at line 1799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 1438 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/module/#a46d5a31c86f52f5b535586397efa5a21">llvm::Module::eraseNamedMetadata</a> and <a href="#ae8578a0e0ed99d2daba95da926662a8d">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-dxilprepare-cpp-/#aefd807d7db1488ed65a2ecb5e857349d">anonymous{DXILPrepare.cpp}::cleanModuleFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/dxilupgrade-cpp/#a55a5c0652f51a63dc1ad0f386fe011f2">handleValVerMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a484621a748732e2f39e7a2a0058b3b07">llvm::stripDebugifyMetadata</a>.</p>

</div>
</div>

### getName() {#a5e90645e97cbfe08194f0db4d0bdec88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef NamedMDNode::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 1442 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga638cf10ec868576e2a3be5a17d0ae39b">LLVMGetNamedMetadataName</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ac514ffc60e99e3e3d07b1b11973e2547">anonymous{AsmWriter.cpp}::AssemblyWriter::printNamedMDNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8564d7984f31fb685c319f454cc4f372">llvm::stripNonLineTableDebugInfo</a>.</p>

</div>
</div>

### getNumOperands() {#acde8007e0e69969423e2de52343b702f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned NamedMDNode::getNumOperands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1811 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 1421 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a81e3dc463e57367ea1eeafe570110894">getNMDOps</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a75955141a4289e3ff78d21aea406a6">llvm::cacheAnnotationFromMD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#aa39f65efac3a51f3001285439ea997be">anonymous{Debugify.cpp}::checkDebugifyMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eeb42cfad58d947c605b1e21376e0b7">llvm::emitAMDGPUPrintfCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a3275b7a3457510661d5af13a82bb48ca">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitModuleCommandLines</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#ae2c3c56fbe514f4a3ee837a4af0499a8">getHiPELiteral</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvmetadata-cpp/#a0593b71037c3b05d8ce0864feb95a5de">getOCLKernelArgAttribute</a>, <a href="#aa24b566603d206b0e74bf63daf521078">getOperand</a>, <a href="#a9fd5b0835b00d3b44fe2c6dbe625600a">op_end</a>, <a href="#a88f102e057dd1bbe3d9c8e7f686b4c35">op_end</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ac514ffc60e99e3e3d07b1b11973e2547">anonymous{AsmWriter.cpp}::AssemblyWriter::printNamedMDNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinecheckdebugify-cpp-/checkdebugmachinemodule/#a326b0f33afafa16b37d37f736e52bf5e">anonymous{MachineCheckDebugify.cpp}::CheckDebugMachineModule::runOnModule</a>, <a href="#a543df3cb1eda9d491a7822ef4216e3b1">setOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a484621a748732e2f39e7a2a0058b3b07">llvm::stripDebugifyMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a40c011ab750e2b4ea0d6b8076345cb0c">llvm::UpgradeModuleFlags</a>.</p>

</div>
</div>

### getOperand() {#aa24b566603d206b0e74bf63daf521078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * NamedMDNode::getOperand (unsigned i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 1425 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a81e3dc463e57367ea1eeafe570110894">getNMDOps</a>, <a href="#acde8007e0e69969423e2de52343b702f">getNumOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a75955141a4289e3ff78d21aea406a6">llvm::cacheAnnotationFromMD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#aa39f65efac3a51f3001285439ea997be">anonymous{Debugify.cpp}::checkDebugifyMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a3275b7a3457510661d5af13a82bb48ca">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitModuleCommandLines</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#ae2c3c56fbe514f4a3ee837a4af0499a8">getHiPELiteral</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvmetadata-cpp/#a0593b71037c3b05d8ce0864feb95a5de">getOCLKernelArgAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/dxilupgrade-cpp/#a55a5c0652f51a63dc1ad0f386fe011f2">handleValVerMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ac514ffc60e99e3e3d07b1b11973e2547">anonymous{AsmWriter.cpp}::AssemblyWriter::printNamedMDNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinecheckdebugify-cpp-/checkdebugmachinemodule/#a326b0f33afafa16b37d37f736e52bf5e">anonymous{MachineCheckDebugify.cpp}::CheckDebugMachineModule::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a40c011ab750e2b4ea0d6b8076345cb0c">llvm::UpgradeModuleFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a227ca4549b5e29e59345b6a9bb74e531">upgradeRetainReleaseMarker</a>.</p>

</div>
</div>

### getParent() {#ae8578a0e0ed99d2daba95da926662a8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * llvm::NamedMDNode::getParent ()</td>
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

<p>Get the module that holds this named metadata collection.</p>

<p>Definition at line 1807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>


<p>Referenced by <a href="#a7b8c6e263c8047823d8869cc27dd8008">eraseFromParent</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#gaacd234d81c636cdd202dd64dad371e1c">LLVMGetNextNamedMetadata</a> and <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga26be85891d4ed0c9b687b41d35b5c6e6">LLVMGetPreviousNamedMetadata</a>.</p>

</div>
</div>

### getParent() {#acedabe7e58f30ff70468957e71db7986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module * llvm::NamedMDNode::getParent ()</td>
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



<p>Definition at line 1808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>

</div>
</div>

### op\_begin() {#ab09c1670b19abdcee5462c8446fa2311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_iterator llvm::NamedMDNode::op_begin ()</td>
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



<p>Definition at line 1825 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="#adc55e223d70c06a924fd5cb248052d9d">operands</a> and <a href="#a9b7190f918e3e193eb9f40ff7b7c0e73">operands</a>.</p>

</div>
</div>

### op\_begin() {#a00b78edfb8d62c0071abb638d18f2101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::NamedMDNode::op_begin ()</td>
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



<p>Definition at line 1830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

### op\_end() {#a9fd5b0835b00d3b44fe2c6dbe625600a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_iterator llvm::NamedMDNode::op_end ()</td>
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



<p>Definition at line 1826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#acde8007e0e69969423e2de52343b702f">getNumOperands</a>.</p>


<p>Referenced by <a href="#adc55e223d70c06a924fd5cb248052d9d">operands</a> and <a href="#a9b7190f918e3e193eb9f40ff7b7c0e73">operands</a>.</p>

</div>
</div>

### op\_end() {#a88f102e057dd1bbe3d9c8e7f686b4c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::NamedMDNode::op_end ()</td>
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



<p>Definition at line 1831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#acde8007e0e69969423e2de52343b702f">getNumOperands</a>.</p>

</div>
</div>

### operands() {#adc55e223d70c06a924fd5cb248052d9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; op_iterator &gt; llvm::NamedMDNode::operands ()</td>
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



<p>Definition at line 1833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ab09c1670b19abdcee5462c8446fa2311">op_begin</a> and <a href="#a9fd5b0835b00d3b44fe2c6dbe625600a">op_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-crossdsocfi-cpp-/crossdsocfi/#ab29f15fad3f35ea8248e93e3dc805224">anonymous{CrossDSOCFI.cpp}::CrossDSOCFI::buildCFICheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a749d7f5580e6a5b6214d911bad2a0b36">getNVPTXMDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a2242b144e54fa6203dae5c5b27fff17c">llvm::OpenMPIRBuilder::loadOffloadInfoMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a484621a748732e2f39e7a2a0058b3b07">llvm::stripDebugifyMetadata</a>.</p>

</div>
</div>

### operands() {#a9b7190f918e3e193eb9f40ff7b7c0e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_op_iterator &gt; llvm::NamedMDNode::operands ()</td>
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



<p>Definition at line 1836 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ab09c1670b19abdcee5462c8446fa2311">op_begin</a> and <a href="#a9fd5b0835b00d3b44fe2c6dbe625600a">op_end</a>.</p>

</div>
</div>

### print() {#a66312117826bfdbd0e36aef38081b9a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NamedMDNode::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; ROS, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 4921 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>.</p>

</div>
</div>

### print() {#a267435660ce6b53b9d83d84f8f257241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NamedMDNode::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; ROS, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1816 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 4928 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a802b848d702c132a97b3da454c1e68c1">llvm::ModuleSlotTracker::getMachine</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>.</p>

</div>
</div>

### setOperand() {#a543df3cb1eda9d491a7822ef4216e3b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NamedMDNode::setOperand (unsigned I, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 1433 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a81e3dc463e57367ea1eeafe570110894">getNMDOps</a>, <a href="#acde8007e0e69969423e2de52343b702f">getNumOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a40c011ab750e2b4ea0d6b8076345cb0c">llvm::UpgradeModuleFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setParent() {#af946b43d301dc0956015c2c03b0527d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::NamedMDNode::setParent (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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



<p>Definition at line 1745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Name {#a9622c23edb4f074adc72d4160f98275d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::NamedMDNode::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

### Operands {#ad90c1c9d30e194eb9391f7cb880ea2f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::NamedMDNode::Operands</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

### Parent {#a4f4fff564bb7429f441c80ffa3b6c8a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* llvm::NamedMDNode::Parent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1742 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
