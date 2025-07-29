---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/attributemask
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AttributeMask` Class

<p>This class stores enough information to efficiently remove some attributes from an existing <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> or <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AttributeMask { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">llvm/IR/AttributeMask.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4688a151549c9f8b86425855f329ba1">AttributeMask</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bfbf7719b9edf6276cc366617b89b55">AttributeMask</a> (const AttributeMask &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa580115d81765bf746548c95e3a0118c">AttributeMask</a> (AttributeMask &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ca47e710738eb3a6474b1b7a3ca355a">AttributeMask</a> (AttributeSet AS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86730a1a0c270eb9b066301bfaac8581">addAttribute</a> (Attribute::AttrKind Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an attribute to the mask. <a href="#a86730a1a0c270eb9b066301bfaac8581">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8718c125d72fe1673865494b72d7154">addAttribute</a> (Attribute A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> object to the builder. <a href="#ac8718c125d72fe1673865494b72d7154">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72fd8eb28b9b8d4523cafd184f43fcef">addAttribute</a> (StringRef A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the target-dependent attribute to the builder. <a href="#a72fd8eb28b9b8d4523cafd184f43fcef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0582254d525e9b4612f0239ac19fd39">contains</a> (Attribute::AttrKind A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the builder has the specified attribute. <a href="#ab0582254d525e9b4612f0239ac19fd39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d1025eb026eaed77c4e4f7504929905">contains</a> (StringRef A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the builder has the specified target-dependent attribute. <a href="#a0d1025eb026eaed77c4e4f7504929905">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb66fe68085ef9390340f538851f64b">contains</a> (Attribute A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the mask contains the specified attribute. <a href="#aebb66fe68085ef9390340f538851f64b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::bitset&lt; <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eadf64174102f26dd4fd9d79cc93ddee1b">Attribute::EndAttrKinds</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0eea68b663eef68e32f0133344896dd">Attrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 32 &gt;, std::less&lt;&gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeadb6d810034c868bbfa31aebe704f55">TargetDepAttrs</a></td>
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

<p>This class stores enough information to efficiently remove some attributes from an existing <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> or <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a>.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AttributeMask() {#aa4688a151549c9f8b86425855f329ba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeMask::AttributeMask ()</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>


<p>Referenced by <a href="#ac8718c125d72fe1673865494b72d7154">addAttribute</a>, <a href="#a86730a1a0c270eb9b066301bfaac8581">addAttribute</a>, <a href="#a72fd8eb28b9b8d4523cafd184f43fcef">addAttribute</a>, <a href="#aa580115d81765bf746548c95e3a0118c">AttributeMask</a> and <a href="#a1bfbf7719b9edf6276cc366617b89b55">AttributeMask</a>.</p>

</div>
</div>

### AttributeMask() {#a1bfbf7719b9edf6276cc366617b89b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeMask::AttributeMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp;)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>


<p>Reference <a href="#aa4688a151549c9f8b86425855f329ba1">AttributeMask</a>.</p>

</div>
</div>

### AttributeMask() {#aa580115d81765bf746548c95e3a0118c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeMask::AttributeMask (<a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp;&amp;)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>


<p>Reference <a href="#aa4688a151549c9f8b86425855f329ba1">AttributeMask</a>.</p>

</div>
</div>

### AttributeMask() {#a0ca47e710738eb3a6474b1b7a3ca355a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeMask::AttributeMask (<a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> AS)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a86730a1a0c270eb9b066301bfaac8581">addAttribute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAttribute() {#a86730a1a0c270eb9b066301bfaac8581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeMask &amp; llvm::AttributeMask::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Val)</td>
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

<p>Add an attribute to the mask.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa4688a151549c9f8b86425855f329ba1">AttributeMask</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eadf64174102f26dd4fd9d79cc93ddee1b">llvm::Attribute::EndAttrKinds</a>.</p>


<p>Referenced by <a href="#ac8718c125d72fe1673865494b72d7154">addAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a68a3391f6fe564a33343e43587478592">adjustCallerSSPLevel</a>, <a href="#a0ca47e710738eb3a6474b1b7a3ca355a">AttributeMask</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilprepare-cpp-/#a75bc124efcc80e995bd054f75dc5452a">anonymous{DXILPrepare.cpp}::collectDeadStringAttrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/attributefuncs/#a67d569e12c844558c447c1d8c1476f10">llvm::AttributeFuncs::getUBImplyingAttributes</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilprepare-cpp-/dxilpreparemodule/#a6bcc20d3d2e7ec05e259efe87ba8fd0c">anonymous{DXILPrepare.cpp}::DXILPrepareModule::runOnModule</a> and <a href="/web-llvm/docs/api/namespaces/llvm/attributefuncs/#ab2dcaa046e6a38983e74ce28a120ce79">llvm::AttributeFuncs::typeIncompatible</a>.</p>

</div>
</div>

### addAttribute() {#ac8718c125d72fe1673865494b72d7154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeMask &amp; llvm::AttributeMask::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> A)</td>
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

<p>Add the <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> object to the builder.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a86730a1a0c270eb9b066301bfaac8581">addAttribute</a> and <a href="#aa4688a151549c9f8b86425855f329ba1">AttributeMask</a>.</p>

</div>
</div>

### addAttribute() {#a72fd8eb28b9b8d4523cafd184f43fcef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeMask &amp; llvm::AttributeMask::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> A)</td>
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

<p>Add the target-dependent attribute to the builder.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#aa4688a151549c9f8b86425855f329ba1">AttributeMask</a>.</p>

</div>
</div>

### contains() {#ab0582254d525e9b4612f0239ac19fd39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeMask::contains (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> A)</td>
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

<p>Return true if the builder has the specified attribute.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eadf64174102f26dd4fd9d79cc93ddee1b">llvm::Attribute::EndAttrKinds</a>.</p>


<p>Referenced by <a href="#aebb66fe68085ef9390340f538851f64b">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a39fc1d3fa5b22ffc2dc48e94b40409e2">llvm::AttrBuilder::overlaps</a> and <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#abf8bb6f24f26021a4ea1b6486bc983db">llvm::AttrBuilder::remove</a>.</p>

</div>
</div>

### contains() {#a0d1025eb026eaed77c4e4f7504929905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeMask::contains (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> A)</td>
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

<p>Return true if the builder has the specified target-dependent attribute.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

### contains() {#aebb66fe68085ef9390340f538851f64b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeMask::contains (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> A)</td>
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

<p>Return true if the mask contains the specified attribute.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#ab0582254d525e9b4612f0239ac19fd39">contains</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Attrs {#af0eea68b663eef68e32f0133344896dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::bitset&lt;Attribute::EndAttrKinds&gt; llvm::AttributeMask::Attrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>

</div>
</div>

### TargetDepAttrs {#aeadb6d810034c868bbfa31aebe704f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;SmallString&lt;32&gt;, std::less&lt;&gt; &gt; llvm::AttributeMask::TargetDepAttrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">AttributeMask.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
