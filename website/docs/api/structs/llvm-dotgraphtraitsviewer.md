---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dotgraphtraitsviewer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DOTGraphTraitsViewer` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename AnalysisT, bool IsSimple, typename GraphT = typename AnalysisT::Result *, typename AnalysisGraphTraitsT = DefaultAnalysisGraphTraits&lt;typename AnalysisT::Result &amp;, GraphT&gt;&gt;
struct llvm::DOTGraphTraitsViewer&lt;AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">llvm/Analysis/DOTGraphTraitsPass.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a925bda662ebad797fd6e0d3130423183">DOTGraphTraitsViewer</a> (StringRef GraphName)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a60e99be77348c5e34276c770b2dd68aa">~DOTGraphTraitsViewer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Avoid compiler warning "has virtual functions but non-virtual destructor
[-Wnon-virtual-dtor]" in derived classes. <a href="#a60e99be77348c5e34276c770b2dd68aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af4e6c4871a90af42bfab2f6f9bc6ad16">processFunction</a> (Function &amp;F, const typename AnalysisT::Result &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this function should be processed. <a href="#af4e6c4871a90af42bfab2f6f9bc6ad16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a785d4e2677b22a4dc41713c1e82c492f">run</a> (Function &amp;F, FunctionAnalysisManager &amp;FAM)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1700cce7ebe2968654c5ed155e920d9a">Name</a></td>
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


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DOTGraphTraitsViewer() {#a925bda662ebad797fd6e0d3130423183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT, bool IsSimple, typename GraphT = typename AnalysisT::Result *, typename AnalysisGraphTraitsT = DefaultAnalysisGraphTraits&lt;typename AnalysisT::Result &amp;, GraphT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DOTGraphTraitsViewer&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::DOTGraphTraitsViewer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GraphName)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~DOTGraphTraitsViewer() {#a60e99be77348c5e34276c770b2dd68aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT, bool IsSimple, typename GraphT = typename AnalysisT::Result *, typename AnalysisGraphTraitsT = DefaultAnalysisGraphTraits&lt;typename AnalysisT::Result &amp;, GraphT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DOTGraphTraitsViewer&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::~DOTGraphTraitsViewer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Avoid compiler warning "has virtual functions but non-virtual destructor
[-Wnon-virtual-dtor]" in derived classes.</p>


<p><a href="/web-llvm/docs/api/structs/llvm/dotgraphtraitsviewer">DOTGraphTraitsViewer</a> is also used as a mixin for avoiding repeated implementation of viewer passes, ie there should be no runtime-polymorphisms/downcasting involving this class and hence no virtual destructor needed. Making this dtor protected stops accidental invocation when the derived class destructor should have been called. Those derived classes sould be marked final to avoid the warning.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### processFunction() {#af4e6c4871a90af42bfab2f6f9bc6ad16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT, bool IsSimple, typename GraphT = typename AnalysisT::Result *, typename AnalysisGraphTraitsT = DefaultAnalysisGraphTraits&lt;typename AnalysisT::Result &amp;, GraphT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::DOTGraphTraitsViewer&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::processFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename AnalysisT::Result &amp; Result)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this function should be processed.</p>


<p>An implementation of this class my override this function to indicate that only certain functions should be viewed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>The current analysis result for this function.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a785d4e2677b22a4dc41713c1e82c492f">llvm::DOTGraphTraitsViewer&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::run</a>.</p>

</div>
</div>

### run() {#a785d4e2677b22a4dc41713c1e82c492f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT, bool IsSimple, typename GraphT = typename AnalysisT::Result *, typename AnalysisGraphTraitsT = DefaultAnalysisGraphTraits&lt;typename AnalysisT::Result &amp;, GraphT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses llvm::DOTGraphTraitsViewer&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="#af4e6c4871a90af42bfab2f6f9bc6ad16">llvm::DOTGraphTraitsViewer&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::processFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a430d86ec8e1580b56c1e87a5109c5cb6">llvm::viewGraphForFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Name {#a1700cce7ebe2968654c5ed155e920d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT, bool IsSimple, typename GraphT = typename AnalysisT::Result *, typename AnalysisGraphTraitsT = DefaultAnalysisGraphTraits&lt;typename AnalysisT::Result &amp;, GraphT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DOTGraphTraitsViewer&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
