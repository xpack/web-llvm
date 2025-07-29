---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/aarch64cc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `AArch64CC` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AArch64CC { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CondCode { <a href="#abfa1f7dce576430da99eed57807c7f28">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ca6ef2f5cc21570610580d628314c5">getCondCodeName</a> (CondCode Code)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#abfa1f7dce576430da99eed57807c7f28">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2ebeb83373be407903e43096e4f7b9">getInvertedCondCode</a> (CondCode Code)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#abfa1f7dce576430da99eed57807c7f28">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8830377a975899c6e40a49d3501f1e63">getSwappedCondition</a> (CondCode CC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSwappedCondition - assume the flags are set by <a href="#abfa1f7dce576430da99eed57807c7f28a913fd2deccaf3e27694eefb90ffeee00">MI(a,b)</a>, return the condition code if we modify the instructions such that flags are set by <a href="#abfa1f7dce576430da99eed57807c7f28a913fd2deccaf3e27694eefb90ffeee00">MI(b,a)</a>. <a href="#a8830377a975899c6e40a49d3501f1e63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affed553a12fdb2f42041ea371820e01f">getNZCVToSatisfyCondCode</a> (CondCode Code)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a condition code, return NZCV flags that would satisfy that condition. <a href="#affed553a12fdb2f42041ea371820e01f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### CondCode {#abfa1f7dce576430da99eed57807c7f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64CC::CondCode </td>
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
<td class="doxyEnumItemName">EQ<a id="abfa1f7dce576430da99eed57807c7f28a756347c46f7abfa1e1fefcc39502c680"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NE<a id="abfa1f7dce576430da99eed57807c7f28a191e89dbc4939ebd0b572cae44aac05f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HS<a id="abfa1f7dce576430da99eed57807c7f28a7d0223b39a4cf6354c08b3d7fcc35630"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LO<a id="abfa1f7dce576430da99eed57807c7f28ab620924321db413fcc748afe522c2303"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MI<a id="abfa1f7dce576430da99eed57807c7f28a913fd2deccaf3e27694eefb90ffeee00"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PL<a id="abfa1f7dce576430da99eed57807c7f28a5b3c2afaad5594cd0eedd58a78a91baf"></a></td>
<td class="doxyEnumItemDescription"> (= 0x5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VS<a id="abfa1f7dce576430da99eed57807c7f28a9f54e5976c204d779cee3d87cabf0b02"></a></td>
<td class="doxyEnumItemDescription"> (= 0x6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VC<a id="abfa1f7dce576430da99eed57807c7f28a0be9a5b045e14f589506ab6372ab6592"></a></td>
<td class="doxyEnumItemDescription"> (= 0x7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HI<a id="abfa1f7dce576430da99eed57807c7f28aa5506efe3dc67f7b794331f0cbffddaf"></a></td>
<td class="doxyEnumItemDescription"> (= 0x8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LS<a id="abfa1f7dce576430da99eed57807c7f28afdd8238d6005774fe2bb9067de76eb8c"></a></td>
<td class="doxyEnumItemDescription"> (= 0x9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GE<a id="abfa1f7dce576430da99eed57807c7f28a2f9f5539ad5eab7c3de9fb21766bc78b"></a></td>
<td class="doxyEnumItemDescription"> (= 0xa)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LT<a id="abfa1f7dce576430da99eed57807c7f28a968f33165430f95099556df970a6336a"></a></td>
<td class="doxyEnumItemDescription"> (= 0xb)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GT<a id="abfa1f7dce576430da99eed57807c7f28a91a0c1b4eac415607c4ceb0a899c4629"></a></td>
<td class="doxyEnumItemDescription"> (= 0xc)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LE<a id="abfa1f7dce576430da99eed57807c7f28aeb67eda6b42e3237bc28fb457347a1cb"></a></td>
<td class="doxyEnumItemDescription"> (= 0xd)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AL<a id="abfa1f7dce576430da99eed57807c7f28ab89adee997fb2a645a2d26e1f1bdaadf"></a></td>
<td class="doxyEnumItemDescription"> (= 0xe)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NV<a id="abfa1f7dce576430da99eed57807c7f28af30bd33ca066862c72c3dd3bd128443d"></a></td>
<td class="doxyEnumItemDescription"> (= 0xf)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Invalid<a id="abfa1f7dce576430da99eed57807c7f28aef225b7df5953a2942e07071d0013eb0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ANY_ACTIVE<a id="abfa1f7dce576430da99eed57807c7f28adb8287192c5585b20e3ea2c98993bebd"></a></td>
<td class="doxyEnumItemDescription"> (= NE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_ACTIVE<a id="abfa1f7dce576430da99eed57807c7f28ab1cfdce38915d998074cf27a5ec3f074"></a></td>
<td class="doxyEnumItemDescription"> (= MI)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_ACTIVE<a id="abfa1f7dce576430da99eed57807c7f28a6593179bd61073e54da03c9cda51f836"></a></td>
<td class="doxyEnumItemDescription"> (= LO)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NONE_ACTIVE<a id="abfa1f7dce576430da99eed57807c7f28a0cbfa80519ca730da8d6090e86f1d9dd"></a></td>
<td class="doxyEnumItemDescription"> (= EQ)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64baseinfo-h">AArch64BaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getCondCodeName() {#af2ca6ef2f5cc21570610580d628314c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AArch64CC::getCondCodeName (<a href="#abfa1f7dce576430da99eed57807c7f28">CondCode</a> Code)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64baseinfo-h">AArch64BaseInfo.h</a>.</p>


<p>References <a href="#abfa1f7dce576430da99eed57807c7f28ab89adee997fb2a645a2d26e1f1bdaadf">AL</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a756347c46f7abfa1e1fefcc39502c680">EQ</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a2f9f5539ad5eab7c3de9fb21766bc78b">GE</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a91a0c1b4eac415607c4ceb0a899c4629">GT</a>, <a href="#abfa1f7dce576430da99eed57807c7f28aa5506efe3dc67f7b794331f0cbffddaf">HI</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a7d0223b39a4cf6354c08b3d7fcc35630">HS</a>, <a href="#abfa1f7dce576430da99eed57807c7f28aeb67eda6b42e3237bc28fb457347a1cb">LE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#abfa1f7dce576430da99eed57807c7f28ab620924321db413fcc748afe522c2303">LO</a>, <a href="#abfa1f7dce576430da99eed57807c7f28afdd8238d6005774fe2bb9067de76eb8c">LS</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a968f33165430f95099556df970a6336a">LT</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a913fd2deccaf3e27694eefb90ffeee00">MI</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a191e89dbc4939ebd0b572cae44aac05f">NE</a>, <a href="#abfa1f7dce576430da99eed57807c7f28af30bd33ca066862c72c3dd3bd128443d">NV</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a5b3c2afaad5594cd0eedd58a78a91baf">PL</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a0be9a5b045e14f589506ab6372ab6592">VC</a> and <a href="#abfa1f7dce576430da99eed57807c7f28a9f54e5976c204d779cee3d87cabf0b02">VS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/ssaccmpconv/#a545b0c16154dffb0ddba86968d798e2f">anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::canConvert</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a28b558fd425cf7678e32a6866e3bda69">llvm::AArch64InstPrinter::printCondCode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#af0d299a16d974eae0d98f96bc7df2308">llvm::AArch64InstPrinter::printInverseCondCode</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#a1ee52a66badadfe0d31d88d614305f41">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::runOnMachineFunction</a>.</p>

</div>
</div>

### getInvertedCondCode() {#afc2ebeb83373be407903e43096e4f7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CondCode llvm::AArch64CC::getInvertedCondCode (<a href="#abfa1f7dce576430da99eed57807c7f28">CondCode</a> Code)</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64baseinfo-h">AArch64BaseInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/ssaccmpconv/#a545b0c16154dffb0ddba86968d798e2f">anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::canConvert</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instrinfo-cpp-/aarch64pipelinerloopinfo/#a3225760dca7855181b535133948ea278">anonymous{AArch64InstrInfo.cpp}::AArch64PipelinerLoopInfo::createRemainingIterationsGreaterCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a02f6de82e3085eef9b1ad0ebe9b2d500">emitConditionalComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a588e5dcf7ccf9ec2b6922f24c012a08a">emitConjunctionRec</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a54a58a0466a38d38cc1fc0c57513195f">foldCSELOfCSEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af46d1ba5c3f2f00b06659c2ba7dc5c7c">getAArch64Cmp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a029c7ad54d8731492ed559aa860e3395">llvm::AArch64InstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0d5f95075554b414bb1d785124a656e2">isSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af0bbac5dd9f698f2c73477c4e5f36b60">llvm::AArch64InstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae2006316fe1239e3e559f680aa00e365">performAddCSelIntoCSinc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4764dd7a5c84db5880e9d37d5c1ce949">performANDORCSELCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afc0543ffe712dea27f610e198260fc8b">performANDSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a434e132c04f973b024b815eaad19165f">performSetccAddFolding</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#af0d299a16d974eae0d98f96bc7df2308">llvm::AArch64InstPrinter::printInverseCondCode</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7cca5afbdfdcb468161ffe0b888668d0">llvm::AArch64InstrInfo::reverseBranchCondition</a>.</p>

</div>
</div>

### getNZCVToSatisfyCondCode() {#affed553a12fdb2f42041ea371820e01f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64CC::getNZCVToSatisfyCondCode (<a href="#abfa1f7dce576430da99eed57807c7f28">CondCode</a> Code)</td>
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

<p>Given a condition code, return NZCV flags that would satisfy that condition.</p>


<p>The flag bits are in the format expected by the ccmp instructions. Note that many different flag settings can satisfy a given condition code, this function just returns one of them.</p>


<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64baseinfo-h">AArch64BaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a756347c46f7abfa1e1fefcc39502c680">EQ</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a2f9f5539ad5eab7c3de9fb21766bc78b">GE</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a91a0c1b4eac415607c4ceb0a899c4629">GT</a>, <a href="#abfa1f7dce576430da99eed57807c7f28aa5506efe3dc67f7b794331f0cbffddaf">HI</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a7d0223b39a4cf6354c08b3d7fcc35630">HS</a>, <a href="#abfa1f7dce576430da99eed57807c7f28aeb67eda6b42e3237bc28fb457347a1cb">LE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#abfa1f7dce576430da99eed57807c7f28ab620924321db413fcc748afe522c2303">LO</a>, <a href="#abfa1f7dce576430da99eed57807c7f28afdd8238d6005774fe2bb9067de76eb8c">LS</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a968f33165430f95099556df970a6336a">LT</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a913fd2deccaf3e27694eefb90ffeee00">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a191e89dbc4939ebd0b572cae44aac05f">NE</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a5b3c2afaad5594cd0eedd58a78a91baf">PL</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a0be9a5b045e14f589506ab6372ab6592">VC</a> and <a href="#abfa1f7dce576430da99eed57807c7f28a9f54e5976c204d779cee3d87cabf0b02">VS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/ssaccmpconv/#a8c2c7a46bf3359100068e45134218920">anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a02f6de82e3085eef9b1ad0ebe9b2d500">emitConditionalComparison</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4764dd7a5c84db5880e9d37d5c1ce949">performANDORCSELCombine</a>.</p>

</div>
</div>

### getSwappedCondition() {#a8830377a975899c6e40a49d3501f1e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CondCode llvm::AArch64CC::getSwappedCondition (<a href="#abfa1f7dce576430da99eed57807c7f28">CondCode</a> CC)</td>
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

<p>getSwappedCondition - assume the flags are set by <a href="#abfa1f7dce576430da99eed57807c7f28a913fd2deccaf3e27694eefb90ffeee00">MI(a,b)</a>, return the condition code if we modify the instructions such that flags are set by <a href="#abfa1f7dce576430da99eed57807c7f28a913fd2deccaf3e27694eefb90ffeee00">MI(b,a)</a>.</p>

<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64baseinfo-h">AArch64BaseInfo.h</a>.</p>


<p>References <a href="#abfa1f7dce576430da99eed57807c7f28ab89adee997fb2a645a2d26e1f1bdaadf">AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a756347c46f7abfa1e1fefcc39502c680">EQ</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a2f9f5539ad5eab7c3de9fb21766bc78b">GE</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a91a0c1b4eac415607c4ceb0a899c4629">GT</a>, <a href="#abfa1f7dce576430da99eed57807c7f28aa5506efe3dc67f7b794331f0cbffddaf">HI</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a7d0223b39a4cf6354c08b3d7fcc35630">HS</a>, <a href="#abfa1f7dce576430da99eed57807c7f28aeb67eda6b42e3237bc28fb457347a1cb">LE</a>, <a href="#abfa1f7dce576430da99eed57807c7f28ab620924321db413fcc748afe522c2303">LO</a>, <a href="#abfa1f7dce576430da99eed57807c7f28afdd8238d6005774fe2bb9067de76eb8c">LS</a>, <a href="#abfa1f7dce576430da99eed57807c7f28a968f33165430f95099556df970a6336a">LT</a> and <a href="#abfa1f7dce576430da99eed57807c7f28a191e89dbc4939ebd0b572cae44aac05f">NE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64baseinfo-h">AArch64BaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
