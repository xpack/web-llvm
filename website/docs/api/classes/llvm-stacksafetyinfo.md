---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/stacksafetyinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StackSafetyInfo` Class Reference

<p>Interface to access stack safety analysis results for single function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::StackSafetyInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">llvm/Analysis/StackSafetyAnalysis.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f7a4bfdbb4be5c85cc2937980bda8d">StackSafetyInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfc69ea97912d6d12d5f72f1cf4ea45d">StackSafetyInfo</a> (Function *F, std::function&lt; ScalarEvolution &amp;()&gt; GetSE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cb8f7bab5ec2b0dc975a8d4a87d4231">StackSafetyInfo</a> (StackSafetyInfo &amp;&amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5852c5cfe7bc9a9868064011755fe323">~StackSafetyInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stacksafetyinfo">StackSafetyInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa504bf8673347b1c033b71eab0519c">operator=</a> (StackSafetyInfo &amp;&amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/stacksafetyinfo/infoty">InfoTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6462fd5937db82b0f163ad1ad17fdf32">getInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46af1eb0327b4025483a506653f21cc1">print</a> (raw_ostream &amp;O) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/paramaccess">FunctionSummary::ParamAccess</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6fcee230630c48fcd48962768e7bcb">getParamAccesses</a> (ModuleSummaryIndex &amp;Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parameters use for a <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a>. <a href="#abc6fcee230630c48fcd48962768e7bcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0b1883089e33e6903e32d2a4ec6208">F</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;()&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a480865f06004fc2064b323f01457c786">GetSE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/stacksafetyinfo/infoty">InfoTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633596487be04b3ac54400efe45cb2af">Info</a></td>
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

<p>Interface to access stack safety analysis results for single function.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StackSafetyInfo() {#a73f7a4bfdbb4be5c85cc2937980bda8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackSafetyInfo::StackSafetyInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>.</p>


<p>Referenced by <a href="#a7fa504bf8673347b1c033b71eab0519c">operator=</a> and <a href="#a6cb8f7bab5ec2b0dc975a8d4a87d4231">StackSafetyInfo</a>.</p>

</div>
</div>

### StackSafetyInfo() {#adfc69ea97912d6d12d5f72f1cf4ea45d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackSafetyInfo::StackSafetyInfo (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;()&gt; GetSE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>, definition at line 885 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>

</div>
</div>

### StackSafetyInfo() {#a6cb8f7bab5ec2b0dc975a8d4a87d4231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackSafetyInfo::StackSafetyInfo (<a href="/web-llvm/docs/api/classes/llvm/stacksafetyinfo">StackSafetyInfo</a> &amp;&amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>.</p>


<p>Reference <a href="#a73f7a4bfdbb4be5c85cc2937980bda8d">StackSafetyInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~StackSafetyInfo() {#a5852c5cfe7bc9a9868064011755fe323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackSafetyInfo::~StackSafetyInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a7fa504bf8673347b1c033b71eab0519c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackSafetyInfo &amp; StackSafetyInfo::operator= (<a href="/web-llvm/docs/api/classes/llvm/stacksafetyinfo">StackSafetyInfo</a> &amp;&amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>.</p>


<p>Reference <a href="#a73f7a4bfdbb4be5c85cc2937980bda8d">StackSafetyInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInfo() {#a6462fd5937db82b0f163ad1ad17fdf32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StackSafetyInfo::InfoTy &amp; StackSafetyInfo::getInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>, definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#abc6fcee230630c48fcd48962768e7bcb">getParamAccesses</a> and <a href="#a46af1eb0327b4025483a506653f21cc1">print</a>.</p>

</div>
</div>

### getParamAccesses() {#abc6fcee230630c48fcd48962768e7bcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; FunctionSummary::ParamAccess &gt; StackSafetyInfo::getParamAccesses (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parameters use for a <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> collects access information of all pointer parameters. Information includes a range of direct access of parameters by the functions and all call sites accepting the parameter. StackSafety assumes that missing parameter information means possibility of access to the parameter with any offset, so we can correctly link code without StackSafety information, e.g. non-ThinLTO.</p>


<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>, definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a6462fd5937db82b0f163ad1ad17fdf32">getInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

### print() {#a46af1eb0327b4025483a506653f21cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackSafetyInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>, definition at line 903 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a6462fd5937db82b0f163ad1ad17fdf32">getInfo</a> and <a href="/web-llvm/docs/api/structs/stacksafetyinfo/infoty/#a0f44ad7c9d7dc077a55421fcce551125">llvm::StackSafetyInfo::InfoTy::Info</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### F {#acf0b1883089e33e6903e32d2a4ec6208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::StackSafetyInfo::F = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>.</p>

</div>
</div>

### GetSE {#a480865f06004fc2064b323f01457c786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;ScalarEvolution &amp;()&gt; llvm::StackSafetyInfo::GetSE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>.</p>

</div>
</div>

### Info {#a633596487be04b3ac54400efe45cb2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InfoTy&gt; llvm::StackSafetyInfo::Info</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">StackSafetyAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
