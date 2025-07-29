---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/adt/apfloat-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `APFloat.h` File

<p>This file declares a class to represent arbitrary precision floating point values and provide a variety of arithmetic operations on them. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">llvm/ADT/FloatingPointMode.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/float128-h">llvm/Support/float128.h</a>"
#include &lt;memory&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/detail">detail</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These are wrappers over isa* function that allow them to be used in generic algorithms such as <span class="doxyComputerOutput">llvm:all_of</span>, <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a></span>, etc. <a href="/web-llvm/docs/api/namespaces/llvm/detail/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase">APFloatBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A self-contained host- and target-independent arbitrary-precision floating-point software implementation. <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/detail/ieeefloat/significand">Significand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A binary fraction with an explicit integer bit. <a href="/web-llvm/docs/api/unions/llvm/detail/ieeefloat/significand/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/apfloat/storage">Storage</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a>(METHOD_CALL)&nbsp;&nbsp;&nbsp;...</td>
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

<p>This file declares a class to represent arbitrary precision floating point values and provide a variety of arithmetic operations on them.</p>

<div class="doxySectionDef">

## Macro Definitions

### APFLOAT\_DISPATCH\_ON\_SEMANTICS {#a91a6dbe6838c079cb3887485f4b1a965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define APFLOAT_DISPATCH_ON_SEMANTICS(METHOD_CALL)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (usesLayout&lt;IEEEFloat&gt;(getSemantics()))                                 \
      return U.IEEE.METHOD_CALL;                                               \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (usesLayout&lt;DoubleAPFloat&gt;(getSemantics()))                             \
      return U.Double.METHOD_CALL;                                             \
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>("Unexpected semantics");                                  \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (false)
</div>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ae7fe7691e456e49addd866aa23896387">llvm::APFloat::changeSign</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a7a046fe3d1230e4804494ce18bae1175">llvm::APFloat::convertFromAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a6cc309055edb782bba7bcb11b415dd17">llvm::APFloat::convertFromSignExtendedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ac83df2fb4fcefd0a95deb09db83a0635">llvm::APFloat::convertFromString</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af8026384a9b6bfd57046298ab64b0ea1">llvm::APFloat::convertFromZeroExtendedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a80fcf8584733a9b06176373b10e49b17">llvm::APFloat::convertToHexString</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aae1f09de4bf1aab27149a7d328715e30">llvm::APFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a133fbd343970e5f7e689c3b94185a605">llvm::APFloat::getExactInverse</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a44d70cf308906fa36b66a9796dc0b6e3">llvm::APFloat::getExactLog2</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a268f8980dd0cba08690326624d4c7235">llvm::APFloat::getExactLog2Abs</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a43c6c871e61d6071a20a680aa2a08009">llvm::APFloat::isDenormal</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ace4517dbbab7dbdefa0d31e29db55969">llvm::APFloat::isInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9e937642977dd028fb0b5293f30ee47d">llvm::APFloat::isLargest</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aaa34fa2837fa3f7355fe90cbca1555e0">llvm::APFloat::isSmallest</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af8943302f831d2fc16d84eaf1f2740ed">llvm::APFloat::isSmallestNormalized</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aba402b558169083d42683af51ae36016">llvm::APFloat::needsCleanup</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab0fdc79bb75e8fe845f98e2199f9d451">llvm::APFloat::next</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ae4eca54fe8b71670e3bd3a2b18469d73">llvm::APFloat::roundToIntegral</a> and <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a416dc650964ad640df99464a32aa49da">llvm::APFloat::toString</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
