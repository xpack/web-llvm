---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/riscvisainfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RISCVISAInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RISCVISAInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">llvm/TargetParser/RISCVISAInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35237f29879a5afa8b3d9017c7bea91a">RISCVISAInfo</a> (const RISCVISAInfo &amp;)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f56e8427fc677fad56b6a373cfb5ae3">RISCVISAInfo</a> (unsigned XLen)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvisainfo">RISCVISAInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c62d86ebb8ea9d4e65d4255e82b76ad">operator=</a> (const RISCVISAInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4ef065f1b58988c5bb0b6ec76846366">toFeatures</a> (bool AddAllExtensions=false, bool IgnoreUnknown=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert RISC-V ISA info to a feature vector. <a href="#af4ef065f1b58988c5bb0b6ec76846366">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/riscvisautils/#a8557faa65915a2ad7c9f4576d736f50b">RISCVISAUtils::OrderedExtensionMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ff53026e58c4443d5dfeca73bb97a6">getExtensions</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c1a6484006d825a2100b5b6136a28e">getXLen</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b591370b95581d45939aac11ca9f37a">getFLen</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30dab1245781bcade05e4bdc00cb3fa1">getMinVLen</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa36eae1e33eadb7c27b2dcba72d03db7">getMaxVLen</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac784544e97c7e1712f790caccf1353ef">getMaxELen</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee62d37fab61fb19a9e890ec9ff8a561">getMaxELenFp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c522e755437c93c44bbd75b768b663">hasExtension</a> (StringRef Ext) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a407dbc4127c54c6a0482293b115fac89">toString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d1ac65da41eb1a6ffc1b6b6fa6e7cbc">computeDefaultABI</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd93e4818dc6cc5d5645ac0b88d741a4">checkDependency</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a929042bf8b738003651c6900c73383">updateImplication</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c15e6f801355810810ebb20989bed69">updateCombination</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd3a80f5ff3e99179c49a7b220b94b37">updateImpliedLengths</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update FLen, MinVLen, MaxELen, and MaxELenFp. <a href="#abd3a80f5ff3e99179c49a7b220b94b37">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad004982939cef83cdca0c1dded85dd77">XLen</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae332987eb176be6c5d98f39a5549f7ec">FLen</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea44800ff3934a81922b4408c4adff4b">MinVLen</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56c59cea74cc04c60ce5b2c0f98d303">MaxELen</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8267ac7da405579b0ef9a40dfdea6a2b">MaxELenFp</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/riscvisautils/#a8557faa65915a2ad7c9f4576d736f50b">RISCVISAUtils::OrderedExtensionMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0649542031dcf99968fbc2cd00edaf56">Exts</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo">RISCVISAInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa18f12a3fd9c95854df97891e6d2c338">parseArchString</a> (StringRef Arch, bool EnableExperimentalExtension, bool ExperimentalExtensionVersionCheck=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse RISC-V ISA info from arch string. <a href="#aa18f12a3fd9c95854df97891e6d2c338">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo">RISCVISAInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32990ca8b9376479e983ffed2e0fe9b4">parseNormalizedArchString</a> (StringRef Arch)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse RISC-V ISA info from an arch string that is already in normalized form (as defined in the psABI). <a href="#a32990ca8b9376479e983ffed2e0fe9b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo">RISCVISAInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac44851c2ceedf8a3136d31773e0f20e2">parseFeatures</a> (unsigned XLen, const std::vector&lt; std::string &gt; &amp;Features)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse RISC-V ISA info from feature vector. <a href="#ac44851c2ceedf8a3136d31773e0f20e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo">RISCVISAInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef85f28ebc1eb3f776d40a32e6f18f0d">createFromExtMap</a> (unsigned XLen, const RISCVISAUtils::OrderedExtensionMap &amp;Exts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06632f7f66681098316a7cbf42927d09">isSupportedExtensionFeature</a> (StringRef Ext)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe02ccc1e3c410eac85a36f70878f18">isSupportedExtension</a> (StringRef Ext)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd8b4904b4e18e880c419386dfe4d85">isSupportedExtensionWithVersion</a> (StringRef Ext)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13af215927d8f3b7a48358c72b084ac4">isSupportedExtension</a> (StringRef Ext, unsigned MajorVersion, unsigned MinorVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24074750f6a79cbc564c654612b773ec">getTargetFeatureForExtension</a> (StringRef Ext)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac192fe2b2eb30e2900fb5a9277432f72">printSupportedExtensions</a> (StringMap&lt; StringRef &gt; &amp;DescMap)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab74c03e7b0136fcbc7195e1243e7a401">printEnabledExtensions</a> (bool IsRV64, std::set&lt; StringRef &gt; &amp;EnabledFeatureNames, StringMap&lt; StringRef &gt; &amp;DescMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; int, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a40242a319096c3a2f6b36801d9774">getRISCVFeaturesBitsInfo</a> (StringRef Ext)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the group id and bit position of __riscv_feature_bits. <a href="#ad5a40242a319096c3a2f6b36801d9774">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo">RISCVISAInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8571b20395549fe4d811883ef70644c8">postProcessAndChecking</a> (std::unique_ptr&lt; RISCVISAInfo &gt; &amp;&amp;ISAInfo)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06744fe29b0b03000d93a3de71838821">FeatureBitSize</a> = 2</td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVISAInfo() {#a35237f29879a5afa8b3d9017c7bea91a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RISCVISAInfo::RISCVISAInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo">RISCVISAInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>


<p>Reference <a href="#a35237f29879a5afa8b3d9017c7bea91a">RISCVISAInfo</a>.</p>


<p>Referenced by <a href="#aef85f28ebc1eb3f776d40a32e6f18f0d">createFromExtMap</a>, <a href="#a1c62d86ebb8ea9d4e65d4255e82b76ad">operator=</a>, <a href="#aa18f12a3fd9c95854df97891e6d2c338">parseArchString</a>, <a href="#ac44851c2ceedf8a3136d31773e0f20e2">parseFeatures</a>, <a href="#a32990ca8b9376479e983ffed2e0fe9b4">parseNormalizedArchString</a> and <a href="#a35237f29879a5afa8b3d9017c7bea91a">RISCVISAInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### RISCVISAInfo() {#a1f56e8427fc677fad56b6a373cfb5ae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RISCVISAInfo::RISCVISAInfo (unsigned XLen)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a1c62d86ebb8ea9d4e65d4255e82b76ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVISAInfo &amp; llvm::RISCVISAInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo">RISCVISAInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>


<p>Reference <a href="#a35237f29879a5afa8b3d9017c7bea91a">RISCVISAInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeDefaultABI() {#a8d1ac65da41eb1a6ffc1b6b6fa6e7cbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef RISCVISAInfo::computeDefaultABI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getExtensions() {#a85ff53026e58c4443d5dfeca73bb97a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVISAUtils::OrderedExtensionMap &amp; llvm::RISCVISAInfo::getExtensions ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### getFLen() {#a3b591370b95581d45939aac11ca9f37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::getFLen ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### getMaxELen() {#ac784544e97c7e1712f790caccf1353ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::getMaxELen ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### getMaxELenFp() {#aee62d37fab61fb19a9e890ec9ff8a561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::getMaxELenFp ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### getMaxVLen() {#aa36eae1e33eadb7c27b2dcba72d03db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::getMaxVLen ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### getMinVLen() {#a30dab1245781bcade05e4bdc00cb3fa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::getMinVLen ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### getXLen() {#ac8c1a6484006d825a2100b5b6136a28e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::getXLen ()</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### hasExtension() {#a34c522e755437c93c44bbd75b768b663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVISAInfo::hasExtension (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="#aafe02ccc1e3c410eac85a36f70878f18">isSupportedExtension</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a977bc5a442868c797e853e7c6bc0b57a">stripExperimentalPrefix</a>.</p>

</div>
</div>

### toFeatures() {#af4ef065f1b58988c5bb0b6ec76846366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::string &gt; RISCVISAInfo::toFeatures (bool AddAllExtensions=false, bool IgnoreUnknown=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert RISC-V ISA info to a feature vector.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a9a744bc5d762669b40be5e20a99ea60b">isExperimentalExtension</a> and <a href="#aafe02ccc1e3c410eac85a36f70878f18">isSupportedExtension</a>.</p>

</div>
</div>

### toString() {#a407dbc4127c54c6a0482293b115fac89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string RISCVISAInfo::toString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 940 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### checkDependency() {#afd93e4818dc6cc5d5645ac0b88d741a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RISCVISAInfo::checkDependency ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 746 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>

</div>
</div>

### updateCombination() {#a5c15e6f801355810810ebb20989bed69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVISAInfo::updateCombination ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>

</div>
</div>

### updateImplication() {#a0a929042bf8b738003651c6900c73383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVISAInfo::updateImplication ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 816 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>

</div>
</div>

### updateImpliedLengths() {#abd3a80f5ff3e99179c49a7b220b94b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVISAInfo::updateImpliedLengths ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update FLen, MinVLen, MaxELen, and MaxELenFp.</p>

<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 891 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Exts {#a0649542031dcf99968fbc2cd00edaf56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVISAUtils::OrderedExtensionMap llvm::RISCVISAInfo::Exts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### FLen {#ae332987eb176be6c5d98f39a5549f7ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::FLen = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### MaxELen {#ae56c59cea74cc04c60ce5b2c0f98d303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::MaxELen = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### MaxELenFp {#a8267ac7da405579b0ef9a40dfdea6a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::MaxELenFp = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### MinVLen {#aea44800ff3934a81922b4408c4adff4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::MinVLen = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

### XLen {#ad004982939cef83cdca0c1dded85dd77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::XLen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createFromExtMap() {#aef85f28ebc1eb3f776d40a32e6f18f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; std::unique_ptr&lt; RISCVISAInfo &gt; &gt; RISCVISAInfo::createFromExtMap (unsigned XLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/riscvisautils/#a8557faa65915a2ad7c9f4576d736f50b">RISCVISAUtils::OrderedExtensionMap</a> &amp; Exts)</td>
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



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a35237f29879a5afa8b3d9017c7bea91a">RISCVISAInfo</a>.</p>


<p>Referenced by <a href="#ab74c03e7b0136fcbc7195e1243e7a401">printEnabledExtensions</a>.</p>

</div>
</div>

### getRISCVFeaturesBitsInfo() {#ad5a40242a319096c3a2f6b36801d9774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int, int &gt; RISCVISAInfo::getRISCVFeaturesBitsInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext)</td>
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

<p>Return the group id and bit position of __riscv_feature_bits.</p>


<p>Returns &lt;-1, -1&gt; if not supported.</p>


<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 1061 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a71ef39ddb5fba5c251f3192de7caa9c2">RISCVBitPositions</a>.</p>

</div>
</div>

### getTargetFeatureForExtension() {#a24074750f6a79cbc564c654612b773ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string RISCVISAInfo::getTargetFeatureForExtension (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext)</td>
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



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a3dba4372ba2b0183b65fcce9e61ca7bc">findLastNonVersionCharacter</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a9a744bc5d762669b40be5e20a99ea60b">isExperimentalExtension</a>, <a href="#aafe02ccc1e3c410eac85a36f70878f18">isSupportedExtension</a> and <a href="#afcd8b4904b4e18e880c419386dfe4d85">isSupportedExtensionWithVersion</a>.</p>

</div>
</div>

### isSupportedExtension() {#aafe02ccc1e3c410eac85a36f70878f18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVISAInfo::isSupportedExtension (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext)</td>
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



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp/#a0063780933c83ab9a27e63c51772154f">verifyTables</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a>, <a href="#a24074750f6a79cbc564c654612b773ec">getTargetFeatureForExtension</a>, <a href="#a34c522e755437c93c44bbd75b768b663">hasExtension</a>, <a href="#aa18f12a3fd9c95854df97891e6d2c338">parseArchString</a> and <a href="#af4ef065f1b58988c5bb0b6ec76846366">toFeatures</a>.</p>

</div>
</div>

### isSupportedExtension() {#a13af215927d8f3b7a48358c72b084ac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVISAInfo::isSupportedExtension (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext, unsigned MajorVersion, unsigned MinorVersion)</td>
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



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### isSupportedExtensionFeature() {#a06632f7f66681098316a7cbf42927d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVISAInfo::isSupportedExtensionFeature (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext)</td>
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



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a977bc5a442868c797e853e7c6bc0b57a">stripExperimentalPrefix</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ada43bee484c2300200c9ab0884003563">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitDirectiveOptionArch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvfeatures/#aeff18ccfe73c98dd2078d7523eb4db04">llvm::RISCVFeatures::parseFeatureBits</a>.</p>

</div>
</div>

### isSupportedExtensionWithVersion() {#afcd8b4904b4e18e880c419386dfe4d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVISAInfo::isSupportedExtensionWithVersion (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ext)</td>
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



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 989 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a3dba4372ba2b0183b65fcce9e61ca7bc">findLastNonVersionCharacter</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a>.</p>


<p>Referenced by <a href="#a24074750f6a79cbc564c654612b773ec">getTargetFeatureForExtension</a>.</p>

</div>
</div>

### parseArchString() {#aa18f12a3fd9c95854df97891e6d2c338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; std::unique_ptr&lt; RISCVISAInfo &gt; &gt; RISCVISAInfo::parseArchString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arch, bool EnableExperimentalExtension, bool ExperimentalExtensionVersionCheck=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Parse RISC-V ISA info from arch string.</p>


<p>If IgnoreUnknown is set, any unrecognised extension names or extensions with unrecognised versions will be silently dropped, except for the special case of the base 'i' and 'e' extensions, where the default version will be used (as ignoring the base is not possible).</p>


<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisautils/#a065d642864b925bfe666f5faf6020165">llvm::RISCVISAUtils::AllStdExts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a3ca5acfa0e6648c73a5143bfc0aa2ee1">findDefaultVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a3dba4372ba2b0183b65fcce9e61ca7bc">findLastNonVersionCharacter</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ad73113c3c3a7bfb64703238645f6fc1e">getError</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a85dc884f90867e8bd3fc2f4839de6fdc">getErrorForInvalidExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a81f19444c5002f0f7c4572fcab85299c">getExtensionType</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a114eafe1ddec6413592fe4c273012b48">getExtensionTypeDesc</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a12d4f37888b638bcbd9fc0201492c776">isDigit</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#aa1dadba0c2f6f1598969e8a239f7f6dd">isLower</a>, <a href="#aafe02ccc1e3c410eac85a36f70878f18">isSupportedExtension</a>, <a href="#aa18f12a3fd9c95854df97891e6d2c338">parseArchString</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp/#a009775794ead70aa23c76df46ab4ed8a">Profile</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#aec2828e79caa1587939e856e8f684a0a">RISCVGImplications</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a235f429dc68b7d26558f6d62634e96c9">RISCVGImplicationsZi</a>, <a href="#a35237f29879a5afa8b3d9017c7bea91a">RISCVISAInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b7d2ab11554bd10d15b6cb21b2c2787">llvm::upper_bound</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ada96d67c594bff6ca1c65fb281f82ca5">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitStartOfAsmFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a1db36bbf675fb1aea08484ef62220faf">llvm::RISCV::getFeaturesForCPU</a> and <a href="#aa18f12a3fd9c95854df97891e6d2c338">parseArchString</a>.</p>

</div>
</div>

### parseFeatures() {#ac44851c2ceedf8a3136d31773e0f20e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; std::unique_ptr&lt; RISCVISAInfo &gt; &gt; RISCVISAInfo::parseFeatures (unsigned XLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; Features)</td>
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

<p>Parse RISC-V ISA info from feature vector.</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="#a35237f29879a5afa8b3d9017c7bea91a">RISCVISAInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a977bc5a442868c797e853e7c6bc0b57a">stripExperimentalPrefix</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/riscvfeatures/#aeff18ccfe73c98dd2078d7523eb4db04">llvm::RISCVFeatures::parseFeatureBits</a>.</p>

</div>
</div>

### parseNormalizedArchString() {#a32990ca8b9376479e983ffed2e0fe9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; std::unique_ptr&lt; RISCVISAInfo &gt; &gt; RISCVISAInfo::parseNormalizedArchString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arch)</td>
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

<p>Parse RISC-V ISA info from an arch string that is already in normalized form (as defined in the psABI).</p>


<p>Unlike parseArchString, this function will not error for unrecognized extension names or extension versions.</p>


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ad73113c3c3a7bfb64703238645f6fc1e">getError</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a12d4f37888b638bcbd9fc0201492c776">isDigit</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#aa1dadba0c2f6f1598969e8a239f7f6dd">isLower</a>, <a href="#a35237f29879a5afa8b3d9017c7bea91a">RISCVISAInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>

</div>
</div>

### printEnabledExtensions() {#ab74c03e7b0136fcbc7195e1243e7a401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVISAInfo::printEnabledExtensions (bool IsRV64, std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; EnabledFeatureNames, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; DescMap)</td>
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



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="#aef85f28ebc1eb3f776d40a32e6f18f0d">createFromExtMap</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#af513f5818af71e93fabc6e30630ed3f2">llvm::StringMapImpl::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a9eeb6ab7ee4a2fd19e22f671d7ce32b2">PrintExtension</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

### printSupportedExtensions() {#ac192fe2b2eb30e2900fb5a9277432f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVISAInfo::printSupportedExtensions (<a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; DescMap)</td>
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



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#af513f5818af71e93fabc6e30630ed3f2">llvm::StringMapImpl::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a9eeb6ab7ee4a2fd19e22f671d7ce32b2">PrintExtension</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### postProcessAndChecking() {#a8571b20395549fe4d811883ef70644c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; std::unique_ptr&lt; RISCVISAInfo &gt; &gt; RISCVISAInfo::postProcessAndChecking (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo">RISCVISAInfo</a> &gt; &amp;&amp; ISAInfo)</td>
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



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>, definition at line 958 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### FeatureBitSize {#a06744fe29b0b03000d93a3de71838821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVISAInfo::FeatureBitSize = 2</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">RISCVISAInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp">RISCVISAInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
