---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/detail/anonymous-apfloat-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{APFloat.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::detail::anonymous{APFloat.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb5a65e2899475a4a85a2b2649289abf">append</a> (SmallVectorImpl&lt; char &gt; &amp;Buffer, StringRef Str)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a015653deceadd540a1e4fc871a1a21ea">AdjustToPrecision</a> (APInt &amp;significand, int &amp;exp, unsigned FormatPrecision)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes data from the given significand until it is no more precise than is required for the desired precision. <a href="#a015653deceadd540a1e4fc871a1a21ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b4f3c32f38913159a0ab75cb4bf133">AdjustToPrecision</a> (SmallVectorImpl&lt; char &gt; &amp;buffer, int &amp;exp, unsigned FormatPrecision)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67a4cef5addbdc43c571874df4ea020d">toStringImpl</a> (SmallVectorImpl&lt; char &gt; &amp;Str, const bool isNeg, int exp, APInt significand, unsigned FormatPrecision, unsigned FormatMaxPadding, bool TruncateZero)</td>
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

## Functions

### AdjustToPrecision() {#a015653deceadd540a1e4fc871a1a21ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::anonymous{APFloat.cpp}::AdjustToPrecision (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; significand, int &amp; exp, unsigned FormatPrecision)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes data from the given significand until it is no more precise than is required for the desired precision.</p>

<p>Definition at line 4209 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#a015653deceadd540a1e4fc871a1a21ea">AdjustToPrecision</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3015474e70e59c0a3ed4f9f0e8644b75">llvm::APInt::getActiveBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a05d674becc60ba4ef8cd4dd4d38ac27a">llvm::APInt::udiv</a>.</p>


<p>Referenced by <a href="#a015653deceadd540a1e4fc871a1a21ea">AdjustToPrecision</a>, <a href="#af9b4f3c32f38913159a0ab75cb4bf133">AdjustToPrecision</a> and <a href="#a67a4cef5addbdc43c571874df4ea020d">toStringImpl</a>.</p>

</div>
</div>

### AdjustToPrecision() {#af9b4f3c32f38913159a0ab75cb4bf133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::anonymous{APFloat.cpp}::AdjustToPrecision (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; buffer, int &amp; exp, unsigned FormatPrecision)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4240 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#a015653deceadd540a1e4fc871a1a21ea">AdjustToPrecision</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### append() {#afb5a65e2899475a4a85a2b2649289abf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::anonymous{APFloat.cpp}::append (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Buffer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4203 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#afb5a65e2899475a4a85a2b2649289abf">append</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>.</p>


<p>Referenced by <a href="#afb5a65e2899475a4a85a2b2649289abf">append</a>.</p>

</div>
</div>

### toStringImpl() {#a67a4cef5addbdc43c571874df4ea020d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::anonymous{APFloat.cpp}::toStringImpl (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool isNeg, int exp, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> significand, unsigned FormatPrecision, unsigned FormatMaxPadding, bool TruncateZero)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4285 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#a015653deceadd540a1e4fc871a1a21ea">AdjustToPrecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp/#a2762113571c7956c9818c452b2d256ae">isNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af338e23a90c301183968435e80cd6a27">llvm::APInt::lshrInPlace</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a67a4cef5addbdc43c571874df4ea020d">toStringImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a0f0a665210e453bb16b4bf1861dbdd58">llvm::APInt::udivrem</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="#a67a4cef5addbdc43c571874df4ea020d">toStringImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
