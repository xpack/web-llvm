---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-stacksafetyanalysis-cpp-/useinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `UseInfo` Struct Template Reference

<p>Describe uses of address (alloca or parameter) inside of the function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename CalleeTy&gt;
struct anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt;CalleeTy&gt; { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CalleeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae046530e0863c5fedb0aa64aa756454f">CallsTy</a> = std::map&lt; <a href="/web-llvm/docs/api/structs/anonymous-stacksafetyanalysis-cpp-/callinfo">CallInfo</a>&lt; CalleeTy &gt;, <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>, typename <a href="/web-llvm/docs/api/structs/anonymous-stacksafetyanalysis-cpp-/callinfo">CallInfo</a>&lt; CalleeTy &gt;::Less &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CalleeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a411caf27b64c8d061fcc65ea6f07e20c">UseInfo</a> (unsigned PointerSize)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CalleeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a241a4e9b3b939a216b2251cded157acd">updateRange</a> (const ConstantRange &amp;R)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CalleeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c47bb26f2fed60cd7388dd6545e9ccb">addRange</a> (const Instruction *I, const ConstantRange &amp;R, bool IsSafe)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CalleeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac2bdcd0c023c0ce457635e76623e3a3b">Range</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CalleeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abff83e23e09a90b818c684f5b658f905">UnsafeAccesses</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CalleeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae046530e0863c5fedb0aa64aa756454f">CallsTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c6815d2124afc4f88df218b3ef2da54">Calls</a></td>
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

<p>Describe uses of address (alloca or parameter) inside of the function.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CallsTy {#ae046530e0863c5fedb0aa64aa756454f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CalleeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::CallsTy =  std::map&lt;CallInfo&lt;CalleeTy&gt;, ConstantRange,
                           typename CallInfo&lt;CalleeTy&gt;::Less&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### UseInfo() {#a411caf27b64c8d061fcc65ea6f07e20c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CalleeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::UseInfo (unsigned PointerSize)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>Reference <a href="#ac2bdcd0c023c0ce457635e76623e3a3b">anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::Range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRange() {#a1c47bb26f2fed60cd7388dd6545e9ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CalleeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::addRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; R, bool IsSafe)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#abff83e23e09a90b818c684f5b658f905">anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::UnsafeAccesses</a> and <a href="#a241a4e9b3b939a216b2251cded157acd">anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::updateRange</a>.</p>

</div>
</div>

### updateRange() {#a241a4e9b3b939a216b2251cded157acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CalleeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::updateRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; R)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>References <a href="#ac2bdcd0c023c0ce457635e76623e3a3b">anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::Range</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a737326872e163eaab95c97313b9677bb">anonymous{StackSafetyAnalysis.cpp}::unionNoWrap</a>.</p>


<p>Referenced by <a href="#a1c47bb26f2fed60cd7388dd6545e9ccb">anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::addRange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Calls {#a1c6815d2124afc4f88df218b3ef2da54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CalleeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsTy anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::Calls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a23c638a26c59517939c88b7ce305c8b7">llvm::generateParamAccessSummary</a>.</p>

</div>
</div>

### Range {#ac2bdcd0c023c0ce457635e76623e3a3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CalleeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::Range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a23c638a26c59517939c88b7ce305c8b7">llvm::generateParamAccessSummary</a>, <a href="#a241a4e9b3b939a216b2251cded157acd">anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::updateRange</a> and <a href="#a411caf27b64c8d061fcc65ea6f07e20c">anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::UseInfo</a>.</p>

</div>
</div>

### UnsafeAccesses {#abff83e23e09a90b818c684f5b658f905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CalleeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;const Instruction *&gt; anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::UnsafeAccesses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#a1c47bb26f2fed60cd7388dd6545e9ccb">anonymous{StackSafetyAnalysis.cpp}::UseInfo&lt; CalleeTy &gt;::addRange</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
