---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/lineinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LineInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::LineInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">llvm/DebugInfo/CodeView/Line.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint32_t { <a href="#a3d703d10804f20cf5ddae9ed66b731e3">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : int { <a href="#a19f638605918061da7679c63d696b1d8">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint32_t { <a href="#a61ee4e4da32bcded51540eecc08224d2">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec12b0be337a12465a9a2f04b973dca8">LineInfo</a> (uint32_t StartLine, uint32_t EndLine, bool IsStatement)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f13d35290e356efbde1381354a61ade">LineInfo</a> (uint32_t LineData)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed22d7b681032dbb33937f3cf426f9d6">getStartLine</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92aacc3bcc7a6a54f146ea47f2b35663">getLineDelta</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6864c7e979343bcdc0263e855a9f9ae">getEndLine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ffd3186913a603c028155b29f9a4240">isStatement</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6df369507b6f0555330f9afafce8b2">getRawData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa397b6bf9ef7052f267cbd847d0fb768">isAlwaysStepInto</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b9a60a998e2c43be73000033ea972f">isNeverStepInto</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cfaa8b7d5fe0d5eb1129de56a4d7de2">LineData</a></td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a3d703d10804f20cf5ddae9ed66b731e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlwaysStepIntoLineNumber<a id="a3d703d10804f20cf5ddae9ed66b731e3a338318879b1a8dccb33cc0831fc8348c"></a></td>
<td class="doxyEnumItemDescription"> (= 0xfeefee)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NeverStepIntoLineNumber<a id="a3d703d10804f20cf5ddae9ed66b731e3a23b4e4c11466ccd3f17681f7f7f6b500"></a></td>
<td class="doxyEnumItemDescription"> (= 0xf00f00)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>

</div>
</div>

### anonymous enum  {#a19f638605918061da7679c63d696b1d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : int</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndLineDeltaShift<a id="a19f638605918061da7679c63d696b1d8af5dfb777e69076c86aa151e8f23a14ca"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>

</div>
</div>

### anonymous enum  {#a61ee4e4da32bcded51540eecc08224d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StartLineMask<a id="a61ee4e4da32bcded51540eecc08224d2a61aed42c1dcbb41881894d88887dfed4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00ffffff)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndLineDeltaMask<a id="a61ee4e4da32bcded51540eecc08224d2a9ab2a9d1bb235a9d832c179a301ca86e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x7f000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StatementFlag<a id="a61ee4e4da32bcded51540eecc08224d2a1181e4a1a533198a7dc59872a9c1e873"></a></td>
<td class="doxyEnumItemDescription"> (= 0x80000000u)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LineInfo() {#aec12b0be337a12465a9a2f04b973dca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineInfo::LineInfo (uint32_t StartLine, uint32_t EndLine, bool IsStatement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>, definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/line-cpp">Line.cpp</a>.</p>


<p>References <a href="#a61ee4e4da32bcded51540eecc08224d2a9ab2a9d1bb235a9d832c179a301ca86e">EndLineDeltaMask</a>, <a href="#a19f638605918061da7679c63d696b1d8af5dfb777e69076c86aa151e8f23a14ca">EndLineDeltaShift</a>, <a href="#aec12b0be337a12465a9a2f04b973dca8">LineInfo</a>, <a href="#a61ee4e4da32bcded51540eecc08224d2a61aed42c1dcbb41881894d88887dfed4">StartLineMask</a> and <a href="#a61ee4e4da32bcded51540eecc08224d2a1181e4a1a533198a7dc59872a9c1e873">StatementFlag</a>.</p>


<p>Referenced by <a href="#aec12b0be337a12465a9a2f04b973dca8">LineInfo</a>.</p>

</div>
</div>

### LineInfo() {#a2f13d35290e356efbde1381354a61ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::LineInfo::LineInfo (uint32_t LineData)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEndLine() {#ad6864c7e979343bcdc0263e855a9f9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::LineInfo::getEndLine ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>


<p>References <a href="#a92aacc3bcc7a6a54f146ea47f2b35663">getLineDelta</a> and <a href="#aed22d7b681032dbb33937f3cf426f9d6">getStartLine</a>.</p>

</div>
</div>

### getLineDelta() {#a92aacc3bcc7a6a54f146ea47f2b35663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::LineInfo::getLineDelta ()</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>


<p>References <a href="#a61ee4e4da32bcded51540eecc08224d2a9ab2a9d1bb235a9d832c179a301ca86e">EndLineDeltaMask</a> and <a href="#a19f638605918061da7679c63d696b1d8af5dfb777e69076c86aa151e8f23a14ca">EndLineDeltaShift</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamllinessubsection/#aec34b23d6a06eb6e4db5290bced7391a">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLLinesSubsection::fromCodeViewSubsection</a> and <a href="#ad6864c7e979343bcdc0263e855a9f9ae">getEndLine</a>.</p>

</div>
</div>

### getRawData() {#a2a6df369507b6f0555330f9afafce8b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::LineInfo::getRawData ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>

</div>
</div>

### getStartLine() {#aed22d7b681032dbb33937f3cf426f9d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::LineInfo::getStartLine ()</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>


<p>Reference <a href="#a61ee4e4da32bcded51540eecc08224d2a61aed42c1dcbb41881894d88887dfed4">StartLineMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamllinessubsection/#aec34b23d6a06eb6e4db5290bced7391a">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLLinesSubsection::fromCodeViewSubsection</a>, <a href="#ad6864c7e979343bcdc0263e855a9f9ae">getEndLine</a>, <a href="#aa397b6bf9ef7052f267cbd847d0fb768">isAlwaysStepInto</a> and <a href="#a03b9a60a998e2c43be73000033ea972f">isNeverStepInto</a>.</p>

</div>
</div>

### isAlwaysStepInto() {#aa397b6bf9ef7052f267cbd847d0fb768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::LineInfo::isAlwaysStepInto ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>


<p>References <a href="#a3d703d10804f20cf5ddae9ed66b731e3a338318879b1a8dccb33cc0831fc8348c">AlwaysStepIntoLineNumber</a> and <a href="#aed22d7b681032dbb33937f3cf426f9d6">getStartLine</a>.</p>

</div>
</div>

### isNeverStepInto() {#a03b9a60a998e2c43be73000033ea972f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::LineInfo::isNeverStepInto ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>


<p>References <a href="#aed22d7b681032dbb33937f3cf426f9d6">getStartLine</a> and <a href="#a3d703d10804f20cf5ddae9ed66b731e3a23b4e4c11466ccd3f17681f7f7f6b500">NeverStepIntoLineNumber</a>.</p>

</div>
</div>

### isStatement() {#a0ffd3186913a603c028155b29f9a4240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::LineInfo::isStatement ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>


<p>Reference <a href="#a61ee4e4da32bcded51540eecc08224d2a1181e4a1a533198a7dc59872a9c1e873">StatementFlag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamllinessubsection/#aec34b23d6a06eb6e4db5290bced7391a">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLLinesSubsection::fromCodeViewSubsection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LineData {#a6cfaa8b7d5fe0d5eb1129de56a4d7de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::LineInfo::LineData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/line-h">Line.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/line-cpp">Line.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
