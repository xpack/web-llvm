---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/riscvattrs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `RISCVAttrs` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::RISCVAttrs { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AttrType : unsigned { <a href="#ac0e6d65dbd5acd98356e49a2ea9c4e72">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RISCVAtomicAbiTag : unsigned { <a href="#a690f0d5292c1bf862c1ec8fb3126bacb">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a72f4c1d0c8ae78a0d81513e5a49b29c3">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8ba0ebd86185aea94f29ed853c4dd97f">TagNameMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade418e22f04bef132f10c2f977406785">getRISCVAttributeTags</a> ()</td>
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

## Enumerations

### anonymous enum  {#a72f4c1d0c8ae78a0d81513e5a49b29c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">NOT_ALLOWED<a id="a72f4c1d0c8ae78a0d81513e5a49b29c3a4c0e47df5625119eac000e6c9a611c6c"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALLOWED<a id="a72f4c1d0c8ae78a0d81513e5a49b29c3a68b684cc4c06d014569ef4a0befdf000"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributes-h">RISCVAttributes.h</a>.</p>

</div>
</div>

### AttrType {#ac0e6d65dbd5acd98356e49a2ea9c4e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RISCVAttrs::AttrType : unsigned</td>
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
<td class="doxyEnumItemName">STACK_ALIGN<a id="ac0e6d65dbd5acd98356e49a2ea9c4e72a35adc9b32c5d6aafb557089b94f65405"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARCH<a id="ac0e6d65dbd5acd98356e49a2ea9c4e72a0100b4efc71f09c9d6a16d6f32ff9daa"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNALIGNED_ACCESS<a id="ac0e6d65dbd5acd98356e49a2ea9c4e72ace72d01296c55f4885fbdefb87892871"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRIV_SPEC<a id="ac0e6d65dbd5acd98356e49a2ea9c4e72a8f3410f163016d35c79393fb044ed47b"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRIV_SPEC_MINOR<a id="ac0e6d65dbd5acd98356e49a2ea9c4e72a042be5b3857670a0e3e0dace53a79601"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRIV_SPEC_REVISION<a id="ac0e6d65dbd5acd98356e49a2ea9c4e72af86ac73473544636443d9eb261b81911"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_ABI<a id="ac0e6d65dbd5acd98356e49a2ea9c4e72a4794d2bd27775559be203df4503d3880"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributes-h">RISCVAttributes.h</a>.</p>

</div>
</div>

### RISCVAtomicAbiTag {#a690f0d5292c1bf862c1ec8fb3126bacb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::RISCVAttrs::RISCVAtomicAbiTag : unsigned</td>
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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNKNOWN<a id="a690f0d5292c1bf862c1ec8fb3126bacba696b031073e74bf2cb98e5ef201d4aa3"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">A6C<a id="a690f0d5292c1bf862c1ec8fb3126bacba9214e1300943d45ef0124bc7ba9770c9"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">A6S<a id="a690f0d5292c1bf862c1ec8fb3126bacba5e5e1c382c45b7ed86f9849450029595"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">A7<a id="a690f0d5292c1bf862c1ec8fb3126bacbabe523bdcc111d8113eb54f747d89d4d7"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributes-h">RISCVAttributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getRISCVAttributeTags() {#ade418e22f04bef132f10c2f977406785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagNameMap &amp; llvm::RISCVAttrs::getRISCVAttributeTags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributes-h">RISCVAttributes.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/support/riscvattributes-cpp">RISCVAttributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/riscvattributes-cpp/#a8381616c1a8aade708926141bbb39116">RISCVAttributeTags</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributes-h">RISCVAttributes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/riscvattributes-cpp">RISCVAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
