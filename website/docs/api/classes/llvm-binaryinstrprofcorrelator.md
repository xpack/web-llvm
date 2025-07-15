---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/binaryinstrprofcorrelator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BinaryInstrProfCorrelator` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/binaryinstrprofcorrelator">BinaryInstrProfCorrelator</a> - A child of <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a> that takes an object file as input to correlate profiles. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class IntPtrT&gt;
class llvm::BinaryInstrProfCorrelator&lt;IntPtrT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">llvm/ProfileData/InstrProfCorrelator.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl&lt;IntPtrT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a> - A child of <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> with a template pointer type so that the ProfileData vector can be materialized. <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a9a4f4600ec30ccc7b2fe6d75dc774ab5">BinaryInstrProfCorrelator</a> (std::unique_ptr&lt; InstrProfCorrelator::Context &gt; Ctx)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a458c057bfde6e2e0bb705849cf1ef25a">getNamesPointer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to the names string that this class constructs. <a href="#a458c057bfde6e2e0bb705849cf1ef25a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a231b075aa389203c8b6fe6d66321b947">getNamesSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bytes in the names string. <a href="#a231b075aa389203c8b6fe6d66321b947">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a847e702f8117e39a65cac8f36a1413e7">correlateProfileDataImpl</a> (int MaxWarnings, InstrProfCorrelator::CorrelationData *Data=nullptr) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa5999fe993d79d43f0d12723047d4f3c">correlateProfileNameImpl</a> () override</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/binaryinstrprofcorrelator">BinaryInstrProfCorrelator</a> - A child of <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a> that takes an object file as input to correlate profiles.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BinaryInstrProfCorrelator() {#a9a4f4600ec30ccc7b2fe6d75dc774ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryInstrProfCorrelator&lt; IntPtrT &gt;::BinaryInstrProfCorrelator (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/context">InstrProfCorrelator::Context</a> &gt; Ctx)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ac9e9fa2e8b9f1243b2f9b970dc245bef">llvm::InstrProfCorrelator::Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#a9110dae8cefc94bca7e5f15b038b2d6a">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::InstrProfCorrelatorImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNamesPointer() {#a458c057bfde6e2e0bb705849cf1ef25a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::BinaryInstrProfCorrelator&lt; IntPtrT &gt;::getNamesPointer ()</td>
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

<p>Return a pointer to the names string that this class constructs.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ac9e9fa2e8b9f1243b2f9b970dc245bef">llvm::InstrProfCorrelator::Ctx</a>.</p>

</div>
</div>

### getNamesSize() {#a231b075aa389203c8b6fe6d66321b947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::BinaryInstrProfCorrelator&lt; IntPtrT &gt;::getNamesSize ()</td>
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

<p>Return the number of bytes in the names string.</p>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ac9e9fa2e8b9f1243b2f9b970dc245bef">llvm::InstrProfCorrelator::Ctx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### correlateProfileDataImpl() {#a847e702f8117e39a65cac8f36a1413e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BinaryInstrProfCorrelator::correlateProfileDataImpl (int MaxWarnings, <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/correlationdata">InstrProfCorrelator::CorrelationData</a> * Data=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>

</div>
</div>

### correlateProfileNameImpl() {#aa5999fe993d79d43f0d12723047d4f3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BinaryInstrProfCorrelator::correlateProfileNameImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
