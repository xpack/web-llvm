---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcobjectfileinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCObjectFileInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCObjectFileInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">llvm/MC/MCObjectFileInfo.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvmcobjectfileinfo">RISCVMCObjectFileInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile">TargetLoweringObjectFile</a></td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf20a9c3eeee245072bf1913e848fe13">~MCObjectFileInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a> (MCContext &amp;MCCtx, bool PIC, bool LargeCodeModel=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcda39b4059eca86c10397b7a938a729">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bbe770dc3f895b2d7ceffa945da0866">getSupportsWeakOmittedEHFrame</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aea2b540e0c76cea347723fdcbf9562">getSupportsCompactUnwindWithoutEHFrame</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace2637cdddf7452b83365442e31a5d1c">getOmitDwarfIfHaveCompactUnwind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b753f5b5ed5d2d28462e83e7c5e923b">getFDEEncoding</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eb24afad571f2444e56298ef8c2693f">getCompactUnwindDwarfEHFrameOnly</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7a8978f9a23fedbc9055993cffe31e7">getTextSectionAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1e49c4350a67d9c442c39ab1dc211eb">getTextSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd9ae84447d7be72e18fd897b3f036d2">getDataSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de12269943e6388af512d8b96cbd9e8">getBSSSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab14fbbabe5077f89e7d887b3d3d90d0a">getReadOnlySection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94b2a8fa73fa90decda080df0772a13d">getLSDASection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc22c43614460f4c34ed60b32c8b2ef3">getImportCallSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8632a15d42e54c1367a81afc1b6602">getCompactUnwindSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac10c6a9d85782db274d19ef8f828d9fc">getDwarfAbbrevSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d739b35c6534d476fc5bf7d2ee57cb">getDwarfInfoSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38bf1682d25dc5998f1de9fdf81fa44f">getDwarfInfoSection</a> (uint64_t Hash) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d3abaa97d9734f17bdd52cfdf00fb7">getDwarfLineSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2906ef9fe9b6b1bef3e104b1519cd0">getDwarfLineStrSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8357c20a6fa8dd32020a98ed65971587">getDwarfFrameSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49eb3fca43b2ceca3ff8c706fae7ddab">getDwarfPubNamesSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97622da3f5114dfa0bb2f2285bf37cea">getDwarfPubTypesSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29cddb4a82114802b9020d33d7e4dbd8">getDwarfGnuPubNamesSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eaa64fd2b7b36baec3fb81e574b6b8a">getDwarfGnuPubTypesSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba4c71757b3cefaeefeb6d440d0ee91">getDwarfDebugInlineSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5915c91abcb7f7eb43cae094ec8b4ec7">getDwarfStrSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7548b994352e41c0a628936d3f75c61">getDwarfLocSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae17df2cce5c5b2cb1688d22f2d90820c">getDwarfARangesSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31df4edd580fc4f6e43318cd9c5ed5bc">getDwarfRangesSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cddd5b91a2f88c1c204cafeca322517">getDwarfRnglistsSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0da64dcd145f4d0e82f845499c055391">getDwarfLoclistsSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae04d121e734cd5ad456233e5d6ebbb3c">getDwarfMacinfoSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba5c0a8e62bf4ce62c2e815808ae159">getDwarfMacroSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7031b56e11bd03c7a1f7ab2e68d5d095">getDwarfDebugNamesSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a98f2924de06f55315c207f3c0eac1">getDwarfAccelNamesSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1a65d3a4229133502a782ab58741e60">getDwarfAccelObjCSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38d14819d39b592f82540549231ed94e">getDwarfAccelNamespaceSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f1b3ba79882a148045283d71753897a">getDwarfAccelTypesSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9643e39995d567cfd19465abcfabaf">getDwarfInfoDWOSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e706526e3ba2c8ee93dae01f573f602">getDwarfTypesSection</a> (uint64_t Hash) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47aba8387dcc1520ee5846c047be762d">getDwarfTypesDWOSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7b38278009d729724c809dcbc9d5b4f">getDwarfAbbrevDWOSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa89ba1b4a04c6aab9e36521b0af3212e">getDwarfStrDWOSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b7d7a8e94a349e8343c52c9759bceb4">getDwarfLineDWOSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c42bab7cf6d48b020adbec53263a2c">getDwarfLocDWOSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2be455ebf2215c76244c7d1cc4697492">getDwarfStrOffDWOSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d677a1ab07bb4796933369f69396459">getDwarfStrOffSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dd91b8042158479671aa8f357fd5f62">getDwarfAddrSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7bd3800ca2a48cd600e03e97c98f059">getDwarfRnglistsDWOSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6713cdb4592c3c97a4a90e3b19a241b5">getDwarfLoclistsDWOSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6f1092f5467897d43cf376fd5c1886">getDwarfMacroDWOSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7512a0f2f3c4476649d5eab18f4888ff">getDwarfMacinfoDWOSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc1a8b3a5ab5c4c460feb4a00dd2a71c">getDwarfCUIndexSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f7b6409e225107d1b3e430471b80c50">getDwarfTUIndexSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac28a6e4a483c4c56f254884ed9024648">getDwarfSwiftASTSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77dbfa104b3138b7684fe0334348011">getCOFFDebugSymbolsSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5f6572e439f23e83446c8b36337f6a1">getCOFFDebugTypesSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af483c4b79ae094d99c1e24a643f61111">getCOFFGlobalTypeHashesSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89686f5c463cd1bb0c9fd25e9c3f518d">getTLSExtraDataSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2600e80f9bd6077b91ca4458d51fea7">getTLSDataSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ba33cc58122be1793d339e452a3b20">getTLSBSSSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaded1e857e3e6aa44d76a3a967624818">getStackMapSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39753c797dc0dce0e2f7f367e4203556">getFaultMapSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706b30b9956c1eb3a09f663d2a09d87d">getRemarksSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ff3ae888d49df6baad0fb54f3cb8dc">getStackSizesSection</a> (const MCSection &amp;TextSec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f09a8aebb37ccdb0041ea53a9b6ba88">getBBAddrMapSection</a> (const MCSection &amp;TextSec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a919076c2cfa73586ca99b52ff984ae40">getKCFITrapSection</a> (const MCSection &amp;TextSec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cec802e187b8b84478ffe1fa783a2dd">getPseudoProbeSection</a> (const MCSection &amp;TextSec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a427ea8030e264e1e94ec134806be72a9">getPseudoProbeDescSection</a> (StringRef FuncName) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2829cb48c8fe186a1318a5df7b4e11da">getLLVMStatsSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6ce753721421b09ebdefeec3e7e993e">getPCSection</a> (StringRef Name, const MCSection *TextSec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0336b43f021525b0a865076f315df0b4">getDataRelROSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13d95da0ffa6baee110e7fa2f4c97bed">getMergeableConst4Section</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7af67f26eb452f7afe236b200622839">getMergeableConst8Section</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a6ce7b3647fc22dc5e8e79dc170aea9">getMergeableConst16Section</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f41a87ecc86ac0049cb84c369ce1188">getMergeableConst32Section</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3032b320a8e9a7d93c1cfa3576c26f5d">getTLSTLVSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d583d9efd88ed3d1f20799fd27b5793">getTLSThreadInitSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0ded12f6aff48c98bd0bc9d98d8b77e">getCStringSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8be1c3795a2c06f2d95df2b2f90fb96">getUStringSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea2d24275e7c37967a519487f5abc4b">getTextCoalSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8a5c332180d7dcf2c7865d7b611a1d">getConstTextCoalSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67cfba876d87d0a698a534ed2c337452">getConstDataSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67fcb9565b45811881bae17102eedcef">getDataCoalSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7248a5a87e6e340ad0b0f3c77eb17b69">getConstDataCoalSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1bd56da7a380fcec3b80dd3994f50f8">getDataCommonSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae91f8af9e6e309f03754093a2892c3ca">getDataBSSSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba452decdc0d6e2ec7c55587cf0e8387">getFourByteConstantSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8986417f698b06ed587b13206ebf6cdf">getEightByteConstantSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e8241ff6fbcd226417943ac30c1a03">getSixteenByteConstantSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bce74eda9ad4f8992b959ad6a7e3386">getLazySymbolPointerSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3992a89b8f47181ead24dd08b5e73ac">getNonLazySymbolPointerSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab444df00c5dc8d4675ffbac693979af6">getThreadLocalPointerSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1ff4f0cc25dc5cc546db7ea694e9dd">getAddrSigSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78c3233931fda64aa2d37bce0ccc0f19">getDrectveSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c221af9ebc8c35c9c0dc601f50c39a">getPDataSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad68702dad1f331b6bd67bf04c2da2d">getXDataSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c945f4a60fb9dd0893b1632944dafc3">getSXDataSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fdc31dfe6ba58f020c623009ea8581e">getGEHContSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b8430be4ec071180c26ab9e34c495a">getGFIDsSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada5d9fd0747603e74881f463d8d87ae5">getGIATsSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace74c8038b708823632d7f3c22e28154">getGLJMPSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f3e57a0a153a47b66dbea2a68962d8d">getPPA1Section</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd4544fcbf850d4876416965a6518725">getPPA2Section</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a913e2c8b44957daa6dfe02d906e8bb09">getPPA2ListSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33186d2160644f7da1730786dc47d5d4">getADASection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2deae42e85e5f97a4f86b2b63062aef">getIDRLSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf115ecc361072e6005a4ee102bad260">getTOCBaseSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31d963341d03839c532b62ef3fd568c2">getEHFrameSection</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97edf1bb7914cfc9e329b9d2d103e2fe">isPositionIndependent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78f3e7ac9f8cd9666d131a26239f89a8">getSwift5ReflectionSection</a> (llvm::binaryformat::Swift5ReflectionSectionKind ReflSectionKind)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f305b12fede7c66c9aae93e295025c">initMachOMCObjectFileInfo</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1f17604a24f702b8ae1ebec13cdebf">initELFMCObjectFileInfo</a> (const Triple &amp;T, bool Large)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdbfe468ddcbc222f2ce9193b78b05cc">initGOFFMCObjectFileInfo</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64eb15897b9d7af9a016b92b4987dee9">initCOFFMCObjectFileInfo</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4170de70ae23dab8b9d845ad4c0b4de7">initSPIRVMCObjectFileInfo</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd88923b7a7dc864fffbdc0ae35fc857">initWasmMCObjectFileInfo</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a653dd68090b96ed353f01978f471f19d">initXCOFFMCObjectFileInfo</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92cb0276b7f75b78c05d34f9d2e20177">initDXContainerObjectFileInfo</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168acdcb7c93355f3220fa7cd378a596">getDwarfComdatSection</a> (const char *Name, uint64_t Hash) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade2d9317005719a662ab8f745300de21">SupportsWeakOmittedEHFrame</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if target object file supports a weak_definition of constant 0 for an omitted EH frame. <a href="#ade2d9317005719a662ab8f745300de21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf79d9f232af620b8db28568ed1ca307">SupportsCompactUnwindWithoutEHFrame</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the target object file supports emitting a compact unwind section without an associated EH frame section. <a href="#abf79d9f232af620b8db28568ed1ca307">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0042d8e0a589778e08ec99787b31ff">OmitDwarfIfHaveCompactUnwind</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OmitDwarfIfHaveCompactUnwind - True if the target object file supports having some functions with compact unwind and other with dwarf unwind. <a href="#a8c0042d8e0a589778e08ec99787b31ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad58390471c241fb327a23c69d639e6ce">FDECFIEncoding</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FDE CFI encoding. <a href="#ad58390471c241fb327a23c69d639e6ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af121f94c2ed06e4970f99a73a9f78b54">CompactUnwindDwarfEHFrameOnly</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compact unwind encoding indicating that we should emit only an EH frame. <a href="#af121f94c2ed06e4970f99a73a9f78b54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a293288e990da3ee0cd54c7c340e33030">TextSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section directive for standard text. <a href="#a293288e990da3ee0cd54c7c340e33030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affe937af7bd751518ed18a8d3e34c687">DataSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section directive for standard data. <a href="#affe937af7bd751518ed18a8d3e34c687">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1df1d88e9ee995e0fd2a17edeaf3321">BSSSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section that is default initialized to zero. <a href="#ae1df1d88e9ee995e0fd2a17edeaf3321">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac01fb290af1907633ce3c08fa92b25e7">ReadOnlySection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section that is readonly and can contain arbitrary initialized data. <a href="#ac01fb290af1907633ce3c08fa92b25e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3958cbb873bc9ea9f052fd2e467c50d8">LSDASection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If exception handling is supported by the target, this is the section the Language Specific Data Area information is emitted to. <a href="#a3958cbb873bc9ea9f052fd2e467c50d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ab2dbd6d2ca2b266a45a5bad4d0aefa">CompactUnwindSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If exception handling is supported by the target and the target can support a compact representation of the CIE and FDE, this is the section to emit them into. <a href="#a3ab2dbd6d2ca2b266a45a5bad4d0aefa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa98be4b747852c7b11e0d262806f54e2">ImportCallSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If import call optimization is supported by the target, this is the section to emit import call data to. <a href="#aa98be4b747852c7b11e0d262806f54e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac841b4f3e34dd6628f8f40563da2f7e9">DwarfAbbrevSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a369f9522689a50e8c8c0fc161a706dc8">DwarfInfoSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1497dee70e29b9ab270c2dd2cbef610">DwarfLineSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdb36daa30c88494aea8d8d9962fcdc1">DwarfLineStrSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ae390860881e2d88fd47f4fd01169b">DwarfFrameSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f66def89abca84ed0ea119213fb1264">DwarfPubTypesSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b87eacdc6ee02c54c643fe61882d9fd">DwarfDebugInlineSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a127671854883d14ccbeebdc4170152ab">DwarfStrSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ba09d000f18b9923498f246ee9fa6a">DwarfLocSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0edfdfa7c2bdda5824ed59211e1a232e">DwarfARangesSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f8acdb78b71dc688dfc697068621c13">DwarfRangesSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b162880199e9302477d958e5eb5553">DwarfMacinfoSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ac9d437c2f7de96e7bde0f597cfa86">DwarfMacroSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247ce466a1cfde2910d105d83fdd54b3">DwarfPubNamesSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ebff500a5ac204a25fd3dbdbf4ced5">DwarfDebugNamesSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accelerator table sections. <a href="#a06ebff500a5ac204a25fd3dbdbf4ced5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61798ea59c94476d34859668b4c011f7">DwarfAccelNamesSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92ec3775abfe9d78ae0c64d4d89162eb">DwarfAccelObjCSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd8dbdf30732f0081eb7bb6eb2ff324e">DwarfAccelNamespaceSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff31709e6edc54596c52fce35f2936ca">DwarfAccelTypesSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b270bb4b74adb06ca82d1e8c66c8fe">DwarfInfoDWOSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3cdf6dd6d008e2ee24ea51f46cf4457">DwarfTypesDWOSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ea306a126227a6229dede74ba5f78a3">DwarfAbbrevDWOSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a403da8c4d9084c878a40126b89af487c">DwarfStrDWOSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac432b773b43055975c7c6d63d3c8882a">DwarfLineDWOSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec34b9a9bb09418b41aa9c4b74c59a9">DwarfLocDWOSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81bd47af3ab89763c79fc35b75724a37">DwarfStrOffDWOSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb97434bcf2f6833e9681db077c25d0d">DwarfMacinfoDWOSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af97d957759ccc048db74a151b6547ed5">DwarfMacroDWOSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c8d00998d8d294405be1110ba8aee38">DwarfStrOffSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DWARF v5 string offset and address table sections. <a href="#a0c8d00998d8d294405be1110ba8aee38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07a1ced7122e124391e700ce7e7c1198">DwarfAddrSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a680ab2608b8af2a908f4c105b9a9f345">DwarfRnglistsSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DWARF v5 range list section. <a href="#a680ab2608b8af2a908f4c105b9a9f345">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491fe4497d0cab1747db14931d0326e9">DwarfLoclistsSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DWARF v5 locations list section. <a href="#a491fe4497d0cab1747db14931d0326e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b4b5c4ed4d1c176833f8c4359bf1b6">DwarfRnglistsDWOSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DWARF v5 range and location list sections for fission. <a href="#aa7b4b5c4ed4d1c176833f8c4359bf1b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1196867114151709d10f1c3b8f853b9">DwarfLoclistsDWOSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b6e8c3916ea763fd485c043646ed9c">DwarfCUIndexSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9231efed560081f768878731eb86d8">DwarfTUIndexSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5264a0fefee534777f0c3f6d087b12c">DwarfGnuPubNamesSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section for newer gnu pubnames. <a href="#af5264a0fefee534777f0c3f6d087b12c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2539ec9bf21cfa4e6acf91af16d9688e">DwarfGnuPubTypesSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section for newer gnu pubtypes. <a href="#a2539ec9bf21cfa4e6acf91af16d9688e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a971ce0f63642ba3d7814d4f9da4b1c1f">DwarfSwiftASTSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bfb927fafa450f69ddfa0dbe784a47b">COFFDebugSymbolsSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f5d29c16645e29ce24ad5c328d141db">COFFDebugTypesSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a197216c7d50361ae89fafb0eefd080a2">COFFGlobalTypeHashesSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a822ec404e4dbb511a1aaf3c6956a9668">TLSExtraDataSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extra TLS Variable Data section. <a href="#a822ec404e4dbb511a1aaf3c6956a9668">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ff225c3f7de6dd8cd9162f786493529">TLSDataSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section directive for Thread Local data. <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a>, and Wasm. <a href="#a2ff225c3f7de6dd8cd9162f786493529">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048d5afdc5ac12623aaf755293c90c7e">TLSBSSSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section directive for Thread Local uninitialized data. <a href="#a048d5afdc5ac12623aaf755293c90c7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5a655ddfa1ed583cd1f738cf1bcadee">StackMapSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>StackMap section. <a href="#af5a655ddfa1ed583cd1f738cf1bcadee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91877751059c85cf922a1972bea85048">FaultMapSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FaultMap section. <a href="#a91877751059c85cf922a1972bea85048">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79f887ebc5b25fdb7faea28be0f11a70">RemarksSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remarks section. <a href="#a79f887ebc5b25fdb7faea28be0f11a70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0f562d2bfd7aff542770ffa13aef00">EHFrameSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EH frame section. <a href="#a8a0f562d2bfd7aff542770ffa13aef00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0bede5b09004d03828616371f3cda92">StackSizesSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section containing metadata on function stack sizes. <a href="#af0bede5b09004d03828616371f3cda92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57fd9c5d628ecc4e5f7d61cba349d51c">PseudoProbeSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section for pseudo probe information used by AutoFDO. <a href="#a57fd9c5d628ecc4e5f7d61cba349d51c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb8541a5f757a42f35d57ab27bb3d90">PseudoProbeDescSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2becbbe728f48493dc12477e8d1820bf">LLVMStatsSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876733c60b97ed94e37dce47534b4ccf">DataRelROSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7abaf19f8d77aa383376e7275492bf">MergeableConst4Section</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30b67c811ff50fad1141f3826d24ebdc">MergeableConst8Section</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13afc727a076f284996b88d722fa312b">MergeableConst16Section</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf4b5d43d65316f3cfe84f355df064c">MergeableConst32Section</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9452324c3ff87cd16cd6c5bb2db1655f">TLSTLVSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section for thread local structure information. <a href="#a9452324c3ff87cd16cd6c5bb2db1655f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f49440c6a3766d411ea0a04e5c8d5d">TLSThreadInitSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section for thread local data initialization functions. <a href="#a08f49440c6a3766d411ea0a04e5c8d5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c9f99d2a934df382458e6e2d6602f8e">CStringSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49603bc80739ef76b0ce19237b42586">UStringSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dad3667a653fbc7a08369b1e04e8615">TextCoalSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee5c90f18c4adc512313f31665e1428">ConstTextCoalSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af57563b5bee19a31b86e29d6593788dd">ConstDataSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0734bed0d8efcf099d0c6e704935552">DataCoalSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b515d5a71b1ed09c80f3069011a32b2">ConstDataCoalSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab574ef9cfe2336b78cd8f0d0fb9dc94a">DataCommonSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dfefb3042725f9ef882ca9fa8147091">DataBSSSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f2a514a3f7bbc64a0c8c3269698beb3">FourByteConstantSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee2ea0a72fcfd6b4bf43042285dfd68f">EightByteConstantSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad1f88c540c39eb55ebb9716e9d63495">SixteenByteConstantSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75325c9432bb89f0c90caeef38461552">LazySymbolPointerSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0423ed6a9ff9b2e653a78a4643838f1a">NonLazySymbolPointerSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3742c569070bc5ddb323deac4983999b">ThreadLocalPointerSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31c1b6bc656f0f1909a03e48513c4706">AddrSigSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f9d4285bc3df2066994a75326e9a285">DrectveSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> specific sections. <a href="#a8f9d4285bc3df2066994a75326e9a285">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b2c08aaf827fbf89b7f265f2234fc5e">PDataSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d0397231f6e4991d3321ea159794d39">XDataSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1439cb6bd26373b56610b4e794fa16a">SXDataSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09d6ad4c554c3bd763fe58208721d176">GEHContSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d5eab61a198061779362db437b1c069">GFIDsSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9361c92c8b4dc87ddd79c56c5266ec">GIATsSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3db2c2f7c00f71cb454e731c42d6a18">GLJMPSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667d3420552bec16c0ba1b92b3b08612">PPA1Section</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5de2729a910fb3705878d9110ac7f93">PPA2Section</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5a22e67493472a697d901aec7bb90de">PPA2ListSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18dd29c8a98853d938003de3728d05ee">ADASection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32faab3bb215ef93964baecd36b5dcd4">IDRLSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4c2e727e78c267cd3618ecd1470060a">TOCBaseSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6552bb97aa2622ca7c1a18f17f8eda38">ReadOnly8Section</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c403c28c309d3dcee0ddaf70bda29fc">ReadOnly16Section</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/binaryformat/#ab355a2b14b4cc35373b4526fbfab894dae1876e1602335f6a4e50b3c18cd836da">binaryformat::Swift5ReflectionSectionKind::last</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a445da24e671664ed5a79d6f034bfb301">Swift5ReflectionSections</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c445574d033021650fc085d0558856">PositionIndependent</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48af47fd266384691ccc49abbb7a99c2">Ctx</a> = nullptr</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~MCObjectFileInfo() {#aaf20a9c3eeee245072bf1913e848fe13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCObjectFileInfo::~MCObjectFileInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getADASection() {#a33186d2160644f7da1730786dc47d5d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getADASection ()</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a18dd29c8a98853d938003de3728d05ee">ADASection</a>.</p>

</div>
</div>

### getAddrSigSection() {#a2f1ff4f0cc25dc5cc546db7ea694e9dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getAddrSigSection ()</td>
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



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a31c1b6bc656f0f1909a03e48513c4706">AddrSigSection</a>.</p>

</div>
</div>

### getBBAddrMapSection() {#a6f09a8aebb37ccdb0041ea53a9b6ba88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * MCObjectFileInfo::getBBAddrMapSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; TextSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 1104 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#aba2770972dc030b69d7c4f799eca7441">llvm::MCSectionELF::getGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a3483097b89f7d84944bd0c03f50cff45">llvm::MCSectionELF::getUniqueID</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890ac8172f032ec16640838e35d9e8c78b50">llvm::MCContext::IsELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa4128c7283d8e6e763e8810a91c2dc1e">llvm::ELF::SHF_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a9284ee71917fdddaa2eeaba1bfe17e2b">llvm::ELF::SHF_LINK_ORDER</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcabf9a9b472d62e43e5e49fc2f468abcce">llvm::ELF::SHT_LLVM_BB_ADDR_MAP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5f32c10b46f4e956f21552b0984ae68f">llvm::AsmPrinter::emitBBAddrMapSection</a>.</p>

</div>
</div>

### getBSSSection() {#a6de12269943e6388af512d8b96cbd9e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getBSSSection ()</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ae1df1d88e9ee995e0fd2a17edeaf3321">BSSSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a98ffe083ab6ade934683a26a65204179">llvm::MCWinCOFFStreamer::emitLocalCommonSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a94031e736c9e04044ac7181147a54bf6">llvm::MipsTargetELFStreamer::finish</a>.</p>

</div>
</div>

### getCOFFDebugSymbolsSection() {#ac77dbfa104b3138b7684fe0334348011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getCOFFDebugSymbolsSection ()</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a3bfb927fafa450f69ddfa0dbe784a47b">COFFDebugSymbolsSection</a>.</p>

</div>
</div>

### getCOFFDebugTypesSection() {#ad5f6572e439f23e83446c8b36337f6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getCOFFDebugTypesSection ()</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a6f5d29c16645e29ce24ad5c328d141db">COFFDebugTypesSection</a>.</p>

</div>
</div>

### getCOFFGlobalTypeHashesSection() {#af483c4b79ae094d99c1e24a643f61111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getCOFFGlobalTypeHashesSection ()</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a197216c7d50361ae89fafb0eefd080a2">COFFGlobalTypeHashesSection</a>.</p>

</div>
</div>

### getCompactUnwindDwarfEHFrameOnly() {#a5eb24afad571f2444e56298ef8c2693f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCObjectFileInfo::getCompactUnwindDwarfEHFrameOnly ()</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#af121f94c2ed06e4970f99a73a9f78b54">CompactUnwindDwarfEHFrameOnly</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a53a38280a7cf030655d4ad153dcf8cc1">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCompactUnwind</a>.</p>

</div>
</div>

### getCompactUnwindSection() {#aff8632a15d42e54c1367a81afc1b6602}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getCompactUnwindSection ()</td>
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



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a3ab2dbd6d2ca2b266a45a5bad4d0aefa">CompactUnwindSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7e24606b8fe6124decedb17e5ffa405e">llvm::X86FrameLowering::enableShrinkWrapping</a>.</p>

</div>
</div>

### getConstDataCoalSection() {#a7248a5a87e6e340ad0b0f3c77eb17b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getConstDataCoalSection ()</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a2b515d5a71b1ed09c80f3069011a32b2">ConstDataCoalSection</a>.</p>

</div>
</div>

### getConstDataSection() {#a67cfba876d87d0a698a534ed2c337452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getConstDataSection ()</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#af57563b5bee19a31b86e29d6593788dd">ConstDataSection</a>.</p>

</div>
</div>

### getConstTextCoalSection() {#a3f8a5c332180d7dcf2c7865d7b611a1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getConstTextCoalSection ()</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a2ee5c90f18c4adc512313f31665e1428">ConstTextCoalSection</a>.</p>

</div>
</div>

### getContext() {#afcda39b4059eca86c10397b7a938a729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext &amp; llvm::MCObjectFileInfo::getContext ()</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a0483bd140eacb91339ca4e622b98ae04">llvm::TargetLoweringObjectFile::emitCGProfileMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a88c088e4fb14a140785c69f3af654b55">llvm::TargetLoweringObjectFileCOFF::emitLinkerDirectives</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3cd35b2eb52932034ebff3b18e0dcf0a">llvm::TargetLoweringObjectFileELF::emitLinkerDirectives</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a467c9de76e4b351317463d4c803cebc4">llvm::TargetLoweringObjectFileCOFF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a7bdbc0657e52a4bffa675c290b32840f">llvm::TargetLoweringObjectFileMachO::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a6d60dc7f70a5ab7a44c79f6bba354c0f">llvm::TargetLoweringObjectFileELF::emitPersonalityValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#a50239bad1326b962fc58f1b311e7e255">llvm::AArch64_ELFTargetObjectFile::emitPersonalityValueImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-erlanggcprinter-cpp-/erlanggcprinter/#a574679a34186d5db3a7b14b0ce5c5078">anonymous{ErlangGCPrinter.cpp}::ErlangGCPrinter::finishAssembly</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#afa8c25d9479e583055f8cd02df823840">llvm::AArch64_ELFTargetObjectFile::getAuthPtrSlotSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#a74cb396080d0202745507029ad8d65c5">llvm::AArch64_MachoTargetObjectFile::getAuthPtrSlotSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2386d783a4ecb933326c3f1d491ab163">llvm::TargetLoweringObjectFile::getCallSiteEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a4969e899dcb64a6d45ddc42b5bf4f236">llvm::TargetLoweringObjectFileELF::getCFIPersonalitySymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#a298d9fbfabe7c231654dab9f79d09a54">llvm::ARMElfTargetObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetobjectfile/#a4824f185b09fa4322916df3508816b22">llvm::MipsTargetObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelftargetobjectfile/#a7aa41b5373e9b1834047d254cf00e9f0">llvm::SystemZELFTargetObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a98b1035db70203b5f4896096926d07be">llvm::TargetLoweringObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/x86elftargetobjectfile/#a98e6b09f214872dfea075356cab62e87">llvm::X86ELFTargetObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/dxiltargetobjectfile/#ae6c346fad803c016b4709a8a6e9deeda">DXILTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#acf4019263b41c295bc55032dd651b6e4">llvm::HexagonTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a1d07788150d8bd44cbba78db405f1574">llvm::TargetLoweringObjectFileCOFF::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#af043f3b43eb6797a702c062b9a3d54fe">llvm::TargetLoweringObjectFileELF::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a5e9dfc1cc5890ea9fb55b1dedcc2bd27">llvm::TargetLoweringObjectFileMachO::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#ad7fddd197449964ffb791c5a7e1900ec">llvm::TargetLoweringObjectFileWasm::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a6027e9f6e624a2ac869c29f803baa739">llvm::TargetLoweringObjectFileXCOFF::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#a820356be1c79740facb142ac6eaa9e39">llvm::XCoreTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a3e40bda8245f90bbe4a72d083b4d8431">llvm::TargetLoweringObjectFileXCOFF::getFunctionEntryPointSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#ab479db6c0dce9d07c70ea70016ed99ff">llvm::AArch64_ELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#aab2cc2813c5a774bb4f83b6f9ae5a98b">llvm::AArch64_MachoTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#a62d13f21f5dde00137a248d95cf8acd6">llvm::ARMElfTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#affc824acbbe220a54656c5519b408c4b">llvm::RISCVELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64elftargetobjectfile/#a7fade16e9dc1ebc9b6974b12857f5abe">llvm::X86_64ELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64machotargetobjectfile/#abe4296cf38fa7bebb355865172c0acac">llvm::X86_64MachoTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#aaf998515054f452d13147bdfa76f33f7">llvm::ARMElfTargetObjectFile::getIndirectSymViaRWPI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#ac81b774f768883eac6a9d46cdc8b82a8">llvm::TargetLoweringObjectFileELF::getSectionForCommandLines</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a8df1069695195b5c96f1cc2ebf3a3973">llvm::TargetLoweringObjectFileMachO::getSectionForCommandLines</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a300546d54aa331d7615052bd9ba5883d">llvm::TargetLoweringObjectFileCOFF::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a2ddf5387f9cd603891e1933c2f84cf65">llvm::TargetLoweringObjectFileXCOFF::getSectionForExternalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#adee710107b7fec9dcf8076bd0dc44d2d">llvm::TargetLoweringObjectFileXCOFF::getSectionForFunctionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#ad75e2aa4d67c101594e1f7448588c8d3">llvm::TargetLoweringObjectFileCOFF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a38d2d101b244807c73327e57f705ef7e">llvm::TargetLoweringObjectFileELF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a59f70e2f83b2a97372e18a6c6316550d">llvm::TargetLoweringObjectFileXCOFF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#ac8b6405ee0ca88cdcd7aea5d129551c4">llvm::TargetLoweringObjectFileELF::getSectionForLSDA</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilegoff/#a75c01c604ceb3f4e3a45c6ee4df1985f">llvm::TargetLoweringObjectFileGOFF::getSectionForLSDA</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afff1a14d07c4f0d35848b797930090c6">llvm::TargetLoweringObjectFileXCOFF::getSectionForLSDA</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#ae5ed3bb52c2c0b532692d33df8dd705f">llvm::TargetLoweringObjectFileELF::getSectionForMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a24e99c9fbb9fedd3a9b504d09ddfa21b">llvm::TargetLoweringObjectFileXCOFF::getSectionForTOCEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5b24916c9e1d8dd6e832abff33c763a8">llvm::TargetLoweringObjectFileCOFF::getStaticCtorSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2db5f2d616786cd3aeab03d0d5115fca">llvm::TargetLoweringObjectFileELF::getStaticCtorSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#a5b6997ec5b6f4358e270f2e5d9be4657">llvm::TargetLoweringObjectFileWasm::getStaticCtorSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#ad08c27804856dd188e679696e0a0343b">llvm::TargetLoweringObjectFileCOFF::getStaticDtorSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a4d95ba93070cf6ac583ce923884ee5da">llvm::TargetLoweringObjectFileELF::getStaticDtorSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#acc39c2b4b06165d766b52ac292ef2aff">llvm::TargetMachine::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a866133bf888d0b8bbce2275845511edb">llvm::TargetLoweringObjectFile::getSymbolWithGlobalValueBase</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#ad8e3992ea2835dec86a54cfa3ba634bf">llvm::RISCVELFTargetObjectFile::getTextSectionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcobjectfileinfo/#a8f714bfcff71c3a30c262042fa355c79">llvm::RISCVMCObjectFileInfo::getTextSectionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#abda04e72e43a3aaef8a55e4ecf91d127">llvm::AArch64_MachoTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#ad44640388d6a28f1c14510e7686042fc">llvm::ARMElfTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelftargetobjectfile/#a953050dfdd0d33bc59eb08438aa5d88c">llvm::SparcELFTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#aa9a2f88f6a81e5a8fa1bef4833eef6ba">llvm::TargetLoweringObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a726934c33655de3d8c59b38d0e946a62">llvm::TargetLoweringObjectFileELF::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#ae41814965809c6fb6403ca6338710a25">llvm::TargetLoweringObjectFileMachO::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64machotargetobjectfile/#a17558be02e5c14c099a7f347669a3132">llvm::X86_64MachoTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#ac1cd29692079a1f57202b9947c5f5521">llvm::TargetLoweringObjectFile::getTTypeReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a050de8d61f37b8c99a85fe4a0f8deaf2">llvm::TargetLoweringObjectFileELF::getUniqueSectionForFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#a6cf97a009c47b155189ba67312aa6054">llvm::HexagonTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetobjectfile/#ab6f22139bb2e11e60a30bb572dfcf5a2">llvm::LanaiTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kelftargetobjectfile/#acb04f79feb01601c3da467d19ea03b9f">llvm::M68kELFTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetobjectfile/#ae3a8326eff629fec000d741c44b730bd">llvm::MipsTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#ac2e30a188970123389a986eb645ed6c7">llvm::RISCVELFTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#ae013785be06f550645a52bb67bea191f">llvm::TargetLoweringObjectFileELF::InitializeELF</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#a43cbf327e1543318ec8d7a084634995a">llvm::TargetLoweringObjectFileWasm::InitializeWasm</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a9c941e2d8cbdc56abb6867dade371206">llvm::TargetLoweringObjectFileELF::lowerDSOLocalEquivalent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a09a7c632e2befc0851032e0d8983029c">llvm::TargetLoweringObjectFileCOFF::lowerRelativeReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a745752b67a45e5dc6b1f2a6985f68937">llvm::TargetLoweringObjectFileELF::lowerRelativeReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#a0d892b52d1df1d1cb59054c2dab539be">llvm::TargetLoweringObjectFileWasm::lowerRelativeReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#af34b3385ad6d2dc040f431e84cd822eb">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::RISCVAsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/r600asmprinter/#a0b18e6ab50db6fc19e4e3722ee459df8">llvm::R600AsmPrinter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetobjectfile/#a2ac5016664f09fbfd8b97a954fccd664">llvm::AVRTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#a56f18a5c4bcd2858f20bb765323fc89a">llvm::RISCVELFTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a7c532f94d6bb9c4aba4190b81a7f8dbf">llvm::TargetLoweringObjectFileELF::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilegoff/#a8c58f11a5aa16a65fa81203993787033">llvm::TargetLoweringObjectFileGOFF::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#ae9c61f87f856e9bf0341b4d68136c3ab">llvm::TargetLoweringObjectFileWasm::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afa6dda813be79bdc7753ef52b9b5ec56">llvm::TargetLoweringObjectFileXCOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getCStringSection() {#ad0ded12f6aff48c98bd0bc9d98d8b77e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getCStringSection ()</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a8c9f99d2a934df382458e6e2d6602f8e">CStringSection</a>.</p>

</div>
</div>

### getDataBSSSection() {#ae91f8af9e6e309f03754093a2892c3ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDataBSSSection ()</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a6dfefb3042725f9ef882ca9fa8147091">DataBSSSection</a>.</p>

</div>
</div>

### getDataCoalSection() {#a67fcb9565b45811881bae17102eedcef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getDataCoalSection ()</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#aa0734bed0d8efcf099d0c6e704935552">DataCoalSection</a>.</p>

</div>
</div>

### getDataCommonSection() {#af1bd56da7a380fcec3b80dd3994f50f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getDataCommonSection ()</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ab574ef9cfe2336b78cd8f0d0fb9dc94a">DataCommonSection</a>.</p>

</div>
</div>

### getDataRelROSection() {#a0336b43f021525b0a865076f315df0b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDataRelROSection ()</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a876733c60b97ed94e37dce47534b4ccf">DataRelROSection</a>.</p>

</div>
</div>

### getDataSection() {#afd9ae84447d7be72e18fd897b3f036d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDataSection ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#affe937af7bd751518ed18a8d3e34c687">DataSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ocamlgcprinter-cpp-/ocamlgcmetadataprinter/#ab53bb67e2b02768e2950e8991829e32d">anonymous{OcamlGCPrinter.cpp}::OcamlGCMetadataPrinter::beginAssembly</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa9a2aed0d26a4fca41f8fc0986a3f12b">llvm::AsmPrinter::doFinalization</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a94031e736c9e04044ac7181147a54bf6">llvm::MipsTargetELFStreamer::finish</a>, <a href="/web-llvm/docs/api/classes/anonymous-ocamlgcprinter-cpp-/ocamlgcmetadataprinter/#a6abb5b979094dd3eba1a0375a96e365a">anonymous{OcamlGCPrinter.cpp}::OcamlGCMetadataPrinter::finishAssembly</a> and <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetobjectfile/#a877dfce288cde68b1059ea4f77208627">llvm::NVPTXTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getDrectveSection() {#a78c3233931fda64aa2d37bce0ccc0f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDrectveSection ()</td>
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



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a8f9d4285bc3df2066994a75326e9a285">DrectveSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a46ca451d0ba24a1a138f28bd71a72271">llvm::MCWinCOFFStreamer::emitCommonSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a88c088e4fb14a140785c69f3af654b55">llvm::TargetLoweringObjectFileCOFF::emitLinkerDirectives</a>.</p>

</div>
</div>

### getDwarfAbbrevDWOSection() {#ab7b38278009d729724c809dcbc9d5b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfAbbrevDWOSection ()</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a6ea306a126227a6229dede74ba5f78a3">DwarfAbbrevDWOSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfAbbrevSection() {#ac10c6a9d85782db274d19ef8f828d9fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfAbbrevSection ()</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ac841b4f3e34dd6628f8f40563da2f7e9">DwarfAbbrevSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0c77b8d4ff2ea875d1c29128d4ef848">llvm::DwarfUnit::emitCommonHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfAccelNamespaceSection() {#a38d14819d39b592f82540549231ed94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfAccelNamespaceSection ()</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#afd8dbdf30732f0081eb7bb6eb2ff324e">DwarfAccelNamespaceSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfAccelNamesSection() {#ab0a98f2924de06f55315c207f3c0eac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfAccelNamesSection ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a61798ea59c94476d34859668b4c011f7">DwarfAccelNamesSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfAccelObjCSection() {#ae1a65d3a4229133502a782ab58741e60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfAccelObjCSection ()</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a92ec3775abfe9d78ae0c64d4d89162eb">DwarfAccelObjCSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfAccelTypesSection() {#a0f1b3ba79882a148045283d71753897a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfAccelTypesSection ()</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#aff31709e6edc54596c52fce35f2936ca">DwarfAccelTypesSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfAddrSection() {#a7dd91b8042158479671aa8f357fd5f62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfAddrSection ()</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a07a1ced7122e124391e700ce7e7c1198">DwarfAddrSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3abb9664e1a14148cc2ad7f330009b20">llvm::DwarfCompileUnit::addAddrTableBase</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfARangesSection() {#ae17df2cce5c5b2cb1688d22f2d90820c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfARangesSection ()</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a0edfdfa7c2bdda5824ed59211e1a232e">DwarfARangesSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfCUIndexSection() {#adc1a8b3a5ab5c4c460feb4a00dd2a71c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfCUIndexSection ()</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a28b6e8c3916ea763fd485c043646ed9c">DwarfCUIndexSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfDebugInlineSection() {#a9ba4c71757b3cefaeefeb6d440d0ee91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getDwarfDebugInlineSection ()</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a6b87eacdc6ee02c54c643fe61882d9fd">DwarfDebugInlineSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfDebugNamesSection() {#a7031b56e11bd03c7a1f7ab2e68d5d095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfDebugNamesSection ()</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a06ebff500a5ac204a25fd3dbdbf4ced5">DwarfDebugNamesSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfFrameSection() {#a8357c20a6fa8dd32020a98ed65971587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfFrameSection ()</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#aa0ae390860881e2d88fd47f4fd01169b">DwarfFrameSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfGnuPubNamesSection() {#a29cddb4a82114802b9020d33d7e4dbd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfGnuPubNamesSection ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#af5264a0fefee534777f0c3f6d087b12c">DwarfGnuPubNamesSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfGnuPubTypesSection() {#a9eaa64fd2b7b36baec3fb81e574b6b8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfGnuPubTypesSection ()</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a2539ec9bf21cfa4e6acf91af16d9688e">DwarfGnuPubTypesSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfInfoDWOSection() {#a3d9643e39995d567cfd19465abcfabaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfInfoDWOSection ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ae1b270bb4b74adb06ca82d1e8c66c8fe">DwarfInfoDWOSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfInfoSection() {#a82d739b35c6534d476fc5bf7d2ee57cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfInfoSection ()</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a369f9522689a50e8c8c0fc161a706dc8">DwarfInfoSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfInfoSection() {#a38bf1682d25dc5998f1de9fdf81fa44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfInfoSection (uint64_t Hash)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>

</div>
</div>

### getDwarfLineDWOSection() {#a3b7d7a8e94a349e8343c52c9759bceb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfLineDWOSection ()</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ac432b773b43055975c7c6d63d3c8882a">DwarfLineDWOSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfLineSection() {#a82d3abaa97d9734f17bdd52cfdf00fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfLineSection ()</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ad1497dee70e29b9ab270c2dd2cbef610">DwarfLineSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a780e3087cd40ac6f03e93e1722993cc2">llvm::DwarfCompileUnit::applyStmtList</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a89cdc6ed6476f39c32e5a49327bb692e">llvm::MCDwarfLineTable::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a5bf6adcaa4ad6740a1a7544e827a5231">llvm::DwarfCompileUnit::initStmtList</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfLineStrSection() {#a5e2906ef9fe9b6b1bef3e104b1519cd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfLineStrSection ()</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#abdb36daa30c88494aea8d8d9962fcdc1">DwarfLineStrSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#a1578026c1ceb637e4b37023412f971ac">llvm::MCDwarfLineStr::emitSection</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfLocDWOSection() {#ae0c42bab7cf6d48b020adbec53263a2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfLocDWOSection ()</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a1ec34b9a9bb09418b41aa9c4b74c59a9">DwarfLocDWOSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfLoclistsDWOSection() {#a6713cdb4592c3c97a4a90e3b19a241b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfLoclistsDWOSection ()</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ae1196867114151709d10f1c3b8f853b9">DwarfLoclistsDWOSection</a>.</p>

</div>
</div>

### getDwarfLoclistsSection() {#a0da64dcd145f4d0e82f845499c055391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfLoclistsSection ()</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a491fe4497d0cab1747db14931d0326e9">DwarfLoclistsSection</a>.</p>

</div>
</div>

### getDwarfLocSection() {#ae7548b994352e41c0a628936d3f75c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfLocSection ()</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a56ba09d000f18b9923498f246ee9fa6a">DwarfLocSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfMacinfoDWOSection() {#a7512a0f2f3c4476649d5eab18f4888ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfMacinfoDWOSection ()</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#afb97434bcf2f6833e9681db077c25d0d">DwarfMacinfoDWOSection</a>.</p>

</div>
</div>

### getDwarfMacinfoSection() {#ae04d121e734cd5ad456233e5d6ebbb3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfMacinfoSection ()</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a22b162880199e9302477d958e5eb5553">DwarfMacinfoSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfMacroDWOSection() {#afa6f1092f5467897d43cf376fd5c1886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfMacroDWOSection ()</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#af97d957759ccc048db74a151b6547ed5">DwarfMacroDWOSection</a>.</p>

</div>
</div>

### getDwarfMacroSection() {#a4ba5c0a8e62bf4ce62c2e815808ae159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfMacroSection ()</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a99ac9d437c2f7de96e7bde0f597cfa86">DwarfMacroSection</a>.</p>

</div>
</div>

### getDwarfPubNamesSection() {#a49eb3fca43b2ceca3ff8c706fae7ddab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfPubNamesSection ()</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a247ce466a1cfde2910d105d83fdd54b3">DwarfPubNamesSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfPubTypesSection() {#a97622da3f5114dfa0bb2f2285bf37cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfPubTypesSection ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a7f66def89abca84ed0ea119213fb1264">DwarfPubTypesSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfRangesSection() {#a31df4edd580fc4f6e43318cd9c5ed5bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfRangesSection ()</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a7f8acdb78b71dc688dfc697068621c13">DwarfRangesSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4e4e697039d4692563c2ccc3608864d1">llvm::DwarfCompileUnit::addScopeRangeList</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfRnglistsDWOSection() {#ab7bd3800ca2a48cd600e03e97c98f059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfRnglistsDWOSection ()</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#aa7b4b5c4ed4d1c176833f8c4359bf1b6">DwarfRnglistsDWOSection</a>.</p>

</div>
</div>

### getDwarfRnglistsSection() {#a7cddd5b91a2f88c1c204cafeca322517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfRnglistsSection ()</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a680ab2608b8af2a908f4c105b9a9f345">DwarfRnglistsSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab967d1b87b81cc88415cd294bc1d70c4">llvm::DwarfUnit::addRnglistsBase</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>.</p>

</div>
</div>

### getDwarfStrDWOSection() {#aa89ba1b4a04c6aab9e36521b0af3212e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfStrDWOSection ()</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a403da8c4d9084c878a40126b89af487c">DwarfStrDWOSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfStrOffDWOSection() {#a2be455ebf2215c76244c7d1cc4697492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfStrOffDWOSection ()</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a81bd47af3ab89763c79fc35b75724a37">DwarfStrOffDWOSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfStrOffSection() {#a3d677a1ab07bb4796933369f69396459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfStrOffSection ()</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a0c8d00998d8d294405be1110ba8aee38">DwarfStrOffSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c1d3ec37aec1008ed52018d257a2608">llvm::DwarfUnit::addStringOffsetsStart</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfStrSection() {#a5915c91abcb7f7eb43cae094ec8b4ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfStrSection ()</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a127671854883d14ccbeebdc4170152ab">DwarfStrSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfSwiftASTSection() {#ac28a6e4a483c4c56f254884ed9024648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfSwiftASTSection ()</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a971ce0f63642ba3d7814d4f9da4b1c1f">DwarfSwiftASTSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfTUIndexSection() {#a6f7b6409e225107d1b3e430471b80c50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfTUIndexSection ()</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#add9231efed560081f768878731eb86d8">DwarfTUIndexSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfTypesDWOSection() {#a47aba8387dcc1520ee5846c047be762d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfTypesDWOSection ()</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#af3cdf6dd6d008e2ee24ea51f46cf4457">DwarfTypesDWOSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp/#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a>.</p>

</div>
</div>

### getDwarfTypesSection() {#a9e706526e3ba2c8ee93dae01f573f602}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getDwarfTypesSection (uint64_t Hash)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>

</div>
</div>

### getEHFrameSection() {#a31d963341d03839c532b62ef3fd568c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getEHFrameSection ()</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a8a0f562d2bfd7aff542770ffa13aef00">EHFrameSection</a>.</p>

</div>
</div>

### getEightByteConstantSection() {#a8986417f698b06ed587b13206ebf6cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getEightByteConstantSection ()</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#aee2ea0a72fcfd6b4bf43042285dfd68f">EightByteConstantSection</a>.</p>

</div>
</div>

### getFaultMapSection() {#a39753c797dc0dce0e2f7f367e4203556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getFaultMapSection ()</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a91877751059c85cf922a1972bea85048">FaultMapSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/faultmaps/#a393b0f5b51aef71d44cc36b4e7b048a7">llvm::FaultMaps::serializeToFaultMapSection</a>.</p>

</div>
</div>

### getFDEEncoding() {#a9b753f5b5ed5d2d28462e83e7c5e923b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCObjectFileInfo::getFDEEncoding ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ad58390471c241fb327a23c69d639e6ce">FDECFIEncoding</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a53a38280a7cf030655d4ad153dcf8cc1">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCompactUnwind</a> and <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>.</p>

</div>
</div>

### getFourByteConstantSection() {#aba452decdc0d6e2ec7c55587cf0e8387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getFourByteConstantSection ()</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a5f2a514a3f7bbc64a0c8c3269698beb3">FourByteConstantSection</a>.</p>

</div>
</div>

### getGEHContSection() {#a3fdc31dfe6ba58f020c623009ea8581e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getGEHContSection ()</td>
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



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a09d6ad4c554c3bd763fe58208721d176">GEHContSection</a>.</p>

</div>
</div>

### getGFIDsSection() {#a63b8430be4ec071180c26ab9e34c495a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getGFIDsSection ()</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a3d5eab61a198061779362db437b1c069">GFIDsSection</a>.</p>

</div>
</div>

### getGIATsSection() {#ada5d9fd0747603e74881f463d8d87ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getGIATsSection ()</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a6e9361c92c8b4dc87ddd79c56c5266ec">GIATsSection</a>.</p>

</div>
</div>

### getGLJMPSection() {#ace74c8038b708823632d7f3c22e28154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getGLJMPSection ()</td>
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



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#af3db2c2f7c00f71cb454e731c42d6a18">GLJMPSection</a>.</p>

</div>
</div>

### getIDRLSection() {#ac2deae42e85e5f97a4f86b2b63062aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getIDRLSection ()</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a32faab3bb215ef93964baecd36b5dcd4">IDRLSection</a>.</p>

</div>
</div>

### getImportCallSection() {#adc22c43614460f4c34ed60b32c8b2ef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getImportCallSection ()</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#aa98be4b747852c7b11e0d262806f54e2">ImportCallSection</a>.</p>

</div>
</div>

### getKCFITrapSection() {#a919076c2cfa73586ca99b52ff984ae40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * MCObjectFileInfo::getKCFITrapSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; TextSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 1124 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#aba2770972dc030b69d7c4f799eca7441">llvm::MCSectionELF::getGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a3483097b89f7d84944bd0c03f50cff45">llvm::MCSectionELF::getUniqueID</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890ac8172f032ec16640838e35d9e8c78b50">llvm::MCContext::IsELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa4128c7283d8e6e763e8810a91c2dc1e">llvm::ELF::SHF_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a9284ee71917fdddaa2eeaba1bfe17e2b">llvm::ELF::SHF_LINK_ORDER</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a37e4077d932671c9b2500a3584f87ae4">llvm::AsmPrinter::emitKCFITrapEntry</a>.</p>

</div>
</div>

### getLazySymbolPointerSection() {#a7bce74eda9ad4f8992b959ad6a7e3386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getLazySymbolPointerSection ()</td>
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



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a75325c9432bb89f0c90caeef38461552">LazySymbolPointerSection</a>.</p>

</div>
</div>

### getLLVMStatsSection() {#a2829cb48c8fe186a1318a5df7b4e11da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * MCObjectFileInfo::getLLVMStatsSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 1184 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>


<p>Reference <a href="#a2becbbe728f48493dc12477e8d1820bf">LLVMStatsSection</a>.</p>

</div>
</div>

### getLSDASection() {#a94b2a8fa73fa90decda080df0772a13d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getLSDASection ()</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a3958cbb873bc9ea9f052fd2e467c50d8">LSDASection</a>.</p>

</div>
</div>

### getMergeableConst16Section() {#a1a6ce7b3647fc22dc5e8e79dc170aea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getMergeableConst16Section ()</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a13afc727a076f284996b88d722fa312b">MergeableConst16Section</a>.</p>

</div>
</div>

### getMergeableConst32Section() {#a1f41a87ecc86ac0049cb84c369ce1188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getMergeableConst32Section ()</td>
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



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#aabf4b5d43d65316f3cfe84f355df064c">MergeableConst32Section</a>.</p>

</div>
</div>

### getMergeableConst4Section() {#a13d95da0ffa6baee110e7fa2f4c97bed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getMergeableConst4Section ()</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a1f7abaf19f8d77aa383376e7275492bf">MergeableConst4Section</a>.</p>

</div>
</div>

### getMergeableConst8Section() {#aa7af67f26eb452f7afe236b200622839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getMergeableConst8Section ()</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a30b67c811ff50fad1141f3826d24ebdc">MergeableConst8Section</a>.</p>

</div>
</div>

### getNonLazySymbolPointerSection() {#ae3992a89b8f47181ead24dd08b5e73ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getNonLazySymbolPointerSection ()</td>
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



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a0423ed6a9ff9b2e653a78a4643838f1a">NonLazySymbolPointerSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a9f2d9f34828769634981f82c4977d930">llvm::ARMAsmPrinter::emitEndOfAsmFile</a>.</p>

</div>
</div>

### getOmitDwarfIfHaveCompactUnwind() {#ace2637cdddf7452b83365442e31a5d1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCObjectFileInfo::getOmitDwarfIfHaveCompactUnwind ()</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a8c0042d8e0a589778e08ec99787b31ff">OmitDwarfIfHaveCompactUnwind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a>.</p>

</div>
</div>

### getPCSection() {#ab6ce753721421b09ebdefeec3e7e993e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * MCObjectFileInfo::getPCSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * TextSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="#af1e49c4350a67d9c442c39ab1dc211eb">getTextSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890ac8172f032ec16640838e35d9e8c78b50">llvm::MCContext::IsELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa4128c7283d8e6e763e8810a91c2dc1e">llvm::ELF::SHF_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a9284ee71917fdddaa2eeaba1bfe17e2b">llvm::ELF::SHF_LINK_ORDER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5fdc8e2ed6d4f1c0f6936a0291ec496c">llvm::AsmPrinter::emitPCSections</a>.</p>

</div>
</div>

### getPDataSection() {#a33c221af9ebc8c35c9c0dc601f50c39a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getPDataSection ()</td>
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



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a7b2c08aaf827fbf89b7f265f2234fc5e">PDataSection</a>.</p>

</div>
</div>

### getPPA1Section() {#a9f3e57a0a153a47b66dbea2a68962d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getPPA1Section ()</td>
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



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a667d3420552bec16c0ba1b92b3b08612">PPA1Section</a>.</p>

</div>
</div>

### getPPA2ListSection() {#a913e2c8b44957daa6dfe02d906e8bb09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getPPA2ListSection ()</td>
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



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ae5a22e67493472a697d901aec7bb90de">PPA2ListSection</a>.</p>

</div>
</div>

### getPPA2Section() {#afd4544fcbf850d4876416965a6518725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getPPA2Section ()</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ad5de2729a910fb3705878d9110ac7f93">PPA2Section</a>.</p>

</div>
</div>

### getPseudoProbeDescSection() {#a427ea8030e264e1e94ec134806be72a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * MCObjectFileInfo::getPseudoProbeDescSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a19048a597f3c3778eefb67f07d3d8bc9">llvm::MCSectionELF::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890ac8172f032ec16640838e35d9e8c78b50">llvm::MCContext::IsELF</a>, <a href="#a7eb8541a5f757a42f35d57ab27bb3d90">PseudoProbeDescSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa4128c7283d8e6e763e8810a91c2dc1e">llvm::ELF::SHF_GROUP</a>.</p>

</div>
</div>

### getPseudoProbeSection() {#a7cec802e187b8b84478ffe1fa783a2dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * MCObjectFileInfo::getPseudoProbeSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; TextSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 1143 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890ac8172f032ec16640838e35d9e8c78b50">llvm::MCContext::IsELF</a>, <a href="#a57fd9c5d628ecc4e5f7d61cba349d51c">PseudoProbeSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa4128c7283d8e6e763e8810a91c2dc1e">llvm::ELF::SHF_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a9284ee71917fdddaa2eeaba1bfe17e2b">llvm::ELF::SHF_LINK_ORDER</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>.</p>

</div>
</div>

### getReadOnlySection() {#ab14fbbabe5077f89e7d887b3d3d90d0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getReadOnlySection ()</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ac01fb290af1907633ce3c08fa92b25e7">ReadOnlySection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa07427c984394cc2c4b4cf8b7158def4">llvm::AMDGPUAsmPrinter::emitFunctionBodyEnd</a>.</p>

</div>
</div>

### getRemarksSection() {#a706b30b9956c1eb3a09f663d2a09d87d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getRemarksSection ()</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a79f887ebc5b25fdb7faea28be0f11a70">RemarksSection</a>.</p>

</div>
</div>

### getSixteenByteConstantSection() {#ae4e8241ff6fbcd226417943ac30c1a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getSixteenByteConstantSection ()</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#aad1f88c540c39eb55ebb9716e9d63495">SixteenByteConstantSection</a>.</p>

</div>
</div>

### getStackMapSection() {#aaded1e857e3e6aa44d76a3a967624818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getStackMapSection ()</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#af5a655ddfa1ed583cd1f738cf1bcadee">StackMapSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#a64f17d34c6ec33d574438b69fa43c2e2">llvm::StackMaps::serializeToStackMapSection</a>.</p>

</div>
</div>

### getStackSizesSection() {#a65ff3ae888d49df6baad0fb54f3cb8dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * MCObjectFileInfo::getStackSizesSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; TextSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#aba2770972dc030b69d7c4f799eca7441">llvm::MCSectionELF::getGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a3483097b89f7d84944bd0c03f50cff45">llvm::MCSectionELF::getUniqueID</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890ac8172f032ec16640838e35d9e8c78b50">llvm::MCContext::IsELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa4128c7283d8e6e763e8810a91c2dc1e">llvm::ELF::SHF_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a9284ee71917fdddaa2eeaba1bfe17e2b">llvm::ELF::SHF_LINK_ORDER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a> and <a href="#af0bede5b09004d03828616371f3cda92">StackSizesSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a9985b2dd892ea5c7888c199fc8b3b9e7">llvm::AsmPrinter::emitStackSizeSection</a>.</p>

</div>
</div>

### getSupportsCompactUnwindWithoutEHFrame() {#a4aea2b540e0c76cea347723fdcbf9562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCObjectFileInfo::getSupportsCompactUnwindWithoutEHFrame ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#abf79d9f232af620b8db28568ed1ca307">SupportsCompactUnwindWithoutEHFrame</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a>.</p>

</div>
</div>

### getSupportsWeakOmittedEHFrame() {#a3bbe770dc3f895b2d7ceffa945da0866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCObjectFileInfo::getSupportsWeakOmittedEHFrame ()</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ade2d9317005719a662ab8f745300de21">SupportsWeakOmittedEHFrame</a>.</p>

</div>
</div>

### getSwift5ReflectionSection() {#a78f3e7ac9f8cd9666d131a26239f89a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getSwift5ReflectionSection (<a href="/web-llvm/docs/api/namespaces/llvm/binaryformat/#ab355a2b14b4cc35373b4526fbfab894d">llvm::binaryformat::Swift5ReflectionSectionKind</a> ReflSectionKind)</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>References <a href="#a445da24e671664ed5a79d6f034bfb301">Swift5ReflectionSections</a> and <a href="/web-llvm/docs/api/namespaces/llvm/binaryformat/#ab355a2b14b4cc35373b4526fbfab894da80eaeeee65cce2c1b9fa9a5741956f9a">llvm::binaryformat::unknown</a>.</p>

</div>
</div>

### getSXDataSection() {#a4c945f4a60fb9dd0893b1632944dafc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getSXDataSection ()</td>
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



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#aa1439cb6bd26373b56610b4e794fa16a">SXDataSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a296ba2dbfb0e9605f94744804b1612b9">llvm::MCWinCOFFStreamer::emitCOFFSafeSEH</a>.</p>

</div>
</div>

### getTextCoalSection() {#a4ea2d24275e7c37967a519487f5abc4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getTextCoalSection ()</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a7dad3667a653fbc7a08369b1e04e8615">TextCoalSection</a>.</p>

</div>
</div>

### getTextSection() {#af1e49c4350a67d9c442c39ab1dc211eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getTextSection ()</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a293288e990da3ee0cd54c7c340e33030">TextSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ocamlgcprinter-cpp-/ocamlgcmetadataprinter/#ab53bb67e2b02768e2950e8991829e32d">anonymous{OcamlGCPrinter.cpp}::OcamlGCMetadataPrinter::beginAssembly</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetstreamer/#a7be9623f16e861e4e6809dceaf3e0d1f">llvm::SystemZTargetStreamer::emitConstantPools</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a94031e736c9e04044ac7181147a54bf6">llvm::MipsTargetELFStreamer::finish</a>, <a href="/web-llvm/docs/api/classes/anonymous-ocamlgcprinter-cpp-/ocamlgcmetadataprinter/#a6abb5b979094dd3eba1a0375a96e365a">anonymous{OcamlGCPrinter.cpp}::OcamlGCMetadataPrinter::finishAssembly</a>, <a href="#ab6ce753721421b09ebdefeec3e7e993e">getPCSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilegoff/#a8c58f11a5aa16a65fa81203993787033">llvm::TargetLoweringObjectFileGOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getTextSectionAlignment() {#ae7a8978f9a23fedbc9055993cffe31e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::MCObjectFileInfo::getTextSectionAlignment ()</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>

</div>
</div>

### getThreadLocalPointerSection() {#ab444df00c5dc8d4675ffbac693979af6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getThreadLocalPointerSection ()</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a3742c569070bc5ddb323deac4983999b">ThreadLocalPointerSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a9f2d9f34828769634981f82c4977d930">llvm::ARMAsmPrinter::emitEndOfAsmFile</a>.</p>

</div>
</div>

### getTLSBSSSection() {#a01ba33cc58122be1793d339e452a3b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getTLSBSSSection ()</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a048d5afdc5ac12623aaf755293c90c7e">TLSBSSSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>.</p>

</div>
</div>

### getTLSDataSection() {#ad2600e80f9bd6077b91ca4458d51fea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getTLSDataSection ()</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a2ff225c3f7de6dd8cd9162f786493529">TLSDataSection</a>.</p>

</div>
</div>

### getTLSExtraDataSection() {#a89686f5c463cd1bb0c9fd25e9c3f518d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getTLSExtraDataSection ()</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a822ec404e4dbb511a1aaf3c6956a9668">TLSExtraDataSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>.</p>

</div>
</div>

### getTLSThreadInitSection() {#a8d583d9efd88ed3d1f20799fd27b5793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getTLSThreadInitSection ()</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a08f49440c6a3766d411ea0a04e5c8d5d">TLSThreadInitSection</a>.</p>

</div>
</div>

### getTLSTLVSection() {#a3032b320a8e9a7d93c1cfa3576c26f5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getTLSTLVSection ()</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a9452324c3ff87cd16cd6c5bb2db1655f">TLSTLVSection</a>.</p>

</div>
</div>

### getTOCBaseSection() {#acf115ecc361072e6005a4ee102bad260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getTOCBaseSection ()</td>
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



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#ad4c2e727e78c267cd3618ecd1470060a">TOCBaseSection</a>.</p>

</div>
</div>

### getUStringSection() {#af8be1c3795a2c06f2d95df2b2f90fb96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection * llvm::MCObjectFileInfo::getUStringSection ()</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#aa49603bc80739ef76b0ce19237b42586">UStringSection</a>.</p>

</div>
</div>

### getXDataSection() {#acad68702dad1f331b6bd67bf04c2da2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::MCObjectFileInfo::getXDataSection ()</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Reference <a href="#a6d0397231f6e4991d3321ea159794d39">XDataSection</a>.</p>

</div>
</div>

### initMCObjectFileInfo() {#a9ce8843410ce45dd5ca786651889b45b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCObjectFileInfo::initMCObjectFileInfo (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; MCCtx, bool PIC, bool LargeCodeModel=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>


<p>References <a href="#af121f94c2ed06e4970f99a73a9f78b54">CompactUnwindDwarfEHFrameOnly</a>, <a href="#a3ab2dbd6d2ca2b266a45a5bad4d0aefa">CompactUnwindSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab8bb265a153372d87860f6a33d858f3e">llvm::dwarf::DW_EH_PE_absptr</a>, <a href="#afd8dbdf30732f0081eb7bb6eb2ff324e">DwarfAccelNamespaceSection</a>, <a href="#a61798ea59c94476d34859668b4c011f7">DwarfAccelNamesSection</a>, <a href="#a92ec3775abfe9d78ae0c64d4d89162eb">DwarfAccelObjCSection</a>, <a href="#aff31709e6edc54596c52fce35f2936ca">DwarfAccelTypesSection</a>, <a href="#a8a0f562d2bfd7aff542770ffa13aef00">EHFrameSection</a>, <a href="#ad58390471c241fb327a23c69d639e6ce">FDECFIEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890a730e6df3f810384d6d4f7970f1853df6">llvm::MCContext::IsCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890ae21b6548859f1d9bb8f608af6b9be307">llvm::MCContext::IsDXContainer</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890ac8172f032ec16640838e35d9e8c78b50">llvm::MCContext::IsELF</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890aa096d16f497f52e13268f3071a82ca31">llvm::MCContext::IsGOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890a1d8067015bb1e7a65f9ebbe516f79bca">llvm::MCContext::IsMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890a1d78ddf6bf9eb21bee5ac825e378b224">llvm::MCContext::IsSPIRV</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890a4a69ee4b595474eec127121caddd21c5">llvm::MCContext::IsWasm</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#af13dae4c64d48ea988d060a767605890a92573e214aa83c1df78138a2320e9e6f">llvm::MCContext::IsXCOFF</a>, <a href="#a8c0042d8e0a589778e08ec99787b31ff">OmitDwarfIfHaveCompactUnwind</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>, <a href="#abf79d9f232af620b8db28568ed1ca307">SupportsCompactUnwindWithoutEHFrame</a> and <a href="#ade2d9317005719a662ab8f745300de21">SupportsWeakOmittedEHFrame</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/target/#a34b1bcd57f9c18a520b55819365ea9bb">llvm::Target::createMCObjectFileInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a70df8ac2134903deb0ab04be58e840f2">createRISCVMCObjectFileInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a61a9950a12d517382dd40feb73973aea">llvm::TargetLoweringObjectFile::Initialize</a>.</p>

</div>
</div>

### isPositionIndependent() {#a97edf1bb7914cfc9e329b9d2d103e2fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCObjectFileInfo::isPositionIndependent ()</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2793bce814c8f8c6fc2f41d4156a4ebb">llvm::TargetLoweringObjectFileELF::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a17d3b4679a104b0852f1679b817d2070">llvm::MipsTargetELFStreamer::MipsTargetELFStreamer</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#af34b3385ad6d2dc040f431e84cd822eb">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::RISCVAsmParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getDwarfComdatSection() {#a168acdcb7c93355f3220fa7cd378a596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * MCObjectFileInfo::getDwarfComdatSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, uint64_t Hash)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 1061 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>

</div>
</div>

### initCOFFMCObjectFileInfo() {#a64eb15897b9d7af9a016b92b4987dee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCObjectFileInfo::initCOFFMCObjectFileInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>

</div>
</div>

### initDXContainerObjectFileInfo() {#a92cb0276b7f75b78c05d34f9d2e20177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCObjectFileInfo::initDXContainerObjectFileInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 1004 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>

</div>
</div>

### initELFMCObjectFileInfo() {#a5a1f17604a24f702b8ae1ebec13cdebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCObjectFileInfo::initELFMCObjectFileInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, bool Large)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>

</div>
</div>

### initGOFFMCObjectFileInfo() {#afdbfe468ddcbc222f2ce9193b78b05cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCObjectFileInfo::initGOFFMCObjectFileInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>

</div>
</div>

### initMachOMCObjectFileInfo() {#ac2f305b12fede7c66c9aae93e295025c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCObjectFileInfo::initMachOMCObjectFileInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>

</div>
</div>

### initSPIRVMCObjectFileInfo() {#a4170de70ae23dab8b9d845ad4c0b4de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCObjectFileInfo::initSPIRVMCObjectFileInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>

</div>
</div>

### initWasmMCObjectFileInfo() {#acd88923b7a7dc864fffbdc0ae35fc857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCObjectFileInfo::initWasmMCObjectFileInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>

</div>
</div>

### initXCOFFMCObjectFileInfo() {#a653dd68090b96ed353f01978f471f19d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCObjectFileInfo::initXCOFFMCObjectFileInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>, definition at line 888 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ADASection {#a18dd29c8a98853d938003de3728d05ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::ADASection = nullptr</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a33186d2160644f7da1730786dc47d5d4">getADASection</a>.</p>

</div>
</div>

### AddrSigSection {#a31c1b6bc656f0f1909a03e48513c4706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::AddrSigSection = nullptr</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a2f1ff4f0cc25dc5cc546db7ea694e9dd">getAddrSigSection</a>.</p>

</div>
</div>

### BSSSection {#ae1df1d88e9ee995e0fd2a17edeaf3321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::BSSSection = nullptr</td>
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

<p>Section that is default initialized to zero.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a6de12269943e6388af512d8b96cbd9e8">getBSSSection</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#a2c4f64159bcbdb3eaca20c9bbac48f77">llvm::XCoreTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#ab64771f762bdb53411b08c38f9d7b125">llvm::HexagonTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### COFFDebugSymbolsSection {#a3bfb927fafa450f69ddfa0dbe784a47b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::COFFDebugSymbolsSection = nullptr</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ac77dbfa104b3138b7684fe0334348011">getCOFFDebugSymbolsSection</a>.</p>

</div>
</div>

### COFFDebugTypesSection {#a6f5d29c16645e29ce24ad5c328d141db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::COFFDebugTypesSection = nullptr</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ad5f6572e439f23e83446c8b36337f6a1">getCOFFDebugTypesSection</a>.</p>

</div>
</div>

### COFFGlobalTypeHashesSection {#a197216c7d50361ae89fafb0eefd080a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::COFFGlobalTypeHashesSection = nullptr</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#af483c4b79ae094d99c1e24a643f61111">getCOFFGlobalTypeHashesSection</a>.</p>

</div>
</div>

### CompactUnwindDwarfEHFrameOnly {#af121f94c2ed06e4970f99a73a9f78b54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCObjectFileInfo::CompactUnwindDwarfEHFrameOnly = 0</td>
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

<p>Compact unwind encoding indicating that we should emit only an EH frame.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a5eb24afad571f2444e56298ef8c2693f">getCompactUnwindDwarfEHFrameOnly</a> and <a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a>.</p>

</div>
</div>

### CompactUnwindSection {#a3ab2dbd6d2ca2b266a45a5bad4d0aefa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::CompactUnwindSection = nullptr</td>
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

<p>If exception handling is supported by the target and the target can support a compact representation of the CIE and FDE, this is the section to emit them into.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#aff8632a15d42e54c1367a81afc1b6602">getCompactUnwindSection</a> and <a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a>.</p>

</div>
</div>

### ConstDataCoalSection {#a2b515d5a71b1ed09c80f3069011a32b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::ConstDataCoalSection = nullptr</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a7248a5a87e6e340ad0b0f3c77eb17b69">getConstDataCoalSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### ConstDataSection {#af57563b5bee19a31b86e29d6593788dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::ConstDataSection = nullptr</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a67cfba876d87d0a698a534ed2c337452">getConstDataSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a1a8a0d05b259429263ca03b31fe6f67e">llvm::TargetLoweringObjectFileMachO::getSectionForConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### ConstTextCoalSection {#a2ee5c90f18c4adc512313f31665e1428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::ConstTextCoalSection = nullptr</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a3f8a5c332180d7dcf2c7865d7b611a1d">getConstTextCoalSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### CStringSection {#a8c9f99d2a934df382458e6e2d6602f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::CStringSection = nullptr</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ad0ded12f6aff48c98bd0bc9d98d8b77e">getCStringSection</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#a2c4f64159bcbdb3eaca20c9bbac48f77">llvm::XCoreTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### DataBSSSection {#a6dfefb3042725f9ef882ca9fa8147091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DataBSSSection = nullptr</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ae91f8af9e6e309f03754093a2892c3ca">getDataBSSSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### DataCoalSection {#aa0734bed0d8efcf099d0c6e704935552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DataCoalSection = nullptr</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a67fcb9565b45811881bae17102eedcef">getDataCoalSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### DataCommonSection {#ab574ef9cfe2336b78cd8f0d0fb9dc94a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DataCommonSection = nullptr</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#af1bd56da7a380fcec3b80dd3994f50f8">getDataCommonSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### DataRelROSection {#a876733c60b97ed94e37dce47534b4ccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DataRelROSection = nullptr</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a0336b43f021525b0a865076f315df0b4">getDataRelROSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2ace703bfd969dcf5e8c86590226fb26">llvm::TargetLoweringObjectFileELF::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#a2c4f64159bcbdb3eaca20c9bbac48f77">llvm::XCoreTargetObjectFile::Initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### DataSection {#affe937af7bd751518ed18a8d3e34c687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DataSection = nullptr</td>
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

<p>Section directive for standard data.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#afd9ae84447d7be72e18fd897b3f036d2">getDataSection</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetobjectfile/#a93cc7761779e5af20ad82d879fb8cc6f">llvm::NVPTXTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a82527e99a9f145fdad328a91f4675dcf">llvm::TargetLoweringObjectFile::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#a2c4f64159bcbdb3eaca20c9bbac48f77">llvm::XCoreTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afa6dda813be79bdc7753ef52b9b5ec56">llvm::TargetLoweringObjectFileXCOFF::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### DrectveSection {#a8f9d4285bc3df2066994a75326e9a285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DrectveSection = nullptr</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> specific sections.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a78c3233931fda64aa2d37bce0ccc0f19">getDrectveSection</a>.</p>

</div>
</div>

### DwarfAbbrevDWOSection {#a6ea306a126227a6229dede74ba5f78a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfAbbrevDWOSection = nullptr</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ab7b38278009d729724c809dcbc9d5b4f">getDwarfAbbrevDWOSection</a>.</p>

</div>
</div>

### DwarfAbbrevSection {#ac841b4f3e34dd6628f8f40563da2f7e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfAbbrevSection = nullptr</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ac10c6a9d85782db274d19ef8f828d9fc">getDwarfAbbrevSection</a>.</p>

</div>
</div>

### DwarfAccelNamespaceSection {#afd8dbdf30732f0081eb7bb6eb2ff324e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfAccelNamespaceSection = nullptr</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a38d14819d39b592f82540549231ed94e">getDwarfAccelNamespaceSection</a> and <a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a>.</p>

</div>
</div>

### DwarfAccelNamesSection {#a61798ea59c94476d34859668b4c011f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfAccelNamesSection = nullptr</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ab0a98f2924de06f55315c207f3c0eac1">getDwarfAccelNamesSection</a> and <a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a>.</p>

</div>
</div>

### DwarfAccelObjCSection {#a92ec3775abfe9d78ae0c64d4d89162eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfAccelObjCSection = nullptr</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ae1a65d3a4229133502a782ab58741e60">getDwarfAccelObjCSection</a> and <a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a>.</p>

</div>
</div>

### DwarfAccelTypesSection {#aff31709e6edc54596c52fce35f2936ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfAccelTypesSection = nullptr</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a0f1b3ba79882a148045283d71753897a">getDwarfAccelTypesSection</a> and <a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a>.</p>

</div>
</div>

### DwarfAddrSection {#a07a1ced7122e124391e700ce7e7c1198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfAddrSection = nullptr</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a7dd91b8042158479671aa8f357fd5f62">getDwarfAddrSection</a>.</p>

</div>
</div>

### DwarfARangesSection {#a0edfdfa7c2bdda5824ed59211e1a232e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfARangesSection = nullptr</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ae17df2cce5c5b2cb1688d22f2d90820c">getDwarfARangesSection</a>.</p>

</div>
</div>

### DwarfCUIndexSection {#a28b6e8c3916ea763fd485c043646ed9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfCUIndexSection = nullptr</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#adc1a8b3a5ab5c4c460feb4a00dd2a71c">getDwarfCUIndexSection</a>.</p>

</div>
</div>

### DwarfDebugInlineSection {#a6b87eacdc6ee02c54c643fe61882d9fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection* llvm::MCObjectFileInfo::DwarfDebugInlineSection = nullptr</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a9ba4c71757b3cefaeefeb6d440d0ee91">getDwarfDebugInlineSection</a>.</p>

</div>
</div>

### DwarfDebugNamesSection {#a06ebff500a5ac204a25fd3dbdbf4ced5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfDebugNamesSection = nullptr</td>
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

<p>Accelerator table sections.</p>


<p>DwarfDebugNamesSection is the DWARF v5 accelerator table, while DwarfAccelNamesSection, DwarfAccelObjCSection, DwarfAccelNamespaceSection, DwarfAccelTypesSection are pre-DWARF v5 extensions.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a7031b56e11bd03c7a1f7ab2e68d5d095">getDwarfDebugNamesSection</a>.</p>

</div>
</div>

### DwarfFrameSection {#aa0ae390860881e2d88fd47f4fd01169b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfFrameSection = nullptr</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a8357c20a6fa8dd32020a98ed65971587">getDwarfFrameSection</a>.</p>

</div>
</div>

### DwarfGnuPubNamesSection {#af5264a0fefee534777f0c3f6d087b12c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfGnuPubNamesSection = nullptr</td>
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

<p>Section for newer gnu pubnames.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a29cddb4a82114802b9020d33d7e4dbd8">getDwarfGnuPubNamesSection</a>.</p>

</div>
</div>

### DwarfGnuPubTypesSection {#a2539ec9bf21cfa4e6acf91af16d9688e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfGnuPubTypesSection = nullptr</td>
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

<p>Section for newer gnu pubtypes.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a9eaa64fd2b7b36baec3fb81e574b6b8a">getDwarfGnuPubTypesSection</a>.</p>

</div>
</div>

### DwarfInfoDWOSection {#ae1b270bb4b74adb06ca82d1e8c66c8fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfInfoDWOSection = nullptr</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a3d9643e39995d567cfd19465abcfabaf">getDwarfInfoDWOSection</a>.</p>

</div>
</div>

### DwarfInfoSection {#a369f9522689a50e8c8c0fc161a706dc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfInfoSection = nullptr</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a82d739b35c6534d476fc5bf7d2ee57cb">getDwarfInfoSection</a>.</p>

</div>
</div>

### DwarfLineDWOSection {#ac432b773b43055975c7c6d63d3c8882a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfLineDWOSection = nullptr</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a3b7d7a8e94a349e8343c52c9759bceb4">getDwarfLineDWOSection</a>.</p>

</div>
</div>

### DwarfLineSection {#ad1497dee70e29b9ab270c2dd2cbef610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfLineSection = nullptr</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a82d3abaa97d9734f17bdd52cfdf00fb7">getDwarfLineSection</a>.</p>

</div>
</div>

### DwarfLineStrSection {#abdb36daa30c88494aea8d8d9962fcdc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfLineStrSection = nullptr</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a5e2906ef9fe9b6b1bef3e104b1519cd0">getDwarfLineStrSection</a>.</p>

</div>
</div>

### DwarfLocDWOSection {#a1ec34b9a9bb09418b41aa9c4b74c59a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfLocDWOSection = nullptr</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ae0c42bab7cf6d48b020adbec53263a2c">getDwarfLocDWOSection</a>.</p>

</div>
</div>

### DwarfLoclistsDWOSection {#ae1196867114151709d10f1c3b8f853b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfLoclistsDWOSection = nullptr</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a6713cdb4592c3c97a4a90e3b19a241b5">getDwarfLoclistsDWOSection</a>.</p>

</div>
</div>

### DwarfLoclistsSection {#a491fe4497d0cab1747db14931d0326e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfLoclistsSection = nullptr</td>
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

<p>The DWARF v5 locations list section.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a0da64dcd145f4d0e82f845499c055391">getDwarfLoclistsSection</a>.</p>

</div>
</div>

### DwarfLocSection {#a56ba09d000f18b9923498f246ee9fa6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfLocSection = nullptr</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ae7548b994352e41c0a628936d3f75c61">getDwarfLocSection</a>.</p>

</div>
</div>

### DwarfMacinfoDWOSection {#afb97434bcf2f6833e9681db077c25d0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfMacinfoDWOSection = nullptr</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a7512a0f2f3c4476649d5eab18f4888ff">getDwarfMacinfoDWOSection</a>.</p>

</div>
</div>

### DwarfMacinfoSection {#a22b162880199e9302477d958e5eb5553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfMacinfoSection = nullptr</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ae04d121e734cd5ad456233e5d6ebbb3c">getDwarfMacinfoSection</a>.</p>

</div>
</div>

### DwarfMacroDWOSection {#af97d957759ccc048db74a151b6547ed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfMacroDWOSection = nullptr</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#afa6f1092f5467897d43cf376fd5c1886">getDwarfMacroDWOSection</a>.</p>

</div>
</div>

### DwarfMacroSection {#a99ac9d437c2f7de96e7bde0f597cfa86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfMacroSection = nullptr</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a4ba5c0a8e62bf4ce62c2e815808ae159">getDwarfMacroSection</a>.</p>

</div>
</div>

### DwarfPubNamesSection {#a247ce466a1cfde2910d105d83fdd54b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfPubNamesSection = nullptr</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a49eb3fca43b2ceca3ff8c706fae7ddab">getDwarfPubNamesSection</a>.</p>

</div>
</div>

### DwarfPubTypesSection {#a7f66def89abca84ed0ea119213fb1264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfPubTypesSection = nullptr</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a97622da3f5114dfa0bb2f2285bf37cea">getDwarfPubTypesSection</a>.</p>

</div>
</div>

### DwarfRangesSection {#a7f8acdb78b71dc688dfc697068621c13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfRangesSection = nullptr</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a31df4edd580fc4f6e43318cd9c5ed5bc">getDwarfRangesSection</a>.</p>

</div>
</div>

### DwarfRnglistsDWOSection {#aa7b4b5c4ed4d1c176833f8c4359bf1b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfRnglistsDWOSection = nullptr</td>
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

<p>The DWARF v5 range and location list sections for fission.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ab7bd3800ca2a48cd600e03e97c98f059">getDwarfRnglistsDWOSection</a>.</p>

</div>
</div>

### DwarfRnglistsSection {#a680ab2608b8af2a908f4c105b9a9f345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfRnglistsSection = nullptr</td>
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

<p>The DWARF v5 range list section.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a7cddd5b91a2f88c1c204cafeca322517">getDwarfRnglistsSection</a>.</p>

</div>
</div>

### DwarfStrDWOSection {#a403da8c4d9084c878a40126b89af487c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfStrDWOSection = nullptr</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#aa89ba1b4a04c6aab9e36521b0af3212e">getDwarfStrDWOSection</a>.</p>

</div>
</div>

### DwarfStrOffDWOSection {#a81bd47af3ab89763c79fc35b75724a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfStrOffDWOSection = nullptr</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a2be455ebf2215c76244c7d1cc4697492">getDwarfStrOffDWOSection</a>.</p>

</div>
</div>

### DwarfStrOffSection {#a0c8d00998d8d294405be1110ba8aee38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfStrOffSection = nullptr</td>
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

<p>The DWARF v5 string offset and address table sections.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a3d677a1ab07bb4796933369f69396459">getDwarfStrOffSection</a>.</p>

</div>
</div>

### DwarfStrSection {#a127671854883d14ccbeebdc4170152ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfStrSection = nullptr</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a5915c91abcb7f7eb43cae094ec8b4ec7">getDwarfStrSection</a>.</p>

</div>
</div>

### DwarfSwiftASTSection {#a971ce0f63642ba3d7814d4f9da4b1c1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfSwiftASTSection = nullptr</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ac28a6e4a483c4c56f254884ed9024648">getDwarfSwiftASTSection</a>.</p>

</div>
</div>

### DwarfTUIndexSection {#add9231efed560081f768878731eb86d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfTUIndexSection = nullptr</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a6f7b6409e225107d1b3e430471b80c50">getDwarfTUIndexSection</a>.</p>

</div>
</div>

### DwarfTypesDWOSection {#af3cdf6dd6d008e2ee24ea51f46cf4457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::DwarfTypesDWOSection = nullptr</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a47aba8387dcc1520ee5846c047be762d">getDwarfTypesDWOSection</a>.</p>

</div>
</div>

### EHFrameSection {#a8a0f562d2bfd7aff542770ffa13aef00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::EHFrameSection = nullptr</td>
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

<p>EH frame section.</p>


<p>It is initialized on demand so it can be overwritten (with uniquing).</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a31d963341d03839c532b62ef3fd568c2">getEHFrameSection</a> and <a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a>.</p>

</div>
</div>

### EightByteConstantSection {#aee2ea0a72fcfd6b4bf43042285dfd68f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::EightByteConstantSection = nullptr</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a8986417f698b06ed587b13206ebf6cdf">getEightByteConstantSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a1a8a0d05b259429263ca03b31fe6f67e">llvm::TargetLoweringObjectFileMachO::getSectionForConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### FaultMapSection {#a91877751059c85cf922a1972bea85048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::FaultMapSection = nullptr</td>
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

<p>FaultMap section.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a39753c797dc0dce0e2f7f367e4203556">getFaultMapSection</a>.</p>

</div>
</div>

### FDECFIEncoding {#ad58390471c241fb327a23c69d639e6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCObjectFileInfo::FDECFIEncoding = 0</td>
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

<p>FDE CFI encoding.</p>


<p>Controls the encoding of the begin label in the .eh_frame section. Unlike the LSDA encoding, personality encoding, and type encodings, this is something that the assembler just "knows" about its target</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a9b753f5b5ed5d2d28462e83e7c5e923b">getFDEEncoding</a> and <a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a>.</p>

</div>
</div>

### FourByteConstantSection {#a5f2a514a3f7bbc64a0c8c3269698beb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::FourByteConstantSection = nullptr</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#aba452decdc0d6e2ec7c55587cf0e8387">getFourByteConstantSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a1a8a0d05b259429263ca03b31fe6f67e">llvm::TargetLoweringObjectFileMachO::getSectionForConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### GEHContSection {#a09d6ad4c554c3bd763fe58208721d176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::GEHContSection = nullptr</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a3fdc31dfe6ba58f020c623009ea8581e">getGEHContSection</a>.</p>

</div>
</div>

### GFIDsSection {#a3d5eab61a198061779362db437b1c069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::GFIDsSection = nullptr</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a63b8430be4ec071180c26ab9e34c495a">getGFIDsSection</a>.</p>

</div>
</div>

### GIATsSection {#a6e9361c92c8b4dc87ddd79c56c5266ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::GIATsSection = nullptr</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ada5d9fd0747603e74881f463d8d87ae5">getGIATsSection</a>.</p>

</div>
</div>

### GLJMPSection {#af3db2c2f7c00f71cb454e731c42d6a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::GLJMPSection = nullptr</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ace74c8038b708823632d7f3c22e28154">getGLJMPSection</a>.</p>

</div>
</div>

### IDRLSection {#a32faab3bb215ef93964baecd36b5dcd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::IDRLSection = nullptr</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ac2deae42e85e5f97a4f86b2b63062aef">getIDRLSection</a>.</p>

</div>
</div>

### ImportCallSection {#aa98be4b747852c7b11e0d262806f54e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::ImportCallSection = nullptr</td>
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

<p>If import call optimization is supported by the target, this is the section to emit import call data to.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#adc22c43614460f4c34ed60b32c8b2ef3">getImportCallSection</a>.</p>

</div>
</div>

### LazySymbolPointerSection {#a75325c9432bb89f0c90caeef38461552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::LazySymbolPointerSection = nullptr</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a7bce74eda9ad4f8992b959ad6a7e3386">getLazySymbolPointerSection</a>.</p>

</div>
</div>

### LLVMStatsSection {#a2becbbe728f48493dc12477e8d1820bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::LLVMStatsSection = nullptr</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a2829cb48c8fe186a1318a5df7b4e11da">getLLVMStatsSection</a>.</p>

</div>
</div>

### LSDASection {#a3958cbb873bc9ea9f052fd2e467c50d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::LSDASection = nullptr</td>
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

<p>If exception handling is supported by the target, this is the section the Language Specific Data Area information is emitted to.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a94b2a8fa73fa90decda080df0772a13d">getLSDASection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a9d1e530594d9083782754e1770b35d3f">llvm::TargetLoweringObjectFile::getSectionForLSDA</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#ac8b6405ee0ca88cdcd7aea5d129551c4">llvm::TargetLoweringObjectFileELF::getSectionForLSDA</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afff1a14d07c4f0d35848b797930090c6">llvm::TargetLoweringObjectFileXCOFF::getSectionForLSDA</a> and <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#ad60d0495301b78e11523def2cb8b2b59">llvm::ARMElfTargetObjectFile::Initialize</a>.</p>

</div>
</div>

### MergeableConst16Section {#a13afc727a076f284996b88d722fa312b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::MergeableConst16Section = nullptr</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a1a6ce7b3647fc22dc5e8e79dc170aea9">getMergeableConst16Section</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2ace703bfd969dcf5e8c86590226fb26">llvm::TargetLoweringObjectFileELF::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#abb3d2db5017c0d0142f336a103f5ce1e">llvm::XCoreTargetObjectFile::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#a2c4f64159bcbdb3eaca20c9bbac48f77">llvm::XCoreTargetObjectFile::Initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### MergeableConst32Section {#aabf4b5d43d65316f3cfe84f355df064c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::MergeableConst32Section = nullptr</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a1f41a87ecc86ac0049cb84c369ce1188">getMergeableConst32Section</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2ace703bfd969dcf5e8c86590226fb26">llvm::TargetLoweringObjectFileELF::getSectionForConstant</a>.</p>

</div>
</div>

### MergeableConst4Section {#a1f7abaf19f8d77aa383376e7275492bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::MergeableConst4Section = nullptr</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a13d95da0ffa6baee110e7fa2f4c97bed">getMergeableConst4Section</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2ace703bfd969dcf5e8c86590226fb26">llvm::TargetLoweringObjectFileELF::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#abb3d2db5017c0d0142f336a103f5ce1e">llvm::XCoreTargetObjectFile::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#a2c4f64159bcbdb3eaca20c9bbac48f77">llvm::XCoreTargetObjectFile::Initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### MergeableConst8Section {#a30b67c811ff50fad1141f3826d24ebdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::MergeableConst8Section = nullptr</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#aa7af67f26eb452f7afe236b200622839">getMergeableConst8Section</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2ace703bfd969dcf5e8c86590226fb26">llvm::TargetLoweringObjectFileELF::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#abb3d2db5017c0d0142f336a103f5ce1e">llvm::XCoreTargetObjectFile::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#a2c4f64159bcbdb3eaca20c9bbac48f77">llvm::XCoreTargetObjectFile::Initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### NonLazySymbolPointerSection {#a0423ed6a9ff9b2e653a78a4643838f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::NonLazySymbolPointerSection = nullptr</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ae3992a89b8f47181ead24dd08b5e73ac">getNonLazySymbolPointerSection</a>.</p>

</div>
</div>

### OmitDwarfIfHaveCompactUnwind {#a8c0042d8e0a589778e08ec99787b31ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCObjectFileInfo::OmitDwarfIfHaveCompactUnwind = false</td>
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

<p>OmitDwarfIfHaveCompactUnwind - True if the target object file supports having some functions with compact unwind and other with dwarf unwind.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ace2637cdddf7452b83365442e31a5d1c">getOmitDwarfIfHaveCompactUnwind</a> and <a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a>.</p>

</div>
</div>

### PDataSection {#a7b2c08aaf827fbf89b7f265f2234fc5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::PDataSection = nullptr</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a33c221af9ebc8c35c9c0dc601f50c39a">getPDataSection</a>.</p>

</div>
</div>

### PPA1Section {#a667d3420552bec16c0ba1b92b3b08612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::PPA1Section = nullptr</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a9f3e57a0a153a47b66dbea2a68962d8d">getPPA1Section</a>.</p>

</div>
</div>

### PPA2ListSection {#ae5a22e67493472a697d901aec7bb90de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::PPA2ListSection = nullptr</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a913e2c8b44957daa6dfe02d906e8bb09">getPPA2ListSection</a>.</p>

</div>
</div>

### PPA2Section {#ad5de2729a910fb3705878d9110ac7f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::PPA2Section = nullptr</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#afd4544fcbf850d4876416965a6518725">getPPA2Section</a>.</p>

</div>
</div>

### PseudoProbeDescSection {#a7eb8541a5f757a42f35d57ab27bb3d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::PseudoProbeDescSection = nullptr</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a427ea8030e264e1e94ec134806be72a9">getPseudoProbeDescSection</a>.</p>

</div>
</div>

### PseudoProbeSection {#a57fd9c5d628ecc4e5f7d61cba349d51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::PseudoProbeSection = nullptr</td>
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

<p>Section for pseudo probe information used by AutoFDO.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a7cec802e187b8b84478ffe1fa783a2dd">getPseudoProbeSection</a>.</p>

</div>
</div>

### ReadOnly16Section {#a4c403c28c309d3dcee0ddaf70bda29fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::ReadOnly16Section = nullptr</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a81d5951cc0d223b8709e34fdf56152fe">llvm::TargetLoweringObjectFileXCOFF::getSectionForConstant</a>.</p>

</div>
</div>

### ReadOnly8Section {#a6552bb97aa2622ca7c1a18f17f8eda38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::ReadOnly8Section = nullptr</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a81d5951cc0d223b8709e34fdf56152fe">llvm::TargetLoweringObjectFileXCOFF::getSectionForConstant</a>.</p>

</div>
</div>

### ReadOnlySection {#ac01fb290af1907633ce3c08fa92b25e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::ReadOnlySection = nullptr</td>
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

<p>Section that is readonly and can contain arbitrary initialized data.</p>


<p>Targets are not required to have a readonly section. If they don't, various bits of code will fall back to using the data section for constants.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ab14fbbabe5077f89e7d887b3d3d90d0a">getReadOnlySection</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetobjectfile/#a371ab7a5cc3087cd118bcbbd8df0c256">llvm::NVPTXTargetObjectFile::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a82527e99a9f145fdad328a91f4675dcf">llvm::TargetLoweringObjectFile::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2ace703bfd969dcf5e8c86590226fb26">llvm::TargetLoweringObjectFileELF::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a1a8a0d05b259429263ca03b31fe6f67e">llvm::TargetLoweringObjectFileMachO::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a81d5951cc0d223b8709e34fdf56152fe">llvm::TargetLoweringObjectFileXCOFF::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#abb3d2db5017c0d0142f336a103f5ce1e">llvm::XCoreTargetObjectFile::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#ad75e2aa4d67c101594e1f7448588c8d3">llvm::TargetLoweringObjectFileCOFF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a38d2d101b244807c73327e57f705ef7e">llvm::TargetLoweringObjectFileELF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a59f70e2f83b2a97372e18a6c6316550d">llvm::TargetLoweringObjectFileXCOFF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#a2c4f64159bcbdb3eaca20c9bbac48f77">llvm::XCoreTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afa6dda813be79bdc7753ef52b9b5ec56">llvm::TargetLoweringObjectFileXCOFF::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### RemarksSection {#a79f887ebc5b25fdb7faea28be0f11a70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::RemarksSection = nullptr</td>
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

<p>Remarks section.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a706b30b9956c1eb3a09f663d2a09d87d">getRemarksSection</a>.</p>

</div>
</div>

### SixteenByteConstantSection {#aad1f88c540c39eb55ebb9716e9d63495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::SixteenByteConstantSection = nullptr</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a1a8a0d05b259429263ca03b31fe6f67e">llvm::TargetLoweringObjectFileMachO::getSectionForConstant</a>, <a href="#ae4e8241ff6fbcd226417943ac30c1a03">getSixteenByteConstantSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### StackMapSection {#af5a655ddfa1ed583cd1f738cf1bcadee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::StackMapSection = nullptr</td>
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

<p>StackMap section.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#aaded1e857e3e6aa44d76a3a967624818">getStackMapSection</a>.</p>

</div>
</div>

### StackSizesSection {#af0bede5b09004d03828616371f3cda92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::StackSizesSection = nullptr</td>
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

<p>Section containing metadata on function stack sizes.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a65ff3ae888d49df6baad0fb54f3cb8dc">getStackSizesSection</a>.</p>

</div>
</div>

### SupportsCompactUnwindWithoutEHFrame {#abf79d9f232af620b8db28568ed1ca307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCObjectFileInfo::SupportsCompactUnwindWithoutEHFrame = false</td>
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

<p>True if the target object file supports emitting a compact unwind section without an associated EH frame section.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a4aea2b540e0c76cea347723fdcbf9562">getSupportsCompactUnwindWithoutEHFrame</a> and <a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a>.</p>

</div>
</div>

### SupportsWeakOmittedEHFrame {#ade2d9317005719a662ab8f745300de21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCObjectFileInfo::SupportsWeakOmittedEHFrame = false</td>
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

<p>True if target object file supports a weak_definition of constant 0 for an omitted EH frame.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a3bbe770dc3f895b2d7ceffa945da0866">getSupportsWeakOmittedEHFrame</a> and <a href="#a9ce8843410ce45dd5ca786651889b45b">initMCObjectFileInfo</a>.</p>

</div>
</div>

### Swift5ReflectionSections {#a445da24e671664ed5a79d6f034bfb301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;MCSection *, binaryformat::Swift5ReflectionSectionKind::last&gt; llvm::MCObjectFileInfo::Swift5ReflectionSections = {}</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a78f3e7ac9f8cd9666d131a26239f89a8">getSwift5ReflectionSection</a>.</p>

</div>
</div>

### SXDataSection {#aa1439cb6bd26373b56610b4e794fa16a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::SXDataSection = nullptr</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a4c945f4a60fb9dd0893b1632944dafc3">getSXDataSection</a>.</p>

</div>
</div>

### TextCoalSection {#a7dad3667a653fbc7a08369b1e04e8615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::TextCoalSection = nullptr</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a4ea2d24275e7c37967a519487f5abc4b">getTextCoalSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### TextSection {#a293288e990da3ee0cd54c7c340e33030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::TextSection = nullptr</td>
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

<p>Section directive for standard text.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvtargetobjectfile/#a3cd5a6c17845d3130d5ebbfde80c9309">llvm::SPIRVTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetobjectfile/#af607debe185fb379b37e34505dee9210">llvm::SPIRVTargetObjectFile::getSectionForConstant</a>, <a href="#af1e49c4350a67d9c442c39ab1dc211eb">getTextSection</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#ad60d0495301b78e11523def2cb8b2b59">llvm::ARMElfTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetobjectfile/#a09d126e0897329e2e372136ffed9f5c3">llvm::AMDGPUTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetobjectfile/#a65df2e8ed2497f3644937b986801a5e6">llvm::SPIRVTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afa6dda813be79bdc7753ef52b9b5ec56">llvm::TargetLoweringObjectFileXCOFF::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### ThreadLocalPointerSection {#a3742c569070bc5ddb323deac4983999b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::ThreadLocalPointerSection = nullptr</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ab444df00c5dc8d4675ffbac693979af6">getThreadLocalPointerSection</a>.</p>

</div>
</div>

### TLSBSSSection {#a048d5afdc5ac12623aaf755293c90c7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::TLSBSSSection = nullptr</td>
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

<p>Section directive for Thread Local uninitialized data.</p>


<p>Null if this target doesn't support a BSS section. <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> only.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a01ba33cc58122be1793d339e452a3b20">getTLSBSSSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### TLSDataSection {#a2ff225c3f7de6dd8cd9162f786493529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::TLSDataSection = nullptr</td>
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

<p>Section directive for Thread Local data. <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a>, and Wasm.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#ad2600e80f9bd6077b91ca4458d51fea7">getTLSDataSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afa6dda813be79bdc7753ef52b9b5ec56">llvm::TargetLoweringObjectFileXCOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### TLSExtraDataSection {#a822ec404e4dbb511a1aaf3c6956a9668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::TLSExtraDataSection = nullptr</td>
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

<p>Extra TLS Variable Data section.</p>


<p>If the target needs to put additional information for a TLS variable, it'll go here.</p>


<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a89686f5c463cd1bb0c9fd25e9c3f518d">getTLSExtraDataSection</a>.</p>

</div>
</div>

### TLSThreadInitSection {#a08f49440c6a3766d411ea0a04e5c8d5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSection* llvm::MCObjectFileInfo::TLSThreadInitSection = nullptr</td>
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

<p>Section for thread local data initialization functions.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a8d583d9efd88ed3d1f20799fd27b5793">getTLSThreadInitSection</a>.</p>

</div>
</div>

### TLSTLVSection {#a9452324c3ff87cd16cd6c5bb2db1655f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::TLSTLVSection = nullptr</td>
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

<p>Section for thread local structure information.</p>


<p>Contains the source code name of the variable, visibility and a pointer to the initial value (.tdata or .tbss).</p>


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#a3032b320a8e9a7d93c1cfa3576c26f5d">getTLSTLVSection</a>.</p>

</div>
</div>

### TOCBaseSection {#ad4c2e727e78c267cd3618ecd1470060a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::TOCBaseSection = nullptr</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#acf115ecc361072e6005a4ee102bad260">getTOCBaseSection</a>.</p>

</div>
</div>

### UStringSection {#aa49603bc80739ef76b0ce19237b42586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::UStringSection = nullptr</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#af8be1c3795a2c06f2d95df2b2f90fb96">getUStringSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### XDataSection {#a6d0397231f6e4991d3321ea159794d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCObjectFileInfo::XDataSection = nullptr</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>


<p>Referenced by <a href="#acad68702dad1f331b6bd67bf04c2da2d">getXDataSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ctx {#a48af47fd266384691ccc49abbb7a99c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext* llvm::MCObjectFileInfo::Ctx = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>

</div>
</div>

### PositionIndependent {#ae3c445574d033021650fc085d0558856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCObjectFileInfo::PositionIndependent = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">MCObjectFileInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectfileinfo-cpp">MCObjectFileInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
