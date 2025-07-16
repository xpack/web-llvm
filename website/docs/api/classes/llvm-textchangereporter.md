---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/textchangereporter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TextChangeReporter` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename IRUnitT&gt;
class llvm::TextChangeReporter&lt;IRUnitT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">llvm/Passes/StandardInstrumentations.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/changereporter">ChangeReporter&lt;IRUnitT&gt;</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5463cbf4b9180422d433483572f9bde8">TextChangeReporter</a> (bool Verbose)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0717f8e10376a5a21049544f98ae975b">handleInitialIR</a> (Any IR) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b6328ccff06e4ca69ae857e476b1df0">omitAfter</a> (StringRef PassID, std::string &amp;Name) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2aef6707bcb223c84bf4544b2f360624">handleInvalidated</a> (StringRef PassID) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af52bf759710c0bfb3e5188a2e4c016c5">handleFiltered</a> (StringRef PassID, std::string &amp;Name) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad15b9044d6771c7fa2e17b0656250306">handleIgnored</a> (StringRef PassID, std::string &amp;Name) override</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac54ee8a8b29737492ef774f233579f16">Out</a></td>
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


<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### TextChangeReporter() {#a5463cbf4b9180422d433483572f9bde8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextChangeReporter::TextChangeReporter (bool Verbose)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/changereporter/#af02006f8d15a1d0e008c0c6f2774d0e0">llvm::ChangeReporter&lt; IRUnitT &gt;::ChangeReporter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac54ee8a8b29737492ef774f233579f16">llvm::TextChangeReporter&lt; IRUnitT &gt;::Out</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### handleFiltered() {#af52bf759710c0bfb3e5188a2e4c016c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextChangeReporter::handleFiltered (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, std::string &amp; Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a> and <a href="#ac54ee8a8b29737492ef774f233579f16">llvm::TextChangeReporter&lt; IRUnitT &gt;::Out</a>.</p>

</div>
</div>

### handleIgnored() {#ad15b9044d6771c7fa2e17b0656250306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextChangeReporter::handleIgnored (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, std::string &amp; Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a> and <a href="#ac54ee8a8b29737492ef774f233579f16">llvm::TextChangeReporter&lt; IRUnitT &gt;::Out</a>.</p>

</div>
</div>

### handleInitialIR() {#a0717f8e10376a5a21049544f98ae975b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextChangeReporter::handleInitialIR (<a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="#ac54ee8a8b29737492ef774f233579f16">llvm::TextChangeReporter&lt; IRUnitT &gt;::Out</a>.</p>

</div>
</div>

### handleInvalidated() {#a2aef6707bcb223c84bf4544b2f360624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextChangeReporter::handleInvalidated (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a> and <a href="#ac54ee8a8b29737492ef774f233579f16">llvm::TextChangeReporter&lt; IRUnitT &gt;::Out</a>.</p>

</div>
</div>

### omitAfter() {#a8b6328ccff06e4ca69ae857e476b1df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextChangeReporter::omitAfter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, std::string &amp; Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a> and <a href="#ac54ee8a8b29737492ef774f233579f16">llvm::TextChangeReporter&lt; IRUnitT &gt;::Out</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Out {#ac54ee8a8b29737492ef774f233579f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::TextChangeReporter&lt; IRUnitT &gt;::Out</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#af52bf759710c0bfb3e5188a2e4c016c5">llvm::TextChangeReporter&lt; IRUnitT &gt;::handleFiltered</a>, <a href="#ad15b9044d6771c7fa2e17b0656250306">llvm::TextChangeReporter&lt; IRUnitT &gt;::handleIgnored</a>, <a href="#a0717f8e10376a5a21049544f98ae975b">llvm::TextChangeReporter&lt; IRUnitT &gt;::handleInitialIR</a>, <a href="#a2aef6707bcb223c84bf4544b2f360624">llvm::TextChangeReporter&lt; IRUnitT &gt;::handleInvalidated</a>, <a href="#a8b6328ccff06e4ca69ae857e476b1df0">llvm::TextChangeReporter&lt; IRUnitT &gt;::omitAfter</a> and <a href="#a5463cbf4b9180422d433483572f9bde8">llvm::TextChangeReporter&lt; IRUnitT &gt;::TextChangeReporter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
