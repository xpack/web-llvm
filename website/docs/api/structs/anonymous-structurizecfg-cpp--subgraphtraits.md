---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-structurizecfg-cpp-/subgraphtraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SubGraphTraits` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{StructurizeCFG.cpp}::SubGraphTraits { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0baba70bd6271bebf47ff10152276c">NodeRef</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> * &gt; * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a384ab8915be86fdf1d813df57abc77c8">BaseSuccIterator</a> = <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> * &gt;<a href="/web-llvm/docs/api/structs/llvm/graphtraits">::ChildIteratorType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a856425616ace6b42c18b1ab454c00c11">ChildIteratorType</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">filter_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/subgraphtraits/wrappedsucciterator">WrappedSuccIterator</a>, bool(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#afd0baba70bd6271bebf47ff10152276c">NodeRef</a> &amp;)&gt;</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d23468b7199813de9814c909ace4fd">filterAll</a> (const NodeRef &amp;N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac54e97dc0b60db5b332df29b11d56a8">filterSet</a> (const NodeRef &amp;N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#afd0baba70bd6271bebf47ff10152276c">NodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34895557d71e0559ff91d451eaf4025d">getEntryNode</a> (Region *R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#afd0baba70bd6271bebf47ff10152276c">NodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3649381b603017749af04afd7e762f7">getEntryNode</a> (NodeRef N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a856425616ace6b42c18b1ab454c00c11">ChildIteratorType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79fd37f041d978a7007cbd751eb9665">children</a> (const NodeRef &amp;N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a856425616ace6b42c18b1ab454c00c11">ChildIteratorType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a57cd464713ac766df43d7ee1a13b2b">child_begin</a> (const NodeRef &amp;N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a856425616ace6b42c18b1ab454c00c11">ChildIteratorType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdcafb537a0536ad04b4787c14116248">child_end</a> (const NodeRef &amp;N)</td>
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


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BaseSuccIterator {#a384ab8915be86fdf1d813df57abc77c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{StructurizeCFG.cpp}::SubGraphTraits::BaseSuccIterator =  GraphTraits&lt;RegionNode *&gt;::ChildIteratorType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### ChildIteratorType {#a856425616ace6b42c18b1ab454c00c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{StructurizeCFG.cpp}::SubGraphTraits::ChildIteratorType = 
      filter_iterator&lt;WrappedSuccIterator, bool (*)(const NodeRef &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### NodeRef {#afd0baba70bd6271bebf47ff10152276c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{StructurizeCFG.cpp}::SubGraphTraits::NodeRef =  std::pair&lt;RegionNode *, SmallDenseSet&lt;RegionNode *&gt; *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### child\_begin() {#a2a57cd464713ac766df43d7ee1a13b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChildIteratorType anonymous{StructurizeCFG.cpp}::SubGraphTraits::child_begin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#afd0baba70bd6271bebf47ff10152276c">NodeRef</a> &amp; N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">llvm::children</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### child\_end() {#acdcafb537a0536ad04b4787c14116248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChildIteratorType anonymous{StructurizeCFG.cpp}::SubGraphTraits::child_end (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#afd0baba70bd6271bebf47ff10152276c">NodeRef</a> &amp; N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">llvm::children</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### children() {#ab79fd37f041d978a7007cbd751eb9665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; ChildIteratorType &gt; anonymous{StructurizeCFG.cpp}::SubGraphTraits::children (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#afd0baba70bd6271bebf47ff10152276c">NodeRef</a> &amp; N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>References <a href="#a12d23468b7199813de9814c909ace4fd">filterAll</a>, <a href="#aac54e97dc0b60db5b332df29b11d56a8">filterSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### filterAll() {#a12d23468b7199813de9814c909ace4fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{StructurizeCFG.cpp}::SubGraphTraits::filterAll (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#afd0baba70bd6271bebf47ff10152276c">NodeRef</a> &amp; N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#ab79fd37f041d978a7007cbd751eb9665">children</a>.</p>

</div>
</div>

### filterSet() {#aac54e97dc0b60db5b332df29b11d56a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{StructurizeCFG.cpp}::SubGraphTraits::filterSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#afd0baba70bd6271bebf47ff10152276c">NodeRef</a> &amp; N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#ab79fd37f041d978a7007cbd751eb9665">children</a>.</p>

</div>
</div>

### getEntryNode() {#a34895557d71e0559ff91d451eaf4025d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef anonymous{StructurizeCFG.cpp}::SubGraphTraits::getEntryNode (<a href="/web-llvm/docs/api/classes/llvm/region">Region</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### getEntryNode() {#ad3649381b603017749af04afd7e762f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef anonymous{StructurizeCFG.cpp}::SubGraphTraits::getEntryNode (<a href="#afd0baba70bd6271bebf47ff10152276c">NodeRef</a> N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
