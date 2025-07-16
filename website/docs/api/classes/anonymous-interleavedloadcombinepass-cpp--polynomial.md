---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Polynomial` Class Reference

<p>First Order <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> on an n-Bit Integer <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{InterleavedLoadCombinePass.cpp}::Polynomial { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BOps { <a href="#aea7c49ab31138f7e07d54d8e954949d2">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Operations on B. <a href="#aea7c49ab31138f7e07d54d8e954949d2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9125cd76962bcc439d4376d8610b74c2">Polynomial</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc37fd9780cd515cf37c4e973418d3f">Polynomial</a> (const APInt &amp;A, unsigned ErrorMSBs=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3bc7492e306ba4d6e41b50f494e7cf1">Polynomial</a> (unsigned BitWidth, uint64_t A, unsigned ErrorMSBs=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fff86391ba2d67f86f73797b4fde21c">Polynomial</a> ()=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b968cc6e2d9e8f74b4675fc69195e38">operator-</a> (const Polynomial &amp;o) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtract two polynomials, return an undefined polynomial if subtraction is not possible. <a href="#a3b968cc6e2d9e8f74b4675fc69195e38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a172c35f92b899d0d67b41e83e1b11fc1">operator-</a> (uint64_t C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtract a constant from a polynomial,. <a href="#a172c35f92b899d0d67b41e83e1b11fc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a394b6565f1081442292450c4e2468b93">operator+</a> (uint64_t C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a constant to a polynomial,. <a href="#a394b6565f1081442292450c4e2468b93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84aceefc69fca55a44b00abbe6c55a39">incErrorMSBs</a> (unsigned amt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Increment and clamp the number of undefined bits. <a href="#a84aceefc69fca55a44b00abbe6c55a39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a655616f261657236062b1639e62c2bb6">decErrorMSBs</a> (unsigned amt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decrement and clamp the number of undefined bits. <a href="#a655616f261657236062b1639e62c2bb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13943fc34f01ec5aa7279d7171077696">add</a> (const APInt &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply an add on the polynomial. <a href="#a13943fc34f01ec5aa7279d7171077696">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa933051dac38f62739216d984595e05">mul</a> (const APInt &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply a multiplication onto the polynomial. <a href="#afa933051dac38f62739216d984595e05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a403ea830c03b537cc0ac0137f162d6ed">lshr</a> (const APInt &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply a logical shift right on the polynomial. <a href="#a403ea830c03b537cc0ac0137f162d6ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1655d28daf2213ac97e059dbca87415b">sextOrTrunc</a> (unsigned n)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply a sign-extend or truncate operation on the polynomial. <a href="#a1655d28daf2213ac97e059dbca87415b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab94db2970b1037205dd210cee9d44df7">isFirstOrder</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if there is a coefficient B. <a href="#ab94db2970b1037205dd210cee9d44df7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18a73a6ac377217c6acbbe16c4259ec9">isCompatibleTo</a> (const Polynomial &amp;o) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test coefficient B of two Polynomials are equal. <a href="#a18a73a6ac377217c6acbbe16c4259ec9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab36480a7c88876050105835be050f98">isProvenEqualTo</a> (const Polynomial &amp;o)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it can be proven that two Polynomials are equal. <a href="#aab36480a7c88876050105835be050f98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcdc662937d2cc9cca72544e5e343f9b">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the polynomial into a stream. <a href="#adcdc662937d2cc9cca72544e5e343f9b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf8714d409c6c1ff96350e9a953c6e89">deleteB</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfed2527e120c5d0623a1340c664a0cc">pushBOperation</a> (const BOps Op, const APInt &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc0b1eca0fc279ba07ad602287b6c99">ErrorMSBs</a> = (unsigned)-1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Bits e. <a href="#aefc0b1eca0fc279ba07ad602287b6c99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8762a3a588a08b3d646c50320d6e6b69">V</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a8762a3a588a08b3d646c50320d6e6b69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; BOps, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2c3ff489bc5377454b11a4b80b5c28f">B</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Coefficient B. <a href="#aa2c3ff489bc5377454b11a4b80b5c28f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa7e537ae2cd56165d11d2e630566a35">A</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Coefficient A. <a href="#afa7e537ae2cd56165d11d2e630566a35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>First Order <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> on an n-Bit Integer <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>


<p>Polynomial(Value) = <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B + A + E*2^(n-e)</p>


<p>A and B are the coefficients. E*2^(n-e) is an error within 'e' most significant bits. It is introduced if an exact computation cannot be proven (e.q. division by 2).</p>


<p>As part of this optimization multiple loads will be combined. It necessary to prove that loads are within some relative offset to each other. This class is used to prove relative offsets of values loaded from memory.</p>


<p>Representing an integer in this form is sound since addition in two's complement is associative (trivial) and multiplication distributes over the addition (see Proof(1) in <a href="#afa933051dac38f62739216d984595e05">Polynomial::mul</a>). Further, both operations commute.</p>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### BOps {#aea7c49ab31138f7e07d54d8e954949d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::BOps </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Operations on B.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LShr<a id="aea7c49ab31138f7e07d54d8e954949d2ac123d2f989448034d794543e9353f835"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mul<a id="aea7c49ab31138f7e07d54d8e954949d2a2a95388474eb554047abaac3f8e0b591"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SExt<a id="aea7c49ab31138f7e07d54d8e954949d2a3f7f83255f39e86841057223f11fee2f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Trunc<a id="aea7c49ab31138f7e07d54d8e954949d2a831ff2f46006b65201876bbe83349014"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Polynomial() {#a9125cd76962bcc439d4376d8610b74c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::Polynomial (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a13943fc34f01ec5aa7279d7171077696">add</a>, <a href="#a18a73a6ac377217c6acbbe16c4259ec9">isCompatibleTo</a>, <a href="#aab36480a7c88876050105835be050f98">isProvenEqualTo</a>, <a href="#a403ea830c03b537cc0ac0137f162d6ed">lshr</a>, <a href="#afa933051dac38f62739216d984595e05">mul</a>, <a href="#a394b6565f1081442292450c4e2468b93">operator+</a>, <a href="#a3b968cc6e2d9e8f74b4675fc69195e38">operator-</a>, <a href="#a172c35f92b899d0d67b41e83e1b11fc1">operator-</a> and <a href="#a1655d28daf2213ac97e059dbca87415b">sextOrTrunc</a>.</p>

</div>
</div>

### Polynomial() {#adcc37fd9780cd515cf37c4e973418d3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::Polynomial (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A, unsigned ErrorMSBs=0)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

### Polynomial() {#ad3bc7492e306ba4d6e41b50f494e7cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::Polynomial (unsigned BitWidth, uint64_t A, unsigned ErrorMSBs=0)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>.</p>

</div>
</div>

### Polynomial() {#a9fff86391ba2d67f86f73797b4fde21c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::Polynomial ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-() {#a3b968cc6e2d9e8f74b4675fc69195e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Polynomial anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::operator- (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> &amp; o)</td>
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

<p>Subtract two polynomials, return an undefined polynomial if subtraction is not possible.</p>

<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="#a18a73a6ac377217c6acbbe16c4259ec9">isCompatibleTo</a> and <a href="#a9125cd76962bcc439d4376d8610b74c2">Polynomial</a>.</p>

</div>
</div>

### operator-() {#a172c35f92b899d0d67b41e83e1b11fc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Polynomial anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::operator- (uint64_t C)</td>
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

<p>Subtract a constant from a polynomial,.</p>

<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a9125cd76962bcc439d4376d8610b74c2">Polynomial</a>.</p>

</div>
</div>

### operator+() {#a394b6565f1081442292450c4e2468b93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Polynomial anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::operator+ (uint64_t C)</td>
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

<p>Add a constant to a polynomial,.</p>

<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a9125cd76962bcc439d4376d8610b74c2">Polynomial</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a13943fc34f01ec5aa7279d7171077696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Polynomial &amp; anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; C)</td>
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

<p>Apply an add on the polynomial.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a9125cd76962bcc439d4376d8610b74c2">Polynomial</a>.</p>

</div>
</div>

### decErrorMSBs() {#a655616f261657236062b1639e62c2bb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::decErrorMSBs (unsigned amt)</td>
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

<p>Decrement and clamp the number of undefined bits.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="#afa933051dac38f62739216d984595e05">mul</a> and <a href="#a1655d28daf2213ac97e059dbca87415b">sextOrTrunc</a>.</p>

</div>
</div>

### incErrorMSBs() {#a84aceefc69fca55a44b00abbe6c55a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::incErrorMSBs (unsigned amt)</td>
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

<p>Increment and clamp the number of undefined bits.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="#a403ea830c03b537cc0ac0137f162d6ed">lshr</a> and <a href="#a1655d28daf2213ac97e059dbca87415b">sextOrTrunc</a>.</p>

</div>
</div>

### isCompatibleTo() {#a18a73a6ac377217c6acbbe16c4259ec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::isCompatibleTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> &amp; o)</td>
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

<p>Test coefficient B of two Polynomials are equal.</p>

<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="#ab94db2970b1037205dd210cee9d44df7">isFirstOrder</a> and <a href="#a9125cd76962bcc439d4376d8610b74c2">Polynomial</a>.</p>


<p>Referenced by <a href="#a3b968cc6e2d9e8f74b4675fc69195e38">operator-</a>.</p>

</div>
</div>

### isFirstOrder() {#ab94db2970b1037205dd210cee9d44df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::isFirstOrder ()</td>
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

<p>Test if there is a coefficient B.</p>

<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="#a18a73a6ac377217c6acbbe16c4259ec9">isCompatibleTo</a> and <a href="#aab36480a7c88876050105835be050f98">isProvenEqualTo</a>.</p>

</div>
</div>

### isProvenEqualTo() {#aab36480a7c88876050105835be050f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::isProvenEqualTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> &amp; o)</td>
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

<p>Returns true if it can be proven that two Polynomials are equal.</p>

<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="#ab94db2970b1037205dd210cee9d44df7">isFirstOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a> and <a href="#a9125cd76962bcc439d4376d8610b74c2">Polynomial</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a204b8dfd1121295f9a57bb5aa0723016">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::isInterleaved</a>.</p>

</div>
</div>

### lshr() {#a403ea830c03b537cc0ac0137f162d6ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Polynomial &amp; anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::lshr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; C)</td>
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

<p>Apply a logical shift right on the polynomial.</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a84aceefc69fca55a44b00abbe6c55a39">incErrorMSBs</a>, <a href="#afa933051dac38f62739216d984595e05">mul</a> and <a href="#a9125cd76962bcc439d4376d8610b74c2">Polynomial</a>.</p>

</div>
</div>

### mul() {#afa933051dac38f62739216d984595e05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Polynomial &amp; anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::mul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; C)</td>
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

<p>Apply a multiplication onto the polynomial.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a655616f261657236062b1639e62c2bb6">decErrorMSBs</a> and <a href="#a9125cd76962bcc439d4376d8610b74c2">Polynomial</a>.</p>


<p>Referenced by <a href="#a403ea830c03b537cc0ac0137f162d6ed">lshr</a>.</p>

</div>
</div>

### print() {#adcdc662937d2cc9cca72544e5e343f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Print the polynomial into a stream.</p>

<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-interleavedloadcombinepass-cpp-/#a3a41fce1c82e39089ed9eca3907d6b93">anonymous{InterleavedLoadCombinePass.cpp}::operator&lt;&lt;</a>.</p>

</div>
</div>

### sextOrTrunc() {#a1655d28daf2213ac97e059dbca87415b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Polynomial &amp; anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::sextOrTrunc (unsigned n)</td>
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

<p>Apply a sign-extend or truncate operation on the polynomial.</p>

<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="#a655616f261657236062b1639e62c2bb6">decErrorMSBs</a>, <a href="#a84aceefc69fca55a44b00abbe6c55a39">incErrorMSBs</a> and <a href="#a9125cd76962bcc439d4376d8610b74c2">Polynomial</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### deleteB() {#acf8714d409c6c1ff96350e9a953c6e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::deleteB ()</td>
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



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

### pushBOperation() {#adfed2527e120c5d0623a1340c664a0cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::pushBOperation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BOps Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; C)</td>
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



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### A {#afa7e537ae2cd56165d11d2e630566a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::A</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Coefficient A.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

### B {#aa2c3ff489bc5377454b11a4b80b5c28f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;BOps, APInt&gt;, 4&gt; anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::B</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Coefficient B.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

### ErrorMSBs {#aefc0b1eca0fc279ba07ad602287b6c99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::ErrorMSBs = (unsigned)-1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Bits e.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

### V {#a8762a3a588a08b3d646c50320d6e6b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::V = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
