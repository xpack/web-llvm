---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/arm-mb
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `ARM_MB` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::ARM_MB { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MemBOpt { <a href="#ad70272e2a9ec2a7e3a497458e1edbc85">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1f4ca826b62d64b97d60c98931634a6">MemBOptToString</a> (unsigned val, bool HasV8)</td>
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

### MemBOpt {#ad70272e2a9ec2a7e3a497458e1edbc85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARM_MB::MemBOpt </td>
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
<td class="doxyEnumItemName">RESERVED_0<a id="ad70272e2a9ec2a7e3a497458e1edbc85ad02a38b75772b4f8855f07ae85c0b3ba"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OSHLD<a id="ad70272e2a9ec2a7e3a497458e1edbc85a67d0b08125dd9a771ca3ed5d3249b3a4"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OSHST<a id="ad70272e2a9ec2a7e3a497458e1edbc85aca1c9ec29474d99d55561584f203d994"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OSH<a id="ad70272e2a9ec2a7e3a497458e1edbc85a431feccac195408b87c77c77b41787ae"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RESERVED_4<a id="ad70272e2a9ec2a7e3a497458e1edbc85a32c268128149881f8dd8aefbe428b7e7"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NSHLD<a id="ad70272e2a9ec2a7e3a497458e1edbc85a4dfbf638d4c209243802d7dac1a2f98d"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NSHST<a id="ad70272e2a9ec2a7e3a497458e1edbc85a924f74a80dce873e73754f380eed85cb"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NSH<a id="ad70272e2a9ec2a7e3a497458e1edbc85a1f2e4ed59c2e87fda3a937b2f0c895a2"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RESERVED_8<a id="ad70272e2a9ec2a7e3a497458e1edbc85a4f1a7b15355f9e8a24a01b995c4648af"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ISHLD<a id="ad70272e2a9ec2a7e3a497458e1edbc85a6a71485f8bf9c7b3097e7553120743b6"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ISHST<a id="ad70272e2a9ec2a7e3a497458e1edbc85a8a7f29f5965f4969d7a34c42ad38b6b1"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ISH<a id="ad70272e2a9ec2a7e3a497458e1edbc85a5d590944cad68ea77c8645fef111801e"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RESERVED_12<a id="ad70272e2a9ec2a7e3a497458e1edbc85abd4288f2e919717542a4cb76520bb7fb"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LD<a id="ad70272e2a9ec2a7e3a497458e1edbc85a7289f7156c17c31399fe5226bf556781"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST<a id="ad70272e2a9ec2a7e3a497458e1edbc85aed0b9bef861c96eee19e89db753db7b2"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SY<a id="ad70272e2a9ec2a7e3a497458e1edbc85a0290018b446a2b2a74d37cebe1bec0cb"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armbaseinfo-h">ARMBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### MemBOptToString() {#ac1f4ca826b62d64b97d60c98931634a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::ARM_MB::MemBOptToString (unsigned val, bool HasV8)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armbaseinfo-h">ARMBaseInfo.h</a>.</p>


<p>References <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a5d590944cad68ea77c8645fef111801e">ISH</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a6a71485f8bf9c7b3097e7553120743b6">ISHLD</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a8a7f29f5965f4969d7a34c42ad38b6b1">ISHST</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a7289f7156c17c31399fe5226bf556781">LD</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a1f2e4ed59c2e87fda3a937b2f0c895a2">NSH</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a4dfbf638d4c209243802d7dac1a2f98d">NSHLD</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a924f74a80dce873e73754f380eed85cb">NSHST</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a431feccac195408b87c77c77b41787ae">OSH</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a67d0b08125dd9a771ca3ed5d3249b3a4">OSHLD</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85aca1c9ec29474d99d55561584f203d994">OSHST</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85ad02a38b75772b4f8855f07ae85c0b3ba">RESERVED_0</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85abd4288f2e919717542a4cb76520bb7fb">RESERVED_12</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a32c268128149881f8dd8aefbe428b7e7">RESERVED_4</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a4f1a7b15355f9e8a24a01b995c4648af">RESERVED_8</a>, <a href="#ad70272e2a9ec2a7e3a497458e1edbc85aed0b9bef861c96eee19e89db753db7b2">ST</a> and <a href="#ad70272e2a9ec2a7e3a497458e1edbc85a0290018b446a2b2a74d37cebe1bec0cb">SY</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a89240de7c30d000b1e6698e0c259d7ef">llvm::ARMInstPrinter::printMemBOption</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armbaseinfo-h">ARMBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
