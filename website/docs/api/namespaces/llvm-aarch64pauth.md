---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/aarch64pauth
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `AArch64PAuth` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::AArch64PAuth { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AuthCheckMethod { <a href="#abf78b4a589091577668be8331dbf3e10">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Variants of check performed on an authenticated pointer. <a href="#abf78b4a589091577668be8331dbf3e10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f9d58f53aa5fefd75ce86659f52f71">getCheckerSizeInBytes</a> (AuthCheckMethod Method)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of bytes added by checkAuthenticatedRegister. <a href="#a89f9d58f53aa5fefd75ce86659f52f71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### AuthCheckMethod {#abf78b4a589091577668be8331dbf3e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::AArch64PAuth::AuthCheckMethod </td>
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

<p>Variants of check performed on an authenticated pointer.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="abf78b4a589091577668be8331dbf3e10a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription">Do not check the value at all</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DummyLoad<a id="abf78b4a589091577668be8331dbf3e10a24204a7fa8ab4d609a76a48ac4673b22"></a></td>
<td class="doxyEnumItemDescription">Perform a load to a temporary register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HighBitsNoTBI<a id="abf78b4a589091577668be8331dbf3e10a47343d56dc562d3a8366d3854eb64161"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> by comparing bits 62 and 61 of the authenticated address</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XPACHint<a id="abf78b4a589091577668be8331dbf3e10a1fb8b484947fc2d97a18d9b90e0c08fb"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> by comparing the authenticated value with an XPAC-ed one without using PAuth instructions not encoded as HINT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XPAC<a id="abf78b4a589091577668be8331dbf3e10ae34527c9d45ac8d5e68634911bfcd36e"></a></td>
<td class="doxyEnumItemDescription">Similar to XPACHint but using Armv8.3-only XPAC instruction, thus not restricted to LR:</td>
</tr>

</table>
</dd>
</dl>


<p>In cases such as authenticating the LR value when performing a tail call or when re-signing a signed pointer with a different signing schema, a failed authentication may not generate an exception on its own and may create an authentication or signing oracle if not checked explicitly.</p>


<p>A number of check methods modify control flow in a similar way by rewriting the code</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">&lt;authenticate LR&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">&lt;more <a href="/web-llvm/docs/api/namespaces/llvm/#a7e3e687ddfdcbacd404bcf17b917dd88">instructions</a>&gt;</span></span></div>

</div>


<p>as follows:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  &lt;authenticate LR&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  &lt;method-specific checker&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">on_fail:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  brk &lt;code&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">on_success:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  &lt;more <a href="/web-llvm/docs/api/namespaces/llvm/#a7e3e687ddfdcbacd404bcf17b917dd88">instructions</a>&gt;</span></span></div>

</div>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-h">AArch64PointerAuth.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getCheckerSizeInBytes() {#a89f9d58f53aa5fefd75ce86659f52f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64PAuth::getCheckerSizeInBytes (<a href="#abf78b4a589091577668be8331dbf3e10">AuthCheckMethod</a> Method)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of bytes added by checkAuthenticatedRegister.</p>

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-h">AArch64PointerAuth.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp">AArch64PointerAuth.cpp</a>.</p>


<p>References <a href="#abf78b4a589091577668be8331dbf3e10a24204a7fa8ab4d609a76a48ac4673b22">DummyLoad</a>, <a href="#abf78b4a589091577668be8331dbf3e10a47343d56dc562d3a8366d3854eb64161">HighBitsNoTBI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#abf78b4a589091577668be8331dbf3e10a6adf97f83acf6453d4a6a4b1070f3754">None</a>, <a href="#abf78b4a589091577668be8331dbf3e10ae34527c9d45ac8d5e68634911bfcd36e">XPAC</a> and <a href="#abf78b4a589091577668be8331dbf3e10a1fb8b484947fc2d97a18d9b90e0c08fb">XPACHint</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a1bf38b3bbe867377cde6e530a0256b29">llvm::AArch64InstrInfo::getInstSizeInBytes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp">AArch64PointerAuth.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-h">AArch64PointerAuth.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
