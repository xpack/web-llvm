---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `BitcodeAnalyzer.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodeanalyzer-h">llvm/Bitcode/BitcodeAnalyzer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">llvm/Bitcode/BitcodeReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">llvm/Bitcode/LLVMBitCodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodes-h">llvm/Bitstream/BitCodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">llvm/Bitstream/BitstreamReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sha1-h">llvm/Support/SHA1.h</a>"
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb8af888c92e0b415ae5021d9c7a59a">reportError</a> (StringRef Message)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a61b4058a0d8fdb477afc3020adee5b">GetBlockName</a> (unsigned BlockID, const BitstreamBlockInfo &amp;BlockInfo, CurStreamTypeType CurStreamType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a symbolic block name if known, otherwise return null. <a href="#a1a61b4058a0d8fdb477afc3020adee5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0ea28d901a2351fedec9ef3deec2663">GetCodeName</a> (unsigned CodeID, unsigned BlockID, const BitstreamBlockInfo &amp;BlockInfo, CurStreamTypeType CurStreamType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a symbolic code name if known, otherwise return null. <a href="#ad0ea28d901a2351fedec9ef3deec2663">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad53301988259f6d90d009aedb2caf8d1">printSize</a> (raw_ostream &amp;OS, double Bits)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04be8461b79f2397e7353d9208ea95a5">printSize</a> (raw_ostream &amp;OS, uint64_t Bits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3">CurStreamTypeType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5668bfbe38566ca0b785a2361a4dcf8">ReadSignature</a> (BitstreamCursor &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3">CurStreamTypeType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebcf13b2162f23607396fffbf2b6ef7e">analyzeHeader</a> (std::optional&lt; BCDumpOptions &gt; O, BitstreamCursor &amp;Stream)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19de3085a4a247bb5dc110a4d4845358">canDecodeBlob</a> (unsigned Code, unsigned BlockID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c40bb7226e9c58fb3a13a3347a02c3c">STRINGIFY_CODE</a>(PREFIX, CODE)&nbsp;&nbsp;&nbsp;...</td>
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

## Functions

### analyzeHeader() {#aebcf13b2162f23607396fffbf2b6ef7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; CurStreamTypeType &gt; analyzeHeader (std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/bcdumpoptions">BCDumpOptions</a> &gt; O, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream)</td>
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



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a35ecf782614a4d3dd4fce5c373c25be5aa9197279828bc3d9c496e12ddef7cebb">llvm::BWH_CPUTypeField</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35ecf782614a4d3dd4fce5c373c25be5aa0bac122dc15039041afae282817da50">llvm::BWH_HeaderSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35ecf782614a4d3dd4fce5c373c25be5a985f1ac192423bce1eff2bdebf87cb2d">llvm::BWH_MagicField</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35ecf782614a4d3dd4fce5c373c25be5a294c560891082c28141beb9cd0b6c774">llvm::BWH_OffsetField</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35ecf782614a4d3dd4fce5c373c25be5ac93160dde10ce8f4f14af2a05c3f781f">llvm::BWH_SizeField</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35ecf782614a4d3dd4fce5c373c25be5a7ea126f72d3dab30cb47c6dac4b727ec">llvm::BWH_VersionField</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a3c1e5edb0f7b3cf4e57e2a4c3933d641">llvm::BitstreamCursor::getBitcodeBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4600455d814c9fad71f2da0ab5d7b33">llvm::isBitcodeWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="#aa5668bfbe38566ca0b785a2361a4dcf8">ReadSignature</a>, <a href="#aecb8af888c92e0b415ae5021d9c7a59a">reportError</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac0fd79668dfc1a7627b754817553138f">llvm::SkipBitcodeWrapperHeader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#add391ff06a593c4b9cb8f05b23882a51">llvm::BitcodeAnalyzer::analyze</a>.</p>

</div>
</div>

### canDecodeBlob() {#a19de3085a4a247bb5dc110a4d4845358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canDecodeBlob (unsigned Code, unsigned BlockID)</td>
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



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da6d85c95035de79006ae3a5dac19ee4a2">llvm::bitc::METADATA_BLOCK_ID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a1439ec3246fdaf3a3b4fb4f4e2683c5ca2a61d14a978b399c1b37c016a80a3924">llvm::bitc::METADATA_STRINGS</a>.</p>

</div>
</div>

### GetBlockName() {#a1a61b4058a0d8fdb477afc3020adee5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; const char * &gt; GetBlockName (unsigned BlockID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo">BitstreamBlockInfo</a> &amp; BlockInfo, <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3">CurStreamTypeType</a> CurStreamType)</td>
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

<p>Return a symbolic block name if known, otherwise return null.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a8cd4dd534ba6c31e93a88ca286c4f0e5a9c269366c4dc4af235c9bb24fa46f915">llvm::bitc::BLOCKINFO_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da48c634bc116b5df0bf52d60f96862947">llvm::bitc::CONSTANTS_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a8cd4dd534ba6c31e93a88ca286c4f0e5ace7b0ab991cf2f44fb20f2f69cd3fdaa">llvm::bitc::FIRST_APPLICATION_BLOCKID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daca3afe4e93910906ab7d0c2e3bd2b90e">llvm::bitc::FULL_LTO_GLOBALVAL_SUMMARY_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da7a137de095b15e7ec696da7678459677">llvm::bitc::FUNCTION_BLOCK_ID</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo/#a0bffe358b2eeea6540e85a510d611f54">llvm::BitstreamBlockInfo::getBlockInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da642102503aff012fc2975f165138b454">llvm::bitc::GLOBALVAL_SUMMARY_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da574b2844e8b4baab9239f12c1b6b0d04">llvm::bitc::IDENTIFICATION_BLOCK_ID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3ac2f3b5457891c08d4e42919a16542475">llvm::LLVMIRBitstream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da6553316df9fbe50417fd8e4630b90ef4">llvm::bitc::METADATA_ATTACHMENT_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da6d85c95035de79006ae3a5dac19ee4a2">llvm::bitc::METADATA_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da5747b302b28e31fd8879df26646da087">llvm::bitc::METADATA_KIND_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da31e5f441b78348934094a9dde0a326e2">llvm::bitc::MODULE_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daca3ed786c04791d9c4961711ebf6c294">llvm::bitc::MODULE_STRTAB_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daea440f1709f0443e3f8ca718ed2084d9">llvm::bitc::OPERAND_BUNDLE_TAGS_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da1bd41d0ca31f107397a953d9d266264b">llvm::bitc::PARAMATTR_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da4a716786c51cc39851c8bf53af9c538a">llvm::bitc::PARAMATTR_GROUP_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da33a2dbf49ae958238e75eb871a9f0b2e">llvm::bitc::STRTAB_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da466acfef0eae5774264a2115c0c1496a">llvm::bitc::SYMTAB_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da1e03bcd25d6c621851c52d1775f15c2a">llvm::bitc::TYPE_BLOCK_ID_NEW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daf34210783792fafaf34e0991cda79352">llvm::bitc::USELIST_BLOCK_ID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933dad03d0513adaa3462afbc7be6241b7db2">llvm::bitc::VALUE_SYMTAB_BLOCK_ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#aeaad4f1a2df47f25ea7e274d175c1b4e">llvm::BitcodeAnalyzer::printStats</a>.</p>

</div>
</div>

### GetCodeName() {#ad0ea28d901a2351fedec9ef3deec2663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; const char * &gt; GetCodeName (unsigned CodeID, unsigned BlockID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo">BitstreamBlockInfo</a> &amp; BlockInfo, <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3">CurStreamTypeType</a> CurStreamType)</td>
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

<p>Return a symbolic code name if known, otherwise return null.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a8cd4dd534ba6c31e93a88ca286c4f0e5a9c269366c4dc4af235c9bb24fa46f915">llvm::bitc::BLOCKINFO_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a6860684558cab9835254eba26b2f7963a3ab749cc5d99cccffd681c29da02fa74">llvm::bitc::BLOCKINFO_CODE_BLOCKNAME</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a6860684558cab9835254eba26b2f7963acf72b4b5b2c1c5b1310721a6715ab010">llvm::bitc::BLOCKINFO_CODE_SETBID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a6860684558cab9835254eba26b2f7963aad1225e67df2c8e94135a067eb3f212e">llvm::bitc::BLOCKINFO_CODE_SETRECORDNAME</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da48c634bc116b5df0bf52d60f96862947">llvm::bitc::CONSTANTS_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2f7b2c9070dd196b7bad476149a7ece1a0a3559a40967f759fb2678b53fd6fbfc">llvm::bitc::CST_CODE_BLOCKADDRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a8cd4dd534ba6c31e93a88ca286c4f0e5ace7b0ab991cf2f44fb20f2f69cd3fdaa">llvm::bitc::FIRST_APPLICATION_BLOCKID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daca3afe4e93910906ab7d0c2e3bd2b90e">llvm::bitc::FULL_LTO_GLOBALVAL_SUMMARY_BLOCK_ID</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/fpenv-cpp/#af03a9549e7632dcca1a384646da10642">FUNCTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da7a137de095b15e7ec696da7678459677">llvm::bitc::FUNCTION_BLOCK_ID</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamblockinfo/#a0bffe358b2eeea6540e85a510d611f54">llvm::BitstreamBlockInfo::getBlockInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da642102503aff012fc2975f165138b454">llvm::bitc::GLOBALVAL_SUMMARY_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da574b2844e8b4baab9239f12c1b6b0d04">llvm::bitc::IDENTIFICATION_BLOCK_ID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">KIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3ac2f3b5457891c08d4e42919a16542475">llvm::LLVMIRBitstream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da6553316df9fbe50417fd8e4630b90ef4">llvm::bitc::METADATA_ATTACHMENT_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da6d85c95035de79006ae3a5dac19ee4a2">llvm::bitc::METADATA_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da5747b302b28e31fd8879df26646da087">llvm::bitc::METADATA_KIND_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51e547c2283920aa77da2650a8ee3a7aa6b7748115db77a5a98a54363b6c74203">llvm::MODULE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da31e5f441b78348934094a9dde0a326e2">llvm::bitc::MODULE_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daca3ed786c04791d9c4961711ebf6c294">llvm::bitc::MODULE_STRTAB_BLOCK_ID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ad845c77e0ea7840ac74d2fa3868ba88d">NODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abfc8b6b0a946284c6f212eda73571106a03b8f2c0149ad8e7b2333fd069569571">llvm::bitc::OPERAND_BUNDLE_TAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daea440f1709f0443e3f8ca718ed2084d9">llvm::bitc::OPERAND_BUNDLE_TAGS_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da1bd41d0ca31f107397a953d9d266264b">llvm::bitc::PARAMATTR_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ac2c80c9b0f575d0333db3cd06da1e51ea7c886568e5c7b7c735e6f3d5ebfb2973">llvm::bitc::PARAMATTR_CODE_ENTRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ac2c80c9b0f575d0333db3cd06da1e51ea24913f2946317d4d3ecf12f900dbd16e">llvm::bitc::PARAMATTR_CODE_ENTRY_OLD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da4a716786c51cc39851c8bf53af9c538a">llvm::bitc::PARAMATTR_GROUP_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ac2c80c9b0f575d0333db3cd06da1e51ea65f8f2ba217d264a39a43fb0b5560a10">llvm::bitc::PARAMATTR_GRP_CODE_ENTRY</a>, <a href="#a0c40bb7226e9c58fb3a13a3347a02c3c">STRINGIFY_CODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aa5f5b04f18dd0147ec2e2ee1dff56c06a8a6e8086acc7a4f894b953311c088549">llvm::bitc::STRTAB_BLOB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da33a2dbf49ae958238e75eb871a9f0b2e">llvm::bitc::STRTAB_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aeb428612b856bd084feccd8f480330dea1329b6bf1ed0b214660309e1a7e4e04c">llvm::bitc::SYMTAB_BLOB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da466acfef0eae5774264a2115c0c1496a">llvm::bitc::SYMTAB_BLOCK_ID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/windowsresource/resourcescripttoken-h/#a19b22269edb285d6af9f6408f276302a">TOKEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da1e03bcd25d6c621851c52d1775f15c2a">llvm::bitc::TYPE_BLOCK_ID_NEW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daf34210783792fafaf34e0991cda79352">llvm::bitc::USELIST_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a77f340cd374889c5a53b3ab26f47ef95a028a27c988ff91790cb09a4cb6969ca2">llvm::bitc::USELIST_CODE_BB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a77f340cd374889c5a53b3ab26f47ef95aa6f510bdef07b7872c929674b3f7b011">llvm::bitc::USELIST_CODE_DEFAULT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933dad03d0513adaa3462afbc7be6241b7db2">llvm::bitc::VALUE_SYMTAB_BLOCK_ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#aeaad4f1a2df47f25ea7e274d175c1b4e">llvm::BitcodeAnalyzer::printStats</a>.</p>

</div>
</div>

### printSize() {#ad53301988259f6d90d009aedb2caf8d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printSize (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, double Bits)</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#aeaad4f1a2df47f25ea7e274d175c1b4e">llvm::BitcodeAnalyzer::printStats</a>.</p>

</div>
</div>

### printSize() {#a04be8461b79f2397e7353d9208ea95a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printSize (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Bits)</td>
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



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>.</p>

</div>
</div>

### ReadSignature() {#aa5668bfbe38566ca0b785a2361a4dcf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; CurStreamTypeType &gt; ReadSignature (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream)</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3ad79dda94ab5cce4dd8c7c36d833f77c2">llvm::ClangSerializedASTBitstream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3a6cf666b14a022d64dec209e643149350">llvm::ClangSerializedDiagnosticsBitstream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3adbcc2ed1fc45de2b53775e8bc8a748e1">llvm::LLVMBitstreamRemarks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3ac2f3b5457891c08d4e42919a16542475">llvm::LLVMIRBitstream</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a455d3003d7f58d83850c9f33c259d3bf">llvm::BitstreamCursor::Read</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab313f8a023b8259fb27cc18af0d999d3a58a116f7665129a297e7d7135bcd0853">llvm::UnknownBitstream</a>.</p>


<p>Referenced by <a href="#aebcf13b2162f23607396fffbf2b6ef7e">analyzeHeader</a>.</p>

</div>
</div>

### reportError() {#aecb8af888c92e0b415ae5021d9c7a59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error reportError (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Message)</td>
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



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#add391ff06a593c4b9cb8f05b23882a51">llvm::BitcodeAnalyzer::analyze</a>, <a href="#aebcf13b2162f23607396fffbf2b6ef7e">analyzeHeader</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64targettransforminfo-cpp-/tailfoldingoption/#a5df8b2fca0d3dc356531c2f218468d2f">anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### STRINGIFY\_CODE {#a0c40bb7226e9c58fb3a13a3347a02c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define STRINGIFY_CODE(PREFIX, CODE)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case bitc::PREFIX##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##CODE:                                                  \
    return #CODE;
</div>
</dd>
</dl>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp">BitcodeAnalyzer.cpp</a>.</p>


<p>Referenced by <a href="#ad0ea28d901a2351fedec9ef3deec2663">GetCodeName</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
