---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/outlinedhashtree
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OutlinedHashTree` Class



## Declaration

<div class="doxyDeclaration">
class llvm::OutlinedHashTree { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">llvm/CGData/OutlinedHashTree.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16db6ae9208787794c5a6af57ee46d00">EdgeCallbackFn</a> = std::function&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a> *)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a73537eee64eb333d78ab92d3065e4c">NodeCallbackFn</a> = std::function&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a> *)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9916a1079ea29d4f2260525d54a8b139">HashSequence</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030ec26b3bbf06a3d5d6af6dd504e70c">HashSequencePair</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">HashSequence</a>, unsigned &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a692390cd6799e674710e434f3658418a">walkGraph</a> (NodeCallbackFn CallbackNode, EdgeCallbackFn CallbackEdge=nullptr, bool SortedWalk=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walks every edge and node in the <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> and calls CallbackEdge for the edges and CallbackNode for the nodes with the <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> for the source and the <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> of the sink for an edge. <a href="#a692390cd6799e674710e434f3658418a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d79a1e68b8960755f9f0bf4aceb1ae1">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release all hash nodes except the root hash node. <a href="#a1d79a1e68b8960755f9f0bf4aceb1ae1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6d8dcfd526383fe146bf9c0cd1c2999">empty</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfea475152d214caa9b72bad101d75a0">size</a> (bool GetTerminalCountOnly=false) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f9dd40bc3145351ebf12cfb4191a0eb">depth</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ddda0cb27c6bde706044fdd46490ff7">getRoot</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75cf4d2ca934ed16ad8042b32e6159f6">getRoot</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc2686042d37b5df938df13eef50cd6e">insert</a> (const HashSequencePair &amp;SequencePair)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts a <span class="doxyComputerOutput">Sequence</span> into the this tree. <a href="#abc2686042d37b5df938df13eef50cd6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d8f153a3d47acbb643fde3d1f215bcc">merge</a> (const OutlinedHashTree *OtherTree)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge a <span class="doxyComputerOutput">OtherTree</span> into this Tree. <a href="#a9d8f153a3d47acbb643fde3d1f215bcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c408d99704ccf35333069847a091eeb">find</a> (const HashSequence &amp;Sequence) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa546b3283c72ded51f821800350a3e73">Root</a></td>
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


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### EdgeCallbackFn {#a16db6ae9208787794c5a6af57ee46d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OutlinedHashTree::EdgeCallbackFn = 
      std::function&lt;void(const HashNode *, const HashNode *)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>

</div>
</div>

### HashSequence {#a9916a1079ea29d4f2260525d54a8b139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OutlinedHashTree::HashSequence =  SmallVector&lt;stable_hash&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>

</div>
</div>

### HashSequencePair {#a030ec26b3bbf06a3d5d6af6dd504e70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OutlinedHashTree::HashSequencePair =  std::pair&lt;HashSequence, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>

</div>
</div>

### NodeCallbackFn {#a9a73537eee64eb333d78ab92d3065e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OutlinedHashTree::NodeCallbackFn =  std::function&lt;void(const HashNode *)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a1d79a1e68b8960755f9f0bf4aceb1ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OutlinedHashTree::clear ()</td>
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

<p>Release all hash nodes except the root hash node.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7ddda0cb27c6bde706044fdd46490ff7">getRoot</a> and <a href="/web-llvm/docs/api/structs/llvm/hashnode/#a1a31b051ee904b573a699443959ce8b6">llvm::HashNode::Successors</a>.</p>

</div>
</div>

### depth() {#a4f9dd40bc3145351ebf12cfb4191a0eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t OutlinedHashTree::depth ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the depth of a <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> by traversing it.</p></dd>
</dl>


<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtree-cpp">OutlinedHashTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a692390cd6799e674710e434f3658418a">walkGraph</a>.</p>

</div>
</div>

### empty() {#af6d8dcfd526383fe146bf9c0cd1c2999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OutlinedHashTree::empty ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the hash tree has only the root node.</p></dd>
</dl>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### find() {#a6c408d99704ccf35333069847a091eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; OutlinedHashTree::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">HashSequence</a> &amp; Sequence)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the matching count if <span class="doxyComputerOutput">Sequence</span> exists in the <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a>.</p></dd>
</dl>


<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtree-cpp">OutlinedHashTree.cpp</a>.</p>


<p>References <a href="#a7ddda0cb27c6bde706044fdd46490ff7">getRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/hashnode/#a1a31b051ee904b573a699443959ce8b6">llvm::HashNode::Successors</a> and <a href="/web-llvm/docs/api/structs/llvm/hashnode/#a66632316e3bbfd1f40384f637f68e625">llvm::HashNode::Terminals</a>.</p>

</div>
</div>

### getRoot() {#a7ddda0cb27c6bde706044fdd46490ff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HashNode * llvm::OutlinedHashTree::getRoot ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the root hash node of a <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a>.</p></dd>
</dl>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>


<p>Referenced by <a href="#a1d79a1e68b8960755f9f0bf4aceb1ae1">clear</a>, <a href="#a6c408d99704ccf35333069847a091eeb">find</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#af08090d2b358f57cbf6b3448a5ff2676">getMatchedEntries</a>, <a href="#abc2686042d37b5df938df13eef50cd6e">insert</a>, <a href="#a9d8f153a3d47acbb643fde3d1f215bcc">merge</a> and <a href="#a692390cd6799e674710e434f3658418a">walkGraph</a>.</p>

</div>
</div>

### getRoot() {#a75cf4d2ca934ed16ad8042b32e6159f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashNode * llvm::OutlinedHashTree::getRoot ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>

</div>
</div>

### insert() {#abc2686042d37b5df938df13eef50cd6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutlinedHashTree::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> HashSequencePair &amp; SequencePair)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inserts a <span class="doxyComputerOutput">Sequence</span> into the this tree.</p>


<p>The last node in the sequence will increase Terminals.</p>


<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtree-cpp">OutlinedHashTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a7ddda0cb27c6bde706044fdd46490ff7">getRoot</a>, <a href="/web-llvm/docs/api/structs/llvm/hashnode/#adf900abae6895805cd64c155430807fe">llvm::HashNode::Hash</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/structs/llvm/hashnode/#a1a31b051ee904b573a699443959ce8b6">llvm::HashNode::Successors</a> and <a href="/web-llvm/docs/api/structs/llvm/hashnode/#a66632316e3bbfd1f40384f637f68e625">llvm::HashNode::Terminals</a>.</p>

</div>
</div>

### merge() {#a9d8f153a3d47acbb643fde3d1f215bcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutlinedHashTree::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> * OtherTree)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge a <span class="doxyComputerOutput">OtherTree</span> into this Tree.</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtree-cpp">OutlinedHashTree.cpp</a>.</p>


<p>References <a href="#a7ddda0cb27c6bde706044fdd46490ff7">getRoot</a>, <a href="/web-llvm/docs/api/structs/llvm/hashnode/#adf900abae6895805cd64c155430807fe">llvm::HashNode::Hash</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### size() {#abfea475152d214caa9b72bad101d75a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t OutlinedHashTree::size (bool GetTerminalCountOnly=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the size of a <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> by traversing it. If <span class="doxyComputerOutput">GetTerminalCountOnly</span> is true, it only counts the terminal nodes (meaning it returns the the number of hash sequences in the <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a>).</p></dd>
</dl>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtree-cpp">OutlinedHashTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a692390cd6799e674710e434f3658418a">walkGraph</a>.</p>

</div>
</div>

### walkGraph() {#a692390cd6799e674710e434f3658418a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutlinedHashTree::walkGraph (NodeCallbackFn CallbackNode, EdgeCallbackFn CallbackEdge=nullptr, bool SortedWalk=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Walks every edge and node in the <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> and calls CallbackEdge for the edges and CallbackNode for the nodes with the <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> for the source and the <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> of the sink for an edge.</p>


<p>These generic callbacks can be used to traverse a <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> for the purpose of print debugging or serializing it.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtree-cpp">OutlinedHashTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="#a7ddda0cb27c6bde706044fdd46490ff7">getRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06add2496ae8d635f9f169602771c88d376">llvm::Successor</a>.</p>


<p>Referenced by <a href="#a4f9dd40bc3145351ebf12cfb4191a0eb">depth</a> and <a href="#abfea475152d214caa9b72bad101d75a0">size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Root {#aa546b3283c72ded51f821800350a3e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashNode llvm::OutlinedHashTree::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/cgdata/outlinedhashtree-cpp">OutlinedHashTree.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
