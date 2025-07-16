---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gsym/outputaggregator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OutputAggregator` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::gsym::OutputAggregator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">llvm/DebugInfo/GSYM/OutputAggregator.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e3b3b19e6adfc366f706660aa8255e8">OutputAggregator</a> (raw_ostream *out)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator">OutputAggregator</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a81964fff9dc7844a7c7f48185a827e34">operator&lt;&lt;</a> (T &amp;&amp;value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dea9185bb17ec8a2eb7d7dba79a21f5">GetNumCategories</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a051eee638f618d1ebe54f433350b7c1d">Report</a> (StringRef s, std::function&lt; void(raw_ostream &amp;o)&gt; detailCallback)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987b74f13eb2c94d22fb702c55b55527">EnumerateResults</a> (std::function&lt; void(StringRef, unsigned)&gt; handleCounts) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1be2c7a42ac407e8eac9396768207dc">GetOS</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af65bf7475eed416d9de9a4a5e5e5ad2f">Merge</a> (const OutputAggregator &amp;other)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac059d31fd5f633ad6cfe296be8ff3c4f">Aggregation</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a753aa5926e1055414cb09133ac724b90">Out</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">OutputAggregator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OutputAggregator() {#a2e3b3b19e6adfc366f706660aa8255e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::gsym::OutputAggregator::OutputAggregator (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> * out)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">OutputAggregator.h</a>.</p>


<p>Reference <a href="#a753aa5926e1055414cb09133ac724b90">Out</a>.</p>


<p>Referenced by <a href="#af65bf7475eed416d9de9a4a5e5e5ad2f">Merge</a> and <a href="#a81964fff9dc7844a7c7f48185a827e34">operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;&lt;() {#a81964fff9dc7844a7c7f48185a827e34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputAggregator &amp; llvm::gsym::OutputAggregator::operator&lt;&lt; (T &amp;&amp; value)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">OutputAggregator.h</a>.</p>


<p>References <a href="#a753aa5926e1055414cb09133ac724b90">Out</a>, <a href="#a2e3b3b19e6adfc366f706660aa8255e8">OutputAggregator</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EnumerateResults() {#a987b74f13eb2c94d22fb702c55b55527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::OutputAggregator::EnumerateResults (std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, unsigned)&gt; handleCounts)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">OutputAggregator.h</a>.</p>


<p>References <a href="#ac059d31fd5f633ad6cfe296be8ff3c4f">Aggregation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>.</p>

</div>
</div>

### GetNumCategories() {#a6dea9185bb17ec8a2eb7d7dba79a21f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::gsym::OutputAggregator::GetNumCategories ()</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">OutputAggregator.h</a>.</p>


<p>Reference <a href="#ac059d31fd5f633ad6cfe296be8ff3c4f">Aggregation</a>.</p>

</div>
</div>

### GetOS() {#ac1be2c7a42ac407e8eac9396768207dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream * llvm::gsym::OutputAggregator::GetOS ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">OutputAggregator.h</a>.</p>


<p>Reference <a href="#a753aa5926e1055414cb09133ac724b90">Out</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ab014307b03ade42770de6ed2f827630b">llvm::gsym::DwarfTransformer::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/objectfiletransformer/#a9940b2d9a5f2a7de1dcfcdb970bf5e51">llvm::gsym::ObjectFileTransformer::convert</a>, <a href="#a051eee638f618d1ebe54f433350b7c1d">Report</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ac40e6efe1caf07771eb6713f41db076b">llvm::gsym::DwarfTransformer::verify</a>.</p>

</div>
</div>

### Merge() {#af65bf7475eed416d9de9a4a5e5e5ad2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::OutputAggregator::Merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator">OutputAggregator</a> &amp; other)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">OutputAggregator.h</a>.</p>


<p>References <a href="#ac059d31fd5f633ad6cfe296be8ff3c4f">Aggregation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a> and <a href="#a2e3b3b19e6adfc366f706660aa8255e8">OutputAggregator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ab014307b03ade42770de6ed2f827630b">llvm::gsym::DwarfTransformer::convert</a>.</p>

</div>
</div>

### Report() {#a051eee638f618d1ebe54f433350b7c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::OutputAggregator::Report (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> s, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;o)&gt; detailCallback)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">OutputAggregator.h</a>.</p>


<p>References <a href="#ac059d31fd5f633ad6cfe296be8ff3c4f">Aggregation</a>, <a href="#ac1be2c7a42ac407e8eac9396768207dc">GetOS</a> and <a href="#a753aa5926e1055414cb09133ac724b90">Out</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ab014307b03ade42770de6ed2f827630b">llvm::gsym::DwarfTransformer::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#abdaa5c17b22848e0de64e78984c8d07c">llvm::gsym::GsymCreator::finalize</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Aggregation {#ac059d31fd5f633ad6cfe296be8ff3c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string, unsigned&gt; llvm::gsym::OutputAggregator::Aggregation</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">OutputAggregator.h</a>.</p>


<p>Referenced by <a href="#a987b74f13eb2c94d22fb702c55b55527">EnumerateResults</a>, <a href="#a6dea9185bb17ec8a2eb7d7dba79a21f5">GetNumCategories</a>, <a href="#af65bf7475eed416d9de9a4a5e5e5ad2f">Merge</a> and <a href="#a051eee638f618d1ebe54f433350b7c1d">Report</a>.</p>

</div>
</div>

### Out {#a753aa5926e1055414cb09133ac724b90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream* llvm::gsym::OutputAggregator::Out</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">OutputAggregator.h</a>.</p>


<p>Referenced by <a href="#ac1be2c7a42ac407e8eac9396768207dc">GetOS</a>, <a href="#a81964fff9dc7844a7c7f48185a827e34">operator&lt;&lt;</a>, <a href="#a2e3b3b19e6adfc366f706660aa8255e8">OutputAggregator</a> and <a href="#a051eee638f618d1ebe54f433350b7c1d">Report</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">OutputAggregator.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
