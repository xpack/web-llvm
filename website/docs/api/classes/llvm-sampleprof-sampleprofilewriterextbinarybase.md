---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SampleProfileWriterExtBinaryBase` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleProfileWriterExtBinaryBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">llvm/ProfileData/SampleProfWriter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary">SampleProfileWriterBinary</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sample-based profile writer (binary format). <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinary">SampleProfileWriterExtBinary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c9e525ff3c6c6034850b0778f8e42d">write</a> (const SampleProfileMap &amp;ProfileMap) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write all the sample profiles in the given map of samples. <a href="#af1c9e525ff3c6c6034850b0778f8e42d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced2f616b4b24d1467a0eb6e73767ad8">setToCompressAllSections</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29bb7e3b667dff2235fa5752fcb27f5e">setToCompressSection</a> (SecType Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5cddc155fef09dd03f4493e99524109">writeSample</a> (const FunctionSamples &amp;S) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write samples of a top-level function to a binary file. <a href="#af5cddc155fef09dd03f4493e99524109">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dd8e727f0005635c2cce8a6791afe92">setUseMD5</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a802ef546c5873e18c12de54700368e97">setPartialProfile</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77dacf197f38b0e191ac68b731234e04">setProfileSymbolList</a> (ProfileSymbolList *PSL) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e639deb948033de0b5b24149c12256">setUseCtxSplitLayout</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e7dfce21ee8c2e8148515070a4ad7d4">resetSecLayout</a> (SectionLayout SL)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6d9741f6d03790df898209e50342f2b">markSectionStart</a> (SecType Type, uint32_t LayoutIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current position and prepare to use it as the start position of a section given the section type <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></span> and its position <span class="doxyComputerOutput">LayoutIdx</span> in SectionHdrLayout. <a href="#ab6d9741f6d03790df898209e50342f2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcb41826a24e17e2c7a615abcf988cab">addNewSection</a> (SecType Sec, uint32_t LayoutIdx, uint64_t SectionStart)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new section into section header table given the section type <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></span>, its position <span class="doxyComputerOutput">LayoutIdx</span> in SectionHdrLayout and the location <span class="doxyComputerOutput">SectionStart</span> where the section should be written to. <a href="#abcb41826a24e17e2c7a615abcf988cab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SecFlagType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaadde29e4289aa91276b5827f0d3bf30">addSectionFlag</a> (SecType Type, SecFlagType Flag)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class SecFlagType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0ac5a3096b16fffd4421657f453ebd6">addSectionFlag</a> (uint32_t SectionIdx, SecFlagType Flag)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb0eaeeea93bca26cb7055c7ab9e94ed">addContext</a> (const SampleContext &amp;Context) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a4bc1cb33515ccdbc6494bb7313a4c">writeCustomSection</a> (SecType Type)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50fd7806de1d0a978a7dc13578c193a6">verifySecLayout</a> (SectionLayout SL)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a818860de490d7d3723ddc2e3f59733c1">writeSections</a> (const SampleProfileMap &amp;ProfileMap)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a> (SecType Type, uint32_t LayoutIdx, const SampleProfileMap &amp;ProfileMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8da3b86e5070140af1716c64925a0495">writeNameTable</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4e88367a9ab641e74700f89be2db0b4">writeContextIdx</a> (const SampleContext &amp;Context) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bc88eec2b14372dd70f9274feeee6bb">writeCSNameIdx</a> (const SampleContext &amp;Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a449a2a9cd2cebab93b804f4a6cbaea5a">writeCSNameTableSection</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27bd438e566ec617ad7d33c562abae5c">writeFuncMetadata</a> (const SampleProfileMap &amp;Profiles)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96315b9b9bda521e4026e537c7d9f139">writeFuncMetadata</a> (const FunctionSamples &amp;Profile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01496927b6d3c4676bc9b45276fd4237">writeNameTableSection</a> (const SampleProfileMap &amp;ProfileMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b40af607c43587edc28f8788e07cefd">writeFuncOffsetTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac620f9ad115b9f0db02f271dde1b586">writeProfileSymbolListSection</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21c3e14a4b9b0bd7777c65f60e8e4d62">allocSecHdrTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae96128366d6744fe0ff95fa7910239ee">writeSecHdrTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa806016eb2d8b37d6c808b727b90b6">writeHeader</a> (const SampleProfileMap &amp;ProfileMap) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a file header for the profile file. <a href="#a7fa806016eb2d8b37d6c808b727b90b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2764cbc43896c6b8ba2cbf5ec48a6ad">compressAndOutput</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc0d64eb352acfe499cccd772a04dbe">SampleProfileWriterBinary</a> (std::unique_ptr&lt; raw_ostream &gt; &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45d9ac5c168a661c76feb9de8172a64">SectionLayout</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac11b775d501bd89e290ce52be9fafef3">SecLayout</a> = <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45d9ac5c168a661c76feb9de8172a64ab2da08f775e5b916867391154137499b">DefaultLayout</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/sampleprof/sechdrtableentry">SecHdrTableEntry</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1075a64a4c4b683d78d00d9db307b5d9">SectionHdrLayout</a> = ...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeef532508adaa218bda66b955705b98">SecLBRProfileStart</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6f23d10b95ee30748450bbb1202c70">LocalBufStream</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af66a876b76699252f8896752a8de2964">FileStart</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbad0afe1ee669eb4bbfb41309e5accb">SecHdrTableOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/sampleprof/sechdrtableentry">SecHdrTableEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711e0e478e702ca1d3da7da1f910829e">SecHdrTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a>, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2af669e769259f80b1800e027b30ce03">FuncOffsetTable</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a113ea8149ba54cf794373ce5c86007bc">UseMD5</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a>, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a412d0586f701046cec97a5dc333f2309">CSNameTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CSNameTable maps function context to its offset in SecCSNameTable section. <a href="#a412d0586f701046cec97a5dc333f2309">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/profilesymbollist">ProfileSymbolList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd9433f7a0d89eb6955c00a26fd50ed">ProfSymList</a> = nullptr</td>
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


<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### resetSecLayout() {#a9e7dfce21ee8c2e8148515070a4ad7d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileWriterExtBinaryBase::resetSecLayout (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45d9ac5c168a661c76feb9de8172a64">SectionLayout</a> SL)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a63904d8c45d8a4f5bf54e8e82d25858a">llvm::sampleprof::ExtBinaryHdrLayoutTable</a>, <a href="#ac11b775d501bd89e290ce52be9fafef3">SecLayout</a>, <a href="#a1075a64a4c4b683d78d00d9db307b5d9">SectionHdrLayout</a> and <a href="#a50fd7806de1d0a978a7dc13578c193a6">verifySecLayout</a>.</p>


<p>Referenced by <a href="#a06e639deb948033de0b5b24149c12256">setUseCtxSplitLayout</a>.</p>

</div>
</div>

### setPartialProfile() {#a802ef546c5873e18c12de54700368e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileWriterExtBinaryBase::setPartialProfile ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>References <a href="#aaadde29e4289aa91276b5827f0d3bf30">addSectionFlag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462ab8c5c1b9457b958b7c66a02adb2dc97a">llvm::sampleprof::SecFlagPartial</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a8c51d0a5a19b4b2ae76846092b479354">llvm::sampleprof::SecProfSummary</a>.</p>

</div>
</div>

### setProfileSymbolList() {#a77dacf197f38b0e191ac68b731234e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileWriterExtBinaryBase::setProfileSymbolList (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/profilesymbollist">ProfileSymbolList</a> * PSL)</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### setToCompressAllSections() {#aced2f616b4b24d1467a0eb6e73767ad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileWriterExtBinaryBase::setToCompressAllSections ()</td>
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



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a39d5bbfc67b336b0cb89b241e3057d1d">llvm::sampleprof::addSecFlag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a249a6a299581a44359596da9619a4b19a16052b6981a5cb6f18149f985d66ab87">llvm::sampleprof::SecFlagCompress</a> and <a href="#a1075a64a4c4b683d78d00d9db307b5d9">SectionHdrLayout</a>.</p>

</div>
</div>

### setToCompressSection() {#a29bb7e3b667dff2235fa5752fcb27f5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileWriterExtBinaryBase::setToCompressSection (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85">SecType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="#aaadde29e4289aa91276b5827f0d3bf30">addSectionFlag</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a249a6a299581a44359596da9619a4b19a16052b6981a5cb6f18149f985d66ab87">llvm::sampleprof::SecFlagCompress</a>.</p>


<p>Referenced by <a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a>.</p>

</div>
</div>

### setUseCtxSplitLayout() {#a06e639deb948033de0b5b24149c12256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileWriterExtBinaryBase::setUseCtxSplitLayout ()</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45d9ac5c168a661c76feb9de8172a64a6ea388ead6d571d9295bc54fa2f5a359">llvm::sampleprof::CtxSplitLayout</a> and <a href="#a9e7dfce21ee8c2e8148515070a4ad7d4">resetSecLayout</a>.</p>

</div>
</div>

### setUseMD5() {#a1dd8e727f0005635c2cce8a6791afe92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileWriterExtBinaryBase::setUseMD5 ()</td>
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



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>References <a href="#aaadde29e4289aa91276b5827f0d3bf30">addSectionFlag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a7d0799e340cf7553a27f898ef20ad6f7a5121eb700a5270cadcb8ec87c2593288">llvm::sampleprof::SecFlagFixedLengthMD5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a7d0799e340cf7553a27f898ef20ad6f7a1780ac16db816da7bda99433dbdb73bf">llvm::sampleprof::SecFlagMD5Name</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a04e75d4659b0c502eb2280e6d6fd6378">llvm::sampleprof::SecNameTable</a>.</p>

</div>
</div>

### write() {#af1c9e525ff3c6c6034850b0778f8e42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::write (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap)</td>
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

<p>Write all the sample profiles in the given map of samples.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>status code of the file update operation.</p></dd>
</dl>


<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a845681147d133c5df69046907e725abf">llvm::sampleprof::SampleProfileWriterBinary::NameTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="#a818860de490d7d3723ddc2e3f59733c1">writeSections</a>.</p>

</div>
</div>

### writeSample() {#af5cddc155fef09dd03f4493e99524109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeSample (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; S)</td>
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

<p>Write samples of a top-level function to a binary file.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the samples were written successfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a6206d4ca96e6f63a40327a7fa147f2a4">llvm::sampleprof::FunctionSamples::getHeadSamples</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="#aeeef532508adaa218bda66b955705b98">SecLBRProfileStart</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#ae7c088ecf1befc97ec9b4d36f30ae06d">llvm::sampleprof::SampleProfileWriterBinary::writeBody</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addContext() {#abb0eaeeea93bca26cb7055c7ab9e94ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileWriterExtBinaryBase::addContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; Context)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#afa66076e59337700916195677d4437a7">llvm::sampleprof::SampleProfileWriterBinary::addName</a>.</p>


<p>Referenced by <a href="#a01496927b6d3c4676bc9b45276fd4237">writeNameTableSection</a>.</p>

</div>
</div>

### addNewSection() {#abcb41826a24e17e2c7a615abcf988cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::addNewSection (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85">SecType</a> Sec, uint32_t LayoutIdx, uint64_t SectionStart)</td>
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

<p>Add a new section into section header table given the section type <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></span>, its position <span class="doxyComputerOutput">LayoutIdx</span> in SectionHdrLayout and the location <span class="doxyComputerOutput">SectionStart</span> where the section should be written to.</p>

<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a3efc74fee0efccc34cb5a64de6b1d84a">llvm::sampleprof::hasSecFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a249a6a299581a44359596da9619a4b19a16052b6981a5cb6f18149f985d66ab87">llvm::sampleprof::SecFlagCompress</a>, <a href="#a1075a64a4c4b683d78d00d9db307b5d9">SectionHdrLayout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a>.</p>

</div>
</div>

### addSectionFlag() {#aaadde29e4289aa91276b5827f0d3bf30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SecFlagType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileWriterExtBinaryBase::addSectionFlag (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85">SecType</a> Type, SecFlagType Flag)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a39d5bbfc67b336b0cb89b241e3057d1d">llvm::sampleprof::addSecFlag</a> and <a href="#a1075a64a4c4b683d78d00d9db307b5d9">SectionHdrLayout</a>.</p>


<p>Referenced by <a href="#a802ef546c5873e18c12de54700368e97">setPartialProfile</a>, <a href="#a29bb7e3b667dff2235fa5752fcb27f5e">setToCompressSection</a>, <a href="#a1dd8e727f0005635c2cce8a6791afe92">setUseMD5</a>, <a href="#a3b40af607c43587edc28f8788e07cefd">writeFuncOffsetTable</a>, <a href="#a01496927b6d3c4676bc9b45276fd4237">writeNameTableSection</a> and <a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a>.</p>

</div>
</div>

### addSectionFlag() {#ad0ac5a3096b16fffd4421657f453ebd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class SecFlagType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleProfileWriterExtBinaryBase::addSectionFlag (uint32_t SectionIdx, SecFlagType Flag)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a39d5bbfc67b336b0cb89b241e3057d1d">llvm::sampleprof::addSecFlag</a> and <a href="#a1075a64a4c4b683d78d00d9db307b5d9">SectionHdrLayout</a>.</p>

</div>
</div>

### markSectionStart() {#ab6d9741f6d03790df898209e50342f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t SampleProfileWriterExtBinaryBase::markSectionStart (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85">SecType</a> Type, uint32_t LayoutIdx)</td>
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

<p>Return the current position and prepare to use it as the start position of a section given the section type <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></span> and its position <span class="doxyComputerOutput">LayoutIdx</span> in SectionHdrLayout.</p>

<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a3efc74fee0efccc34cb5a64de6b1d84a">llvm::sampleprof::hasSecFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a249a6a299581a44359596da9619a4b19a16052b6981a5cb6f18149f985d66ab87">llvm::sampleprof::SecFlagCompress</a> and <a href="#a1075a64a4c4b683d78d00d9db307b5d9">SectionHdrLayout</a>.</p>


<p>Referenced by <a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a>.</p>

</div>
</div>

### verifySecLayout() {#a50fd7806de1d0a978a7dc13578c193a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sampleprof::SampleProfileWriterExtBinaryBase::verifySecLayout (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45d9ac5c168a661c76feb9de8172a64">SectionLayout</a> SL)</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="#a9e7dfce21ee8c2e8148515070a4ad7d4">resetSecLayout</a>.</p>

</div>
</div>

### writeContextIdx() {#af4e88367a9ab641e74700f89be2db0b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeContextIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; Context)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="#a4bc88eec2b14372dd70f9274feeee6bb">writeCSNameIdx</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#af63eb7fece187a61531bdb743120f3c7">llvm::sampleprof::SampleProfileWriterBinary::writeNameIdx</a>.</p>


<p>Referenced by <a href="#a96315b9b9bda521e4026e537c7d9f139">writeFuncMetadata</a> and <a href="#a3b40af607c43587edc28f8788e07cefd">writeFuncOffsetTable</a>.</p>

</div>
</div>

### writeCSNameIdx() {#a4bc88eec2b14372dd70f9274feeee6bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeCSNameIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; Context)</td>
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



<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea98266342cea8a7fb97a2c17d98fd230a">llvm::truncated_name_table</a>.</p>


<p>Referenced by <a href="#af4e88367a9ab641e74700f89be2db0b4">writeContextIdx</a>.</p>

</div>
</div>

### writeCSNameTableSection() {#a449a2a9cd2cebab93b804f4a6cbaea5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeCSNameTableSection ()</td>
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



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#af63eb7fece187a61531bdb743120f3c7">llvm::sampleprof::SampleProfileWriterBinary::writeNameIdx</a>.</p>


<p>Referenced by <a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a>.</p>

</div>
</div>

### writeCustomSection() {#a30a4bc1cb33515ccdbc6494bb7313a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeCustomSection (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85">SecType</a> Type)</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a>.</p>

</div>
</div>

### writeFuncMetadata() {#a27bd438e566ec617ad7d33c562abae5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeFuncMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; Profiles)</td>
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



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a08b33b498078ac3694a992f4ab8a5761">llvm::sampleprof::FunctionSamples::ProfileIsPreInlined</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="#a27bd438e566ec617ad7d33c562abae5c">writeFuncMetadata</a>.</p>


<p>Referenced by <a href="#a96315b9b9bda521e4026e537c7d9f139">writeFuncMetadata</a>, <a href="#a27bd438e566ec617ad7d33c562abae5c">writeFuncMetadata</a> and <a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a>.</p>

</div>
</div>

### writeFuncMetadata() {#a96315b9b9bda521e4026e537c7d9f139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeFuncMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; Profile)</td>
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



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#ac14fcf43c57c449e8398370de8d9a2dc">llvm::sampleprof::SampleContext::getAllAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ae216a9dc4cce5948cec7fbf16ff462dd">llvm::sampleprof::FunctionSamples::getCallsiteSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a7ffff5be739dfce8ccdb944c3f485306">llvm::sampleprof::FunctionSamples::getFunctionHash</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a08b33b498078ac3694a992f4ab8a5761">llvm::sampleprof::FunctionSamples::ProfileIsPreInlined</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="#af4e88367a9ab641e74700f89be2db0b4">writeContextIdx</a> and <a href="#a27bd438e566ec617ad7d33c562abae5c">writeFuncMetadata</a>.</p>

</div>
</div>

### writeFuncOffsetTable() {#a3b40af607c43587edc28f8788e07cefd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeFuncOffsetTable ()</td>
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



<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="#aaadde29e4289aa91276b5827f0d3bf30">addSectionFlag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#abed83dc828c8bfb55967efc3b9313758a3cc23f4782f1fd246c14392b45a2646f">llvm::sampleprof::SecFlagOrdered</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85ae3b5e1c40206f7ac0a1e8b9c1f4fa4d7">llvm::sampleprof::SecFuncOffsetTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="#af4e88367a9ab641e74700f89be2db0b4">writeContextIdx</a>.</p>


<p>Referenced by <a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a>.</p>

</div>
</div>

### writeNameTable() {#a8da3b86e5070140af1716c64925a0495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeNameTable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a845681147d133c5df69046907e725abf">llvm::sampleprof::SampleProfileWriterBinary::NameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a3a9843c8238bc35707b209597d873d9b">llvm::sampleprof::SampleProfileWriterBinary::stablizeNameTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#a16a69d4248bb11c84536099421ea833b">llvm::support::endian::Writer::write</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a61e7926d242ffc3cac8fc92591b4178d">llvm::sampleprof::SampleProfileWriterBinary::writeNameTable</a>.</p>


<p>Referenced by <a href="#a01496927b6d3c4676bc9b45276fd4237">writeNameTableSection</a>.</p>

</div>
</div>

### writeNameTableSection() {#a01496927b6d3c4676bc9b45276fd4237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeNameTableSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap)</td>
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



<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="#abb0eaeeea93bca26cb7055c7ab9e94ed">addContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a880b4a9e6f81baaa1c9a1fe9a2151cfd">llvm::sampleprof::SampleProfileWriterBinary::addNames</a>, <a href="#aaadde29e4289aa91276b5827f0d3bf30">addSectionFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a845681147d133c5df69046907e725abf">llvm::sampleprof::SampleProfileWriterBinary::NameTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a7d0799e340cf7553a27f898ef20ad6f7a27ba0d92f39f8d4651a98190c098df5d">llvm::sampleprof::SecFlagUniqSuffix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a04e75d4659b0c502eb2280e6d6fd6378">llvm::sampleprof::SecNameTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a2c9ea2741f8ae073da01be9dfcae147a">llvm::sampleprof::FunctionSamples::UniqSuffix</a> and <a href="#a8da3b86e5070140af1716c64925a0495">writeNameTable</a>.</p>


<p>Referenced by <a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a>.</p>

</div>
</div>

### writeOneSection() {#a33203b3c9366fd57c4d7d30f1f4c83b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeOneSection (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85">SecType</a> Type, uint32_t LayoutIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="#abcb41826a24e17e2c7a615abcf988cab">addNewSection</a>, <a href="#aaadde29e4289aa91276b5827f0d3bf30">addSectionFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a4f8b2ab39ae70cd859c323fd97219c23">llvm::sampleprof::SampleProfileWriter::computeSummary</a>, <a href="#ab6d9741f6d03790df898209e50342f2b">markSectionStart</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ac78db34e62da1555e9b84b5b5b1d907d">llvm::sampleprof::FunctionSamples::ProfileIsFS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a08b33b498078ac3694a992f4ab8a5761">llvm::sampleprof::FunctionSamples::ProfileIsPreInlined</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a99873f635fc6dccc55e1bc82ef297827">llvm::sampleprof::SecCSNameTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462abbe7033a4a1f24db956320bb1a7b7ce3">llvm::sampleprof::SecFlagFSDiscriminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462ad8375f4e079a5af243f36f91334691e7">llvm::sampleprof::SecFlagFullContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ad2f473dc3a871939a4781efc92f0931ba4771c0f8db64857edd1ee64cfde3edca">llvm::sampleprof::SecFlagHasAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#aa229d20f76a2d8473f321b97cb494462a6517bd773ca68b78f926ec08f55daac3">llvm::sampleprof::SecFlagIsPreInlined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ad2f473dc3a871939a4781efc92f0931ba538d11ebcb8192686ae93eb46ec92ebc">llvm::sampleprof::SecFlagIsProbeBased</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85aaa2da63cc16b51f0005debd3ae000a18">llvm::sampleprof::SecFuncMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85ae3b5e1c40206f7ac0a1e8b9c1f4fa4d7">llvm::sampleprof::SecFuncOffsetTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a0e83cbbb890deaad56570290e86506ed">llvm::sampleprof::SecLBRProfile</a>, <a href="#aeeef532508adaa218bda66b955705b98">SecLBRProfileStart</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a04e75d4659b0c502eb2280e6d6fd6378">llvm::sampleprof::SecNameTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85ac77da6bc3aa6f736acc11b4fa1c59857">llvm::sampleprof::SecProfileSymbolList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#af9c6f2601a71ffce0953ca9df59a3e85a8c51d0a5a19b4b2ae76846092b479354">llvm::sampleprof::SecProfSummary</a>, <a href="#a29bb7e3b667dff2235fa5752fcb27f5e">setToCompressSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>, <a href="#a449a2a9cd2cebab93b804f4a6cbaea5a">writeCSNameTableSection</a>, <a href="#a30a4bc1cb33515ccdbc6494bb7313a4c">writeCustomSection</a>, <a href="#a27bd438e566ec617ad7d33c562abae5c">writeFuncMetadata</a>, <a href="#a3b40af607c43587edc28f8788e07cefd">writeFuncOffsetTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6467bcd55ce5f034a9c0f4007ff92889">llvm::sampleprof::SampleProfileWriter::writeFuncProfiles</a>, <a href="#a01496927b6d3c4676bc9b45276fd4237">writeNameTableSection</a>, <a href="#aac620f9ad115b9f0db02f271dde1b586">writeProfileSymbolListSection</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a74c686413929f11d2301cb47bec0fcdb">llvm::sampleprof::SampleProfileWriterBinary::writeSummary</a>.</p>

</div>
</div>

### writeProfileSymbolListSection() {#aac620f9ad115b9f0db02f271dde1b586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeProfileSymbolListSection ()</td>
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



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a6bc387785b288e17a87e9494b57cb937">llvm::sampleprof::SampleProfileWriter::OutputStream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a>.</p>

</div>
</div>

### writeSections() {#a818860de490d7d3723ddc2e3f59733c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeSections (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap)</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp/#a009775794ead70aa23c76df46ab4ed8a">Profile</a>.</p>


<p>Referenced by <a href="#af1c9e525ff3c6c6034850b0778f8e42d">write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### allocSecHdrTable() {#a21c3e14a4b9b0bd7777c65f60e8e4d62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileWriterExtBinaryBase::allocSecHdrTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>

</div>
</div>

### compressAndOutput() {#ae2764cbc43896c6b8ba2cbf5ec48a6ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::compressAndOutput ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>

</div>
</div>

### SampleProfileWriterBinary() {#a0dc0d64eb352acfe499cccd772a04dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleProfileWriterBinary::SampleProfileWriterBinary (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &gt; &amp; OS)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### writeHeader() {#a7fa806016eb2d8b37d6c808b727b90b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap)</td>
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

<p>Write a file header for the profile file.</p>

<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 798 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>

</div>
</div>

### writeSecHdrTable() {#ae96128366d6744fe0ff95fa7910239ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code SampleProfileWriterExtBinaryBase::writeSecHdrTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### SecLayout {#ac11b775d501bd89e290ce52be9fafef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionLayout llvm::sampleprof::SampleProfileWriterExtBinaryBase::SecLayout = <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45d9ac5c168a661c76feb9de8172a64ab2da08f775e5b916867391154137499b">DefaultLayout</a></td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="#a9e7dfce21ee8c2e8148515070a4ad7d4">resetSecLayout</a>.</p>

</div>
</div>

### SecLBRProfileStart {#aeeef532508adaa218bda66b955705b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::SampleProfileWriterExtBinaryBase::SecLBRProfileStart = 0</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="#a33203b3c9366fd57c4d7d30f1f4c83b3">writeOneSection</a> and <a href="#af5cddc155fef09dd03f4493e99524109">writeSample</a>.</p>

</div>
</div>

### SectionHdrLayout {#a1075a64a4c4b683d78d00d9db307b5d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SecHdrTableEntry, 8&gt; llvm::sampleprof::SampleProfileWriterExtBinaryBase::SectionHdrLayout</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a63904d8c45d8a4f5bf54e8e82d25858a">ExtBinaryHdrLayoutTable</a>[<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45d9ac5c168a661c76feb9de8172a64ab2da08f775e5b916867391154137499b">DefaultLayout</a>]
</div>
</dd>
</dl>

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="#abcb41826a24e17e2c7a615abcf988cab">addNewSection</a>, <a href="#aaadde29e4289aa91276b5827f0d3bf30">addSectionFlag</a>, <a href="#ad0ac5a3096b16fffd4421657f453ebd6">addSectionFlag</a>, <a href="#ab6d9741f6d03790df898209e50342f2b">markSectionStart</a>, <a href="#a9e7dfce21ee8c2e8148515070a4ad7d4">resetSecLayout</a> and <a href="#aced2f616b4b24d1467a0eb6e73767ad8">setToCompressAllSections</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CSNameTable {#a412d0586f701046cec97a5dc333f2309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;SampleContext, uint32_t&gt; llvm::sampleprof::SampleProfileWriterExtBinaryBase::CSNameTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CSNameTable maps function context to its offset in SecCSNameTable section.</p>


<p>The offset will be used everywhere where the context is referenced.</p>


<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### FileStart {#af66a876b76699252f8896752a8de2964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::SampleProfileWriterExtBinaryBase::FileStart</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### FuncOffsetTable {#a2af669e769259f80b1800e027b30ce03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;SampleContext, uint64_t&gt; llvm::sampleprof::SampleProfileWriterExtBinaryBase::FuncOffsetTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### LocalBufStream {#aaf6f23d10b95ee30748450bbb1202c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;raw_ostream&gt; llvm::sampleprof::SampleProfileWriterExtBinaryBase::LocalBufStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### ProfSymList {#a1fd9433f7a0d89eb6955c00a26fd50ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSymbolList* llvm::sampleprof::SampleProfileWriterExtBinaryBase::ProfSymList = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### SecHdrTable {#a711e0e478e702ca1d3da7da1f910829e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SecHdrTableEntry&gt; llvm::sampleprof::SampleProfileWriterExtBinaryBase::SecHdrTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### SecHdrTableOffset {#adbad0afe1ee669eb4bbfb41309e5accb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::SampleProfileWriterExtBinaryBase::SecHdrTableOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

### UseMD5 {#a113ea8149ba54cf794373ce5c86007bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleProfileWriterExtBinaryBase::UseMD5 = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
