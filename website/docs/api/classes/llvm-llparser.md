---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/llparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LLParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LLParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">llvm/AsmParser/LLParser.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lllexer/#a8ba87c44f4d51a249fbf317476e120dd">LLLexer::LocTy</a> <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46c5867d668a3d90501974f900f56a13">IdToIndexMapType</a> = std::map&lt; unsigned, std::vector&lt; std::pair&lt; unsigned, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt; &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5485c7c2ab01078824368fba31aace60">IdLocListType</a> = std::vector&lt; std::pair&lt; unsigned, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt; &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TailCallType { <a href="#aa116397fc363f9b4aa49ddb7f56ff83e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InstResult { <a href="#adab10abb8ce4248333d9443f225341bb">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f145595be2ff704a2f264e57cd41c55">LLParser</a> (StringRef F, SourceMgr &amp;SM, SMDiagnostic &amp;Err, Module *M, ModuleSummaryIndex *Index, LLVMContext &amp;Context, SlotMapping *Slots=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeabb9a69009bc6019e909b931db71937">Run</a> (bool UpgradeDebugInfo, DataLayoutCallbackTy DataLayoutCallback=[](StringRef, StringRef) { return std::nullopt;})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run: module ::= toplevelentity*. <a href="#aeabb9a69009bc6019e909b931db71937">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a8518366b4a3c7ae8ffcfa342f7137">parseStandaloneConstantValue</a> (Constant *&amp;C, const SlotMapping *Slots)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a933523072cbd91ce32852b7b52a74d52">parseTypeAtBeginning</a> (Type *&amp;Ty, unsigned &amp;Read, const SlotMapping *Slots)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a854410b123568e0bb9824f0a3cb94c">parseDIExpressionBodyAtBeginning</a> (MDNode *&amp;Result, unsigned &amp;Read, const SlotMapping *Slots)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d0c164bcb08d642a0ab4047f07be8c8">getContext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae731f70b809827b785b51b3e2e24413d">parseMDField</a> (LocTy Loc, StringRef Name, MDAPSIntField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af22c380ad7396a702e8bc0c4a9b837e4">parseMDField</a> (LocTy Loc, StringRef Name, MDUnsignedField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1f7e18ed94e0769ee2de12128c2e2cf">parseMDField</a> (LocTy Loc, StringRef Name, LineField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe7bade8e1ef5dd6e786170633168f90">parseMDField</a> (LocTy Loc, StringRef Name, ColumnField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5ae8011166e33d1f6b5ea8847cb9329">parseMDField</a> (LocTy Loc, StringRef Name, DwarfTagField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089d6dfe66bd827e2bdad201383a5d63">parseMDField</a> (LocTy Loc, StringRef Name, DwarfMacinfoTypeField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b98975ff05abf17080af8cd0278a60e">parseMDField</a> (LocTy Loc, StringRef Name, DwarfVirtualityField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adedf4778a9d218a587c1d18bf9e02474">parseMDField</a> (LocTy Loc, StringRef Name, DwarfLangField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345d7c4db2764f44efd8bf58770928d7">parseMDField</a> (LocTy Loc, StringRef Name, DwarfCCField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46836f2cf5e318baf7539c56130c16ab">parseMDField</a> (LocTy Loc, StringRef Name, EmissionKindField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2375ce5af65ae70e5450c3a7938a26">parseMDField</a> (LocTy Loc, StringRef Name, NameTableKindField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056d8ee2e72bc9d8bc6fc68313378e23">parseMDField</a> (LocTy Loc, StringRef Name, DwarfAttEncodingField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab301262b421c4bacda7d25bf5283ab0e">parseMDField</a> (LocTy Loc, StringRef Name, DIFlagField &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DIFlagField ::= uint32 ::= DIFlagVector ::= DIFlagVector '|' DIFlagFwdDecl '|' uint32 '|' DIFlagPublic. <a href="#ab301262b421c4bacda7d25bf5283ab0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a139caabba1e0e7afddf9b19804483dab">parseMDField</a> (LocTy Loc, StringRef Name, DISPFlagField &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DISPFlagField ::= uint32 ::= DISPFlagVector ::= DISPFlagVector '|' DISPFlag* '|' uint32. <a href="#a139caabba1e0e7afddf9b19804483dab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ca5648a3b5b77172872866f4d17c80">parseMDField</a> (LocTy Loc, StringRef Name, MDSignedField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67695067bd720a3fabfa95588cf43823">parseMDField</a> (LocTy Loc, StringRef Name, MDBoolField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dd00d42b68ddec3d9bde61d3d68b4c3">parseMDField</a> (LocTy Loc, StringRef Name, MDField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acefe52ec8f85d7b71cc97bd5ee550f21">parseMDField</a> (LocTy Loc, StringRef Name, MDSignedOrMDField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48a9cfa41a13b34d64b9dcb824d9075a">parseMDField</a> (LocTy Loc, StringRef Name, MDStringField &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc489c5343ab75b8ae77c119e7a71c53">parseMDField</a> (LocTy Loc, StringRef Name, MDFieldList &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd526ef47b9208261d3dbc3acc67b8d9">parseMDField</a> (LocTy Loc, StringRef Name, ChecksumKindField &amp;Result)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2af960f0818e6272c48799698f3b25dd">error</a> (LocTy L, const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c2408964745a0e8d69b0ae1dcf21cdc">tokError</a> (const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb3fb450509b874395236ce03da905d4">checkValueID</a> (LocTy L, StringRef Kind, StringRef Prefix, unsigned NextID, unsigned ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac681d16991c75c695db1dfde8673eab5">restoreParsingState</a> (const SlotMapping *Slots)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Restore the internal name and slot mappings using the mappings that were created at an earlier parsing stage. <a href="#ac681d16991c75c695db1dfde8673eab5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06465f20c2f8128f18d0fd79da6b1dc9">getGlobalVal</a> (const std::string &amp;N, Type *Ty, LocTy Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getGlobalVal - Get a value with the specified name or <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, creating a forward reference record if needed. <a href="#a06465f20c2f8128f18d0fd79da6b1dc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c42e5acf881bf7bdc62c07f2dce3e3">getGlobalVal</a> (unsigned ID, Type *Ty, LocTy Loc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a989a109e8eadec290aa6b5934bdd2e42">getComdat</a> (const std::string &amp;Name, LocTy Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> with the specified name, creating a forward reference record if needed. <a href="#a989a109e8eadec290aa6b5934bdd2e42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fc2366bbf5022df182be87beee68bd2">parseToken</a> (lltok::Kind T, const char *ErrMsg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseToken - If the current token has the specified kind, eat it and return success. <a href="#a9fc2366bbf5022df182be87beee68bd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adada81c08e8dfed09386b888d7e4161a">EatIfPresent</a> (lltok::Kind T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7b353760e5004218cf01ad4a2fac4c">EatFastMathFlagsIfPresent</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1a6ba4fae0bc5aa93f82c2255192dc3">parseOptionalToken</a> (lltok::Kind T, bool &amp;Present, LocTy *Loc=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594c3663e4725d48154e1f015a4de6f1">parseStringConstant</a> (std::string &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseStringConstant ::= StringConstant <a href="#a594c3663e4725d48154e1f015a4de6f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add7eabd4126cef5e821f839c12498ebb">parseUInt32</a> (unsigned &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab61ea68d95f527d1114e50313271a5c5">parseUInt32</a> (unsigned &amp;Val, LocTy &amp;Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac81c15155a8fc0e67652cde2e42cd0f5">parseUInt64</a> (uint64_t &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseUInt64 ::= uint64 <a href="#ac81c15155a8fc0e67652cde2e42cd0f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c31c25087bdd59def483fe36755cb5d">parseUInt64</a> (uint64_t &amp;Val, LocTy &amp;Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcb7ff211e3247a023f61d9c7f5ff48d">parseFlag</a> (unsigned &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag ::= [0|1]. <a href="#afcb7ff211e3247a023f61d9c7f5ff48d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40feba9fa26c09b5b3fdadda58d602d">parseStringAttribute</a> (AttrBuilder &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseStringAttribute := StringConstant := StringConstant '=' StringConstant <a href="#ad40feba9fa26c09b5b3fdadda58d602d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8938108b39e6a1d29096e332f12bc9b">parseTLSModel</a> (GlobalVariable::ThreadLocalMode &amp;TLM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseTLSModel := 'localdynamic' := 'initialexec' := 'localexec' <a href="#ab8938108b39e6a1d29096e332f12bc9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb325b2c3b2bb51b3fa617de31d1652d">parseOptionalThreadLocal</a> (GlobalVariable::ThreadLocalMode &amp;TLM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalThreadLocal := /*empty*‍/ := 'thread_local' := 'thread_local' '(' tlsmodel ')' <a href="#aeb325b2c3b2bb51b3fa617de31d1652d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bc9c5a6df3a6b4efd4576fb3ecded24">parseOptionalUnnamedAddr</a> (GlobalVariable::UnnamedAddr &amp;UnnamedAddr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13818507aa8a132f667b4173f5b9430e">parseOptionalAddrSpace</a> (unsigned &amp;AddrSpace, unsigned DefaultAS=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalAddrSpace := /*empty*‍/ := 'addrspace' '(' uint32 ')' <a href="#a13818507aa8a132f667b4173f5b9430e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88d5f7952ed1652450e6012366aa9ed">parseOptionalProgramAddrSpace</a> (unsigned &amp;AddrSpace)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d3b5700c0a44cc31b8587c44fc14cb">parseEnumAttribute</a> (Attribute::AttrKind Attr, AttrBuilder &amp;B, bool InAttrGroup)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b55ed6278f19796048f45a116c1d59">parseOptionalParamOrReturnAttrs</a> (AttrBuilder &amp;B, bool IsParam)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a potentially empty list of parameter or return attributes. <a href="#a00b55ed6278f19796048f45a116c1d59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac048bc31e2424d06f7e4a38bf1af5a43">parseOptionalParamAttrs</a> (AttrBuilder &amp;B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9397e0e46b851e37619d63fd0511bca3">parseOptionalReturnAttrs</a> (AttrBuilder &amp;B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9195753d6181fd770002272b0d452e8">parseOptionalLinkage</a> (unsigned &amp;Res, bool &amp;HasLinkage, unsigned &amp;Visibility, unsigned &amp;DLLStorageClass, bool &amp;DSOLocal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalLinkage ::= /*empty*‍/ ::= 'private' ::= 'internal' ::= 'weak' ::= 'weak_odr' ::= 'linkonce' ::= 'linkonce_odr' ::= 'available_externally' ::= 'appending' ::= 'common' ::= 'extern_weak' ::= 'external' <a href="#aa9195753d6181fd770002272b0d452e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af84e1e037e1a1463f4738c407222c069">parseOptionalDSOLocal</a> (bool &amp;DSOLocal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae1efceb106c8f8b54d913a0275a13e2">parseOptionalVisibility</a> (unsigned &amp;Res)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalVisibility ::= /*empty*‍/ ::= 'default' ::= 'hidden' ::= 'protected' <a href="#aae1efceb106c8f8b54d913a0275a13e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ebe877e76e2f684d8dff47881255e7d">parseOptionalImportType</a> (lltok::Kind Kind, GlobalValueSummary::ImportKind &amp;Res)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72fb22953b5dae49af866723c1f95b43">parseOptionalDLLStorageClass</a> (unsigned &amp;Res)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalDLLStorageClass ::= /*empty*‍/ ::= 'dllimport' ::= 'dllexport' <a href="#a72fb22953b5dae49af866723c1f95b43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6824539a00fc41c4154f06e67f3f7dee">parseOptionalCallingConv</a> (unsigned &amp;CC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalCallingConv ::= /*empty*‍/ ::= 'ccc' ::= 'fastcc' ::= 'intel_ocl_bicc' ::= 'coldcc' ::= 'cfguard_checkcc' ::= 'x86_stdcallcc' ::= 'x86_fastcallcc' ::= 'x86_thiscallcc' ::= 'x86_vectorcallcc' ::= 'arm_apcscc' ::= 'arm_aapcscc' ::= 'arm_aapcs_vfpcc' ::= 'aarch64_vector_pcs' ::= 'aarch64_sve_vector_pcs' ::= 'aarch64_sme_preservemost_from_x0' ::= 'aarch64_sme_preservemost_from_x1' ::= 'aarch64_sme_preservemost_from_x2' ::= 'msp430_intrcc' ::= 'avr_intrcc' ::= 'avr_signalcc' ::= 'ptx_kernel' ::= 'ptx_device' ::= 'spir_func' ::= 'spir_kernel' ::= 'x86_64_sysvcc' ::= 'win64cc' ::= 'anyregcc' ::= 'preserve_mostcc' ::= 'preserve_allcc' ::= 'preserve_nonecc' ::= 'ghccc' ::= 'swiftcc' ::= 'swifttailcc' ::= 'x86_intrcc' ::= 'hhvmcc' ::= 'hhvm_ccc' ::= 'cxx_fast_tlscc' ::= 'amdgpu_vs' ::= 'amdgpu_ls' ::= 'amdgpu_hs' ::= 'amdgpu_es' ::= 'amdgpu_gs' ::= 'amdgpu_ps' ::= 'amdgpu_cs' ::= 'amdgpu_cs_chain' ::= 'amdgpu_cs_chain_preserve' ::= 'amdgpu_kernel' ::= 'tailcc' ::= 'm68k_rtdcc' ::= 'graalcc' ::= 'riscv_vector_cc' ::= 'cc' UINT <a href="#a6824539a00fc41c4154f06e67f3f7dee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86135a3f2f890c0994224d127014faa4">parseOptionalAlignment</a> (MaybeAlign &amp;Alignment, bool AllowParens=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalAlignment ::= /* empty *‍/ ::= 'align' 4 <a href="#a86135a3f2f890c0994224d127014faa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9d5a12f809ead1f46c07ecd6b50e9e">parseOptionalCodeModel</a> (CodeModel::Model &amp;model)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalCodeModel ::= /* empty *‍/ ::= 'code_model' "large" <a href="#a4c9d5a12f809ead1f46c07ecd6b50e9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8082f408b5d089d5a85e927d4bf06f28">parseOptionalDerefAttrBytes</a> (lltok::Kind AttrKind, uint64_t &amp;Bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalDerefAttrBytes ::= /* empty *‍/ ::= AttrKind '(' 4 ')' <a href="#a8082f408b5d089d5a85e927d4bf06f28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2e08d591e0d6d9098dd310986aa075c">parseOptionalUWTableKind</a> (UWTableKind &amp;Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6482ed9e8c1e73634dbd530012f3362d">parseAllocKind</a> (AllocFnKind &amp;Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11e09e058f1aae17d91dd8ba033e6cc">parseMemoryAttr</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85d940ace9bdd5bb2d774de2c4804fea">parseNoFPClassAttr</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6262e11e6598a41e5c38efde0656cf36">parseScopeAndOrdering</a> (bool IsAtomic, SyncScope::ID &amp;SSID, AtomicOrdering &amp;Ordering)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseScopeAndOrdering if isAtomic: ::= <a href="/web-llvm/docs/api/namespaces/llvm/syncscope">SyncScope</a>? <a href="#a6262e11e6598a41e5c38efde0656cf36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a421856eb96fb87f3b99018da8d5bdcd8">parseScope</a> (SyncScope::ID &amp;SSID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseScope ::= syncscope("singlethread" | "&lt;target scope&gt;")? <a href="#a421856eb96fb87f3b99018da8d5bdcd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b03d6146b5d411b5878e695ef69e5cf">parseOrdering</a> (AtomicOrdering &amp;Ordering)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOrdering ::= <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> <a href="#a0b03d6146b5d411b5878e695ef69e5cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5749ad1b6ebab8ea58f2ea8300d309f">parseOptionalStackAlignment</a> (unsigned &amp;Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalStackAlignment ::= /* empty *‍/ ::= 'alignstack' '(' 4 ')' <a href="#aa5749ad1b6ebab8ea58f2ea8300d309f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad16d1d4f310a95770a704887634fe645">parseOptionalCommaAlign</a> (MaybeAlign &amp;Alignment, bool &amp;AteExtraComma)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalCommaAlign ::= ::= ',' align 4 <a href="#ad16d1d4f310a95770a704887634fe645">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5df233044a54ed1bb6210aa2ac76481f">parseOptionalCommaAddrSpace</a> (unsigned &amp;AddrSpace, LocTy &amp;Loc, bool &amp;AteExtraComma)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalCommaAddrSpace ::= ::= ',' addrspace(1) <a href="#a5df233044a54ed1bb6210aa2ac76481f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f89d9d12e5712c171ce4c6b2b09e352">parseAllocSizeArguments</a> (unsigned &amp;BaseSizeArg, std::optional&lt; unsigned &gt; &amp;HowManyArg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb5056352d0199cc950ea9010b0e24f">parseVScaleRangeArguments</a> (unsigned &amp;MinValue, unsigned &amp;MaxValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc9406829303f8355fb924e7f5b96f75">parseIndexList</a> (SmallVectorImpl&lt; unsigned &gt; &amp;Indices, bool &amp;AteExtraComma)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseIndexList - This parses the index list for an insert/extractvalue instruction. <a href="#acc9406829303f8355fb924e7f5b96f75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca9350267d2815ba3aaa1a482dfb1def">parseIndexList</a> (SmallVectorImpl&lt; unsigned &gt; &amp;Indices)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ac16debaa45260f4394f672073bcc8">parseTopLevelEntities</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9046e7aed1bdcb48074f18962cf17922">dropUnknownMetadataReferences</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a9a7f6c6652ce5d144a012aa5cc4232">validateEndOfModule</a> (bool UpgradeDebugInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>validateEndOfModule - Do final validity and basic correctness checks at the end of the module. <a href="#a1a9a7f6c6652ce5d144a012aa5cc4232">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa12efff8fcbe6a62bf8014b4f45edae">validateEndOfIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do final validity and basic correctness checks at the end of the index. <a href="#aaa12efff8fcbe6a62bf8014b4f45edae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59d2a9c17c62c4192b4d8e57e8824e4">parseTargetDefinitions</a> (DataLayoutCallbackTy DataLayoutCallback)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0575c40c069e2478a12221e026a0b99b">parseTargetDefinition</a> (std::string &amp;TentativeDLStr, LocTy &amp;DLStrLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>toplevelentity ::= 'target' 'triple' '=' STRINGCONSTANT ::= 'target' 'datalayout' '=' STRINGCONSTANT <a href="#a0575c40c069e2478a12221e026a0b99b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac170d9a7f149548b061e3714fd4f154e">parseModuleAsm</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>toplevelentity ::= 'module' 'asm' STRINGCONSTANT <a href="#ac170d9a7f149548b061e3714fd4f154e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7da87993ec1871ce635b03493a3b9be">parseSourceFileName</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>toplevelentity ::= 'source_filename' '=' STRINGCONSTANT <a href="#aa7da87993ec1871ce635b03493a3b9be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f37aa2b76fdb514203aa50fab09fa27">parseUnnamedType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseUnnamedType: ::= LocalVarID '=' 'type' type <a href="#a0f37aa2b76fdb514203aa50fab09fa27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6389dfd5cb1cffee60a99966d126734e">parseNamedType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>toplevelentity ::= LocalVar '=' 'type' type <a href="#a6389dfd5cb1cffee60a99966d126734e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4c2c18fd74080f22d7d6f7305c503b4">parseDeclare</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>toplevelentity ::= 'declare' FunctionHeader <a href="#ab4c2c18fd74080f22d7d6f7305c503b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d954d20c0cf4b966579bffbedcf72ad">parseDefine</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>toplevelentity ::= 'define' FunctionHeader (!dbg !56)* '{' ... <a href="#a0d954d20c0cf4b966579bffbedcf72ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af723973e40edaa112204cc289a96bb90">parseGlobalType</a> (bool &amp;IsConstant)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseGlobalType ::= 'constant' ::= 'global' <a href="#af723973e40edaa112204cc289a96bb90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1567b67aa20b64c63d925dc3a0dc02d6">parseUnnamedGlobal</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseUnnamedGlobal: OptionalVisibility (ALIAS | IFUNC) ... OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass ... -&gt; global variable GlobalID '=' OptionalVisibility (ALIAS | IFUNC) ... GlobalID '=' OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass ... -&gt; global variable <a href="#a1567b67aa20b64c63d925dc3a0dc02d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0016f60d16340a5abc2cafc7f8e0df1a">parseNamedGlobal</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseNamedGlobal: GlobalVar '=' OptionalVisibility (ALIAS | IFUNC) ... GlobalVar '=' OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass ... -&gt; global variable <a href="#a0016f60d16340a5abc2cafc7f8e0df1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cd67cba6b2bd0c2df8bee3ff2d5aadc">parseGlobal</a> (const std::string &amp;Name, unsigned NameID, LocTy NameLoc, unsigned Linkage, bool HasLinkage, unsigned Visibility, unsigned DLLStorageClass, bool DSOLocal, GlobalVariable::ThreadLocalMode TLM, GlobalVariable::UnnamedAddr UnnamedAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseGlobal ::= GlobalVar '=' OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass OptionalThreadLocal OptionalUnnamedAddr OptionalAddrSpace OptionalExternallyInitialized GlobalType <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Const OptionalAttrs ::= OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass OptionalThreadLocal OptionalUnnamedAddr OptionalAddrSpace OptionalExternallyInitialized GlobalType <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Const OptionalAttrs <a href="#a4cd67cba6b2bd0c2df8bee3ff2d5aadc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a8f742d10fbe56e056c536c4426537">parseAliasOrIFunc</a> (const std::string &amp;Name, unsigned NameID, LocTy NameLoc, unsigned L, unsigned Visibility, unsigned DLLStorageClass, bool DSOLocal, GlobalVariable::ThreadLocalMode TLM, GlobalVariable::UnnamedAddr UnnamedAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseAliasOrIFunc: ::= GlobalVar '=' OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass OptionalThreadLocal OptionalUnnamedAddr 'alias|ifunc' AliaseeOrResolver SymbolAttrs* <a href="#ac4a8f742d10fbe56e056c536c4426537">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27fff091ba3e53d9316f738a6b0fc01e">parseComdat</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ae6d5e1593954e460e54f243e4d85e">parseStandaloneMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseStandaloneMetadata: !42 = ! <a href="#a70ae6d5e1593954e460e54f243e4d85e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacfb785cbfd2bc80310b8276309d892b">parseNamedMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseNamedMetadata: !foo = ! <a href="#aacfb785cbfd2bc80310b8276309d892b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef1b894f508200664bd2793bfdb0c4e0">parseMDString</a> (MDString *&amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46c8a47a98715a4c5aa39e83544b6612">parseMDNodeID</a> (MDNode *&amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1245ec308f8107c3a0c94b2e42cd96e7">parseUnnamedAttrGrp</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseUnnamedAttrGrp ::= 'attributes' AttrGrpID '=' '{' AttrValPair+ '}' <a href="#a1245ec308f8107c3a0c94b2e42cd96e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea4507592a437656b40404b7c3ee03cd">parseFnAttributeValuePairs</a> (AttrBuilder &amp;B, std::vector&lt; unsigned &gt; &amp;FwdRefAttrGrps, bool inAttrGrp, LocTy &amp;BuiltinLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseFnAttributeValuePairs ::= &lt;attr&gt; | &lt;attr&gt; '=' <a href="#aea4507592a437656b40404b7c3ee03cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0d45d3a5ca287f2101fd8c73e3caa4">parseRangeAttr</a> (AttrBuilder &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseRangeAttr ::= range(&lt;ty&gt; &lt;n&gt;,&lt;n&gt;) <a href="#a0e0d45d3a5ca287f2101fd8c73e3caa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94bc5025f53ae140673c30f805f0c457">parseInitializesAttr</a> (AttrBuilder &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseInitializesAttr ::= initializes((Lo1,Hi1),(Lo2,Hi2),...) <a href="#a94bc5025f53ae140673c30f805f0c457">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54318a610458bc7ab4fed1f2660d70c6">parseCapturesAttr</a> (AttrBuilder &amp;B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3df96c16b7d2a71aa037e3c60fb2b1">parseRequiredTypeAttr</a> (AttrBuilder &amp;B, lltok::Kind AttrToken, Attribute::AttrKind AttrKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseRequiredTypeAttr ::= attrname(&lt;ty&gt;) <a href="#a1e3df96c16b7d2a71aa037e3c60fb2b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfe33e52aa5775f62aba99b44372ecb3">skipModuleSummaryEntry</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d07be785e547c4910068648a9afbefe">parseSummaryEntry</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SummaryEntry ::= SummaryID '=' GVEntry | ModuleEntry | TypeIdEntry. <a href="#a2d07be785e547c4910068648a9afbefe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89b03c1898bd42cfab2cd7d4837bf8bb">parseModuleEntry</a> (unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ModuleEntry ::= 'module' ':' '(' 'path' ':' STRINGCONSTANT ',' 'hash' ':' Hash ')' Hash ::= '(' UInt32 ',' UInt32 ',' UInt32 ',' UInt32 ',' UInt32 ')'. <a href="#a89b03c1898bd42cfab2cd7d4837bf8bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cdb5dc9b80fe804a0673303b1d37be1">parseModuleReference</a> (StringRef &amp;ModulePath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ModuleReference ::= 'module' ':' UInt. <a href="#a5cdb5dc9b80fe804a0673303b1d37be1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af104cd0446948799afb3ce6b08f416fe">parseGVReference</a> (ValueInfo &amp;VI, unsigned &amp;GVId)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GVReference ::= SummaryID. <a href="#af104cd0446948799afb3ce6b08f416fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a493da8131f6eb3837c7ea7ed12db9d17">parseSummaryIndexFlags</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseSummaryIndexFlags ::= 'flags' ':' UInt64 <a href="#a493da8131f6eb3837c7ea7ed12db9d17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a189a32ad9efb64a7e2526f3d4c6e72c1">parseBlockCount</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseBlockCount ::= 'blockcount' ':' UInt64 <a href="#a189a32ad9efb64a7e2526f3d4c6e72c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eca6ad4c688af18d352aa8660566440">parseGVEntry</a> (unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseGVEntry ::= 'gv' ':' '(' ('name' ':' STRINGCONSTANT | 'guid' ':' UInt64) [',' 'summaries' ':' Summary[',' Summary]* ]? <a href="#a3eca6ad4c688af18d352aa8660566440">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ef8cbea99e8515e98a40c73369906a6">parseFunctionSummary</a> (std::string Name, GlobalValue::GUID, unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> ::= 'function' ':' '(' 'module' ':' ModuleReference ',' GVFlags ',' 'insts' ':' UInt32 [',' OptionalFFlags]? <a href="#a2ef8cbea99e8515e98a40c73369906a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fa884a8360986aa8e9154ab45daecec">parseVariableSummary</a> (std::string Name, GlobalValue::GUID, unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VariableSummary ::= 'variable' ':' '(' 'module' ':' ModuleReference ',' GVFlags [',' OptionalRefs]? <a href="#a2fa884a8360986aa8e9154ab45daecec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286da85df0ce8a8ae5a4312a163da57c">parseAliasSummary</a> (std::string Name, GlobalValue::GUID, unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/aliassummary">AliasSummary</a> ::= 'alias' ':' '(' 'module' ':' ModuleReference ',' GVFlags ',' 'aliasee' ':' GVReference ')'. <a href="#a286da85df0ce8a8ae5a4312a163da57c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3d2f31e08b01f661372a0bafebd61d8">parseGVFlags</a> (GlobalValueSummary::GVFlags &amp;GVFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GVFlags ::= 'flags' ':' '(' 'linkage' ':' OptionalLinkageAux ',' 'visibility' ':' Flag 'notEligibleToImport' ':' Flag ',' 'live' ':' Flag ',' 'dsoLocal' ':' Flag ',' 'canAutoHide' ':' Flag ',' ')'. <a href="#ac3d2f31e08b01f661372a0bafebd61d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5c23be5f0905d10fc55e81ae36c0baf">parseGVarFlags</a> (GlobalVarSummary::GVarFlags &amp;GVarFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GVarFlags ::= 'varFlags' ':' '(' 'readonly' ':' Flag ',' 'writeonly' ':' Flag ',' 'constant' ':' Flag ')'. <a href="#ac5c23be5f0905d10fc55e81ae36c0baf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb682244968b9862d11eea8b12ac070">parseOptionalFFlags</a> (FunctionSummary::FFlags &amp;FFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptionalFFlags := 'funcFlags' ':' '(' ['readNone' ':' Flag]? <a href="#a7eb682244968b9862d11eea8b12ac070">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf8012e1403fbd7f97bb66b9b286d093">parseOptionalCalls</a> (SmallVectorImpl&lt; FunctionSummary::EdgeTy &gt; &amp;Calls)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptionalCalls := 'calls' ':' '(' Call [',' Call]* ')' Call ::= '(' 'callee' ':' GVReference [( ',' 'hotness' ':' Hotness | ',' 'relbf' ':' UInt32 )]? <a href="#aaf8012e1403fbd7f97bb66b9b286d093">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69852d83ae5ad725687f3f0393456c75">parseHotness</a> (CalleeInfo::HotnessType &amp;Hotness)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hotness := ('unknown'|'cold'|'none'|'hot'|'critical') <a href="#a69852d83ae5ad725687f3f0393456c75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd85eb3c2000dc7e9b3eb90b8b60d2a5">parseOptionalTypeIdInfo</a> (FunctionSummary::TypeIdInfo &amp;TypeIdInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptionalTypeIdInfo := 'typeidinfo' ':' '(' [',' TypeTests]? <a href="#acd85eb3c2000dc7e9b3eb90b8b60d2a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedecc61c15e359c60fd92af7dba3379f">parseTypeTests</a> (std::vector&lt; GlobalValue::GUID &gt; &amp;TypeTests)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TypeTests ::= 'typeTests' ':' '(' (SummaryID | UInt64) [',' (SummaryID | UInt64)]* ')'. <a href="#aedecc61c15e359c60fd92af7dba3379f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e8507d3c21b9b5d132b257240449b1">parseVFuncIdList</a> (lltok::Kind Kind, std::vector&lt; FunctionSummary::VFuncId &gt; &amp;VFuncIdList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VFuncIdList ::= Kind ':' '(' VFuncId [',' VFuncId]* ')'. <a href="#a27e8507d3c21b9b5d132b257240449b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9115f747af80d51ab61111530276fa66">parseConstVCallList</a> (lltok::Kind Kind, std::vector&lt; FunctionSummary::ConstVCall &gt; &amp;ConstVCallList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ConstVCallList ::= Kind ':' '(' ConstVCall [',' ConstVCall]* ')'. <a href="#a9115f747af80d51ab61111530276fa66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07aee1d4ebf71d83d497616fd2a40e2">parseConstVCall</a> (FunctionSummary::ConstVCall &amp;ConstVCall, IdToIndexMapType &amp;IdToIndexMap, unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ConstVCall ::= '(' VFuncId ',' Args ')'. <a href="#ad07aee1d4ebf71d83d497616fd2a40e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3a92f8adf43b6ee6a2fe415ca8ca74">parseVFuncId</a> (FunctionSummary::VFuncId &amp;VFuncId, IdToIndexMapType &amp;IdToIndexMap, unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VFuncId ::= 'vFuncId' ':' '(' (SummaryID | 'guid' ':' UInt64) ',' 'offset' ':' UInt64 ')'. <a href="#a6e3a92f8adf43b6ee6a2fe415ca8ca74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec55ececd9c99090fe3afc9ef191433f">parseOptionalVTableFuncs</a> (VTableFuncList &amp;VTableFuncs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptionalVTableFuncs := 'vTableFuncs' ':' '(' VTableFunc [',' VTableFunc]* ')' VTableFunc ::= '(' 'virtFunc' ':' GVReference ',' 'offset' ':' UInt64 ')'. <a href="#aec55ececd9c99090fe3afc9ef191433f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45797abac6f6bf347c64012834303f2a">parseOptionalParamAccesses</a> (std::vector&lt; FunctionSummary::ParamAccess &gt; &amp;Params)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptionalParamAccesses := 'params' ':' '(' ParamAccess [',' ParamAccess]* ')'. <a href="#a45797abac6f6bf347c64012834303f2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d55b42b03286ed821cf1b1b72022244">parseParamNo</a> (uint64_t &amp;ParamNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParamNo := 'param' ':' UInt64. <a href="#a8d55b42b03286ed821cf1b1b72022244">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d221b29a04a3db04d8581da4dcf22a">parseParamAccess</a> (FunctionSummary::ParamAccess &amp;Param, IdLocListType &amp;IdLocList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParamAccess := '(' ParamNo ',' ParamAccessOffset [',' OptionalParamAccessCalls]? <a href="#ab7d221b29a04a3db04d8581da4dcf22a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5de913ec69c73e9690b8d75ec8fa955">parseParamAccessCall</a> (FunctionSummary::ParamAccess::Call &amp;Call, IdLocListType &amp;IdLocList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParamAccessCall := '(' 'callee' ':' GVReference ',' ParamNo ',' ParamAccessOffset ')'. <a href="#ac5de913ec69c73e9690b8d75ec8fa955">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9484b79c7f6c694dfc283c6da258bd6a">parseParamAccessOffset</a> (ConstantRange &amp;Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParamAccessOffset := 'offset' ':' '[' APSINTVAL ',' APSINTVAL ']'. <a href="#a9484b79c7f6c694dfc283c6da258bd6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21b808b58d34e7de8692eae6429e73eb">parseOptionalRefs</a> (SmallVectorImpl&lt; ValueInfo &gt; &amp;Refs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptionalRefs := 'refs' ':' '(' GVReference [',' GVReference]* ')'. <a href="#a21b808b58d34e7de8692eae6429e73eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83c7cab447e724997d0b88bba9cb266f">parseTypeIdEntry</a> (unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TypeIdEntry ::= 'typeid' ':' '(' 'name' ':' STRINGCONSTANT ',' <a href="/web-llvm/docs/api/structs/llvm/typeidsummary">TypeIdSummary</a> ')'. <a href="#a83c7cab447e724997d0b88bba9cb266f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c8d32ab262d41b7d3e5849eb856dcb4">parseTypeIdSummary</a> (TypeIdSummary &amp;TIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/typeidsummary">TypeIdSummary</a> ::= 'summary' ':' '(' <a href="/web-llvm/docs/api/structs/llvm/typetestresolution">TypeTestResolution</a> [',' OptionalWpdResolutions]? <a href="#a2c8d32ab262d41b7d3e5849eb856dcb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1bebee585d201a7f0f0675fb0db78c">parseTypeIdCompatibleVtableEntry</a> (unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TypeIdCompatibleVtableEntry ::= 'typeidCompatibleVTable' ':' '(' 'name' ':' STRINGCONSTANT ',' <a href="/web-llvm/docs/api/namespaces/llvm/#ada2485ca228b028f8639ad86ce41d6ec">TypeIdCompatibleVtableInfo</a> ')'. <a href="#aca1bebee585d201a7f0f0675fb0db78c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb217a088f5ccbea19007567c87787d">parseTypeTestResolution</a> (TypeTestResolution &amp;TTRes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/typetestresolution">TypeTestResolution</a> ::= 'typeTestRes' ':' '(' 'kind' ':' ( 'unsat' | 'byteArray' | 'inline' | 'single' | 'allOnes' ) ',' 'sizeM1BitWidth' ':' SizeM1BitWidth [',' 'alignLog2' ':' UInt64]? <a href="#aefb217a088f5ccbea19007567c87787d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb1451e2f64d69058edcec383707ccb9">parseOptionalWpdResolutions</a> (std::map&lt; uint64_t, WholeProgramDevirtResolution &gt; &amp;WPDResMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptionalWpdResolutions ::= 'wpsResolutions' ':' '(' WpdResolution [',' WpdResolution]* ')' WpdResolution ::= '(' 'offset' ':' UInt64 ',' WpdRes ')'. <a href="#acb1451e2f64d69058edcec383707ccb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca0789c7710ebd17d1595669cccfcbbd">parseWpdRes</a> (WholeProgramDevirtResolution &amp;WPDRes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WpdRes ::= 'wpdRes' ':' '(' 'kind' ':' 'indir' [',' OptionalResByArg]? <a href="#aca0789c7710ebd17d1595669cccfcbbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a240f5e03c41d358e4f7d29e33463c14a">parseOptionalResByArg</a> (std::map&lt; std::vector&lt; uint64_t &gt;, WholeProgramDevirtResolution::ByArg &gt; &amp;ResByArg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptionalResByArg ::= 'wpdRes' ':' '(' ResByArg[, ResByArg]* ')' ResByArg ::= Args ',' 'byArg' ':' '(' 'kind' ':' ( 'indir' | 'uniformRetVal' | 'UniqueRetVal' | 'virtualConstProp' ) [',' 'info' ':' UInt64]? <a href="#a240f5e03c41d358e4f7d29e33463c14a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223a5869d6caa835319bcf91aa38e90a">parseArgs</a> (std::vector&lt; uint64_t &gt; &amp;Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptionalResByArg ::= 'args' ':' '(' UInt64[, UInt64]* ')'. <a href="#a223a5869d6caa835319bcf91aa38e90a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed05964eda5c0764df24848d3f4e6255">addGlobalValueToIndex</a> (std::string Name, GlobalValue::GUID, GlobalValue::LinkageTypes Linkage, unsigned ID, std::unique_ptr&lt; GlobalValueSummary &gt; Summary, LocTy Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores the given Name/GUID and associated summary into the Index. <a href="#aed05964eda5c0764df24848d3f4e6255">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa7818545366d11975abb143cd83a0fe">parseOptionalAllocs</a> (std::vector&lt; AllocInfo &gt; &amp;Allocs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptionalAllocs := 'allocs' ':' '(' Alloc [',' Alloc]* ')' Alloc ::= '(' 'versions' ':' '(' Version [',' Version]* ')' ',' MemProfs ')' Version ::= UInt32. <a href="#afa7818545366d11975abb143cd83a0fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44ed818bd973c80ac89a247d76ba613d">parseMemProfs</a> (std::vector&lt; MIBInfo &gt; &amp;MIBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MemProfs := 'memProf' ':' '(' MemProf [',' MemProf]* ')' MemProf ::= '(' 'type' ':' <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#abb725d65acc814edc5c025fb8ee6d55b">AllocType</a> ',' 'stackIds' ':' '(' StackId [',' StackId]* ')' ')' StackId ::= UInt64. <a href="#a44ed818bd973c80ac89a247d76ba613d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d0cdca819f2ece3a84e580f566bcf42">parseAllocType</a> (uint8_t &amp;AllocType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#abb725d65acc814edc5c025fb8ee6d55b">AllocType</a> := ('none'|'notcold'|'cold'|'hot') <a href="#a3d0cdca819f2ece3a84e580f566bcf42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcc728d4910b8718d92cbf443d337d48">parseOptionalCallsites</a> (std::vector&lt; CallsiteInfo &gt; &amp;Callsites)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptionalCallsites := 'callsites' ':' '(' Callsite [',' Callsite]* ')' Callsite ::= '(' 'callee' ':' GVReference ',' 'clones' ':' '(' Version [',' Version]* ')' ',' 'stackIds' ':' '(' StackId [',' StackId]* ')' ')' Version ::= UInt32 StackId ::= UInt64. <a href="#abcc728d4910b8718d92cbf443d337d48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a635a905f19a3fe6523c18010b628e4b7">parseType</a> (Type *&amp;Result, const Twine &amp;Msg, bool AllowVoid=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseType - parse a type. <a href="#a635a905f19a3fe6523c18010b628e4b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a058e99fcfdb85b6b689be1138a04c997">parseType</a> (Type *&amp;Result, bool AllowVoid=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b8c2e72294b6f84b4dea953f38044f3">parseType</a> (Type *&amp;Result, const Twine &amp;Msg, LocTy &amp;Loc, bool AllowVoid=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab9c6459cde961aabaf3f27e55eca850">parseType</a> (Type *&amp;Result, LocTy &amp;Loc, bool AllowVoid=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa668cc36d37d5dbff0d3d2031eccb06b">parseAnonStructType</a> (Type *&amp;Result, bool Packed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseAnonStructType - parse an anonymous struct type, which is inlined into other structs. <a href="#aa668cc36d37d5dbff0d3d2031eccb06b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4542a952dd0ef632d997e724611176a">parseStructBody</a> (SmallVectorImpl&lt; Type * &gt; &amp;Body)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseStructType: Handles packed and unpacked types. <a href="#ad4542a952dd0ef632d997e724611176a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38b6370117609a323a5b5e1ccad8f13d">parseStructDefinition</a> (SMLoc TypeLoc, StringRef Name, std::pair&lt; Type *, LocTy &gt; &amp;Entry, Type *&amp;ResultTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseStructDefinition - parse a struct in a 'type' definition. <a href="#a38b6370117609a323a5b5e1ccad8f13d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d01f9eba8017e6a965960f055a96f32">parseArrayVectorType</a> (Type *&amp;Result, bool IsVector)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseArrayVectorType - parse an array or vector type, assuming the first token has already been consumed. <a href="#a9d01f9eba8017e6a965960f055a96f32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17785ceaa8026ee170df5c094af99b75">parseFunctionType</a> (Type *&amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseFunctionType ::= <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ArgumentList OptionalAttrs <a href="#a17785ceaa8026ee170df5c094af99b75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a68ea85d96605d2bdfe0bea06f80663">parseTargetExtType</a> (Type *&amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseTargetExtType - handle target extension type syntax <a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> ::= 'target' '(' STRINGCONSTANT TargetExtTypeParams TargetExtIntParams ')' <a href="#a7a68ea85d96605d2bdfe0bea06f80663">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50a38b5a4f35538bc62685b6fa469e81">convertValIDToValue</a> (Type *Ty, ValID &amp;ID, Value *&amp;V, PerFunctionState *PFS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5544a5f99ec01602cc0cec68e28c02d">checkValidVariableType</a> (LocTy Loc, const Twine &amp;Name, Type *Ty, Value *Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad202e64f2e8706d17d818f6a2eaa96">parseConstantValue</a> (Type *Ty, Constant *&amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4c69e44ead55a0425881c29d8c94cd">parseValue</a> (Type *Ty, Value *&amp;V, PerFunctionState *PFS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12c0505850061d14ec85d47325ee7fd8">parseValue</a> (Type *Ty, Value *&amp;V, PerFunctionState &amp;PFS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ddc82b85dad9cb50e5ac714d6532b2">parseValue</a> (Type *Ty, Value *&amp;V, LocTy &amp;Loc, PerFunctionState &amp;PFS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99627eba593f579978c9671b0ba8e95c">parseTypeAndValue</a> (Value *&amp;V, PerFunctionState *PFS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15567575c038137f98f7360f1f2ba3c1">parseTypeAndValue</a> (Value *&amp;V, PerFunctionState &amp;PFS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5af80f85ac9b6be1a6e27cb2d252a856">parseTypeAndValue</a> (Value *&amp;V, LocTy &amp;Loc, PerFunctionState &amp;PFS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae84a5753dac0a5f9523532c388499bfb">parseTypeAndBasicBlock</a> (BasicBlock *&amp;BB, LocTy &amp;Loc, PerFunctionState &amp;PFS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ddd7621152818c1abe9e8b2bcf4815a">parseTypeAndBasicBlock</a> (BasicBlock *&amp;BB, PerFunctionState &amp;PFS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f945f21880094ae719be6f19d6ef8a8">parseParameterList</a> (SmallVectorImpl&lt; ParamInfo &gt; &amp;ArgList, PerFunctionState &amp;PFS, bool IsMustTailCall=false, bool InVarArgsFunc=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseParameterList ::= '(' ')' ::= '(' Arg (',' Arg)* ')' Arg ::= <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> OptionalAttributes <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> OptionalAttributes <a href="#a9f945f21880094ae719be6f19d6ef8a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4ae60d13572b8c5bfbbd41e24b6274">parseOptionalOperandBundles</a> (SmallVectorImpl&lt; OperandBundleDef &gt; &amp;BundleList, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalOperandBundles ::= /*empty*‍/ ::= '[' OperandBundle [, OperandBundle ]* ']' <a href="#a9f4ae60d13572b8c5bfbbd41e24b6274">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01fb701860a15fdd9c5da3bfde4aa41a">parseExceptionArgs</a> (SmallVectorImpl&lt; Value * &gt; &amp;Args, PerFunctionState &amp;PFS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2fccd59dd394590c6d5cab6c18b75d">resolveFunctionType</a> (Type *RetType, ArrayRef&lt; ParamInfo &gt; ArgList, FunctionType *&amp;FuncTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dd5c44bbb0785ee35a7bc7298c5cd44">parseValID</a> (ValID &amp;ID, PerFunctionState *PFS, Type *ExpectedTy=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseValID - parse an abstract value that doesn't necessarily have a type implied. <a href="#a6dd5c44bbb0785ee35a7bc7298c5cd44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a759af821267048054a2fcebca0aa08">parseGlobalValue</a> (Type *Ty, Constant *&amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseGlobalValue - parse a global value with the specified type. <a href="#a1a759af821267048054a2fcebca0aa08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7fef328a172bcb0d17db68b3f3eef15">parseGlobalTypeAndValue</a> (Constant *&amp;V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a9eaffb3813182e5eb5a6d0416e37c8">parseGlobalValueVector</a> (SmallVectorImpl&lt; Constant * &gt; &amp;Elts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseGlobalValueVector ::= /*empty*‍/ ::= TypeAndValue (',' TypeAndValue)* <a href="#a8a9eaffb3813182e5eb5a6d0416e37c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17b814efa41d979551dda7a033810bc">parseOptionalComdat</a> (StringRef GlobalName, Comdat *&amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80653d46b51ef51f9f6193bdbcef5261">parseSanitizer</a> (GlobalVariable *GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41efbecade521b8e9120156c8a6a39d4">parseMetadataAsValue</a> (Value *&amp;V, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseMetadataAsValue ::= metadata i32 local ::= metadata i32 @global ::= metadata i32 7 ::= metadata !0 ::= metadata ! <a href="#a41efbecade521b8e9120156c8a6a39d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08240794a713e167dd0e7f74348f0b8a">parseValueAsMetadata</a> (Metadata *&amp;MD, const Twine &amp;TypeMsg, PerFunctionState *PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseValueAsMetadata ::= i32 local ::= i32 @global ::= i32 7 <a href="#a08240794a713e167dd0e7f74348f0b8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac59f050e6aeae5c5932793f551a843ea">parseDIArgList</a> (Metadata *&amp;MD, PerFunctionState *PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDIArgList: ::= !DIArgList(i32 7, i64 %0) <a href="#ac59f050e6aeae5c5932793f551a843ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bdd0eecede328c52d4104ea8fb2e640">parseMetadata</a> (Metadata *&amp;MD, PerFunctionState *PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseMetadata ::= i32 local ::= i32 @global ::= i32 7 ::= !42 ::= ! <a href="#a9bdd0eecede328c52d4104ea8fb2e640">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af022032dbd55f5c0b340b50ec132ec86">parseMDTuple</a> (MDNode *&amp;MD, bool IsDistinct=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2287d84b332961a15cf7e79e3bff855">parseMDNode</a> (MDNode *&amp;N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a>: ::= ! <a href="#ab2287d84b332961a15cf7e79e3bff855">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a855381996d351e557441b6c22ecd702d">parseMDNodeTail</a> (MDNode *&amp;N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2d4220f1d605382239f833bf83e9379">parseMDNodeVector</a> (SmallVectorImpl&lt; Metadata * &gt; &amp;Elts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseMDNodeVector ::= { Element (',' Element)* } Element ::= 'null' | <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> <a href="#ae2d4220f1d605382239f833bf83e9379">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa9026627bf539b3ea8bee39110512d1">parseMetadataAttachment</a> (unsigned &amp;Kind, MDNode *&amp;MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseMetadataAttachment ::= !dbg !42 <a href="#afa9026627bf539b3ea8bee39110512d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58c4833b29ba725c7b32ae46750c0cff">parseDebugRecord</a> (DbgRecord *&amp;DR, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDebugRecord ::= #dbg_label '(' <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> ')' ::= #dbg_type '(' <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> ',' <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> ',' <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> ',' (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> ',' <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> ',' <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> ',')? <a href="#a58c4833b29ba725c7b32ae46750c0cff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d1f72b969d9b358ec1f88917f71c709">parseInstructionMetadata</a> (Instruction &amp;Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseInstructionMetadata ::= !dbg !42 (',' !dbg !57)* <a href="#a2d1f72b969d9b358ec1f88917f71c709">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad600116d5518922bb7cd62f1452338ab">parseGlobalObjectMetadataAttachment</a> (GlobalObject &amp;GO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseGlobalObjectMetadataAttachment ::= !dbg !57 <a href="#ad600116d5518922bb7cd62f1452338ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34a5924990fa09b5be9f217f3c77be5">parseOptionalFunctionMetadata</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseOptionalFunctionMetadata ::= (!dbg !57)* <a href="#ab34a5924990fa09b5be9f217f3c77be5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FieldTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac70624a8e77b26361523dda7d22f6252">parseMDField</a> (LocTy Loc, StringRef Name, FieldTy &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FieldTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac463db763b3cade5cb0ba26ba1529068">parseMDField</a> (StringRef Name, FieldTy &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ParserTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a947255a02d35180d19d7aeb40f3638e3">parseMDFieldsImplBody</a> (ParserTy ParseField)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ParserTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf46cc2151e3af05bd98bd23f4eba798">parseMDFieldsImpl</a> (ParserTy ParseField, LocTy &amp;ClosingLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5e3a226d5c38dcb65fdd50a1edae425">parseSpecializedMDNode</a> (MDNode *&amp;N, bool IsDistinct=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac89194e2eb36115e65de3003f5901a24">parseDIExpressionBody</a> (MDNode *&amp;Result, bool IsDistinct)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDIExpressionBody: ::= (0, 7, -1) <a href="#ac89194e2eb36115e65de3003f5901a24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a098253c44b8ebe6b9b921c4b2053bbb9">parseArgumentList</a> (SmallVectorImpl&lt; ArgInfo &gt; &amp;ArgList, SmallVectorImpl&lt; unsigned &gt; &amp;UnnamedArgNums, bool &amp;IsVarArg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseArgumentList - parse the argument list for a function type or function prototype. <a href="#a098253c44b8ebe6b9b921c4b2053bbb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad8a1be5edde21668b9fa932651cf92">parseFunctionHeader</a> (Function *&amp;Fn, bool IsDefine, unsigned &amp;FunctionNumber, SmallVectorImpl&lt; unsigned &gt; &amp;UnnamedArgNums)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FunctionHeader ::= OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalCallingConv OptRetAttrs OptUnnamedAddr <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> GlobalName '(' ArgList ')' OptAddrSpace OptFuncAttrs OptSection OptionalAlign OptGC OptionalPrefix OptionalPrologue OptPersonalityFn. <a href="#aaad8a1be5edde21668b9fa932651cf92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437206570f755cbf3c4817a8714a9a6d">parseFunctionBody</a> (Function &amp;Fn, unsigned FunctionNumber, ArrayRef&lt; unsigned &gt; UnnamedArgNums)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseFunctionBody ::= '{' BasicBlock+ UseListOrderDirective* '}' <a href="#a437206570f755cbf3c4817a8714a9a6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a25452002cf7cd9c40b8ee931db059e">parseBasicBlock</a> (PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseBasicBlock ::= (LabelStr|LabelID)? <a href="#a6a25452002cf7cd9c40b8ee931db059e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a577d0c87777ad23c7a653216f94c8645">parseInstruction</a> (Instruction *&amp;Inst, BasicBlock *BB, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseInstruction - parse one of the many different instructions. <a href="#a577d0c87777ad23c7a653216f94c8645">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2221b165fb9515a1bf05b7b1aedc6af">parseCmpPredicate</a> (unsigned &amp;P, unsigned Opc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCmpPredicate - parse an integer or fp predicate, based on Kind. <a href="#aa2221b165fb9515a1bf05b7b1aedc6af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52b0d5e832c5698ae18bc903f43461ee">parseRet</a> (Instruction *&amp;Inst, BasicBlock *BB, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseRet - parse a return instruction. <a href="#a52b0d5e832c5698ae18bc903f43461ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb4ad3400ae82d666ebe4c970c5383ef">parseBr</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseBr ::= 'br' TypeAndValue ::= 'br' TypeAndValue ',' TypeAndValue ',' TypeAndValue <a href="#aeb4ad3400ae82d666ebe4c970c5383ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a350d81444b0c4ec21d8e0b9e2d12ab44">parseSwitch</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseSwitch <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> ::= 'switch' TypeAndValue ',' TypeAndValue '[' <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> ']' <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> ::= (TypeAndValue ',' TypeAndValue)* <a href="#a350d81444b0c4ec21d8e0b9e2d12ab44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f66a093e64b897aa4b2599bae77627f">parseIndirectBr</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseIndirectBr <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> ::= 'indirectbr' TypeAndValue ',' '[' LabelList ']' <a href="#a9f66a093e64b897aa4b2599bae77627f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70abb57c6788478af53fca4518cf1295">parseInvoke</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseInvoke ::= 'invoke' OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParamList OptionalAttrs 'to' TypeAndValue 'unwind' TypeAndValue <a href="#a70abb57c6788478af53fca4518cf1295">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f4437b2ae6e8d61711247093882b6a">parseResume</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseResume ::= 'resume' TypeAndValue <a href="#ad7f4437b2ae6e8d61711247093882b6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8554a72d5478d1efa450f45d17f9bf3b">parseCleanupRet</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCleanupRet ::= 'cleanupret' from <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> unwind ('to' 'caller' | TypeAndValue) <a href="#a8554a72d5478d1efa450f45d17f9bf3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a737c31a03097a51b99239280edb62147">parseCatchRet</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCatchRet ::= 'catchret' from Parent <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> 'to' TypeAndValue <a href="#a737c31a03097a51b99239280edb62147">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa07a7b082e4d4a82a553e5ccf5d8121b">parseCatchSwitch</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCatchSwitch ::= 'catchswitch' within Parent <a href="#aa07a7b082e4d4a82a553e5ccf5d8121b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb1ce005efd6b5ce0bb316213a474ae9">parseCatchPad</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCatchPad ::= 'catchpad' ParamList 'to' TypeAndValue 'unwind' TypeAndValue <a href="#acb1ce005efd6b5ce0bb316213a474ae9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5a9e25931c1c830d3094348bbd4bf6">parseCleanupPad</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCleanupPad ::= 'cleanuppad' within Parent ParamList <a href="#afd5a9e25931c1c830d3094348bbd4bf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0156b24b4b5ded49a3fa9b6d39ecdea5">parseCallBr</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCallBr ::= 'callbr' OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParamList OptionalAttrs OptionalOperandBundles 'to' TypeAndValue '[' LabelList ']' <a href="#a0156b24b4b5ded49a3fa9b6d39ecdea5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab0ce8f7a6541d885c459ec512f2f83e">parseUnaryOp</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS, unsigned Opc, bool IsFP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseUnaryOp ::= UnaryOp TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> <a href="#aab0ce8f7a6541d885c459ec512f2f83e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f17221b593e0a0f074f7a02683ae8c3">parseArithmetic</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS, unsigned Opc, bool IsFP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseArithmetic ::= ArithmeticOps TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> <a href="#a7f17221b593e0a0f074f7a02683ae8c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc2ddd83dca007140a4e9b9cd8df2632">parseLogical</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS, unsigned Opc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseLogical ::= ArithmeticOps TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> { <a href="#abc2ddd83dca007140a4e9b9cd8df2632">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0253e2d9222f514ac0befc28c81c5ec0">parseCompare</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS, unsigned Opc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCompare ::= 'icmp' IPredicates TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ::= 'fcmp' FPredicates TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> <a href="#a0253e2d9222f514ac0befc28c81c5ec0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125a5025030b4c685053438a9813afbd">parseCast</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS, unsigned Opc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCast ::= CastOpc TypeAndValue 'to' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="#a125a5025030b4c685053438a9813afbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3f8dca115211f1b404bd78b0c7ca0ae">parseSelect</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseSelect ::= 'select' TypeAndValue ',' TypeAndValue ',' TypeAndValue <a href="#ae3f8dca115211f1b404bd78b0c7ca0ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2005e9bf905aba912ce0eead054433">parseVAArg</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseVAArg ::= 'va_arg' TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="#a8d2005e9bf905aba912ce0eead054433">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b40efc511780eb113a07751fb584480">parseExtractElement</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseExtractElement ::= 'extractelement' TypeAndValue ',' TypeAndValue <a href="#a2b40efc511780eb113a07751fb584480">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada9f778516d48c22fcffb5b3f9382d8c">parseInsertElement</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseInsertElement ::= 'insertelement' TypeAndValue ',' TypeAndValue ',' TypeAndValue <a href="#ada9f778516d48c22fcffb5b3f9382d8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542dddf00ac7267abc44ad4365b46a2c">parseShuffleVector</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseShuffleVector ::= 'shufflevector' TypeAndValue ',' TypeAndValue ',' TypeAndValue <a href="#a542dddf00ac7267abc44ad4365b46a2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa21b1b01e811866c0b4eb9fa54327e9f">parsePHI</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parsePHI ::= 'phi' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> '[' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ']' (',' '[' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ']')* <a href="#aa21b1b01e811866c0b4eb9fa54327e9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a013d7487ce2a192d1c188bdf7a6f7ee8">parseLandingPad</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseLandingPad ::= 'landingpad' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> 'personality' TypeAndValue 'cleanup'? <a href="#a013d7487ce2a192d1c188bdf7a6f7ee8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72ecea162e782cc420391bce23586d7e">parseCall</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS, CallInst::TailCallKind TCK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCall ::= 'call' OptionalFastMathFlags OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParameterList OptionalAttrs ::= 'tail' 'call' OptionalFastMathFlags OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParameterList OptionalAttrs ::= 'musttail' 'call' OptionalFastMathFlags OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParameterList OptionalAttrs ::= 'notail' 'call' OptionalFastMathFlags OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParameterList OptionalAttrs <a href="#a72ecea162e782cc420391bce23586d7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a34f2743d22c9d14c651970a25a0202">parseAlloc</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseAlloc ::= 'alloca' 'inalloca'? <a href="#a6a34f2743d22c9d14c651970a25a0202">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed58983b12ae6bebe3e145f8418d42a">parseLoad</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseLoad ::= 'load' 'volatile'? <a href="#a5ed58983b12ae6bebe3e145f8418d42a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc9e755250dc6530798fabaf52832e0e">parseStore</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseStore <a href="#abc9e755250dc6530798fabaf52832e0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90c948d32e05705b4a8f5ed6a65acab4">parseCmpXchg</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseCmpXchg ::= 'cmpxchg' 'weak'? <a href="#a90c948d32e05705b4a8f5ed6a65acab4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac49526e6b39457bc68cb3ef8644d8f57">parseAtomicRMW</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseAtomicRMW ::= 'atomicrmw' 'volatile'? <a href="#ac49526e6b39457bc68cb3ef8644d8f57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0f6f2ac4d45a07bd548f75a42684918">parseFence</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseFence ::= 'fence' 'singlethread'? <a href="#af0f6f2ac4d45a07bd548f75a42684918">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeccf0ca635b3fe24fa8f322d19a1aa3c">parseGetElementPtr</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseGetElementPtr ::= 'getelementptr' 'inbounds'? <a href="#aeccf0ca635b3fe24fa8f322d19a1aa3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad192bf01844c65a3bee9484c332ece43">parseExtractValue</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseExtractValue ::= 'extractvalue' TypeAndValue (',' uint32)+ <a href="#ad192bf01844c65a3bee9484c332ece43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f933d70efec36c72b020a84f1b8696">parseInsertValue</a> (Instruction *&amp;Inst, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseInsertValue ::= 'insertvalue' TypeAndValue ',' TypeAndValue (',' uint32)+ <a href="#aa7f933d70efec36c72b020a84f1b8696">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcda09f695c93fd3c773f9b18e5d3137">parseFreeze</a> (Instruction *&amp;I, PerFunctionState &amp;PFS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseFreeze ::= 'freeze' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> <a href="#adcda09f695c93fd3c773f9b18e5d3137">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4076fafa42ba77bfc5bdf64624ea90c0">parseUseListOrder</a> (PerFunctionState *PFS=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseUseListOrder ::= 'uselistorder' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' UseListOrderIndexes <a href="#a4076fafa42ba77bfc5bdf64624ea90c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a729b0ab5e3e4a7f51a1fdb795c12de">parseUseListOrderBB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseUseListOrderBB ::= 'uselistorder_bb' @foo ',' bar ',' UseListOrderIndexes <a href="#a5a729b0ab5e3e4a7f51a1fdb795c12de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8d60fcbde9043c0ba28531fef408db">parseUseListOrderIndexes</a> (SmallVectorImpl&lt; unsigned &gt; &amp;Indexes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseUseListOrderIndexes ::= '{' uint32 (',' uint32)+ '}' <a href="#a9b8d60fcbde9043c0ba28531fef408db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e6297e2c93e3b39efb76285b04cf60">sortUseListOrder</a> (Value *V, ArrayRef&lt; unsigned &gt; Indexes, SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8deb1c6359fa7a3a8995c007f46da4">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lllexer">LLLexer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21fb246023b5db88df9623fb4571ed0c">OPLex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lllexer">LLLexer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24e927c277dba845155e4da1675395e6">Lex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c747c27281d840b271d42e7a5400c8f">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07e3dba6442627cc412f334f4e160250">Index</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55e0a2331371d5d1dea068a8bd5eb641">Slots</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc212a4cfb8733532dc6c14c3091a295">InstsWithTBAATag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 2 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7606a05aa6b21ba6e544a2098c8afe35">TempDIAssignIDAttachments</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> metadata does not support temporary RAUW so we cannot use the normal metadata forward reference resolution method. <a href="#a7606a05aa6b21ba6e544a2098c8afe35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc2eea497b1bdb080f773f5a2d130e2">NamedTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b0359b7acd0ec4a2ba79fed8c561c9c">NumberedTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7597d5980742ff874adb56fe3e463a97">NumberedMetadata</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, std::pair&lt; TempMDTuple, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a3f1d73549d693102a8501e995c22df">ForwardRefMDNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa07607f35d18f486162a126611f1892e">ForwardRefVals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f43ceb88e86acc608903df344b2fe9">ForwardRefValIDs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/numberedvalues">NumberedValues</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b27ec2aed8bc890d9c9dab1dcadbde3">NumberedVals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461f347a75dc7881586a9bfbdef889f4">ForwardRefComdats</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/valid">ValID</a>, std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/valid">ValID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fee7065f9bb3a53990ce6a3dd80aeb7">ForwardRefBlockAddresses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PerFunctionState *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77e62957c6607cdbf53ec3cf444417d6">BlockAddressPFS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to per-function state to allow basic blocks to be forward-referenced by blockaddress instructions within the same function. <a href="#a77e62957c6607cdbf53ec3cf444417d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/valid">ValID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a485a5b2ef004237091c2e6b69a212cf0">ForwardRefDSOLocalEquivalentNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/valid">ValID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08a954a59489b1503784cadf83574037">ForwardRefDSOLocalEquivalentIDs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, std::vector&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d8d6fd7939b12dd5af5af5defc73d7a">ForwardRefAttrGroups</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, AttrBuilder &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6057124d00bff7c0940be3fba72903b6">NumberedAttrBuilders</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> *, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9591e8afe030a7bc5c44079de748fdc">ForwardRefValueInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/aliassummary">AliasSummary</a> *, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae962401d5e156abf775d4024e832d9ef">ForwardRefAliasees</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97fdaf32f97bdca5c8891618a0640ae5">NumberedValueInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> *, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1992c874d2ded5e67272d72e5fd157a">ForwardRefTypeIds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83670dcf80f0eb6ba99a8bcec1daa3f0">ModuleIdMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac41bf6e3f8d1cc14e4c358a307bda9f5">UpgradeDebugInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only the llvm-as tool may set this to false to bypass UpgradeDebuginfo so it can generate broken bitcode. <a href="#ac41bf6e3f8d1cc14e4c358a307bda9f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cb42cc0f2f9eeab3e90c0c11bdee714">SeenNewDbgInfoFormat</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fea7ca88f89311d7cb657b3c8c1a17a">SeenOldDbgInfoFormat</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bda931a40d2d0292064e83d561e7826">SourceFileName</a></td>
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


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LocTy {#a41214230e1d2e66a2b675eeaa0ee2c7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef LLLexer::LocTy llvm::LLParser::LocTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### IdLocListType {#a5485c7c2ab01078824368fba31aace60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LLParser::IdLocListType =  std::vector&lt;std::pair&lt;unsigned, LocTy&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### IdToIndexMapType {#a46c5867d668a3d90501974f900f56a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LLParser::IdToIndexMapType = 
        std::map&lt;unsigned, std::vector&lt;std::pair&lt;unsigned, LocTy&gt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### InstResult {#adab10abb8ce4248333d9443f225341bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LLParser::InstResult </td>
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
<td class="doxyEnumItemName">InstNormal<a id="adab10abb8ce4248333d9443f225341bba9a1196dbe9cc88a7dd4336f6bfc0b361"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InstError<a id="adab10abb8ce4248333d9443f225341bbaa2703cc20f09060357a6107d114b9800"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InstExtraComma<a id="adab10abb8ce4248333d9443f225341bba852a9aa8c6542b794c45c79286b943fd"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### TailCallType {#aa116397fc363f9b4aa49ddb7f56ff83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LLParser::TailCallType </td>
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
<td class="doxyEnumItemName">TCT_None<a id="aa116397fc363f9b4aa49ddb7f56ff83eaa1f0bb1edab0f3b482200fe8970dddcb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCT_Tail<a id="aa116397fc363f9b4aa49ddb7f56ff83eab5aacd9d844391e4f8b64cbb67cc69cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TCT_MustTail<a id="aa116397fc363f9b4aa49ddb7f56ff83ea52d79304cc98895c6d09029e62511cdb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LLParser() {#a8f145595be2ff704a2f264e57cd41c55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LLParser::LLParser (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> F, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Err, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * Index, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a> * Slots=nullptr)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getContext() {#a7d0c164bcb08d642a0ab4047f07be8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; llvm::LLParser::getContext ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseDIExpressionBodyAtBeginning() {#a2a854410b123568e0bb9824f0a3cb94c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseDIExpressionBodyAtBeginning (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; Result, unsigned &amp; Read, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a> * Slots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smloc/#a7428ebe08f75a705043e1bd005d0542d">llvm::SMLoc::getPointer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa33af1aad55fa136e2ab54409f4b4891f">llvm::Read</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a693d5398216b0ca25097c2bde8fe6284">llvm::parseDIExpressionBodyAtBeginning</a>.</p>

</div>
</div>

### parseMDField() {#ae731f70b809827b785b51b3e2e24413d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, MDAPSIntField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4782 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>.</p>

</div>
</div>

### parseMDField() {#af22c380ad7396a702e8bc0c4a9b837e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, MDUnsignedField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4792 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### parseMDField() {#ae1f7e18ed94e0769ee2de12128c2e2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, LineField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4808 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDField() {#afe7bade8e1ef5dd6e786170633168f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, ColumnField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4812 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDField() {#ab5ae8011166e33d1f6b5ea8847cb9329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, DwarfTagField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4817 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4a64aca7a0743065ff63ca84cb013f08fd">llvm::dwarf::DW_TAG_invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a98d2b836dbaf72babd8ccfc743dc400a">llvm::lltok::DwarfTag</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga5e36554e194e99d7da32c35d16ba453a">llvm::dwarf::getTag</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### parseMDField() {#a089d6dfe66bd827e2bdad201383a5d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, DwarfMacinfoTypeField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4835 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4a955ccfcc72dc8efd5d68f8ede36cb563">llvm::dwarf::DW_MACINFO_invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a9cf06524b2c8c2fb2118feddd864c996">llvm::lltok::DwarfMacinfo</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#gaedfb90cbf93ba3782def5165b3830452">llvm::dwarf::getMacinfo</a>.</p>

</div>
</div>

### parseMDField() {#a8b98975ff05abf17080af8cd0278a60e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, DwarfVirtualityField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4855 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4aace94a5cb6c3f6e98251b9257a5e7893">llvm::dwarf::DW_VIRTUALITY_invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a083d5b71a2019a6576708547039c3944">llvm::lltok::DwarfVirtuality</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga79029f75d17b7821fd61ec6b992d0f84">llvm::dwarf::getVirtuality</a>.</p>

</div>
</div>

### parseMDField() {#adedf4778a9d218a587c1d18bf9e02474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, DwarfLangField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4874 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1aa8f3c22c37ad8056cebe70faf0fa3f7a">llvm::lltok::DwarfLang</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga74b19c4e1fb8540a9975e774efc46fd9">llvm::dwarf::getLanguage</a>.</p>

</div>
</div>

### parseMDField() {#a345d7c4db2764f44efd8bf58770928d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, DwarfCCField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4892 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a24f95326a653c35176f39f1159e53ecf">llvm::lltok::DwarfCC</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga70747367467013c5b906dd29773f16e0">llvm::dwarf::getCallingConvention</a>.</p>

</div>
</div>

### parseMDField() {#a46836f2cf5e318baf7539c56130c16ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, EmissionKindField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4910 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1aa6d90017a54975765547a91f8dc37360">llvm::lltok::EmissionKind</a> and <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a2d4862073480e7ac7169a3741fef1339">llvm::DICompileUnit::getEmissionKind</a>.</p>

</div>
</div>

### parseMDField() {#a1e2375ce5af65ae70e5450c3a7938a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, NameTableKindField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4929 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a9111ba431ceafe9283b9ee0a587f533d">llvm::DICompileUnit::getNameTableKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a736d24d0082969cb0e456c35871124de">llvm::lltok::NameTableKind</a>.</p>

</div>
</div>

### parseMDField() {#a056d8ee2e72bc9d8bc6fc68313378e23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, DwarfAttEncodingField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4948 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a57c1ac56877d1ffed49c0bbb2d8a05d9">llvm::lltok::DwarfAttEncoding</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga42773bac5182a842f016704db8007e54">llvm::dwarf::getAttributeEncoding</a>.</p>

</div>
</div>

### parseMDField() {#ab301262b421c4bacda7d25bf5283ab0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, DIFlagField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DIFlagField ::= uint32 ::= DIFlagVector ::= DIFlagVector '|' DIFlagFwdDecl '|' uint32 '|' DIFlagPublic.</p>

<p>Definition at line 4971 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a90341ec0034ef3ce30ba4c96acf92173">llvm::lltok::bar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a3599a77cab244f001c4d27c542588fde">llvm::lltok::DIFlag</a> and <a href="/web-llvm/docs/api/classes/llvm/dinode/#a35d619dfbd94cfdf3aabaf66cdb6115c">llvm::DINode::getFlag</a>.</p>

</div>
</div>

### parseMDField() {#a139caabba1e0e7afddf9b19804483dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, DISPFlagField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DISPFlagField ::= uint32 ::= DISPFlagVector ::= DISPFlagVector '|' DISPFlag* '|' uint32.</p>

<p>Definition at line 5011 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a90341ec0034ef3ce30ba4c96acf92173">llvm::lltok::bar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a89ce121a78ce9a52d0ea5eda4ecef3bc">llvm::lltok::DISPFlag</a> and <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#ab048654bcb9a1b09231983bf1c71efb9">llvm::DISubprogram::getFlag</a>.</p>

</div>
</div>

### parseMDField() {#ac8ca5648a3b5b77172872866f4d17c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, MDSignedField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5047 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### parseMDField() {#a67695067bd720a3fabfa95588cf43823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, MDBoolField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5066 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a6d70bc322669462be9f9b122df6edf13">llvm::lltok::kw_false</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a0e366197164a4728411e0e1828072de6">llvm::lltok::kw_true</a>.</p>

</div>
</div>

### parseMDField() {#a1dd00d42b68ddec3d9bde61d3d68b4c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, MDField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5082 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1ae70b2db121a3e6353649277dbd1ff628">llvm::lltok::kw_null</a>.</p>

</div>
</div>

### parseMDField() {#acefe52ec8f85d7b71cc97bd5ee550f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, MDSignedOrMDField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5100 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2a534f35c27ab3eb596772936555af70">llvm::lltok::APSInt</a>.</p>

</div>
</div>

### parseMDField() {#a48a9cfa41a13b34d64b9dcb824d9075a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, MDStringField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5123 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a> and <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>.</p>

</div>
</div>

### parseMDField() {#afc489c5343ab75b8ae77c119e7a71c53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, MDFieldList &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5137 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDField() {#acd526ef47b9208261d3dbc3acc67b8d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, ChecksumKindField &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5147 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a97c0978253894c181d89e066ee692cb3">llvm::lltok::ChecksumKind</a> and <a href="/web-llvm/docs/api/classes/llvm/difile/#a7f69484f6a25f76fceea4fda06fee60d">llvm::DIFile::getChecksumKind</a>.</p>

</div>
</div>

### parseStandaloneConstantValue() {#ab0a8518366b4a3c7ae8ffcfa342f7137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseStandaloneConstantValue (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *&amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a> * Slots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a7aeb5b2275fc35a5237b14f4967e3d8f">llvm::lltok::Eof</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abf2c472d771169c6100c6302079309da">llvm::parseConstantValue</a>.</p>

</div>
</div>

### parseTypeAtBeginning() {#a933523072cbd91ce32852b7b52a74d52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTypeAtBeginning (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; Ty, unsigned &amp; Read, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a> * Slots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smloc/#a7428ebe08f75a705043e1bd005d0542d">llvm::SMLoc::getPointer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa33af1aad55fa136e2ab54409f4b4891f">llvm::Read</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a35d32e57764638fe887f59392490e49c">llvm::parseTypeAtBeginning</a>.</p>

</div>
</div>

### Run() {#aeabb9a69009bc6019e909b931db71937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::Run (bool UpgradeDebugInfo, <a href="/web-llvm/docs/api/namespaces/llvm/#aa50ec5faa5aae091f99b0f840f58a379">DataLayoutCallbackTy</a> DataLayoutCallback=[](<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) { return std::nullopt;})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run: module ::= toplevelentity*.</p>

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp/#a982f596dc670886cba9172ea00cb7a48">parseAssemblyInto</a> and <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp/#a3f2868a82e652c99a57c4dd99683af87">parseSummaryIndexAssemblyInto</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addGlobalValueToIndex() {#aed05964eda5c0764df24848d3f4e6255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::addGlobalValueToIndex (std::string Name, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> GUID, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> Linkage, unsigned ID, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> &gt; Summary, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores the given Name/GUID and associated summary into the Index.</p>


<p>Also updates any forward references to the associated entry <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>Declaration at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9291 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### checkValidVariableType() {#ae5544a5f99ec01602cc0cec68e28c02d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LLParser::checkValidVariableType (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1762 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### checkValueID() {#adb3fb450509b874395236ce03da905d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::checkValueID (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> L, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, unsigned NextID, unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3289 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### convertValIDToValue() {#a50a38b5a4f35538bc62685b6fa469e81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::convertValIDToValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/structs/llvm/valid">ValID</a> &amp; ID, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V, PerFunctionState * PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6157 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### dropUnknownMetadataReferences() {#a9046e7aed1bdcb48074f18962cf17922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLParser::dropUnknownMetadataReferences ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### EatFastMathFlagsIfPresent() {#a7e7b353760e5004218cf01ad4a2fac4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags llvm::LLParser::EatFastMathFlagsIfPresent ()</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### EatIfPresent() {#adada81c08e8dfed09386b888d7e4161a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::EatIfPresent (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> T)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### error() {#a2af960f0818e6272c48799698f3b25dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::error (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### getComdat() {#a989a109e8eadec290aa6b5934bdd2e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Comdat * LLParser::getComdat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> with the specified name, creating a forward reference record if needed.</p>

<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1842 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### getGlobalVal() {#a06465f20c2f8128f18d0fd79da6b1dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue * LLParser::getGlobalVal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getGlobalVal - Get a value with the specified name or <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, creating a forward reference record if needed.</p>


<p>This can return null if the value exists but does not have the right type.</p>


<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1779 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### getGlobalVal() {#ac8c42e5acf881bf7bdc62c07f2dce3e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue * LLParser::getGlobalVal (unsigned ID, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1810 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseAliasOrIFunc() {#ac4a8f742d10fbe56e056c536c4426537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseAliasOrIFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name, unsigned NameID, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> NameLoc, unsigned L, unsigned Visibility, unsigned DLLStorageClass, bool DSOLocal, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62">GlobalVariable::ThreadLocalMode</a> TLM, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45">GlobalVariable::UnnamedAddr</a> UnnamedAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseAliasOrIFunc: ::= GlobalVar '=' OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass OptionalThreadLocal OptionalUnnamedAddr 'alias|ifunc' AliaseeOrResolver SymbolAttrs*</p>


<p>AliaseeOrResolver ::= TypeAndValue</p>


<p>SymbolAttrs ::= ',' 'partition' StringConstant</p>


<p>Everything through OptionalUnnamedAddr has already been parsed.</p>


<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1165 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseAliasSummary() {#a286da85df0ce8a8ae5a4312a163da57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseAliasSummary (std::string Name, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> GUID, unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/aliassummary">AliasSummary</a> ::= 'alias' ':' '(' 'module' ':' ModuleReference ',' GVFlags ',' 'aliasee' ':' GVReference ')'.</p>

<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9618 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseAlloc() {#a6a34f2743d22c9d14c651970a25a0202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLParser::parseAlloc (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseAlloc ::= 'alloca' 'inalloca'?</p>


<p>'swifterror'? <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> (',' TypeAndValue)? (',' 'align' i32)? (',', 'addrspace(n))?</p>


<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8191 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseAllocKind() {#a6482ed9e8c1e73634dbd530012f3362d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseAllocKind (<a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1">AllocFnKind</a> &amp; Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2453 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseAllocSizeArguments() {#a9f89d9d12e5712c171ce4c6b2b09e352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseAllocSizeArguments (unsigned &amp; BaseSizeArg, std::optional&lt; unsigned &gt; &amp; HowManyArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2701 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseAllocType() {#a3d0cdca819f2ece3a84e580f566bcf42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseAllocType (uint8_t &amp; AllocType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#abb725d65acc814edc5c025fb8ee6d55b">AllocType</a> := ('none'|'notcold'|'cold'|'hot')</p>

<p>Declaration at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10632 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseAnonStructType() {#aa668cc36d37d5dbff0d3d2031eccb06b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseAnonStructType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; Result, bool Packed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseAnonStructType - parse an anonymous struct type, which is inlined into other structs.</p>

<p>Declaration at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3395 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseArgs() {#a223a5869d6caa835319bcf91aa38e90a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseArgs (std::vector&lt; uint64_t &gt; &amp; Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptionalResByArg ::= 'args' ':' '(' UInt64[, UInt64]* ')'.</p>

<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9257 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseArgumentList() {#a098253c44b8ebe6b9b921c4b2053bbb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseArgumentList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; ArgInfo &gt; &amp; ArgList, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; UnnamedArgNums, bool &amp; IsVarArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseArgumentList - parse the argument list for a function type or function prototype.</p>


<p>::= '(' ArgTypeListI ')' ArgTypeListI ::= /*empty*‍/ ::= '...' ::= ArgTypeList ',' '...' ::= ArgType (',' ArgType)*</p>


<p>Declaration at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3307 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseArithmetic() {#a7f17221b593e0a0f074f7a02683ae8c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseArithmetic (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS, unsigned Opc, bool IsFP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseArithmetic ::= ArithmeticOps TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a></p>


<p>If IsFP is false, then any integer operand is allowed, if it is true, any fp operand is allowed.</p>


<p>Declaration at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7781 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseArrayVectorType() {#a9d01f9eba8017e6a965960f055a96f32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseArrayVectorType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; Result, bool IsVector)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseArrayVectorType - parse an array or vector type, assuming the first token has already been consumed.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ::= '[' APSINTVAL 'x' Types ']' ::= '&lt;' APSINTVAL 'x' Types '&gt;' ::= '&lt;' 'vscale' 'x' APSINTVAL 'x' Types '&gt;'</p>


<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3505 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseAtomicRMW() {#ac49526e6b39457bc68cb3ef8644d8f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLParser::parseAtomicRMW (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseAtomicRMW ::= 'atomicrmw' 'volatile'?</p>


<p>BinOp TypeAndValue ',' TypeAndValue 'singlethread'? <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></p>


<p>Declaration at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8412 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseBasicBlock() {#a6a25452002cf7cd9c40b8ee931db059e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseBasicBlock (PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseBasicBlock ::= (LabelStr|LabelID)?</p>


<p>Instruction*</p>


<p>Declaration at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6711 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseBlockCount() {#a189a32ad9efb64a7e2526f3d4c6e72c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseBlockCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseBlockCount ::= 'blockcount' ':' UInt64</p>

<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9375 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseBr() {#aeb4ad3400ae82d666ebe4c970c5383ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseBr (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseBr ::= 'br' TypeAndValue ::= 'br' TypeAndValue ',' TypeAndValue ',' TypeAndValue</p>

<p>Declaration at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7239 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCall() {#a72ecea162e782cc420391bce23586d7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseCall (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/callinst/#ad682514c13f12f1a8d759d422fce6aef">CallInst::TailCallKind</a> TCK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCall ::= 'call' OptionalFastMathFlags OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParameterList OptionalAttrs ::= 'tail' 'call' OptionalFastMathFlags OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParameterList OptionalAttrs ::= 'musttail' 'call' OptionalFastMathFlags OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParameterList OptionalAttrs ::= 'notail' 'call' OptionalFastMathFlags OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParameterList OptionalAttrs</p>

<p>Declaration at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8077 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCallBr() {#a0156b24b4b5ded49a3fa9b6d39ecdea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseCallBr (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCallBr ::= 'callbr' OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParamList OptionalAttrs OptionalOperandBundles 'to' TypeAndValue '[' LabelList ']'</p>

<p>Declaration at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7673 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCapturesAttr() {#a54318a610458bc7ab4fed1f2660d70c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseCapturesAttr (AttrBuilder &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3170 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCast() {#a125a5025030b4c685053438a9813afbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseCast (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS, unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCast ::= CastOpc TypeAndValue 'to' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a></p>

<p>Declaration at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7851 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCatchPad() {#acb1ce005efd6b5ce0bb316213a474ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseCatchPad (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCatchPad ::= 'catchpad' ParamList 'to' TypeAndValue 'unwind' TypeAndValue</p>

<p>Declaration at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7601 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCatchRet() {#a737c31a03097a51b99239280edb62147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseCatchRet (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCatchRet ::= 'catchret' from Parent <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> 'to' TypeAndValue</p>

<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7532 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCatchSwitch() {#aa07a7b082e4d4a82a553e5ccf5d8121b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseCatchSwitch (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCatchSwitch ::= 'catchswitch' within Parent</p>

<p>Declaration at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7552 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCleanupPad() {#afd5a9e25931c1c830d3094348bbd4bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseCleanupPad (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCleanupPad ::= 'cleanuppad' within Parent ParamList</p>

<p>Declaration at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7623 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCleanupRet() {#a8554a72d5478d1efa450f45d17f9bf3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseCleanupRet (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCleanupRet ::= 'cleanupret' from <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> unwind ('to' 'caller' | TypeAndValue)</p>

<p>Declaration at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7503 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCmpPredicate() {#aa2221b165fb9515a1bf05b7b1aedc6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseCmpPredicate (unsigned &amp; P, unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCmpPredicate - parse an integer or fp predicate, based on Kind.</p>

<p>Declaration at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7157 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCmpXchg() {#a90c948d32e05705b4a8f5ed6a65acab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLParser::parseCmpXchg (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCmpXchg ::= 'cmpxchg' 'weak'?</p>


<p>'volatile'? TypeAndValue ',' TypeAndValue ',' TypeAndValue 'singlethread'? <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> ',' '<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>'?</p>


<p>Declaration at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8358 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseComdat() {#a27fff091ba3e53d9316f738a6b0fc01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseComdat ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseCompare() {#a0253e2d9222f514ac0befc28c81c5ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseCompare (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS, unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseCompare ::= 'icmp' IPredicates TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ::= 'fcmp' FPredicates TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a></p>

<p>Declaration at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7820 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseConstantValue() {#a1ad202e64f2e8706d17d818f6a2eaa96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseConstantValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *&amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6315 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseConstVCall() {#ad07aee1d4ebf71d83d497616fd2a40e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseConstVCall (<a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">FunctionSummary::ConstVCall</a> &amp; ConstVCall, IdToIndexMapType &amp; IdToIndexMap, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ConstVCall ::= '(' VFuncId ',' Args ')'.</p>

<p>Declaration at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10308 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseConstVCallList() {#a9115f747af80d51ab61111530276fa66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseConstVCallList (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Kind, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">FunctionSummary::ConstVCall</a> &gt; &amp; ConstVCallList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ConstVCallList ::= Kind ':' '(' ConstVCall [',' ConstVCall]* ')'.</p>

<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10271 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseDebugRecord() {#a58c4833b29ba725c7b32ae46750c0cff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseDebugRecord (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> *&amp; DR, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDebugRecord ::= #dbg_label '(' <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> ')' ::= #dbg_type '(' <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> ',' <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> ',' <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> ',' (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> ',' <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> ',' <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> ',')?</p>


<p><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> ')'</p>


<p>Declaration at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6816 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseDeclare() {#ab4c2c18fd74080f22d7d6f7305c503b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseDeclare ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>toplevelentity ::= 'declare' FunctionHeader</p>

<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseDefine() {#a0d954d20c0cf4b966579bffbedcf72ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseDefine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>toplevelentity ::= 'define' FunctionHeader (!dbg !56)* '{' ...</p>

<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseDIArgList() {#ac59f050e6aeae5c5932793f551a843ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseDIArgList (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *&amp; MD, PerFunctionState * PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDIArgList: ::= !DIArgList(i32 7, i64 %0)</p>

<p>Declaration at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 5973 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseDIExpressionBody() {#ac89194e2eb36115e65de3003f5901a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseDIExpressionBody (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; Result, bool IsDistinct)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDIExpressionBody: ::= (0, 7, -1)</p>

<p>Declaration at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 5918 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseEnumAttribute() {#a17d3b5700c0a44cc31b8587c44fc14cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseEnumAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Attr, AttrBuilder &amp; B, bool InAttrGroup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1548 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseExceptionArgs() {#a01fb701860a15fdd9c5da3bfde4aa41a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseExceptionArgs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Args, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 564 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7469 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseExtractElement() {#a2b40efc511780eb113a07751fb584480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseExtractElement (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseExtractElement ::= 'extractelement' TypeAndValue ',' TypeAndValue</p>

<p>Declaration at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7908 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseExtractValue() {#ad192bf01844c65a3bee9484c332ece43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLParser::parseExtractValue (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseExtractValue ::= 'extractvalue' TypeAndValue (',' uint32)+</p>

<p>Declaration at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8619 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseFence() {#af0f6f2ac4d45a07bd548f75a42684918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLParser::parseFence (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseFence ::= 'fence' 'singlethread'?</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></p>


<p>Declaration at line 668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8526 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseFlag() {#afcb7ff211e3247a023f61d9c7f5ff48d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseFlag (unsigned &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag ::= [0|1].</p>

<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9667 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseFnAttributeValuePairs() {#aea4507592a437656b40404b7c3ee03cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseFnAttributeValuePairs (AttrBuilder &amp; B, std::vector&lt; unsigned &gt; &amp; FwdRefAttrGrps, bool inAttrGrp, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &amp; BuiltinLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseFnAttributeValuePairs ::= &lt;attr&gt; | &lt;attr&gt; '='</p>

<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1683 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseFreeze() {#adcda09f695c93fd3c773f9b18e5d3137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseFreeze (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; I, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseFreeze ::= 'freeze' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a></p>

<p>Declaration at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8058 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseFunctionBody() {#a437206570f755cbf3c4817a8714a9a6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseFunctionBody (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, unsigned FunctionNumber, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; UnnamedArgNums)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseFunctionBody ::= '{' BasicBlock+ UseListOrderDirective* '}'</p>

<p>Declaration at line 621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6675 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseFunctionHeader() {#aaad8a1be5edde21668b9fa932651cf92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseFunctionHeader (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *&amp; Fn, bool IsDefine, unsigned &amp; FunctionNumber, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; UnnamedArgNums)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FunctionHeader ::= OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalCallingConv OptRetAttrs OptUnnamedAddr <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> GlobalName '(' ArgList ')' OptAddrSpace OptFuncAttrs OptSection OptionalAlign OptGC OptionalPrefix OptionalPrologue OptPersonalityFn.</p>

<p>Declaration at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6386 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseFunctionSummary() {#a2ef8cbea99e8515e98a40c73369906a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseFunctionSummary (std::string Name, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> GUID, unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> ::= 'function' ':' '(' 'module' ':' ModuleReference ',' GVFlags ',' 'insts' ':' UInt32 [',' OptionalFFlags]?</p>


<p>[',' OptionalCalls]? [',' OptionalTypeIdInfo]? [',' OptionalParamAccesses]? [',' OptionalRefs]? ')'</p>


<p>Declaration at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9471 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseFunctionType() {#a17785ceaa8026ee170df5c094af99b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseFunctionType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseFunctionType ::= <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ArgumentList OptionalAttrs</p>

<p>Declaration at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3365 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseGetElementPtr() {#aeccf0ca635b3fe24fa8f322d19a1aa3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLParser::parseGetElementPtr (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseGetElementPtr ::= 'getelementptr' 'inbounds'?</p>


<p>TypeAndValue (',' TypeAndValue)*</p>


<p>Declaration at line 669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8543 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseGlobal() {#a4cd67cba6b2bd0c2df8bee3ff2d5aadc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name, unsigned NameID, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> NameLoc, unsigned Linkage, bool HasLinkage, unsigned Visibility, unsigned DLLStorageClass, bool DSOLocal, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62">GlobalVariable::ThreadLocalMode</a> TLM, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45">GlobalVariable::UnnamedAddr</a> UnnamedAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseGlobal ::= GlobalVar '=' OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass OptionalThreadLocal OptionalUnnamedAddr OptionalAddrSpace OptionalExternallyInitialized GlobalType <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Const OptionalAttrs ::= OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass OptionalThreadLocal OptionalUnnamedAddr OptionalAddrSpace OptionalExternallyInitialized GlobalType <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Const OptionalAttrs</p>


<p>Everything up to and including OptionalUnnamedAddr has been parsed already.</p>


<p>Declaration at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1356 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseGlobalObjectMetadataAttachment() {#ad600116d5518922bb7cd62f1452338ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseGlobalObjectMetadataAttachment (<a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> &amp; GO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseGlobalObjectMetadataAttachment ::= !dbg !57</p>

<p>Declaration at line 590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2335 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseGlobalType() {#af723973e40edaa112204cc289a96bb90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseGlobalType (bool &amp; IsConstant)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseGlobalType ::= 'constant' ::= 'global'</p>

<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseGlobalTypeAndValue() {#af7fef328a172bcb0d17db68b3f3eef15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseGlobalTypeAndValue (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *&amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 4525 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseGlobalValue() {#a1a759af821267048054a2fcebca0aa08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseGlobalValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *&amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseGlobalValue - parse a global value with the specified type.</p>

<p>Declaration at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 4514 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseGlobalValueVector() {#a8a9eaffb3813182e5eb5a6d0416e37c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseGlobalValueVector (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &amp; Elts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseGlobalValueVector ::= /*empty*‍/ ::= TypeAndValue (',' TypeAndValue)*</p>

<p>Declaration at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 4556 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseGVarFlags() {#ac5c23be5f0905d10fc55e81ae36c0baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseGVarFlags (<a href="/web-llvm/docs/api/structs/llvm/globalvarsummary/gvarflags">GlobalVarSummary::GVarFlags</a> &amp; GVarFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GVarFlags ::= 'varFlags' ':' '(' 'readonly' ':' Flag ',' 'writeonly' ':' Flag ',' 'constant' ':' Flag ')'.</p>

<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10441 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseGVEntry() {#a3eca6ad4c688af18d352aa8660566440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseGVEntry (unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseGVEntry ::= 'gv' ':' '(' ('name' ':' STRINGCONSTANT | 'guid' ':' UInt64) [',' 'summaries' ':' Summary[',' Summary]* ]?</p>


<p>')' Summary ::= '(' (<a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> | VariableSummary | <a href="/web-llvm/docs/api/classes/llvm/aliassummary">AliasSummary</a>) ')'</p>


<p>Declaration at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9393 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseGVFlags() {#ac3d2f31e08b01f661372a0bafebd61d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseGVFlags (<a href="/web-llvm/docs/api/structs/llvm/globalvaluesummary/gvflags">GlobalValueSummary::GVFlags</a> &amp; GVFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GVFlags ::= 'flags' ':' '(' 'linkage' ':' OptionalLinkageAux ',' 'visibility' ':' Flag 'notEligibleToImport' ':' Flag ',' 'live' ':' Flag ',' 'dsoLocal' ':' Flag ',' 'canAutoHide' ':' Flag ',' ')'.</p>

<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10365 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseGVReference() {#af104cd0446948799afb3ce6b08f416fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseGVReference (<a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &amp; VI, unsigned &amp; GVId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GVReference ::= SummaryID.</p>

<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10505 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseHotness() {#a69852d83ae5ad725687f3f0393456c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseHotness (<a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caa">CalleeInfo::HotnessType</a> &amp; Hotness)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hotness := ('unknown'|'cold'|'none'|'hot'|'critical')</p>

<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9855 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseIndexList() {#acc9406829303f8355fb924e7f5b96f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseIndexList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Indices, bool &amp; AteExtraComma)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseIndexList - This parses the index list for an insert/extractvalue instruction.</p>


<p>This sets AteExtraComma in the case where we eat an extra comma at the end of the line and find that it is followed by metadata. Clients that don't allow metadata can call the version of this function that only takes one argument.</p>


<p>parseIndexList ::= (',' uint32)+</p>


<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2845 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseIndexList() {#aca9350267d2815ba3aaa1a482dfb1def}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseIndexList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Indices)</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseIndirectBr() {#a9f66a093e64b897aa4b2599bae77627f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseIndirectBr (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseIndirectBr <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> ::= 'indirectbr' TypeAndValue ',' '[' LabelList ']'</p>

<p>Declaration at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7314 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseInitializesAttr() {#a94bc5025f53ae140673c30f805f0c457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseInitializesAttr (AttrBuilder &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseInitializesAttr ::= initializes((Lo1,Hi1),(Lo2,Hi2),...)</p>

<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3126 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseInsertElement() {#ada9f778516d48c22fcffb5b3f9382d8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseInsertElement (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseInsertElement ::= 'insertelement' TypeAndValue ',' TypeAndValue ',' TypeAndValue</p>

<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7925 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseInsertValue() {#aa7f933d70efec36c72b020a84f1b8696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLParser::parseInsertValue (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseInsertValue ::= 'insertvalue' TypeAndValue ',' TypeAndValue (',' uint32)+</p>

<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8638 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseInstruction() {#a577d0c87777ad23c7a653216f94c8645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLParser::parseInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseInstruction - parse one of the many different instructions.</p>

<p>Declaration at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6920 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseInstructionMetadata() {#a2d1f72b969d9b358ec1f88917f71c709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseInstructionMetadata (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseInstructionMetadata ::= !dbg !42 (',' !dbg !57)*</p>

<p>Declaration at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2310 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseInvoke() {#a70abb57c6788478af53fca4518cf1295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseInvoke (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseInvoke ::= 'invoke' OptionalCallingConv OptionalAttrs <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ParamList OptionalAttrs 'to' TypeAndValue 'unwind' TypeAndValue</p>

<p>Declaration at line 638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7375 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseLandingPad() {#a013d7487ce2a192d1c188bdf7a6f7ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseLandingPad (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseLandingPad ::= 'landingpad' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> 'personality' TypeAndValue 'cleanup'?</p>


<p>Clause+ <a href="/web-llvm/docs/api/classes/llvm/clause">Clause</a> ::= 'catch' TypeAndValue ::= 'filter' ::= 'filter' TypeAndValue ( ',' TypeAndValue )*</p>


<p>Declaration at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8013 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseLoad() {#a5ed58983b12ae6bebe3e145f8418d42a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLParser::parseLoad (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseLoad ::= 'load' 'volatile'?</p>


<p>TypeAndValue (',' 'align' i32)? ::= 'load' 'atomic' 'volatile'? TypeAndValue 'singlethread'? <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> (',' 'align' i32)?</p>


<p>Declaration at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8259 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseLogical() {#abc2ddd83dca007140a4e9b9cd8df2632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseLogical (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS, unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseLogical ::= ArithmeticOps TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> {</p>

<p>Declaration at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7801 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDField() {#ac70624a8e77b26361523dda7d22f6252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FieldTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseMDField (<a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, FieldTy &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseMDField() {#ac463db763b3cade5cb0ba26ba1529068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FieldTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMDField (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, FieldTy &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 5192 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDFieldsImpl() {#aaf46cc2151e3af05bd98bd23f4eba798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ParserTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMDFieldsImpl (ParserTy ParseField, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &amp; ClosingLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 5177 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDFieldsImplBody() {#a947255a02d35180d19d7aeb40f3638e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ParserTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMDFieldsImplBody (ParserTy ParseField)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 5164 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDNode() {#ab2287d84b332961a15cf7e79e3bff855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMDNode (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a>: ::= !</p>


<p>{ ... } ::= !7 ::= !DILocation(...)</p>


<p>Declaration at line 584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 4591 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDNodeID() {#a46c8a47a98715a4c5aa39e83544b6612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMDNodeID (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 936 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDNodeTail() {#a855381996d351e557441b6c22ecd702d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMDNodeTail (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 4598 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDNodeVector() {#ae2d4220f1d605382239f833bf83e9379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMDNodeVector (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &amp; Elts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseMDNodeVector ::= { Element (',' Element)* } Element ::= 'null' | <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a></p>

<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8670 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDString() {#aef1b894f508200664bd2793bfdb0c4e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMDString (<a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *&amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMDTuple() {#af022032dbd55f5c0b340b50ec132ec86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMDTuple (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; MD, bool IsDistinct=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 4578 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMemoryAttr() {#ae11e09e058f1aae17d91dd8ba033e6cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MemoryEffects &gt; LLParser::parseMemoryAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2513 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMemProfs() {#a44ed818bd973c80ac89a247d76ba613d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMemProfs (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/mibinfo">MIBInfo</a> &gt; &amp; MIBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MemProfs := 'memProf' ':' '(' MemProf [',' MemProf]* ')' MemProf ::= '(' 'type' ':' <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#abb725d65acc814edc5c025fb8ee6d55b">AllocType</a> ',' 'stackIds' ':' '(' StackId [',' StackId]* ')' ')' StackId ::= UInt64.</p>

<p>Declaration at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10582 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMetadata() {#a9bdd0eecede328c52d4104ea8fb2e640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMetadata (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *&amp; MD, PerFunctionState * PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseMetadata ::= i32 local ::= i32 @global ::= i32 7 ::= !42 ::= !</p>


<p>{...} ::= !"string" ::= !DILocation(...)</p>


<p>Declaration at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6105 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMetadataAsValue() {#a41efbecade521b8e9120156c8a6a39d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMetadataAsValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseMetadataAsValue ::= metadata i32 local ::= metadata i32 @global ::= metadata i32 7 ::= metadata !0 ::= metadata !</p>


<p>{...} ::= metadata !"string"</p>


<p>Declaration at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6066 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseMetadataAttachment() {#afa9026627bf539b3ea8bee39110512d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseMetadataAttachment (unsigned &amp; Kind, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; MD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseMetadataAttachment ::= !dbg !42</p>

<p>Declaration at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2298 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseModuleAsm() {#ac170d9a7f149548b061e3714fd4f154e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseModuleAsm ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>toplevelentity ::= 'module' 'asm' STRINGCONSTANT</p>

<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseModuleEntry() {#a89b03c1898bd42cfab2cd7d4837bf8bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseModuleEntry (unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ModuleEntry ::= 'module' ':' '(' 'path' ':' STRINGCONSTANT ',' 'hash' ':' Hash ')' Hash ::= '(' UInt32 ',' UInt32 ',' UInt32 ',' UInt32 ',' UInt32 ')'.</p>

<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8830 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseModuleReference() {#a5cdb5dc9b80fe804a0673303b1d37be1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseModuleReference (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ModulePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ModuleReference ::= 'module' ':' UInt.</p>

<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10488 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseNamedGlobal() {#a0016f60d16340a5abc2cafc7f8e0df1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseNamedGlobal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseNamedGlobal: GlobalVar '=' OptionalVisibility (ALIAS | IFUNC) ... GlobalVar '=' OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass ... -&gt; global variable</p>

<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseNamedMetadata() {#aacfb785cbfd2bc80310b8276309d892b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseNamedMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseNamedMetadata: !foo = !</p>


<p>{ !1, !2 }</p>


<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 960 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseNamedType() {#a6389dfd5cb1cffee60a99966d126734e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseNamedType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>toplevelentity ::= LocalVar '=' 'type' type</p>

<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseNoFPClassAttr() {#a85d940ace9bdd5bb2d774de2c4804fea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLParser::parseNoFPClassAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2607 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalAddrSpace() {#a13818507aa8a132f667b4173f5b9430e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalAddrSpace (unsigned &amp; AddrSpace, unsigned DefaultAS=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalAddrSpace := /*empty*‍/ := 'addrspace' '(' uint32 ')'</p>

<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1945 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalAlignment() {#a86135a3f2f890c0994224d127014faa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalAlignment (<a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> &amp; Alignment, bool AllowParens=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalAlignment ::= /* empty *‍/ ::= 'align' 4</p>

<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2357 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalAllocs() {#afa7818545366d11975abb143cd83a0fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalAllocs (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/allocinfo">AllocInfo</a> &gt; &amp; Allocs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptionalAllocs := 'allocs' ':' '(' Alloc [',' Alloc]* ')' Alloc ::= '(' 'versions' ':' '(' Version [',' Version]* ')' ',' MemProfs ')' Version ::= UInt32.</p>

<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10533 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalCallingConv() {#a6824539a00fc41c4154f06e67f3f7dee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalCallingConv (unsigned &amp; CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalCallingConv ::= /*empty*‍/ ::= 'ccc' ::= 'fastcc' ::= 'intel_ocl_bicc' ::= 'coldcc' ::= 'cfguard_checkcc' ::= 'x86_stdcallcc' ::= 'x86_fastcallcc' ::= 'x86_thiscallcc' ::= 'x86_vectorcallcc' ::= 'arm_apcscc' ::= 'arm_aapcscc' ::= 'arm_aapcs_vfpcc' ::= 'aarch64_vector_pcs' ::= 'aarch64_sve_vector_pcs' ::= 'aarch64_sme_preservemost_from_x0' ::= 'aarch64_sme_preservemost_from_x1' ::= 'aarch64_sme_preservemost_from_x2' ::= 'msp430_intrcc' ::= 'avr_intrcc' ::= 'avr_signalcc' ::= 'ptx_kernel' ::= 'ptx_device' ::= 'spir_func' ::= 'spir_kernel' ::= 'x86_64_sysvcc' ::= 'win64cc' ::= 'anyregcc' ::= 'preserve_mostcc' ::= 'preserve_allcc' ::= 'preserve_nonecc' ::= 'ghccc' ::= 'swiftcc' ::= 'swifttailcc' ::= 'x86_intrcc' ::= 'hhvmcc' ::= 'hhvm_ccc' ::= 'cxx_fast_tlscc' ::= 'amdgpu_vs' ::= 'amdgpu_ls' ::= 'amdgpu_hs' ::= 'amdgpu_es' ::= 'amdgpu_gs' ::= 'amdgpu_ps' ::= 'amdgpu_cs' ::= 'amdgpu_cs_chain' ::= 'amdgpu_cs_chain_preserve' ::= 'amdgpu_kernel' ::= 'tailcc' ::= 'm68k_rtdcc' ::= 'graalcc' ::= 'riscv_vector_cc' ::= 'cc' UINT</p>

<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2212 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalCalls() {#aaf8012e1403fbd7f97bb66b9b286d093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalCalls (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/functionsummary/#a434edf3518376986c8bb393f5e0eec33">FunctionSummary::EdgeTy</a> &gt; &amp; Calls)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptionalCalls := 'calls' ':' '(' Call [',' Call]* ')' Call ::= '(' 'callee' ':' GVReference [( ',' 'hotness' ':' Hotness | ',' 'relbf' ':' UInt32 )]?</p>


<p>[ ',' 'tail' ]? ')'</p>


<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9773 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalCallsites() {#abcc728d4910b8718d92cbf443d337d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalCallsites (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/callsiteinfo">CallsiteInfo</a> &gt; &amp; Callsites)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptionalCallsites := 'callsites' ':' '(' Callsite [',' Callsite]* ')' Callsite ::= '(' 'callee' ':' GVReference ',' 'clones' ':' '(' Version [',' Version]* ')' ',' 'stackIds' ':' '(' StackId [',' StackId]* ')' ')' Version ::= UInt32 StackId ::= UInt64.</p>

<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10660 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalCodeModel() {#a4c9d5a12f809ead1f46c07ecd6b50e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalCodeModel (<a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &amp; model)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalCodeModel ::= /* empty *‍/ ::= 'code_model' "large"</p>

<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2388 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalComdat() {#af17b814efa41d979551dda7a033810bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalComdat (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GlobalName, <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *&amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 4530 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalCommaAddrSpace() {#a5df233044a54ed1bb6210aa2ac76481f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalCommaAddrSpace (unsigned &amp; AddrSpace, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &amp; Loc, bool &amp; AteExtraComma)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalCommaAddrSpace ::= ::= ',' addrspace(1)</p>


<p>This returns with AteExtraComma set to true if it ate an excess comma at the end.</p>


<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2680 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalCommaAlign() {#ad16d1d4f310a95770a704887634fe645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalCommaAlign (<a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> &amp; Alignment, bool &amp; AteExtraComma)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalCommaAlign ::= ::= ',' align 4</p>


<p>This returns with AteExtraComma set to true if it ate an excess comma at the end.</p>


<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2654 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalDerefAttrBytes() {#a8082f408b5d089d5a85e927d4bf06f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalDerefAttrBytes (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> AttrKind, uint64_t &amp; Bytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalDerefAttrBytes ::= /* empty *‍/ ::= AttrKind '(' 4 ')'</p>


<p>where AttrKind is either 'dereferenceable' or 'dereferenceable_or_null'.</p>


<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2414 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalDLLStorageClass() {#a72fb22953b5dae49af866723c1f95b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLParser::parseOptionalDLLStorageClass (unsigned &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalDLLStorageClass ::= /*empty*‍/ ::= 'dllimport' ::= 'dllexport'</p>

<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2142 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalDSOLocal() {#af84e1e037e1a1463f4738c407222c069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLParser::parseOptionalDSOLocal (bool &amp; DSOLocal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2083 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalFFlags() {#a7eb682244968b9862d11eea8b12ac070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalFFlags (<a href="/web-llvm/docs/api/structs/llvm/functionsummary/fflags">FunctionSummary::FFlags</a> &amp; FFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptionalFFlags := 'funcFlags' ':' '(' ['readNone' ':' Flag]?</p>


<p>[',' 'readOnly' ':' Flag]? [',' 'noRecurse' ':' Flag]? [',' 'returnDoesNotAlias' ':' Flag]? ')' [',' 'noInline' ':' Flag]? ')' [',' 'alwaysInline' ':' Flag]? ')' [',' 'noUnwind' ':' Flag]? ')' [',' 'mayThrow' ':' Flag]? ')' [',' 'hasUnknownCall' ':' Flag]? ')' [',' 'mustBeUnreachable' ':' Flag]? ')'</p>


<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9686 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalFunctionMetadata() {#ab34a5924990fa09b5be9f217f3c77be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalFunctionMetadata (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalFunctionMetadata ::= (!dbg !57)*</p>

<p>Declaration at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2347 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalImportType() {#a4ebe877e76e2f684d8dff47881255e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalImportType (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a04e3abfb7aee7a96d3d56a99c9f0b737">GlobalValueSummary::ImportKind</a> &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2123 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalLinkage() {#aa9195753d6181fd770002272b0d452e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalLinkage (unsigned &amp; Res, bool &amp; HasLinkage, unsigned &amp; Visibility, unsigned &amp; DLLStorageClass, bool &amp; DSOLocal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalLinkage ::= /*empty*‍/ ::= 'private' ::= 'internal' ::= 'weak' ::= 'weak_odr' ::= 'linkonce' ::= 'linkonce_odr' ::= 'available_externally' ::= 'appending' ::= 'common' ::= 'extern_weak' ::= 'external'</p>

<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2066 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalOperandBundles() {#a9f4ae60d13572b8c5bfbbd41e24b6274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalOperandBundles (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; &amp; BundleList, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalOperandBundles ::= /*empty*‍/ ::= '[' OperandBundle [, OperandBundle ]* ']'</p>


<p>OperandBundle ::= bundle-tag '(' ')' ::= bundle-tag '(' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> [, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ]* ')'</p>


<p>bundle-tag ::= String <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a></p>


<p>Declaration at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3238 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalParamAccesses() {#a45797abac6f6bf347c64012834303f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalParamAccesses (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/paramaccess">FunctionSummary::ParamAccess</a> &gt; &amp; Params)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptionalParamAccesses := 'params' ':' '(' ParamAccess [',' ParamAccess]* ')'.</p>

<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10040 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalParamAttrs() {#ac048bc31e2424d06f7e4a38bf1af5a43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseOptionalParamAttrs (AttrBuilder &amp; B)</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseOptionalParamOrReturnAttrs() {#a00b55ed6278f19796048f45a116c1d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalParamOrReturnAttrs (AttrBuilder &amp; B, bool IsParam)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a potentially empty list of parameter or return attributes.</p>

<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1994 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalProgramAddrSpace() {#ad88d5f7952ed1652450e6012366aa9ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseOptionalProgramAddrSpace (unsigned &amp; AddrSpace)</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseOptionalRefs() {#a21b808b58d34e7de8692eae6429e73eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalRefs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &gt; &amp; Refs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptionalRefs := 'refs' ':' '(' GVReference [',' GVReference]* ')'.</p>

<p>Declaration at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10082 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalResByArg() {#a240f5e03c41d358e4f7d29e33463c14a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalResByArg (std::map&lt; std::vector&lt; uint64_t &gt;, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg">WholeProgramDevirtResolution::ByArg</a> &gt; &amp; ResByArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptionalResByArg ::= 'wpdRes' ':' '(' ResByArg[, ResByArg]* ')' ResByArg ::= Args ',' 'byArg' ':' '(' 'kind' ':' ( 'indir' | 'uniformRetVal' | 'UniqueRetVal' | 'virtualConstProp' ) [',' 'info' ':' UInt64]?</p>


<p>[',' 'byte' ':' UInt32]? [',' 'bit' ':' UInt32]? ')'</p>


<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9178 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalReturnAttrs() {#a9397e0e46b851e37619d63fd0511bca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseOptionalReturnAttrs (AttrBuilder &amp; B)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseOptionalStackAlignment() {#aa5749ad1b6ebab8ea58f2ea8300d309f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalStackAlignment (unsigned &amp; Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalStackAlignment ::= /* empty *‍/ ::= 'alignstack' '(' 4 ')'</p>

<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2818 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalThreadLocal() {#aeb325b2c3b2bb51b3fa617de31d1652d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalThreadLocal (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62">GlobalVariable::ThreadLocalMode</a> &amp; TLM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalThreadLocal := /*empty*‍/ := 'thread_local' := 'thread_local' '(' tlsmodel ')'</p>

<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1928 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalToken() {#aa1a6ba4fae0bc5aa93f82c2255192dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseOptionalToken (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> T, bool &amp; Present, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> * Loc=nullptr)</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseOptionalTypeIdInfo() {#acd85eb3c2000dc7e9b3eb90b8b60d2a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalTypeIdInfo (<a href="/web-llvm/docs/api/structs/llvm/functionsummary/typeidinfo">FunctionSummary::TypeIdInfo</a> &amp; TypeIdInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptionalTypeIdInfo := 'typeidinfo' ':' '(' [',' TypeTests]?</p>


<p>[',' TypeTestAssumeVCalls]? [',' TypeCheckedLoadVCalls]? [',' TypeTestAssumeConstVCalls]? [',' TypeCheckedLoadConstVCalls]? ')'</p>


<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10143 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalUnnamedAddr() {#a3bc9c5a6df3a6b4efd4576fb3ecded24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalUnnamedAddr (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45">GlobalVariable::UnnamedAddr</a> &amp; UnnamedAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalUWTableKind() {#ae2e08d591e0d6d9098dd310986aa075c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalUWTableKind (<a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8">UWTableKind</a> &amp; Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2437 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalVisibility() {#aae1efceb106c8f8b54d913a0275a13e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLParser::parseOptionalVisibility (unsigned &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOptionalVisibility ::= /*empty*‍/ ::= 'default' ::= 'hidden' ::= 'protected'</p>

<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2105 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalVTableFuncs() {#aec55ececd9c99090fe3afc9ef191433f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalVTableFuncs (<a href="/web-llvm/docs/api/namespaces/llvm/#a0cba6e4101e6b20a4b71aa098d1b6c2c">VTableFuncList</a> &amp; VTableFuncs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptionalVTableFuncs := 'vTableFuncs' ':' '(' VTableFunc [',' VTableFunc]* ')' VTableFunc ::= '(' 'virtFunc' ':' GVReference ',' 'offset' ':' UInt64 ')'.</p>

<p>Declaration at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9882 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOptionalWpdResolutions() {#acb1451e2f64d69058edcec383707ccb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOptionalWpdResolutions (std::map&lt; uint64_t, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> &gt; &amp; WPDResMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptionalWpdResolutions ::= 'wpsResolutions' ':' '(' WpdResolution [',' WpdResolution]* ')' WpdResolution ::= '(' 'offset' ':' UInt64 ',' WpdRes ')'.</p>

<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9090 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseOrdering() {#a0b03d6146b5d411b5878e695ef69e5cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseOrdering (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> &amp; Ordering)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseOrdering ::= <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></p>


<p>This sets Ordering to the parsed value.</p>


<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2796 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseParamAccess() {#ab7d221b29a04a3db04d8581da4dcf22a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseParamAccess (<a href="/web-llvm/docs/api/structs/llvm/functionsummary/paramaccess">FunctionSummary::ParamAccess</a> &amp; Param, IdLocListType &amp; IdLocList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParamAccess := '(' ParamNo ',' ParamAccessOffset [',' OptionalParamAccessCalls]?</p>


<p>')' OptionalParamAccessCalls := '(' Call [',' Call]* ')'</p>


<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10008 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseParamAccessCall() {#ac5de913ec69c73e9690b8d75ec8fa955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseParamAccessCall (<a href="/web-llvm/docs/api/structs/llvm/functionsummary/paramaccess/call">FunctionSummary::ParamAccess::Call</a> &amp; Call, IdLocListType &amp; IdLocList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParamAccessCall := '(' 'callee' ':' GVReference ',' ParamNo ',' ParamAccessOffset ')'.</p>

<p>Declaration at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9977 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseParamAccessOffset() {#a9484b79c7f6c694dfc283c6da258bd6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseParamAccessOffset (<a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParamAccessOffset := 'offset' ':' '[' APSINTVAL ',' APSINTVAL ']'.</p>

<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9947 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseParameterList() {#a9f945f21880094ae719be6f19d6ef8a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseParameterList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; ParamInfo &gt; &amp; ArgList, PerFunctionState &amp; PFS, bool IsMustTailCall=false, bool InVarArgsFunc=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseParameterList ::= '(' ')' ::= '(' Arg (',' Arg)* ')' Arg ::= <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> OptionalAttributes <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> OptionalAttributes</p>

<p>Declaration at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3013 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseParamNo() {#a8d55b42b03286ed821cf1b1b72022244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseParamNo (uint64_t &amp; ParamNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParamNo := 'param' ':' UInt64.</p>

<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9939 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parsePHI() {#aa21b1b01e811866c0b4eb9fa54327e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLParser::parsePHI (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parsePHI ::= 'phi' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> '[' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ']' (',' '[' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ']')*</p>

<p>Declaration at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7963 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseRangeAttr() {#a0e0d45d3a5ca287f2101fd8c73e3caa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseRangeAttr (AttrBuilder &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseRangeAttr ::= range(&lt;ty&gt; &lt;n&gt;,&lt;n&gt;)</p>

<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3085 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseRequiredTypeAttr() {#a1e3df96c16b7d2a71aa037e3c60fb2b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseRequiredTypeAttr (AttrBuilder &amp; B, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> AttrToken, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> AttrKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseRequiredTypeAttr ::= attrname(&lt;ty&gt;)</p>

<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3067 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseResume() {#ad7f4437b2ae6e8d61711247093882b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseResume (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseResume ::= 'resume' TypeAndValue</p>

<p>Declaration at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7459 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseRet() {#a52b0d5e832c5698ae18bc903f43461ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseRet (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseRet - parse a return instruction.</p>


<p>::= 'ret' void (',' !dbg, !1)* ::= 'ret' TypeAndValue (',' !dbg, !1)*</p>


<p>Declaration at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7206 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseSanitizer() {#a80653d46b51ef51f9f6193bdbcef5261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseSanitizer (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1316 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseScope() {#a421856eb96fb87f3b99018da8d5bdcd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseScope (<a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> &amp; SSID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseScope ::= syncscope("singlethread" | "&lt;target scope&gt;")?</p>


<p>This sets synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the parsed value.</p>


<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2770 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseScopeAndOrdering() {#a6262e11e6598a41e5c38efde0656cf36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseScopeAndOrdering (bool IsAtomic, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> &amp; SSID, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> &amp; Ordering)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseScopeAndOrdering if isAtomic: ::= <a href="/web-llvm/docs/api/namespaces/llvm/syncscope">SyncScope</a>?</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> else: ::=</p>


<p>This sets Scope and Ordering to the parsed values.</p>


<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2758 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseSelect() {#ae3f8dca115211f1b404bd78b0c7ca0ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseSelect (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseSelect ::= 'select' TypeAndValue ',' TypeAndValue ',' TypeAndValue</p>

<p>Declaration at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7871 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseShuffleVector() {#a542dddf00ac7267abc44ad4365b46a2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseShuffleVector (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseShuffleVector ::= 'shufflevector' TypeAndValue ',' TypeAndValue ',' TypeAndValue</p>

<p>Declaration at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7944 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseSourceFileName() {#aa7da87993ec1871ce635b03493a3b9be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseSourceFileName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>toplevelentity ::= 'source_filename' '=' STRINGCONSTANT</p>

<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseSpecializedMDNode() {#ad5e3a226d5c38dcb65fdd50a1edae425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseSpecializedMDNode (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; N, bool IsDistinct=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 5201 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseStandaloneMetadata() {#a70ae6d5e1593954e460e54f243e4d85e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseStandaloneMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseStandaloneMetadata: !42 = !</p>


<p>{...}</p>


<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 998 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseStore() {#abc9e755250dc6530798fabaf52832e0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLParser::parseStore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseStore</p>


<p>::= 'store' 'volatile'? TypeAndValue ',' TypeAndValue (',' 'align' i32)? ::= 'store' 'atomic' 'volatile'? TypeAndValue ',' TypeAndValue 'singlethread'? <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> (',' 'align' i32)?</p>


<p>Declaration at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8309 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseStringAttribute() {#ad40feba9fa26c09b5b3fdadda58d602d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseStringAttribute (AttrBuilder &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseStringAttribute := StringConstant := StringConstant '=' StringConstant</p>

<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1983 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseStringConstant() {#a594c3663e4725d48154e1f015a4de6f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseStringConstant (std::string &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseStringConstant ::= StringConstant</p>

<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1870 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseStructBody() {#ad4542a952dd0ef632d997e724611176a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseStructBody (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; Body)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseStructType: Handles packed and unpacked types.</p>


<p>&lt;/&gt; parsed elsewhere. <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> ::= '{' '}' ::= '{' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> (',' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>)* '}' ::= '&lt;' '{' '}' '&gt;' ::= '&lt;' '{' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> (',' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>)* '}' '&gt;'</p>


<p>Declaration at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3468 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseStructDefinition() {#a38b6370117609a323a5b5e1ccad8f13d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseStructDefinition (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> TypeLoc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &gt; &amp; Entry, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; ResultTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseStructDefinition - parse a struct in a 'type' definition.</p>

<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3405 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseSummaryEntry() {#a2d07be785e547c4910068648a9afbefe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseSummaryEntry ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SummaryEntry ::= SummaryID '=' GVEntry | ModuleEntry | TypeIdEntry.</p>

<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1091 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseSummaryIndexFlags() {#a493da8131f6eb3837c7ea7ed12db9d17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseSummaryIndexFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseSummaryIndexFlags ::= 'flags' ':' UInt64</p>

<p>Declaration at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9359 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseSwitch() {#a350d81444b0c4ec21d8e0b9e2d12ab44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseSwitch (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseSwitch <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> ::= 'switch' TypeAndValue ',' TypeAndValue '[' <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> ']' <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> ::= (TypeAndValue ',' TypeAndValue)*</p>

<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7269 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseTargetDefinition() {#a0575c40c069e2478a12221e026a0b99b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTargetDefinition (std::string &amp; TentativeDLStr, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &amp; DLStrLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>toplevelentity ::= 'target' 'triple' '=' STRINGCONSTANT ::= 'target' 'datalayout' '=' STRINGCONSTANT</p>

<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseTargetDefinitions() {#ae59d2a9c17c62c4192b4d8e57e8824e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTargetDefinitions (<a href="/web-llvm/docs/api/namespaces/llvm/#aa50ec5faa5aae091f99b0f840f58a379">DataLayoutCallbackTy</a> DataLayoutCallback)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseTargetExtType() {#a7a68ea85d96605d2bdfe0bea06f80663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTargetExtType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseTargetExtType - handle target extension type syntax <a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> ::= 'target' '(' STRINGCONSTANT TargetExtTypeParams TargetExtIntParams ')'</p>


<p>TargetExtTypeParams ::= /*empty*‍/ ::= ',' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> TargetExtTypeParams</p>


<p>TargetExtIntParams ::= /*empty*‍/ ::= ',' uint32 TargetExtIntParams</p>


<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3563 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseTLSModel() {#ab8938108b39e6a1d29096e332f12bc9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTLSModel (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62">GlobalVariable::ThreadLocalMode</a> &amp; TLM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseTLSModel := 'localdynamic' := 'initialexec' := 'localexec'</p>

<p>Declaration at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1905 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseToken() {#a9fc2366bbf5022df182be87beee68bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseToken (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseToken - If the current token has the specified kind, eat it and return success.</p>


<p>Otherwise, emit the specified error and return failure.</p>


<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1861 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseTopLevelEntities() {#a90ac16debaa45260f4394f672073bcc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTopLevelEntities ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseType() {#a635a905f19a3fe6523c18010b628e4b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, bool AllowVoid=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseType - parse a type.</p>

<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2873 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseType() {#a058e99fcfdb85b6b689be1138a04c997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; Result, bool AllowVoid=false)</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseType() {#a8b8c2e72294b6f84b4dea953f38044f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &amp; Loc, bool AllowVoid=false)</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseType() {#aab9c6459cde961aabaf3f27e55eca850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; Result, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &amp; Loc, bool AllowVoid=false)</td>
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



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseTypeAndBasicBlock() {#ae84a5753dac0a5f9523532c388499bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTypeAndBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; BB, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &amp; Loc, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6358 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseTypeAndBasicBlock() {#a9ddd7621152818c1abe9e8b2bcf4815a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseTypeAndBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; BB, PerFunctionState &amp; PFS)</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseTypeAndValue() {#a99627eba593f579978c9671b0ba8e95c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTypeAndValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V, PerFunctionState * PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6353 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseTypeAndValue() {#a15567575c038137f98f7360f1f2ba3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseTypeAndValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V, PerFunctionState &amp; PFS)</td>
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



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseTypeAndValue() {#a5af80f85ac9b6be1a6e27cb2d252a856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseTypeAndValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &amp; Loc, PerFunctionState &amp; PFS)</td>
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



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseTypeIdCompatibleVtableEntry() {#aca1bebee585d201a7f0f0675fb0db78c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTypeIdCompatibleVtableEntry (unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TypeIdCompatibleVtableEntry ::= 'typeidCompatibleVTable' ':' '(' 'name' ':' STRINGCONSTANT ',' <a href="/web-llvm/docs/api/namespaces/llvm/#ada2485ca228b028f8639ad86ce41d6ec">TypeIdCompatibleVtableInfo</a> ')'.</p>

<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8926 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseTypeIdEntry() {#a83c7cab447e724997d0b88bba9cb266f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTypeIdEntry (unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TypeIdEntry ::= 'typeid' ':' '(' 'name' ':' STRINGCONSTANT ',' <a href="/web-llvm/docs/api/structs/llvm/typeidsummary">TypeIdSummary</a> ')'.</p>

<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8866 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseTypeIdSummary() {#a2c8d32ab262d41b7d3e5849eb856dcb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTypeIdSummary (<a href="/web-llvm/docs/api/structs/llvm/typeidsummary">TypeIdSummary</a> &amp; TIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/typeidsummary">TypeIdSummary</a> ::= 'summary' ':' '(' <a href="/web-llvm/docs/api/structs/llvm/typetestresolution">TypeTestResolution</a> [',' OptionalWpdResolutions]?</p>


<p>')'</p>


<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8900 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseTypeTestResolution() {#aefb217a088f5ccbea19007567c87787d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTypeTestResolution (<a href="/web-llvm/docs/api/structs/llvm/typetestresolution">TypeTestResolution</a> &amp; TTRes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/typetestresolution">TypeTestResolution</a> ::= 'typeTestRes' ':' '(' 'kind' ':' ( 'unsat' | 'byteArray' | 'inline' | 'single' | 'allOnes' ) ',' 'sizeM1BitWidth' ':' SizeM1BitWidth [',' 'alignLog2' ':' UInt64]?</p>


<p>[',' 'sizeM1' ':' UInt64]? [',' 'bitMask' ':' UInt8]? [',' 'inlinesBits' ':' UInt64]? ')'</p>


<p>Declaration at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9009 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseTypeTests() {#aedecc61c15e359c60fd92af7dba3379f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseTypeTests (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; TypeTests)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TypeTests ::= 'typeTests' ':' '(' (SummaryID | UInt64) [',' (SummaryID | UInt64)]* ')'.</p>

<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10192 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseUInt32() {#add7eabd4126cef5e821f839c12498ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseUInt32 (unsigned &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseUInt32() {#ab61ea68d95f527d1114e50313271a5c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseUInt32 (unsigned &amp; Val, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &amp; Loc)</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseUInt64() {#ac81c15155a8fc0e67652cde2e42cd0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseUInt64 (uint64_t &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseUInt64 ::= uint64</p>

<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1893 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseUInt64() {#a6c31c25087bdd59def483fe36755cb5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseUInt64 (uint64_t &amp; Val, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &amp; Loc)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseUnaryOp() {#aab0ce8f7a6541d885c459ec512f2f83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseUnaryOp (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS, unsigned Opc, bool IsFP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseUnaryOp ::= UnaryOp TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/value">Value</a></p>


<p>If IsFP is false, then any integer operand is allowed, if it is true, any fp operand is allowed.</p>


<p>Declaration at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7653 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseUnnamedAttrGrp() {#a1245ec308f8107c3a0c94b2e42cd96e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseUnnamedAttrGrp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseUnnamedAttrGrp ::= 'attributes' AttrGrpID '=' '{' AttrValPair+ '}'</p>

<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1505 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseUnnamedGlobal() {#a1567b67aa20b64c63d925dc3a0dc02d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseUnnamedGlobal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseUnnamedGlobal: OptionalVisibility (ALIAS | IFUNC) ... OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass ... -&gt; global variable GlobalID '=' OptionalVisibility (ALIAS | IFUNC) ... GlobalID '=' OptionalLinkage OptionalPreemptionSpecifier OptionalVisibility OptionalDLLStorageClass ... -&gt; global variable</p>

<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseUnnamedType() {#a0f37aa2b76fdb514203aa50fab09fa27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseUnnamedType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseUnnamedType: ::= LocalVarID '=' 'type' type</p>

<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseUseListOrder() {#a4076fafa42ba77bfc5bdf64624ea90c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseUseListOrder (PerFunctionState * PFS=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseUseListOrder ::= 'uselistorder' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ',' UseListOrderIndexes</p>

<p>Declaration at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8765 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseUseListOrderBB() {#a5a729b0ab5e3e4a7f51a1fdb795c12de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseUseListOrderBB ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseUseListOrderBB ::= 'uselistorder_bb' @foo ',' bar ',' UseListOrderIndexes</p>

<p>Declaration at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8782 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseUseListOrderIndexes() {#a9b8d60fcbde9043c0ba28531fef408db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseUseListOrderIndexes (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Indexes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseUseListOrderIndexes ::= '{' uint32 (',' uint32)+ '}'</p>

<p>Declaration at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8722 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseVAArg() {#a8d2005e9bf905aba912ce0eead054433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseVAArg (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, PerFunctionState &amp; PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseVAArg ::= 'va_arg' TypeAndValue ',' <a href="/web-llvm/docs/api/classes/llvm/type">Type</a></p>

<p>Declaration at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7890 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseValID() {#a6dd5c44bbb0785ee35a7bc7298c5cd44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseValID (<a href="/web-llvm/docs/api/structs/llvm/valid">ValID</a> &amp; ID, PerFunctionState * PFS, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ExpectedTy=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseValID - parse an abstract value that doesn't necessarily have a type implied.</p>


<p>For example, if we parse "4" we don't know what integer type it has. The value will later be combined with its type and checked for basic correctness. PFS is used to convert function-local operands of metadata (since metadata operands are not just parsed here but also converted to values). PFS can be null when we are not parsing metadata values inside a function.</p>


<p>Declaration at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 3868 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseValue() {#a8b4c69e44ead55a0425881c29d8c94cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V, PerFunctionState * PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6346 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseValue() {#a12c0505850061d14ec85d47325ee7fd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V, PerFunctionState &amp; PFS)</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseValue() {#a23ddc82b85dad9cb50e5ac714d6532b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::parseValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V, <a href="#a41214230e1d2e66a2b675eeaa0ee2c7f">LocTy</a> &amp; Loc, PerFunctionState &amp; PFS)</td>
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



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### parseValueAsMetadata() {#a08240794a713e167dd0e7f74348f0b8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseValueAsMetadata (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *&amp; MD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; TypeMsg, PerFunctionState * PFS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseValueAsMetadata ::= i32 local ::= i32 @global ::= i32 7</p>

<p>Declaration at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 6080 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseVariableSummary() {#a2fa884a8360986aa8e9154ab45daecec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseVariableSummary (std::string Name, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> GUID, unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VariableSummary ::= 'variable' ':' '(' 'module' ':' ModuleReference ',' GVFlags [',' OptionalRefs]?</p>


<p>')'</p>


<p>Declaration at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9559 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseVFuncId() {#a6e3a92f8adf43b6ee6a2fe415ca8ca74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseVFuncId (<a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a> &amp; VFuncId, IdToIndexMapType &amp; IdToIndexMap, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VFuncId ::= 'vFuncId' ':' '(' (SummaryID | 'guid' ':' UInt64) ',' 'offset' ':' UInt64 ')'.</p>

<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10327 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseVFuncIdList() {#a27e8507d3c21b9b5d132b257240449b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseVFuncIdList (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Kind, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a> &gt; &amp; VFuncIdList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VFuncIdList ::= Kind ':' '(' VFuncId [',' VFuncId]* ')'.</p>

<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 10235 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseVScaleRangeArguments() {#aecb5056352d0199cc950ea9010b0e24f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseVScaleRangeArguments (unsigned &amp; MinValue, unsigned &amp; MaxValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 2730 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### parseWpdRes() {#aca0789c7710ebd17d1595669cccfcbbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::parseWpdRes (<a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> &amp; WPDRes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>WpdRes ::= 'wpdRes' ':' '(' 'kind' ':' 'indir' [',' OptionalResByArg]?</p>


<p>')' ::= 'wpdRes' ':' '(' 'kind' ':' 'singleImpl' ',' 'singleImplName' ':' STRINGCONSTANT ',' [',' OptionalResByArg]? ')' ::= 'wpdRes' ':' '(' 'kind' ':' 'branchFunnel' [',' OptionalResByArg]? ')'</p>


<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 9123 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### resolveFunctionType() {#acd2fccd59dd394590c6d5cab6c18b75d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::resolveFunctionType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; ParamInfo &gt; ArgList, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *&amp; FuncTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 7354 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### restoreParsingState() {#ac681d16991c75c695db1dfde8673eab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLParser::restoreParsingState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a> * Slots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Restore the internal name and slot mappings using the mappings that were created at an earlier parsing stage.</p>

<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### skipModuleSummaryEntry() {#acfe33e52aa5775f62aba99b44372ecb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::skipModuleSummaryEntry ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### sortUseListOrder() {#a84e6297e2c93e3b39efb76285b04cf60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::sortUseListOrder (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Indexes, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 8696 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### tokError() {#a3c2408964745a0e8d69b0ae1dcf21cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::tokError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### validateEndOfIndex() {#aaa12efff8fcbe6a62bf8014b4f45edae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::validateEndOfIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do final validity and basic correctness checks at the end of the index.</p>

<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### validateEndOfModule() {#a1a9a7f6c6652ce5d144a012aa5cc4232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLParser::validateEndOfModule (bool UpgradeDebugInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>validateEndOfModule - Do final validity and basic correctness checks at the end of the module.</p>

<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockAddressPFS {#a77e62957c6607cdbf53ec3cf444417d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerFunctionState* llvm::LLParser::BlockAddressPFS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to per-function state to allow basic blocks to be forward-referenced by blockaddress instructions within the same function.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### Context {#a1b8deb1c6359fa7a3a8995c007f46da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::LLParser::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ForwardRefAliasees {#ae962401d5e156abf775d4024e832d9ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, std::vector&lt;std::pair&lt;AliasSummary *, LocTy&gt; &gt; &gt; llvm::LLParser::ForwardRefAliasees</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ForwardRefAttrGroups {#a8d8d6fd7939b12dd5af5af5defc73d7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;Value*, std::vector&lt;unsigned&gt; &gt; llvm::LLParser::ForwardRefAttrGroups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ForwardRefBlockAddresses {#a9fee7065f9bb3a53990ce6a3dd80aeb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;ValID, std::map&lt;ValID, GlobalValue *&gt; &gt; llvm::LLParser::ForwardRefBlockAddresses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ForwardRefComdats {#a461f347a75dc7881586a9bfbdef889f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string, LocTy&gt; llvm::LLParser::ForwardRefComdats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ForwardRefDSOLocalEquivalentIDs {#a08a954a59489b1503784cadf83574037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;ValID, GlobalValue *&gt; llvm::LLParser::ForwardRefDSOLocalEquivalentIDs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ForwardRefDSOLocalEquivalentNames {#a485a5b2ef004237091c2e6b69a212cf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;ValID, GlobalValue *&gt; llvm::LLParser::ForwardRefDSOLocalEquivalentNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ForwardRefMDNodes {#a1a3f1d73549d693102a8501e995c22df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, std::pair&lt;TempMDTuple, LocTy&gt; &gt; llvm::LLParser::ForwardRefMDNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ForwardRefTypeIds {#aa1992c874d2ded5e67272d72e5fd157a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, std::vector&lt;std::pair&lt;GlobalValue::GUID *, LocTy&gt; &gt; &gt; llvm::LLParser::ForwardRefTypeIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ForwardRefValIDs {#ab5f43ceb88e86acc608903df344b2fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, std::pair&lt;GlobalValue*, LocTy&gt; &gt; llvm::LLParser::ForwardRefValIDs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ForwardRefVals {#aa07607f35d18f486162a126611f1892e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string, std::pair&lt;GlobalValue*, LocTy&gt; &gt; llvm::LLParser::ForwardRefVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ForwardRefValueInfos {#aa9591e8afe030a7bc5c44079de748fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, std::vector&lt;std::pair&lt;ValueInfo *, LocTy&gt; &gt; &gt; llvm::LLParser::ForwardRefValueInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### Index {#a07e3dba6442627cc412f334f4e160250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSummaryIndex* llvm::LLParser::Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### InstsWithTBAATag {#acc212a4cfb8733532dc6c14c3091a295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction*, 64&gt; llvm::LLParser::InstsWithTBAATag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### Lex {#a24e927c277dba845155e4da1675395e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLLexer llvm::LLParser::Lex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### M {#a5c747c27281d840b271d42e7a5400c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* llvm::LLParser::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### ModuleIdMap {#a83670dcf80f0eb6ba99a8bcec1daa3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, StringRef&gt; llvm::LLParser::ModuleIdMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### NamedTypes {#a6bc2eea497b1bdb080f773f5a2d130e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::pair&lt;Type*, LocTy&gt; &gt; llvm::LLParser::NamedTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### NumberedAttrBuilders {#a6057124d00bff7c0940be3fba72903b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, AttrBuilder&gt; llvm::LLParser::NumberedAttrBuilders</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### NumberedMetadata {#a7597d5980742ff874adb56fe3e463a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, TrackingMDNodeRef&gt; llvm::LLParser::NumberedMetadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### NumberedTypes {#a9b0359b7acd0ec4a2ba79fed8c561c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, std::pair&lt;Type*, LocTy&gt; &gt; llvm::LLParser::NumberedTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### NumberedVals {#a2b27ec2aed8bc890d9c9dab1dcadbde3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NumberedValues&lt;GlobalValue *&gt; llvm::LLParser::NumberedVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### NumberedValueInfos {#a97fdaf32f97bdca5c8891618a0640ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ValueInfo&gt; llvm::LLParser::NumberedValueInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### OPLex {#a21fb246023b5db88df9623fb4571ed0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLLexer llvm::LLParser::OPLex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### SeenNewDbgInfoFormat {#a7cb42cc0f2f9eeab3e90c0c11bdee714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::SeenNewDbgInfoFormat = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### SeenOldDbgInfoFormat {#a5fea7ca88f89311d7cb657b3c8c1a17a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::SeenOldDbgInfoFormat = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### Slots {#a55e0a2331371d5d1dea068a8bd5eb641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotMapping* llvm::LLParser::Slots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### SourceFileName {#a3bda931a40d2d0292064e83d561e7826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LLParser::SourceFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### TempDIAssignIDAttachments {#a7606a05aa6b21ba6e544a2098c8afe35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MDNode *, SmallVector&lt;Instruction *, 2&gt; &gt; llvm::LLParser::TempDIAssignIDAttachments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> metadata does not support temporary RAUW so we cannot use the normal metadata forward reference resolution method.</p>


<p>Instead, non-temporary <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> are attached to instructions (recorded here) then replaced later.</p>


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

### UpgradeDebugInfo {#ac41bf6e3f8d1cc14e4c358a307bda9f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLParser::UpgradeDebugInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Only the llvm-as tool may set this to false to bypass UpgradeDebuginfo so it can generate broken bitcode.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">LLParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
