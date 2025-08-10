---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-debugutils-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{DebugUtils.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{DebugUtils.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugutils-cpp-/printall">PrintAll&lt;T&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-debugutils-cpp-/sequenceprinter">SequencePrinter&lt;Sequence, Pred&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugutils-cpp-/printsymbolflagsmapelemsmatchingclopts">PrintSymbolFlagsMapElemsMatchingCLOpts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugutils-cpp-/printsymbolmapelemsmatchingclopts">PrintSymbolMapElemsMatchingCLOpts</a></td>
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

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Sequence, typename Pred&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3e5dd3fc582ce67a904121b6b9360f53">operator&lt;&lt;</a> (llvm::raw_ostream &amp;OS, const SequencePrinter&lt; Sequence, Pred &gt; &amp;Printer)</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d2735b18a80cee6de0303ddb41b147">anyPrintSymbolOptionSet</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7169841385f74ebfe3107720ef2b6e9b">flagsMatchCLOpts</a> (const JITSymbolFlags &amp;Flags)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Sequence, typename Pred&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a69f9fdf6717b2b765d1bff6d563e98c5">printSequence</a> (const Sequence &amp;S, char OpenSeq, char CloseSeq, Pred P=Pred()) -&gt; <a href="/web-llvm/docs/api/classes/anonymous-debugutils-cpp-/sequenceprinter">SequencePrinter</a>&lt; Sequence, Pred &gt;</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c7e8c00527b45e0de1c0d1b1e63e13f">PrintHidden</a>("debug-orc-print-hidden", cl::init(true), cl::desc("debug print hidden symbols defined by " "materialization units"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0c6ad7f14e63d3506f5d6937d38311">PrintCallable</a>("debug-orc-print-callable", cl::init(true), cl::desc("debug print callable symbols defined by " "materialization units"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaea450801f4bc5cb41d956245163c401">PrintData</a>("debug-orc-print-data", cl::init(true), cl::desc("debug print data symbols defined by " "materialization units"), cl::Hidden)</td>
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


<div class="doxySectionDef">

## Operators

### operator&lt;&lt;() {#a3e5dd3fc582ce67a904121b6b9360f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Sequence, typename Pred&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::raw_ostream &amp; anonymous{DebugUtils.cpp}::operator&lt;&lt; (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-debugutils-cpp-/sequenceprinter">SequencePrinter</a>&lt; Sequence, Pred &gt; &amp; Printer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### anyPrintSymbolOptionSet() {#a12d2735b18a80cee6de0303ddb41b147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DebugUtils.cpp}::anyPrintSymbolOptionSet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a>.</p>


<p>References <a href="#a0f0c6ad7f14e63d3506f5d6937d38311">PrintCallable</a>, <a href="#aaea450801f4bc5cb41d956245163c401">PrintData</a> and <a href="#a2c7e8c00527b45e0de1c0d1b1e63e13f">PrintHidden</a>.</p>

</div>
</div>

### flagsMatchCLOpts() {#a7169841385f74ebfe3107720ef2b6e9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DebugUtils.cpp}::flagsMatchCLOpts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> &amp; Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a>.</p>


<p>References <a href="#a0f0c6ad7f14e63d3506f5d6937d38311">PrintCallable</a>, <a href="#aaea450801f4bc5cb41d956245163c401">PrintData</a> and <a href="#a2c7e8c00527b45e0de1c0d1b1e63e13f">PrintHidden</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-debugutils-cpp-/printsymbolflagsmapelemsmatchingclopts/#a2744121dfe094bc78eca334e10f93e2a">anonymous{DebugUtils.cpp}::PrintSymbolFlagsMapElemsMatchingCLOpts::operator()</a> and <a href="/web-llvm/docs/api/structs/anonymous-debugutils-cpp-/printsymbolmapelemsmatchingclopts/#a79963919c301b1c9e23af75e1930514b">anonymous{DebugUtils.cpp}::PrintSymbolMapElemsMatchingCLOpts::operator()</a>.</p>

</div>
</div>

### printSequence() {#a69f9fdf6717b2b765d1bff6d563e98c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Sequence, typename Pred&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SequencePrinter&lt; Sequence, Pred &gt; anonymous{DebugUtils.cpp}::printSequence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Sequence &amp; S, char OpenSeq, char CloseSeq, Pred P=Pred())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/anonymous-debugutils-cpp-/sequenceprinter/#a4796d97a1d5ce3d758cc2cf56a3925fe">anonymous{DebugUtils.cpp}::SequencePrinter&lt; Sequence, Pred &gt;::SequencePrinter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### PrintCallable {#a0f0c6ad7f14e63d3506f5d6937d38311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{DebugUtils.cpp}::PrintCallable("debug-orc-print-callable", cl::init(true), cl::desc("debug print callable symbols defined by " "materialization units"), cl::Hidden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a>.</p>


<p>Referenced by <a href="#a12d2735b18a80cee6de0303ddb41b147">anyPrintSymbolOptionSet</a> and <a href="#a7169841385f74ebfe3107720ef2b6e9b">flagsMatchCLOpts</a>.</p>

</div>
</div>

### PrintData {#aaea450801f4bc5cb41d956245163c401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{DebugUtils.cpp}::PrintData("debug-orc-print-data", cl::init(true), cl::desc("debug print data symbols defined by " "materialization units"), cl::Hidden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a>.</p>


<p>Referenced by <a href="#a12d2735b18a80cee6de0303ddb41b147">anyPrintSymbolOptionSet</a> and <a href="#a7169841385f74ebfe3107720ef2b6e9b">flagsMatchCLOpts</a>.</p>

</div>
</div>

### PrintHidden {#a2c7e8c00527b45e0de1c0d1b1e63e13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{DebugUtils.cpp}::PrintHidden("debug-orc-print-hidden", cl::init(true), cl::desc("debug print hidden symbols defined by " "materialization units"), cl::Hidden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a>.</p>


<p>Referenced by <a href="#a12d2735b18a80cee6de0303ddb41b147">anyPrintSymbolOptionSet</a> and <a href="#a7169841385f74ebfe3107720ef2b6e9b">flagsMatchCLOpts</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
