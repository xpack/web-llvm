---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-symbolrewriter-cpp-/patternrewritedescriptor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PatternRewriteDescriptor` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;RewriteDescriptor::Type DT, typename ValueType, ValueType *(Module::*)(StringRef) const Get, iterator_range&lt; typename iplist&lt; ValueType &gt;::iterator &gt;(Module::*)() Iterator&gt;
class anonymous{SymbolRewriter.cpp}::PatternRewriteDescriptor&lt;DT, ValueType, Get, Iterator&gt; { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/symbolrewriter/rewritedescriptor">RewriteDescriptor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The basic entity representing a rewrite operation. <a href="/web-llvm/docs/api/classes/llvm/symbolrewriter/rewritedescriptor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a383e7504bb441ccc0eaebda5870030e6">PatternRewriteDescriptor</a> (StringRef P, StringRef T)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a634757052a33e4bba359e83b8b33199a">performOnModule</a> (Module &amp;M) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2d0dd9a10e7c8e6d05d6c9c0daba1eed">Pattern</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a011c0e662ff0f7763f776fb52da73ac7">Transform</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af7083ff725f489214631ad45ed39a6e6">classof</a> (const RewriteDescriptor *RD)</td>
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


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PatternRewriteDescriptor() {#a383e7504bb441ccc0eaebda5870030e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;RewriteDescriptor::Type DT, typename ValueType, ValueType *(Module::*)(StringRef) const Get, iterator_range&lt; typename iplist&lt; ValueType &gt;::iterator &gt;(Module::*)() Iterator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SymbolRewriter.cpp}::PatternRewriteDescriptor&lt; DT, ValueType, Get, Iterator &gt;::PatternRewriteDescriptor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> P, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> T)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### performOnModule() {#a634757052a33e4bba359e83b8b33199a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;RewriteDescriptor::Type DT, typename ValueType, ValueType *(Module::*)(StringRef) const Get, iterator_range&lt; typename iplist&lt; ValueType &gt;::iterator &gt;(Module::*)() Iterator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PatternRewriteDescriptor::performOnModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a2d0dd9a10e7c8e6d05d6c9c0daba1eed">anonymous{SymbolRewriter.cpp}::PatternRewriteDescriptor&lt; DT, ValueType, Get, Iterator &gt;::Pattern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp/#aabf6669a0eeb25780619fa043d4c945a">rewriteComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a> and <a href="#a011c0e662ff0f7763f776fb52da73ac7">anonymous{SymbolRewriter.cpp}::PatternRewriteDescriptor&lt; DT, ValueType, Get, Iterator &gt;::Transform</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Pattern {#a2d0dd9a10e7c8e6d05d6c9c0daba1eed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;RewriteDescriptor::Type DT, typename ValueType, ValueType *(Module::*)(StringRef) const Get, iterator_range&lt; typename iplist&lt; ValueType &gt;::iterator &gt;(Module::*)() Iterator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{SymbolRewriter.cpp}::PatternRewriteDescriptor&lt; DT, ValueType, Get, Iterator &gt;::Pattern</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>


<p>Referenced by <a href="#a634757052a33e4bba359e83b8b33199a">anonymous{SymbolRewriter.cpp}::PatternRewriteDescriptor&lt; DT, ValueType, Get, Iterator &gt;::performOnModule</a>.</p>

</div>
</div>

### Transform {#a011c0e662ff0f7763f776fb52da73ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;RewriteDescriptor::Type DT, typename ValueType, ValueType *(Module::*)(StringRef) const Get, iterator_range&lt; typename iplist&lt; ValueType &gt;::iterator &gt;(Module::*)() Iterator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{SymbolRewriter.cpp}::PatternRewriteDescriptor&lt; DT, ValueType, Get, Iterator &gt;::Transform</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>


<p>Referenced by <a href="#a634757052a33e4bba359e83b8b33199a">anonymous{SymbolRewriter.cpp}::PatternRewriteDescriptor&lt; DT, ValueType, Get, Iterator &gt;::performOnModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#af7083ff725f489214631ad45ed39a6e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;RewriteDescriptor::Type DT, typename ValueType, ValueType *(Module::*)(StringRef) const Get, iterator_range&lt; typename iplist&lt; ValueType &gt;::iterator &gt;(Module::*)() Iterator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SymbolRewriter.cpp}::PatternRewriteDescriptor&lt; DT, ValueType, Get, Iterator &gt;::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/symbolrewriter/rewritedescriptor">RewriteDescriptor</a> * RD)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
