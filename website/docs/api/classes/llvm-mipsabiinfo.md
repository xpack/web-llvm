---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipsabiinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MipsABIInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MipsABIInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">Target/Mips/MCTargetDesc/MipsABIInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ABI { <a href="#a0a7cb81026c8f99a3acb10520e669578">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c61ea10fcd6e85592b6c02eb3699a7">MipsABIInfo</a> (ABI ThisABI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6512d0f8b12785db4500487e4e76551f">operator&lt;</a> (const MipsABIInfo Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ordering of <a href="#a0a7cb81026c8f99a3acb10520e669578">ABI</a>'s MipsGenSubtargetInfo.inc will use this to resolve conflicts when given multiple <a href="#a0a7cb81026c8f99a3acb10520e669578">ABI</a> options. <a href="#a6512d0f8b12785db4500487e4e76551f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b79202578f3154d255986af2dcbb06">IsKnown</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb3a7a1d98e9fbb76e87a71aafdbc6d">IsO32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac59352a7ddd52db0dabe853439909dc6">IsN32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0630cff2e64996376ddcaa94211c4eac">IsN64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0a7cb81026c8f99a3acb10520e669578">ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a083bc49c362923774e17b4930a8476b9">GetEnumValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa682266c506cc18c1949775a7886ed08">GetByValArgRegs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The registers to use for byval arguments. <a href="#aa682266c506cc18c1949775a7886ed08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20d7e1d4427cdefab35b5bd104f9f523">GetVarArgRegs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The registers to use for the variable argument list. <a href="#a20d7e1d4427cdefab35b5bd104f9f523">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5827191810a64527509ddc04472c4a07">GetCalleeAllocdArgSizeInBytes</a> (CallingConv::ID CC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the size of the area allocated by the callee for arguments. <a href="#a5827191810a64527509ddc04472c4a07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45acf10e3fa054fb114f5cad80d98bae">GetStackPtr</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2780f625a6691e866aa0a34556fc3a">GetFramePtr</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca51a53566aa81408345e5e29c8bacb2">GetBasePtr</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06c1c614fb8e1240ee98815d6c1ba4f0">GetGlobalPtr</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9e3696aa316a1d862931ad0c858e09b">GetNullPtr</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a550835f67b4830bb7c19218e6d6566ef">GetZeroReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe8ed016793fcba9cb5301e90025840d">GetPtrAdduOp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656432cd552486086064a5af478c8b07">GetPtrAddiuOp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb0e923f97df02841ea645644c2bc035">GetPtrSubuOp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7135f4d7ca1aaadc2f5d2f93c9dbda51">GetPtrAndOp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a301ece4a7472f2b8bcf8598a92fb61d3">GetGPRMoveOp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0551766c1aa7fa28012947a1cbd2f0ce">AreGprs64bit</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e91c4477e0bd5aeb3623c9deecab93b">GetEhDataReg</a> (unsigned I) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0a7cb81026c8f99a3acb10520e669578">ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae91e4f8d024c12f832f145949441c3b8">ThisABI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92db0d6559f297c89c2ebc01819e33fd">Unknown</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11526f61f6c73d495cd72ff6bd688dfd">O32</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f6189dad91aa91e65bb954b0a4cfab">N32</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e17d38855b4505b183e0a3d75040c81">N64</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e5ac48dc2d9e13a26e34521926876a">computeTargetABI</a> (const Triple &amp;TT, StringRef CPU, const MCTargetOptions &amp;Options)</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ABI {#a0a7cb81026c8f99a3acb10520e669578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::MipsABIInfo::ABI </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Unknown<a id="a0a7cb81026c8f99a3acb10520e669578a88183b946cc5f0e8c96b2e66e1c74a7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">O32<a id="a0a7cb81026c8f99a3acb10520e669578a9d0dce15ea3c51e2da2071c10d59e896"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N32<a id="a0a7cb81026c8f99a3acb10520e669578ad71d06768593fa82be8fd84d1f8a33c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N64<a id="a0a7cb81026c8f99a3acb10520e669578a7ac2840a241d00a82aa085fa66622bd1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MipsABIInfo() {#a14c61ea10fcd6e85592b6c02eb3699a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MipsABIInfo::MipsABIInfo (<a href="#a0a7cb81026c8f99a3acb10520e669578">ABI</a> ThisABI)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>Reference <a href="#ae91e4f8d024c12f832f145949441c3b8">ThisABI</a>.</p>


<p>Referenced by <a href="#a87e5ac48dc2d9e13a26e34521926876a">computeTargetABI</a>, <a href="#a49f6189dad91aa91e65bb954b0a4cfab">N32</a>, <a href="#a5e17d38855b4505b183e0a3d75040c81">N64</a>, <a href="#a11526f61f6c73d495cd72ff6bd688dfd">O32</a>, <a href="#a6512d0f8b12785db4500487e4e76551f">operator&lt;</a> and <a href="#a92db0d6559f297c89c2ebc01819e33fd">Unknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a6512d0f8b12785db4500487e4e76551f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsABIInfo::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a> Other)</td>
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

<p>Ordering of <a href="#a0a7cb81026c8f99a3acb10520e669578">ABI</a>'s MipsGenSubtargetInfo.inc will use this to resolve conflicts when given multiple <a href="#a0a7cb81026c8f99a3acb10520e669578">ABI</a> options.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>References <a href="#a14c61ea10fcd6e85592b6c02eb3699a7">MipsABIInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae91e4f8d024c12f832f145949441c3b8">ThisABI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AreGprs64bit() {#a0551766c1aa7fa28012947a1cbd2f0ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsABIInfo::AreGprs64bit ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>References <a href="#ac59352a7ddd52db0dabe853439909dc6">IsN32</a> and <a href="#a0630cff2e64996376ddcaa94211c4eac">IsN64</a>.</p>


<p>Referenced by <a href="#a550835f67b4830bb7c19218e6d6566ef">GetZeroReg</a>.</p>

</div>
</div>

### ArePtrs64bit() {#a2a988fc1c2adb8253ffbb3c297a5624c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsABIInfo::ArePtrs64bit ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>Reference <a href="#a0630cff2e64996376ddcaa94211c4eac">IsN64</a>.</p>


<p>Referenced by <a href="#aca51a53566aa81408345e5e29c8bacb2">GetBasePtr</a>, <a href="#a7d2780f625a6691e866aa0a34556fc3a">GetFramePtr</a>, <a href="#a06c1c614fb8e1240ee98815d6c1ba4f0">GetGlobalPtr</a>, <a href="#a301ece4a7472f2b8bcf8598a92fb61d3">GetGPRMoveOp</a>, <a href="#aa9e3696aa316a1d862931ad0c858e09b">GetNullPtr</a>, <a href="#a656432cd552486086064a5af478c8b07">GetPtrAddiuOp</a>, <a href="#abe8ed016793fcba9cb5301e90025840d">GetPtrAdduOp</a>, <a href="#a7135f4d7ca1aaadc2f5d2f93c9dbda51">GetPtrAndOp</a>, <a href="#acb0e923f97df02841ea645644c2bc035">GetPtrSubuOp</a> and <a href="#a45acf10e3fa054fb114f5cad80d98bae">GetStackPtr</a>.</p>

</div>
</div>

### GetBasePtr() {#aca51a53566aa81408345e5e29c8bacb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetBasePtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>Reference <a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a>.</p>

</div>
</div>

### GetByValArgRegs() {#aa682266c506cc18c1949775a7886ed08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; MipsABIInfo::GetByValArgRegs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The registers to use for byval arguments.</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#ac59352a7ddd52db0dabe853439909dc6">IsN32</a>, <a href="#a0630cff2e64996376ddcaa94211c4eac">IsN64</a>, <a href="#aefb3a7a1d98e9fbb76e87a71aafdbc6d">IsO32</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### GetCalleeAllocdArgSizeInBytes() {#a5827191810a64527509ddc04472c4a07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetCalleeAllocdArgSizeInBytes (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the size of the area allocated by the callee for arguments.</p>


<p>CallingConv::FastCall affects the value for O32.</p>


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="#ac59352a7ddd52db0dabe853439909dc6">IsN32</a>, <a href="#a0630cff2e64996376ddcaa94211c4eac">IsN64</a>, <a href="#aefb3a7a1d98e9fbb76e87a71aafdbc6d">IsO32</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### GetEhDataReg() {#a1e91c4477e0bd5aeb3623c9deecab93b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetEhDataReg (unsigned I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a0630cff2e64996376ddcaa94211c4eac">IsN64</a>.</p>

</div>
</div>

### GetEnumValue() {#a083bc49c362923774e17b4930a8476b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ABI llvm::MipsABIInfo::GetEnumValue ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>Reference <a href="#ae91e4f8d024c12f832f145949441c3b8">ThisABI</a>.</p>

</div>
</div>

### GetFramePtr() {#a7d2780f625a6691e866aa0a34556fc3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetFramePtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>Reference <a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a>.</p>

</div>
</div>

### GetGlobalPtr() {#a06c1c614fb8e1240ee98815d6c1ba4f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetGlobalPtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>Reference <a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a>.</p>

</div>
</div>

### GetGPRMoveOp() {#a301ece4a7472f2b8bcf8598a92fb61d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetGPRMoveOp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>Reference <a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a>.</p>

</div>
</div>

### GetNullPtr() {#aa9e3696aa316a1d862931ad0c858e09b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetNullPtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>Reference <a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a>.</p>

</div>
</div>

### GetPtrAddiuOp() {#a656432cd552486086064a5af478c8b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetPtrAddiuOp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>Reference <a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a>.</p>

</div>
</div>

### GetPtrAdduOp() {#abe8ed016793fcba9cb5301e90025840d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetPtrAdduOp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>Reference <a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a>.</p>

</div>
</div>

### GetPtrAndOp() {#a7135f4d7ca1aaadc2f5d2f93c9dbda51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetPtrAndOp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>Reference <a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a>.</p>

</div>
</div>

### GetPtrSubuOp() {#acb0e923f97df02841ea645644c2bc035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetPtrSubuOp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>Reference <a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a>.</p>

</div>
</div>

### GetStackPtr() {#a45acf10e3fa054fb114f5cad80d98bae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetStackPtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>Reference <a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a>.</p>

</div>
</div>

### GetVarArgRegs() {#a20d7e1d4427cdefab35b5bd104f9f523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; MipsABIInfo::GetVarArgRegs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The registers to use for the variable argument list.</p>

<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#ac59352a7ddd52db0dabe853439909dc6">IsN32</a>, <a href="#a0630cff2e64996376ddcaa94211c4eac">IsN64</a>, <a href="#aefb3a7a1d98e9fbb76e87a71aafdbc6d">IsO32</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### GetZeroReg() {#a550835f67b4830bb7c19218e6d6566ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsABIInfo::GetZeroReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>Reference <a href="#a0551766c1aa7fa28012947a1cbd2f0ce">AreGprs64bit</a>.</p>

</div>
</div>

### IsKnown() {#ac4b79202578f3154d255986af2dcbb06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsABIInfo::IsKnown ()</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>References <a href="#ae91e4f8d024c12f832f145949441c3b8">ThisABI</a> and <a href="#a0a7cb81026c8f99a3acb10520e669578a88183b946cc5f0e8c96b2e66e1c74a7e">Unknown</a>.</p>

</div>
</div>

### IsN32() {#ac59352a7ddd52db0dabe853439909dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsABIInfo::IsN32 ()</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>References <a href="#a0a7cb81026c8f99a3acb10520e669578ad71d06768593fa82be8fd84d1f8a33c3">N32</a> and <a href="#ae91e4f8d024c12f832f145949441c3b8">ThisABI</a>.</p>


<p>Referenced by <a href="#a0551766c1aa7fa28012947a1cbd2f0ce">AreGprs64bit</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsreginforecord/#aa84b1e01b55d45024625b88ccccd4772">llvm::MipsRegInfoRecord::EmitMipsOptionRecord</a>, <a href="#aa682266c506cc18c1949775a7886ed08">GetByValArgRegs</a>, <a href="#a5827191810a64527509ddc04472c4a07">GetCalleeAllocdArgSizeInBytes</a>, <a href="#a20d7e1d4427cdefab35b5bd104f9f523">GetVarArgRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#ac02bea8ca73149f8cc190e33553a8dec">llvm::MipsSubtarget::isABI_N32</a>.</p>

</div>
</div>

### IsN64() {#a0630cff2e64996376ddcaa94211c4eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsABIInfo::IsN64 ()</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>References <a href="#a0a7cb81026c8f99a3acb10520e669578a7ac2840a241d00a82aa085fa66622bd1">N64</a> and <a href="#ae91e4f8d024c12f832f145949441c3b8">ThisABI</a>.</p>


<p>Referenced by <a href="#a0551766c1aa7fa28012947a1cbd2f0ce">AreGprs64bit</a>, <a href="#a2a988fc1c2adb8253ffbb3c297a5624c">ArePtrs64bit</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#abc6950c9642cee4a3149ee5e1afbf5fe">llvm::MipsFunctionInfo::createEhDataRegsFI</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsreginforecord/#aa84b1e01b55d45024625b88ccccd4772">llvm::MipsRegInfoRecord::EmitMipsOptionRecord</a>, <a href="#aa682266c506cc18c1949775a7886ed08">GetByValArgRegs</a>, <a href="#a5827191810a64527509ddc04472c4a07">GetCalleeAllocdArgSizeInBytes</a>, <a href="#a1e91c4477e0bd5aeb3623c9deecab93b">GetEhDataReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a233e4dd01a9c98f407775d1061ec5d97">llvm::MipsRegisterInfo::getFrameRegister</a>, <a href="#a20d7e1d4427cdefab35b5bd104f9f523">GetVarArgRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#a4fea8a54127e89dd0e6aec5afba826a1">llvm::MipsSubtarget::isABI_N64</a>.</p>

</div>
</div>

### IsO32() {#aefb3a7a1d98e9fbb76e87a71aafdbc6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsABIInfo::IsO32 ()</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>References <a href="#a0a7cb81026c8f99a3acb10520e669578a9d0dce15ea3c51e2da2071c10d59e896">O32</a> and <a href="#ae91e4f8d024c12f832f145949441c3b8">ThisABI</a>.</p>


<p>Referenced by <a href="#aa682266c506cc18c1949775a7886ed08">GetByValArgRegs</a>, <a href="#a5827191810a64527509ddc04472c4a07">GetCalleeAllocdArgSizeInBytes</a>, <a href="#a20d7e1d4427cdefab35b5bd104f9f523">GetVarArgRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#ab590cd4af22d8898397715814cf3bdd7">llvm::MipsSubtarget::isABI_O32</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ThisABI {#ae91e4f8d024c12f832f145949441c3b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ABI llvm::MipsABIInfo::ThisABI</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>Referenced by <a href="#a083bc49c362923774e17b4930a8476b9">GetEnumValue</a>, <a href="#ac4b79202578f3154d255986af2dcbb06">IsKnown</a>, <a href="#ac59352a7ddd52db0dabe853439909dc6">IsN32</a>, <a href="#a0630cff2e64996376ddcaa94211c4eac">IsN64</a>, <a href="#aefb3a7a1d98e9fbb76e87a71aafdbc6d">IsO32</a>, <a href="#a14c61ea10fcd6e85592b6c02eb3699a7">MipsABIInfo</a> and <a href="#a6512d0f8b12785db4500487e4e76551f">operator&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### computeTargetABI() {#a87e5ac48dc2d9e13a26e34521926876a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsABIInfo MipsABIInfo::computeTargetABI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a14c61ea10fcd6e85592b6c02eb3699a7">MipsABIInfo</a>, <a href="#a49f6189dad91aa91e65bb954b0a4cfab">N32</a>, <a href="#a5e17d38855b4505b183e0a3d75040c81">N64</a>, <a href="#a11526f61f6c73d495cd72ff6bd688dfd">O32</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetmachine-cpp/#adb29b487708f0dc2a940345b68649270">computeDataLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af07717de265cdc07e01ca26be29c1a60">llvm::createMipsAsmBackend</a> and <a href="/web-llvm/docs/api/classes/llvm/mipselfmcasminfo/#a8708ca800840e855dc74da7c335cae33">llvm::MipsELFMCAsmInfo::MipsELFMCAsmInfo</a>.</p>

</div>
</div>

### N32() {#a49f6189dad91aa91e65bb954b0a4cfab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsABIInfo llvm::MipsABIInfo::N32 ()</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>References <a href="#a14c61ea10fcd6e85592b6c02eb3699a7">MipsABIInfo</a> and <a href="#a0a7cb81026c8f99a3acb10520e669578ad71d06768593fa82be8fd84d1f8a33c3">N32</a>.</p>


<p>Referenced by <a href="#a87e5ac48dc2d9e13a26e34521926876a">computeTargetABI</a>.</p>

</div>
</div>

### N64() {#a5e17d38855b4505b183e0a3d75040c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsABIInfo llvm::MipsABIInfo::N64 ()</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>References <a href="#a14c61ea10fcd6e85592b6c02eb3699a7">MipsABIInfo</a> and <a href="#a0a7cb81026c8f99a3acb10520e669578a7ac2840a241d00a82aa085fa66622bd1">N64</a>.</p>


<p>Referenced by <a href="#a87e5ac48dc2d9e13a26e34521926876a">computeTargetABI</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a17d3b4679a104b0852f1679b817d2070">llvm::MipsTargetELFStreamer::MipsTargetELFStreamer</a>.</p>

</div>
</div>

### O32() {#a11526f61f6c73d495cd72ff6bd688dfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsABIInfo llvm::MipsABIInfo::O32 ()</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>References <a href="#a14c61ea10fcd6e85592b6c02eb3699a7">MipsABIInfo</a> and <a href="#a0a7cb81026c8f99a3acb10520e669578a9d0dce15ea3c51e2da2071c10d59e896">O32</a>.</p>


<p>Referenced by <a href="#a87e5ac48dc2d9e13a26e34521926876a">computeTargetABI</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a17d3b4679a104b0852f1679b817d2070">llvm::MipsTargetELFStreamer::MipsTargetELFStreamer</a>.</p>

</div>
</div>

### Unknown() {#a92db0d6559f297c89c2ebc01819e33fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsABIInfo llvm::MipsABIInfo::Unknown ()</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a>.</p>


<p>References <a href="#a14c61ea10fcd6e85592b6c02eb3699a7">MipsABIInfo</a> and <a href="#a0a7cb81026c8f99a3acb10520e669578a88183b946cc5f0e8c96b2e66e1c74a7e">Unknown</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-cpp">MipsABIInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MipsABIInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
