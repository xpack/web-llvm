---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/dot
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `DOT` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::DOT { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cab6453a8243573f35f162cd94f33ba">EscapeString</a> (const std::string &amp;Label)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ec6bb0b1bfe75533186557a9077d28">getColorString</a> (unsigned NodeNumber)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a color string for this node number. <a href="#a65ec6bb0b1bfe75533186557a9077d28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### EscapeString() {#a4cab6453a8243573f35f162cd94f33ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOT::EscapeString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/graphwriter-h">GraphWriter.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/support/graphwriter-cpp">GraphWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplanprinter/#abf65de021b888eeddb9cc578116d9211">llvm::VPlanPrinter::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/graphwriter/#a5f409f860e49edb941120a2908613c43">llvm::GraphWriter&lt; GraphType &gt;::emitSimpleNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#aa23cb08728e5bb13e2bf43eb614c3efa">printNodeDOT</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraphdotprinterpass/#a172985546be95f992c665ac5d82e4a08">llvm::LazyCallGraphDOTPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/graphwriter/#ae6d4aa3516673900b59b36270de4d327">llvm::GraphWriter&lt; GraphType &gt;::writeHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/graphwriter/#a2f9acb4356fb561c08c041c7761210d8">llvm::GraphWriter&lt; GraphType &gt;::writeNode</a>.</p>

</div>
</div>

### getColorString() {#a65ec6bb0b1bfe75533186557a9077d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DOT::getColorString (unsigned ColorNumber)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a color string for this node number.</p>


<p>Simply round-robin selects from a reasonable number of colors.</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/graphwriter-h">GraphWriter.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/support/graphwriter-cpp">GraphWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-3e4d2beef0711eb028dcc7799677e405/#aeec5b7bbdeddc6e81486c44f34c5975a">llvm::DOTGraphTraits&lt; ScheduleDAGMI * &gt;::getNodeAttributes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/graphwriter-h">GraphWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/graphwriter-cpp">GraphWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
