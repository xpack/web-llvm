---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dxil/dxilbitcodewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DXILBitcodeWriter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::dxil::DXILBitcodeWriter { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a908df3831ca94bfdcafa6009374b2be8">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These are manifest constants used by the bitcode writer. <a href="#a908df3831ca94bfdcafa6009374b2be8">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade090ef88b076e918fd2e278692729d5">DXILBitcodeWriter</a> (const Module &amp;M, SmallVectorImpl&lt; char &gt; &amp;Buffer, StringTableBuilder &amp;StrtabBuilder, BitstreamWriter &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a ModuleBitcodeWriter object for the given <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, writing to the provided <span class="doxyComputerOutput">Buffer</span>. <a href="#ade090ef88b076e918fd2e278692729d5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dcf66963c3a9abb47b944fd2ce9f8cc">write</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the current module to the bitstream. <a href="#a8dcf66963c3a9abb47b944fd2ce9f8cc">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca1537b61cb0dcecb4178287a8d388f">writeModuleVersion</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09978ef084c1b204b667747c8a234fb0">writePerModuleGlobalValueSummary</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3b461e1432c37351f20aed5275c5d85">writePerModuleFunctionSummaryRecord</a> (SmallVector&lt; uint64_t, 64 &gt; &amp;NameVals, GlobalValueSummary *Summary, unsigned ValueID, unsigned FSCallsAbbrev, unsigned FSCallsProfileAbbrev, const Function &amp;F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec19805fe5e217f048b5cc93aae5798">writeModuleLevelReferences</a> (const GlobalVariable &amp;V, SmallVector&lt; uint64_t, 64 &gt; &amp;NameVals, unsigned FSModRefsAbbrev, unsigned FSModVTableRefsAbbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c7af57be5dfab69bb7af7d8cd005842">assignValueId</a> (GlobalValue::GUID ValGUID)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7405290d44a7d781df9b5e4411892859">getValueId</a> (GlobalValue::GUID ValGUID)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef27aad717b82d393ee891c1de6d38bc">getValueId</a> (ValueInfo VI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, unsigned &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdcb00a02295004c66cf93f8804db79f">valueIds</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09f647e413c581868ed5a9dc6be15c4a">bitcodeStartBit</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25d8e3de64471704d578645cb9c60bc4">addToStrtab</a> (StringRef Str)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a23728bbdc3dc028099a61394d2cd16">createDILocationAbbrev</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c2da686bc4403468f05a9093a9a1101">createGenericDINodeAbbrev</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af80e7b9882baa93b1b1f77b206d99fb1">writeAttributeGroupTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Begin <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilbitcodewriter">DXILBitcodeWriter</a> Implementation. <a href="#af80e7b9882baa93b1b1f77b206d99fb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af964bfe3490b26299e6ef517a1c45bb6">writeAttributeTable</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed40369d4d3eb6ca6da38a1ab19b3d6">writeTypeTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WriteTypeTable - Write out the type table for a module. <a href="#a9ed40369d4d3eb6ca6da38a1ab19b3d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7905b0f843a465c015dea571cb60c633">writeComdats</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6371b1d9726aaa057f671cdc80f0fbd7">writeValueSymbolTableForwardDecl</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbdff9f93b53f0b8e5380acdd6f3f160">writeModuleInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit top-level description of module, including target triple, inline asm, descriptors for global variables, and function prototype info. <a href="#adbdff9f93b53f0b8e5380acdd6f3f160">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c3cb50b66c254e56c31f48f6a81842">writeValueAsMetadata</a> (const ValueAsMetadata *MD, SmallVectorImpl&lt; uint64_t &gt; &amp;Record)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a47a1fc46b4548f6ed4d08b1f8be93b">writeMDTuple</a> (const MDTuple *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc242e9ae7166af34d18598a766f9f7">writeDILocation</a> (const DILocation *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned &amp;Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42219aff4ef11909934e3ebcce8d65b3">writeGenericDINode</a> (const GenericDINode *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned &amp;Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa100e9d78d5504440630a767f1cd9b51">writeDISubrange</a> (const DISubrange *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a570da5d2e3a02cc5acf71a27dc198">writeDIGenericSubrange</a> (const DIGenericSubrange *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c65a5408a3a77df645d83de77a3a0c">writeDIEnumerator</a> (const DIEnumerator *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae37ad1982a505b134e8c21b618a77760">writeDIBasicType</a> (const DIBasicType *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc26478855314e8b4d72f52164ddc39c">writeDIStringType</a> (const DIStringType *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b4c2e85fc0053f53fa8b712c258249c">writeDIDerivedType</a> (const DIDerivedType *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af517a41610f71438ed9d8c4ef6623701">writeDICompositeType</a> (const DICompositeType *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a328c655adf68b7265341498077254b7c">writeDISubroutineType</a> (const DISubroutineType *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14664e68368357ead59acf3175e91a4c">writeDIFile</a> (const DIFile *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bedfb16c7a0251412622ada52c3c2c6">writeDICompileUnit</a> (const DICompileUnit *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a881b6bcd9f50e816ce9dc0eb3cae78df">writeDISubprogram</a> (const DISubprogram *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1dd9cdf99b8bebfd941abd124523257">writeDILexicalBlock</a> (const DILexicalBlock *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50951891132e5f4b09d6fa176dbc6126">writeDILexicalBlockFile</a> (const DILexicalBlockFile *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea7bca2d265e54f135130f2328fae4ca">writeDICommonBlock</a> (const DICommonBlock *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345070ab1976b9985e1148a769715d9c">writeDINamespace</a> (const DINamespace *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a387e1ad306f1fe3b00ff80f888ec798e">writeDIMacro</a> (const DIMacro *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae08d4a813a897f979b9bf2b42402ef">writeDIMacroFile</a> (const DIMacroFile *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2873507df343e1d341e98d0572d97071">writeDIArgList</a> (const DIArgList *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9b1515f3350e3cd4051b98590fc1af1">writeDIAssignID</a> (const DIAssignID *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9742b8ffa979e5578537fa305ea738b3">writeDIModule</a> (const DIModule *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a621ef043e5b8f3891f560685855562">writeDITemplateTypeParameter</a> (const DITemplateTypeParameter *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd4cf82a3e3eac281e94ac73f7377444">writeDITemplateValueParameter</a> (const DITemplateValueParameter *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a500e3643be057f39db420124651e7cf0">writeDIGlobalVariable</a> (const DIGlobalVariable *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad339fa47c3207dbadd609221dfbcbe8f">writeDILocalVariable</a> (const DILocalVariable *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e7e505194f9021d55f4b4cd8427785e">writeDILabel</a> (const DILabel *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb82c753b9011af96b59197a117101c1">writeDIExpression</a> (const DIExpression *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa93fe8d1ff0550875263a735c31e4889">writeDIGlobalVariableExpression</a> (const DIGlobalVariableExpression *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9775b4859bd37b37e627cddc1a0d6e69">writeDIObjCProperty</a> (const DIObjCProperty *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e406da20e876251902227dd9212d46b">writeDIImportedEntity</a> (const DIImportedEntity *N, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, unsigned Abbrev)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae45bff51d0196cabede09b4a22081b9e">createNamedMetadataAbbrev</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b4e08789bd59cbbc4f410d6c40547f1">writeNamedMetadata</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Record)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237730478b0633f9df25c86685cc028d">createMetadataStringsAbbrev</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2509fecff8a4b010d75bfcbd8d99d548">writeMetadataStrings</a> (ArrayRef&lt; const Metadata * &gt; Strings, SmallVectorImpl&lt; uint64_t &gt; &amp;Record)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae753f5e018f8ce269008271e44149987">writeMetadataRecords</a> (ArrayRef&lt; const Metadata * &gt; MDs, SmallVectorImpl&lt; uint64_t &gt; &amp;Record, std::vector&lt; unsigned &gt; *MDAbbrevs=nullptr, std::vector&lt; uint64_t &gt; *IndexPos=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46180e838f5c0d67bc7f8d668e356c29">writeModuleMetadata</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1790ed8c546d7104cbdea06f4c489316">writeFunctionMetadata</a> (const Function &amp;F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65189cbd317d37bb75fed41c95799f33">writeFunctionMetadataAttachment</a> (const Function &amp;F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaddf13a3e383680a93ac5d32bf2ab51">pushGlobalMetadataAttachment</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Record, const GlobalObject &amp;GO)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e2511d5d3e5454be32920d87ecc864">writeModuleMetadataKinds</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7398b3c8ebba1b9c3e868a87aefdc926">writeOperandBundleTags</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3844acdf079f01349a695741b74c0c3e">writeSyncScopeNames</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a489a59d24e884b8813fd5bfb15a13ff8">writeConstants</a> (unsigned FirstVal, unsigned LastVal, bool isGlobal)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3b5f3db24882b22fb47d1fa4902d13">writeModuleConstants</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8e00c560f86ba453b17752abc24d22">pushValueAndType</a> (const Value *V, unsigned InstID, SmallVectorImpl&lt; unsigned &gt; &amp;Vals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>pushValueAndType - The file has to encode both the value and type id for many values, because we need to know what type to create for forward references. <a href="#ade8e00c560f86ba453b17752abc24d22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4451b4b80f70be225b651a4200119ee6">writeOperandBundles</a> (const CallBase &amp;CB, unsigned InstID)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42353da226dc111836e56ee212a983df">pushValue</a> (const Value *V, unsigned InstID, SmallVectorImpl&lt; unsigned &gt; &amp;Vals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>pushValue - Like pushValueAndType, but where the type of the value is omitted (perhaps it was already encoded in an earlier operand). <a href="#a42353da226dc111836e56ee212a983df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192848a728c9dd8d0f142ac143cb745e">pushValueSigned</a> (const Value *V, unsigned InstID, SmallVectorImpl&lt; uint64_t &gt; &amp;Vals)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae0e2e1f16b19832254916dd6d61f316">writeInstruction</a> (const Instruction &amp;I, unsigned InstID, SmallVectorImpl&lt; unsigned &gt; &amp;Vals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WriteInstruction - Emit an instruction. <a href="#aae0e2e1f16b19832254916dd6d61f316">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2bf0e1ea17ad86fa74b246a5fcdec99">writeFunctionLevelValueSymbolTable</a> (const ValueSymbolTable &amp;VST)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad451c71ad48ad823198871e8d2dc64f7">writeGlobalValueSymbolTable</a> (DenseMap&lt; const Function *, uint64_t &gt; &amp;FunctionToBitcodeIndex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60057add960ac3ca14dc5e010f27552d">writeFunction</a> (const Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a function body to the module stream. <a href="#a60057add960ac3ca14dc5e010f27552d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20bccf4f828e01335ee8a1ae92ce2ad5">writeBlockInfo</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a183bde1e5e2ae2388e237378b92a47b8">getEncodedSyncScopeID</a> (SyncScope::ID SSID)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadab4490e94616b6a869ac15810e686d">getEncodedAlign</a> (MaybeAlign Alignment)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa873787d313fb0458049a677ce6d5a42">getTypeID</a> (Type *T, const Value *V=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40cd7e358fd7baf0980dc18a74984c61">getGlobalObjectValueTypeID</a> (Type *T, const GlobalObject *G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getGlobalObjectValueTypeID - returns the element type for a <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> <a href="#a40cd7e358fd7baf0980dc18a74984c61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad98192c1cffbc99311fa21cf26db22c4">I8Ty</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1d786722cc34cfa95cf88cc8c579a69">I8PtrTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa52510012d3d40a0b4a8155f1af1af6">Stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The stream created and owned by the client. <a href="#afa52510012d3d40a0b4a8155f1af1af6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab334b62af66fd1350c1944b8038f685a">StrtabBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56dfa4d168131d1c5fbf38200683d691">M</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to write to bitcode. <a href="#a56dfa4d168131d1c5fbf38200683d691">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dxil/valueenumerator">ValueEnumerator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94cdb5845ecbbd80cc63dc874cdfb351">VE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerates ids for all values in the module. <a href="#a94cdb5845ecbbd80cc63dc874cdfb351">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32b4a7831dc4cd22fc6d50a985d18425">GUIDToValueIdMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map that holds the correspondence between GUIDs in the summary index, that came from indirect call profiles, and a value id generated by this class to use in the VST and summary block records. <a href="#a32b4a7831dc4cd22fc6d50a985d18425">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69b73445c6db9d0e8cc06e9eccbab15">GlobalValueId</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracks the last value id recorded in the GUIDToValueMap. <a href="#ae69b73445c6db9d0e8cc06e9eccbab15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3584f9010f59c3e9a55719f3af8eea3d">VSTOffsetPlaceholder</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Saves the offset of the VSTOffset record that must eventually be backpatched with the offset of the actual VST. <a href="#a3584f9010f59c3e9a55719f3af8eea3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81e5194d91eb08a6047a20f3a3e4d062">Buffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the buffer allocated by caller for bitcode writing. <a href="#a81e5194d91eb08a6047a20f3a3e4d062">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedb006f6edfb70db5d11ca6435be8b91">BitcodeStartBit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The start bit of the identification block. <a href="#aedb006f6edfb70db5d11ca6435be8b91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a57d4be532c191d9bb111cecdd1a63709">PointerTypeMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567063cfc8d9e0ccc8e48d7bd21a952b">PointerMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This maps values to their typed pointers. <a href="#a567063cfc8d9e0ccc8e48d7bd21a952b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617848d18948dae1936150f76db98011">getAttrKindEncoding</a> (Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56bf1b8486ba52a5e85a2613e8e10c52">writeStringRecord</a> (BitstreamWriter &amp;Stream, unsigned Code, StringRef Str, unsigned AbbrevToUse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f244a8578b0143781cb54fa6750f926">writeIdentificationBlock</a> (BitstreamWriter &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9973792296d07d67ee9c2a6788dc7bc4">emitSignedInt64</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Vals, uint64_t V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14a689ea0e6b8f399585adc4aec8451d">emitWideAPInt</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Vals, const APInt &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20f68aa968285253642b3df50d4224a">getEncodedComdatSelectionKind</a> (const Comdat &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f86a215f525703479598846b589a41">getEncodedLinkage</a> (const GlobalValue::LinkageTypes Linkage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a586414510277aa6c4ef316c8644518a3">getEncodedLinkage</a> (const GlobalValue &amp;GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82c3d62e3e31689738ff29dc4c2bceb5">getEncodedVisibility</a> (const GlobalValue &amp;GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27deb340295be3eb8c6fa8b611944e6f">getEncodedThreadLocalMode</a> (const GlobalValue &amp;GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ff87aa2d11681bf60bcbe10ef2f2ea4">getEncodedDLLStorageClass</a> (const GlobalValue &amp;GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f7509a746eff107351ddedb7ccf871">getEncodedCastOpcode</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Begin dxil::BitcodeWriterBase Implementation. <a href="#a55f7509a746eff107351ddedb7ccf871">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb5965073f5357caf8cfd62d414e6c0">getEncodedUnaryOpcode</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a993b26f7f4142aa72f542d25581c7201">getEncodedBinaryOpcode</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85e76fce8fe9aed9406ed2d9b6f671e">getEncodedRMWOperation</a> (AtomicRMWInst::BinOp Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7541865486d11f84653ce3dc7d5a1618">getEncodedOrdering</a> (AtomicOrdering Ordering)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55de374d4280b901de2e6b0168f4ac9">getOptimizationFlags</a> (const Value *V)</td>
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


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a908df3831ca94bfdcafa6009374b2be8}

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

<p>These are manifest constants used by the bitcode writer.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST_ENTRY_8_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8a3e62089b347f0d3d87fef5dcb9846881"></a></td>
<td class="doxyEnumItemDescription"> (= bitc::FIRST_APPLICATION_ABBREV)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST_ENTRY_7_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8a8b22990b466ada58f5856325ac286965"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST_ENTRY_6_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8ac434717e3f6abf6c925cac05e3474650"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST_BBENTRY_6_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8ac09ccbd04089abe0afed77c29f8176c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANTS_SETTYPE_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8aaf186c51bed72533a15514252b75e110"></a></td>
<td class="doxyEnumItemDescription"> (= bitc::FIRST_APPLICATION_ABBREV)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANTS_INTEGER_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8aca472a470ea52cf0f25ea3c005a22888"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANTS_CE_CAST_Abbrev<a id="a908df3831ca94bfdcafa6009374b2be8aa2f48b746550a7f736528a50bafaabf7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANTS_NULL_Abbrev<a id="a908df3831ca94bfdcafa6009374b2be8aad2c2dcad17970199f39b5409efd1739"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_LOAD_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8aa94bb807ca829ccf4f7231762fda9ca6"></a></td>
<td class="doxyEnumItemDescription"> (= bitc::FIRST_APPLICATION_ABBREV)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_BINOP_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8ab24471e69f77b649e7940cc0b913c323"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_BINOP_FLAGS_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8a2284a20573ed27d68bca2162632ffbca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_CAST_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8af9f13083713b299b3cb64981c3b0c7e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_RET_VOID_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8a3432b910ad852d05e61595d9b6856760"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_RET_VAL_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8af5945fb4294621095dd60dfffac163a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_UNREACHABLE_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8a57f95b1cd5ab936f552fbf44e60b797d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNCTION_INST_GEP_ABBREV<a id="a908df3831ca94bfdcafa6009374b2be8aacf7954f8938e34315cf75cf568cafc6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>They do not need to be kept in sync with the reader, but need to be consistent within this file.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DXILBitcodeWriter() {#ade090ef88b076e918fd2e278692729d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dxil::DXILBitcodeWriter::DXILBitcodeWriter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Buffer, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; StrtabBuilder, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream)</td>
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

<p>Constructs a ModuleBitcodeWriter object for the given <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, writing to the provided <span class="doxyComputerOutput">Buffer</span>.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### write() {#a8dcf66963c3a9abb47b944fd2ce9f8cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::write ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the current module to the bitstream.</p>


<p>WriteModule - Emit the specified module to the bitstream.</p>


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da31e5f441b78348934094a9dde0a326e2">llvm::bitc::MODULE_BLOCK_ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/bitcodewriter/#a0d275df8548c45a0aa1ae5031235a996">llvm::dxil::BitcodeWriter::writeModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addToStrtab() {#a25d8e3de64471704d578645cb9c60bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::dxil::DXILBitcodeWriter::addToStrtab (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### assignValueId() {#a6c7af57be5dfab69bb7af7d8cd005842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::assignValueId (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> ValGUID)</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### bitcodeStartBit() {#a09f647e413c581868ed5a9dc6be15c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dxil::DXILBitcodeWriter::bitcodeStartBit ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### createDILocationAbbrev() {#a5a23728bbdc3dc028099a61394d2cd16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::createDILocationAbbrev ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### createGenericDINodeAbbrev() {#a9c2da686bc4403468f05a9093a9a1101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::createGenericDINodeAbbrev ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### createMetadataStringsAbbrev() {#a237730478b0633f9df25c86685cc028d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::createMetadataStringsAbbrev ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### createNamedMetadataAbbrev() {#ae45bff51d0196cabede09b4a22081b9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dxil::DXILBitcodeWriter::createNamedMetadataAbbrev ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### getEncodedAlign() {#aadab4490e94616b6a869ac15810e686d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dxil::DXILBitcodeWriter::getEncodedAlign (<a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Alignment)</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### getEncodedSyncScopeID() {#a183bde1e5e2ae2388e237378b92a47b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dxil::DXILBitcodeWriter::getEncodedSyncScopeID (<a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID)</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### getGlobalObjectValueTypeID() {#a40cd7e358fd7baf0980dc18a74984c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getGlobalObjectValueTypeID (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getGlobalObjectValueTypeID - returns the element type for a <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a></p>


<p><a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> types are saved by <a href="/web-llvm/docs/api/namespaces/llvm/dxil/pointertypeanalysis">PointerTypeAnalysis</a> as pointers to the <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a>, but in the bitcode writer we need the pointer element type.</p>


<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### getTypeID() {#aa873787d313fb0458049a677ce6d5a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getTypeID (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### getValueId() {#a7405290d44a7d781df9b5e4411892859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dxil::DXILBitcodeWriter::getValueId (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> ValGUID)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### getValueId() {#aef27aad717b82d393ee891c1de6d38bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dxil::DXILBitcodeWriter::getValueId (<a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> VI)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### pushGlobalMetadataAttachment() {#adaddf13a3e383680a93ac5d32bf2ab51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::pushGlobalMetadataAttachment (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> &amp; GO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### pushValue() {#a42353da226dc111836e56ee212a983df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::pushValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned InstID, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Vals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>pushValue - Like pushValueAndType, but where the type of the value is omitted (perhaps it was already encoded in an earlier operand).</p>

<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### pushValueAndType() {#ade8e00c560f86ba453b17752abc24d22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DXILBitcodeWriter::pushValueAndType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned InstID, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Vals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>pushValueAndType - The file has to encode both the value and type id for many values, because we need to know what type to create for forward references.</p>


<p>However, most operands are not forward references, so this type field is not needed.</p>


<p>This function adds V's value <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to Vals. If the value <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> is higher than the instruction <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, then it is a forward reference, and it also includes the type <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. The value <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> that is written is encoded relative to the InstID.</p>


<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### pushValueSigned() {#a192848a728c9dd8d0f142ac143cb745e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::pushValueSigned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned InstID, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Vals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### valueIds() {#abdcb00a02295004c66cf93f8804db79f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt; GlobalValue::GUID, unsigned &gt; &amp; llvm::dxil::DXILBitcodeWriter::valueIds ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeAttributeGroupTable() {#af80e7b9882baa93b1b1f77b206d99fb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeAttributeGroupTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Begin <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilbitcodewriter">DXILBitcodeWriter</a> Implementation.</p>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeAttributeTable() {#af964bfe3490b26299e6ef517a1c45bb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeAttributeTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeBlockInfo() {#a20bccf4f828e01335ee8a1ae92ce2ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeBlockInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeComdats() {#a7905b0f843a465c015dea571cb60c633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeComdats ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeConstants() {#a489a59d24e884b8813fd5bfb15a13ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeConstants (unsigned FirstVal, unsigned LastVal, bool isGlobal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIArgList() {#a2873507df343e1d341e98d0572d97071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeDIArgList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diarglist">DIArgList</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIAssignID() {#ac9b1515f3350e3cd4051b98590fc1af1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeDIAssignID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIBasicType() {#ae37ad1982a505b134e8c21b618a77760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDIBasicType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDICommonBlock() {#aea7bca2d265e54f135130f2328fae4ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeDICommonBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicommonblock">DICommonBlock</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDICompileUnit() {#a6bedfb16c7a0251412622ada52c3c2c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDICompileUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDICompositeType() {#af517a41610f71438ed9d8c4ef6623701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDICompositeType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIDerivedType() {#a2b4c2e85fc0053f53fa8b712c258249c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDIDerivedType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIEnumerator() {#ac3c65a5408a3a77df645d83de77a3a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDIEnumerator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dienumerator">DIEnumerator</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIExpression() {#aeb82c753b9011af96b59197a117101c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDIExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIFile() {#a14664e68368357ead59acf3175e91a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDIFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIGenericSubrange() {#ac6a570da5d2e3a02cc5acf71a27dc198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeDIGenericSubrange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/digenericsubrange">DIGenericSubrange</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIGlobalVariable() {#a500e3643be057f39db420124651e7cf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDIGlobalVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable">DIGlobalVariable</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIGlobalVariableExpression() {#aa93fe8d1ff0550875263a735c31e4889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeDIGlobalVariableExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression">DIGlobalVariableExpression</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIImportedEntity() {#a9e406da20e876251902227dd9212d46b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDIImportedEntity (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diimportedentity">DIImportedEntity</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDILabel() {#a5e7e505194f9021d55f4b4cd8427785e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeDILabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDILexicalBlock() {#af1dd9cdf99b8bebfd941abd124523257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDILexicalBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock">DILexicalBlock</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDILexicalBlockFile() {#a50951891132e5f4b09d6fa176dbc6126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDILexicalBlockFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockfile">DILexicalBlockFile</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDILocalVariable() {#ad339fa47c3207dbadd609221dfbcbe8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDILocalVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDILocation() {#aefc242e9ae7166af34d18598a766f9f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDILocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned &amp; Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIMacro() {#a387e1ad306f1fe3b00ff80f888ec798e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeDIMacro (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dimacro">DIMacro</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIMacroFile() {#a3ae08d4a813a897f979b9bf2b42402ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeDIMacroFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dimacrofile">DIMacroFile</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIModule() {#a9742b8ffa979e5578537fa305ea738b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDIModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dimodule">DIModule</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDINamespace() {#a345070ab1976b9985e1148a769715d9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDINamespace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinamespace">DINamespace</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIObjCProperty() {#a9775b4859bd37b37e627cddc1a0d6e69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDIObjCProperty (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diobjcproperty">DIObjCProperty</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDIStringType() {#abc26478855314e8b4d72f52164ddc39c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeDIStringType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDISubprogram() {#a881b6bcd9f50e816ce9dc0eb3cae78df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDISubprogram (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDISubrange() {#aa100e9d78d5504440630a767f1cd9b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDISubrange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubrange">DISubrange</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDISubroutineType() {#a328c655adf68b7265341498077254b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDISubroutineType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype">DISubroutineType</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDITemplateTypeParameter() {#a0a621ef043e5b8f3891f560685855562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDITemplateTypeParameter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditemplatetypeparameter">DITemplateTypeParameter</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeDITemplateValueParameter() {#abd4cf82a3e3eac281e94ac73f7377444}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeDITemplateValueParameter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditemplatevalueparameter">DITemplateValueParameter</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeFunction() {#a60057add960ac3ca14dc5e010f27552d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a function body to the module stream.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeFunctionLevelValueSymbolTable() {#ae2bf0e1ea17ad86fa74b246a5fcdec99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeFunctionLevelValueSymbolTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuesymboltable">ValueSymbolTable</a> &amp; VST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeFunctionMetadata() {#a1790ed8c546d7104cbdea06f4c489316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeFunctionMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeFunctionMetadataAttachment() {#a65189cbd317d37bb75fed41c95799f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeFunctionMetadataAttachment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeGenericDINode() {#a42219aff4ef11909934e3ebcce8d65b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeGenericDINode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/genericdinode">GenericDINode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned &amp; Abbrev)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeGlobalValueSymbolTable() {#ad451c71ad48ad823198871e8d2dc64f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeGlobalValueSymbolTable (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, uint64_t &gt; &amp; FunctionToBitcodeIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeInstruction() {#aae0e2e1f16b19832254916dd6d61f316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, unsigned InstID, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Vals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>WriteInstruction - Emit an instruction.</p>

<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeMDTuple() {#a0a47a1fc46b4548f6ed4d08b1f8be93b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeMDTuple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, unsigned Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeMetadataRecords() {#ae753f5e018f8ce269008271e44149987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeMetadataRecords (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; MDs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, std::vector&lt; unsigned &gt; * MDAbbrevs=nullptr, std::vector&lt; uint64_t &gt; * IndexPos=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeMetadataStrings() {#a2509fecff8a4b010d75bfcbd8d99d548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeMetadataStrings (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Strings, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeModuleConstants() {#a4f3b5f3db24882b22fb47d1fa4902d13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeModuleConstants ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeModuleInfo() {#adbdff9f93b53f0b8e5380acdd6f3f160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeModuleInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit top-level description of module, including target triple, inline asm, descriptors for global variables, and function prototype info.</p>


<p>Returns the bit offset to backpatch with the location of the real VST.</p>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeModuleLevelReferences() {#a1ec19805fe5e217f048b5cc93aae5798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeModuleLevelReferences (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t, 64 &gt; &amp; NameVals, unsigned FSModRefsAbbrev, unsigned FSModVTableRefsAbbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeModuleMetadata() {#a46180e838f5c0d67bc7f8d668e356c29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeModuleMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeModuleMetadataKinds() {#a92e2511d5d3e5454be32920d87ecc864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeModuleMetadataKinds ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeModuleVersion() {#acca1537b61cb0dcecb4178287a8d388f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeModuleVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeNamedMetadata() {#a3b4e08789bd59cbbc4f410d6c40547f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeNamedMetadata (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeOperandBundles() {#a4451b4b80f70be225b651a4200119ee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeOperandBundles (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, unsigned InstID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeOperandBundleTags() {#a7398b3c8ebba1b9c3e868a87aefdc926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeOperandBundleTags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writePerModuleFunctionSummaryRecord() {#aa3b461e1432c37351f20aed5275c5d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writePerModuleFunctionSummaryRecord (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t, 64 &gt; &amp; NameVals, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> * Summary, unsigned ValueID, unsigned FSCallsAbbrev, unsigned FSCallsProfileAbbrev, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writePerModuleGlobalValueSummary() {#a09978ef084c1b204b667747c8a234fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writePerModuleGlobalValueSummary ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeSyncScopeNames() {#a3844acdf079f01349a695741b74c0c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeSyncScopeNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeTypeTable() {#a9ed40369d4d3eb6ca6da38a1ab19b3d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeTypeTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>WriteTypeTable - Write out the type table for a module.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeValueAsMetadata() {#a86c3cb50b66c254e56c31f48f6a81842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeValueAsMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata">ValueAsMetadata</a> * MD, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeValueSymbolTableForwardDecl() {#a6371b1d9726aaa057f671cdc80f0fbd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeValueSymbolTableForwardDecl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BitcodeStartBit {#aedb006f6edfb70db5d11ca6435be8b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dxil::DXILBitcodeWriter::BitcodeStartBit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The start bit of the identification block.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### Buffer {#a81e5194d91eb08a6047a20f3a3e4d062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt;char&gt;&amp; llvm::dxil::DXILBitcodeWriter::Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the buffer allocated by caller for bitcode writing.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### GlobalValueId {#ae69b73445c6db9d0e8cc06e9eccbab15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dxil::DXILBitcodeWriter::GlobalValueId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tracks the last value id recorded in the GUIDToValueMap.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### GUIDToValueIdMap {#a32b4a7831dc4cd22fc6d50a985d18425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;GlobalValue::GUID, unsigned&gt; llvm::dxil::DXILBitcodeWriter::GUIDToValueIdMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map that holds the correspondence between GUIDs in the summary index, that came from indirect call profiles, and a value id generated by this class to use in the VST and summary block records.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### I8PtrTy {#ae1d786722cc34cfa95cf88cc8c579a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::dxil::DXILBitcodeWriter::I8PtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### I8Ty {#ad98192c1cffbc99311fa21cf26db22c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::dxil::DXILBitcodeWriter::I8Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### M {#a56dfa4d168131d1c5fbf38200683d691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module&amp; llvm::dxil::DXILBitcodeWriter::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to write to bitcode.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### PointerMap {#a567063cfc8d9e0ccc8e48d7bd21a952b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerTypeMap llvm::dxil::DXILBitcodeWriter::PointerMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This maps values to their typed pointers.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### Stream {#afa52510012d3d40a0b4a8155f1af1af6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamWriter&amp; llvm::dxil::DXILBitcodeWriter::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The stream created and owned by the client.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### StrtabBuilder {#ab334b62af66fd1350c1944b8038f685a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder&amp; llvm::dxil::DXILBitcodeWriter::StrtabBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### VE {#a94cdb5845ecbbd80cc63dc874cdfb351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueEnumerator llvm::dxil::DXILBitcodeWriter::VE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enumerates ids for all values in the module.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

### VSTOffsetPlaceholder {#a3584f9010f59c3e9a55719f3af8eea3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dxil::DXILBitcodeWriter::VSTOffsetPlaceholder = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Saves the offset of the VSTOffset record that must eventually be backpatched with the offset of the actual VST.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### emitSignedInt64() {#a9973792296d07d67ee9c2a6788dc7bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::emitSignedInt64 (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Vals, uint64_t V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a14a689ea0e6b8f399585adc4aec8451d">emitWideAPInt</a>.</p>

</div>
</div>

### emitWideAPInt() {#a14a689ea0e6b8f399585adc4aec8451d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::emitWideAPInt (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Vals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a9973792296d07d67ee9c2a6788dc7bc4">emitSignedInt64</a>.</p>

</div>
</div>

### getAttrKindEncoding() {#a617848d18948dae1936150f76db98011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DXILBitcodeWriter::getAttrKindEncoding (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3abadb9d66c19008e4ddb353c55d2c28e2">llvm::bitc::ATTR_KIND_ALIGNMENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ac21e10518d20fe0353e65cca06bd5256">llvm::bitc::ATTR_KIND_ALWAYS_INLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a86f312d48859fc97a288d8718d4e4e81">llvm::bitc::ATTR_KIND_BUILTIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa3b7dab5234bc2c00ecd7e64878b715d">llvm::bitc::ATTR_KIND_BY_VAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6b5c1960ea5bf27bae724fbe40458671">llvm::bitc::ATTR_KIND_COLD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a3b0c92f3637b859b97dd9575a33ffec9">llvm::bitc::ATTR_KIND_CONVERGENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a94f778cea4955c8d871aa0ebc22b4852">llvm::bitc::ATTR_KIND_DEREFERENCEABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aaec534c7d966b2ce46814f56cee8d88a">llvm::bitc::ATTR_KIND_DEREFERENCEABLE_OR_NULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ab90bb54c98fe726dfded55b337f3cf71">llvm::bitc::ATTR_KIND_IN_ALLOCA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ab535e133afc06aad0ae2a4cd2a3ba5b2">llvm::bitc::ATTR_KIND_IN_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a554f2b13f875de1d1b91fae8f22f1219">llvm::bitc::ATTR_KIND_INLINE_HINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad87194f39c5d544c6e47d387fad0087d">llvm::bitc::ATTR_KIND_JUMP_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a1a3eec7201b20fd0a7be025a2c9c4325">llvm::bitc::ATTR_KIND_MIN_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a458ace7cc504125aa2a1d7160c41e7d4">llvm::bitc::ATTR_KIND_NAKED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4e8e90d675a52048aa4b579214515238">llvm::bitc::ATTR_KIND_NEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad330adbe19c74c6c37c35f4f5e796bc6">llvm::bitc::ATTR_KIND_NO_ALIAS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2f56428e2de63871e29676305d87de09">llvm::bitc::ATTR_KIND_NO_BUILTIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2107a048bcc160f3ff3266424324ea31">llvm::bitc::ATTR_KIND_NO_CAPTURE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a920b3cacbba0ced6115f2566900e127d">llvm::bitc::ATTR_KIND_NO_DUPLICATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2efc67c46821e4185ae5480eb9dd26cd">llvm::bitc::ATTR_KIND_NO_IMPLICIT_FLOAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3adc9ed5109d2f0dca6fdd2b4bd83c41f7">llvm::bitc::ATTR_KIND_NO_INLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aaa665c4d4c4bc24191c6d60ae71fe62e">llvm::bitc::ATTR_KIND_NO_RED_ZONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a59af608118cf63c82feeb91c9d88b6e2">llvm::bitc::ATTR_KIND_NO_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a05dd5faacf5c7eb49825debc35136169">llvm::bitc::ATTR_KIND_NO_UNWIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a93538315516b14f95e92df987821a58a">llvm::bitc::ATTR_KIND_NON_LAZY_BIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a57d48f7ace267b453bc4d3ad164e58fb">llvm::bitc::ATTR_KIND_NON_NULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a10ccf7458de7661ed59552aa375f91e8">llvm::bitc::ATTR_KIND_OPTIMIZE_FOR_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa695e2248b1cb68eb1afcdc2c5d62491">llvm::bitc::ATTR_KIND_OPTIMIZE_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a974c5448b13d159116dfa73138e2058c">llvm::bitc::ATTR_KIND_READ_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3abac7a26689aa32f57183deb05ff4e8b7">llvm::bitc::ATTR_KIND_READ_ONLY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4d40d2b7ab76139b227d085040438acf">llvm::bitc::ATTR_KIND_RETURNED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6321311fb493fcbb0fbf655bda813424">llvm::bitc::ATTR_KIND_RETURNS_TWICE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa08af93fce49bf40ea23e92f7fd99b43">llvm::bitc::ATTR_KIND_S_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a100c3c2639fc32a8d64953a2c29741a5">llvm::bitc::ATTR_KIND_SAFESTACK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2e2b64c82183308aa47d372943092e39">llvm::bitc::ATTR_KIND_SANITIZE_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a063fce6939dfcc85c3d919cbb90cdbe1">llvm::bitc::ATTR_KIND_SANITIZE_MEMORY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3af4da5ef4d5aada8b57baf7b42330d168">llvm::bitc::ATTR_KIND_SANITIZE_THREAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4d708f6ef22af69a714124a9e6d27a29">llvm::bitc::ATTR_KIND_STACK_ALIGNMENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a02985b5b9b00d8fcf0c3456548704f89">llvm::bitc::ATTR_KIND_STACK_PROTECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a52eaba8bee5d2693ac99f44de939c95f">llvm::bitc::ATTR_KIND_STACK_PROTECT_REQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a05f5e41019f7c20785c7a657d9f8158c">llvm::bitc::ATTR_KIND_STACK_PROTECT_STRONG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a1a17ef11f6af6c1c96c256a885d2bba7">llvm::bitc::ATTR_KIND_STRUCT_RET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa1ee732e66faee6f738611e8af19ba32">llvm::bitc::ATTR_KIND_UW_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a656d32cce3f0da0c87a066dce0a9ae0f">llvm::bitc::ATTR_KIND_Z_EXT</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eaa108685538d49543443a0ce281efd1d8">llvm::Attribute::EmptyKey</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eadf64174102f26dd4fd9d79cc93ddee1b">llvm::Attribute::EndAttrKinds</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea3e672d8a791835da7d662b61f79590a6">llvm::Attribute::TombstoneKey</a>.</p>

</div>
</div>

### getEncodedBinaryOpcode() {#a993b26f7f4142aa72f542d25581c7201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getEncodedBinaryOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a68d9d8c75aa2cbd98cc3cd6088cd88c3">llvm::bitc::BINOP_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1acecfe220fcf28ba017208977312a468c">llvm::bitc::BINOP_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a9a30fed92fd54e316fd32e7e745aeb14">llvm::bitc::BINOP_ASHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a9ec979797d756b39ae37a5f2e25a0d38">llvm::bitc::BINOP_LSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1aa4396fd4122548b531cc7177512b139e">llvm::bitc::BINOP_MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a9b125c378940a11c60ad335b0e60b1a2">llvm::bitc::BINOP_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1aa4e1b66237a655ae124026c28b26d481">llvm::bitc::BINOP_SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a01aa051969198a4085e944234de2446e">llvm::bitc::BINOP_SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1ac799944d2a5b7b91210b803504e77319">llvm::bitc::BINOP_SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1af044d7456abdac4e41aef374cbb43e12">llvm::bitc::BINOP_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a6fc7d38cbdd784e6f2573ba865138210">llvm::bitc::BINOP_UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a26868218c32dc434e202a4d694ad3f45">llvm::bitc::BINOP_UREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1ac6a71c3796edcf421edd6fadb028be68">llvm::bitc::BINOP_XOR</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getEncodedCastOpcode() {#a55f7509a746eff107351ddedb7ccf871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getEncodedCastOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Begin dxil::BitcodeWriterBase Implementation.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ab8be0ead019884e9180369dcf5ca0470">llvm::bitc::CAST_ADDRSPACECAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a07f83ec620595d592fb799d051ac6e75">llvm::bitc::CAST_BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ab585d6900abdafe339c6e9c910035859">llvm::bitc::CAST_FPEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a2d6fc7cca02f499939b68491dff00f58">llvm::bitc::CAST_FPTOSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a84dd2da5c7f3314061ca10f524e7dcb0">llvm::bitc::CAST_FPTOUI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ac7c030dde4055cefd0471ef8fb27038d">llvm::bitc::CAST_FPTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078aaa14daa58dc521dbc0ef0a696aa9e6dd">llvm::bitc::CAST_INTTOPTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ad441909766521e384654c38484c6f169">llvm::bitc::CAST_PTRTOINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078aacc1fb2c439b83d10dd250ff5a2b93f3">llvm::bitc::CAST_SEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a9eaca2882fcf0ec475854e8e5c2279e8">llvm::bitc::CAST_SITOFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078aa1a60e212be26cd7a84d0218675285c2">llvm::bitc::CAST_TRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a0aa29b41007b5fbfce2da261d9816978">llvm::bitc::CAST_UITOFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ab1d860827fec09b9116e81923e3f20aa">llvm::bitc::CAST_ZEXT</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getEncodedComdatSelectionKind() {#ae20f68aa968285253642b3df50d4224a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getEncodedComdatSelectionKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> &amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be">llvm::Comdat::Any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba228d51974aa5c21ba52010a40302a0fc">llvm::bitc::COMDAT_SELECTION_KIND_ANY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba8cfeeb1451c75f879a6876b6beaf6c6d">llvm::bitc::COMDAT_SELECTION_KIND_EXACT_MATCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba10c8fffe9e95a186479d54d05cb03507">llvm::bitc::COMDAT_SELECTION_KIND_LARGEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266baa4e0a5bb065b0f0330ec4a9b80b47ca6">llvm::bitc::COMDAT_SELECTION_KIND_NO_DUPLICATES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba78a05db06e72b074e5ff734665534e49">llvm::bitc::COMDAT_SELECTION_KIND_SAME_SIZE</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035acceb065ea69a5e06e80bd6ceddd7b9a7">llvm::Comdat::ExactMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a2444b05a47619decc80c2ce0cc224dc8">llvm::Comdat::Largest</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035ab2d0d4bc9ba11b7324f5ffc20a9dc37a">llvm::Comdat::NoDeduplicate</a> and <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8b148d3d05688ddb23b7abb81527b7ce">llvm::Comdat::SameSize</a>.</p>

</div>
</div>

### getEncodedDLLStorageClass() {#a6ff87aa2d11681bf60bcbe10ef2f2ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getEncodedDLLStorageClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a5354f0f932438b7ec4d5d82d4ec1ae22">llvm::GlobalValue::DefaultStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a81819441fb6de420d4290ac79aaf9dc0">llvm::GlobalValue::DLLExportStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8aadc8e43e72669932581b5243b4b444b6">llvm::GlobalValue::DLLImportStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af09a662b4e302d0683d0fe9dc2a9335f">llvm::GlobalValue::getDLLStorageClass</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getEncodedLinkage() {#a80f86a215f525703479598846b589a41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getEncodedLinkage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> Linkage)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca96ad6314ba9210b223b93dc3e15baf99">llvm::GlobalValue::AppendingLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">llvm::GlobalValue::AvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">llvm::GlobalValue::CommonLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">llvm::GlobalValue::ExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">llvm::GlobalValue::LinkOnceAnyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>


<p>Referenced by <a href="#a586414510277aa6c4ef316c8644518a3">getEncodedLinkage</a>.</p>

</div>
</div>

### getEncodedLinkage() {#a586414510277aa6c4ef316c8644518a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getEncodedLinkage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="#a80f86a215f525703479598846b589a41">getEncodedLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3547d58a060ee2e4a29cbea85bef91af">llvm::GlobalValue::getLinkage</a>.</p>

</div>
</div>

### getEncodedOrdering() {#a7541865486d11f84653ce3dc7d5a1618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getEncodedOrdering (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ordering)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a133fea251780f2b0a86a520addd9c184">llvm::bitc::ORDERING_ACQREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a0b468dec37bac00c148e2e9a20711bb9">llvm::bitc::ORDERING_ACQUIRE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077aec3d86ca51de0866abd0fc0d1ec71b9d">llvm::bitc::ORDERING_MONOTONIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a83f6d5a33251a1af65bfd012765dbec7">llvm::bitc::ORDERING_NOTATOMIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a47017037bf5808b06c2cd2e184c55de2">llvm::bitc::ORDERING_RELEASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077ab5a2748be1fde542bf8baeb43f6f44cb">llvm::bitc::ORDERING_SEQCST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a8768765e8f788907885fbd23ae6a8edb">llvm::bitc::ORDERING_UNORDERED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

</div>
</div>

### getEncodedRMWOperation() {#ad85e76fce8fe9aed9406ed2d9b6f671e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getEncodedRMWOperation (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> Op)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0794c42b44989f9d9f1454d79ca0dd88">llvm::AtomicRMWInst::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">llvm::AtomicRMWInst::And</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a08ef06068dcd583c2476568dda59b324">llvm::AtomicRMWInst::FAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615acce124326ba87b0127b36c412bf555fd">llvm::AtomicRMWInst::FMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abd5e733a10a36f3572105b1a67538e18">llvm::AtomicRMWInst::FMin</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a92f66d4bc04fc8514bee80509f3e78d4">llvm::AtomicRMWInst::FSub</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afdcdc631cf4fa6829fd7499cd06a306b">llvm::AtomicRMWInst::Nand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">llvm::AtomicRMWInst::Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaf3617c1779061deeeae4a24e1c45d015">llvm::bitc::RMW_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa1fffe440fc04d4931be511a6759fb0bf">llvm::bitc::RMW_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa56e0b4e94e457f1abf28de75d156eed2">llvm::bitc::RMW_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaf6ff61c0bdbe5ab915efd9cdc1ffb3bc">llvm::bitc::RMW_FMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa0f985a5852d333645b18af7dd342b366">llvm::bitc::RMW_FMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaae916e663743bef5cdc843ae1fe2bb50">llvm::bitc::RMW_FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa0f7c09593b49ad69a24976fd79491ca9">llvm::bitc::RMW_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aafef3e0c3498ab6999f170022e942b675">llvm::bitc::RMW_MIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaf1143967d78add27bf0a34cd120b05b9">llvm::bitc::RMW_NAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa659ec22852b50f1b2907cb553ccd3003">llvm::bitc::RMW_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa7786115a5d20e2d7377870813a8e91fe">llvm::bitc::RMW_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa974e4f980368e5eb72fbc4693ce077bc">llvm::bitc::RMW_UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa3458453a8e9b396ca571f9c7ee12b9fd">llvm::bitc::RMW_UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa172fe635673085e6d5efc03db990e68e">llvm::bitc::RMW_XCHG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa75792f75bfdfd0639c08b8f4a6d7422e">llvm::bitc::RMW_XOR</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5db6ca0c3e18acd87290f22ccb2ce564">llvm::AtomicRMWInst::Sub</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e">llvm::AtomicRMWInst::UMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d">llvm::AtomicRMWInst::UMin</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a71aab8ee954b6d71a4eed315e8f6556e">llvm::AtomicRMWInst::Xor</a>.</p>

</div>
</div>

### getEncodedThreadLocalMode() {#a27deb340295be3eb8c6fa8b611944e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getEncodedThreadLocalMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a55e32c080bb5217324a597d4fb441660">llvm::GlobalValue::GeneralDynamicTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a52126ae2091b18cecfd5ad0f0012839a">llvm::GlobalValue::getThreadLocalMode</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a92e26a4a1218d351f5a91e7385a3a320">llvm::GlobalValue::InitialExecTLSModel</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62ac9f6ea05a2d4cca9e093366042dfa6b8">llvm::GlobalValue::LocalDynamicTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a41529b6e723f5025e59ca9364cf70128">llvm::GlobalValue::LocalExecTLSModel</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>.</p>

</div>
</div>

### getEncodedUnaryOpcode() {#aaeb5965073f5357caf8cfd62d414e6c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getEncodedUnaryOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a635e5fcb068bb33406c8f4478fec92acaff0bbded1d2517cb24d7d941a40cfd31">llvm::bitc::UNOP_FNEG</a>.</p>

</div>
</div>

### getEncodedVisibility() {#a82c3d62e3e31689738ff29dc4c2bceb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DXILBitcodeWriter::getEncodedVisibility (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">llvm::GlobalValue::DefaultVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a28b9561d9ef3d237ef894023187fa26c">llvm::GlobalValue::getVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195ae1cc9a390520055573d459de25747caa">llvm::GlobalValue::ProtectedVisibility</a>.</p>

</div>
</div>

### getOptimizationFlags() {#af55de374d4280b901de2e6b0168f4ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DXILBitcodeWriter::getOptimizationFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aafa457615c7642f4cb8e1758bc6673c09">llvm::bitc::AllowReciprocal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa7615867f60ad3984f710b758a7fa794a">llvm::bitc::NoInfs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa0b6078f1d27619490c8569776bfaea2f">llvm::bitc::NoNaNs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa5570d4f40666e6352950e1e45696cbd2">llvm::bitc::NoSignedZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a5d729bc0f60b0cc1cee0d3d16e8a6954a23e6dd46c09ce9c6c771b637a5d3eb69">llvm::bitc::OBO_NO_SIGNED_WRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a5d729bc0f60b0cc1cee0d3d16e8a6954a2fc4d70f7ea4e9bb62acf87e73ad6508">llvm::bitc::OBO_NO_UNSIGNED_WRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a49372e72493c55831abbcfcd59a3d49ca2bb97e5d0b49ccf94e9cae8079c4a4b5">llvm::bitc::PEO_EXACT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aab9ae7390ca4271aea1cc0fd8ad959ed2">llvm::bitc::UnsafeAlgebra</a>.</p>

</div>
</div>

### writeIdentificationBlock() {#a8f244a8578b0143781cb54fa6750f926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::DXILBitcodeWriter::writeIdentificationBlock (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### writeStringRecord() {#a56bf1b8486ba52a5e85a2613e8e10c52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBitcodeWriter::writeStringRecord (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream, unsigned Code, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, unsigned AbbrevToUse)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a04864a36012093c3174c0e762331eb23">llvm::BitCodeAbbrevOp::isChar6</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp">DXILBitcodeWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
