---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavingcompositenode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ComplexDeinterleavingCompositeNode` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a781ca662febf19b61660e05649156c3e">NodePtr</a> = std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavingcompositenode">ComplexDeinterleavingCompositeNode</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea5795d3775a7ff5dbea03591b75c20b">RawNodePtr</a> = <a href="/web-llvm/docs/api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavingcompositenode">ComplexDeinterleavingCompositeNode</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a20bf433b40630a764d8732447bc56">ComplexDeinterleavingGraph</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa23b8f4232ba83b1af0f234154478163">ComplexDeinterleavingCompositeNode</a> (ComplexDeinterleavingOperation Op, Value *R, Value *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ca506436a000deaf084f21abb6cef2f">addOperand</a> (NodePtr Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9cf130d3c9e6eb5661b759bef40fe9">dump</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7473c3f5ed85f24f3bdf9c0f8d059833">dump</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98e8e740a0a12d73ee2aa5bc9fff8c91">areOperandsValid</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764">ComplexDeinterleavingOperation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0efd69ced633d0ff27002b79aa63c4f">Operation</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3880ab5821673c3d1696cd34d092c7c5">Real</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac47a8d8f865344548c0d5ad19e1ef9cb">Imag</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36c0c380d0bc8e65152e6a6d215bf43e">Opcode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90c0a2d9808870e2f7b626adc75b5e04">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9ffbf98bd55746f804742b79f524ac7f">ComplexDeinterleavingRotation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a878832bc8be830e2529429b212bc935c">Rotation</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavingcompositenode">RawNodePtr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbdd425853c7775fd2771e587630f5d6">Operands</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41eef88e6d241527de85df10ccea45d">ReplacementNode</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa62529ac348e130cfd3a74b6e942b445">OperandsValid</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### NodePtr {#a781ca662febf19b61660e05649156c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::NodePtr =  std::shared_ptr&lt;ComplexDeinterleavingCompositeNode&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### RawNodePtr {#aea5795d3775a7ff5dbea03591b75c20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::RawNodePtr =  ComplexDeinterleavingCompositeNode *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ComplexDeinterleavingGraph {#a63a20bf433b40630a764d8732447bc56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph">ComplexDeinterleavingGraph</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>References <a href="#aa23b8f4232ba83b1af0f234154478163">ComplexDeinterleavingCompositeNode</a> and <a href="#a63a20bf433b40630a764d8732447bc56">ComplexDeinterleavingGraph</a>.</p>


<p>Referenced by <a href="#a63a20bf433b40630a764d8732447bc56">ComplexDeinterleavingGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ComplexDeinterleavingCompositeNode() {#aa23b8f4232ba83b1af0f234154478163}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::ComplexDeinterleavingCompositeNode (<a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764">ComplexDeinterleavingOperation</a> Op, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * R, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * I)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac47a8d8f865344548c0d5ad19e1ef9cb">Imag</a>, <a href="#af0efd69ced633d0ff27002b79aa63c4f">Operation</a> and <a href="#a3880ab5821673c3d1696cd34d092c7c5">Real</a>.</p>


<p>Referenced by <a href="#a63a20bf433b40630a764d8732447bc56">ComplexDeinterleavingGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addOperand() {#a7ca506436a000deaf084f21abb6cef2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::addOperand (NodePtr Node)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>Reference <a href="#acbdd425853c7775fd2771e587630f5d6">Operands</a>.</p>

</div>
</div>

### areOperandsValid() {#a98e8e740a0a12d73ee2aa5bc9fff8c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::areOperandsValid ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### dump() {#a0b9cf130d3c9e6eb5661b759bef40fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::dump ()</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a0b9cf130d3c9e6eb5661b759bef40fe9">dump</a>.</p>


<p>Referenced by <a href="#a0b9cf130d3c9e6eb5661b759bef40fe9">dump</a> and <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#a257b23cbc3b86d61dc953bad7beeaa5b">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::identifyNodes</a>.</p>

</div>
</div>

### dump() {#a7473c3f5ed85f24f3bdf9c0f8d059833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>References <a href="#ac47a8d8f865344548c0d5ad19e1ef9cb">Imag</a>, <a href="#acbdd425853c7775fd2771e587630f5d6">Operands</a>, <a href="#af0efd69ced633d0ff27002b79aa63c4f">Operation</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#a3880ab5821673c3d1696cd34d092c7c5">Real</a>, <a href="#ab41eef88e6d241527de85df10ccea45d">ReplacementNode</a> and <a href="#a878832bc8be830e2529429b212bc935c">Rotation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Flags {#a90c0a2d9808870e2f7b626adc75b5e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;FastMathFlags&gt; anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### Imag {#ac47a8d8f865344548c0d5ad19e1ef9cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::Imag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>Referenced by <a href="#aa23b8f4232ba83b1af0f234154478163">ComplexDeinterleavingCompositeNode</a> and <a href="#a7473c3f5ed85f24f3bdf9c0f8d059833">dump</a>.</p>

</div>
</div>

### Opcode {#a36c0c380d0bc8e65152e6a6d215bf43e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### Operands {#acbdd425853c7775fd2771e587630f5d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RawNodePtr&gt; anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::Operands</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>Referenced by <a href="#a7ca506436a000deaf084f21abb6cef2f">addOperand</a> and <a href="#a7473c3f5ed85f24f3bdf9c0f8d059833">dump</a>.</p>

</div>
</div>

### Operation {#af0efd69ced633d0ff27002b79aa63c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingOperation anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::Operation</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>Referenced by <a href="#aa23b8f4232ba83b1af0f234154478163">ComplexDeinterleavingCompositeNode</a> and <a href="#a7473c3f5ed85f24f3bdf9c0f8d059833">dump</a>.</p>

</div>
</div>

### Real {#a3880ab5821673c3d1696cd34d092c7c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::Real</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>Referenced by <a href="#aa23b8f4232ba83b1af0f234154478163">ComplexDeinterleavingCompositeNode</a> and <a href="#a7473c3f5ed85f24f3bdf9c0f8d059833">dump</a>.</p>

</div>
</div>

### ReplacementNode {#ab41eef88e6d241527de85df10ccea45d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::ReplacementNode = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>Referenced by <a href="#a7473c3f5ed85f24f3bdf9c0f8d059833">dump</a>.</p>

</div>
</div>

### Rotation {#a878832bc8be830e2529429b212bc935c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingRotation anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::Rotation</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      ComplexDeinterleavingRotation::Rotation_0
</div>
</dd>
</dl>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>Referenced by <a href="#a7473c3f5ed85f24f3bdf9c0f8d059833">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OperandsValid {#aa62529ac348e130cfd3a74b6e942b445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::OperandsValid = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
