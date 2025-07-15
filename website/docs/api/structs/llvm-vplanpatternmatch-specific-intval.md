---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vplanpatternmatch/specific-intval
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `specific_intval` Struct Template Reference

<p>Match a specified integer value or vector of all elements of that value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;unsigned BitWidth = 0&gt;
struct llvm::VPlanPatternMatch::specific_intval&lt;BitWidth&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanpatternmatch-h">Transforms/Vectorize/VPlanPatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned BitWidth = 0&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad8c0b6db7e976abe686902e0c583b8be">specific_intval</a> (APInt V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned BitWidth = 0&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afaa3726bf59f26e6b1040f80c99167aa">match</a> (VPValue *VPV) const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned BitWidth = 0&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa96264228dab6fa0e2274d8db4e107a8">Val</a></td>
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

<p>Match a specified integer value or vector of all elements of that value.</p>


<p><span class="doxyComputerOutput">BitWidth</span> optionally specifies the bitwidth the matched constant must have. If it is 0, the matched constant can have any bitwidth.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanpatternmatch-h">VPlanPatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### specific\_intval() {#ad8c0b6db7e976abe686902e0c583b8be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned BitWidth = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPlanPatternMatch::specific_intval&lt; BitWidth &gt;::specific_intval (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> V)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanpatternmatch-h">VPlanPatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#aa96264228dab6fa0e2274d8db4e107a8">llvm::VPlanPatternMatch::specific_intval&lt; BitWidth &gt;::Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#afaa3726bf59f26e6b1040f80c99167aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned BitWidth = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPlanPatternMatch::specific_intval&lt; BitWidth &gt;::match (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * VPV)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanpatternmatch-h">VPlanPatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#ac6f0bd9ed63fe4a784697d73ae3b6fa0">llvm::VPValue::getLiveInIRValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#add6179d3564ac5ea4736366b93d23829">llvm::VPValue::isLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad76807eccec7690dec05dd5f36aceb08">llvm::APInt::isSameValue</a> and <a href="#aa96264228dab6fa0e2274d8db4e107a8">llvm::VPlanPatternMatch::specific_intval&lt; BitWidth &gt;::Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Val {#aa96264228dab6fa0e2274d8db4e107a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned BitWidth = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::VPlanPatternMatch::specific_intval&lt; BitWidth &gt;::Val</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanpatternmatch-h">VPlanPatternMatch.h</a>.</p>


<p>Referenced by <a href="#afaa3726bf59f26e6b1040f80c99167aa">llvm::VPlanPatternMatch::specific_intval&lt; BitWidth &gt;::match</a> and <a href="#ad8c0b6db7e976abe686902e0c583b8be">llvm::VPlanPatternMatch::specific_intval&lt; BitWidth &gt;::specific_intval</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanpatternmatch-h">VPlanPatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
