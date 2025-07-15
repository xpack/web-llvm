---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CVPLatticeVal` Class Reference

<p>The lattice value type used by our custom lattice function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{CalledValuePropagation.cpp}::CVPLatticeVal { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CVPLatticeStateTy { <a href="#a047b15b8d63ce6fef09a75567338eb78">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The states of the lattice values. <a href="#a047b15b8d63ce6fef09a75567338eb78">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e695347fc29b8adcd616dc29eba9e39">CVPLatticeVal</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e65ae4f62dda3e00962712b5797354">CVPLatticeVal</a> (CVPLatticeStateTy LatticeState)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a176ae3309ad13660d5b6e552a99197e6">CVPLatticeVal</a> (std::vector&lt; Function * &gt; &amp;&amp;Functions)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23fbcb5544fb7fb011f0baabb9ce16a5">operator==</a> (const CVPLatticeVal &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac438b5e0fb725ae81414831e1ff635c5">operator!=</a> (const CVPLatticeVal &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77757f87f0fdd136cd60ad02141dec53">getFunctions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the functions held by this lattice value. <a href="#a77757f87f0fdd136cd60ad02141dec53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27bf6cf99101d7870e801cb8df22dc8d">isFunctionSet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the lattice value is in the FunctionSet state. <a href="#a27bf6cf99101d7870e801cb8df22dc8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a047b15b8d63ce6fef09a75567338eb78">CVPLatticeStateTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb7482a52a73acdc6436cebf28186316">LatticeState</a> = <a href="#a047b15b8d63ce6fef09a75567338eb78ab59fcbd316a6bfe3b0922133698fc5a6">Undefined</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the state this lattice value is in. <a href="#afb7482a52a73acdc6436cebf28186316">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af33eafd9b0aa8b46c991d95f98e64d78">Functions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds functions indicating the possible targets of call sites. <a href="#af33eafd9b0aa8b46c991d95f98e64d78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The lattice value type used by our custom lattice function.</p>


<p>It holds the lattice state, and a set of functions.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### CVPLatticeStateTy {#a047b15b8d63ce6fef09a75567338eb78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{CalledValuePropagation.cpp}::CVPLatticeVal::CVPLatticeStateTy </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The states of the lattice values.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Undefined<a id="a047b15b8d63ce6fef09a75567338eb78ab59fcbd316a6bfe3b0922133698fc5a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FunctionSet<a id="a047b15b8d63ce6fef09a75567338eb78acc895ad91ee371788dd37f8cd140ef95"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Overdefined<a id="a047b15b8d63ce6fef09a75567338eb78a6a35a13d8d3010e075dccba902f72bbd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Untracked<a id="a047b15b8d63ce6fef09a75567338eb78a97e4df3b28f28d1185a29ebc1de4c47e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>Only the FunctionSet state is interesting. It indicates the set of functions to which an LLVM value may refer.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CVPLatticeVal() {#a7e695347fc29b8adcd616dc29eba9e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CalledValuePropagation.cpp}::CVPLatticeVal::CVPLatticeVal ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>Referenced by <a href="#ac438b5e0fb725ae81414831e1ff635c5">operator!=</a>, <a href="#a23fbcb5544fb7fb011f0baabb9ce16a5">operator==</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp/#a1d2bce545ae26cccf351c2c0d35d64e4">runCVP</a>.</p>

</div>
</div>

### CVPLatticeVal() {#a37e65ae4f62dda3e00962712b5797354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CalledValuePropagation.cpp}::CVPLatticeVal::CVPLatticeVal (<a href="#a047b15b8d63ce6fef09a75567338eb78">CVPLatticeStateTy</a> LatticeState)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

### CVPLatticeVal() {#a176ae3309ad13660d5b6e552a99197e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CalledValuePropagation.cpp}::CVPLatticeVal::CVPLatticeVal (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp;&amp; Functions)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a047b15b8d63ce6fef09a75567338eb78acc895ad91ee371788dd37f8cd140ef95">FunctionSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#ac438b5e0fb725ae81414831e1ff635c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CalledValuePropagation.cpp}::CVPLatticeVal::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> &amp; RHS)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>Reference <a href="#a7e695347fc29b8adcd616dc29eba9e39">CVPLatticeVal</a>.</p>

</div>
</div>

### operator==() {#a23fbcb5544fb7fb011f0baabb9ce16a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CalledValuePropagation.cpp}::CVPLatticeVal::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> &amp; RHS)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>Reference <a href="#a7e695347fc29b8adcd616dc29eba9e39">CVPLatticeVal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFunctions() {#a77757f87f0fdd136cd60ad02141dec53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; Function * &gt; &amp; anonymous{CalledValuePropagation.cpp}::CVPLatticeVal::getFunctions ()</td>
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

<p>Get a reference to the functions held by this lattice value.</p>


<p>The number of functions will be zero for states other than FunctionSet.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

### isFunctionSet() {#a27bf6cf99101d7870e801cb8df22dc8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CalledValuePropagation.cpp}::CVPLatticeVal::isFunctionSet ()</td>
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

<p>Returns true if the lattice value is in the FunctionSet state.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>Reference <a href="#a047b15b8d63ce6fef09a75567338eb78acc895ad91ee371788dd37f8cd140ef95">FunctionSet</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Functions {#af33eafd9b0aa8b46c991d95f98e64d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Function *&gt; anonymous{CalledValuePropagation.cpp}::CVPLatticeVal::Functions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds functions indicating the possible targets of call sites.</p>


<p>This set is empty for lattice values in the undefined, overdefined, and untracked states. The maximum size of the set is controlled by MaxFunctionsPerValue. Since most LLVM values are expected to be in uninteresting states (i.e., overdefined), <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> objects should be small and efficiently copyable.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

### LatticeState {#afb7482a52a73acdc6436cebf28186316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVPLatticeStateTy anonymous{CalledValuePropagation.cpp}::CVPLatticeVal::LatticeState = <a href="#a047b15b8d63ce6fef09a75567338eb78ab59fcbd316a6bfe3b0922133698fc5a6">Undefined</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the state this lattice value is in.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
