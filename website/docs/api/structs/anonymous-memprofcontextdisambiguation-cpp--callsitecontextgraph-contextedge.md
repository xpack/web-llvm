---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ContextEdge` Struct Reference

<p>Edge in the Callsite Context Graph from a <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> N to a caller or callee. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph::ContextEdge { ... }
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae78bfc290ecbb1156b1ce115e746985c">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4594c0ee75981d06cba08b0efe990589">ContextEdge</a> (ContextNode *Callee, ContextNode *Caller, uint8_t AllocType, DenseSet&lt; uint32_t &gt; ContextIds)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb420b741de9451d15bd7847381fb2e2">getContextIds</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ec5a7179a466b002c0ff0c0e4446906">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d8636303c3e359d3b1c5c177d7882f">isRemoved</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5857119fe2945f58e00ac6d95feda0b">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6c023223ec2c5481dd82c860deed2f8">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379dfc9cccef17b06b38998fe9e9006f">Callee</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2acb60c189c35d3ce862eb0cd35bbf8e">Caller</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae01bac6d29d485d1e9db1e014f33bcf7">AllocTypes</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a2093e55606370a5d2faa561511b9d">ContextIds</a></td>
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

<p>Edge in the Callsite Context Graph from a <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> N to a caller or callee.</p>

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#ae78bfc290ecbb1156b1ce115e746985c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> &amp; Edge</td>
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


<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Reference <a href="#a4594c0ee75981d06cba08b0efe990589">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextEdge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ContextEdge() {#a4594c0ee75981d06cba08b0efe990589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextEdge (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Callee, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Caller, uint8_t AllocType, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt; ContextIds)</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#ae01bac6d29d485d1e9db1e014f33bcf7">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::AllocTypes</a>, <a href="#a379dfc9cccef17b06b38998fe9e9006f">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::Callee</a>, <a href="#a2acb60c189c35d3ce862eb0cd35bbf8e">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::Caller</a>, <a href="#ad8a2093e55606370a5d2faa561511b9d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextIds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#ae78bfc290ecbb1156b1ce115e746985c">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a6ec5a7179a466b002c0ff0c0e4446906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::clear ()</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#ae01bac6d29d485d1e9db1e014f33bcf7">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::AllocTypes</a>, <a href="#a379dfc9cccef17b06b38998fe9e9006f">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::Callee</a>, <a href="#a2acb60c189c35d3ce862eb0cd35bbf8e">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::Caller</a>, <a href="#ad8a2093e55606370a5d2faa561511b9d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextIds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### dump() {#aa5857119fe2945f58e00ac6d95feda0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::ContextEdge::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a9b182ff5e447c562a7d45505c4b5a63a">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::print</a>.</p>

</div>
</div>

### getContextIds() {#acb420b741de9451d15bd7847381fb2e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt; uint32_t &gt; &amp; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::getContextIds ()</td>
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



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Reference <a href="#ad8a2093e55606370a5d2faa561511b9d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextIds</a>.</p>

</div>
</div>

### isRemoved() {#a46d8636303c3e359d3b1c5c177d7882f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::isRemoved ()</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#ae01bac6d29d485d1e9db1e014f33bcf7">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::AllocTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a379dfc9cccef17b06b38998fe9e9006f">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::Callee</a>, <a href="#a2acb60c189c35d3ce862eb0cd35bbf8e">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::Caller</a>, <a href="#ad8a2093e55606370a5d2faa561511b9d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextIds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### print() {#ab6c023223ec2c5481dd82c860deed2f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::ContextEdge::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#ae01bac6d29d485d1e9db1e014f33bcf7">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::AllocTypes</a>, <a href="#a379dfc9cccef17b06b38998fe9e9006f">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::Callee</a>, <a href="#a2acb60c189c35d3ce862eb0cd35bbf8e">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::Caller</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a>, <a href="#ad8a2093e55606370a5d2faa561511b9d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextIds</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#a78e5652d529e02da75e8087017930e28">getAllocTypeString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllocTypes {#ae01bac6d29d485d1e9db1e014f33bcf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::AllocTypes = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#a6ec5a7179a466b002c0ff0c0e4446906">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::clear</a>, <a href="#a4594c0ee75981d06cba08b0efe990589">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextEdge</a>, <a href="#a46d8636303c3e359d3b1c5c177d7882f">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::isRemoved</a> and <a href="#ab6c023223ec2c5481dd82c860deed2f8">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::print</a>.</p>

</div>
</div>

### Callee {#a379dfc9cccef17b06b38998fe9e9006f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextNode* anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::Callee</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#a6ec5a7179a466b002c0ff0c0e4446906">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::clear</a>, <a href="#a4594c0ee75981d06cba08b0efe990589">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextEdge</a>, <a href="#a46d8636303c3e359d3b1c5c177d7882f">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::isRemoved</a> and <a href="#ab6c023223ec2c5481dd82c860deed2f8">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::print</a>.</p>

</div>
</div>

### Caller {#a2acb60c189c35d3ce862eb0cd35bbf8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextNode* anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::Caller</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#a6ec5a7179a466b002c0ff0c0e4446906">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::clear</a>, <a href="#a4594c0ee75981d06cba08b0efe990589">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextEdge</a>, <a href="#a46d8636303c3e359d3b1c5c177d7882f">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::isRemoved</a> and <a href="#ab6c023223ec2c5481dd82c860deed2f8">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::print</a>.</p>

</div>
</div>

### ContextIds {#ad8a2093e55606370a5d2faa561511b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;uint32_t&gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#a6ec5a7179a466b002c0ff0c0e4446906">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::clear</a>, <a href="#a4594c0ee75981d06cba08b0efe990589">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::ContextEdge</a>, <a href="#acb420b741de9451d15bd7847381fb2e2">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::getContextIds</a>, <a href="#a46d8636303c3e359d3b1c5c177d7882f">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::isRemoved</a> and <a href="#ab6c023223ec2c5481dd82c860deed2f8">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
