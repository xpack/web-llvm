---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/loongarchabi
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `LoongArchABI` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::LoongArchABI { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ABI { <a href="#a19370946dd9514a9d3e18275e9f7b6fb">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a19370946dd9514a9d3e18275e9f7b6fb">ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1455e394db66c8dcd49ca40a901ad169">checkABIStandardized</a> (ABI Abi)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a19370946dd9514a9d3e18275e9f7b6fb">ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c05d40008f164ab08d50a05563111c">getTripleABI</a> (const Triple &amp;TT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a19370946dd9514a9d3e18275e9f7b6fb">ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af00c65f1a835c8452272468c2f09bd18">computeTargetABI</a> (const Triple &amp;TT, const FeatureBitset &amp;FeatureBits, StringRef ABIName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a19370946dd9514a9d3e18275e9f7b6fb">ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8217dcfbfb9f249429cf83c5b9dc107">getTargetABI</a> (StringRef ABIName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52c76c78d8c7899d21f8466677f676a9">getBPReg</a> ()</td>
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

### ABI {#a19370946dd9514a9d3e18275e9f7b6fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LoongArchABI::ABI </td>
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
<td class="doxyEnumItemName">ABI_ILP32S<a id="a19370946dd9514a9d3e18275e9f7b6fba305d5ae54529960b7995ea72126052b9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_ILP32F<a id="a19370946dd9514a9d3e18275e9f7b6fba63a439edbbd4d87298181cbcf098e233"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_ILP32D<a id="a19370946dd9514a9d3e18275e9f7b6fba7642477c0b9114a91ab95db52b0bf513"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_LP64S<a id="a19370946dd9514a9d3e18275e9f7b6fba30063a83b98d2cffbcf49f46a8db223f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_LP64F<a id="a19370946dd9514a9d3e18275e9f7b6fba09b260d81c6fe1cdf0386e65e5e3d5e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_LP64D<a id="a19370946dd9514a9d3e18275e9f7b6fbae688d614de378b5e595020a7ac3c378c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABI_Unknown<a id="a19370946dd9514a9d3e18275e9f7b6fbab3d8d71ca8b3f20b7551c6db0b02a9da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-h">LoongArchBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### checkABIStandardized() {#a1455e394db66c8dcd49ca40a901ad169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ABI llvm::LoongArchABI::checkABIStandardized (<a href="#a19370946dd9514a9d3e18275e9f7b6fb">ABI</a> Abi)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-cpp">LoongArchBaseInfo.cpp</a>.</p>


<p>References <a href="#a19370946dd9514a9d3e18275e9f7b6fba7642477c0b9114a91ab95db52b0bf513">ABI_ILP32D</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba63a439edbbd4d87298181cbcf098e233">ABI_ILP32F</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba305d5ae54529960b7995ea72126052b9">ABI_ILP32S</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fbae688d614de378b5e595020a7ac3c378c">ABI_LP64D</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba09b260d81c6fe1cdf0386e65e5e3d5e4">ABI_LP64F</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba30063a83b98d2cffbcf49f46a8db223f">ABI_LP64S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#af00c65f1a835c8452272468c2f09bd18">computeTargetABI</a>.</p>

</div>
</div>

### computeTargetABI() {#af00c65f1a835c8452272468c2f09bd18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ABI llvm::LoongArchABI::computeTargetABI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; FeatureBits, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ABIName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-cpp">LoongArchBaseInfo.cpp</a>.</p>


<p>References <a href="#a19370946dd9514a9d3e18275e9f7b6fba7642477c0b9114a91ab95db52b0bf513">ABI_ILP32D</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba63a439edbbd4d87298181cbcf098e233">ABI_ILP32F</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba305d5ae54529960b7995ea72126052b9">ABI_ILP32S</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fbae688d614de378b5e595020a7ac3c378c">ABI_LP64D</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba09b260d81c6fe1cdf0386e65e5e3d5e4">ABI_LP64F</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba30063a83b98d2cffbcf49f46a8db223f">ABI_LP64S</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fbab3d8d71ca8b3f20b7551c6db0b02a9da">ABI_Unknown</a>, <a href="#a1455e394db66c8dcd49ca40a901ad169">checkABIStandardized</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#af8217dcfbfb9f249429cf83c5b9dc107">getTargetABI</a>, <a href="#a84c05d40008f164ab08d50a05563111c">getTripleABI</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetelfstreamer/#aedd14021422c2f6fba707ef8188d6d28">llvm::LoongArchTargetELFStreamer::LoongArchTargetELFStreamer</a>.</p>

</div>
</div>

### getBPReg() {#a52c76c78d8c7899d21f8466677f676a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::LoongArchABI::getBPReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-cpp">LoongArchBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loongarchregisterinfo/#ab65e9927fad0d0edd47ffed7f1bfb2bf">llvm::LoongArchRegisterInfo::canRealignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a759033addb47f61385c08c441120184a">llvm::LoongArchFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a0f71a92dc6f774b7059d9490a29d52ad">llvm::LoongArchFrameLowering::getFrameIndexReference</a> and <a href="/web-llvm/docs/api/structs/llvm/loongarchregisterinfo/#a996c657889038c51217898181b61f455">llvm::LoongArchRegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### getTargetABI() {#af8217dcfbfb9f249429cf83c5b9dc107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ABI llvm::LoongArchABI::getTargetABI (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ABIName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-cpp">LoongArchBaseInfo.cpp</a>.</p>


<p>References <a href="#a19370946dd9514a9d3e18275e9f7b6fba7642477c0b9114a91ab95db52b0bf513">ABI_ILP32D</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba63a439edbbd4d87298181cbcf098e233">ABI_ILP32F</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba305d5ae54529960b7995ea72126052b9">ABI_ILP32S</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fbae688d614de378b5e595020a7ac3c378c">ABI_LP64D</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba09b260d81c6fe1cdf0386e65e5e3d5e4">ABI_LP64F</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba30063a83b98d2cffbcf49f46a8db223f">ABI_LP64S</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fbab3d8d71ca8b3f20b7551c6db0b02a9da">ABI_Unknown</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a> and <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>


<p>Referenced by <a href="#af00c65f1a835c8452272468c2f09bd18">computeTargetABI</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#ac0030767228d11167dfbe14d6c0d369b">llvm::LoongArchTargetMachine::getSubtargetImpl</a>.</p>

</div>
</div>

### getTripleABI() {#a84c05d40008f164ab08d50a05563111c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ABI llvm::LoongArchABI::getTripleABI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-cpp">LoongArchBaseInfo.cpp</a>.</p>


<p>References <a href="#a19370946dd9514a9d3e18275e9f7b6fba7642477c0b9114a91ab95db52b0bf513">ABI_ILP32D</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba63a439edbbd4d87298181cbcf098e233">ABI_ILP32F</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba305d5ae54529960b7995ea72126052b9">ABI_ILP32S</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fbae688d614de378b5e595020a7ac3c378c">ABI_LP64D</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba09b260d81c6fe1cdf0386e65e5e3d5e4">ABI_LP64F</a>, <a href="#a19370946dd9514a9d3e18275e9f7b6fba30063a83b98d2cffbcf49f46a8db223f">ABI_LP64S</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a61ce851e1f60ad25421987629f5ac2c2">llvm::Triple::GNUF32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a587bfd81081ee91855e23c7cc05d4487">llvm::Triple::GNUF64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a9953bc1a6bb23d4a733faf9afb0df99a">llvm::Triple::GNUSF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a66008454cd4031dad58b64c0eae7f9e4">llvm::Triple::MuslF32</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324aff5daa73e757da85e8803ea0e323d5b0">llvm::Triple::MuslSF</a>.</p>


<p>Referenced by <a href="#af00c65f1a835c8452272468c2f09bd18">computeTargetABI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-cpp">LoongArchBaseInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchbaseinfo-h">LoongArchBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
