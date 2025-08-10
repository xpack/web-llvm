---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/legalityresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LegalityResult` Class

<p>The legality outcome is represented by a class rather than an enum class because in some cases the legality checks are expensive and look for a particular instruction that can be passed along to the vectorizer to avoid repeating the same expensive computation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::LegalityResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">llvm/Transforms/Vectorize/SandboxVectorizer/Legality.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreuse">DiamondReuse</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreusemultiinput">DiamondReuseMultiInput</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreusewithshuffle">DiamondReuseWithShuffle</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityresultwithreason">LegalityResultWithReason</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for results with reason. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityresultwithreason/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/widen">Widen</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56eca949fe2f0a2f7fd274ff5854abf9">LegalityAnalysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33b521a75a6c136e5dbe5533e8983624">operator&lt;&lt;</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb7e37e3a1dd3b7cb1b54c1299d3418f">LegalityResult</a> (LegalityResultID ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only Legality can create LegalityResults. <a href="#adb7e37e3a1dd3b7cb1b54c1299d3418f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae93089216c699bb1ac4fb12f219c170a">LegalityResult</a> (const LegalityResult &amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We shouldn't need copies. <a href="#ae93089216c699bb1ac4fb12f219c170a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5769ba33f80a3a7908f060fdc41cbd8f">~LegalityResult</a> ()</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityresult">LegalityResult</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a019abad21252fb1ce3b1a7d88d543f09">operator=</a> (const LegalityResult &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a26b0c28c43366c455232e14a5ebee1b6">LegalityResultID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe732481be34af1d8d4057e05f3b53f2">getSubclassID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac45ada55c2eb4f56eac51088fed5d4e2">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93d24c55e4f135833a83f6e099eaba6b">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a26b0c28c43366c455232e14a5ebee1b6">LegalityResultID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656a668a4f4c6eff3825ed7e31d5c1eb">ID</a></td>
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

<p>The legality outcome is represented by a class rather than an enum class because in some cases the legality checks are expensive and look for a particular instruction that can be passed along to the vectorizer to avoid repeating the same expensive computation.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<div class="doxySectionDef">

## Friends

### LegalityAnalysis {#a56eca949fe2f0a2f7fd274ff5854abf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityanalysis">LegalityAnalysis</a></td>
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


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<p>Reference <a href="#a56eca949fe2f0a2f7fd274ff5854abf9">LegalityAnalysis</a>.</p>


<p>Referenced by <a href="#a56eca949fe2f0a2f7fd274ff5854abf9">LegalityAnalysis</a>.</p>

</div>
</div>

### operator&lt;&lt; {#a33b521a75a6c136e5dbe5533e8983624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityresult">LegalityResult</a> &amp; LR</td>
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


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<p>References <a href="#adb7e37e3a1dd3b7cb1b54c1299d3418f">LegalityResult</a> and <a href="#ac45ada55c2eb4f56eac51088fed5d4e2">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### LegalityResult() {#adb7e37e3a1dd3b7cb1b54c1299d3418f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::LegalityResult::LegalityResult (<a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a26b0c28c43366c455232e14a5ebee1b6">LegalityResultID</a> ID)</td>
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

<p>Only Legality can create LegalityResults.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<p>Reference <a href="#a656a668a4f4c6eff3825ed7e31d5c1eb">ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreuse/#a5e3e5f0d1fa304f9420d514406be7952">llvm::sandboxir::DiamondReuse::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreusemultiinput/#acde69f9f488f91d2ce43a6814fd445ca">llvm::sandboxir::DiamondReuseMultiInput::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreusewithshuffle/#a7413d02ed0a575e82f0c8b6b92fbd2c2">llvm::sandboxir::DiamondReuseWithShuffle::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/widen/#acff3eaa56dec058e3025a3df864f6cf5">llvm::sandboxir::Widen::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreuse/#a56eca949fe2f0a2f7fd274ff5854abf9">llvm::sandboxir::DiamondReuse::LegalityAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreusemultiinput/#a56eca949fe2f0a2f7fd274ff5854abf9">llvm::sandboxir::DiamondReuseMultiInput::LegalityAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreusewithshuffle/#a56eca949fe2f0a2f7fd274ff5854abf9">llvm::sandboxir::DiamondReuseWithShuffle::LegalityAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/widen/#a56eca949fe2f0a2f7fd274ff5854abf9">llvm::sandboxir::Widen::LegalityAnalysis</a>, <a href="#ae93089216c699bb1ac4fb12f219c170a">LegalityResult</a>, <a href="#a33b521a75a6c136e5dbe5533e8983624">operator&lt;&lt;</a> and <a href="#a019abad21252fb1ce3b1a7d88d543f09">operator=</a>.</p>

</div>
</div>

### LegalityResult() {#ae93089216c699bb1ac4fb12f219c170a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::LegalityResult::LegalityResult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityresult">LegalityResult</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We shouldn't need copies.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<p>Reference <a href="#adb7e37e3a1dd3b7cb1b54c1299d3418f">LegalityResult</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LegalityResult() {#a5769ba33f80a3a7908f060fdc41cbd8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::sandboxir::LegalityResult::~LegalityResult ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#a019abad21252fb1ce3b1a7d88d543f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityResult &amp; llvm::sandboxir::LegalityResult::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityresult">LegalityResult</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<p>Reference <a href="#adb7e37e3a1dd3b7cb1b54c1299d3418f">LegalityResult</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a93d24c55e4f135833a83f6e099eaba6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::LegalityResult::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/legality-cpp">Legality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#ac45ada55c2eb4f56eac51088fed5d4e2">print</a>.</p>

</div>
</div>

### getSubclassID() {#abe732481be34af1d8d4057e05f3b53f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityResultID llvm::sandboxir::LegalityResult::getSubclassID ()</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<p>Reference <a href="#a656a668a4f4c6eff3825ed7e31d5c1eb">ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreuse/#a5e3e5f0d1fa304f9420d514406be7952">llvm::sandboxir::DiamondReuse::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreusemultiinput/#acde69f9f488f91d2ce43a6814fd445ca">llvm::sandboxir::DiamondReuseMultiInput::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/diamondreusewithshuffle/#a7413d02ed0a575e82f0c8b6b92fbd2c2">llvm::sandboxir::DiamondReuseWithShuffle::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pack/#a8f2f52aef12c9cc11085b6bf58e76d79">llvm::sandboxir::Pack::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/widen/#acff3eaa56dec058e3025a3df864f6cf5">llvm::sandboxir::Widen::classof</a>.</p>

</div>
</div>

### print() {#ac45ada55c2eb4f56eac51088fed5d4e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sandboxir::LegalityResult::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/sandboxir/tostr/#ac4110cbc5123ca0efdcc039dddb8d571">llvm::sandboxir::ToStr::getLegalityResultID</a> and <a href="#a656a668a4f4c6eff3825ed7e31d5c1eb">ID</a>.</p>


<p>Referenced by <a href="#a93d24c55e4f135833a83f6e099eaba6b">dump</a>, <a href="#a33b521a75a6c136e5dbe5533e8983624">operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityresultwithreason/#a8c3753b5d60c36291573bbead47fa840">llvm::sandboxir::LegalityResultWithReason::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ID {#a656a668a4f4c6eff3825ed7e31d5c1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityResultID llvm::sandboxir::LegalityResult::ID</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a>.</p>


<p>Referenced by <a href="#abe732481be34af1d8d4057e05f3b53f2">getSubclassID</a>, <a href="#adb7e37e3a1dd3b7cb1b54c1299d3418f">LegalityResult</a> and <a href="#ac45ada55c2eb4f56eac51088fed5d4e2">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/legality-h">Legality.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/legality-cpp">Legality.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
