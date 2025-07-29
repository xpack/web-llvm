---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aggressiveinstcombine-cpp-/strncmpinliner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `StrNCmpInliner` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AggressiveInstCombine.cpp}::StrNCmpInliner { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a98f71dd14d83355b08b9921c3899d1">StrNCmpInliner</a> (CallInst *CI, LibFunc Func, DomTreeUpdater *DTU, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d71bcb73b24374e675d3ac3b8f5e8b">optimizeStrNCmp</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>First we normalize calls to strncmp/strcmp to the form of compare(s1, s2, N), which means comparing first N bytes of s1 and s2 (without considering '\0'). <a href="#ac9d71bcb73b24374e675d3ac3b8f5e8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa45bb97a2545ac411b158bdbedf2ebef">inlineCompare</a> (Value *LHS, StringRef RHS, uint64_t N, bool Swapped)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert. <a href="#aa45bb97a2545ac411b158bdbedf2ebef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1a5fd8274376225fe26ac5b37c0a99b">CI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2e04927d045bbc52de719210778a8ef">Func</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52389dd1d83f6c60e5a84502e59a8769">DTU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92c2c92b98b8317dd087aba95ed14786">DL</a></td>
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


<p>Definition at line 919 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp">AggressiveInstCombine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StrNCmpInliner() {#a6a98f71dd14d83355b08b9921c3899d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AggressiveInstCombine.cpp}::StrNCmpInliner::StrNCmpInliner (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> Func, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp">AggressiveInstCombine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#af1da24e35a7154a7043bc87d971982a6">foldLibCalls</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### optimizeStrNCmp() {#ac9d71bcb73b24374e675d3ac3b8f5e8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StrNCmpInliner::optimizeStrNCmp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>First we normalize calls to strncmp/strcmp to the form of compare(s1, s2, N), which means comparing first N bytes of s1 and s2 (without considering '\0').</p>


<p>Examples:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">strncmp(s, </span><span class="doxyHighlightStringLiteral">"a"</span><span class="doxyHighlight">, 3) -&gt; <a href="/web-llvm/docs/api/namespaces/llvm/scalednumbers/#a0651aa0a52c69c4fe12cf730e7ed65ab">compare</a>(s, </span><span class="doxyHighlightStringLiteral">"a"</span><span class="doxyHighlight">, 2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">strncmp(s, </span><span class="doxyHighlightStringLiteral">"abc"</span><span class="doxyHighlight">, 3) -&gt; compare(s, </span><span class="doxyHighlightStringLiteral">"abc"</span><span class="doxyHighlight">, 3)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">strncmp(s, </span><span class="doxyHighlightStringLiteral">"a\0b"</span><span class="doxyHighlight">, 3) -&gt; compare(s, </span><span class="doxyHighlightStringLiteral">"a\0b"</span><span class="doxyHighlight">, 2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">strcmp(s, </span><span class="doxyHighlightStringLiteral">"a"</span><span class="doxyHighlight">) -&gt; compare(s, </span><span class="doxyHighlightStringLiteral">"a"</span><span class="doxyHighlight">, 2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> s2[] = {</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">strncmp(s, s2, 3) -&gt; <a href="/web-llvm/docs/api/namespaces/llvm/scalednumbers/#a0651aa0a52c69c4fe12cf730e7ed65ab">compare</a>(s, s2, 3)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">char s2[] = {</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight">, </span><span class="doxyHighlightCharLiteral">'b'</span><span class="doxyHighlight">, </span><span class="doxyHighlightCharLiteral">'c'</span><span class="doxyHighlight">, </span><span class="doxyHighlightCharLiteral">'d'</span><span class="doxyHighlight">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">strncmp(s, s2, 3) -&gt; <a href="/web-llvm/docs/api/namespaces/llvm/scalednumbers/#a0651aa0a52c69c4fe12cf730e7ed65ab">compare</a>(s, s2, 3)</span></span></div>

</div>


<p>We only handle cases where N and exactly one of s1 and s2 are constant. Cases that s1 and s2 are both constant are already handled by the instcombine pass.</p>


<p>We do not handle cases where N &gt; StrNCmpInlineThreshold.</p>


<p>We also do not handles cases where N &lt; 2, which are already handled by the instcombine pass.</p>


<p>Definition at line 925 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp">AggressiveInstCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2bcd261c0da622d37e1c5aeb02496e12">llvm::getConstantStringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#acfdc7354dccb27bc092d9ac8c92b76c7">llvm::Value::getPointerDereferenceableBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2668ffbfda69c33fb1e12266d882b191">llvm::isOnlyUsedInZeroComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#ad0f54a163ac500b144590640c6f1eb6b">anonymous{Path.cpp}::StringRef::npos</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a433e643adece00c5f916ddc504fc9110">StrNCmpInlineThreshold</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#af1da24e35a7154a7043bc87d971982a6">foldLibCalls</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### inlineCompare() {#aa45bb97a2545ac411b158bdbedf2ebef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StrNCmpInliner::inlineCompare (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS, uint64_t N, bool Swapped)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">ret = <a href="/web-llvm/docs/api/namespaces/llvm/scalednumbers/#a0651aa0a52c69c4fe12cf730e7ed65ab">compare</a>(s1, s2, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>)</span></span></div>

</div>


<p>into</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">ret = (int)s1[0] - (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)s2[0]</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ret != 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28a191e89dbc4939ebd0b572cae44aac05f">NE</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">ret = (int)s1[<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>-2] - (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)s2[<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>-2]</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ret != 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28a191e89dbc4939ebd0b572cae44aac05f">NE</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">ret = (int)s1[<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>-1] - (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)s2[<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>-1]</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28a191e89dbc4939ebd0b572cae44aac05f">NE</a>:</span></span></div>

</div>


<p>CFG before and after the transformation:</p>


<p>(before) BBCI</p>


<p>(after) BBCI -&gt; BBSubs[0] (sub,icmp) –NE-&gt; BBNE -&gt; BBTail | ^ E | | | BBSubs[1] (sub,icmp) –NE--—+ ... | BBSubs[N-1] (sub) ------—+</p>


<p>Definition at line 928 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp">AggressiveInstCombine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CI {#ab1a5fd8274376225fe26ac5b37c0a99b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst* anonymous{AggressiveInstCombine.cpp}::StrNCmpInliner::CI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp">AggressiveInstCombine.cpp</a>.</p>

</div>
</div>

### DL {#a92c2c92b98b8317dd087aba95ed14786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{AggressiveInstCombine.cpp}::StrNCmpInliner::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 933 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp">AggressiveInstCombine.cpp</a>.</p>

</div>
</div>

### DTU {#a52389dd1d83f6c60e5a84502e59a8769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeUpdater* anonymous{AggressiveInstCombine.cpp}::StrNCmpInliner::DTU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 932 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp">AggressiveInstCombine.cpp</a>.</p>

</div>
</div>

### Func {#ab2e04927d045bbc52de719210778a8ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LibFunc anonymous{AggressiveInstCombine.cpp}::StrNCmpInliner::Func</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp">AggressiveInstCombine.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp">AggressiveInstCombine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
