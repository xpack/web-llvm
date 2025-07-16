---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/loop/loopbounds
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LoopBounds` Struct Reference

<p>Below are some utilities to get the loop guard, loop bounds and induction variable, and to check if a given phinode is an auxiliary induction variable, if the loop is guarded, and if the loop is canonical. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::Loop::LoopBounds { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Direction { <a href="#a1c06ad0290f168148c08edc0ce69703f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An enum for the direction of the loop. <a href="#a1c06ad0290f168148c08edc0ce69703f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d419c4815e2004cc08fdf2f5764145">LoopBounds</a> (const Loop &amp;Loop, Value &amp;I, Instruction &amp;SI, Value *SV, Value &amp;F, ScalarEvolution &amp;SE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef50b00cc2255dbd10973bfc3037ed6d">getInitialIVValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the initial value of the loop induction variable. <a href="#aef50b00cc2255dbd10973bfc3037ed6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9f6ce7426d11ba1d161c9ab70c165eb">getStepInst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the instruction that updates the loop induction variable. <a href="#aa9f6ce7426d11ba1d161c9ab70c165eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c3f3e19245c65fd42f3dd807a9f58a9">getStepValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the step that the loop induction variable gets updated by in each loop iteration. <a href="#a8c3f3e19245c65fd42f3dd807a9f58a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d893e58d8dc7d1b3453ad94392761f7">getFinalIVValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the final value of the loop induction variable. <a href="#a1d893e58d8dc7d1b3453ad94392761f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">ICmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfa250dd5ec97448681f9833e22d50cf">getCanonicalPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the canonical predicate for the latch compare instruction, if able to be calcuated. <a href="#acfa250dd5ec97448681f9833e22d50cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1c06ad0290f168148c08edc0ce69703f">Direction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add7a81b41f9b52c89fbf1e09265753f3">getDirection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the direction of the loop. <a href="#add7a81b41f9b52c89fbf1e09265753f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae21c53fd9fe7470cdbba0bd00956f98d">L</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3245a4879d1cadd9ba8c30d0c0d73c83">InitialIVValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab316f1061b8c3f0e7a9a1c8354b05381">StepInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1aca82ed8b16aff0960d4d706e95ab5">StepValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a974fcbb525c26a433e75b9ed2a3591bd">FinalIVValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad33386c385b9bb451fd251e30e288fcb">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds">Loop::LoopBounds</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a075be8282fe6debdda46c86d24a07684">getBounds</a> (const Loop &amp;L, PHINode &amp;IndVar, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds">LoopBounds</a> object if. <a href="#a075be8282fe6debdda46c86d24a07684">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Below are some utilities to get the loop guard, loop bounds and induction variable, and to check if a given phinode is an auxiliary induction variable, if the loop is guarded, and if the loop is canonical.</p>


<p>Here is an example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = lb; i &lt; ub; i+=step)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  &lt;loop body&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">--- <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp/#a31df8275bbc686a779424eb21ad67d5e">pseudo</a> LLVMIR ---</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">beforeloop:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  guardcmp = (lb &lt; ub)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (guardcmp) goto <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#aecea88f231914d2a6dc7ecf19a57f583">preheader</a>; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> afterloop</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#aecea88f231914d2a6dc7ecf19a57f583">preheader</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">loop:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  i_1 = <a href="/web-llvm/docs/api/namespaces/llvm/numbers/#a9473b507816be4056a158a41cfb86807">phi</a>[{lb, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#aecea88f231914d2a6dc7ecf19a57f583">preheader</a>}, {i_2, latch}]</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  &lt;loop body&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  i_2 = i_1 + step</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">latch:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  cmp = (i_2 &lt; ub)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cmp) </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> loop</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">exit:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">afterloop:</span></span></div>

</div>


<ul class="doxyList ">
<li>getBounds

<ul class="doxyList ">
<li>getInitialIVValue --&gt; lb</li>
<li>getStepInst --&gt; i_2 = i_1 + step</li>
<li>getStepValue --&gt; step</li>
<li>getFinalIVValue --&gt; ub</li>
<li>getCanonicalPredicate --&gt; '&lt;'</li>
<li>getDirection --&gt; Increasing</li>
</ul></li>
<li>getInductionVariable --&gt; i_1</li>
<li>isAuxiliaryInductionVariable(x) --&gt; true if x == i_1</li>
<li><a href="/web-llvm/docs/api/classes/llvm/loop/#a580a6361a2bad87e6071ecc795bdae96">getLoopGuardBranch()</a> --&gt; <span class="doxyComputerOutput">if (guardcmp) goto preheader; else goto afterloop</span></li>
<li><a href="/web-llvm/docs/api/classes/llvm/loop/#a25404d322e551103ea5a4af8686099b9">isGuarded()</a> --&gt; true</li>
<li>isCanonical --&gt; false</li>
</ul>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Direction {#a1c06ad0290f168148c08edc0ce69703f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::Loop::LoopBounds::Direction </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An enum for the direction of the loop.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Increasing<a id="a1c06ad0290f168148c08edc0ce69703faf3ff61f20d0c8eedfa348b0298df5edd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Decreasing<a id="a1c06ad0290f168148c08edc0ce69703fa2e6a9b0375c021e8f650a5eb22012b5b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unknown<a id="a1c06ad0290f168148c08edc0ce69703fa88183b946cc5f0e8c96b2e66e1c74a7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<ul class="doxyList ">
<li>for (int i = 0; i &lt; ub; ++i) --&gt; Increasing</li>
<li>for (int i = ub; i &gt; 0; –i) --&gt; Descresing</li>
<li>for (int i = x; i != y; i+=z) --&gt; Unknown</li>
</ul>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LoopBounds() {#a62d419c4815e2004cc08fdf2f5764145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Loop::LoopBounds::LoopBounds (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; Loop, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; SI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SV, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCanonicalPredicate() {#acfa250dd5ec97448681f9833e22d50cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ICmpInst::Predicate Loop::LoopBounds::getCanonicalPredicate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the canonical predicate for the latch compare instruction, if able to be calcuated.</p>


<p>Else BAD_ICMP_PREDICATE.</p>


<p>A predicate is considered as canonical if requirements below are all satisfied:</p>


<ol class="doxyList" type="1">
<li>The first successor of the latch branch is the loop header If not, inverse the predicate.</li>
<li>One of the operands of the latch comparison is StepInst If not, and

<ul class="doxyList ">
<li>if the current calcuated predicate is not ne or eq, flip the predicate.</li>
<li>else if the loop is increasing, return slt (notice that it is safe to change from ne or eq to sign compare)</li>
<li>else if the loop is decreasing, return sgt (notice that it is safe to change from ne or eq to sign compare)</li>
</ul></li>
</ol>

<p>Here is an example when both (1) and (2) are not satisfied:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">loop.header:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"> %iv = <a href="/web-llvm/docs/api/namespaces/llvm/numbers/#a9473b507816be4056a158a41cfb86807">phi</a> [%initialiv, %loop.preheader], [%inc, %loop.header]</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"> %inc = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> %iv, %step</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"> %cmp = slt %iv, %finaliv</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"> br %cmp, %loop.exit, %loop.header</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">loop.exit:</span></span></div>

</div>


<ul class="doxyList ">
<li>The second successor of the latch branch is the loop header instead of the first successor (slt -&gt; sge)</li>
<li>The first operand of the latch comparison (cmp) is the IndVar (iv) instead of the StepInst (inc) (sge -&gt; sgt)</li>
</ul>

<p>The predicate would be sgt if both (1) and (2) are satisfied. <a href="#acfa250dd5ec97448681f9833e22d50cf">getCanonicalPredicate()</a> returns sgt for this example. Note: The IR is not changed.</p>


<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">llvm::CmpInst::BAD_ICMP_PREDICATE</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aebd4af5642453ce3169094f08dd3d7b8">llvm::BranchInst::getCondition</a>, <a href="#add7a81b41f9b52c89fbf1e09265753f3">getDirection</a>, <a href="#a1d893e58d8dc7d1b3453ad94392761f7">getFinalIVValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aafc99bbdcf56632d353043ae3e2bca21">llvm::CmpInst::getFlippedStrictnessPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="#aa9f6ce7426d11ba1d161c9ab70c165eb">getStepInst</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a> and <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a7e4be8b16fbd68c9045a388904044e01">llvm::BranchInst::isConditional</a>.</p>

</div>
</div>

### getDirection() {#add7a81b41f9b52c89fbf1e09265753f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Direction Loop::LoopBounds::getDirection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the direction of the loop.</p>

<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#aa9f6ce7426d11ba1d161c9ab70c165eb">getStepInst</a>.</p>


<p>Referenced by <a href="#acfa250dd5ec97448681f9833e22d50cf">getCanonicalPredicate</a>.</p>

</div>
</div>

### getFinalIVValue() {#a1d893e58d8dc7d1b3453ad94392761f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value &amp; llvm::Loop::LoopBounds::getFinalIVValue ()</td>
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

<p>Get the final value of the loop induction variable.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>


<p>Referenced by <a href="#acfa250dd5ec97448681f9833e22d50cf">getCanonicalPredicate</a>.</p>

</div>
</div>

### getInitialIVValue() {#aef50b00cc2255dbd10973bfc3037ed6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value &amp; llvm::Loop::LoopBounds::getInitialIVValue ()</td>
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

<p>Get the initial value of the loop induction variable.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

### getStepInst() {#aa9f6ce7426d11ba1d161c9ab70c165eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction &amp; llvm::Loop::LoopBounds::getStepInst ()</td>
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

<p>Get the instruction that updates the loop induction variable.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>


<p>Referenced by <a href="#acfa250dd5ec97448681f9833e22d50cf">getCanonicalPredicate</a> and <a href="#add7a81b41f9b52c89fbf1e09265753f3">getDirection</a>.</p>

</div>
</div>

### getStepValue() {#a8c3f3e19245c65fd42f3dd807a9f58a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::Loop::LoopBounds::getStepValue ()</td>
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

<p>Get the step that the loop induction variable gets updated by in each loop iteration.</p>


<p>Return nullptr if not found.</p>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FinalIVValue {#a974fcbb525c26a433e75b9ed2a3591bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value&amp; llvm::Loop::LoopBounds::FinalIVValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

### InitialIVValue {#a3245a4879d1cadd9ba8c30d0c0d73c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value&amp; llvm::Loop::LoopBounds::InitialIVValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

### L {#ae21c53fd9fe7470cdbba0bd00956f98d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop&amp; llvm::Loop::LoopBounds::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

### SE {#ad33386c385b9bb451fd251e30e288fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; llvm::Loop::LoopBounds::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

### StepInst {#ab316f1061b8c3f0e7a9a1c8354b05381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction&amp; llvm::Loop::LoopBounds::StepInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

### StepValue {#ac1aca82ed8b16aff0960d4d706e95ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::Loop::LoopBounds::StepValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getBounds() {#a075be8282fe6debdda46c86d24a07684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Loop::LoopBounds &gt; Loop::LoopBounds::getBounds (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; IndVar, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds">LoopBounds</a> object if.</p>


<ul class="doxyList ">
<li>the given <span class="doxyComputerOutput">IndVar</span> is an induction variable</li>
<li>the initial value of the induction variable can be found</li>
<li>the step instruction of the induction variable can be found</li>
<li>the final value of the induction variable can be found</li>
</ul>

<p>Else std::nullopt.</p>


<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#aab83ba77d9d7f1be86b2f06abe3f1bdb">findFinalIVValue</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a02906e4d107570bd0727048a4b0df9a5">llvm::InductionDescriptor::getInductionBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#aea63dae61a488e20e237f5f517ed1491">llvm::InductionDescriptor::getStartValue</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a83b5b65084a0c1de3a76f36f198b1b0c">llvm::InductionDescriptor::getStep</a> and <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loop/#a096b15bbaad7c5f24d29b0592339b9e8">llvm::Loop::getBounds</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
